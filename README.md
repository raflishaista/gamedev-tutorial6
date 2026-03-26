Tombol pada layar game over untuk kembali ke menu utama.

Sebuah node LinkButton ditambahkan sebagai child node, dan script dan connection untuk melakukan redirect ke scene dimana nama scene dapat dispesifikasi. Disini, scene akan meredirect ke main menu.

Fitur Select Stage (yang konon sudah ada button-nya di main menu namun tidak dihiraukan).

Scene baru dibuat, berdasarkan scene game over yang menggunakan ColorRect. Tiga LinkButton dibuat, dimana dua button ditempatkan sejajar ditengah rect, yang berisi script dan connection pressed untuk melakukan redirect ke level 1 dan level 2, sehingga menu untuk memilih dua level dibuat. Kemudian, linkbutton ketika ditambahkan di pojok bawah kanan, untuk redireksi ke main menu kembali, sebagai tombol back, dengan teks tersendiri. Terakhir, untuk mengakses halaman ini, pada teks select stage di menu, sebuah signal dan script untuk melakukan redirect ke scene baru level selection dibuat. 

Layar dan efek transisi antar level, dari level 1 ke level 2.

Scene Baru ColorRect dibuat, dengan warna biru cerah untuk menandakan bahwa pemain berhasil melewati level, dengan Label teks selamat untuk memberikan selamat ke player. Lalu, ada dua LinkButton, satu untuk redireksi ke level selanjutnya, dan satu lagi untuk kembali ke main menu, dimana kedua button disertai dengan script dan connection dengan mengisi target.

Polishing

Polishing dilakukan kepada fitur select stage. Kedua tombol untuk memilih scene digerakkan ke bawah sedikit. Gambar dari layout kedua level ditambahkan ke asset. Pada halaman select stage, dua Sprite2D ditambahkan, yang ditambahkan gambar kedua level tersebut. Sprite2D tersebut diluruskan kepada kedua linkbutton, untuk menunjukkan bagaimana visualisasi level yang dapat dipilih terlihat seperti apa. Lalu, LinkButton juga ditambahkan kepada gambar Sprite2D tersebut, sehingga pemain dapat menekan gambar tersebut untuk mengakses level juga, menciptakan visualisasi untuk level select.