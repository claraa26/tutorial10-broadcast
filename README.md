# Nama: Clara Sista Widhiastuti
# NPM: 2206825782
# Kelas: AdvPro A


### 2.1. Original code of broadcast chat.
![](https://imgur.com/9vwD1rF.jpg)
![](https://imgur.com/lU1e9Y0.jpg)
![](https://imgur.com/UtH09Re.jpg)
![](https://imgur.com/SySxOZE.jpg)

Untuk menjalankan program perlu menjalankan perintah `cargo run --bin server` terlebih dahulu. Kemudian menjalankan perintah
`cargo run --bin client`. Pada sis client nantinya dapat menuliskan suatu pesan yang dikirimkan ke server dan server mengirimkan
kembali ke client yang terhubung pada server. 

### 2.2. Modifying the websocket port
![](https://imgur.com/va62wTl.jpg)
![](https://imgur.com/vdejWgV.jpg)

Karna port diubah client yang berjalan di port sebelumnya tidak bisa mengirim pesan lagi. Sehingga dapat disimpulkan jika client
ingin mengirim pesan harus dipastikan bahwa client-server harus terhubung pada port yang sama.