# SI2PE (Sistem informasi Pengelolaan Penelitian)
---
## Intoduction
<br>
<p>Ini merupakan projek untuk menyelesaikan Mata Kuliah PBW (Pemrograman Berbasis Web). UangKuini merupakan sebuah website untuk membantu dalam mempermudah pencatatan keuangan baik secara individu maupun kelompok.</p>

<p>1. Membantu para pengguna dalam pencatatan keuangan".
</p>2. Membantu pengelompokksn pemsduksn msupun pengeluaran psda pengguna.
</p>
    <p>Jadi dalam projek pengguna akan mencatat keuangan secara online dan mempermudah dalam mencatat keuangan seperti pemasukan dan pengeluaran dikarenakan dapat dikelompokan dalam beberapa kategori sehingga user dapat menganalisa manajemen keuangan mereka.</p>
  
## Contibutor
1. Rahmat Azrima Pelangi (2108107010077)
2. Aulia Muzhaffar (2108107010033)

# Si2PE


<p> Berikut ini adalah langkah-langkah dalam menjalankan aplikasi ini </p>

<p> 1. Clone repository ini </p>
<pre><code> git clone https://github.com/AuliaMuzhaffar/UangKu.git</pre></code>

<p> 2. Masuk ke direktori aplikasi </p>
<pre><code> cd Uangku </pre></code>

<p> 3. Install composer </p>
<pre><code> composer install </pre></code>

<p> 4. Buat file .env </p>
<pre><code> cp .env.example .env </pre></code>

<p> 5. Generate key </p>
<pre><code> php artisan key:generate </pre></code>

<p> 6. Buat database baru </p>
<pre><code> create database project_keuangan_laravel </pre></code>

<p> 7. Setting database di file .env </p>
<!-- samakan nama databese anda dengan nama database di file env -->

<p> 8. Migrate database </p>
<pre><code> php artisan migrate:fresh --seed </pre></code>

<p> 9. Install npm </p>
<pre><code> npm install </pre></code>

<p> 11. Jalankan npm dev agar kompilasi css dapat dilakukan </p>
<pre><code>  npm run dev  </pre></code>

<p> 12. Jalankan aplikasi </p>
<pre><code> php artisan serve </pre></code>