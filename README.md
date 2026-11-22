# Network Speed

Modul KernelSU Next yang mengunci mode jaringan ke NR/LTE (LTE, LTE_CA, NR) segera setelah HP selesai booting.

## Fungsi
- Memastikan izin jaringan tetap LTE, LTE_CA, dan NR setelah reboot.
- Jika izin berubah, modul akan mengembalikannya ke NR/LTE selama sekitar 2 menit setelah booting.

## Persyaratan
- HP dengan root KernelSU Next.
- Diuji di Poco X7 5G (malachite) dengan HyperOS.

## Cara pasang
1. Unduh `Network.Speed.zip` dari halaman **Releases**.
2. Buka KernelSU Next, pilih **Modul**, lalu **Instal dari penyimpanan** dan pilih file zip.
3. Reboot HP.
4. Cek mode jaringan di pengaturan. Pilihannya seharusnya langsung NR/LTE.

## Cara hapus
Buka KernelSU Next, pilih modul **Network Speed**, lalu hapus. Reboot setelah itu.

## Catatan
- Modul ini memakai perintah `cmd phone set-allowed-network-types-for-users`. Jika ROM berubah, perilakunya bisa berbeda.
- Modul ini tidak mengubah modem atau partisi apa pun.

## Pengembang
Skypin 969, Telegram @Skypin969
