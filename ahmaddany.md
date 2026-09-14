# 1. Menampilkan direktori saat ini
pwd

<img width="800" height="600" alt="1" src="https://github.com/user-attachments/assets/a8df5361-59c6-43e6-ab0b-6b59e07cf295" />


# 2. Menampilkan daftar file dan folder
ls

<img width="800" height="600" alt="2" src="https://github.com/user-attachments/assets/b287e682-9bf7-4773-b3ad-098841c48ab5" />


# 3. Menampilkan file secara detail
ls -l

<img width="800" height="600" alt="3" src="https://github.com/user-attachments/assets/f4ecc217-f1be-477c-8922-fc254959f3e0" />


# 4. Menampilkan file tersembunyi
ls -a

<img width="800" height="600" alt="4" src="https://github.com/user-attachments/assets/94928c6c-d39d-4cf7-9a1d-98cb5f6090b3" />


# 5. Menampilkan nama user yang sedang digunakan
whoami


<img width="800" height="600" alt="5" src="https://github.com/user-attachments/assets/d5222e7e-2242-486e-9981-bcb2ffd7c4db" />


# 6. Menampilkan nama komputer
hostname


<img width="800" height="600" alt="6" src="https://github.com/user-attachments/assets/09a455fe-a49f-4e36-8495-984ebe746f95" />


# 7. Menampilkan tanggal dan waktu
date


<img width="800" height="600" alt="7" src="https://github.com/user-attachments/assets/4c512e3b-31bb-4ab9-8996-93ed0e40fbab" />


# 8. Menampilkan kalender
cal


<img width="800" height="600" alt="8" src="https://github.com/user-attachments/assets/41d5babf-1648-48c8-b6ac-9d5a32dfa4c0" />


# 9. Menampilkan informasi kernel dan sistem
uname -a


<img width="800" height="600" alt="9" src="https://github.com/user-attachments/assets/90a01ab2-cc4c-485f-8bf3-b89962263361" />


# 10. Menampilkan versi Ubuntu
lsb_release -a


<img width="800" height="600" alt="10" src="https://github.com/user-attachments/assets/0db06a81-119e-4d2e-bde8-f375048f5667" />


# 11. Membersihkan terminal
clear


<img width="800" height="600" alt="11" src="https://github.com/user-attachments/assets/35463a57-1e5f-437f-9afb-c5bf57e822b6" />


# 12. Membuat folder bernama latihan
mkdir latihan


<img width="800" height="600" alt="12" src="https://github.com/user-attachments/assets/a5fb8501-57a4-4650-acdd-8dd709c314ab" />


# 13. Masuk ke folder latihan
cd latihan


<img width="800" height="600" alt="13" src="https://github.com/user-attachments/assets/e2d54063-2f26-476d-8012-a4e10a77bcf2" />


# 14. Membuat file kosong
touch file1.txt


<img width="800" height="600" alt="14" src="https://github.com/user-attachments/assets/bda2d325-cbd2-44ff-9465-5c3a8cfaf197" />


# 15. Menulis teks ke dalam file
echo "Hello Ubuntu" > file1.txt


<img width="800" height="600" alt="15" src="https://github.com/user-attachments/assets/3f8c2984-495b-480e-a0a8-04118f471f61" />


# 16. Menampilkan isi file
cat file1.txt


<img width="800" height="600" alt="16" src="https://github.com/user-attachments/assets/6b29a420-168c-47ba-b5d2-a29c8f2a9318" />


# 17. Menambahkan teks ke file
echo "Belajar Linux" >> file1.txt


<img width="800" height="600" alt="17" src="https://github.com/user-attachments/assets/2d169501-205f-4f1d-be2f-b3a48417033f" />


# 18. Menampilkan isi file setelah ditambahkan
cat file1.txt


<img width="800" height="600" alt="18" src="https://github.com/user-attachments/assets/df227eb0-4f3f-493f-9840-a48df397cb6c" />


# 19. Menyalin file
cp file1.txt file2.txt


<img width="800" height="600" alt="19" src="https://github.com/user-attachments/assets/a96f90a1-2d05-4d08-a9e2-cd7edaa83ad0" />


# 20. Melihat file yang tersedia
ls -l


<img width="800" height="600" alt="20" src="https://github.com/user-attachments/assets/f1e79a0a-0d78-4672-b539-94124b84b17d" />


# 21. Mengubah nama file
mv file2.txt file_baru.txt


<img width="800" height="600" alt="21" src="https://github.com/user-attachments/assets/1511d94f-a8d7-4862-a75a-7f65a38bff17" />


# 22. Menampilkan daftar file
ls


<img width="800" height="600" alt="22" src="https://github.com/user-attachments/assets/54f74ff9-7dfe-44a4-ab33-48c8a5627711" />


# 23. Membuat folder baru
mkdir folder1


<img width="800" height="600" alt="23" src="https://github.com/user-attachments/assets/af150237-032f-48ad-8ce2-800e04d8b24a" />


# 24. Menyalin file ke folder
cp file1.txt folder1/


<img width="800" height="600" alt="24" src="https://github.com/user-attachments/assets/ab07607f-3af7-4f74-a02f-a96dad8ed68e" />


# 25. Melihat isi folder
ls folder1


<img width="800" height="600" alt="25" src="https://github.com/user-attachments/assets/c8f19dc6-2de4-49d6-8025-544dc1cabc14" />


# 26. Mencari file
find . -name "file1.txt"


<img width="800" height="600" alt="26" src="https://github.com/user-attachments/assets/bd906009-80eb-458e-ae91-fd179fd0db8d" />


# 27. Mencari kata Ubuntu dalam file
grep "Ubuntu" file1.txt


<img width="800" height="600" alt="27" src="https://github.com/user-attachments/assets/dc494b80-2c08-4b48-a808-a2982790d050" />


# 28. Menampilkan 10 baris pertama file
head file1.txt


<img width="800" height="600" alt="28" src="https://github.com/user-attachments/assets/d1557bd7-4d6f-42f1-89fc-7f7a45161da4" />


# 29. Menampilkan 10 baris terakhir file
tail file1.txt


<img width="800" height="600" alt="29" src="https://github.com/user-attachments/assets/52890597-ff0d-4c72-ad55-4097a0801d12" />


# 30. Menghitung baris, kata, dan karakter
wc file1.txt


<img width="800" height="600" alt="30" src="https://github.com/user-attachments/assets/c3049102-1ba9-4e1b-bc01-7741545614b8" />


# 31. Melihat ukuran folder saat ini
du -sh .


<img width="800" height="600" alt="31" src="https://github.com/user-attachments/assets/a00bb577-ae34-4e77-878f-8ac41cc48044" />


# 32. Melihat kapasitas penyimpanan
df -h


<img width="800" height="600" alt="32" src="https://github.com/user-attachments/assets/4d093423-ddf2-4b6a-a8ba-1ff01af237cd" />


# 33. Melihat penggunaan RAM
free -h


<img width="800" height="600" alt="33" src="https://github.com/user-attachments/assets/18618cba-f4a3-4d6b-94f7-6ea1bf0fc6e2" />


# 34. Melihat proses yang sedang berjalan
ps


<img width="800" height="600" alt="34" src="https://github.com/user-attachments/assets/6e51ca63-3371-4c15-ab9e-227f1f6a017a" />


# 35. Melihat semua proses
ps aux


<img width="800" height="600" alt="35" src="https://github.com/user-attachments/assets/97485c88-234e-45be-b670-a9c7cd63a106" />


# 36. Melihat proses secara realtime
top


<img width="800" height="600" alt="36" src="https://github.com/user-attachments/assets/8875d133-3fa2-4726-9cfc-f5cc0430c9db" />


# 37. Melihat alamat IP
ip addr


<img width="800" height="600" alt="37" src="https://github.com/user-attachments/assets/19080660-a3f9-40d3-949b-7f2802ed7e3a" />


# 38. Melihat routing jaringan
ip route


<img width="800" height="600" alt="38" src="https://github.com/user-attachments/assets/c71c2631-a726-4ede-90f3-50644ded45b7" />


# 39. Mengecek koneksi internet
ping -c 4 google.com


<img width="800" height="600" alt="39" src="https://github.com/user-attachments/assets/ceea3773-08da-498c-bfb5-ff50e4a3a629" />


# 40. Mengetahui lokasi command bash
which bash


<img width="800" height="600" alt="40" src="https://github.com/user-attachments/assets/a8717ca6-5b03-44b4-af5f-582bea0e542b" />


# 41. Mengetahui lokasi Python 3
which python3


<img width="800" height="600" alt="41" src="https://github.com/user-attachments/assets/5ec5abd5-86e6-40e9-b2a2-9f648bb24fb0" />


# 42. Melihat versi Python 3
python3 --version


<img width="800" height="600" alt="42" src="https://github.com/user-attachments/assets/ae1b7fdd-edb9-4e8b-a152-bef159b388ac" />


# 43. Melihat isi folder /home
ls /home


<img width="800" height="600" alt="43" src="https://github.com/user-attachments/assets/72e7818d-628e-4830-b625-0a50ef18190a" />


# 44. Melihat isi folder /etc
ls /etc


<img width="800" height="600" alt="44" src="https://github.com/user-attachments/assets/7ddf5073-dbda-45a0-ade6-f23bb8f53f97" />


# 45. Melihat isi folder /var
ls /var


<img width="800" height="600" alt="45" src="https://github.com/user-attachments/assets/0bba468c-9d7b-42e2-abbb-86cb7e5ae3af" />


# 46. Memperbarui daftar paket Ubuntu
sudo apt update


<img width="800" height="600" alt="46" src="https://github.com/user-attachments/assets/68b26135-4183-4f37-be73-5f96605fa1f9" />


# 47. Melihat paket yang dapat diperbarui
apt list --upgradable


<img width="800" height="600" alt="47" src="https://github.com/user-attachments/assets/86da6748-36ec-41cd-bcab-d77eea1c89ab" />


# 48. Melihat riwayat command
history


<img width="800" height="600" alt="48" src="https://github.com/user-attachments/assets/0736d546-b6fd-4a98-84bc-3d272bb2e85a" />


# 49. Kembali satu folder
cd ..


<img width="800" height="600" alt="49" src="https://github.com/user-attachments/assets/431d438c-70e3-4e46-b4bd-98d8a76522bd" />


# 50. Menghapus folder latihan beserta isinya
rm -rf latihan


<img width="800" height="600" alt="50" src="https://github.com/user-attachments/assets/953ed654-2959-4575-85e1-aae411475e10" />
