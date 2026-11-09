\# Contributing Guide



\## 1. Branch Convention



Format: `<type>/<short-description>`



| Type | Kegunaan | Contoh |

|---|---|---|

| feature/ | Fitur baru | feature/123-user-login |

| fix/ | Memperbaiki bug | fix/cart-total |

| hotfix/ | Perbaikan darurat | hotfix/payment-down |

| refactor/ | Merapikan kode | refactor/order-service |

| docs/ | Dokumentasi | docs/api-reference |

| test/ | Pengujian | test/checkout-flow |

| chore/ | Pemeliharaan | chore/update-deps |



Aturan:

\- Menggunakan huruf kecil.

\- Menggunakan tanda hubung (-), bukan spasi.

\- Menyertakan nomor tiket jika tersedia.

\- Maksimal 50 karakter.



\## 2. Commit Convention



Format: `<type>(<scope>): <subject>`



Type yang digunakan:

\- feat: menambahkan fitur.

\- fix: memperbaiki bug.

\- docs: memperbarui dokumentasi.

\- style: perubahan format kode.

\- refactor: merapikan kode.

\- perf: meningkatkan performa.

\- test: menambahkan pengujian.

\- build: perubahan sistem build.

\- ci: perubahan konfigurasi CI.

\- chore: pemeliharaan proyek.

\- revert: membatalkan commit.



Contoh:

\- feat(auth): add JWT refresh token

\- fix(cart): correct total when discount applied

\- docs(readme): update installation steps



Aturan:

\- Subject menggunakan huruf kecil.

\- Menggunakan imperative mood.

\- Tidak menggunakan titik di akhir.

\- Maksimal 50 karakter untuk subject.

\- Referensi issue ditulis menggunakan Closes #123.



\## 3. Pull Request



\- Judul PR mengikuti format commit message.

\- Ukuran PR kurang dari 400 baris.

\- Wajib mendapatkan persetujuan minimal satu reviewer.

\- Wajib lolos CI.

\- Menggunakan Squash Merge.



\## 4. Code Review



Label komentar:

\- blocking: perubahan wajib diperbaiki.

\- nit: saran kecil dan opsional.

\- question: meminta klarifikasi.

\- praise: memberikan apresiasi.



\## 5. Workflow



1\. Mengambil perubahan terbaru dari main.

2\. Membuat branch baru.

3\. Mengerjakan fitur dan membuat commit.

4\. Push branch ke GitHub.

5\. Membuat Pull Request.

6\. Menunggu review dan CI.

7\. Melakukan Squash Merge.

8\. Menghapus branch setelah merge.



\## 6. Hal yang Dilarang



\- Push langsung ke branch main.

\- Menggunakan commit message tidak jelas seperti wip, test, dan asdf.

\- Mengunggah file .env, node\_modules, atau credentials.

\- Melakukan rebase pada branch yang sudah di-push dan digunakan anggota lain.



\## 7. Teknologi Proyek



Teknologi yang digunakan disesuaikan dengan kebutuhan proyek kelompok. Setiap anggota wajib mengikuti standar penulisan kode, commit, dan workflow Git yang telah disepakati.

