# Phase-0-Week-6

# **Week 6: Git (add, commit, push, status)**

## **1. Penjelasan**
Git adalah sistem kontrol versi terdistribusi yang memungkinkan pengembang melacak perubahan kode dan bekerja secara kolaboratif. Dalam minggu ini, kita akan mempelajari perintah dasar berikut:

- `git add` → Menambahkan perubahan ke dalam staging area.
- `git commit` → Menyimpan perubahan ke dalam repository lokal.
- `git push` → Mengirim perubahan dari repository lokal ke repository remote.
- `git status` → Menampilkan status perubahan dalam repository.

### **Staged vs Unstaged**
- **Unstaged**: File yang telah diubah tetapi belum ditambahkan ke staging area.
- **Staged**: File yang telah ditambahkan ke staging area dan siap untuk di-commit.

### **Local vs Remote Repository**
- **Local repository**: Repositori di komputer lokal tempat pengembang bekerja.
- **Remote repository**: Repositori yang di-hosting di layanan seperti GitHub, GitLab, atau Bitbucket.

---

## **2. Contoh Penggunaan**

### **1. Menampilkan status repository**
```sh
$ git status
```
Output ini menunjukkan perubahan yang belum dikomit dan apakah ada perubahan yang belum ditambahkan ke staging area.

### **2. Menambahkan perubahan ke staging area**
```sh
$ git add nama_file.txt
```
Atau untuk menambahkan semua perubahan:
```sh
$ git add .
```

### **3. Menyimpan perubahan dengan commit**
```sh
$ git commit -m "Menambahkan fitur baru"
```

### **4. Mengirim perubahan ke repository remote**
```sh
$ git push origin main
```

---

## **3. Tugas / Assignment**
### **Instruksi:**
1. Buat repository baru di GitHub/GitLab.
2. Clone repository ke komputer lokal.
3. Buat file `README.md` dengan isi deskripsi proyek.
4. Gunakan perintah `git add`, `git commit`, dan `git push` untuk menyimpan perubahan ke repository remote.
5. Sertakan hasil tangkapan layar dari terminal sebagai bukti keberhasilan.

Selamat belajar dan praktikkan perintah Git di proyek Anda!
