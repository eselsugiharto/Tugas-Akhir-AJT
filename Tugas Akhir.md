# Muhammad Esel Sugiharto
# 195150307111034
# Tugas-Akhir-AJT
## Tugas 1
Buat EC2 Instance di AWS Academy:
•	Name and tags: Tugas Akhir
•	OS Images: Ubuntu Server 22.04 LTS 64 bit
•	Instance type: t2.medium
•	Key pair: vockey
•	Edit Network settings: allow SSH, allow HTTP, allow HTTPS, allow TCP port 8080, allow TCP port 8081
•	Configure storage: 30 GiB, gp3

Setelah EC2 Instance siap, lakukan instalasi Mininet+OpenFlow, Ryu dll.

![image](https://user-images.githubusercontent.com/99634757/172603722-2ebc870a-1150-446d-a068-9802b3e88891.png)

## Tugas 2
Membuat program sederhana untuk custom topology dengan 6 host dan 3 switch, lalu membuat flow nya terhubung ke seluruh host nya dan sekalian diuji koneksi nya.

![image](https://user-images.githubusercontent.com/99634757/172603824-14f4b8e0-1e69-426a-a3b0-2ce71198ff38.png)

## Tugas 3
Membuat load balancer. Load balancing adalah proses pembagian beban traffic sebuah aplikasi atau server. Dengan load balancer, beban traffic tidak akan dibebankan kepada beberapa jalur koneksi. Hal ini mempercepat waktu respons server Anda dan mencegahnya dari overloading. Dengan begini, kinerja server Anda akan lebih maksimal tidak peduli berapa banyak traffic yang Anda dapatkan.

![image](https://user-images.githubusercontent.com/99634757/172603983-13131479-367c-4e20-a35a-41864bd93b30.png)
![image](https://user-images.githubusercontent.com/99634757/172604077-5bb8b322-3401-47b9-a490-487cb195aef7.png)

## Tugas 4
Menggunakan gitclone untuk menyalin repository dari https://github.com/abazh/learn_sdn.git pada terminal satu dan mengganti direktori ke learn_sdf/SPF pada terminal 1.
Menulis kode ‘ryu-manager --observe-links dijkstra_Ryu_controller.py’ pada terminal 1.
Screenshot terminal 1:

Terminal 1:

![image](https://user-images.githubusercontent.com/99634757/172604193-12cb7ce6-c05e-4d8c-8f40-fffd6ea2f67f.png)

Mengganti direktori ke learn_sdn/SPF seperti pada terminal 1 dan menuliskan perintah ‘sudo python3 topo-spf_lab.py’ pada terminal 2:

Terminal 2:

![image](https://user-images.githubusercontent.com/99634757/172604282-94c9f18c-908a-4352-8705-698d043a765c.png)

Mengecek konektivitas ping: h1 ping -c 4 h4.

Terminal 2:

![image](https://user-images.githubusercontent.com/99634757/172604448-72dfcf39-0d9c-4c6e-8aa4-5c2cd15924ff.png)

Terminal 1:

![image](https://user-images.githubusercontent.com/99634757/172604521-d838304a-f0e6-4e3b-967a-c1541ce2efc0.png)



