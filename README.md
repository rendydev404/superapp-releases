# Superapp Suka Shawarma — rilis

Repo ini hanya menyimpan file rilis aplikasi Android Superapp (APK penuh dan patch delta `.fbf`).
Source code tidak ada di sini.

Setiap versi punya satu Release dengan tag `v<versionCode>`, misalnya `v53` untuk 1.7.4.
Aplikasi mengunduh file dari sini sesuai manifest di server, lalu memeriksa SHA-256-nya sebelum dipasang.
