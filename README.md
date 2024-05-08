Figo Athallah <br>
2006535571 <br>
Game Development

# Latihan Mandiri: Rencana Polishing & Balancing Pada Game Proyek Kelompok

1. Apa saja hal-hal positif yang kamu identifikasi dari pengalaman para pemain ketika mencoba game kelompok?

- Dari pengamatan kami saat playtesting, pemain relatif senang dengan mekanik yang ada pada game, terutama katapel. Mereka juga tertarik dengan _art direction_ yang ditampilkan serta ada beberapa yang menyukai tingkat kesulitan level yang didemokan yang menantang namun seru.

2. Apa saja hal-hal negatif (atau, pain points) yang kamu identifikasi dari pengalaman para pemain ketika mencoba game kelompok?

- Isu yang mencolok yaitu mekanik "dash" yang pada beta stage, dilakukan dengan memencet tombol _direction_ 2 kali dengan cepat. Akan tetapi, ini menyebabkan eksekusi mekanik tersebut menjadi sangat sensitif sehingga rentan menjadi penghadang dibanding pembantu saat para playtester mencoba melakukannya (melakukan dash padahal tidak bermaksud). Selain itu, ada isu dengan kamera statis yang mengikuti player saat ganti scene saja, dimana pergerakannya bisa menyebabkan motion sickness, dan disarankan untuk membuat kameranya mengikuti player secara murni saja, serta feedback berupa story dari game yang belum terlihat. (akan ada saat final product)

3. Dari feedback-feedback yang telah diperoleh, apakah ada isu yang terkait pencapaian kondisi flow oleh pemain?
   - Misalnya, apakah ada tantangan di dalam game yang masih kurang tepat dengan kemampuan pemain pada level tertentu?
   - Atau, apakah ada rancangan level di dalam game yang dirasa terlalu membosankan bagi pemain?

- Pemain cenderung frustrasi karena sering mati pada level yang didemokan, sehingga mereka menganggap level tersebut agak menantang untuk diselesaikan. Namun di sisi lain, ada juga pemain yang menganggap level tersebut terlalu mudah dan pendek. Dikotomi tersebut adalah salah satu bukti nyata dibutuhkannya _game balancing_ pada Contrite.

4. Dari jawaban kamu terhadap pertanyaan 1 hingga 3, tuliskan secara singkat, dalam bentuk bullet points, apa saja hal yang ingin kamu polish dan balance?

- Merombak mekanik dash agar menjadi lebih responsif dan natural
- Mengubah sedikit layout map level yang didemokan agar tidak terlalu pendek dan terdapat keseimbangan dalam tingkat kesulitannya
- Meningkatkan kualitas art dan sprite yang ada di game
- Memperbaiki posisi kamera agar tidak menganggu

5. Untuk masing-masing poin di jawaban pertanyaan 4, jabarkan secara singkat (1 - 3 kalimat) mengenai rencana kerja kamu untuk mengimplementasikan usulan tersebut.

a. Merombak mekanik dash agar menjadi lebih responsif dan natural

- Mengganti tombol dash dari shift menjadi tombol lain, serta mengubah parameter delay menjadi lebih cepat agar tidak terlalu sensitif terhadap input.

b. Mengubah sedikit layout map level yang didemokan agar tidak terlalu pendek dan terdapat keseimbangan dalam tingkat kesulitannya

- Ada platform map yang terpotong kamera, hal tersebut akan diubah, selain itu akan ditambahkan obstacle/enemy dan bagian2 baru agar flow level lebih natural.

c. Meningkatkan kualitas art dan sprite yang ada di game

- Melakukan koordinasi dengan tim design agar membagi rata design TileMap, collectibles, boss dan NPC, serta background. Direncanakan ada bantuan eksternal untuk gambar background level.

d. Memperbaiki posisi kamera agar tidak menganggu

- Mengubah sifat Camera2D agar tetap mengikuti player saat ganti scene saja, namun tidak mengikutinya saat melewati area yang tidak ada apapun seperti jurang atau ketinggian setelah meluncur dari katapel.
