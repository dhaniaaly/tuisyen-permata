# tuisyen-permata
PENDAFTARAN TUISYEN PERMATA
[Uploading index.h<!DOCTYPE html>
<html lang="ms">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TUISYEN PENGUKUHAN AKADEMIK PERMATA</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fff;
            color: black;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
            text-align: center;
        }
        h1 {
            color: #d4af37; /* Warna gold */
        }
        .info {
            background-color: black;
            color: white;
            padding: 15px;
            border-radius: 5px;
        }
        form {
            background-color: #f8f8f8;
            padding: 20px;
            border-radius: 5px;
            margin-top: 20px;
        }
        input, select, button {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #d4af37;
            color: white;
            font-size: 16px;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="logo.png" alt="Logo Tuisyen" width="150">
        <h1>TUISYEN PENGUKUHAN AKADEMIK PERMATA</h1>

        <div class="info">
            <p><strong>Alamat:</strong> Tingkat 2, No. 890, Jalan Senai Utama 4/1, Taman Senai Utama, 81400 Senai, Johor.</p>
            <p>(Berhadapan Padang SK Senai Utama)</p>
            <p><strong>PIC:</strong> Siti Meriam Binti Haron</p>
        </div>

        <form action="#" method="post">
            <h2>Pendaftaran Kelas Tuisyen</h2>
            <label for="nama">Nama Anak:</label>
            <input type="text" id="nama" name="nama" required>

            <label for="sekolah">Sekolah:</label>
            <input type="text" id="sekolah" name="sekolah" required>

            <label for="telefon">Nombor Telefon:</label>
            <input type="tel" id="telefon" name="telefon" required>

            <label for="alamat">Alamat:</label>
            <input type="text" id="alamat" name="alamat" required>

            <label for="darjah">Darjah:</label>
            <select id="darjah" name="darjah" required>
                <option value="membaca">Membaca</option>
                <option value="tahun1">Tahun 1</option>
                <option value="tahun2">Tahun 2</option>
                <option value="tahun3">Tahun 3</option>
                <option value="tahun4">Tahun 4</option>
                <option value="tahun5">Tahun 5</option>
                <option value="tahun6">Tahun 6</option>
            </select>

            <label for="bayaran">Kaedah Pembayaran:</label>
            <select id="bayaran" name="bayaran" required>
                <option value="online">Online Transfer</option>
                <option value="cash">Cash</option>
            </select>

            <label for="bukti">Bukti Pembayaran (jika online transfer):</label>
            <input type="file" id="bukti" name="bukti">

            <button type="submit">Daftar Sekarang</button>
        </form>

        <div class="info">
            <h3>Maklumat Pembayaran</h3>
            <p><strong>Bank:</strong> CIMB</p>
            <p><strong>No Akaun:</strong> </p>
            <p><strong>Nama :</strong> Siti Meriam </p>
        </div>
    </div>
</body>
</html>
tml…]()
[Uploading style.body {
    background-color: #fff;
    font-family: Arial, sans-serif;
}

h1 {
    color: #d4af37;
}
css…]()
[Uploading script.js…]()document.querySelector("form").addEventListener("submit", function(event) {
    alert("Pendaftaran berjaya! Kami akan hubungi anda segera.");
});

