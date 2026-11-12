# CONTRIBUTING.md

## 1. Tujuan

Dokumen ini berisi aturan kontribusi dan penggunaan Git dalam pengembangan proyek. Seluruh anggota tim wajib mengikuti aturan ini agar proses kerja lebih teratur, mudah dipahami, dan mengurangi konflik saat menggabungkan kode.

## 2. Aturan Branch

Branch utama yang digunakan adalah `main`. Setiap anggota tim harus membuat branch baru sebelum mengerjakan fitur atau perbaikan.

Format nama branch:

- `feature/nama-fitur` untuk penambahan fitur.
- `fix/nama-masalah` untuk memperbaiki bug.
- `docs/nama-dokumentasi` untuk perubahan dokumentasi.
- `refactor/nama-bagian` untuk merapikan kode tanpa mengubah fungsi.

Contoh: `feature/login-user` atau `fix/error-validasi`.

Hindari mengerjakan perubahan langsung pada branch `main`.

## 3. Aturan Commit Message

Setiap commit harus menggunakan format Conventional Commits:

`type: deskripsi singkat`

Jenis commit yang digunakan:

- `feat`: menambahkan fitur baru.
- `fix`: memperbaiki bug.
- `docs`: mengubah dokumentasi.
- `style`: perubahan format atau tampilan kode tanpa mengubah logika.
- `refactor`: merapikan struktur kode.
- `test`: menambahkan atau memperbaiki pengujian.
- `chore`: pekerjaan pemeliharaan proyek.

Contoh:
- `feat: menambahkan halaman login`
- `fix: memperbaiki validasi formulir`
- `docs: memperbarui panduan instalasi`

Gunakan huruf kecil pada deskripsi dan tuliskan pesan commit yang singkat serta jelas.

## 4. Aturan Pull Request

Sebelum perubahan digabungkan ke `main`, anggota tim harus membuat Pull Request (PR). Setiap PR wajib:

1. Menggunakan judul yang menjelaskan perubahan.
2. Menjelaskan tujuan dan bagian yang diubah.
3. Memastikan kode sudah diuji.
4. Tidak memiliki konflik dengan branch tujuan.
5. Mendapatkan pemeriksaan dari anggota tim lain sebelum digabungkan.

## 5. Proses Pengembangan

1. Ambil perubahan terbaru dari repository.
2. Buat branch sesuai jenis pekerjaan.
3. Kerjakan perubahan pada branch tersebut.
4. Simpan perubahan menggunakan commit message sesuai aturan.
5. Push branch ke GitHub.
6. Buat Pull Request menuju `main`.
7. Lakukan pemeriksaan dan perbaikan jika diperlukan.
8. Gabungkan PR setelah disetujui.

## 6. Ketentuan Tambahan

- Jangan mengunggah file rahasia seperti password, token, atau API key.
- Jangan mengunggah file hasil build atau file sementara yang tidak diperlukan.
- Setiap anggota bertanggung jawab terhadap perubahan yang dibuat.
- Komunikasikan perubahan yang berdampak pada pekerjaan anggota lain.

Dengan mengikuti aturan ini, diharapkan kolaborasi tim berjalan lebih konsisten, terstruktur, dan mudah dipelihara.