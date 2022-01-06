<h1>Web Gudang Distributor (About)</h1>
<p align="justify">Aplikasi berupa inventory gudang/warehouse pada distributor produk berbasis web. Aplikasi sederhana ini dibuat menggunakan framework CodeIgniter. Project ini dibuat untuk memenuhi penugasan mata kuliah Interaksi Manusia dan Komputer.</br>
  <br><b>Created by :</b>
  <li>Nama  : I Made Arthya Andika Putra</li>
  <li>NIM   : 2008561052</li>
  <li>Kelas : B</li>
  <li>Prodi : Informatika</li>
</p>

<h2>Requirements</h2>
<p align="justify"><li>PHP versi 5.3.7 atau yang lebih tinggi (saya menggunakan PHP versi 7.4).</li>
  <li>XAMPP atau sejenisnya.</li>
</p>

<h2>User Login Database</h2>
<p align="justify"><b>Username dan Password yang disediakan untuk "Admin"</b>
  <li>Username : admin</li>
  <li>Password : admin</li>
  
  <br><b>Username dan Password yang disediakan untuk "User"</b></br>
  <li>Username : user</li>
  <li>Password : user</li>
  <br>Note : <i>dapat registrasi akun user baru sesuai dengan keinginan kita.</i></br>
</p>

<h2>Notes</h2>
<p align="justify"><li>Setelah repo ini di clone atau di download, harap ganti nama folder menjadi "webgudang".</li>
  <li>Jika terjadi error pada bagian invoice, maka anda perlu men-<i>copy</i> file tcpdf yang terbaru (dapat di clone atau di download disini https://github.com/tecnickcom/TCPDF), lalu copy and paste semua filenya dan masukkan kedalam folder "application/libraries/tcpdf".</li>
</p>

<h2>How to Run Program</h2>
<p align="justify"><li>Paste folder repo yang telah di clone/di download (folder repo yang telah direname menjadi "webgudang") pada direktori "<code>C://xampp/htdocs/</code>".</li>
  <li>Buka XAMPP Control Panel, lalu start Apache dan MySQL service.</li>
  <li>Buat database terlebih dahulu pada <code>localhost/phpmyadmin</code> dengan nama "web_gudang". Lalu mport file "<code>web_gudang.sql</code>" pada database yang telah dibuat.</li>
  <li>Setelah semua proses diatas telah selesai, script dapat dijalankan pada browser masing-masing dengan host <code>localhost/webgudang</code></li>
</p>

