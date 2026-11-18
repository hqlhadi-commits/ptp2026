# Majlis Pengiktirafan Program Transformasi Produktiviti 2026

Laman pendaratan rasmi untuk Majlis Pengiktirafan PTP 2026 (1 Disember 2026, Sunway Resort Hotel) anjuran Perbadanan Produktiviti Malaysia (MPC).

## Kandungan

- `index.html` ialah keseluruhan laman dalam satu fail. Logo MPC, kod QR dan gambar kecil video sudah dibenam dalam fail ini.
- Laman ini memuat dari luar: Google Fonts (Poppins) dan pemain video Facebook.

## Mengemas kini kandungan

Semua tetapan berada dalam objek `CONFIG` di bahagian `<script>` paling bawah dalam `index.html`:

| Tetapan | Kegunaan |
| --- | --- |
| `DRAF` | `true` memaparkan bar pratonton fasa dan teks pemegang tempat. Mesti `false` untuk laman langsung. |
| `MAKLUMAT_URL` | Pautan kod QR "Untuk maklumat lanjut" (butang "Buka pautan"). |
| `VIDEO.teaser.fb` | Pautan video teaser Facebook. |
| `SYARIKAT` | Senarai logo 100 syarikat: `{ nama: "...", logo: "..." }`. |
| `SOSIAL` | Pautan media sosial @MPCProductivity. |

Atur cara diubah dalam senarai `AGENDA` di bawah `CONFIG`.

## Fasa automatik (waktu Malaysia)

- Sebelum 1 Disember 2026: kiraan detik dan butiran majlis.
- 1 Disember 2026: "Sekarang / Seterusnya" mengikut atur cara.
- Mulai 2 Disember 2026: sorotan majlis.

## Menerbitkan dengan GitHub Pages

1. Settings → General → Danger Zone → Change visibility → **Public** (GitHub Pages percuma memerlukan repositori awam).
2. Settings → Pages → Build and deployment → Source: **Deploy from a branch** → Branch: **main**, folder **/ (root)** → Save.
3. Laman akan tersedia di `https://hqlhadi-commits.github.io/ptp2026/` dalam beberapa minit.
