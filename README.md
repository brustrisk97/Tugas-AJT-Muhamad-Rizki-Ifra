# Tugas-AJT-Muhamad-Rizki-Ifra
Mahasiswa Filkom UB
<br>Tugas 1 Membuat Instance EC2 </br>
<br> ![ajt 1 (1)](https://user-images.githubusercontent.com/31241550/172861576-923ff7ee-3e80-4408-b181-ce230a078f14.png)</br>
<br> ![ajt 2 (1)](https://user-images.githubusercontent.com/31241550/172861659-b10b7349-29a3-428c-a91f-59d176211aa1.png)</br>
<br> ![ajt 3 (1)](https://user-images.githubusercontent.com/31241550/172862016-54dc311f-b62c-4b02-8755-b828ff43a0f4.png)</br>
<br> ![ajt 4 (1)](https://user-images.githubusercontent.com/31241550/172862094-b3505370-52cd-49b5-a7c3-be0e5b7cddd4.png)</br>
<br>1. Kemudian Menginstall Mininet, Mininet adalah aplikasi yang berguna untuk menciptakan jaringan virtual yang mampu menjalankan real kernel serta switch dan kode aplikasi </br>
<br> ![ajt 5 (1)](https://user-images.githubusercontent.com/31241550/172862177-c64c4db5-c66e-4bc0-9884-f0860a55090b.png) </br>
<br>2. Selanjutnya menginstall OpenFlow, OpenFlow adalah protokol yang berada pada control dan forwarding layer yang berguna untuk membangun jaringan virtual berbasis SDN</br>
<br> ![ajt 6 (1)](https://user-images.githubusercontent.com/31241550/172862275-d1ed903a-ce52-4e75-b54f-837644f7bce9.png) </br>
<br>3. Selanjutnya yaitu Ryu, Ryu merupakan salah satu controller yang digunakan pada SDN, ryu merupakan Open Source yang dikembangkan oleh NTT
<br> ![ajt 7 (1)](https://user-images.githubusercontent.com/31241550/172862388-3ac89f21-d935-406a-b1df-d16f2437796e.png) </br>
<br></br>
<br></br>
<br></br>
<br> Tugas 2 Membuat Custom Topology Sederhana </br>
<br>pada tugas ini membuat sebuah topologi sederhana yang mampu menghubungkan 6 host dengan 3 switch seperti pada gambar berikut</br>
<br>![ajt tgs 2 (3)](https://user-images.githubusercontent.com/31241550/172866211-4657115e-23d3-4d73-95e9-0c5205af69e9.png)</br>
<br>1. berikut coding untuk membuat topologi seperti gambar diatas</br>
<br> ![ajt tgs 2 (1)](https://user-images.githubusercontent.com/31241550/172866515-de9b33ac-7110-420e-aa44-83241f249b23.png) </br>
<br> ![asdad](https://user-images.githubusercontent.com/31241550/172868007-8132c624-d42a-40fd-a4b7-230cb2bbb7c9.png) </br>
<br>2. selanjutnya jalankan topologi yang sudah dibuat di mininet dengan "sudo mn --controller=none --custom tugas2.py --topo mytopo --mac --arp", setelah itu buat flow agar h1 dapat terhubung dengan h2, kemudian uji koneksi dari h1 ke h2 </br>
<br> ![ajt tgs 2 (2)](https://user-images.githubusercontent.com/31241550/172867785-fa97182b-adfd-401e-80c7-506e8084f613.png)</br>
<br></br>
<br></br>
<br></br>
<br> Tugas 3 Membuat Aplikasi Ryu Balancer </br>
<br> pada tugas ini yaitu membuat aplikasi ryu balancer dengan menggunakan topologi yang terdiri atas 4 host dan 1 switch dengan h1 sebagai web client dan h2,h3,h4 sebagai web server</br>
<br> namun pada tugas ini saya masih mengalami kendala, saya sudah mencoba clone github bapak tetapi terjadi error pada coding rr_lb.py sedangkan topo_lb.py berhasil dijalankan </br>
<br>1. menjalankan "sudo python3 topo_lb.py" untuk menjalankan topologi </br>
<br>![ajt tgs 3 (1)](https://user-images.githubusercontent.com/31241550/172870271-7a4cd89e-cdfe-43fa-a8c5-d3aedd521c80.png)</br>
<br>2. error yang saya dapatkan </br>
<br> ![ajt tgs 3 (2)](https://user-images.githubusercontent.com/31241550/172870974-ec0e1205-81ec-495a-a7f9-dc9dd463a238.png) </br>
<br></br>
<br></br>
<br></br>
<br> Tugas 4 Membuat Aplikasi Ryu SPF Routing </br>
<br> pada tugas ini yaitu membuat aplikasi Ryu SPF Routing yang digunakan untuk mencari jalur terpendek </br>
<br> namun pada tugas ini saya mencoba instance EC2 saya yang lama, dikarena terjadi error </br>
<br> 1. setelah melakukan gitclone "https://github.com/abazh/learn_sdn/tree/main/SPF" selanjutnya yaitu jalankan "ryu-manager --observe-links dijkstra_Ryu_controller.py" pada terminal 1 </br>
<br> ![ajt tgs 4 (1)](https://user-images.githubusercontent.com/31241550/172871896-806f6acf-c6b8-45ac-895d-f205faf95303.png)</br>
<br> 2. kemudian menjalankan "sudo python3 topo-spf_lab.py" pada terminal 2 dan lakukan uji koneksi misal "h1 ping -c h4 >
<br> ![ajt tgs 4 (2)](https://user-images.githubusercontent.com/31241550/172872029-13780de8-249b-45b0-a644-ebe892092384.png)</br>




