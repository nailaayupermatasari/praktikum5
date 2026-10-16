1.Pengertian Bootstrap

Bootstrap adalah framework CSS *open-source* yang populer digunakan untuk mengembangkan website yang responsif dan menerapkan pendekatan *mobile-first*. Bootstrap berguna untuk mempercepat proses pembuatan website karena menyediakan komponen HTML, CSS, dan JavaScript siap pakai, seperti tombol, form, navbar, dan sistem grid. Selain itu, Bootstrap membantu menjaga konsistensi tampilan website di berbagai browser dan ukuran layar perangkat.

2. Memasang Bootstrap

Ada beberapa cara untuk menggunakan Bootstrap dalam sebuah project. Pertama, menggunakan CDN (*Content Delivery Network*), yaitu menghubungkan file CSS dan JavaScript Bootstrap melalui URL yang disediakan tanpa perlu mengunduh file secara manual. Kedua, mengunduh file Bootstrap dan menyimpannya di dalam folder project. Ketiga, menggunakan *package manager* seperti npm atau Yarn untuk memasang Bootstrap, biasanya pada project berbasis Node.js. Keempat, menggunakan *bundler* seperti Vite, Webpack, atau Parcel untuk mengintegrasikan Bootstrap ke dalam project.

3. Grid dan Breakpoint

Grid adalah sistem tata letak Bootstrap yang menggunakan 12 kolom untuk mengatur posisi dan ukuran elemen website. Class utama yang digunakan dalam sistem grid adalah `container`, `row`, dan `col`. Sementara itu, breakpoint merupakan batas ukuran lebar layar tertentu yang digunakan untuk menyesuaikan tata letak website agar responsif pada berbagai perangkat. Pada Bootstrap 5, breakpoint terdiri dari `sm` (≥576px), `md` (≥768px), `lg` (≥992px), `xl` (≥1200px), dan `xxl` (≥1400px). Contohnya, class `col-12 col-md-6` berarti elemen menggunakan lebar penuh pada layar kecil dan setengah lebar baris mulai dari ukuran layar medium.

4. Class Bootstrap

Bootstrap menyediakan berbagai class yang dapat digunakan untuk mengatur tampilan website. Class `container` berfungsi membungkus konten serta mengatur lebar dan padding secara responsif. Class `btn btn-success` digunakan untuk membuat tombol berwarna hijau, sedangkan class `row` digunakan untuk membuat baris yang menampung kolom dalam sistem grid. Class `text-center` berfungsi mengatur teks agar rata tengah, class `shadow` memberikan efek bayangan pada elemen, dan class `mt-3` memberikan jarak margin pada bagian atas elemen sesuai skala spacing Bootstrap.

5. Gambar Responsif

Untuk membuat gambar responsif, gunakan class `img-fluid` pada elemen gambar (`<img>`). Class ini menerapkan properti CSS `max-width: 100%` dan `height: auto`, sehingga gambar dapat menyesuaikan lebar elemen induknya tanpa mengubah proporsi aslinya. Contoh penggunaannya adalah `<img src="gambar.jpg" class="img-fluid" alt="Contoh gambar">`. Dengan menggunakan class `img-fluid`, gambar dapat menyesuaikan ukuran layar perangkat dan tidak melebihi lebar elemen induknya.
