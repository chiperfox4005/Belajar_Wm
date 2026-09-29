# Pembelajaran Version Control System dengan Git & GitHub

## Tentang Pembelajaran

Pembelajaran ini membahas **Version Control System (VCS)** sebagai salah satu bagian penting dalam pengembangan perangkat lunak. VCS digunakan untuk mencatat perubahan pada source code dari waktu ke waktu sehingga proses pengembangan dapat dilakukan dengan lebih terstruktur dan mudah dikelola.

Materi berfokus pada pengenalan **Git** sebagai software Version Control System dan **GitHub** sebagai platform untuk menyimpan serta membagikan repository Git secara online.

## Materi yang Dipelajari

### 1. Version Control System

Version Control System merupakan sistem yang digunakan untuk mencatat perubahan pada project atau source code. Dengan VCS, perubahan dapat dilacak sehingga pengembang dapat mengetahui siapa yang melakukan perubahan, kapan perubahan dilakukan, membandingkan versi, serta mengembalikan project ke kondisi sebelumnya.

VCS juga membantu dalam proses kolaborasi ketika beberapa orang mengerjakan project yang sama.

### 2. Permasalahan Tanpa Version Control

Pengelolaan source code tanpa VCS dapat menyebabkan beberapa permasalahan, seperti:

* File project memiliki banyak versi yang sulit dibedakan.
* Perubahan pada file dapat tertimpa.
* Sulit mengetahui siapa yang melakukan perubahan.
* Tidak tersedia riwayat perubahan yang jelas.
* Kolaborasi dalam project menjadi lebih sulit.
* Sulit mengembalikan project ke versi sebelumnya.

Version Control digunakan untuk mengatasi permasalahan tersebut dengan menyimpan riwayat perubahan secara terstruktur.

### 3. Git

Git merupakan software Version Control System yang digunakan untuk mengelola perubahan pada source code.

Git dapat digunakan untuk:

* Menyimpan riwayat perubahan project.
* Mengetahui perubahan yang dilakukan.
* Membandingkan perubahan antar versi.
* Mengembalikan project ke versi sebelumnya.
* Mendukung pekerjaan secara kolaboratif.

Salah satu konsep penting dalam Git adalah **commit**. Commit dapat dipahami sebagai snapshot atau kondisi project yang disimpan pada suatu waktu tertentu.

### 4. GitHub

GitHub merupakan platform berbasis cloud yang digunakan untuk menyimpan repository Git secara online.

Git dan GitHub memiliki fungsi yang berbeda. Git digunakan untuk mengelola versi project pada komputer, sedangkan GitHub digunakan sebagai tempat penyimpanan repository secara online.

Git dapat digunakan secara offline, sementara GitHub digunakan melalui internet untuk menyimpan, berbagi, dan mengelola repository.

### 5. Git Workflow

Dalam Git terdapat beberapa kondisi perubahan yang perlu dipahami, yaitu:

**Untracked → Modified → Staged → Committed**

* **Untracked**: file belum dikenali oleh Git.
* **Modified**: file yang sudah dikenali Git mengalami perubahan.
* **Staged**: perubahan telah dipilih dan siap disimpan.
* **Committed**: perubahan telah disimpan sebagai bagian dari riwayat project.

Git juga memiliki tiga area utama:

* **Working Directory** — tempat file project dikerjakan dan diubah.
* **Staging Area** — tempat perubahan yang akan disimpan dipilih.
* **Repository** — tempat riwayat perubahan project disimpan.

### 6. Git dan GitHub dalam Kolaborasi

Git dan GitHub dapat digunakan bersama untuk mendukung pengembangan project secara kolaboratif.

Git mengelola perubahan pada project secara lokal, sedangkan GitHub menyediakan repository secara online. Perubahan yang telah disimpan melalui commit dapat dikirim ke repository GitHub dan perubahan dari repository tersebut dapat diambil kembali ke komputer.

Konsep ini memungkinkan anggota tim untuk bekerja pada project yang sama dengan riwayat perubahan yang lebih jelas.

## Command yang Dipelajari

Beberapa command Git dan GitHub yang dibahas dalam pembelajaran antara lain:

| Command                 | Fungsi                                                  |
| ----------------------- | ------------------------------------------------------- |
| `git init`              | Membuat repository Git                                  |
| `git status`            | Melihat kondisi project                                 |
| `git add .`             | Memasukkan perubahan ke staging area                    |
| `git commit`            | Menyimpan snapshot perubahan                            |
| `git log`               | Melihat riwayat commit                                  |
| `git restore`           | Mengembalikan file ke kondisi tertentu                  |
| `git remote add origin` | Menghubungkan repository lokal dengan repository GitHub |
| `git remote -v`         | Melihat remote yang terhubung                           |
| `git branch -M main`    | Mengubah nama branch menjadi `main`                     |
| `git push`              | Mengirim commit ke repository GitHub                    |
| `git clone`             | Mengambil repository dari GitHub                        |
| `git pull`              | Mengambil perubahan terbaru dari GitHub                 |

## Tujuan Pembelajaran

Setelah mempelajari materi ini, peserta diharapkan memahami konsep dasar Version Control System serta peran Git dan GitHub dalam pengembangan perangkat lunak.

Pembelajaran juga memberikan pemahaman mengenai bagaimana perubahan pada source code dapat dikelola melalui riwayat commit dan bagaimana repository dapat digunakan untuk mendukung kolaborasi dalam sebuah project.

## Kesimpulan

Version Control System membantu pengembang mengelola perubahan source code secara lebih terstruktur. Git berperan dalam mencatat dan mengelola versi project, sedangkan GitHub menyediakan tempat penyimpanan repository secara online.

Pemahaman terhadap Git dan GitHub menjadi dasar penting dalam pengembangan perangkat lunak, khususnya ketika project dikerjakan secara individu maupun bersama tim.
