<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Sederhana</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: white;
            color: black;
            padding: 7px;
            text-align: center;
        }
        .container {
            margin: 20px auto;
            width: 80%;
            max-width: 800px;
            background: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            padding: 20px;
        }
        .flex-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .image-section, .form-section {
            flex: 1;
        }
        .image-section img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }
        form {
            margin-top: 20px;
        }
        form label {
            display: block;
            margin: 10px 0 5px;
        }
        form input, form textarea, form button {
            width: 100%; /* Sama lebar dengan tombol */
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            box-sizing: border-box; /* Pastikan padding dihitung dalam ukuran */
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        table, th, td {
            border: 1px solid #ddd;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: white;
            color: black;
        }
    </style>
</head>
<body>
    <header>
        <h1>Kelas konsep Bahasa Pemrograman</h1>
        <hr>
    </header>

    <div class="container">
        <!-- Bagian Flexbox -->
        <div class="flex-container">
            <!-- Menampilkan gambar -->
            <section class="image-section">
                <h2>Foto Sedang Di Kelas</h2>
                <img src="kelas KBP.jpg" alt="Inspirasi">
            </section>

            <!-- Menampilkan formulir -->
            <section class="form-section">
                <h2>Formulir</h2>
                <form action="#" method="post">
                    <label for="name">Nama:</label>
                    <input type="text" id="name" name="name" placeholder="Masukkan Nama Anda" required>

                    <label for="NIM">NIM:</label>
                    <input type="NIM" id="NIM" name="NIM" placeholder="Masukkan NIM Anda" required>

                    <label for="message">Berikan Komentar Jika Hadir:</label>
                    <input type="message" id="message" placeholder="Tulis Komentar Anda di sini" required>

                    <button type="submit">Kirim</button>
                </form>
            </section>
        </div>

        <!-- Menampilkan tabel -->
        <section class="table-section">
            <h2>Materi Belajar</h2>
            <table>
                <thead>
                    <tr>
                        <th>No</th>
                        <th>Materi</th>
                        <th>Jadwal</th>
                        <th>Tempat</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>1</td>
                        <td>Praktikum PHP</td>
                        <td>Kamis Jam 08:50 - 10:35</td>
                        <td>Lab RPL</td>
                    </tr>
                    <tr>
                        <td>2</td>
                        <td>Praktikum Javascript</td>
                        <td>Kamis Jam 08:50 - 10:35</td>
                        <td>Lab RPL</td>
                    </tr>
                    <tr>
                        <td>3</td>
                        <td>Membuat Website Dasar</td>
                        <td>Kamis Jam 08:50 - 10:35</td>
                        <td>Lab RPL</td>
                    </tr>
                </tbody>
            </table>
        </section>
    </div>
</body>
</html>

