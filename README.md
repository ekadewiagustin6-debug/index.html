<!DOCTYPE html>
<html>
<head>
  <title>Form Jastip Caca</title>
  <style>
    body {
      font-family: Arial;
      background: #fff7f9;
      padding: 20px;
    }
    h2 {
      color: #ff4d6d;
    }
    .box {
      background: white;
      padding: 15px;
      border-radius: 10px;
      margin-bottom: 15px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    input, textarea, select {
      width: 100%;
      padding: 8px;
      margin-top: 5px;
      margin-bottom: 10px;
      border-radius: 6px;
      border: 1px solid #ccc;
    }
    button {
      background: #ff4d6d;
      color: white;
      border: none;
      padding: 10px;
      border-radius: 8px;
      cursor: pointer;
    }
  </style>
</head>

<body>

<h2>🛍️ JASTIP ORDER LIST – CACA</h2>

<div class="box">
  <h3>Data Customer</h3>
  <input type="text" placeholder="Nama">
  <input type="text" placeholder="No WA / IG">
  <textarea placeholder="Alamat Lengkap"></textarea>
</div>

<div class="box">
  <h3>Detail Titipan</h3>
  <input type="text" placeholder="Nama Barang / Makanan">
  <input type="text" placeholder="Toko / Tempat">
  <input type="number" placeholder="Jumlah">
  <input type="text" placeholder="Varian / Rasa">
  <input type="number" placeholder="Estimasi Harga">
</div>

<div class="box">
  <h3>Rincian Biaya</h3>
  <input type="number" placeholder="Harga Barang">
  <input type="number" placeholder="Fee Jastip">
  <input type="number" placeholder="Ongkir">
  <input type="number" placeholder="Total">
</div>

<div class="box">
  <h3>Status</h3>
  <select>
    <option>Menunggu</option>
    <option>Dibeli</option>
    <option>Dikirim</option>
    <option>Selesai</option>
  </select>
</div>

<button>Submit Order</button>

</body>
</html>
