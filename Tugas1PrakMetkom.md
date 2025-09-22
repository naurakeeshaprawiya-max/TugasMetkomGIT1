# Langkah-langkah membuat repository:
1. Tanda + pada kanan atas dipilih kemudian dipilih 'New Repository' setelah itu diberi nama serta deskripsi.
![Tampilan New Repository](images/newrepository.png)

2. Repository Name diisi dan Deskripsi, kemudian visibility di-setting ke public serta add README diaktifkan. Selanjutnya, create repository dipilih.
![Tampilan New Repository](images/createrepository)

# Langkah-langkah menambahkan repository ke VSCode:
1. Anaconda Promt dibuka untuk menuju ke directory penyimpanan file dengan digunakan dir (cek directory) dan cd (change directory).
![Tampilan New Repository](images/dircd.png)
![Tampilan New Repository](images/dircd2.png)

2. Digunakan git clone dengan format git clone (linkcoderepository).
![Tampilan New Repository](images/gitclone.png)

3. Digunakan dir dan cd kembali ke repository yang dibuat dengan format dir (nama repository yang dibuat) kemudian cd (nama repository yang dibuat).
![Tampilan New Repository](images/dircd3.png)

4. Digunakan git config dengan format git config --global user.email "(nama email yang dipakai sebagai akun di GitHub)"
![Tampilan New Repository](images/gitconfig.png)

5. Kemudian digunakan juga git init.
![Tampilan New Repository](images/gitinit.png)

# Langkah-langkah membuat README:
1. Setelah itu, VSCode dibuka dan dipilih file kemudian dipilih open folder untuk membuka folder repository yang dibuat.
![Tampilan New Repository](images/openfolder.png)


2. README.md dibuka dan ditambahkan isi.
![Tampilan New Repository](images/isi.png)

3. README.md yang sudah diisi, disimpan dengan cara dipilih file kemudian dipilih save.
![Tampilan New Repository](images/save.png)

# Langkah-langkah membuat MARKDOWN:
1. Dipilih New File kemudian dinamai dengan format namafile.md kemudian diisi markdown.
![Tampilan New Repository](images/naming.png)

2. Gambar lampiran di dalam folder yang sama dimasukkan ke markdown ![Tampilan New Repository](images/naming2.png)

3. Markdown disimpan dengan cara cara dipilih file kemudian dipilih save.
![Tampilan New Repository](images/save2.png)

4. Dibuka kembali jendela Anaconda Prompt dan digunakkan git add . atau git add . "README.md".

5. Digunakan git commit -m "linkcoderepository".

6. Digunakan git push origin main.

7. Buka kembali GitHub kemudian dimuat ulang.