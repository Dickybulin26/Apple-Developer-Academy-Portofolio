## DAFTAR ISI

```
DAFTAR ISI.............................................................................................................i
DAFTAR GAMBAR...............................................................................................ii
DAFTAR TABEL...................................................................................................iii
```
- BAB 1. PENDAHULUAN...................................................................................... DAFTAR LAMPIRAN...........................................................................................iv
   - 1.1. Latar Belakang............................................................................................
   - 1.2. Rumusan Masalah.......................................................................................
   - 1.3. Tujuan.........................................................................................................
   - 1.4. Luaran Kegiatan..........................................................................................
   - 1.5. Tema PKM (Kemandirian Pangan, Energi, dan Air)..................................
   - 1.6. Manfaat.......................................................................................................
- BAB 2. TINJAUAN PUSTAKA..............................................................................
   - 2.1. Tanaman Cabai............................................................................................
   - 2.2. Deteksi Hama Pada Tanaman......................................................................
   - 2.3. Computer Vision.........................................................................................
   - 2.4. Artificial Intelligence..................................................................................
   - 2.5. Internet of Thing (IoT)................................................................................
   - 2.6. Sistem Terintegrasi dengan Aplikasi Mobile..............................................
   - 2.7. Teknologi Yang Digunakan.........................................................................
   - 2.8. State of the Art............................................................................................
   - 2.9. Kemutakhiran IPTEK yang Diadopsi.........................................................
   - 2.10. Potensi Program Usulan............................................................................
- BAB 3. TAHAP PELAKSANAAN.........................................................................
   - 3.1.Identifikasi dan Analisis Masalah................................................................
   - 3.2.Studi Pustaka................................................................................................
   - 3.3.Pengembangan Prototype.............................................................................
- BAB 4. BIAYA DAN JADWAL KEGIATAN.........................................................
   - 4.1. Anggaran Biaya...........................................................................................
   - 4.2. Jadwal Kegiatan..........................................................................................
- DAFTAR PUSTAKA.............................................................................................
- LAMPIRAN...........................................................................................................
   - Lampiran 1. Biodata Ketua dan Anggota, serta Dosen Pendamping...............
   - Lampiran 2. Justifikasi Anggaran Kegiatan.....................................................
   - Lampiran 3. Susunan Tim Pengusul dan Pembagian Tugas............................
   - Lampiran 4. Surat Pernyataan Ketua Tim Pengusul........................................
   - Lampiran 5. Gambaran Teknologi yang akan Dikembangkan.........................
   - atau yang lainnya) dengan indeks similaritas maksimum 25%....................... Lampiran 6. Hasil Uji Periksa Similaritas Proposal ( Turnitin, iThenticate


#### DAFTAR GAMBAR

Gambar 3.1. Tahap Pelaksanaan.............................................................................. 7
Gambar L5.1. Gambaran Alur Kerja Sistem.......................................................... 23
Gambar L5.2. Tampak Bawah (Dimensi: 15x10x8cm)......................................... 23
Gambar L5.3. Tampak Samping (Dimensi: 15x10x8cm)...................................... 23
Gambar L5.4 Prototype (Dimensi : 15x10x8cm)................................................... 24
Gambar L.5.5 Flowchart Ecotra............................................................................. 24

```
ii
```

#### DAFTAR TABEL

Tabel 2.1. Teknologi Yang Digunakan..................................................................... 4
Tabel 2.2. State of the Art........................................................................................ 5
Tabel 2.3. Kemutakhiran IPTEK yang Diadopsi...................................................... 6
Tabel 4.1. Rekapitulasi Rencana Anggaran Biaya................................................... 9
Tabel 4.2. Jadwal Kegiatan...................................................................................... 9

```
iii
```

#### DAFTAR LAMPIRAN

Lampiran 1. Biodata Ketua dan Anggota, serta Dosen Pendamping..................... 11
Lampiran 2. Justifikasi Anggaran Kegiatan........................................................... 18
Lampiran 3. Susunan Tim Pengusul dan Pembagian Tugas.................................. 20
Lampiran 4. Surat Pernyataan Ketua Tim Pengusul.............................................. 21
Lampiran 5. Gambaran Teknologi yang akan Dikembangkan............................... 22
Lampiran 6. Hasil Uji Periksa Similaritas Proposal ( Turnitin, iThenticate atau
yang lainnya) dengan indeks similaritas maksimum 25%..................................... 26

```
iv
```

#### BAB 1. PENDAHULUAN

### 1.1. Latar Belakang............................................................................................

Komoditas cabai merah ( _Capsicum annuum L._ ) berstatus strategis dalam
menopang ketahanan pangan dan ekonomi Indonesia (Witanti, Arie Anggara and
Melina, 2024). Sayangnya, produksi cabai rentan berfluktuasi ekstrem akibat
cuaca hingga memicu inflasi nasional (Wahyuni, Satriani and Mandamdari, 2024).
Kegagalan panen umumnya dipicu oleh hama dan penyakit (antraknosa, _Thrips_ ,
_Gemini_ , serta kutu daun) yang dapat merusak lahan hingga 100% jika pengawasan
manual terlambat dilakukan (Arsi, Anafiotika, Suparman, Fauziah, Zhafirah,
Margareta, Rani, Wardani dan Yusniawan., 2023). Selama ini, penanganan hama
masih didominasi metode _blanket spraying_ (penyemprotan menyeluruh) yang
boros dan mencemari ekosistem dengan residu kimiawi (Jamin, Auliani, Rusli dan
Pramono, 2024). Ancaman krisis agrikultur ini juga diperparah oleh fenomena
penuaan petani ( _aging farmers_ ) dan menurunnya minat generasi muda akibat
stigma pekerjaan yang melelahkan (Marpaung and Bangun, 2023).
Inovasi ini dikembangkan berdasarkan riset terdahulu dari Universitas
Gunadarma (Islamy and Wisudawati, 2023) mengenai sistem _smart garden_ cabai
berbasis _Internet of Things_ (IoT) yang masih statis ( _rule-based_ ) dan hanya
mengandalkan notifikasi satu arah via Telegram. Sebagai bentuk penyempurnaan,
diusulkanlah ECOTRA ( _Ecosystem Optimization for Chili Cultivation Through AI
and IoT Automation_ ) dengan empat pilar kecerdasan prediktif: (1) aktuasi
_automatic sprayer_ berbasis _Computer Vision_ ( _MobileNetV2_ ) untuk deteksi
penyakit daun cabai secara spesifik (Fatmawati, Podungge and Rahman, 2026);
(2) pemantauan kualitas hara tanah _real-time_ via IoT (Fajriyati, Ajeng Mayang
Kurniaviep Sugeng, and Muhammad Adli Rizqulloh, 2025); (3) laporan performa
musiman; serta (4) asisten _Chatbot_ interaktif berbasis pemrosesan bahasa alami
pada aplikasi _mobile_ untuk memandu keputusan petani awam (Wirayudha,
Nurhasanah, and Andriyana, 2025).
Fase final yang ingin dicapai dalam program PKM-KC ini adalah
terwujudnya purwarupa fungsional (perangkat keras _edge computing_ dan aplikasi
lunak) yang siap diuji coba. Prototipe ini tidak hanya menjamin efisiensi input
pestisida guna mencegah gagal panen secara terukur, tetapi juga diharapkan
mampu meningkatkan daya tarik pemuda untuk terjun ke sektor _smart farming_
(Halawa, 2024).

### 1.2. Rumusan Masalah.......................................................................................

Berdasarkan uraian latar belakang di atas, maka rumusan masalah di
dalam PKM-KC ini adalah sebagai berikut:

1. Bagaimana pembuatan purwarupa ECOTRA berbasis IoT dan _Computer Vision_
dapat menangani mitigasi hama secara otomatis serta menjaga kondisi ideal tanah
pada perkebunan cabai?


2. Bagaimana penerapan protokol komunikasi data dalam menghubungkan
purwarupa ECOTRA dengan aplikasi mobile untuk memantau performa
perkebunan secara _real-time_?
3. Bagaimana pemanfaatan kecerdasan buatan dalam aplikasi ECOTRA untuk
menyusun laporan performa musiman dan menyediakan layanan asisten _chatbot_
bagi petani?

### 1.3. Tujuan.........................................................................................................

Berdasarkan rumusan masalah yang telah disebutkan sebelumnya,
sehingga dapat diketahui tujuan usulan program ini yaitu sebagai berikut:

1. Dapat memahami proses pembuatan purwarupa ECOTRA berbasis IoT dan
_Computer Vision_ untuk memitigasi serangan hama secara otomatis serta menjaga
kondisi ideal tanah pada perkebunan cabai.
2. Dapat mengetahui penerapan protokol komunikasi data dalam integrasi
purwarupa ECOTRA dengan aplikasi mobile untuk memantau kondisi dan
performa perkebunan secara _real-time_.
3. Mengetahui pemanfaatan kecerdasan buatan pada aplikasi mobile ECOTRA
untuk menghasilkan laporan performa perkebunan musiman dan layanan asisten
_chatbot_ sebagai media interaksi data.

### 1.4. Luaran Kegiatan..........................................................................................

```
Luaran kegiatan PKM-KC dari usulan ini berupa:
```
1. Laporan Kemajuan; berupa dokumen formal yang mencatat perkembangan
    proses pendalaman masalah, perancangan, hingga pembuatan prototipe
    ECOTRA selama periode program berjalan.
2. Laporan Akhir; berupa dokumen hasil akhir pelaksanaan program yang
    memuat data pengujian fungsionalitas sistem, analisis keberhasilan, serta
    kesimpulan dari implementasi teknologi ECOTRA.
3. Prototipe Produk Fungsional; berupa perangkat fisik modular ECOTRA
    yang dilengkapi dengan sistem _automatic sprayer_ , sensor kualitas tanah
    terintegrasi IoT, serta aplikasi _mobile_ yang memiliki fitur laporan musiman
    dan asisten _chatbot_ berbasis kecerdasan buatan. Biaya realisasi prototipe
    disesuaikan dengan batasan pendanaan yang disetujui.
4. Akun Media Sosial ECOTRA.PKMKC; sebagai sarana publikasi, edukasi,
    dan dokumentasi proses pengembangan produk guna meningkatkan
    _awareness_ masyarakat terhadap teknologi pertanian cerdas.
5. Draf Hak Kekayaan Intelektual (HKI); berupa draf perlindungan Hak
    Cipta Program Komputer untuk algoritma deteksi hama dan sistem
    manajemen data ECOTRA (sebagai luaran tambahan).

### 1.5. Tema PKM (Kemandirian Pangan, Energi, dan Air)..................................

```
ECOTRA termasuk pada poin ke-1 dari 10 tematik yang menjadi
konsentrasi Belmawa pada tahun 2026 mengenai Kemandirian Pangan,
Energi, dan Air. Hal ini dibuktikan dengan tujuan utama dari ECOTRA,
yaitu memitigasi risiko gagal panen pada perkebunan cabai akibat
```

```
serangan hama dan menjaga kondisi ideal tanah secara presisi
menggunakan integrasi Internet of Things (IoT) dan Artificial Intelligence
(AI) guna menopang ketahanan dan kemandirian pangan nasional.
```
### 1.6. Manfaat.......................................................................................................

1. Bagi Tim Pengusul: Mengakselerasi kompetensi mahasiswa dalam
    merancang teknologi terapan ( _applied technology_ ) serta menumbuhkan
    jiwa wirausaha berbasis integrasi IoT dan AI ( _technopreneurship_ ).
2. Bagi Masyarakat (Petani dan Konsumen): Memitigasi gagal panen dan
    menekan biaya pestisida bagi petani, sekaligus menjamin ketersediaan
    cabai yang sehat dan minim residu kimia bagi konsumen.
3. Bagi Pemerintah dan Instansi Terkait: Mendukung ketahanan pangan dan
    stabilitas inflasi nasional, serta menyediakan ekosistem data riil sebagai
    landasan perumusan kebijakan pertanian ( _data-driven policy_ ).
4. Bagi Perkembangan IPTEK: Memperkaya literatur _Smart Farming_ di
    Indonesia melalui inovasi integrasi _Computer Vision_ (CNN) untuk deteksi
    hama presisi dan asisten _chatbot_ (NLP) khusus agrikultur.

## BAB 2. TINJAUAN PUSTAKA..............................................................................

### 2.1. Tanaman Cabai............................................................................................

Tanaman cabai merupakan komoditas hortikultura bernilai ekonomi tinggi
yang sensitif terhadap perubahan lingkungan seperti suhu, kelembapan, dan
kondisi tanah Oleh karena itu, diperlukan sistem pemantauan yang mampu
menjaga kondisi optimal tanaman (Wahyuni, Satriani and Mandamdari, 2024).

### 2.2. Deteksi Hama Pada Tanaman......................................................................

Deteksi hama secara manual memiliki keterbatasan dalam kecepatan dan
akurasi sehingga berpotensi menyebabkan keterlambatan penanganan
Pemanfaatan teknologi digital memungkinkan proses deteksi dilakukan secara
otomatis dan lebih akurat (Arsi, Anafiotika, Suparman, Fauziah, Zhafirah,
Margareta, Rani, Wardani dan Yusniawan., 2023).

### 2.3. Computer Vision.........................................................................................

Computer Vision merupakan teknologi yang memungkinkan sistem
mengenali objek dan pola dari citra digital, seperti perubahan warna daun atau
kerusakan akibat hama (Fatmawati, Podungge and Rahman, 2026).

### 2.4. Artificial Intelligence..................................................................................

Artificial Intelligence (AI) digunakan untuk menganalisis data dan
mengambil keputusan secara otomatis. Salah satu metode yang umum digunakan
adalah Convolutional Neural Network (CNN) yang mampu mengenali pola visual
pada citra tanaman (Wirayudha, Nurhasanah, and Andriyana, 2025).

### 2.5. Internet of Thing (IoT)................................................................................

IoT memungkinkan perangkat sensor mengirimkan data lingkungan secara
real-time ke sistem pusat untuk diproses dan dianalisis (Fajriyati, Ajeng Mayang
Kurniaviep Sugeng, and Muhammad Adli Rizqulloh, 2025).


### 2.6. Sistem Terintegrasi dengan Aplikasi Mobile..............................................

Aplikasi mobile digunakan sebagai antarmuka untuk menampilkan data,
memberikan notifikasi, serta membantu pengambilan keputusan berdasarkan hasil
analisis sistem (Islamy and Wisudawati, 2023).

### 2.7. Teknologi Yang Digunakan.........................................................................

```
Tabel 2.1. Teknologi Yang Digunakan
No Teknologi Kegunaan
```
```
1 Google AntiGravity
```
```
Digunakan sebagai text editor yang terintegrasi
dengan teknologi kecerdasan buatan dalam
proses pengembangan aplikasi.
2 Figma
Dimanfaatkan sebagai media perancangan dan
pembuatan prototipe desain aplikasi.
```
```
3 Expo / Expo Go
Berfungsi untuk melakukan pengujian serta
pratinjau aplikasi mobile berbasis React Native.
4 Typescript
Digunakan sebagai bahasa pendukung dalam
pengembangan aplikasi mobile.
```
```
5 React Native
Berperan sebagai framework utama dalam
sistem pengembangan aplikasi mobile.
```
```
6 Python
```
```
Digunakan sebagai bahasa pemrograman utama
dalam pengembangan sistem kecerdasan
buatan.
7
Google Gemini
LLM
```
```
Dimanfaatkan untuk menyediakan layanan
asisten virtual bagi pengguna aplikasi.
```
```
8
Orange PI Zero 3
RAM 4GB
```
```
Berfungsi sebagai perangkat komputasi untuk
pemrosesan data dan menjalankan sistem AI.
```
```
9
```
```
Camera Orange PI
OV5640 Wide
Angle Sensor 5MP
```
```
Digunakan untuk menangkap dan memperoleh
citra tanaman.
```
```
10 Sensor DS18B
Berfungsi untuk mengukur suhu tanah pada
tanaman.
11
Sensor Kelembapan
Tanah
```
```
Berfungsi untuk mengukur kelembaban tanah
pada tanaman
```
```
12
DC Motor Water
Pump R
```
```
Memompa Cairan Pestisida dan
menyemprotkannya ke Tanaman
13
Ublox NEO-6M
GPS Module
```
```
Digunakan untuk menentukan koordinat lokasi
perangkat sekaligus merekam data area lahan.
```
```
14 Nozzle Mist Sprayer
Memungkinkan proses penyemprotan pestisida
dilakukan secara otomatis.
15 Firebase
Digunakan sebagai sistem penyimpanan basis
data yang berjalan secara real-time.
```

### 2.8. State of the Art............................................................................................

```
2.2. State of the Art
```
```
No Nama Aplikasi Pengembang Keterangan Tahun
```
#### 1

```
Sistem
Monitoring
Smart Garden
Tanaman Cabai
Berbasis IoT
Menggunakan
Protokol MQTT,
Node Red, dan
Telegram Bot
```
```
Irfan Islamy,
Lulu
Mawaddah
Wisudawati
```
```
Fitur: Memonitor Suhu
dan Kelembaban tanah
(ESP8266), Penyiraman
otomatis, serta notifikasi
via Telegram dan
Node-Red.
```
```
Kekurangan: Belum
dilengkapi A.I untuk
analisis kondisi tanaman
yang lebih mendalam
```
#### 2023

#### 2

```
Sistem Smart
Farming Cabai
Berbasis IoT
dan
Node-RED
```
```
Fajriyati,
Sugeng,
Rizqulloh
```
```
Fitur: Monitoring
lingkungan tanaman
berbasis sensor dan
rule-based system.
```
```
Kekurangan: Keputusan
masih berbasis aturan
statis, belum adaptif dan
tidak menggunakan
Computer Vision
```
#### 2025

#### 3

```
Klasifikasi
Penyakit
Tanaman Cabai
Menggunakan
CNN MobileNet
v
```
```
Fatmawati,
Podungge,
Rahman
```
```
Fitur: Deteksi penyakit
daun cabai menggunakan
CNN (MobileNetV2)
dengan akurasi tinggi.
```
```
Kekurangan: Tidak
terintegrasi dengan sistem
IoT dan belum ada
aktuator (sprayer
otomatis).
```
#### 2026

```
No Teknologi Kegunaan
```
```
16
TensorFlow / CNN
model
```
```
Digunakan sebagai model kecerdasan buatan
untuk mendeteksi hama pada tanaman cabai.
```

### 2.9. Kemutakhiran IPTEK yang Diadopsi.........................................................

```
Tabel 2.3. Kemutakhiran IPTEK yang Diadopsi
Metode/Algoritma Data Input Perangkat Hasil
```
```
Sistem IoT
(Non-AI)
```
```
Suhu dan
kelembaban
tanah
```
```
Orange Pi 3 Zero,
MQTT,
DS18B20,
Moisture Soil
```
```
Monitoring
kondisi tanah
pada tanaman
secara real-time
```
```
CNN
(MobileNetV2)
```
```
Citra daun cabai Camera OV
dan Orange Pi 3
Zero
```
```
Klasifikasi
hama/penyakit
otomatis
```
```
ECOTRA LLM
ChatBot
```
```
Data sensor dan
citra tanaman
```
```
Orange Pi 3 Zero,
Sensor IoT,
Kamera, Sprayer
Pestisida
```
Membantu petani
dalam membaca
hasil data serta
pengambilan
keputusan dengan
cepat
Kemutakhiran IPTEK ECOTRA terletak pada integrasi Internet of Things
(IoT) dan Artificial Intelligence (AI) berbasis komputasi lokal ( _Edge Computing_ ).
Sistem ini mengadopsi algoritma Computer Vision (MobileNetV2) untuk
mendeteksi penyakit daun cabai secara _real-time_ , yang secara instan memicu
aktuasi penyemprotan otomatis ( _spot-spraying_ ) secara presisi. Sebagai
penyempurna, ECOTRA mengintegrasikan Natural Language Processing (NLP)
pada aplikasi _mobile_ berupa _chatbot_ interaktif untuk menerjemahkan data sensorik
menjadi rekomendasi agrikultur yang mudah dipahami oleh petani awam.

### 2.10. Potensi Program Usulan............................................................................

Program ECOTRA berpotensi menghasilkan purwarupa pertanian presisi
( _precision agriculture_ ) fungsional yang efektif memitigasi gagal panen dan
menekan pemborosan pestisida. Secara keilmuan, integrasi multidisiplin antara
_Computer Vision_ , sensor IoT, dan NLP ini akan memperkaya literatur Smart
Farming di Indonesia. Inovasi ekosistem cerdas ini diharapkan menjadi referensi
empiris bagi riset agrikultur masa depan, sekaligus memicu kembali ketertarikan
generasi muda terhadap sektor pertanian modern.

```
BAB 3. TAHAP PELAKSANAAN
```

```
Gambar 3.1. Tahap Pelaksanaan
```
### 3.1.Identifikasi dan Analisis Masalah................................................................

Tahap awal difokuskan pada observasi dan wawancara mengenai tingginya
risiko gagal panen cabai akibat serangan hama (kutu daun, _Thrips_ , ulat, lalat buah)
dan penyakit (layu fusarium, virus kuning, busuk buah) (Arsi, Anafiotika,
Suparman, Fauziah, Zhafirah, Margareta, Rani, Wardani dan Yusniawan, 2023).
Selama ini, penanganan kendala tersebut masih mengandalkan metode
penyemprotan buta ( _blanket spraying_ ) ke seluruh lahan yang memicu pemborosan
pestisida dan pencemaran lingkungan. Sehingga solusi dari permasalahan tersebut
dapat dilakukan dengan inovasi ECOTRA berbasis _Internet of Things_ (IoT) dan
_Artificial Intelligence_ (AI) untuk mendeteksi dan mitigasi hama yang presisi
secara otomatis.

### 3.2.Studi Pustaka................................................................................................

Pengumpulan data sekunder difokuskan pada kajian literatur mutakhir
terkait penerapan IoT, Kecerdasan Buatan, dan _Computer Vision_ (CNN) dalam
agrikultur (Fajriyati, Ajeng Mayang Kurniaviep Sugeng, and Muhammad Adli
Rizqulloh, 2025). Studi komparatif terhadap sistem _smart farming_ terdahulu juga
dilakukan secara kritis untuk menentukan arsitektur komputasi dan teknologi
komponen yang paling optimal bagi ECOTRA.

### 3.3.Pengembangan Prototype.............................................................................

Tahap ini merupakan pembuatan cetak biru ( _blueprint_ ) arsitektur dan
eksekusi langsung purwarupa ECOTRA yang mengintegrasikan perangkat keras,
perangkat lunak, dan kecerdasan buatan. Pada pe ngembangan perangkat keras
(IoT), sistem menggunakan Orange Pi Zero 3 sebagai pusat komputasi lokal


( _Edge Computing_ ). Sebagai _input_ , digunakan kamera OV5640 5MP untuk
mengakuisisi citra tanaman, sensor DS18B20 untuk mendeteksi suhu, sensor
kelembapan tanah, serta modul Ublox NEO-6M GPS untuk pencatatan koordinat
lahan. Sebagai _output_ aktuasi, sistem menggunakan _relay_ yang terhubung ke
pompa air R580 dan _nozzle mist sprayer_. _Nozzle_ dirancang secara statis di atas
pot, sehingga jika hama terdeteksi, penyemprotan pestisida dilakukan secara
menyeluruh pada satu tanaman cabai tersebut untuk memutus penyebaran, tanpa
harus melakukan penyemprotan ke seluruh kebun. Pada sisi perangkat lunak,
desain antarmuka aplikasi dirancang menggunakan Figma. Aplikasi _mobile_
dibangun menggunakan _framework_ React Native dengan bahasa pemrograman
TypeScript, serta diuji menggunakan Expo. Penulisan kode dibantu oleh _text
editor_ Google AntiGravity. Sementara itu, untuk pengembangan _Artificial
Intelligence_ (AI), model deteksi hama dilatih menggunakan bahasa Python dan
algoritma TensorFlow (model CNN) berbasis pemrosesan _cloud_. Sistem juga
mengintegrasikan _Application Programming Interface_ (API) dari Google Gemini
LLM untuk menyediakan layanan asisten virtual ( _chatbot_ ) interaktif pada aplikasi.
3.4. Integrasi Sistem
Tahap ini merupakan proses sinkronisasi antara perangkat keras,
komputasi awan ( _cloud_ ), dan perangkat lunak. Data dari sensor dan kamera
Orange Pi dikirim ke _cloud_ menggunakan protokol telemetri MQTT dan HTTP.
Data sensor disimpan di Firebase sebagai _database real-time_ , sementara citra
dianalisis oleh AI. Hasil pemrosesan seperti dasbor pemantauan, status pompa,
dan notifikasi peringatan hama kemudian disinkronisasikan secara _real-time_ ke
aplikasi _mobile_ ECOTRA.
3.5.Pengujian
Pengujian dilakukan untuk mengevaluasi performa sistem dalam
mendeteksi hama serta merespons kondisi lingkungan. Parameter yang diuji
meliputi akurasi model AI, kecepatan respon sistem, serta kestabilan komunikasi
data antara perangkat dan aplikasi.
3.6.Evaluasi
Evaluasi dilakukan berdasarkan hasil pengujian untuk mengidentifikasi
kekurangan sistem. Perbaikan dilakukan pada model AI, konfigurasi sensor, serta
tampilan aplikasi guna meningkatkan performa dan keandalan sistem.

BAB 4. BIAYA DAN JADWAL KEGIATAN
4.1. Anggaran Biaya
Tabel 4.1. Rekapitulasi Rencana Anggaran Biaya
No Jenis Pengeluaran Sumber Dana Besaran Dana (Rp)

1 Bahan Habis Pakai

```
Belmawa 4.150.
Perguruan Tinggi 175.
Instansi Lain (jika ada) 0
```
2 Sewa dan Jasa

```
Belmawa 1.600.
Perguruan Tinggi 225.
Instansi Lain (jika ada) 0
```
3 Transportasi Lokal

```
Belmawa 1.280.
Perguruan Tinggi 500.
```

```
No Jenis Pengeluaran Sumber Dana Besaran Dana (Rp)
Instansi Lain (jika ada) 0
```
4 Lain-lain

Belmawa 970.
Perguruan Tinggi 1.300.
Instansi Lain (jika ada) 0
Jumlah 9.300.
Rekap Sumber Dana Belmawa 8.000.
Perguruan Tinggi 1.300.
Instansi Lain (jika ada) 0
Jumlah 9.300.

### 4.2. Jadwal Kegiatan..........................................................................................

```
Tabel 4.2. Jadwal Kegiatan
```
```
No Jenis Kegiatan
Bulan
Penanggung Jawab
1 2 3 4
```
```
1 Persiapan
Farell Rhezky
Alvianto
2
Identifikasi dan
Analisis Masalah
```
```
Dicky Asqaeliany
Ibnul Hakim
```
```
3
Mempelajari Studi
Pustaka
```
```
Dicky Asqaeliany
Ibnul Hakim
4 Pembuatan Konsep
Farell Rhezky
Alvianto
```
```
5
Pembuatan Desain
Produk
```
```
Steven Joshua
Widjaya
6 Pembuatan Prototipe
Rafie Restu
Ramadhani
```
```
7 Pengujian dan Analisis
Rafie Restu
Ramadhani
8 Evaluasi
Farell Rhezky
Alvianto
```
```
9 Penyusunan Laporan
Chivo Hifdz Addien
Kurniawan
```

## DAFTAR PUSTAKA.............................................................................................

Anafiotika, R., Fauziah, Z., Zhafirah, A.M., Margareta, G., Rani, F.D., Wardani,
A. and Yusniawan, M.T. (2023) ‘Intensitas Serangan Hama & Penyakit
Cabai Rawit di Provinsi Sumatera Selatan’. Available
At:https://semnas.bpfp-unib.com/index.php/SENATASI/article/view/224/
4.
Fajriyati, A.L., Ajeng Mayang Kurniaviep Sugeng, and Muhammad Adli
Rizqulloh (2025) “Sistem Smart Farming Cabai dengan Rule-Based System
Node-RED dan Berbasis Internet of Things,” Jurnal Teknologi, 18(1), pp.
38–46. Available at: https://doi.org/10.34151/jurtek.v18i1.5229.
Fatmawati, I., Podungge, E.S. and Rahman, A. (2026) “Classification of diseases
in chili plants using the convolutional neural network method with
MobileNetV2architecture,”14(3). Available at:
https://doi.org/https://doi.org/10.35335/mandiri.v14i3.476.
Halawa, D.N. (2024) ‘Peran Teknologi Pertanian Cerdas (Smart Farming) untuk
Generasi Pertanian Indonesia’, _JURNAL KRIDATAMA SAINS DAN
TEKNOLOGI,_ 6(02), pp. 502–512. doi:
https://doi.org/10.53863/kst.v6i02.1226.
Islamy, I. and Wisudawati, L.M. (2023) “Sistem Monitoring Smart Garden
Tanaman Cabai Berbasis IoT Menggunakan Protokol MQTT, Node Red,
dan Telegram Bot,” Jurnal Teknotan, 17(3), p. 197. Available at:
https://doi.org/10.24198/jt.vol17n3.6.
Jamin, Rusli, Aulian and Pramono (2024) “Penggunaan Pestisida dalam
Pertanian: Resiko Kesehatan dan Alternatif Ramah Lingkungan.” Available
at: https://doi.org/https://doi.org/10.56338/jks.v7i11.6342.
Marpaung, N. and Bangun, I.C. (2023) “Pentingnya Regenerasi Petani dalam
Modernisasi Pertanian,” Jurnal Kajian Agraria dan Kedaulatan Pangan
(JKAKP),2(2),pp.27–33.Available At:
https://doi.org/10.32734/jkakp.v2i2.14195.
Wahyuni, T.S., Satriani, R. and Mandamdari, A.N. (2024) “Pengaruh Fluktuasi
Harga Cabai Rawit Merah Terhadap Inflasi di Kabupaten Banyumas,”
Mimbar Agribisnis : Jurnal Pemikiran Masyarakat Ilmiah Berwawasan
Agribisnis,10(2),p.1866.Available At:
https://doi.org/10.25157/ma.v10i2.13684.
Wirayudha, E., Nurhasanah, Y., and Andriyana (2025) “Implementasi Chatbot
Interaktif Pada Website PT Berdikari Untuk Meningkatkan Layanan
Konsumen Dan Edukasi Agribisnis,” Jurnal Komputer, Informasi dan
Teknologi,5(1),p.13.Available At:
https://doi.org/10.53697/jkomitek.v5i1.


## LAMPIRAN...........................................................................................................

### Lampiran 1. Biodata Ketua dan Anggota, serta Dosen Pendamping...............






Biodata Dosen Pendamping



### Lampiran 2. Justifikasi Anggaran Kegiatan.....................................................

```
No Jenis Pengeluaran Volume Harga Satuan
(Rp)
```
```
Total (Rp)
```
```
1 Belanja Bahan (maks. 60%)
Orange PI Zero 3 Ram
4GB
```
#### 1 850.000 850.000

```
Camera Orange PI
OV5640 Wide Angle
Sensor 5MP
```
#### 2 310.000 620.000

```
Sensor DS18B20 6 40.000 240.000
BreadBoard 6 15.000 90.000
Kabel Jumper 10 30.000 300.000
Ublox NEO-6M GPS
Module
```
#### 4 60.000 240.000

```
Nozzle Mist Sprayer 10 10.000 100.000
Selang 1 Meter 10 8.000 80.000
DC Motor Water Pump
R385
```
#### 6 25.000 150.000

```
Relay (Dana PT) 10 10.000 100.000
Sensor Kelembapan
Tanah
```
#### 6 60.000 360.000

```
Token LLM Gemini 10 100.000 1.000.000
Set Obeng 1 70.000 70.000
Baut PCB 1 50.000 50.000
Kabel Ties (Dana PT) 1 20.000 20.000
HVS (Dana PT) 1 55.000 55.000
SUB TOTAL 85 - 4.325.000
2 Belanja Sewa (maks. 15%)
Sewa Server
VPS/Hosting/Domain
```
#### 1 400.000 400.000

```
Sewa Lab
(Pengembangan
Prototipe)
```
#### 4 100.000 400.000

```
Sewa Lab (Uji Coba
Prototipe) (Dana PT)
```
#### 2 75.000 150.000

```
Google One +
Antigravity (Pro)
```
#### 6 37.500 22.5000

```
Jasa Design Chasing 1 250.000 250.000
Jasa 3D Printer 1 400.000 400.000
SUB TOTAL 15 - 1.825.000
```

3 Perjalanan (maks. 30%)
Kegiatan Penyiapan
Bahan

#### 3 50.000 150.000

```
Kegiatan Pendampingan
(DANA PT)
```
#### 10 50.000 500.000

```
Kegiatan Pengembangan
Prototipe
```
#### 8 50.000 400.000

```
Kegiatan Uji Coba
Prototipe dan Pengguna
```
#### 5 50.000 250.000

FGD Dengan Pakar 4 120.000 480.000
SUB TOTAL 30 - 1.780.000
4 Lain-lain (maks. 15%)
Kuota Internet 4 100.000 400.000
Materai 10000 7 10.000 70.000
Publikasi HAKI (DANA
PT)

#### 2 200.000 400.000

_Ads_ Media Sosial 4 125.000 500.000
SUB TOTAL 17 - 1.370.000
GRAND TOTAL 147 - 9.300.000
GRAND TOTAL (Terbilang Sembilan juta tiga ratus ribu rupiah)


### Lampiran 3. Susunan Tim Pengusul dan Pembagian Tugas............................

```
No Nama/NIM
Program
Studi
```
```
Bidang
Ilmu
```
```
Alokasi
Waktu
(jam/ming
gu)
```
```
Uraian Tugas
```
#### 1

```
Farell
Rhezky
Alvianto /
20125328
```
```
Sistem
Komputer
```
```
IoT
Engineer
```
#### 12

1. Mengelola tugas
tim
2. Merancang dan
mengembangkan
prototipe perangkat
_Internet of Things_

#### 2

```
Dicky
Asqaeliany
Ibnul hakim
/ 20125258
```
```
Sistem
Komputer
```
#### AI

```
Engineer
```
#### 12

```
Pengembangan dan
Penerapan
Kecerdasan Buatan
(ML & LLM) pada
Prototipe Perangkat
Tertanam dan
Aplikasi Mobile
```
```
3
```
```
Rafie Restu
Ramadhani /
10125885
```
```
Sistem
Informasi
```
```
Mobile
Engineer
```
#### 12

```
Perancangan dan
Pengembangan
Aplikasi Mobile
```
#### 4

```
Chivo Hifdz
Addien
Kurniawan /
10225368
```
```
Manajeme
n
```
```
Administ
rasi
```
#### 12

```
Mengelola
administratif dan
keuangan dalam
pelaksanaan
program
```
#### 5

```
Steven
Joshua
Widjaya /
11125047
```
```
Sistem
Informasi
```
#### UI/UX

```
Designer
```
#### 12

```
Membuat laporan
dan merancang
desain aplikasi
mobile
```

### Lampiran 4. Surat Pernyataan Ketua Tim Pengusul........................................


### Lampiran 5. Gambaran Teknologi yang akan Dikembangkan.........................


```
Gambar L5.1. Gambaran Alur Kerja Sistem
```
```
Gambar L5.2. Tampak Bawah (Dimensi: 15x10x8cm)
```
Gambar L5.3. Tampak Samping (Dimensi: 15x10x8cm)


```
Gambar L5.4 Prototype (Dimensi : 15x10x8cm)
```
Gambaran Pembuatan Prototipe

```
Gambar L.5.5 Flowchart Ecotra
```

Gambaran Aplikasi menggunakan Figma

```
Halaman Menu utama
Halaman menu utama
aplikasi mobile
ECOTRA yang
Menampilkan navigasi
utama aplikasi seperti
Beranda, Pemantauan
Sensor, Laporan, dan
Pengaturan.
```
```
Halaman Beranda
Menampilkan ringkasan
kondisi kebun secara
real-time seperti suhu,
kelembapan, pH air,
serta status kesehatan
tanaman dan notifikasi
serangan hama untuk
membantu pengguna
memahami kondisi lahan
secara cepat.
```
```
Halaman Semprot
Menampilkan kontrol
sistem penyemprotan
otomatis dan manual
yang terhubung dengan
perangkat IoT serta
didukung rekomendasi
AI sehingga proses
penyemprotan menjadi
lebih efisien dan tepat
sasaran.
```

(^)
Halaman AI Chat
Menyediakan layanan
asisten virtual berbasis
AI yang dapat menjawab
pertanyaan pengguna
terkait kondisi kebun
dan memberikan
rekomendasi berbasis
data secara cepat dan
praktis.
Halaman Pemantauan
Sensor
Menampilkan data
sensor secara detail
seperti suhu,
kelembapan, curah
hujan, dan pH air dalam
bentuk visual sehingga
pengguna dapat
melakukan analisis
kondisi lingkungan
tanaman secara lebih
akurat.
Halaman Pengaturan
Berfungsi untuk
mengatur preferensi
aplikasi seperti mode
tampilan, keamanan
akun, serta informasi
kebun sehingga
pengguna dapat
menyesuaikan
penggunaan aplikasi
sesuai kebutuhan.


### atau yang lainnya) dengan indeks similaritas maksimum 25%....................... Lampiran 6. Hasil Uji Periksa Similaritas Proposal ( Turnitin, iThenticate

```
yang lainnya) dengan indeks similaritas maksimum 25%
```





