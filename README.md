1. Pengertian Bootstrap 
Bootstrap adalah framework CSS open-source yang populer digunakan untuk mengembangkan website yang responsif dan menerapkan pendekatan mobile-first.
Kegunaannya: Bootstrap mempercepat proses pembuatan website karena menyediakan komponen HTML, CSS, dan JavaScript siap pakai, seperti tombol, form, navbar, dan sistem grid. Selain itu, Bootstrap membantu menjaga konsistensi tampilan website di berbagai browser dan ukuran layar perangkat.

2. Memasang Bootstrap 
Ada beberapa cara untuk menggunakan Bootstrap dalam sebuah project, yaitu:
1.	CDN (Content Delivery Network): Menghubungkan file CSS dan JavaScript Bootstrap melalui URL yang disediakan sehingga tidak perlu mengunduh file secara manual.
2.	Download File: Mengunduh file Bootstrap, kemudian menyimpannya di dalam folder project.
3.	Package Manager: Memasang Bootstrap menggunakan package manager seperti npm atau Yarn, biasanya untuk project berbasis Node.js. 
4.	Bundler: Mengintegrasikan Bootstrap ke dalam project menggunakan tools seperti Vite, Webpack, atau Parcel.
   
3. Grid dan Breakpoint 
•	Grid Class: Sistem tata letak Bootstrap yang menggunakan 12 kolom untuk mengatur posisi dan ukuran elemen website. Class utama yang digunakan adalah container, row, dan col.
•	Breakpoint: Batas ukuran lebar layar tertentu yang digunakan untuk menyesuaikan tata letak website agar responsif pada berbagai perangkat. Pada Bootstrap 5, breakpoint terdiri dari sm (≥576px), md (≥768px), lg (≥992px), xl (≥1200px), dan xxl (≥1400px).
Contoh penggunaan: col-12 col-md-6 berarti elemen menggunakan lebar penuh pada layar kecil dan setengah lebar baris mulai dari ukuran layar medium.

4. Class Bootstrap 
Berikut beberapa contoh class Bootstrap beserta kegunaannya:
1.	container: Membungkus konten dan mengatur lebar serta padding secara responsif.
2.	btn btn-success: Membuat tombol dengan tampilan berwarna hijau.
3.	row: Membuat baris untuk menampung kolom dalam sistem grid.
4.	text-center: Mengatur teks agar rata tengah.
5.	shadow: Memberikan efek bayangan pada elemen.
6.	mt-3: Memberikan jarak margin pada bagian atas elemen sesuai skala spacing Bootstrap.
   
5. Gambar Responsif 
Untuk membuat gambar responsif, gunakan class img-fluid pada elemen gambar (<img>). Class ini menerapkan properti CSS max-width: 100% dan height: auto, sehingga gambar dapat menyesuaikan lebar elemen induknya tanpa mengubah proporsi aslinya.
Contoh penggunaan:
<img src="gambar.jpg" class="img-fluid" alt="Contoh gambar">
Dengan menggunakan class img-fluid, gambar dapat menyesuaikan ukuran layar perangkat dan tidak melebihi lebar elemen induknya
