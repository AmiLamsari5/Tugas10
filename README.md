# Tugas10
# Nama  : AMI LAMSARI
# NIM : 311910534
# Kelas : TI19B2
# Backup dan Restore
# 1. Masuk ke Database
![image](https://user-images.githubusercontent.com/81812068/125197264-1a9ea900-e287-11eb-8fe0-2834005ee7c5.png)
![image](https://user-images.githubusercontent.com/81812068/125197298-3d30c200-e287-11eb-92d9-8bea6b02bf93.png)

# 2. Melakukan Proses Penguncian
![image](https://user-images.githubusercontent.com/81812068/125197437-d8299c00-e287-11eb-9eff-5764a061d26f.png)

# 3. Melakukan Backup dan Restore menggunakan perintah SQL
![image](https://user-images.githubusercontent.com/81812068/125197353-7c5f1300-e287-11eb-9c71-1bf285fbac2b.png)
![image](https://user-images.githubusercontent.com/81812068/125197406-a6183a00-e287-11eb-9bc4-c8320363e816.png)
![image](https://user-images.githubusercontent.com/81812068/125197065-7a488480-e286-11eb-859a-d197f1313253.png)

# Tulisakan script cron job untuk melakukan backupotomatis setiap hari minggu jam 12 malam !
# 1. Script Untuk menjalankan backup database setiap hari minggu jam 12 malam : script dibawah :
# 0 0 * * 7 mysqldump -u root -p31564 miftahul_311910740 > backup2.sql
