# Jarkom-Modul-4-E07-2023
Laporan Resmi Praktikum Modul 4 Jaringan Komputer 2023

### Kelompok E07
| Nama | NRP |
|:----:|:---:|
| [Akmal Sulthon Fathulloh](https://github.com/afsulthon) | 5025211047 |
| [Fadilla Rizky Nurhidayah](https://github.com/fadillaarn) | 5025211110 |

## Daftar Isi
- [Topologi](#topologi)
  - [Topologi pada Cisco Packet Tracer](#topologi-pada-cisco-packet-tracer)
  - [Topologi pada GNS3](#topologi-pada-gns3)
  - [Pembagian Subnet](#pembagian-subnet)
- [VLSM](#vlsm)
  - [VLSM Tree](#vlsm-tree)
  - [Pembagian IP](#pembagian-ip)
  - [Testing](#testing)
- [CIDR](#cidr)
  - [Penggabungan IP](#penggabungan-ip)
  - [CIDR Tree](#cidr-tree)
  - [Pembagian IP](#pembagian-ip)
  - [Testing](#testing)
- [Kendala](#kendala)

## Topologi
### Topologi pada Cisco Packet Tracer
### Topologi pada GNS3
Berikut adalah topologi jaringan pada GNS3.  
![Topologi pada GNS3](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/107914177/bf433c47-5783-4954-906c-fa32eb9f6316)
### Pembagian Subnet
Berikut adalah visualisasi pembagian subnet pada topologi jaringan.
![Subnet Map](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/107914177/5609e3dc-f0a3-4c2d-82a2-e9001623ac1d)

## VLSM
### VLSM Tree
### Pembagian IP
### Testing

## CIDR
Classless Inter-Domain Routing (CIDR) adalah metode pengalamatan IP yang memungkinkan alokasi alamat yang lebih efisien dengan menggunakan panjang prefix untuk menentukan panjang subnet. Contoh implementasi CIDR adalah sebagai berikut
```
10.40.1.0/24
```
Berdasarkan alamat IP di atas, 24 bit pertama adalah bagian dari jaringan dan sisanya digunakan untuk host, memungkinkan alokasi hingga 256 alamat IP (2<sup>8</sup>) untuk perangkat dalam subnet tersebut.

### Penggabungan IP
Berikut adalah langkah-langkah penggabungan IP subnet yang telah kami tentukan sebelumnya.
#### Kondisi Semula (Subnet A)
![Subnet Map](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/107914177/b25ccd3d-3357-4c76-a075-85eeda05a2a1)  
![image](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/107914177/df8a39bf-8ea4-4b76-8a4c-3a4c3f5d3602)  

#### Penggabungan 1 (Subnet B)
![Penggabungan - 1](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/107914177/5367f035-adf1-4783-8b3e-2b190ef74a2e)  
![image](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/107914177/e5b4c923-9516-4faa-9c2e-b8052ac716fe)  

#### Penggabungan 2 (Subnet C)
![Penggabungan - 2](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/107914177/334b5ec0-f63f-407a-89b4-5917a0e914ca)  
![image](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/107914177/70901ce5-c1b6-41c2-885f-3a0b42ad9c2c)  

#### Penggabungan 3 (Subnet D)
![Penggabungan - 3](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/107914177/41d7f67d-ee70-4c6f-b1f1-2001b5638f12)  
![image](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/107914177/17ca438d-4012-4847-bc7d-cf701fb9df4b)  

#### Penggabungan 4 (Subnet E)
![Penggabungan - 4](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/107914177/d786b4a9-9254-4c77-8e65-ba6b340b1646)  
![image](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/107914177/d8efc8e6-1c6e-436d-b7cd-52536f7376f0)  

#### Penggabungan 5 (Subnet F)
![Penggabungan - 5](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/107914177/4f5ef519-2257-44e9-adf6-45b289a7e30f)  
![image](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/107914177/36da0d61-91b5-4ea1-9298-67eb24aede25)  

#### Penggabungan 6 (Subnet G)
![Penggabungan - 6](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/107914177/995f36d1-a9ec-4c5f-b44b-418a64c93433)  
![image](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/107914177/8aea6066-42ed-4473-9472-9c3dfd95d461)  

### CIDR Tree
Berikut adalah visualisasi IP tree berdasarkan penggabungan subnet yang telah dilakukan sebelumnya.
![IP Tree](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/107914177/f0d99151-c0ed-4519-9d38-8c8a41e769fd)  

### Pembagian IP
Berikut adalah tabel hasil dari pembagian IP berdasarkan tree di atas.
![image](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/107914177/da5c7c42-414e-4762-8fa7-ff7bb48eb548)

### Testing
Setelah melakukan routing, kita dapat mengecek apakah konfigurasi route sudah benar dengan memasukkan perintah sebagai berikut pada terminal.
```
route -n
```
Berikut adalah konfigurasi routing pada node Frieren.
```bash
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.40.66.34 # bind everywhere
route add -net 10.40.0.0 netmask 255.255.248.0 gw 10.40.16.1 # subnet A1
route add -net 10.40.8.0 netmask 255.255.255.252 gw 10.40.16.1 # subnet A2
route add -net 10.40.32.0 netmask 255.255.252.0 gw 10.40.16.1 # subnet A3
route add -net 10.40.36.8 netmask 255.255.255.252 gw 10.40.16.1 # subnet A4
route add -net 10.40.36.0 netmask 255.255.255.248 gw 10.40.16.1 # subnet A5
```
Setelah dilakukan pengecekan dengan perintah `route -n`, maka akan terlihat sebagai berikut.
![route](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/107914177/3804ffe7-96cf-4827-9ed5-fe000053dba0)


Selain itu, kita dapat mengetes apakah routing telah sukses dengan melakukan PING dari node ke node. Misalkan, kita melakukan PING dari client AppetitRegion menuju server Sein.
![PING](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/107914177/b789aedc-9753-4d5d-a029-3f13ad11c615)  
Kita dapat melakukan command berikut pada terminal AppetitRegion untuk meng-PING Sein. (`10.40.128.2` merupakan alamat IP dari Sein)
```
ping 10.40.128.2
```
Berikut adalah tampilan terminal ketika berhasil melakukan PING.
![ping](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/107914177/943cc860-cfc7-444d-b528-d90a03003ed4)


## Kendala
- Kurangnya informasi terkait implementasi CIDR pada topologi GNS3 di modul praktikum membuat sedikit bingung saat melakukan konfigurasi node.
- Terkadang terjadi anomali saat melakukan PING pada node tertentu di GNS3, namun ketika projek dibuka ulang PING kembali normal.