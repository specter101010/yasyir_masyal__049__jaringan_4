# yasyir_masyal__049__jaringan_4

  <table>
        <tr>
            <th>Nama</th>
            <td>: yasyir masy'al</td>
        </tr>
        <tr>
            <th>Kelas</th>
            <td>: Tk 4 B</td>
        </tr>
        <tr>
            <th>Nim</th>
            <td>: 09030282327049</td>
        </tr>
    </table>


<h1 style="font-weight: bold;">
SWITCHING IN CISCO
</h1 >

<h2>Topologi</h2>
 <img  src="topologi 1.png" alt="cable"  width="300px">
 
<h2>Mengubah Nama Switch</h2>
 <img  src="Mengubah Nama Switch.png" alt="cable"  width="300px">
 
<h2>Membuat Banner</h2>
 <img  src="Membuat Banner.png" alt="cable"  width="300px">
 
<h2>Membuat Sandi / Password</h2>
 <img  src="Membuat Sandi  Password.png" alt="cable"  width="300px">
 
<h2>Membuat Settingan U/Telnet</h2>
 <img  src="Membuat Settingan UTelnet.png" alt="cable"  width="300px">
 
<h2>Membuat Settingan VLAN</h2>
 <img  src="Membuat Settingan VLAN.png" alt="cable"  width="300px">
 
<h2>Konfigurasi member port untuk VLAN</h2>
 <img  src="Konfigurasi member port untuk VLAN.png" alt="cable"  width="300px">
 
<h2>Menyimpan konfigurasi di NVRAM</h2>
 <img  src="Menyimpan konfigurasi di NVRAM.png" alt="cable"  width="300px">
 
<h2>Melihat daftar VLAN</h2>

<br>
<br>
<br>

<h2>Topologi</h2>
 <img  src="topologi 2.png" alt="cable"  width="300px">

<h2>Melihat daftar VLAN</h2>
 
<h2 style="font-weight: bold;">Konfigurasi SWITCH VTP SERVER</h2>
<h2>Membuat Nama pada Switc</h2>

<h2>Membuat Banner</h2>
 <img  src="Membuat Banner SERVER.png" alt="cable"  width="300px">
 
<h2>Membuat Sandi / Password</h2>
 <img  src="Membuat Sandi  Password SERVER.png" alt="cable"  width="300px">

<h2>Membuat Settingan U/ Telnet</h2>
 <img  src="Membuat Settingan U Telnet SERVER.png" alt="cable"  width="300px">

<h2>Membuat Settingan VLAN</h2>
 <img  src="Membuat Settingan VLAN SERVER.png" alt="cable"  width="300px">

<h2>Konfigurasi VLAN untuk member port</h2>
 <img  src="Konfigurasi VLAN untuk member port SERVER.png" alt="cable"  width="300px">

<h2>Konfigurasi Server VTP</h2>
 <img  src="Konfigurasi Server VTP SERVER.png" alt="cable"  width="300px">

<h2>Konfigurasi pada Port Trunk</h2>
 <img  src="Konfigurasi pada Port Trunk SERVER.png" alt="cable"  width="300px">

<h2>Menyimpan konfigurasi di NVRAM</h2>
 <img  src="Menyimpan konfigurasi di NVRAM SERVER.png" alt="cable"  width="300px">

<h2 style="font-weight: bold;">Konfigurasi SWITCH VTP CLIENT</h2>

<h2>Membuat Nama pada Switch</h2>
 <img  src="Membuat Nama pada Switch CLIENT.png" alt="cable"  width="300px">
 
<h2>Membuat Banner</h2>
 <img  src="Membuat BanneR CLIENT.png" alt="cable"  width="300px">

<h2>Membuat sandi / password</h2>
 <img  src="Membuat sandi  password CLIENT.png" alt="cable"  width="300px">

<h2>Konfigurasi VLAN untuk member port</h2>
 <img  src="Konfigurasi VLAN untuk member port CLIENT.png" alt="cable"  width="300px">

<h2>Konfigurasi Server VTP</h2>

<h2>Konfigurasi pada Port Trunk</h2>
 <img  src="Konfigurasi pada Port Trunk CLIENT.png" alt="cable"  width="300px">

<h2>Menyimpan konfigurasi di NVRAM</h2>
 <img  src="Menyimpan konfigurasi di NVRAM CLIENT.png" alt="cable"  width="300px">

<h2 style="font-weight: bold;">Melihat status VTP pada SERVER</h2>
 <img  src="Melihat status VTP pada SERVER.png" alt="cable"  width="300px">

<h2 style="font-weight: bold;">Melihat status VTP pada CLIENT</h2>
 <img  src="Melihat status VTP pada CLIENT.png" alt="cable"  width="300px">
 
<h2 style="font-weight: bold;">Melihat status VTP pada SERVER</h2>
 <img  src="Melihat status VTP pada SERVER_TRUNK.png" alt="cable"  width="300px">

<h2 style="font-weight: bold;">Melihat status VTP pada CLIENT</h2>
 <img  src="Melihat status VTP pada CLIENT TRUNK.png" alt="cable"  width="300px">

<h1 style="font-weight: bold;">
Analisis
</h1 >

<ul>
  <li>
       VLAN digunakan untuk membagi jaringan dalam satu switch agar lebih terstruktur dan aman. Setiap VLAN memiliki subnet berbeda, sehingga komunikasi antar VLAN membutuhkan router atau inter-VLAN routing.
  </li>
  <li>
    VTP (VLAN Trunking Protocol) mempermudah pengelolaan VLAN di jaringan multi-switch. Server VTP membuat dan menyebarkan VLAN ke Client VTP, sehingga konfigurasi VLAN lebih efisien.
  </li>
  <li>
    Port Trunk memungkinkan lalu lintas beberapa VLAN melewati satu link antar-switch, memastikan VLAN tetap terhubung di seluruh jaringan.
  </li>
  <li>
    Verifikasi dengan show vlan brief, show interface trunk, dan show vtp status menunjukkan apakah konfigurasi sudah benar dan VLAN telah terdistribusi ke semua switch.
  </li>
</ul>

 
    
    
    


<h1 style="font-weight: bold;">
Kesimpulan
</h1 >

<ul>
  <li>
VLAN digunakan untuk membagi jaringan secara logis dalam satu switch, meningkatkan keamanan dan efisiensi jaringan.
  </li>
  <li>
VTP mempermudah pengelolaan VLAN di jaringan dengan banyak switch, karena semua VLAN dibuat di satu switch (server) dan otomatis didistribusikan ke switch lainnya (client).
  </li>
  <li>
Port trunk sangat penting untuk menghubungkan switch dalam jaringan berbasis VLAN, memungkinkan lalu lintas VLAN melewati satu link fisik.
  </li>
  <li>
Dengan konfigurasi ini, setiap PC dalam VLAN yang sama dapat saling berkomunikasi, sedangkan VLAN yang berbeda tidak bisa berkomunikasi langsung tanpa inter-VLAN routing.
  </li>
  <li>
Verifikasi dengan show vlan brief, show interface trunk, dan show vtp status menunjukkan apakah konfigurasi sudah berjalan dengan ba
  </li>
</ul>






 

