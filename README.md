 # Ini adalah panduan sederhana untuk mempelajari Express.js dan Git.

Panduan ini mengajarkan Anda cara memulai proyek dengan Express.js dan Git, termasuk menyiapkan proyek Anda, menjalankan server, dan menangani versi kode dengan Git.

## Ekspres.js.

Express.js adalah alat untuk membuat aplikasi web di Node.js menjadi sederhana. Dengan Express.js, Anda dapat membuat server, menangani jalur, dan menggunakan fungsi pembantu dengan mudah.

### 1.Instalasi.

Pastikan Anda telah menginstal Node.js dan npm. Untuk memulai proyek Express.js, ikuti langkah-langkah berikut.


1. **Buat direktori proyek baru**:
    ```bash
    mkdir my-express-app
    cd my-express-app
    ```

2. **Inisialisasi proyek Node.js**:
    ```
    npm init -y
    ```

3. **Instal Express.js**:
    ```
    npm install express
    ```

### 2. Membuat Server Sederhana

Setelah instalasi, Anda dapat membuat server Express.js dasar. Buat file `app.js` dan tambahkan kode berikut:

```javascript
##const express = require('express');
##const app = express();

w

##app.get('/', (req, res) => {
    ##res.send('Hello World!');
##});

##const port = process.env.PORT || 3000;
##app.listen(port, () => {
    ##console.log(`Server berjalan di http://localhost:${port}`);
##});
