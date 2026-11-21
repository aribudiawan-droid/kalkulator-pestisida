# Kalkulator Pestisida

Kalkulator dosis dan volume semprot untuk pestisida, dengan fitur kalibrasi nozzle.

## Fitur

**Dosis dan tangki**
- Hitung total produk, total larutan semprot, dan produk per tangki dari luas lahan, dosis, dan volume semprot per hektar.
- Pilih tipe formulasi: EC, SL, SC, EW, OD (cair, satuan L) atau WP, WG, SG, GR (padat, satuan kg).
- Masukkan dosis dalam produk per hektar, g ai/ha (gram bahan aktif), atau g ae/ha (gram acid equivalent). Untuk dosis g ai/ha dan g ae/ha, isi kandungan bahan aktif dari label produk.
- Hitung jumlah tangki, luas yang tercakup per tangki, dan konsentrasi larutan.
- Hitung jumlah kemasan produk yang perlu dibeli, dibulatkan ke atas.
- Salin ringkasan hasil ke clipboard.

**Kalibrasi nozzle**
- Hitung output nozzle (L/menit) dari volume yang tertampung dalam waktu tertentu.
- Hitung volume aktual (L/ha) dari lebar semprot dan kecepatan jalan.
- Bandingkan dengan target volume dan lihat kecepatan jalan yang dibutuhkan.

## Cara pakai

1. Pilih tipe formulasi dan satuan dosis sesuai label produk.
2. Isi luas lahan, dosis, volume semprot per hektar, kapasitas tangki, dan ukuran kemasan.
3. Tekan **Hitung**.
4. Untuk kalibrasi, buka tab **Kalibrasi Nozzle**, ukur output nozzle dengan gelas ukur, lalu isi datanya.

## Rumus

- Total larutan = luas × volume/ha
- Produk per tangki = dosis/ha × (tangki ÷ volume/ha)
- Produk/ha dari g ai/ha atau g ae/ha = dosis (g) ÷ kandungan (g per L atau kg)
- Output (L/menit) = mL total ÷ 1000 × 60 ÷ detik
- Volume (L/ha) = 600 × output (L/menit) ÷ (lebar m × kecepatan km/jam)

## Catatan

Hasil perhitungan ini hanya alat bantu. Pastikan dosis dan cara aplikasi sesuai label produk, anjuran penyuluh, dan peraturan setempat. Gunakan alat pelindung diri saat mencampur dan menyemprot.

## Pembuat

Ari Budiawan · aribudia@gmail.com
