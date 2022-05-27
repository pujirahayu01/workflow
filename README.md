# workflow
Repository ini ditujukan untuk memenuhi tugas dari matakuliah literasi digital
Nama : Puji Rahayu 
NIM : E41200378

# Clone repository workflow
Pertama saya membuat sebuah repository dengan nama workflow pada github.
Setelah itu, saya melakukan clonning repository menggunakan gitbash dengan perintah: git clone https://github.com/pujirahayu01/workflow.git
Dilanjutkan dengan masuk pada direktori workflow dengan perintah: cd workflow

Selanjutnya saya menambahkan sebuah file dengan nama kalkulator.php . Selanjutnya saya akan memindahkan file kalkulator.php yang berada pada working area menuju
staging area dengan perintah:  git add . untuk memindahkan lebih dari satu (semua) file. Setelah berhasil, commit file tersebut dengan perintah: git commit -m "Menambahkan file kalkulator.php" , Dilanjutkan dengan perintah: git push 

Langkah berikutnya saya menambahkan deskripsi pada file kalkulator lalu, dilakukan commit kembali dengan perintah:  git commit -am "Menambahkan sebuah deskripsi pada kalkulator.php" , lalu dilanjutkan dengan perintah: git push

# Membuat branch dan melakukan merge
Saya akan menambahkan sebuah branch(cabang) dengan nama tampilan menggunakan perintah:  git checkout -b tampilan . Kini head pada repo ini berpindah dari main menuju tampilan dan dapat dilihat pada tulisan berwarna biru disebelah kanan. Selanjutnya saya membuah sebuah file yang bernama style.css pada branch tampilan. Lalu ketikkan perintah: git add .  dilanjutkan dengan perintah:  git commit -m "Menambahkan file style.css" dilanjutkan dengan perintah: git push --set-upstream origin tampilan

Selanjutnya saya ingin menggabungkan file style.css yang ada pada branch tampilan menuju branch main. Pertama berpindah terlebih dahulu ke branch main dengan perintah:  git checkout main   dilanjutkan dengan menggabungkan file style.css dengan perintah: git merge tampilan  ,dan   git push  maka penggabungan branch berhasil.

# Membuat release branch dan hotfix branch
Untuk membuat release branch cukup dengan perintah: git checkout -b release/v1.0.0  dan dilanjutkan dengan perintah: git add .  ,kemudian git commit -m "release v1.0.0" ,dan push dengan perintah: git push -u origin release/v1.0.0
Untuk membuat hotfix branch sama dengan release branch dengan perintah: git checkout -b hotfix/nama  git add .   git commit -m "hotfix/nama"  git push -u origin hotfix/nama








