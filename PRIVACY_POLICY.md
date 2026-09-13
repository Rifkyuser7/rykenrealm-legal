# Privacy Policy — RykenRealm

**Terakhir diperbarui:** 13 September 2026

Kebijakan privasi ini menjelaskan data apa saja yang dikumpulkan, disimpan, dan diproses oleh bot Discord **RykenRealm** (selanjutnya disebut **"RykenRealm"** atau **"Bot"**), yang dikembangkan dan dikelola oleh **Rizuki (@ryin.r)**. Dengan menggunakan Bot, kamu menyetujui praktik yang dijelaskan di bawah ini.

Server komunitas resmi: https://discord.gg/kME469thr6

---

## 1. Data yang Dikumpulkan & Disimpan

Bot menyimpan data berikut agar fitur-fiturnya bisa berfungsi:

- **Identitas dasar Discord** — User ID Discord kamu dan nama tampilan (display name), agar Bot bisa mengenali dan menyapa kamu dengan benar.
- **ID Server (Guild ID)** — dipakai untuk sistem whitelist/aktivasi server dan leaderboard per-server.
- **Data ekonomi virtual** — saldo mata uang virtual (clean cash, dirty cash), riwayat pekerjaan, kepemilikan rumah virtual, saham/kripto virtual, dan progres lain di sistem ekonomi Bot.
- **Data RPG** — level, inventaris, progress dungeon/tower, status crafting, dan data karakter RPG lainnya.
- **Data pasangan/keluarga fiksi** — nama karakter anime yang "dinikahi" (diambil dari database publik MyAnimeList via Jikan API), status hubungan, dan data anak fiksi dalam fitur tersebut.
- **Preferensi pengguna** — pengaturan bahasa (`.language`), zona waktu untuk fitur pengingat/ulang tahun jika diisi.
- **Statistik penggunaan ringan** — XP level chat, cooldown fitur (mis. kapan terakhir kali memakai `.daily`/`.hunt`/`.heist`), untuk mencegah penyalahgunaan command.

Bot **tidak** menyimpan isi pesan biasa (obrolan non-command) di server. Bot hanya memproses pesan yang diawali command (`.`) untuk menjalankan fiturnya.

## 2. Data yang Diproses tapi Tidak Disimpan Permanen

- **Fitur AI Chat** — pesan yang kamu kirim ke fitur AI chat diteruskan ke penyedia model AI pihak ketiga (Google Gemini API) untuk diproses dan dijawab. Perlakuan data pada sisi penyedia tersebut tunduk pada [Kebijakan Privasi Google](https://policies.google.com/privacy). Bot sendiri tidak menyimpan histori percakapan AI secara permanen di database miliknya.
- **Fitur downloader/konversi media** — tautan (link) atau file yang kamu kirim untuk diunduh/dikonversi (mis. dari Mediafire, video ke MP3) diproses sementara untuk menghasilkan file keluaran, lalu tidak disimpan setelah dikirim balik kepadamu.
- **Pencarian karakter anime** — nama karakter yang kamu cari untuk fitur pasangan dikirim ke Jikan API (wrapper publik MyAnimeList) untuk mengambil data karakter tersebut.

## 3. Bagaimana Data Digunakan

Data yang disimpan hanya digunakan untuk:

- Menjalankan dan mempertahankan progres fitur-fitur Bot (ekonomi, RPG, pasangan, dll) antar sesi.
- Menampilkan leaderboard dan statistik di dalam server tempat Bot aktif.
- Mencegah penyalahgunaan sistem (cooldown, deteksi multi-akun sederhana).

Data **tidak** dijual, disewakan, atau dibagikan ke pihak ketiga untuk tujuan komersial/iklan.

## 4. Penyimpanan & Keamanan Data

- Data disimpan dalam bentuk file database pada layanan hosting Bot (Railway) dengan volume penyimpanan persisten.
- Akses ke server hosting dan database dibatasi hanya untuk pemilik Bot (Rizuki).
- Meskipun sudah diupayakan aman, tidak ada sistem yang 100% bebas risiko. Bot tidak menyimpan data sensitif seperti kata sandi, informasi pembayaran, atau dokumen identitas apapun — Bot memang tidak pernah meminta data semacam itu.

## 5. Layanan Pihak Ketiga yang Digunakan

Bot berinteraksi dengan layanan pihak ketiga berikut untuk menjalankan fiturnya:

| Layanan | Fungsi |
|---|---|
| Discord API | Platform utama tempat Bot berjalan |
| Google Gemini API | Fitur AI chat & analisis gambar |
| Jikan API (MyAnimeList) | Data karakter anime untuk fitur pasangan |
| Mediafire | Fitur download file |
| yt-dlp (layanan video publik) | Konversi video/audio |

Masing-masing layanan tunduk pada kebijakan privasinya sendiri.

## 6. Hak Pengguna

Kamu berhak untuk:

- **Meminta penghapusan data** — hubungi Rizuki (@ryin.r) melalui server komunitas untuk meminta data ekonomi/RPG/pasangan kamu dihapus dari database.
- **Reset mandiri** — beberapa data ekonomi dapat direset sendiri melalui command yang tersedia di Bot (mis. `.resetekonomi`, dengan pengecualian data pasangan/anak jika berlaku).
- **Berhenti menggunakan Bot kapan saja** — cukup dengan tidak lagi memakai command Bot atau meminta admin server mengeluarkan Bot dari server.

## 7. Privasi Anak

Bot tidak ditujukan untuk anak di bawah usia minimum yang disyaratkan [Ketentuan Layanan Discord](https://discord.com/terms). Bot tidak secara sadar mengumpulkan data dari pengguna yang diketahui berada di bawah batas usia tersebut.

## 8. Perubahan Kebijakan

Kebijakan ini dapat diperbarui sewaktu-waktu mengikuti perubahan fitur Bot. Versi terbaru akan selalu tersedia di tempat yang sama, dan perubahan penting akan diumumkan di server komunitas resmi.

## 9. Kontak

Pertanyaan seputar privasi atau permintaan terkait data pribadi dapat disampaikan melalui:

- Server Discord: https://discord.gg/kME469thr6
- Owner & Developer: **Rizuki** (@ryin.r)

---

*Kebijakan ini berlaku bersamaan dengan [Terms of Service](./TERMS_OF_SERVICE.md) Bot.*
