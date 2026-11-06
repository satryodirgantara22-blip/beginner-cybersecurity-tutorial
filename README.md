# Cybersecurity untuk Pemula

Panduan belajar keamanan siber dari dasar, dengan fokus pada perlindungan, pemahaman risiko, dan latihan yang aman. Repositori ini terinspirasi oleh format koleksi sumber belajar seperti [Cybersecurity-Indonesia](https://github.com/screetsec/Cybersecurity-Indonesia), tetapi menyajikan materi yang disusun sebagai roadmap pemula dan menekankan praktik defensif.

> **Etika dan keselamatan:** Pelajari dan uji hanya perangkat, akun, jaringan, dan laboratorium yang Anda miliki atau yang secara jelas memberi izin. Jangan memindai, menguji, atau mencoba mengakses sistem orang lain tanpa izin. Materi di sini untuk edukasi dan pertahanan.

## Daftar Isi

- [Mulai di sini](#mulai-di-sini)
- [Roadmap belajar](#roadmap-belajar)
- [Keamanan akun dan perangkat](#keamanan-akun-dan-perangkat)
- [Jaringan dan internet](#jaringan-dan-internet)
- [Keamanan web—dasar](#keamanan-webdasar)
- [Blue team dan respons insiden](#blue-team-dan-respons-insiden)
- [Latihan yang aman](#latihan-yang-aman)
- [Glosarium singkat](#glosarium-singkat)
- [Kontribusi](#kontribusi)

## Mulai di sini

Jika Anda baru mulai, ikuti urutan ini:

1. Pelajari konsep dasar: aset, ancaman, kerentanan, risiko, dan kontrol keamanan.
2. Amankan akun pribadi: gunakan kata sandi unik, pengelola kata sandi, dan autentikasi multifaktor (MFA).
3. Perbarui perangkat lunak, aktifkan kunci layar, dan siapkan cadangan data.
4. Pelajari dasar jaringan dan cara kerja web.
5. Pahami bagaimana organisasi mencegah, mendeteksi, dan merespons insiden.
6. Berlatih hanya di lab yang memang dibuat untuk latihan dan ikuti ketentuannya.

Tidak perlu langsung mengunduh alat keamanan atau mencoba menguji situs publik. Fondasi dan kebiasaan aman lebih penting.

## Roadmap belajar

### Tahap 1 — Fondasi keamanan

Pahami tujuan kerahasiaan, integritas, dan ketersediaan (CIA); identifikasi aset dan risiko; serta kenali rekayasa sosial, phishing, dan kebiasaan keamanan yang baik.

- [CISA: Secure Our World](https://www.cisa.gov/secure-our-world) — kebiasaan dasar keamanan digital.
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework) — kerangka untuk memahami dan mengelola risiko keamanan.
- **Latihan:** Buat daftar akun penting Anda, aktifkan MFA, periksa metode pemulihan, dan ganti kata sandi yang dipakai ulang.

### Tahap 2 — Sistem operasi dan jaringan

Pelajari file, izin akses, proses, pembaruan, alamat IP, DNS, router, dan perbedaan jaringan lokal dengan internet. Mulailah dari dokumentasi sistem yang Anda gunakan.

- [Cloudflare Learning Center](https://www.cloudflare.com/learning/) — penjelasan konsep internet dan jaringan.
- [Cisco Networking Basics](https://www.netacad.com/courses/networking-basics) — materi pengantar jaringan.
- **Latihan:** Gambar peta sederhana perangkat di jaringan rumah Anda. Jangan menguji perangkat pihak lain.

### Tahap 3 — Keamanan web

Pelajari peran browser dan server, HTTPS, sesi, autentikasi, otorisasi, validasi masukan, dan prinsip hak akses minimum. Fokus pada cara mencegah masalah dan mengenali dampaknya.

- [OWASP Top 10](https://owasp.org/www-project-top-ten/) — gambaran risiko keamanan aplikasi web yang umum.
- [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/) — panduan mitigasi untuk pengembang dan tim keamanan.
- **Latihan:** Tinjau aplikasi milik Anda atau contoh lokal, lalu tulis daftar kontrol defensif yang digunakan—misalnya pembaruan dependensi, autentikasi aman, dan pembatasan akses.

### Tahap 4 — Blue team dan respons insiden

Blue team berfokus pada perlindungan, pemantauan, deteksi, dan pemulihan. Pahami log, peringatan, pencadangan, inventaris aset, dan alur pelaporan insiden.

- [CISA: Incident Response](https://www.cisa.gov/topics/cyber-threats-and-advisories/incident-detection-response) — informasi deteksi dan respons insiden.
- [NIST Computer Security Incident Handling Guide (SP 800-61)](https://csrc.nist.gov/pubs/sp/800/61/r2/final) — panduan penanganan insiden.
- **Latihan:** Susun checklist sederhana: siapa yang dihubungi, perangkat mana yang perlu diamankan, dan bagaimana memulihkan data dari cadangan.

### Tahap 5 — Pilih spesialisasi

Setelah fondasi, jelajahi bidang seperti keamanan aplikasi, keamanan cloud, tata kelola dan risiko, forensik digital, atau operasi keamanan. Pelajari persyaratan peran dan gunakan sumber resmi serta lab berizin.

## Keamanan akun dan perangkat

- Gunakan kata sandi panjang dan berbeda untuk setiap akun; simpan dengan pengelola kata sandi tepercaya.
- Aktifkan MFA, terutama pada email, penyimpanan awan, media sosial, dan akun keuangan.
- Jangan pernah membagikan kode verifikasi atau menyetujui permintaan masuk yang tidak Anda mulai.
- Pasang pembaruan otomatis untuk sistem operasi, browser, dan aplikasi.
- Aktifkan kunci layar dan pencadangan rutin; uji bahwa cadangan dapat dipulihkan.
- Waspadai pesan mendesak, lampiran tak terduga, alamat pengirim yang tidak cocok, dan tautan mencurigakan. Buka situs melalui aplikasi atau alamat yang Anda ketik sendiri.
- Di Wi-Fi publik, hindari tindakan sensitif bila tidak yakin dengan koneksinya; gunakan koneksi seluler jika lebih aman.

## Jaringan dan internet

Konsep yang berguna dipelajari: IP address, DNS, router, port, protokol, HTTP/HTTPS, enkripsi, dan firewall. Tujuannya adalah memahami bagaimana komunikasi berlangsung dan bagaimana konfigurasi defensif melindunginya—bukan mencoba masuk ke jaringan tanpa izin.

## Keamanan web—dasar

Keamanan aplikasi web meliputi desain, implementasi, konfigurasi, dan pemeliharaan yang aman. Sebagai pemula, pelajari cara mengurangi risiko:

- Terapkan autentikasi dan pemeriksaan otorisasi di sisi server.
- Batasi hak akses sesuai kebutuhan.
- Validasi data dan gunakan API basis data yang aman.
- Lindungi sesi dan data sensitif dengan konfigurasi yang sesuai.
- Perbarui dependensi dan tinjau perubahan sebelum rilis.
- Laporkan kelemahan secara bertanggung jawab kepada pemilik sistem.

Gunakan materi OWASP sebagai pengantar dan praktikkan hanya pada aplikasi lokal atau lab yang secara eksplisit mengizinkan latihan.

## Blue team dan respons insiden

Kebiasaan defensif yang dapat dipraktikkan:

- Catat aset penting dan pemiliknya.
- Aktifkan pencatatan log yang relevan dan lindungi akses ke log.
- Tinjau peringatan keamanan melalui prosedur yang disetujui.
- Siapkan rencana respons dan jalur eskalasi sebelum insiden terjadi.
- Simpan cadangan terpisah dan uji pemulihannya.
- Jika menemukan insiden, ikuti prosedur organisasi; jangan menghapus bukti atau mencoba menyelidiki sistem di luar wewenang Anda.

## Latihan yang aman

- Amankan akun dan perangkat milik sendiri menggunakan checklist di atas.
- Gunakan lab edukasi yang sengaja dibuat untuk latihan, baca aturan dan batas cakupannya, dan jangan hubungkan lab rentan ke jaringan atau data penting.
- Catat tujuan, lingkungan, izin, dan hasil pembelajaran sebelum latihan.
- Jangan memindai atau menguji alamat IP, domain, aplikasi, atau akun pihak lain tanpa izin tertulis yang jelas.
- Jika menemukan kelemahan secara tidak sengaja, hentikan pengujian dan laporkan melalui kanal resmi pemilik sistem.

## Glosarium singkat

- **Aset:** data, perangkat, layanan, atau hal lain yang perlu dilindungi.
- **Ancaman:** sesuatu yang berpotensi menyebabkan kerugian.
- **Kerentanan:** kelemahan yang dapat dimanfaatkan atau menyebabkan kegagalan keamanan.
- **Risiko:** kemungkinan dan dampak dari suatu kejadian keamanan.
- **MFA:** autentikasi multifaktor; login menggunakan lebih dari satu bukti identitas.
- **Blue team:** peran atau tim yang berfokus pada pertahanan dan deteksi.
- **Responsible disclosure:** pelaporan kelemahan secara privat dan bertanggung jawab kepada pemilik sistem.

## Kontribusi

Kontribusi berupa perbaikan ejaan, penjelasan yang lebih ramah pemula, dan tautan ke sumber tepercaya dipersilakan. Sebelum mengirim perubahan:

1. Pastikan sumbernya relevan, dapat diakses, dan aman untuk pemula.
2. Jelaskan apakah materi berbahasa Indonesia atau Inggris.
3. Jangan menambahkan instruksi untuk menyerang sistem nyata, mencuri data, menghindari deteksi, atau mengakses tanpa izin.
4. Sertakan konteks dan batasan keselamatan untuk materi praktik.

---

Materi ini adalah titik awal belajar, bukan pengganti kebijakan keamanan organisasi, nasihat profesional, atau izin eksplisit untuk menguji sistem.
