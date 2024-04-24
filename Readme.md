![Header](logo.png)

## Latar Belakang

New York Taxi and Limousine Commision(TLC) adalah badan pemerintahan yang bertanggung jawab atas regulasi dan pengawasan layanan taksi dan limusin di New York City . TLC didirikan pada tahun 1971 sebagai respon terhadap perubahan dalam industri taksi dan limusin di kota New York City tersebut.

# Pernyataan Masalah

Stackholder yang bersangkutan yaitu dari vendor manajer VeriFone Inc.

Stackholder ingin melakukan peningkatan profit dari bisnis taxinya dengan mengetahui tampat-tampat yang berpotensi ramai penumpang. strategi ini sangat penting bagi vendor dikarenakan akan meningkatkan profit dari sebuah perusahan VeriFone Inc.

saya sebagai seorang data analyst, akan menjawab pertanyaan berikut :

<b>Bagaimana cara meningkatkan profit perusahaan dan meningkatkan efektifitas lokasi penjemputan yang akurat ?</b>

## Dataset

Untuk menjawab peryataan permasalah diatas, kami akan menganalisa data NYCTLCTripRecord yang dikumpulkan oleh perusahan. Data dapat diakses <a href='https://drive.google.com/drive/folders/1NYHIL-RgVPW-HONz4pdzlcbIChF-c37N'>disini.</a>

Data set ini berisikan informasi terkait trip perjalanan dari setiap taksi yang ada di New York City. Ada 17 kolom didalam data set NYCTLCTripRecord, yaitu seperti berikut :

- VendorID = Kode perusahan/ vendor yang berkerja sama dengan TLC.\
   1 = Creative Mobile Technologies, LLC.  
   2 = VeriFone Inc.

- lpep_pickup_datetime = Tanggal dan waktu penjemputan penumpang(ketika taximer dinyalakan).

- lpep_dropoff_datetime = Tanggal dan waktu menurunkan penumpang (ketika taximer dimatikan) .

- Passenger_count = Jumlah penumpang didalam kendaraan.

- Trip_distance = Jarak tempuh perjalanan dalam mill dihitung menggunakan taximeter selama perjalanan.

- PULocationID = Lokasi penjemputan.

- DOLocationID = Lokasi penurunan.

- RateCodeID = kode tarif akhir bagi penumpang.\
   1 = Standard rate (tarif standar)\
   2 = JFK(kode tarif perjalanan menuju bandara John ef khanedy)\
   3 = Newark (kode tarif perjalanan menuju bandara Newrak liberty)\
   4 = Nassau or Westchester (kode tarif perjalanan menuju Nassau dan Westchester)\
   5 = Negotiated fare (tarif yang ditawar)\
   6 = Group ride(tarif perjalanan kelompok)

- Store_and_fwd_flag = This flag indicates whether the trip record was held in the vehicle memory before sending to the vendor,aka “store and forward,” because the vehicle did not have a connection to the server.\
   Y = (catatan perjalanan disimpan diperangkat memory kendaran kemudian dikirim ke server)\
   N = (catatan perjalann dikirim langsung keserver tampa disimpan di perangkat memory)

- Fare_Amount = Jumlah tarif penumpang yang dihitung berdasarkan waktu dan jarak tempuh serta pajak MTA sebesar 0.50 dolar dan 1 dolar pada jam sibuk dan jam malam.

- MTA_tax = Biyaya tambahan yang dikenakan untuk mendukung layanan transportasi umum didaerah metropolitan New York City, biyaya ini dikenakan saat perjalanan menggunakan taxi di New York City.

- Tip_amount = Jumlah tips yang diberikan penumpang.

- Tolls_amount = Jumlah biyaya masuk toll yang harus dibayar oleh penumpang.

- Improvement_surcharge = Biyaya tambahan sebesar 0.30 dolar untuk pelanggan yang ingin pesan secara langsung dijalan tampa memesan terlebih dahulu.

- Total_amount = Jumlah biyaya yang dikenakan penumpang selama perjalanan taxi (tidak termasuk tips).

- Paymen_type = Tipe pembayaran.\
   1 = Credit_card\
   2 = Cash\
   3 = No charge\
   4 = Dispute\
   5 = Unknow\
   6 = Voided trip
- Trip_type =
  1 = Tipe penumpang secara langsung dijalan(street-hail) seperti melambaikan tangan dijalan tampa memesan melalui kantor pusat.
  2 = Tipe penumpang terlebih dahulu memesan melalui kantor pusat (dispatch) dan kantor pusat akan mencarikan taxi terdekat.

berikut 5 data baris pertama sebagai berikut :

## Installation

To get this project, you can clone it by running the following code:

    https://github.com/muhammadtofikhidayat/Toko-Berkah-Jaya

## Project Organization

The directory structure of Tokoh Berkah Jaya project looks like this:

      |── Readme.md
      ├── data
      │   └── NYCTLCTripRecord.csv
      ├── requirements.txt
      ├── src
          └── script.ipynb

## Contribute

If you'd like to contribute to Toko Berkah Jaya Apps, check out https://github.com/muhammadtofikhidayat/Toko-Berkah-Jaya, or feel free to contact me.
