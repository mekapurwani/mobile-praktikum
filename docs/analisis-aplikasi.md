# Analisis Aplikasi m-BCA

## Aplikasi yang Diamati
Aplikasi yang diamati adalah m-BCA, yaitu layanan mobile banking dari Bank Central Asia (BCA). Sebelum adanya mobile banking, pengguna harus mengantre di mesin ATM atau datang ke kantor cabang untuk melakukan transaksi seperti transfer uang, mengecek mutasi, atau membayar tagihan. m-BCA menyelesaikan masalah tersebut dengan memberikan kemudahan dan efisiensi waktu karena pengguna dapat mengelola keuangan dan melakukan berbagai transaksi langsung melalui smartphone tanpa harus mencari mesin ATM atau datang ke kantor cabang.

## Pengguna
Pengguna m-BCA adalah nasabah Bank Central Asia (BCA) dari berbagai kalangan yang membutuhkan layanan perbankan secara praktis. Penggunanya dapat berasal dari mahasiswa, karyawan, ibu rumah tangga, hingga pelaku UMKM yang membutuhkan platform untuk melakukan transaksi sehari-hari dengan mobilitas tinggi dan cepat.

## Tiga Fitur Utama
### 1. m-Transfer
m-Transfer digunakan untuk memudahkan pengguna dalam melakukan pengiriman dana, baik ke sesama rekening BCA maupun ke bank lain secara real-time. Fitur ini bermanfaat karena pengguna dapat melakukan transfer tanpa harus mencari mesin ATM.

### 2. m-Payment
m-Payment digunakan untuk melakukan pembayaran berbagai kebutuhan atau tagihan, seperti listrik, air, kartu kredit, asuransi, dan telepon. Fitur ini membantu pengguna menyelesaikan pembayaran dengan lebih praktis melalui smartphone.

### 3. Cardless
Cardless merupakan fitur yang memungkinkan pengguna melakukan transaksi tertentu di ATM BCA tanpa menggunakan kartu ATM secara langsung. Pengguna dapat memperoleh kode atau akses transaksi melalui aplikasi m-BCA, kemudian menggunakannya pada ATM. Fitur ini bermanfaat ketika pengguna ingin melakukan transaksi di ATM tetapi tidak membawa kartu fisik.

## Usulan Perbaikan
Salah satu kendala yang ditemukan pada m-BCA adalah indikator lampu jaringan yang cukup sensitif terhadap gangguan sinyal maupun jeda waktu. Jika pengguna mendiamkan aplikasi sebentar atau sinyal mengalami sedikit perubahan, indikator dapat berubah menjadi merah dan transaksi dapat gagal atau terputus. Pengguna kemudian harus menutup aplikasi dan mengulang proses transaksi dari awal.

Perbaikan yang dapat diusulkan adalah menambahkan sistem auto-retry dan background pinging yang memberikan toleransi waktu koneksi beberapa detik sebelum mematikan sesi transaksi atau mengembalikan pengguna ke menu awal. Gangguan sinyal atau jeda beberapa detik saat melakukan transaksi, misalnya ketika melakukan scan QRIS, merupakan hal yang dapat terjadi. Dengan adanya toleransi waktu dan percobaan koneksi ulang secara otomatis, pengguna tidak perlu mengulang seluruh proses hanya karena koneksi mengalami gangguan sementara.