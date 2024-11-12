
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SIMDONDAR - Sistem Informasi Donor Darah</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #ff4b5c;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    main {
      padding: 20px;
    }
    .card {
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      margin-bottom: 20px;
      padding: 20px;
      text-align: center;
    }
    button {
      background-color: #ff4b5c;
      color: #fff;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #ff6f71;
    }
  </style>
</head>
<body>
  <header>
    <h1>SIMDONDAR</h1>
    <p>Sistem Informasi Donor Darah</p>
  </header>
  <main>
    <div class="card">
      <h2>Informasi Donor Darah</h2>
      <p>Cari informasi mengenai jadwal donor darah, lokasi, dan jenis darah yang tersedia.</p>
      <button onclick="alert('Navigasi ke Informasi Donor')">Cari Informasi</button>
    </div>
    <div class="card">
      <h2>Donor Baru</h2>
      <p>Daftarkan diri Anda sebagai calon pendonor darah.</p>
      <button onclick="alert('Navigasi ke Formulir Pendaftaran Donor Baru')">Daftar Sekarang</button>
    </div>
    <div class="card">
      <h2>Penerima Darah</h2>
      <p>Cari informasi mengenai kebutuhan darah untuk penerima.</p>
      <button onclick="alert('Navigasi ke Informasi Kebutuhan Darah')">Cari Kebutuhan Darah</button>
    </div>
  </main>
</body>
</html>
