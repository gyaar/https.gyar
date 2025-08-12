<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Data Barang</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: rgb(7, 7, 8);
            margin: 0;
            padding: 20px;
            color: rgb(249, 246, 246);
        }
        h1 {
            text-align: center;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            background-color: white;
            color: black;
            border-radius: 10px;
            overflow: hidden;
        }
        th, td {
            padding: 10px;
            border: 1px solid #090707;
            text-align: center;
        }
        img {
            width: 80px;
            height: auto;
        }
        button {
            padding: 5px 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            color: rgb(11, 10, 10);
        }
        .edit {
            background-color: #3498db;
        }
        .hapus {
            background-color: #e74c3c;
        }
        .tambah {
            background-color: #2ecc71;
            margin-bottom: 10px;
        }
        /* Efek hover tombol */
        .edit:hover {
            background-color: #2980b9;
            cursor: pointer;
        }
        .hapus:hover {
            background-color: #c0392b;
            cursor: pointer;
        }
        .tambah:hover {
            background-color: #27ae60;
            cursor: pointer;
        }
    </style>
</head>
<body>

<h1>Data Barang</h1>

<button>Tambah Barang</button>

<table border="1" cellspacing="0" cellpadding="5">
    <tr>
        <th>No</th>
        <th>Foto</th>
        <th>Nama</th>
        <th>Stok</th>
        <th>Harga</th>
        <th>Aksi</th>
    </tr>
    <tr>
        <td>1</td>
        <td><img src="chromebook.jpg" alt="chromebook"></td>
        <td>chromebook</td>
        <td>10</td>
        <td>Rp 2.000.000</td>
        <td><button>Edit</button> <button>Hapus</button></td>
    </tr>
    <tr>
        <td>2</td>
        <td><img src="hp.jpg" alt="Hp"></td>
        <td>Hp</td>
        <td>15</td>
        <td>Rp 20.000.000</td>
        <td><button>Edit</button> <button>Hapus</button></td>
    </tr>
    <tr>
        <td>3</td>
        <td><img src="kursii.jpeg" alt="kursi"></td>
        <td>kursi</td>
        <td>5</td>
        <td>Rp 800.000</td>
        <td><button>Edit</button> <button>Hapus</button></td>
    </tr>
    <tr>
        <td>4</td>
        <td><img src="rakbuku.jpg" alt="Rak Buku"></td>
        <td>Rak Buku</td>
        <td>8</td>
        <td>Rp 300.000</td>
        <td><button>Edit</button> <button>Hapus</button></td>
    </tr>
    <tr>
        <td>5</td>
        <td><img src="sofa.jpeg" alt="Sofa"></td>
        <td>Sofa</td>
        <td>3</td>
        <td>Rp 1.200.000</td>
        <td><button>Edit</button> <button>Hapus</button></td>
    </tr>
    <tr>
        <td>6</td>
        <td><img src="kasur.jpeg" alt="Kasur"></td>
        <td>Kasur</td>
        <td>6</td>
        <td>Rp 2.000.000</td>
        <td><button>Edit</button> <button>Hapus</button></td>
    </tr>
    <tr>
        <td>7</td>
        <td><img src="lampu.jpg" alt="Lampu"></td>
        <td>Lampu</td>
        <td>20</td>
        <td>Rp 50.000</td>
        <td><button>Edit</button> <button>Hapus</button></td>
    </tr>
    <tr>
        <td>8</td>
        <td><img src="kipas angin.jpg" alt="Kipas Angin"></td>
        <td>Kipas Angin</td>
        <td>12</td>
        <td>Rp 250.000</td>
        <td><button>Edit</button> <button>Hapus</button></td>
    </tr>
    <tr>
        <td>9</td>
        <td><img src="tv.jpg" alt="Televisi"></td>
        <td>Televisi</td>
        <td>4</td>
        <td>Rp 3.000.000</td>
        <td><button>Edit</button> <button>Hapus</button></td>
    </tr>
    <tr>
        <td>10</td>
        <td><img src="kulkas.png" alt="Kulkas"></td>
        <td>Kulkas</td>
        <td>2</td>
        <td>Rp 4.000.000</td>
        <td><button>Edit</button> <button>Hapus</button></td>
    </tr>
</table>

</body>
</html><!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Data Barang</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: rgb(7, 7, 8);
            margin: 0;
            padding: 20px;
            color: rgb(249, 246, 246);
        }
        h1 {
            text-align: center;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            background-color: white;
            color: black;
            border-radius: 10px;
            overflow: hidden;
        }
        th, td {
            padding: 10px;
            border: 1px solid #090707;
            text-align: center;
        }
        img {
            width: 80px;
            height: auto;
        }
        button {
            padding: 5px 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            color: rgb(11, 10, 10);
        }
        .edit {
            background-color: #3498db;
        }
        .hapus {
            background-color: #e74c3c;
        }
        .tambah {
            background-color: #2ecc71;
            margin-bottom: 10px;
        }
        /* Efek hover tombol */
        .edit:hover {
            background-color: #2980b9;
            cursor: pointer;
        }
        .hapus:hover {
            background-color: #c0392b;
            cursor: pointer;
        }
        .tambah:hover {
            background-color: #27ae60;
            cursor: pointer;
        }
    </style>
</head>
<body>

<h1>Data Barang</h1>

<button>Tambah Barang</button>

<table border="1" cellspacing="0" cellpadding="5">
    <tr>
        <th>No</th>
        <th>Foto</th>
        <th>Nama</th>
        <th>Stok</th>
        <th>Harga</th>
        <th>Aksi</th>
    </tr>
    <tr>
        <td>1</td>
        <td><img src="chromebook.jpg" alt="chromebook"></td>
        <td>chromebook</td>
        <td>10</td>
        <td>Rp 2.000.000</td>
        <td><button>Edit</button> <button>Hapus</button></td>
    </tr>
    <tr>
        <td>2</td>
        <td><img src="hp.jpg" alt="Hp"></td>
        <td>Hp</td>
        <td>15</td>
        <td>Rp 20.000.000</td>
        <td><button>Edit</button> <button>Hapus</button></td>
    </tr>
    <tr>
        <td>3</td>
        <td><img src="kursii.jpeg" alt="kursi"></td>
        <td>kursi</td>
        <td>5</td>
        <td>Rp 800.000</td>
        <td><button>Edit</button> <button>Hapus</button></td>
    </tr>
    <tr>
        <td>4</td>
        <td><img src="rakbuku.jpg" alt="Rak Buku"></td>
        <td>Rak Buku</td>
        <td>8</td>
        <td>Rp 300.000</td>
        <td><button>Edit</button> <button>Hapus</button></td>
    </tr>
    <tr>
        <td>5</td>
        <td><img src="sofa.jpeg" alt="Sofa"></td>
        <td>Sofa</td>
        <td>3</td>
        <td>Rp 1.200.000</td>
        <td><button>Edit</button> <button>Hapus</button></td>
    </tr>
    <tr>
        <td>6</td>
        <td><img src="kasur.jpeg" alt="Kasur"></td>
        <td>Kasur</td>
        <td>6</td>
        <td>Rp 2.000.000</td>
        <td><button>Edit</button> <button>Hapus</button></td>
    </tr>
    <tr>
        <td>7</td>
        <td><img src="lampu.jpg" alt="Lampu"></td>
        <td>Lampu</td>
        <td>20</td>
        <td>Rp 50.000</td>
        <td><button>Edit</button> <button>Hapus</button></td>
    </tr>
    <tr>
        <td>8</td>
        <td><img src="kipas angin.jpg" alt="Kipas Angin"></td>
        <td>Kipas Angin</td>
        <td>12</td>
        <td>Rp 250.000</td>
        <td><button>Edit</button> <button>Hapus</button></td>
    </tr>
    <tr>
        <td>9</td>
        <td><img src="tv.jpg" alt="Televisi"></td>
        <td>Televisi</td>
        <td>4</td>
        <td>Rp 3.000.000</td>
        <td><button>Edit</button> <button>Hapus</button></td>
    </tr>
    <tr>
        <td>10</td>
        <td><img src="kulkas.png" alt="Kulkas"></td>
        <td>Kulkas</td>
        <td>2</td>
        <td>Rp 4.000.000</td>
        <td><button>Edit</button> <button>Hapus</button></td>
    </tr>
</table>

</body>
</html>
