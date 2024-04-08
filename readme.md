# Background / Latar Belakang

AWS (Amazon Web Service) adalah layanan Komputasi Awan (Cloud Computing) dari perusahaan Amazon. AWS merupakan salah satu pilihan utama untuk komputasi awan dengan serangkaian keunggulan dan fitur. Amazon Web Services (AWS) adalah platform awan yang paling komprehensif di dunia, menawarkan lebih dari 200 layanan yang lengkap dari pusat data di seluruh dunia. Hal ini banyak diadopsi oleh jutaan pelanggan, termasuk startup, perusahaan besar, dan lembaga pemerintah terkemuka. 

SaaS (Software as a Service) di AWS mengacu pada model layanan di mana perangkat lunak disediakan dan diakses melalui internet. Dalam konteks AWS, SaaS bisa berarti aplikasi perangkat lunak yang di-host dan dijalankan di infrastruktur AWS, yang kemudian diakses oleh pengguna melalui web browser. AWS menyediakan berbagai layanan yang mendukung pengembangan, penyebaran, dan pengelolaan aplikasi SaaS, termasuk Amazon Elastic Compute Cloud (EC2) untuk menjalankan aplikasi, Amazon Relational Database Service (RDS) untuk menyimpan data, dan Amazon Simple Storage Service (S3) untuk penyimpanan objek. Dengan menggunakan layanan AWS, perusahaan dapat membangun dan mengoperasikan aplikasi SaaS mereka dengan skalabilitas, keandalan, dan keamanan yang tinggi.

dikutip dari  artikel yang ditulis oleh [Felix Richter](https://www.statista.com/chart/18819/worldwide-market-share-of-leading-cloud-infrastructure-service-providers/)  menurut perkiraan dari Synergy Research Group, pangsa pasar Amazon dalam pasar global Infrastruktur Cloud mencapai 31 persen pada kuartal keempat tahun 2023, turun dari 33 persen setahun sebelumnya. 


Dengan adanya artikel tersebut, sebagai seorang Analis Data, kita dapat mengidentifikasi pola dan tren dalam volume penjualan. Selain itu, kita juga dapat mengeksplorasi perilaku pembelian perusahaan hal ini termasuk  distribusi geografis pelanggan, produk yang disukai dan lain sebagainya. 


# Problem Statement

SaaS (Software as a Service) sales adalah penjualan perangkat lunak sebagai layanan. Dalam konteks AWS, ini mengacu pada penjualan produk perangkat lunak yang diakses dan digunakan secara berlangganan melalui internet, tanpa perlu menginstal perangkat lunak secara fisik di perangkat pengguna. Dalam hal ini, perusahaan AWS menjual perangkat lunak penjualan dan pemasaran kepada perusahaan lain (B2B) dalam bentuk layanan yang dapat diakses secara online.

kali ini akan mencari faktor-faktor yang menyumbang pada profitabilitas negatif dalam penjualan produk SaaS di AWS, terutama dalam konteks produk yang menghasilkan keuntungan negatif. Tujuan dari analisis ini adalah untuk mengidentifikasi variabel-variabel yang mungkin mempengaruhi profitabilitas negatif berdasarkan kinerja penjualan, segmen pelanggan, dan pasar perusahaan. Sebagai seorang analis data, kita akan mencoba menjawab pertanyaan atas masalah **faktor apa saja yang berkontribusi terhadap penurunan profit dalam penjualan SaaS di AWS, dan bagaimana  mengoptimalisasi produk yang memiliki profibilitas kurang baik dalam penjualan, dengan bedasarkan analisis terhapada sales performance, pasar perusahaan , dan segmentasi pelanggan.**

dari masalah diatas , maka akan diuji analisis menggunakan 2 cara analisis. 
1. **Analisis kinerja penjualan perusahaan.** menganalisis faktor yang mempengaruhi penjualan dan keuntungan. terlebih untuk keuntungan negatif.hal ini akan diuji salah satu caranya dengan faktor dari pemberian diskon.

2. **Analisis segmentasi perusahaan.** identifikasi performansi wilayah atau subwilayah , dan analisis segmentasi pembelian produk di berbagai industri.

3. # Goal / Tujuan

Tujuan dari analisis ini untuk mengetahui faktor apa saja yang berkontribusi terhadap profit yang negatif sehingga mempengaruhi trend dari penjualan produk AWS. faktor ini akan dilakukan dengan 2 cara analisis yang diharapkan akan membuat Perusahaan Amazon khususnya di AWS agar bisa mendapatkan masukan / insight sehingga dari sisi perusahaan bisa mengambil keputusan yang tepat agar dapat meningkatkan kembali penjualan dan profitabilitasnya dan pada ujungnya diharapkan tetap mempertahankan posisinya sebagai leader di dunia web service. 

# EDA (Exploratory Data Analysis)

Profit akan dijadikan variabel target , hal ini dikarenakan secara eksplisit terlihat adanya hal menarik yaitu profit negatif. analisis diharapkan akan menentukan faktor-faktor apa yang mempengaruhi profitabilitas negatif dalam penjualan produk SaaS di AWS.

- variabel target (dependen) : Profit
- variabel yang mempengaruhi (independen) : kolom lainnya

# Kesimpulan


Secara Konsisten Marketing Suites mengalami profitabilitas dengan trend negatif. dari keseluruhan produk di perusahaan khususnya di SaaS sales, marketing suite menjadi faktor berkurangnya profit. trend negatif yang terus konsisten merupakan tanda perlunya perhatian khusus dari perusahaan. dilihat dari analisis korelasi antar variabel secara numerik , ataupun dilihat dari analisis regional, sub regional , negara (country) secara konsisten terdapat trend negatif. hal ini menyatakan bahwa marketing suite menjadi produk yang mendapat banyak rintangan dari beberapa wilayah. berikut akan disimpulkan beberapa hasil temuan dan analisis pendukung bagi perusahaan : 

1. Jika kita melihat trend dari diskon dan Profit , Peningkatan diskon sangat berkolasi dengan penurunan profit. semakin tinggi diskon makan semakin turun profit. hal ini diperlukan strategi/peninjauan ulang dari tim bisnis/ marketing terkait penjualan marketing suites , optimalkan strategi diskon untuk mencapai keseimbangan antara meningkatkan penjualan dan mempertahankan margin keuntungan. Pertimbangkan penawaran diskon bertingkat atau penawaran bersyarat untuk mempertahankan profitabilitas.
2. Analisis Regional menunjukkan beberapa memilik profit positif di beberapa regional, tetapi di beberapa regional juga mengalami penurunan. hal ini diperlukan strategi unntuk mendukung kenaikan profit. hal ini bisa diketahui dari faktor lain lain yang harus diketahui, seperti faktor kebiasaan pasar, faktor budaya, dan lain lain. 
3. untuk mengetahui dan mendukung point no 2 , kami melakukan analisis lebih dalam dengan menganalisis sub region dan negara mana saja yang memiliki profitbilitas negatif dan positif. berfokus di negara, Top 3 negara dengan Profit negatif adalah Japan, Russia, France dengan kerugian masing-masing sebesar -2408.92, -2391.14, dan -2896 setelah melakukan beberapa pengumpulan data diluar melalui beberapa artikel   ternyata tedapat beberapa faktor ketiga negara tersebut memiliki kebiasaan pemasaran/marketing yang berbeda. seperti yang terdapat pada artikel  [Sistem Pemasaran ala Jepang](https://www.blj.co.id/2013/03/17/sistem-pemasaran-ala-jepang/) , Jepang memiliki kemampuan memasarkan produknya ke negara lain secara komersial. Sistem pemasaran yang efektif menjadi katalisator pertumbuhan ekonomi di negara tersebut. Jepang membuktikan mereka dapat menembus semua pasaran. Jepang yang mengedepankan Marketing secara konvensional melalui budaya walaupun hampir berjalan beriringan dengan digital, tapi Jepang selalu membuat strategi marketing dengan seperti membuat event event besar di beberapa bulan yang berbeda yang memancing rasa penasaran wisatawan. sedangkan france mengedepankan marketing dari sisi kreatifitas khususnya di bidang Fashion dengan kualitas yang sangat baik , penekanan pada seni & tradisi yang hal itu juga memancing rasa penasaran wisatawan/ pelanggan. walaupun beriringan dengan marketing digital tetapi startegi lainnya lebih memiliki faktor besar.
4. dengan mengetahui segmentasi kegunaan produk, kita bisa melihat adanya presentase besar di segment SMB (Small-Medium Business), hal ini bisa dimanfaatkan untuk merancang strategi penjualan dengan melakukan research apa yang menjadikan mereka membeli marketing suite. analisis lebih lanjut faktor-faktor yang menyebabkan kerugian di antara pelanggan tertentu bertujuan mengembangkan strategi yang ditargetkan untuk perbaikan atau jika diperlukan/dipertimbangkan untuk mengevaluasi ulang penjualan. 
5. Lakukan analisis manfaat produk dan biaya yang teliti terhadap produk Marketing Suite untuk memahami struktur biayanya dan nilai yang dirasakan. Hal ini akan membantu dalam menilai apakah strategi penetapan harga sejalan dengan harapan pelanggan dan kondisi pasar. jika dirasa ada kekurangan, bisa dikaji ulang apakah perlu atau tidak paket Marketing Suite diadakan, mengingat pengaruh negatif untuk profit yang begitu besar.


