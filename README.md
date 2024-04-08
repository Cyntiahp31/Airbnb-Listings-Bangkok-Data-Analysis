# Airbnb-Listings-Bangkok-Data-Analysis
Comprehensive Analysis on Airbnb Listings Bangkok

# Cyntia Angelica

# Link
1. Link Tableau: https://public.tableau.com/views/DataAnalysis-AirbnbBangkok/Dashboard1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link
2. Link PowerPoint: https://www.canva.com/design/DAGBU61TbOc/0o4mZc_2PnXHh-3yCjQlvQ/edit?utm_content=DAGBU61TbOc&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
3. Link Video Presentasi: https://drive.google.com/file/d/1U6EY7ZrNKDFJdIIi-0igUUZ_C7d8TnDD/view?usp=sharing

# Background
Airbnb adalah sebuah perusahaan yang bergerak di bidang perhotelan. Airbnb menawarkan berbagai pilihan untuk pelancong, dari kamar hotel, rumah, resort, condominium, bahkan kamar bersama. Airbnb menawarkan short-term maupun long-term stay, sehingga cocok bagi seorang turis ataupun warga menetap.
Sebagai kota yang kaya akan budaya, Bangkok tak jarang menjadi destinasi wisata favorit. Mulai dari night market yang menjual kuliner khas Thailand, club malam gemerlap, hingga pantai yang memanjakan mata, semua ada di Bangkok.
Airbnb hadir di Bangkok untuk memudahkan para turis lokal dan mancanegara untuk berwisata di Bangkok tanpa mengkhawatirkan akomodasi. Fitur Airbnb yang memungkinkan ulasan hanya dari tamu yang telah melakukan pemesanan lewat Airbnb, memberikan bantuan bagi wisatawan dalam menemukan listing yang sesuai dengan preferensi mereka.
Pada analisis ini kita akan fokus pada price dan melihat apa saja variabel yang memengaruhinya.

# Problem Statement
Tarif sewa pada Airbnb dipasang oleh host (source). Maka dari itu, dengan memahami faktor-faktor yang mempengaruhi tarif kamar, Airbnb dapat memberikan rekomendasi kepada para host homestay untuk menetapkan harga yang lebih optimal. Host yang menggunakan platform Airbnb harus membayar biaya layanan kepada Airbnb, yaitu 3% dari subtotal yang dibayar penyewa (source). Dengan demikian, semakin optimal harga yang ditetapkan oleh host, semakin tinggi pendapatan yang diperoleh oleh Airbnb melalui biaya layanan. Namun, tantangan muncul dalam menyeimbangkan antara harga yang kompetitif dan memastikan keuntungan maksimal bagi host dan platform. Selain itu, banyaknya listing yang kurang populer meninimalisir profitabilitas sebuah listing.

Sebagai data analyst, kita akan menjawab pertanyaan berikut ini:

1. Bagaimana karakteristik sebuah listing memengaruhi tarif harian yang ditetapkan oleh host? Apa saja faktor yang memengaruhi tarif harian listing? Apa yang dapat dilakukan untuk meningkatkan profit host? Bagaimana cara menetapkan harga yang bersaing?
2. Bagaimana karakteristik dari listing yang populer? Apa langkah yang dapat diambil untuk meningkatkan popularitas listing?
3. Bagaimana bahasa dari judul listing memengaruhi tarif harian listing dan popularitas listing?

# Insights
Dari analisis yang telah dilakukan sebelumnya, ada beberapa insight yang didapat:

General:

- Dari 15,846 data yang kita miliki, hanya 1471 listing yang tergolong listing populer
- Terdapat 4 tipe kamar yang ditawarkan ('Entire home/apt', 'Private room', 'Hotel room', dan 'Shared room'). Tipe kamar yang paling banyak ditawarkan adalah 'Entire home/apt', dan 'Private room'.
- Listing populer didominasi oleh 'Entire home/apt' dan 'Private room'
- Vadhana, Khlong Toei, dan Huai Khwang adalah distrik dengan jumlah listing terbanyak.

price:

- Listing yang tergolong populer memiliki median tarif harian yang lebih besar daripada listing yang tidak populer.
- Tipe kamar 'Hotel room', 'Entire home/apt', dan 'Private room' merupakan tipe kamar dengan median tarif harian tertinggi, yaitu 1700 THB, 1536 THB, 1212 THB.
- Distrik yang berada di tengah kota memiliki median tarif harian yang lebih tinggi.
- Nong Chok, Pathum Wan, dan Vadhana merupakan distrik dengan median tarif harian tertinggi. Sedangkan distrik dengan median tarif terendah adalah distrik yang berada di pinggir kota seperti Nong Khaem, Wang Thong Lang, dan Don Mueang.
- Median tarif harian listing yang disewakan secara 'short-term' lebih besar dibandingkan listing yang disewakan secara 'long-term'
- Listing yang berjudul bahasa Inggris memiliki median tarif yang lebih tinggi daripada listing yang berjudul bahasa lain.

popularity:

- Tipe kamar memengaruhi popularitas sebuah listing
- Durasi menginap tidak memengaruhi popularitas sebuah listing
- Listing yang populer mayoritas terletak di pusat kota, khususnya di distrik Khloeng Toei, Vadhana, Sathon, Bang Rak, Ratchathewi, Pathum Wan, dan Phaya Thai. Distrik-distrik tersebut memang terkenal dengan night market, night club, mall mewah, bar, dan hiburan lainnya.
- Selain di pusat kota, listing populer juga ditemukan di sekitar bandara Internasional Don Mueang (distrik Don Mueang) dan bandara Suvarnabhumi (terletak distrik Bang Phli yang terletak di luar Bangkok).
- Listing populer cenderung dimiliki oleh host yang mempunyai listing yang banyak.
- Bahasa dari judul listing memengaruhi popularitas sebuah listing. Selain itu, listing berbahasa Inggris juga memiliki jumlah review yang lebih banyak dibandingkan listing berbahasa lainnya.
- 
Other analysis:

- Tiap distrik didominasi oleh listing bertipe 'Entire home/apt' atau 'Private room'
