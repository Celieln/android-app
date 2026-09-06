# Contributing

Kami menerima kontribusi untuk pengembangan aplikasi Android ini!

## Cara Berkontribusi

1. **Fork** repository ini
2. Clone fork ke lokal
3. Buat branch baru: `git checkout -b fitur/nama-fitur`
4. Lakukan perubahan kode
5. Commit dengan pesan yang jelas
6. Push dan buat **Pull Request**

## Build

```bash
# Release build (R8 obfuscated)
./gradlew assembleRelease

# Debug build
./gradlew assembleDebug
```

## Guidelines

- Gunakan Kotlin dan ikuti gaya kode yang konsisten
- Jangan commit keystore, API key, atau file sensitif
- Uji sebelum membuat PR

Terima kasih sudah berkontribusi!