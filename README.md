# 1.1 Latar Belakang
With my background as a fast food trader in a 2-month job selling kebabs, burgers, and hotdogs, I have gained experience and understanding of the challenges and needs in the fast food industry. This experience has benefited me especially in stock management, customer management, and effective marketing strategies.Dengan latar belakang saya, pernah menjadi pedagang makanan cepat saji yang dalam menjalankan pekerjaan penjualan kebab, burger, dan hotdog selama 2 bulan an, saya telah mendapatkan pengalaman dan pemahaman tentang tantangan dan kebutuhan dalam industri makanan cepat saji. Pengalaman ini memberi maanfaat untuk saya terutama dalam manajemen stok, pengelolaan pelanggan, dan strategi pemasaran yang efektif.
# 1.2 Deskripsi
I plan to develop an innovative information technology solution designed to optimise the operations of fast food merchants. Our platform will include various features, including:

-A sophisticated tool to monitor and manage inventory of ingredients and equipment.

-To provide deep insights into sales trends and overall business performance.

-I as a merchant want to build better relationships with customers and provide a more personalised experience.

-I want to Increase the effectiveness of product promotion and reach new customers.

Saya berencana untuk mengembangkan sebuah solusi teknologi informasi inovatif yang dirancang untuk mengoptimalkan operasional pedagang makanan cepat saji. Platform kami akan mencakup berbagai fitur, termasuk:

-Sebuah alat yang canggih untuk memantau dan mengelola persediaan bahan makanan dan peralatan.

-Untuk menyediakan wawasan mendalam tentang tren penjualan dan performa bisnis secara keseluruhan.

-Saya sebagai pedagang ingin membangun hubungan yang lebih baik dengan pelanggan dan menyediakan pengalaman yang lebih personal.
-Saya ingin Meningkatkan efektivitas promosi produk dan meraih pelanggan baru.
# 1.3 Branding
- merk : A flash (Acoy Flavor Dash)
- Tagline : "Flavor Perfected through Digital Fusion,Cita Rasa yang Disempurnakan melalui Fusi Digital"
- campaign :tempat untuk orang membeli burger,kebab, dan hotdog melalui teknologi informasi
- Target user :
   - orang yang ingin membeli burger
- User experience theme:
   - sederhana
   - warna : dominan warna hitam, warna putih dan cream

# 2. User Story

sebagai | saya ingin bisa | sehingga | prioritas
---|---|---|---
masyarakat | membuat laporan pengaduan | bisa kejadian/keadaan di desanya | ⭐⭐⭐⭐⭐
masyarakat | melihat laporan yang saya buat | bisa mengingat laporan yang saya buat | ⭐⭐⭐⭐
# 3. Struktur Data

mermaid
erDiagram
    masyarakat ||--o{ pengaduan : membuat
    masyarakat {
        char nik
        varchar nama
        varchar username
        varchar password
        varchar telp
    }
    pengaduan ||--|{ petugas : terkirim
    pengaduan {
        bigint id_pengaduan
        datetime tgl_pengaduan
        char nik
        text isi_laporan
        varchar foto
        enum status
    }
    petugas ||--|{ tanggapan : menanggapi
    petugas {
        bigint id_petugas
        varchar nama_petugas
        varchar username
        varchar password
        varchar telp
        enum level
    }
    tanggapan {
        bigint id_tanggapan
        bigint id_pengaduan
        datetime tgl_tanggapan
        text tanggapan
        bigint id_petugas
}

## 4 Arsitektur Sistem
mermaid
flowchart TD
    id1[(Database: MySQL)] <--> id2[Aplikasi Web Backend: Laravel] <--> id3[Web Server: Laravel]  

# 5. Teknologi, Library, dan Framework

Untuk teknologi saya menggunakan Visual Studio Code Sedangkan dalam pemrograman saya menggunakan Framework Laravel
# 6. Desain User Experience dan User Interface

## Design UI & UX Menggunakan Figma
### Link Figma
> https://www.figma.com/file/yq2L28KRVuFQePBRRs0U4i/pekat?type=design&node-id=0%3A1&mode=design&t=HHtm69bUVSGFYLqu-1
- *Landing Page*
- ![landing](https://github.com/fauzanzianulhaq/pengenalan-informatika/assets/115859323/0df17eca-61e4-459e-96c2-23aaf277cb2f)
- *Halaman Login Petugas*
- ![masuk petugas](https://github.com/fauzanzianulhaq/pengenalan-informatika/assets/115859323/9bff21cf-91d4-4c88-92d8-330fb4027e0c)
- ** Halaman Daftar**
- ![daftar masyarakat](https://github.com/fauzanzianulhaq/pengenalan-informatika/assets/115859323/69ce0793-cd66-4bc6-9fee-4001ecf12aa8)
## 7. Demonstrasi Video

Link youtube nya

## 8. Bagaimana mesin komputasi dan sistem operasi berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 9. Bagaimana algoritma, struktur data, dan bahasa pemrograman berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 10. Bagaimana metode pengembangan perangkat lunak / Software Development Life Cycle berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 11. Bagaimana database / sistem basis data berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini# Interview.pengenalaninformatika
