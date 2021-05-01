# Lab5Web
# Pemograman Web
~~~
Nama   = Endrik
NIM    = 311910088
Kelas  = TI.19.C.1
Universitas Pelita Bangsa
~~~
## Langkah-langkah Praktikum
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





