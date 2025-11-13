# Praktikum 3

Project Modul 3 - Pengaturan Layout (Alignment)

📖 Deskripsi

Project ini adalah kelanjutan dari Modul 2 yang berfokus pada Row dan Column. Pada modul ini, Anda akan belajar mengendalikan tata letak secara presisi menggunakan properti alignment (perataan).

Anda akan mempraktikkan konsep MainAxis (sumbu utama) dan CrossAxis (sumbu silang) untuk mengatur posisi dan distribusi widget di dalam Row dan Column.

🎯 Tujuan Utama Project

Memahami Axis: Mengerti konsep main axis (horizontal untuk Row, vertikal untuk Column) dan cross axis.

Mengatur Ukuran Axis: Memahami dan menerapkan MainAxisSize.min (seukuran konten) dan MainAxisSize.max (memenuhi layar).

Mengatur Main Axis: Mampu menggunakan properti mainAxisAlignment (misalnya: start, center, end, spaceBetween, spaceAround, spaceEvenly) untuk mendistribusikan widget.

Mengatur Cross Axis: Mampu menggunakan properti crossAxisAlignment (misalnya: start, center, end, stretch) untuk meratakan widget di sumbu silangnya.

Studi Kasus: Membangun antarmuka (UI) statis sederhana (info cuaca) dengan menggabungkan semua konsep di atas.

✅ Daftar Tugas (To-Do List)

Berikut adalah hal-hal yang harus Anda kerjakan berdasarkan modul:

Buat Project Baru:

[ ] Buat "New Flutter Project" (misalnya dengan nama layout_alignment).

Latihan Dasar (Sesuai Modul):

[ ] Ikuti dan pahami semua latihan di modul yang mendemonstrasikan penggunaan:

MainAxisSize (.min dan .max)

MainAxisAlignment (coba semua nilai seperti spaceEvenly, center, dll.)

CrossAxisAlignment (coba semua nilai seperti start, center, stretch, dll.)

[ ] Pastikan Anda mengamati perbedaan visual dari setiap properti yang diubah.

Tugas Utama: Membuat UI Cuaca Sederhana

[ ] Buatlah sebuah tampilan UI statis sesuai dengan gambar di modul. Tampilan tersebut harus memuat elemen-elemen berikut:

[ ] Sebuah Column utama untuk seluruh layar.

[ ] Teks "Malang".

[ ] Teks "25°" (atau 25 derajat).

[ ] Sebuah Row yang berisi 3 hari prakiraan cuaca. Gunakan mainAxisAlignment untuk memberi jarak antar hari (misal: spaceEvenly).

[ ] Di dalam Row tersebut, buat 3 buah Column (satu untuk setiap hari).

[ ] Kolom Hari 1:

Text("Minggu")

Icon (sesuai dengan "sunny", misal: Icons.wb_sunny)

Text("20°C")

[ ] Kolom Hari 2:

Text("Senin")

Icon (sesuai dengan "cloudy_snowing", misal: Icons.ac_unit)

Text("23°C")

[ ] Kolom Hari 3:

Text("Selasa")

Icon (sesuai dengan "cloud", misal: Icons.cloud)

Text("22°C")

[ ] Catatan: Modul menyebutkan nama ikon "sunny", "cloudy_snowing", dan "cloud". Anda harus mencari konstanta Icon yang paling sesuai di Flutter (misal: Icons.wb_sunny, Icons.ac_unit, Icons.cloud).

Kesimpulan (Pemahaman Anda tentang MainAxisAlignment, CrossAxisAlignment, dan MainAxisSize)
