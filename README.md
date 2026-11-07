# Day-1-Bus_Simulator_Abdillah_Gumilang
Repository dokumentasi kegiatan Day 1 Proyek Workshop yang berisi rangkuman materi, catatan pembelajaran, dan dokumentasi kegiatan.
# Dokumentasi Day 1 Proyek Workshop
## Building with AI, Managing Change with GitHub

## 1. Identitas Peserta
- **Nama Lengkap:** Abdillah Gumilang
- **Kelompok:** Bus Simulator
- **Kegiatan:** Day 1 Proyek Workshop
- **Tanggal:** 7 November 2026

## 2. Deskripsi Repository
Repository ini dibuat sebagai tempat dokumentasi kegiatan Day 1 Proyek Workshop dengan tema *Building with AI, Managing Change with GitHub*.

Repository ini berisi rangkuman materi, catatan pembelajaran, serta pengalaman selama mengikuti workshop. Dokumentasi disusun menggunakan README.md agar informasi dapat dibaca dan diakses dengan mudah melalui GitHub.

## 3. Tujuan Repository
1. Mendokumentasikan materi yang disampaikan selama workshop.
2. Memahami penggunaan AI melalui teknik Prompt Engineering.
3. Mengenal Git dan GitHub sebagai alat pengelolaan proyek.
4. Memahami proses version control dalam pengembangan aplikasi.
5. Mencatat pengetahuan baru yang diperoleh selama kegiatan workshop.

## 4. Rangkuman Materi Workshop

### A. Prompt Engineering

Prompt Engineering merupakan cara merancang instruksi agar AI dapat memberikan jawaban yang tepat, relevan, dan sesuai dengan kebutuhan pengguna.

Prompt adalah instruksi atau masukan yang diberikan kepada model AI untuk mendapatkan hasil tertentu. Prompt dapat berupa pertanyaan sederhana, kata kunci, instruksi kompleks, maupun potongan kode.

**Struktur prompt yang baik**

Dalam workshop dijelaskan bahwa prompt yang baik memiliki empat bagian utama:

1. **Role:** Menentukan peran yang harus dijalankan oleh AI.
2. **Task:** Menjelaskan tugas yang harus dikerjakan.
3. **Context:** Memberikan informasi atau latar belakang agar AI memahami kebutuhan pengguna.
4. **Format:** Menentukan bentuk hasil atau jawaban yang diinginkan.

**Keuntungan Prompt Engineering:**
- Meningkatkan performa AI model.
- Mengurangi bias dan respons yang bersifat offensive.
- Meningkatkan kontrol dan prediktabilitas hasil AI.
- Memberikan pengalaman pengguna yang lebih baik.

### B. Git dan GitHub

**1. Pengertian Git**

Git merupakan sistem version control yang digunakan untuk melacak perubahan pada file, termasuk siapa yang melakukan perubahan, kapan perubahan dilakukan, dan apa saja yang diubah.

Git diciptakan oleh Linus Torvalds pada tahun 2005.

**2. Pengertian GitHub**

GitHub merupakan platform berbasis web yang digunakan untuk menyimpan repository Git secara online serta mendukung kolaborasi dalam pengembangan proyek.

**3. Perbedaan Git dan GitHub**

- **Git:** Sistem version control yang digunakan untuk melacak dan mengelola perubahan proyek secara lokal.
- **GitHub:** Platform online untuk menyimpan repository Git dan mendukung kolaborasi.

**4. Git Workflow**

Terdapat tiga bagian penting dalam alur kerja Git:

- **Working Directory:** Tempat file proyek dikerjakan dan dimodifikasi.
- **Staging Area:** Tempat menyimpan perubahan yang akan dimasukkan ke commit berikutnya.
- **Git Directory:** Tempat Git menyimpan metadata dan database objek proyek.

**5. Perintah Dasar Git**

| Perintah | Fungsi |
|---|---|
| `git init` | Memulai repository Git baru. |
| `git add .` | Memindahkan perubahan file ke staging area. |
| `git commit -m "message"` | Menyimpan perubahan ke repository. |
| `git remote add origin <url>` | Menghubungkan repository lokal dengan repository online. |
| `git push origin main` | Mengirim perubahan ke GitHub. |
| `git pull origin main` | Mengambil perubahan dari GitHub dan menggabungkannya ke branch aktif. |

**6. Pengaturan Awal Git**

Sebelum menggunakan Git, diperlukan pengaturan identitas pengguna menggunakan perintah:

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

Untuk memeriksa konfigurasi:

```bash
git config --global --list
```

**7. GitHub SSH Key**

SSH Key digunakan untuk menghubungkan komputer dengan GitHub melalui autentikasi SSH.

Pada materi workshop, dijelaskan proses pembuatan SSH Key menggunakan perintah:

```bash
ssh-keygen -t ed25519 -C "email@domain.com"
```

Kemudian public key ditambahkan ke pengaturan SSH and GPG keys pada GitHub.

## 5. Praktik Workshop: Student Task Planner

Pada bagian praktik, peserta diarahkan untuk membuat aplikasi sederhana bernama **Student Task Planner** dengan bantuan AI.

Aplikasi ini ditujukan untuk membantu mahasiswa tahun pertama mengelola tugas dan tenggat waktu.

Tahapan praktik yang disampaikan:

1. Menginstal platform berbantuan AI seperti Claude, Antigravity, atau ChatGPT.
2. Menulis prompt untuk membuat aplikasi atau web.
3. Memulai pengelolaan proyek menggunakan `git init`.
4. Melakukan commit dan push ke GitHub.
5. Melakukan perubahan pada proyek.
6. Melakukan commit dan push kembali ke GitHub.

Melalui praktik ini, peserta diperkenalkan pada penggunaan AI dalam pembuatan aplikasi serta pengelolaan perubahan proyek menggunakan Git dan GitHub.

## 6. Poin Penting dan Pengetahuan Baru

Beberapa pengetahuan yang saya dapatkan selama mengikuti workshop Day 1 antara lain:

1. Prompt yang memiliki instruksi, konteks, dan format yang jelas dapat membantu AI menghasilkan jawaban yang lebih sesuai dengan kebutuhan.
2. Git dan GitHub memiliki fungsi yang berbeda, tetapi saling melengkapi dalam pengembangan proyek.
3. Git dapat digunakan untuk melacak perubahan sehingga perkembangan proyek lebih mudah dikelola.
4. Staging Area dan Commit merupakan bagian penting dalam proses penyimpanan perubahan menggunakan Git.
5. GitHub dapat digunakan sebagai tempat penyimpanan repository secara online sekaligus sarana kolaborasi.
6. AI dapat dimanfaatkan untuk membantu proses pembuatan aplikasi, sedangkan Git digunakan untuk mengelola perubahan pada proyek tersebut.

## 7. Pendapat Pribadi tentang Day 1 Proyek Workshop

Menurut saya, kegiatan Day 1 Proyek Workshop cukup menarik dan memberikan banyak pengetahuan baru, terutama mengenai penggunaan AI dan pengelolaan proyek menggunakan GitHub.

Salah satu hal yang paling menarik adalah pembahasan mengenai Prompt Engineering. Saya jadi memahami bahwa untuk mendapatkan hasil yang baik dari AI, kita tidak cukup hanya memberikan pertanyaan, tetapi juga perlu memberikan instruksi dan konteks yang jelas.

Selain itu, materi Git dan GitHub memberikan pemahaman baru mengenai pentingnya mengelola perubahan dalam sebuah proyek. Sebelumnya, saya belum terlalu memahami bagaimana proses version control digunakan dalam pengembangan aplikasi.

Melalui kegiatan ini, saya menjadi lebih tertarik untuk mempelajari Git, GitHub, dan pemanfaatan AI dalam bidang pengembangan perangkat lunak. Saya berharap materi yang diperoleh pada hari pertama ini dapat menjadi bekal untuk mengikuti kegiatan workshop selanjutnya.

## 8. Penutup

Demikian dokumentasi kegiatan Day 1 Proyek Workshop yang berisi rangkuman materi, poin pembelajaran, serta pendapat pribadi selama mengikuti kegiatan.

Repository ini diharapkan dapat menjadi catatan pembelajaran sekaligus dokumentasi perkembangan pengetahuan selama mengikuti rangkaian workshop.

---

**Dokumentasi Day 1 Proyek Workshop — Building with AI, Managing Change with GitHub.**
