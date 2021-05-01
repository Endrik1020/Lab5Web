# Lab5Web
# Pemograman Web
~~~
Nama   = Endrik
NIM    = 311910088
Kelas  = TI.19.C.1
Universitas Pelita Bangsa
~~~
# Langkah-langkah Praktikum
Buka aplikasi Visualcode 
Persiapankan membuat dokumen HTML dengan nama file lab5_javascript.html seperti berikut:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
 <title>Mengenal JavaScript</title>
</head>
<body>
 <h1>Pengenalan JavaScript</h1>
 <h3>Contoh document.write dan console.log</h3>
 <script>
 document.write("Hello World");
 console.log("Hello World");
 </script>
</body>
</html>
~~~
![1](https://user-images.githubusercontent.com/81820421/116763805-077e8a00-aa49-11eb-8cb9-c3e496d1ade7.JPG)
![2](https://user-images.githubusercontent.com/81820421/116763977-9f7c7380-aa49-11eb-96b7-5aa113a36b48.JPG)
　　
# Javascrip Dasar
Pemakaian Alert sebagai property window
~~~
<!DOCTYPE  html>
<html>
<head>
<title>alert box</title>
</head>
<body>
<script language = "javascript">
<!--
    window.alert("ini merupakan pesan untuk anda");
    //-->
</script>
</body>
</html>
~~~
![3](https://user-images.githubusercontent.com/81820421/116764160-54af2b80-aa4a-11eb-8192-396d959d3407.JPG)

# Pemakaian method dalam objek
~~~
<!DOCTYPE  html>
<html>
<head>
<title>skrip javascript</title>
</head>
<body>
Percobaan Memakai Javascript<br> 
<script language = "javascript">
<!--
    document.write("selamat mencoba javasript<br>");
    document.write("semoga sukses!");
    //-->
</script>
</body>
</html>
~~~
![4](https://user-images.githubusercontent.com/81820421/116764252-bd96a380-aa4a-11eb-85b9-9c9d2d611b07.JPG)

# Pemakaian method Prompt
~~~
<!DOCTYPE  html>
<html>
<head>
<title>pemasukan data</title>
</head>
<body>
<script language = "javascript">
<!--
    var nama = prompt("siapa nama anda?","Endrik Bin Suwarih");
    document.write("hai ","Endrik Bin Suwarih");
    //-->
</script>
</body>
</html>
~~~
![5](https://user-images.githubusercontent.com/81820421/116764490-7361f200-aa4b-11eb-8cbb-7aad65be1eb2.JPG)
![6](https://user-images.githubusercontent.com/81820421/116764567-b4f29d00-aa4b-11eb-8281-61e79bb100f8.JPG)
# Pembuatan fungsi dan cara pemanggilannya
~~~
<!DOCTYPE  html>
<html>
<head>
    <title>Contoh program javascript</title>
    <script language = "javascript">
    function pesan(){alert ("Memanggil javascript lewat body onload")
    }
    </script>
</head>
<body onload=pesan()>
</body>
</html>
~~~
![7](https://user-images.githubusercontent.com/81820421/116764699-19156100-aa4c-11eb-86cc-29377657ffea.JPG)
# Dasar Pemrograman Di Javascript
Operasi dasar aritmatika
~~~
<html>
<head>
    <title>Contoh program javascript</title>

    <script language = "javascript">
    function test (val1,val2)
    {   
        document.write("<br>"+"perkalian : val1*val2 "+"<br>")
        document.write(val1*val2)
        document.write("<br>"+"pembagian : val1/val2 "+"<br>")
        document.write(val1/val2)
        document.write("<br>"+"penjumlahan : val1+val2 "+"<br>")
        document.write(val1+val2)
        document.write("<br>"+"pengurangan : val1-val2 "+"<br>")
        document.write(val1-val2)
        document.write("<br>"+"modulus : val1%val2 "+"<br>")
        document.write(val1%val2)
    }
    </script>
</head>
<body>
    <input type="button" name="button1" value="aritmatika" onclick=test(9,4)>
</body>
</html>
~~~
![8](https://user-images.githubusercontent.com/81820421/116764815-8c1ed780-aa4c-11eb-8251-f08d645f9e1b.JPG)
## Setelah direfresh muncul tulisan aritmatika . klik aritmatika akan muncul seperti ini :
![9](https://user-images.githubusercontent.com/81820421/116764922-f768a980-aa4c-11eb-8f94-27e2744020be.JPG)
# Seleksi kondisi (if..else)
~~~
<html>
<head>
    <title>Contoh if-else</title>
</head>
<body>
    <script language = "javascript">
    <!--
    var nilai = prompt("nilai (0-10): ", 0);
    var hasil = "";
    if (nilai >=60)
    hasil = "lulus";
    else
    hasil = "tidak lulus";
    document.write("hasil: " + hasil);
    //-->    
    </script>
</body>
</html>
~~~
![10](https://user-images.githubusercontent.com/81820421/116764960-3139b000-aa4d-11eb-9ea4-6348b15c4a5f.JPG)
## klik OK . akan muncul seperti ini 
![11](https://user-images.githubusercontent.com/81820421/116765024-6f36d400-aa4d-11eb-863e-8b4111dffaf2.JPG)

# Penggunaan operator switch untuk seleksi kondisi
~~~
<html>
<head>
    <title>Contoh program javascript</title>

    <script language = "javascript">
    function test ()
    {
        vall=window.prompt("input nilai (1-5):")
        switch (vall)
        {
            case "1" :
                document.write("bilangan satu")
                break
            case "2" :
                document.write("bilangan dua")
                break
            case "3" :
                document.write("bilangan tiga")
                break
            case "4" :
                document.write("bilangan empat")
                break            
            case "5" :
                document.write("bilangan lima")
                break
            default :
                document.write("bilangan lainnya")
        }
    }
    </script>
</head>
<body>
    <input type="button" name="button1" value="switch" onclick=test()>
</body>
</html>
~~~
![12](https://user-images.githubusercontent.com/81820421/116765130-f5531a80-aa4d-11eb-85a9-70a8d0ce1a9c.JPG)
## Lakukan sesuai perintah . kita coba input angka 5 
![13](https://user-images.githubusercontent.com/81820421/116765152-0c920800-aa4e-11eb-896f-75066af1e50f.JPG)
## Setelah itu akan muncul seperti ini 
![14](https://user-images.githubusercontent.com/81820421/116765162-19aef700-aa4e-11eb-9b75-d9a96f2444d4.JPG)

# Pembuatan Form
Form Input
~~~
<html>
<head>
    <title>Contoh program javascript</title>

    <script language = "javascript">
    function test ()
    {
        var val1=document.kirim.T1.value
        if (val1%2==0)
            document.kirim.T2.value="bilangan genap"
        else
            document.kirim.T2.value="bilangan ganjil"
    }
    </script>
</head>
<body>
    <form method="POST" name="kirim">
        <p>BIL <input type="text" name="T1" size="20">
        MERUPAKAN BIL <input type="text" name="T2" size="20"></p>
        <p><input type="button" value="TEBAK" name="B1" onclick=test()></p>
    </form>
</body>
</html>
~~~
![15](https://user-images.githubusercontent.com/81820421/116765479-84acfd80-aa4f-11eb-8535-6553ec89320e.JPG)
![16](https://user-images.githubusercontent.com/81820421/116765526-c8076c00-aa4f-11eb-959d-7461d7770a40.JPG)
# Form Button
~~~
<html>
<head>
    <title>Contoh program javascript</title>
</head>
<body>
    <script language = "javascript">
    <!--
    function ubahWarnaLB(warna) {
        document.bgColor = warna;
    }
    function ubahWarnaLD(warna) {
        document.fgColor = warna;
    }   
        -->
    </script>
    <h1>Tes</h1>
    <form>
        <input type="button" value="Latar Belakang Hijau" onClick="ubahWarnaLB('GREEN')">
        <input type="button" value="Latar Belakang Putih" onClick="ubahWarnaLB('WHITE')">
        <input type="button" value="Teks Kuning" onClick="ubahWarnaLD('YELLOW')">
        <input type="button" value="Teks Biru" onClick="ubahWarnaLD('BLUE')">
    </form>
    <script language = "javascript">
    <!--
     document.write("Dimodifikasi terakhir pada" +
     document.lastModified);
    //-->
    </script>
</body>
</html>
~~~
![17](https://user-images.githubusercontent.com/81820421/116765610-36e4c500-aa50-11eb-9b96-37446887c93c.JPG)
## Lakukan percobaan . klik button latar belakang Hijau dan Teks kuning
akan muncul seperti ini 
![18](https://user-images.githubusercontent.com/81820421/116765677-875c2280-aa50-11eb-8845-90f8997b3f15.JPG)
## Lakukan percobaan . klik button latar belakang Putih dan Teks Biru
akan muncul seperti ini 
![19](https://user-images.githubusercontent.com/81820421/116765706-b8d4ee00-aa50-11eb-9159-82e72bf0ef4b.JPG)

# HTML DOM
Pilihan menggunakan checkBox dengan perhitungan otomatis
~~~
 <!--
File: daftar_menu.html
//-->
<html>
<head>
    <title>Daftar Menu</title>
    <script>
        function hitung(ele) {
            var total = document.getElementById('total').value;
                total = (total ? parseInt(total) : 0);
            var harga = 0;

            if (ele.checked) {
                harga = ele.value;
                total += parseInt(harga);
            }
            else {
                harga = ele.value;
                if (total > 0)
                    total -= parseInt(harga);
            }
            document.getElementById('total').value = total;
        }
    </script>
</head>
<body>
<h1>Daftar Menu Makanan</h1>
<label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);" /> Ayam Goreng Rp.5000 </label><br />
<label><input type="checkbox" value="500" id="menu2" onclick="hitung(this);" /> Tempe Goreng Rp.500 </label><br />
<label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);" /> Telur Dadar Rp.2500 </label><hr />
<strong>Total Bayar : Rp. <input id="total" type="text" /></strong>
</body>
</html>
~~~
![20](https://user-images.githubusercontent.com/81820421/116765784-36006300-aa51-11eb-89a7-f90e6446d3fc.JPG)
![21](https://user-images.githubusercontent.com/81820421/116765809-55978b80-aa51-11eb-8726-bbf4c73c32ea.JPG)

# Pertanyaan dan Tugas
Buat script untuk melakukan validasi pada isian form.
~~~
<!DOCTYPE HTML>
<html>
<head>
   <title>Validasi Isian Form</title>
</head>
<body>
   <h1>Validasi Isian Form</h1>
   <form>
      <fieldset>
       <legend>Formulir Pendaftaran</legend>
       Nama Lengkap:<br>
         <input type="text" name="nama" required><br>
       Alamat Email:<br>
         <input type="email" name="email" required><br>
       Sandi:<br>
         <input type="password" name="sandi1" required><br>
       Sandi (ulangi):<br>
         <input type="password" name="sandi2" required><br>
     <br>
         <input type="submit" value="Kirim">
    </fieldset>	 
   </form>
</body>
</html>
~~~
![22](https://user-images.githubusercontent.com/81820421/116766255-bde76c80-aa53-11eb-9aa2-129879592960.JPG)
## Jika ada yang belum di isi akan muncul seperti ini 
![23](https://user-images.githubusercontent.com/81820421/116766309-fe46ea80-aa53-11eb-9945-8d8f6713794e.JPG)











