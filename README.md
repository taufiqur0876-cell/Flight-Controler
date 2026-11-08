# Flight Controller

Proyek pembuatan **flight controller** (pengendali penerbangan) untuk wahana terbang, dirancang dari nol mulai dari skematik hingga desain PCB.

## Status

🚧 **Dalam pengembangan** — saat ini berada di tahap perancangan skematik dan layout PCB.

## Gambaran Singkat

Flight controller ini dirancang sebagai papan kendali utama yang mengatur pembacaan sensor, pemrosesan data, dan keluaran kendali ke aktuator. Desain dibagi menjadi beberapa blok rangkaian:

- **Mikrokontroler utama** beserta rangkaian pendukung (clock/kristal, reset, boot)
- **Manajemen daya** (regulator tegangan)
- **Antarmuka komunikasi** (USB dan modul nirkabel)
- **Antarmuka sensor**
- **Driver keluaran** untuk motor/aktuator
- **Konektor I/O** untuk perangkat eksternal

## Isi Repositori

| Folder / File | Keterangan |
|---|---|
| `schematic/` | File skematik rangkaian |
| `pcb/` | File desain layout PCB |
| `docs/` | Dokumentasi dan catatan perancangan |

## Rencana Pengembangan

- [x] Perancangan skematik
- [ ] Penyelesaian routing PCB
- [ ] Design Rule Check (DRC) dan review
- [ ] Fabrikasi PCB
- [ ] Perakitan dan pengujian hardware
- [ ] Pengembangan firmware

## Catatan

Proyek ini masih berjalan, sehingga desain dan struktur repositori dapat berubah sewaktu-waktu.

## Penulis

Taufiqur Rahman — Politeknik Elektronika Negeri Surabaya (PENS)
