# Nama Proyek

![Build](https://github.com/USERNAME/REPO/actions/workflows/build-cpp.yml/badge.svg)

Program C++ yang otomatis dikompilasi menjadi `.exe` menggunakan GitHub Actions.

## Download

- **Build terbaru:** buka tab [Actions](https://github.com/USERNAME/REPO/actions), pilih run terbaru, lalu unduh `app-windows` di bagian *Artifacts*.
- **Versi rilis:** lihat halaman [Releases](https://github.com/USERNAME/REPO/releases).

## Cara Build Otomatis

Setiap push ke branch `main`, GitHub Actions akan mengompilasi semua file `.cpp` menjadi `app.exe`.

Untuk membuat rilis, buat tag versi:

```bash
git tag v1.0
git push origin v1.0
```

## Build Manual (Lokal)

Pastikan g++ sudah terpasang, lalu jalankan:

```bash
g++ -std=c++17 -O2 -static *.cpp -o app.exe
```

## Lisensi

MIT
