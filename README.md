# Football Club API

## Deskripsi
Football Club API adalah proyek berbasis **Express.js** dengan arsitektur **MVC** yang mensimulasikan data klub dan pemain sepak bola menggunakan array sebagai database sementara. Proyek ini bertujuan untuk memahami bagaimana data yang berelasi dapat diatur dan diakses dalam aplikasi berbasis **Node.js**.

## Fitur
- Menampilkan daftar klub sepak bola
- Menampilkan daftar pemain sepak bola

## Teknologi yang Digunakan
- **Node.js** (Runtime JavaScript)
- **Express.js** (Framework Backend)
- **MVC Architecture** (Model-View-Controller)

## Struktur Folder
```
football-club-api/
│   README.md
│   package.json
│   package-lock.json
│   app.js
│
├── api/v1/
│   ├── club/
│   │   ├── controller.js
│   │   ├── model.js
│   │   ├── router.js
│   ├── player/
│   │   ├── controller.js
│   │   ├── model.js
│   │   ├── router.js
│
├── public/
│  
├── views/
│   ├── club/
│   │   ├── index.ejs
│   ├── player/
│   │   ├── index.ejs
│   ├── template/
│   │   ├── app.ejs
│   │   ├── footer.ejs
│   │   ├── header.ejs
```

## 🔧 Cara Menjalankan
1. **Clone Repository:**
   ```sh
   git clone https://github.com/username/football-club-api.git
   cd football-club-api
   ```
2. **Install Dependencies:**
   ```sh
   npm install
   ```
3. **Jalankan Server:**
   ```sh
   npm start
   ```
4. **Akses API di Browser atau Postman:**
   - `http://localhost:3000/club/` → Menampilkan daftar klub
   - `http://localhost:3000/player/` → Menampilkan daftar pemain

## Lisensi
Proyek ini dibuat untuk tujuan edukasi dan open-source di bawah lisensi **MIT**.

---
Jika ada saran atau pertanyaan, jangan ragu untuk membuka **Issues** atau **Pull Request**! ⚽🚀

