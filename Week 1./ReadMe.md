# Writing and Presentation Test Week 1


## HTML
HTML atau singkatan dari Hyper Text Markup Language merupakan sebuah bahasa struktural yang digunakan dalam membuat website, disebut bahasa struktural karena merupakan sebuah bahasa untuk membuat struktur-struktur dalam web atau bisa disebut sebagai kerangka web, sehingga bukan dikategorikan sebagai bahasa pemrogaman karena tidak menghasilkan sebuah fungsi.

### Struktur Dasar HTML
<p align="center" width="100%">
    <img width="60%" src="https://www.petanikode.com/img/html/dasar/struktur-html.png">
</p>
<h6 align="center">gambar di atas merupakan sebuah struktur paling dasar dalam membuat HTML</h6>
Dalam gambar dijelaskan bahwa tag yang paling penting adalah tag HTML karena merupakan tag yang mendeklarasikan bahwa sebuah file tersebut atau tag tesebut dibaca sebagai sebuah HTML. <br> <br>

Sebenarnya dalam mempelajari HTML yang terpenting adalah kita harus memahami sebuah struktur dari Tag terlebih dahulu, berikut struktur Tag dalam HTML:
<p align="center" width="100%">
    <img width="60%" src="https://www.petanikode.com/img/html/tag/element.png">
</p>
<h6 align="center">gambar di atas merupakan sebuah struktur Tag yang ada dalam HTML</h6>

Struktur paling luar adalah pembuka dan penutup tag disimbolkan dengan < dan > atau sering disebut dengan angled brackets, didalamnya bisa diisikan sebuah atribut untuk memberikan sifat dari tag tersebut. Antara kurung <> </> adalah konten dari sebuah tag yang ingin kita beri, bisa berupa text, foto, maupun video, tergangtung element tag yang kita beri.

### Jenis-Jenis Tag HTML
Dalam HTML ada 2 jenis Tag yaitu:
  <h4>
    <ol>
      <li>
      <h3>Single tag</h3>
      </li>
      Merupakan tag html yang hanya 1 kurung saja, contohnya:
        <p width="100%">
            <img width="33%" src="https://github.com/Chopin44/Writing-and-Presentation-Test/blob/d473b55e69f1c9db81b54bdd1484730b5c4d5c6b/Week%201./singletag.png">
        </p>
      <li>
          <h3>Double tag</h3>
      </li>
        Merupakan tag pada umumnya yang memiliki pembuka dan penutup, contohnnya:
        <p width="100%">
            <img width="33%" src="https://github.com/Chopin44/Writing-and-Presentation-Test/blob/d473b55e69f1c9db81b54bdd1484730b5c4d5c6b/Week%201./doubletag.png">
        </p> 
    </ol>
  </h4>

## Exercise
<ol>
    <li>Siapkan Text Editor bisa menggunakan Notepad++, Atom, Sublime, ataupun Visual Studio Code sesuai yang diinginkan</li>
    <li>Buka Text Editor dan buat sebuah file baru</li>
     <p width="100%">
        <img width="33%" src="https://github.com/Chopin44/Writing-and-Presentation-Test/blob/154a9169831960641e292887104b1435e8cc92a6/Week%201./1.png">
    </p>
    <p width="100%">
        <img width="100%" src="https://github.com/Chopin44/Writing-and-Presentation-Test/blob/154a9169831960641e292887104b1435e8cc92a6/Week%201./2.png">
    </p>
    <li>Deklarasikan tag-tag yang penting dalam HTML</li>
    <p width="100%">
        <img width="100%" src="https://github.com/Chopin44/Writing-and-Presentation-Test/blob/154a9169831960641e292887104b1435e8cc92a6/Week%201./3.png">
    </p>
    <li>Kita coba beri tag H1</li>
    <p width="100%">
        <img width="100%" src="https://github.com/Chopin44/Writing-and-Presentation-Test/blob/154a9169831960641e292887104b1435e8cc92a6/Week%201./4.png">
    </p>
    <li>Buka File tersebut via browser</li>
    <li>Terdapat Text Hello World! di browser maka HTML berhasil dibuat</li>
    <p width="100%">
        <img width="100%" src="https://github.com/Chopin44/Writing-and-Presentation-Test/blob/154a9169831960641e292887104b1435e8cc92a6/Week%201./5.png">
    </p>
</ol>

## CSS
CSS atau singkatan dari Cascading Style Sheets yaitu bahasa yang digunakan untuk menentukan tampilan dan format halaman website. Dengan CSS, kita bisa mengatur jenis font, warna tulisan, latar belakang halaman, dan masih banyak lagi. Dengan adanya CSS website kita akan terlihat lebih menarik, sehingga bisa juga dikatakan sebagai baju atau kosmetik yang disisi lain HTML adalah sebagai kerangkanya.

### Struktur Penulisan CSS
<p align="center" width="100%">
    <img width="60%" src="https://bilabil.com/wp-content/uploads/2019/12/struktur-css.jpg">
</p>
<h6 align="center">gambar di atas merupakan sebuah struktur penulisan dalam membuat CSS</h6>

Dalam gambar tersebut ada sebuah selector, property, dan value, nah apakah itu?
<h4>
    <ol>
      <li>
      <h3>Selector</h3>
        </li>
        Merupakan sebuah sintaks yang ditulis agar element sebuah CSS dapat ditunjuk. Seperti contoh tag-tag pada HTML seperti h1, p, div, span, img, dan masih banyak lagi.
      <li>
          <h3>Property</h3>
      </li>
        Merupakan pemberian sifat pada sebuah element. Seperti contoh ingin memberi warna text dengan color: , memberi warna background dengan background-color: , dan masih banyak lagi contohnya.
       <li>
          <h3>Value</h3>
      </li>
        Merupakan isi dari sebauh property atau sifat apa yang ingin diberikan ke dalam element tertentu. Contoh, color: red, propertynya color atau warna, warna apa yang ingin kita beri? red atau merah.
    </ol>
 </h4>


### Cara Penulisan CSS
<h4>
<ol>
  <li>
  <h3>Inline</h3>
  </li>
  Merupakan cara penulisan CSS langsung ke dalam tag HTML, berikut contohnya:
    <p width="100%">
        <img width="100%" src="https://github.com/Chopin44/Writing-and-Presentation-Test/blob/06ba36d85a39721d02b16ca7c01b3497dd98313f/Week%201./css%201.png">
    </p>
  <li>
      <h3>Internal</h3>
  </li>
    Merupakan penulisan CSS dalam file HTML, dengan tag Style sebagai pembuka dan penutupnya, berikut contohnya:
    <p width="100%">
         <img width="100%" src="https://github.com/Chopin44/Writing-and-Presentation-Test/blob/0d709ab2e2c70934c59882dd84155c6c566ca6c3/Week%201./css%202.png">
    </p>
    <li>
      <h3>Eksternal</h3>
  </li>
    Merupakan penulisan CSS diluar file HTML, untuk memanggilnya bisa menggunakan tag link, berikut contohnya:
    <p width="100%">
         <img width="100%" src="https://github.com/Chopin44/Writing-and-Presentation-Test/blob/0d709ab2e2c70934c59882dd84155c6c566ca6c3/Week%201./css%203.png">
    </p>
    <p width="100%">
         <img width="100%" src="https://github.com/Chopin44/Writing-and-Presentation-Test/blob/06ba36d85a39721d02b16ca7c01b3497dd98313f/Week%201./css%204.png">
    </p> 
</ol>
</h4>

## Exercise
Mungkin setelah memahami struktur penulisan CSS dan cara penulisan CSS, kita masuk saja ke dalam sebuah latihan. (Disini penulis menganggap semua sudah memahami HTML)
<ol>
    <li>Seperti biasa, siapkan Text Editor bisa menggunakan Notepad++, Atom, Sublime, ataupun Visual Studio Code sesuai yang diinginkan</li>
    <li>Buka Text Editor dan buat sebuah file baru CSS (sebelumnya sudah exercise <a href="https://github.com/Chopin44/Writing-and-Presentation-Test/edit/main/Week%201./ReadMe.md#exercise">HTML</a>)</li> 
     <p width="100%">
        <img width="100%" src="https://github.com/Chopin44/Writing-and-Presentation-Test/blob/f176d0e20bf0c8d884a9754c026db4105bae289c/Week%201./css-lat1.png">
    </p>
    <li>Isikan beberapa sintaks berikut</li>
    <p width="100%">
        <img width="100%" src="https://github.com/Chopin44/Writing-and-Presentation-Test/blob/f176d0e20bf0c8d884a9754c026db4105bae289c/Week%201./css-lat2.png">
    </p>
    <li>Panggil CSS ke dalam file Html menggunakan tag link</li>
    <p width="100%">
        <img width="100%" src="https://github.com/Chopin44/Writing-and-Presentation-Test/blob/f176d0e20bf0c8d884a9754c026db4105bae289c/Week%201./css-lat3.png">
    </p>
    <li>Buka file html lewat browser</li>
    <li>Text dengan tag h1 yaitu Hello World akan berubah sesaui property dan value yang diberikan yaitu text yang diberi warna merah</li>
    <p width="100%">
        <img width="100%" src="https://github.com/Chopin44/Writing-and-Presentation-Test/blob/429243a5ffcbaef073d8d154a4f14d10642b66f8/Week%201./css-lat4.png">
    </p>
</ol>

## Javascript Dasar
JavaScript adalah bahasa pemrograman yang digunakan dalam pengembangan website agar lebih dinamis dan interaktif. Kalau sebelumnya kita mengenal HTML dan CSS, yang merupakan kerangka dan komestik dari suatu website sekarang akan ada yang namanya JavaScript, Javascript dapat meningkatkan fungsionalitas pada halaman web. Bahkan dengan JavaScript ini kita bisa membuat aplikasi, tools, atau bahkan game pada web.

JavaScript atau kita singkat menjadi JS merupakan bahasa pemrograman jenis interpreter, sehingga kita tidak memerlukan compiler untuk menjalankannya. JavaScript memiliki fitur-fitur seperti berorientasi objek, client-side, high-level programming, dan loosely typed.

## Cara menjalankan Javacript
Berikut langkah menjalankannya:
1. Kita dapat menjalankan javascript langsung dengan menggunakan browser.
2. Untuk menjalankan Javascript di dalam browser tentunya kita harus memiliki file [HTML](https://github.com/Chopin44/Writing-and-Presentation-Test/edit/main/Week%201./ReadMe.md#exercise) terlebih dahulu.
3. Buatlah file baru berformat js tuliskan beberapa kode berikut:
```
console.log("Hello World")
```
<p width="100%">
        <img width="100%" src="https://github.com/Chopin44/Writing-and-Presentation-Test/blob/a19dab8a6b383a67431e514e80880c766ad1d94a/Week%201./js-1.png">
</p>
4. Sisipkan tag script pada file HTML sepertri berikut untuk memanggil javascript
<p width="100%">
        <img width="100%" src="https://github.com/Chopin44/Writing-and-Presentation-Test/blob/a19dab8a6b383a67431e514e80880c766ad1d94a/Week%201./js-2.png">
</p>
5. atau kalian bisa menuliskannya langsung ke dalam file HTML menggunakan tag script
<p width="100%">
        <img width="100%" src="https://github.com/Chopin44/Writing-and-Presentation-Test/blob/a19dab8a6b383a67431e514e80880c766ad1d94a/Week%201./js-3.png">
</p>
6. Kemudian buka file HTML lewat browser, memang tidak akan menampilkan apa-apa di dalam laman, tetapi kalian bisa melihat hasilnya di dalam console, dengan meng klik kanan mouse dan inspect element, cari bagian console.
<p width="100%">
        <img width="100%" src="https://github.com/Chopin44/Writing-and-Presentation-Test/blob/a19dab8a6b383a67431e514e80880c766ad1d94a/Week%201./js-4.png">
</p>


