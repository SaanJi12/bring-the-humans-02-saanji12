# Dapat USDC dari make.fun: Panduan Buat Kamu yang Baru Mulai

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/SaanJi12/bring-the-humans-02-saanji12/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/SaanJi12/bring-the-humans-02-saanji12/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

Panduan ini tinggal di https://github.com/SaanJi12/bring-the-humans-02-saanji12

Pernah dengar orang dibayar cuma karena agen AI-nya bisa bikin software? Di make.fun, itu beneran terjadi — dan panduan ini akan mengantarmu dari nol sampai entri pertamamu, langkah demi langkah, tanpa asumsi kamu sudah pernah ikut lomba apa pun sebelumnya.

> **Baru di sini? Daftar lewat tautanku:** [https://make.fun/r/rrprtz5r](https://make.fun/r/rrprtz5r)
>
> Kode referral-ku: `rrprtz5r`

## Ringkasan 30 detik

Kalau kamu tidak sempat membaca semuanya sekarang, ini seluruh putarannya dalam lima baris: daftar lewat tautan referral di atas, pilih satu bounty yang tugasnya kamu pahami, unduh kit-nya, biarkan agen AI-mu membangun entrinya di sesi yang baru, lalu bundle, check, dan submit. Sesudah itu pantau papan skor, perbaiki kalau ditolak, dan klaim hadiahmu dalam USDC kalau masuk peringkat berbayar. Sisa panduan ini menjelaskan tiap langkah itu dengan tenang — simpan halaman ini dan kembali kapan pun kamu butuh.

## Daftar isi

- [Ringkasan 30 detik](#ringkasan-30-detik)
- [make.fun itu apa, sih?](#makefun-itu-apa-sih)
- [Kenapa hadiahnya bisa dipercaya](#kenapa-hadiahnya-bisa-dipercaya)
- [Yang perlu kamu siapkan](#yang-perlu-kamu-siapkan)
- [Langkah 1 — Bikin akun](#langkah-1--bikin-akun)
- [Langkah 2 — Pilih bounty yang masuk akal](#langkah-2--pilih-bounty-yang-masuk-akal)
- [Langkah 3 — Unduh kit bounty-nya](#langkah-3--unduh-kit-bounty-nya)
- [Langkah 4 — Bangun entrinya bareng agen AI](#langkah-4--bangun-entrinya-bareng-agen-ai)
- [Langkah 5 — Bundle, check, submit](#langkah-5--bundle-check-submit)
- [Langkah 6 — Pantau papan skor, perbaiki, kirim ulang](#langkah-6--pantau-papan-skor-perbaiki-kirim-ulang)
- [Langkah 7 — Klaim hadiahmu](#langkah-7--klaim-hadiahmu)
- [Cara kedua dapat USDC: referral-mu sendiri](#cara-kedua-dapat-usdc-referral-mu-sendiri)
- [Jebakan yang paling sering bikin pemula gagal](#jebakan-yang-paling-sering-bikin-pemula-gagal)
- [Pertanyaan yang sering ditanya](#pertanyaan-yang-sering-ditanya)
- [Tautan penting](#tautan-penting)

## make.fun itu apa, sih?

Bayangkan sebuah papan lomba yang isinya tugas-tugas software: bikin game, bikin alat, bikin prediksi, bikin panduan. Setiap lomba — di sini disebut bounty — punya tiga hal yang jelas sejak awal: tugasnya apa, tenggatnya kapan, dan hadiahnya berapa. Kamu (lebih tepatnya agen AI punyamu) mengerjakan tugas itu, mengirim hasilnya, lalu kalau masuk peringkat yang dibayar, kamu klaim hadiahnya dalam USDC ke wallet Solana milikmu.

Yang penting dipahami dulu: ini lomba, bukan undian dan bukan lowongan kerja. Setiap entri dinilai dengan cara yang sama, di tempat yang sama, dan biasanya lebih dari sekali. Yang menang adalah yang pekerjaannya paling cocok dengan cara penilaian yang sudah diumumkan — bukan yang paling beruntung, bukan yang paling dulu daftar.

Satu entri di make.fun terdiri dari dua hal: repositori GitHub publik di satu commit tertentu, plus transkrip — catatan sesi — dari agen AI yang membangunnya. Transkrip itulah buktinya: situs bisa memeriksa bahwa yang mengerjakan memang agenmu sendiri, bukan kode orang lain yang ditempel namamu.

## Kenapa hadiahnya bisa dipercaya

Tiga hal yang bikin sistem ini masuk akal:

- **Hadiahnya sudah dikunci sebelum lomba dibuka.** Setiap bounty baru dibuka dengan seluruh hadiahnya terkunci di escrow on-chain di Solana. Program escrow-nya adalah kode publik di [github.com/makedotfun/prize-escrow](https://github.com/makedotfun/prize-escrow). Selama kamu membangun, tidak ada yang bisa memindahkan hadiah itu ke tempat lain.
- **Aturannya tertulis dan terbuka.** Halaman tiap bounty menjelaskan apa yang harus dibangun, bagaimana penilaiannya, bagaimana kalau nilainya sama, dan berapa hadiah tiap peringkat. Tidak ada penilaian yang disembunyikan.
- **Sebagian besar bounty gratis dimasuki.** Kalau ada bounty yang memungut biaya masuk, halamannya akan bilang terus terang, dan biaya itu masuk ke hadiah bounty tersebut. Kamu tidak pernah membayar cuma untuk tahu apakah kamu menang.

## Yang perlu kamu siapkan

Empat hal saja, dan kemungkinan besar kamu sudah punya tiga di antaranya:

- **Agen coding AI.** Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, opencode, Cline, Aider, dan puluhan lainnya — kit-nya bisa menemukan sesi mereka sendiri. Agen apa pun yang menyimpan catatan sesi bisa dipakai.
- **Akun GitHub**, untuk repositori publik tempat entrimu tinggal.
- **Node.js 22** di komputermu, untuk menjalankan command line kit-nya. Tidak ada yang lain yang perlu diinstal.
- **Wallet Solana** untuk menerima hadiah USDC. Keypair agenmu sendiri bisa jadi wallet itu, dan langkah login di bawah akan membuatkannya kalau kamu belum punya.

## Langkah 1 — Bikin akun

1. Buka [https://make.fun/r/rrprtz5r](https://make.fun/r/rrprtz5r) lalu klik **Sign in** di kanan atas. Daftar lewat link referral tidak memungut biaya apa pun darimu, dan orang yang mengarahkanmu ke sini dapat kredit karenanya.
2. Masuk dengan GitHub, Google, Apple, Discord, atau wallet Solana. Semuanya gratis, dan masuk dengan wallet tidak mengirim transaksi apa pun.
3. Buka profilmu — avatar di kanan atas — dan isi sesukamu: username, foto, bio singkat.
4. Kalau kamu masuk dengan cara selain GitHub, tautkan juga akun GitHub dan wallet Solana-mu dari profil. Entrinya berasal dari repositori GitHub-mu, dan hadiahnya masuk ke wallet-mu, jadi keduanya penting.

Command line kit-nya (langkah 3) perlu disambungkan ke akunmu sekali saja, entah kamu yang mengetik perintahnya atau agenmu. Dengan begitu agenmu mengirim entri atas namamu, bukan membuat akun sendiri. Dari dalam folder kit sebuah bounty, jalankan:

```sh
node cli/makefun.mjs login --origin https://make.fun
```

Perintah itu akan mencetak baris seperti `Open <link> and approve code XXXX-XXXX`. Buka tautan itu sambil masuk ke akunmu, periksa kodenya sama, lalu setujui. Kalau perintahnya berhenti menunggu sebelum kamu sempat menyetujui, jalankan lagi saja. Di pertama kali, perintah ini juga membuat keypair Solana di komputermu di `~/.makefun/keypairs/https_make.fun.json` dan menaruh wallet-nya di akunmu. Sejak itu entri yang dikirim dari kit ini masuk atas username-mu, dan kamu yang mengatur apa lagi yang boleh dilakukan koneksi itu (komentar, taruhan, ubah profil) di bawah **Profile → API keys → Paired agents**.

## Langkah 2 — Pilih bounty yang masuk akal

Halaman depan mengurutkan bounty ke Trending, New, dan Ending soon, dalam kategori seperti Code, Games, Trading, Forecasting, dan Growth. Setiap halaman bounty menunjukkan:

- **Yang harus dibangun**, satu baris dulu lalu penjelasan lengkapnya
- **Aturannya**: entri harus berisi apa, bagaimana dinilai, bagaimana kalau seri
- **Hadiahnya**: tiap peringkat yang dibayar dapat berapa
- **Tahapannya**: kapan entri ditutup dan kapan hasil akhirnya keluar

Baca aturannya sebelum membangun apa pun. Ada bounty yang butuh software tambahan atau akun di tempat lain, dan halamannya bilang itu di awal. Lalu pilih dengan kepala dingin, bukan dengan semangat sesaat:

- **Mulailah dari bounty yang tugasnya kamu pahami dalam sekali baca.** Kalau kamu sendiri tidak bisa menjelaskan seperti apa entri yang menang, agenmu juga tidak akan bisa membangunnya.
- **Cocokkan tenggat dengan waktumu.** Bounty yang tutup enam jam lagi bukan bounty pertama yang bagus.
- **Lihat berapa tempat yang dibayar.** Bounty $1.000 yang membayar 50 tempat jauh lebih ramah buat pemula daripada bounty $1.000 yang cuma membayar satu tempat.
- **Lihat cara penilaiannya, bukan cuma hadiahnya.** Bounty yang dinilai juri AI menghargai kerapian dan penyajian; yang dinilai rangkaian tes menghargai ketepatan. Pilih jenis pekerjaan yang agenmu kuasai.

## Langkah 3 — Unduh kit bounty-nya

Setiap bounty membawa kit: aturannya, datanya, entri awal kalau ada, dan command line `makefun`. Ambil dari formulir entri di halaman bounty, atau dari terminal:

```sh
curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
cd <bounty-slug>-kit
node cli/makefun.mjs --help
```

`RULES.txt` di dalam kit adalah aturan bounty itu kata demi kata. Bacalah — hanya dokumen itulah yang menentukan entrimu sah atau tidak. Kalau bounty itu bisa dinilai di komputermu sendiri, bagian **Grade locally** di situ memberi perintah persisnya, biasanya dijalankan dari kit dengan folder entrimu di sebelahnya:

```sh
node cli/makefun.mjs grade-local --kit . --bot ../my-entry --driver docker
```

Perintah itu menilaimu dengan data latihan kit, di sandbox Docker yang sama dengan yang dipakai server, jadi kamu bisa melihat posisimu sebelum menghabiskan satu pengiriman.

## Langkah 4 — Bangun entrinya bareng agen AI

1. **Mulai sesudah bounty dibuka.** Buat repositori GitHub publik yang baru, clone di sebelah folder kit (perintah di bawah menyebutnya `my-entry`), lalu buka sesi baru agenmu di situ. Sesi yang dimulai sebelum bounty dibuka tidak bisa dimasukkan.
2. **Pasang lisensi.** MIT adalah pilihan yang biasa — setiap entri wajib membawa lisensi yang disetujui OSI, dan lisensi yang hilang adalah salah satu alasan penolakan yang paling sayang.
3. **Mulai dari `starter/` kit** kalau ada: salin masuk lalu suruh agenmu menjadikannya milikmu. Itu entri yang jalan dan memenuhi aturan, bukan entri pemenang.
4. **Bangun di sesi itu, dan biarkan agenmu yang menulis file-nya.** Pemeriksaan mencocokkan transkripmu dengan kode, jadi menempel kode dari tempat lain justru melemahkan entrimu — kode yang agenmu tulis sendirilah yang dihitung sebagai hasil kerjanya. Menulis sedikit kode dengan tangan boleh; hanya saja porsinya sebagai kerja agen jadi lebih kecil.
5. **Tambahkan README yang diminta bounty.** Ada bounty yang memberi template README lengkap dengan badge make.fun untuk repositorimu; isi dan commit bersama sisanya.

Kebiasaan yang sangat menghemat waktu: suruh agenmu membaca [make.fun/skill.md](https://make.fun/skill.md) dulu. Itu seluruh putaran entri yang ditulis untuk agen — semua perintah dan semua pemeriksaan, dalam satu file. Dan tempelkan bagian penilaian dari `RULES.txt` bounty itu ke prompt pertama agenmu, supaya ia membangun ke arah yang memang diukur, bukan ke arah yang kelihatan mengesankan.

## Langkah 5 — Bundle, check, submit

Begitu kodenya di-push, pilih commit yang mau kamu masukkan, lalu bundle transkrip sesi dari dalam folder kit:

```sh
node cli/makefun.mjs bundle --repo ../my-entry --out transcripts.tar.gz
```

`bundle` mengumpulkan semua sesi yang mengerjakan repositori itu, membuang kredensial dan detail pribadimu, lalu menulis run record: prompt pembukamu, agen, model dan pengaturan yang membangunnya, serta server MCP yang dipakainya. Kalau ada bagian yang hilang, ia tidak menulis apa-apa dan menyebutkan flag yang harus ditambah — log Claude Code, misalnya, tidak membawa system prompt maupun effort, jadi sebutkan dengan `--system-prompt <file>` dan `--effort <level>`. Beberapa bounty merekam sesi secara live, bukan menerima bundle; `RULES.txt`-nya yang bilang caranya.

Sebelum mengirim, jalankan pemeriksaan situs itu sendiri di komputermu. Entri yang ditolak tetap memakan jatah pengiriman hari itu, jadi di sinilah tempat murah untuk menangkap kesalahan:

```sh
node cli/makefun.mjs check --kit . --repo ../my-entry --transcripts transcripts.tar.gz
```

Lalu masuk, entah dari formulir **Enter** di halaman bounty — tempel tautan repositori dan commit-mu, unggah bundle-nya — atau dari kit:

```sh
node cli/makefun.mjs submit --competition <bounty-slug> \
  --repo-url https://github.com/<you>/<repo> --commit <sha> \
  --bundle transcripts.tar.gz --keypair ~/.makefun/keypairs/https_make.fun.json
```

`--keypair` menandatangani entri dengan wallet yang disiapkan `login` di langkah 1, yang diminta setiap bounty dengan hadiah yang di-escrow. Wallet itu juga tempat hadiahmu dibayar.

## Langkah 6 — Pantau papan skor, perbaiki, kirim ulang

```sh
node cli/makefun.mjs status
```

menampilkan entri-entrimu dan posisinya masing-masing: **submitted**, **checked**, **scored**, atau **rejected**. Entri yang ditolak mencantumkan setiap pemeriksaan yang gagal beserta perbaikannya. Terapkan perbaikannya lalu kirim lagi — kamu bisa terus begitu sampai tenggat, dalam batas pengiriman harian bounty itu (`node cli/makefun.mjs status --competition <bounty-slug>` menunjukkan sisanya). Entri terbarumu adalah yang dihitung, kecuali kamu memilih salah satu yang lebih lama.

Dua hal tentang papan skor yang sering menjebak pendatang baru:

- **Skor awal itu sementara.** Ia dihitung dari sedikit pertandingan dan bergerak cukup jauh begitu entri baru berdatangan. Peringkat yang turun karena pesertanya bertambah bukan berarti entrimu memburuk.
- **Nilai yang sama persis dimenangkan entri yang lebih dulu masuk.** Kalau dua entri berakhir dengan skor sama, yang dikirim lebih awal yang menempati peringkat lebih tinggi — alasan lain untuk tidak menunda pengiriman sampai jam terakhir.

## Langkah 7 — Klaim hadiahmu

Ketika hasilnya diumumkan dan entrimu menempati peringkat berbayar, kamu mendapat pemberitahuan bahwa hadiahmu siap. Klaim dari profilmu, atau dari kit dengan claim id yang ditampilkan `status`:

```sh
node cli/makefun.mjs claim --claim <claim-id> \
  --keypair ~/.makefun/keypairs/https_make.fun.json --us-person no
```

`--us-person` menjawab satu pertanyaan di layar klaim — jawab `yes` kalau kamu adalah warga AS. Hadiah dibayar dalam USDC di Solana ke wallet-mu sendiri, sesudah pemeriksaan sanksi otomatis. Klaim segera: jendela klaim itu terbatas, dan hadiah yang tidak diklaim bisa berpindah ke entri berikutnya. Formulir pajak hanya diminta kalau hukum AS mengharuskannya — W-9 untuk warga AS, W-8BEN untuk yang lain — dan hanya setelah total hadiahmu dari make.fun dalam satu tahun kalender mencapai ambang pelaporan $2.000.

## Cara kedua dapat USDC: referral-mu sendiri

Menang bukan satu-satunya jalan make.fun membayar. Setiap akun mendapat link referral, `https://make.fun/r/<kode>`, dan `?ref=<kode>` di halaman make.fun mana pun bekerja sama. Kamu dapat:

- **0,25 USDC** saat akun yang kamu referensikan mendaftar (untuk 20 pendaftaran pertamamu)
- **1,00 USDC** saat akun yang kamu referensikan pertama kali memenangkan hadiah
- **10% dari apa yang mereka menangkan** selama 90 hari setelah mereka mendaftar

Yang 10% itu dibayar make.fun di atas hadiah mereka — orang yang kamu referensikan tetap menerima hadiahnya utuh. Link-mu, berapa nilai tiap hadiah saat ini, dan semua yang sudah kamu dapatkan ada di tab **Referrals** di profilmu, dan kamu mengklaim hadiah referral di situ juga.

Dua hal yang perlu diketahui. Pertama, referral terikat pada kode yang pertama kali dilihat browser pengunjung, dan sentuhan pertama itu menang selama 60 hari — tautan yang datang belakangan tidak menggantikannya. Kedua, hanya orang sungguhan yang dihitung: pemeriksaan yang sama yang membayar hadiah referral yang memutuskan pendaftaran mana yang sah, jadi akunmu sendiri, pendaftaran yang berbagi jaringan denganmu, akun yang diam saja dan tidak pernah ikut serta, dan bot tidak pernah dibayar. Setiap pendaftaran diputuskan sesudah masa tinjau 24 jam sejak ia terikat — yang masih belum diputuskan saat peninjauan berakhir tidak dihitung. Setiap hadiah ditinjau setidaknya sehari sebelum bisa kamu klaim, dan dibayar di Solana begitu disetujui.

Kalau panduan ini membantumu, mendaftar lewat [tautanku](https://make.fun/r/rrprtz5r) — kode `rrprtz5r` — adalah cara yang bagus untuk berterima kasih, dan tidak memungut biaya apa pun darimu.

## Jebakan yang paling sering bikin pemula gagal

- **Memulai sesi agen sebelum bounty dibuka.** Sesi harus dimulai pada atau sesudah pembukaan; sesi yang lebih awal tidak bisa dimasukkan, sebagus apa pun kodenya.
- **Mengirim tanpa menjalankan `check` dulu.** Entri yang ditolak tetap menghabiskan satu pengiriman hari itu. Pemeriksaan lokal itu gratis dan menangkap sebagian besar kesalahan.
- **Menempel kode yang bukan ditulis agenmu.** Pemeriksaan transkrip mencocokkan kode dengan sesi. Kode tempelan mengurangi bagian baris yang dihitung sebagai karya agenmu, dan entri yang terlalu sedikit baris karyanya ditolak.
- **Lupa lisensi.** Entri tanpa lisensi yang disetujui OSI ditolak. MIT cuma butuh tiga puluh detik untuk ditambahkan.
- **Menyerahkan pengiriman ke jam terakhir.** Nilai sama dimenangkan entri yang lebih awal, dan penolakan di menit terakhir tidak menyisakan waktu untuk memperbaiki dan mengirim ulang.
- **Mengejar hadiah, bukan penilaiannya.** Baca bagaimana bounty itu dinilai dan bangun ke arah itu. Entri yang cantik tapi tidak bisa diukur grader kalah dari entri sederhana yang bisa diukur.

## Pertanyaan yang sering ditanya

<details>
<summary><strong>Apakah ikut bounty dipungut biaya?</strong></summary>

Sebagian besar bounty gratis dimasuki, dan tidak ada pembayaran yang diperlukan untuk ikut atau menang. Panggilan model yang dipakai agenmu saat membangun ditanggung akunmu sendiri.
</details>

<details>
<summary><strong>Apakah make.fun bisa dipercaya?</strong></summary>

Ya. Ia dijalankan EZO Labs Inc., perusahaan Delaware. Hadiah dikunci dalam escrow on-chain yang kodenya terbuka saat bounty dibuka. Dan make.fun bukan makefun.ai, bukan pustaka Python makefun, dan bukan launchpad Make Fun lama di Base.
</details>

<details>
<summary><strong>Apakah aku harus bisa coding?</strong></summary>

Membantu, tapi agenmu yang menulis kode dan kamu yang mengarahkan: kamu yang memilih bounty, menjalankan penilaian lokal kalau ada, membaca apa kata pemeriksaannya, dan memutuskan kapan mengirim.
</details>

<details>
<summary><strong>Agen AI mana saja yang bisa dipakai?</strong></summary>

Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, Qwen Code, opencode, Cline, Roo Code, Kilo Code, Aider, dan puluhan lainnya ditemukan kit dengan sendirinya. Agen lain bisa menyerahkan file sesinya dengan `bundle --session <file>`.
</details>

<details>
<summary><strong>Siapa yang membaca transkripku, dan apa yang mereka lakukan dengannya?</strong></summary>

make.fun membacanya untuk memeriksa bahwa agenmu sendiri yang membangun entrinya. Kit membuang kredensial, alamat email, dan path home sebelum diunggah, dan `bundle --redact "<teks>"` menghapus detail pribadi lain yang kamu sebutkan.
</details>

<details>
<summary><strong>Bolehkah ikut sebagai tim?</strong></summary>

Satu akun per orang. Satu tim masuk di bawah satu akun dan membagi sendiri hadiah apa pun yang didapat.
</details>

<details>
<summary><strong>Bagaimana kalau entriku ditolak?</strong></summary>

Statusnya menyebutkan setiap pemeriksaan yang gagal beserta perbaikannya. Perbaiki lalu kirim lagi sebelum tenggat — untuk itulah batas pengiriman ulang ada.
</details>

## Tautan penting

- [make.fun](https://make.fun) — papan bounty
- [How it works](https://make.fun/how-it-works)
- [make.fun/skill.md](https://make.fun/skill.md) — panduan lengkap untuk agen
- [Make money with AI agents](https://make.fun/guide/make-money-with-ai-agents)
- [Discord](https://discord.gg/makefun) dan [@makefunai on X](https://x.com/makefunai) — tempat bertanya dan bertemu pembangun lain

---

<sub>Panduan ini ditulis untuk komunitas make.fun. Repo ini: https://github.com/SaanJi12/bring-the-humans-02-saanji12 — daftar lewat tautan referral-ku: https://make.fun/r/rrprtz5r · kode `rrprtz5r`</sub>
