# Step by Step menjalankan Test

Menjalankan Semua Test :

```bash
flutter test
```

Menjalankan Integration Test :

```bash
flutter test integration_test/app_test.dart
```
Menjalankan Performance APP :

```bash
flutter drive \
  --driver=test_driver/perf_driver.dart \
  --target=integration_test/perf_test.dart \
  --profile \
  --no-dds
```

# Summary
Projek Flutter ini belajar cara untuk mengimplementasikan test codee kedalam aplikasi Flutter menggunakan Unit test, Widget Test, dan juga Integration Test

Test yang dilakukan: 

File: test/models/favorites_test.dart
Target: Menambahkan dan Mengurangi item pada Favorites
Hasil: Berhasil

File: test/home_test.dart
Target: Mencari Listvew dan Mengetes Icon dan Button 
Hasil: Berhasil


File: integration_test/app_test.dart 
Target: Menambahkan item kedalam Menu Favorites dan juga masuk kedalam Menu Favorites lalu menghapus Item dari dalam Menu Favorites
Hasil: Berhasil 


# Masalah 
Terjadi Error ketika saya awalnya mencoba debuggin tanpa HP
