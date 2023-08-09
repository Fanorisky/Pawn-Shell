# Pawn Compiler for Termux

> Original by DeviceBlack and BeerlID

> Translated by Fanorisky



# Original Source

[Termux-Pawn dari DeviceBlack](https://github.com/Device-Black/Termux-Pawn)



# Diperlukan

- Android 7+ (Sudah diuji pada: armv7, armv8, aarch64)

- [Termux:App_v118.0 dari F-Droid](https://f-droid.org/repo/com.termux_118.apk)



### Konfigurasi

Update repositori dan membuka akses ijin memori internal.

```sh

yes | pkg update -y && yes | pkg upgrade -y

termux-setup-storage

```



### Penginstalan

Menyimpan file virtual dalam cache dan menjalankannya.

```sh

curl https://raw.githubusercontent.com/Device-Black/Termux-Pawn/DeviceBlack/install.sh | sh

```



### Pembongkaran

Menghapus file compiler.

```sh

rm $PREFIX/bin/pawn* && rm $PREFIX/lib/libpawnc.so && exit

```
