# RyzenTimeBus

Web app jadwal bus dan kalender kerja, responsif untuk HP, tablet, dan komputer.

## Isi
- index.html: seluruh HTML, CSS, JavaScript, jadwal bus, kalender libur, dan shift kerja.
- logo.svg: logo yang kamu kirim.

## Membuka
Ekstrak ZIP, lalu buka index.html di browser modern. Jangan memindahkan index.html tanpa logo.svg.
Untuk akses paling mudah dari semua perangkat, unggah kedua file ke hosting statis (misalnya GitHub Pages, Netlify, atau Cloudflare Pages), lalu buka tautan HTTPS-nya. Tidak perlu install dependensi atau build.

## Hosting
Unggah isi folder ini sehingga index.html berada di akar situs. Pada GitHub Pages, simpan index.html dan logo.svg di root repositori, lalu aktifkan Pages untuk branch tersebut. Situs statis biasa tidak menyediakan login: siapa pun yang bisa membuka situs dapat membaca data shift di kode. Hapus data pribadi sebelum membagikan secara publik bila diperlukan.

## Data & pengaturan
- Bus dua arah: Chounoyamakouen ↔ Imazu, dari foto yang dikirim.
- Shift レザ: hanya November 2026.
- Libur nasional Jepang: 2026–2027.
- Jam selalu waktu Jepang (Asia/Tokyo).
- A 07.00; B 08.00; ウ 10.00; カ 12.00; 公 libur; 有 cuti berbayar.
- Arah perjalanan dan jeda keberangkatan tersimpan di browser masing-masing; tidak tersinkron otomatis antardevice.
- Jeda awal 30 menit adalah asumsi yang bisa diubah; jam tiba bus belum tersedia.
- Bus bukan pelacakan langsung. Keterlambatan dan perubahan jadwal operator tidak diperbarui otomatis.

## Mengedit
Buka index.html di editor teks. Cari workShifts untuk shift, schedules/returnSchedules untuk bus, dan holidayRows untuk kalender hari libur. Simpan lalu unggah ulang.
