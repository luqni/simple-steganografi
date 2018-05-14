* format berkas digital yang dapat dijadikan media untuk menyembunyikan pesan
[1] format image : bitmap(bmp),gif,pcx,jpeg dll.
[2] format audio : wav,voc,mp3 dll
[3] format lain : teks file,html,pdf dll


*Example
1. Buat file dengan format txt (tes.txt)
2. Buat file dengan format .zip dari file yang akan kita sembunyikan ketik:
3. zip -r secret-file.zip test.txt
4. Gabungkan file secret-file.zip dengan gambar yang mau kita sisipan (secret-file.zip berisi pesan rahasia tes.txt
5. cat pinguin.png secret-file.zip > pinguin-imut.png
6. sekarang cek ukuran gambar pinguin.png dengan pinguin-imut.png
7. untuk membuka pesan lakukan unzip :
6. unzip pinguin-imut.png