## exercise-git ##

1. Step command line saat menginisialisai project hingga push ke github yaitu 
     1. git init dulu , untuk inisisalisi existing project
     2. kalo bukan, git init (nama repo)
     3. git remote add origin [link http]
     4. git add . Itu seluruh file yang mengalami perubahan masuk kondisi stage
     5. git add index.html , file html yang mengalami perubhan dan dikirimkan ke kondisi stage
     6. git commit -m "Message nya apa" memberikan informasi perubahan untuk developer
     7. git push -u [Name origin] [name-branch] master/main

2. Perbedaan git reset dan git revert yaitu
Perintah git reset , akan mengembalikan file ke kondisi sebelumnya, kemudian menghapus history commit beikutnya. Perintah git revert mengembalikan file dengan tidak menghapus history commit.


3. Perbedaan GIT dan GITHUB yaitu 
Git merupakan version control, sedangkan github merupakan penyedia service untuk melakukan version control.
Kedua platform ini pada konsep kerjanya hampir sama dengan Dropbox dan Google Drive, hanya saja Git dan GitHub bekerja untuk mengolah kode script. Sedangkan DropBox dan Google Drive bertugas untuk mengolah kata.
