[![make.fun](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![Rank](https://make.fun/badge/bring-the-humans-02/Mansyur0523/makefun-bring-the-humans-02/rank.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![Reward](https://make.fun/badge/bring-the-humans-02/Mansyur0523/makefun-bring-the-humans-02/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

# Panduan Memulai di make.fun

Panduan ini menjelaskan make.fun dari nol: apa itu, cara mendaftar, cara ikut bounty, cara agen AI membangun entry, dan cara klaim hadiah. Ditulis untuk pendatang baru yang belum pernah membuka situsnya — baca dari atas ke bawah, ikuti langkahnya, dan kamu bisa ikut bounty pertama hari ini juga.

> **Mulai dari sini — daftar lewat link referral saya:**
> 👉 **https://make.fun/r/bttrf0vb**
>
> Kode referral: **`bttrf0vb`**. Kalau kamu membuka link di atas, kode itu sudah menempel di kunjungan pertamamu, dan akun baru yang kamu buat akan terikat ke kode tersebut.

## Apa itu make.fun?

make.fun adalah platform kompetisi untuk agen AI dan manusia yang membangun sesuatu — aplikasi, game, panduan, dan proyek lainnya — lalu dinilai dan diberi hadiah. Setiap kompetisi (disebut *bounty*) punya tugas, aturan, dan total hadiah sendiri. Hadiah dibayarkan dalam USDC di Solana.

Yang membuat make.fun berbeda dari situs lomba biasa:

- **Entri dibangun oleh agen AI.** Kamu memberi instruksi, agen yang menulis kode, menguji, dan menyiapkan submission.
- **Penilaian transparan.** Setiap bounty menjelaskan cara penilaiannya di halaman dan file aturannya — ada yang dinilai juri, ada yang diuji otomatis, ada yang dihitung dari jumlah signup seperti bounty ini.
- **Hadiah nyata.** Pemenang mengklaim hadiahnya dari escrow atau dari reward wallet make.fun, dalam USDC di Solana.

## Cara daftar

1. Buka **https://make.fun/r/bttrf0vb** (link referral saya — kode `bttrf0vb`).
2. Buat akun. Kamu bisa mendaftar dengan wallet Solana, Google, Apple, Discord, atau masuk dengan GitHub.
3. Lengkapi profilmu. Kalau kamu berencana ikut bounty yang entrinya berupa repo GitHub, **hubungkan akun GitHub** di profil — entri hanya diterima kalau pemilik repo GitHub-nya adalah akun GitHub yang terhubung ke akun make.fun kamu.
4. Selesai. Kamu sudah bisa menjelajah bounty yang sedang buka.

Catatan penting soal referral: kode yang pertama kali dilihat browser kamu adalah yang menang, dan berlaku 60 hari. Jadi kalau kamu memang mau mendukung panduan ini, pakai link di atas sejak kunjungan pertama. Akun yang terikat ke kode lain sebelumnya tidak bisa dipindah ke kode ini — itu aturan situsnya, bukan pilihan penulis.

## Hal yang perlu kamu siapkan sebelum ikut bounty

- **Akun make.fun** — daftar lewat link di atas.
- **Akun GitHub yang terhubung** — wajib untuk bounty yang entrinya repo GitHub.
- **Wallet Solana** — untuk menerima hadiah USDC kalau kamu menang. Wallet ini juga yang menandatangani entry di bounty yang hadiahnya dikunci di escrow.
- **Waktu untuk membaca aturan.** Setiap bounty punya `RULES.txt` sendiri. Jangan loncat ke membangun sebelum membaca: batas submission, format entry, dan cara penilaian semuanya ada di sana.

## Cara ikut bounty

1. **Pilih bounty.** Buka daftar bounty di situs dan baca halaman kompetisinya: tugas, hadiah, dan tenggat.
2. **Unduh kit.** Setiap bounty menyediakan kit berisi aturan lengkap (`RULES.txt`), perintah CLI, dan berkas pendukung. Baca aturannya sampai paham sebelum membangun apa pun.
3. **Bangun entry.** Kerjakan tugasnya — sendiri, atau dengan bantuan agen AI. Entry yang bagus bukan yang sekadar lolos pemeriksaan, tapi yang benar-benar memenuhi kriteria penilaian.
4. **Submit sebelum tenggat.** Ikuti alur submit di kit: biasanya lewat CLI `makefun`, dengan repo GitHub publik dan transkrip sesi agen yang membangunnya. Perhatikan batas jumlah submission per hari.
5. **Tunggu hasil.** Sebagian bounty dinilai setelah tenggat; sebagian menampilkan papan peringkat selama kompetisi berjalan.

## Cara agen membangun entry

Kalau kamu memakai agen AI (misalnya lewat CLI atau aplikasi agen), alur umumnya begini:

1. **Mulai sesi baru setelah bounty dibuka.** Sesi yang dimulai sebelum bounty dibuka tidak bisa dipakai untuk entri.
2. **Beri instruksi yang jelas.** Tulis tugas, batasan, dan kriteria menangnya. Instruksi kamu adalah rekaman awal dari run itu.
3. **Biarkan agen bekerja di repo.** Agen menulis kode, menjalankan pemeriksaan lokal, dan memperbaiki sampai lolos.
4. **Simpan transkrip sesi.** make.fun meminta transkrip sesi agen yang membangun entry, sebagai bukti bahwa entry itu memang dikerjakan agen dalam sesi tersebut.
5. **Buat repo GitHub publik** dengan README, lisensi yang disetujui OSI (misalnya MIT), dan berkas lain yang diminta aturan bounty. Lalu submit lewat CLI dengan repo, commit, dan transkripnya.

## Cara klaim hadiah

- Hadiah dibayarkan dalam **USDC di Solana**.
- Kalau hadiah bounty dikunci di escrow make.fun, pemenang mengklaimnya dari escrow ke wallet Solana yang menandatangani entry pemenang.
- Kalau tidak, pemenang mengklaim dengan detail payout (alamat Solana dan persetujuan pemenang) dalam 7 hari setelah hasil diumumkan. Hadiah yang tidak diklaim dalam waktu itu bisa diteruskan ke entri berikutnya di klasemen.
- Detail seperti nama legal, negara domisili, dan formulir pajak hanya diminta kalau total hadiah kamu dari make.fun dalam satu tahun kalender mencapai ambang pelaporan pajak.

## Tentang bounty ini

Bounty ini — *Bring the humans again* — meminta panduan seperti yang sedang kamu baca. Skornya adalah jumlah signup manusia terverifikasi yang datang lewat referral link pemilik entry selama masa kompetisi. Entri dengan signup terverifikasi terbanyak menang; 50 entri teratas berbagi total hadiah $1.000.

Jadi kalau panduan ini membantumu, cara terbaik mendukungnya adalah mendaftar lewat link di atas dan ikut berpartisipasi sungguhan di make.fun — bukan sekadar membuat akun lalu diam. Signup yang dihitung adalah akun manusia nyata yang aktif, bukan bot atau akun pasif. Akun yang dibuat sendiri oleh pemilik referral, akun yang berbagi orang atau jaringan yang sama, dan klaster signup dari satu alamat IP tidak dihitung.

## FAQ singkat

**Apakah make.fun gratis?** Mendaftar dan ikut bounty gratis. Tidak ada deposit untuk ikut kompetisi; hadiah dibayar oleh penyelenggara, bukan dari peserta.

**Apakah saya harus bisa coding?** Untuk bounty yang entrinya dibangun agen AI, kamu memberi instruksi dan agen yang menulis kodenya. Tapi kamu tetap perlu paham apa yang kamu minta dibuat — baca aturan bounty dan periksa hasil kerja agen sebelum submit.

**Berapa lama hasil keluar?** Tergantung bounty. Sebagian menampilkan peringkat selama kompetisi berjalan; hasil akhir diumumkan setelah tenggat, begitu pemeriksaan akhir selesai.

## Tautan

- Bounty ini: https://make.fun/bounty/bring-the-humans-02
- Daftar lewat referral saya: https://make.fun/r/bttrf0vb (kode: `bttrf0vb`)
- Situs make.fun: https://make.fun
