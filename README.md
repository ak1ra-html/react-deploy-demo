# React Deployment Demo 🚀

Project deployment aplikasi React menggunakan GitHub dan Vercel.

## Teknologi yang Digunakan

* React.js
* GitHub
* Vercel

---

# Langkah-Langkah Pengerjaan

## 1. Membuat Project React

Buka terminal lalu jalankan:

```bash
npx create-react-app react-deploy-demo
```

Masuk ke folder project:

```bash
cd react-deploy-demo
```

---

## 2. Menjalankan React Secara Lokal

Jalankan project:

```bash
npm start
```

Aplikasi akan berjalan di:

```text
http://localhost:3000
```

---

## 3. Mengubah Tampilan React

Buka file:

```text
src/App.js
```

Lalu ubah isi file menjadi:

```jsx
function App() {
  return (
    <div style={{
      textAlign: 'center',
      marginTop: '100px',
      fontFamily: 'Arial'
    }}>
      <h1>Deployment React Berhasil 🚀</h1>
      <p>Aplikasi berhasil dijalankan dan siap deploy.</p>
    </div>
  );
}

export default App;
```

Simpan file.

---

## 4. Membuat Repository GitHub

1. Login ke GitHub
2. Klik **New Repository**
3. Buat repository dengan nama:

```text
react-deploy-demo
```

4. Klik **Create Repository**

---

## 5. Upload Project ke GitHub

Inisialisasi Git:

```bash
git init
```

Tambahkan semua file:

```bash
git add .
```

Commit project:

```bash
git commit -m "first commit"
```

Hubungkan ke repository GitHub:

```bash
git remote add origin https://github.com/USERNAME/react-deploy-demo.git
```

Push project:

```bash
git branch -M main
git push -u origin main
```

---

## 6. Deploy ke Vercel

1. Buka https://vercel.com
2. Login menggunakan GitHub
3. Klik **Add New Project**
4. Pilih repository React
5. Klik **Deploy**

Tunggu proses deployment selesai.

---

## 7. Hasil Deployment

Setelah berhasil deploy, aplikasi dapat diakses secara online melalui link Vercel.

Contoh:

```text
https://react-deploy-demo.vercel.app
```

---

## 8. Testing CI/CD

Ubah isi file `App.js`.

Contoh:

```jsx
<h1>CI/CD React Berhasil 🔥</h1>
```

Lalu push kembali ke GitHub:

```bash
git add .
git commit -m "update website"
git push
```

Vercel akan otomatis melakukan deployment ulang.

---

# Output

## Repository GitHub

```text
https://github.com/USERNAME/react-deploy-demo
```

## Deployment Vercel

```text
https://xxxx.vercel.app
```

---

# Kesimpulan

Pada praktikum ini berhasil dilakukan deployment aplikasi React.js menggunakan Vercel. Integrasi GitHub dan Vercel memungkinkan proses CI/CD berjalan otomatis setiap kali terjadi push ke repository.
