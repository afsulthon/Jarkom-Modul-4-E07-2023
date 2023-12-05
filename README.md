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
  - [Pembagian IP](#pembagian-ip-2)
  - [Konfigurasi dan Routing](#konfigurasi-dan-routing)
  - [Testing](#testing-cidr)
- [Kendala](#kendala)

## Topologi
### Topologi pada Cisco Packet Tracer
Berikut adalah topologi jaringan pada Cisco.
<img width="1002" alt="Screenshot 2023-12-04 at 20 21 22" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/a3700fa2-4457-4c74-9bce-5370a96e03c9">

### Pembagian Subnet
Berikut adalah visualisasi pembagian subnet pada topologi jaringan.
<img width="1002" alt="Screenshot 2023-12-04 at 20 07 11" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/154977b9-30b4-49cf-a5a7-b46cb72f5d47">

### Topologi pada GNS3
Berikut adalah topologi jaringan pada GNS3.  
![Topologi pada GNS3](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/107914177/bf433c47-5783-4954-906c-fa32eb9f6316)

### Pembagian Subnet
Berikut adalah visualisasi pembagian subnet pada topologi jaringan.
![Subnet Map](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/107914177/5609e3dc-f0a3-4c2d-82a2-e9001623ac1d)

## VLSM
### VLSM Tree
![Jarkom4-Mantap](https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/192bf6f7-3212-44b1-9bcf-18951616ed5c)

### Pembagian IP
<img width="831" alt="Screenshot 2023-12-04 at 19 47 22" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/c724c53f-0ac1-479f-980d-98b18b91047f">

### IP berdasarkan subnetting yang sudah dibuat di dalam Packet Tracer
- Router Aura
<img width="700" alt="Screenshot 2023-12-05 at 10 16 53" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/533acc8c-2ba3-48fc-8c8f-d51c7f60c187">

- Router Frieren
<img width="699" alt="Screenshot 2023-12-05 at 10 17 58" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/6b748d88-da1f-49c0-a7e8-de824572211f">

- Router Flamme
<img width="696" alt="Screenshot 2023-12-05 at 10 18 14" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/fbff3f48-c1de-4dd6-af95-21fa0a38433d">

- Router Fern
<img width="698" alt="Screenshot 2023-12-05 at 10 18 34" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/82fd363c-5f15-4edc-a5d2-2b77c2826ed7">

- Router Himmel
<img width="695" alt="Screenshot 2023-12-05 at 10 18 45" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/1a6a96cf-3876-4b70-b8b0-46aca859c1da">

- Router Denken
<img width="697" alt="Screenshot 2023-12-05 at 10 19 01" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/c8245537-09d8-407d-99e9-bf3f19782d18">

- Router Eisen
<img width="696" alt="Screenshot 2023-12-05 at 10 19 21" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/27c49296-fd67-4ea9-a5e8-1abb53690657">

- Router Lugner
<img width="697" alt="Screenshot 2023-12-05 at 10 19 34" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/6bf9ba03-cad5-4f95-aef5-fddf7f58f3bd">

- Router Linie
<img width="696" alt="Screenshot 2023-12-05 at 10 19 48" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/dd9aed43-df32-4000-8ade-d41122b2bce8">

- Router Lawine
<img width="695" alt="Screenshot 2023-12-05 at 10 20 02" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/54ac9072-b804-4b1e-b5a2-726a3e94353a">

- Router Heiter
<img width="692" alt="Screenshot 2023-12-05 at 10 20 15" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/4bfa9a28-4cdd-43e1-9330-5aa3b22239af">

- Client LaubHills
<img width="697" alt="Screenshot 2023-12-05 at 10 43 45" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/60d2dd8d-cceb-4e23-b4f3-1477acd7b8f1">

- Client AppetitRegion
<img width="698" alt="Screenshot 2023-12-05 at 10 43 56" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/c4ae81db-180c-4d6a-be50-a35acd8ffb53">

- Client RohrRoad
<img width="692" alt="Screenshot 2023-12-05 at 10 48 01" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/3dcf3506-e3a2-41d7-af7c-3abd3983aa68">

- Client SchwerMountains
<img width="690" alt="Screenshot 2023-12-05 at 10 51 32" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/078cd52e-395f-4acf-b188-2ce5652eea97">

- Client LakeKorridor
<img width="694" alt="Screenshot 2023-12-05 at 10 51 46" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/4b467039-72b1-45d7-a57e-f57f8cb8bdb7">

- Client RoyalCapital
<img width="695" alt="Screenshot 2023-12-05 at 10 51 59" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/b430279a-c9fc-417d-80d4-d34c0e96a310">

- Client WileRegion
<img width="698" alt="Screenshot 2023-12-05 at 10 52 12" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/e29477e2-a997-4949-b03f-f79866789904">

- Server Stark
<img width="696" alt="Screenshot 2023-12-05 at 10 52 27" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/ce85ca9f-6c4b-499a-8bb0-3d03b82ad092">

- Server Richter
<img width="693" alt="Screenshot 2023-12-05 at 10 52 38" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/d194d977-e3e2-4eff-accd-713826b5d087">

- Server Revolte
<img width="697" alt="Screenshot 2023-12-05 at 10 52 52" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/4add11f6-c351-4d86-b2ea-a2d7fc0083af">

- Client TurkRegion
<img width="695" alt="Screenshot 2023-12-05 at 10 53 05" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/bf1bf779-c1b2-4960-a002-28db6d4c13a4">

- Client GrobeForest
<img width="690" alt="Screenshot 2023-12-05 at 10 53 18" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/804d1597-c702-4972-a87b-cb70cc2d8ee5">

- Client BredtRegion
<img width="697" alt="Screenshot 2023-12-05 at 10 53 30" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/a471810b-338f-4d9b-ad2f-7b31d852a6b4">

- Client RiegelCanyon
<img width="698" alt="Screenshot 2023-12-05 at 10 53 43" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/de66ca52-38e4-4f13-bdab-263e892efd8e">

- Server Sein
<img width="700" alt="Screenshot 2023-12-05 at 10 53 54" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/2026c32a-31b6-446e-b540-13e7110ce3b2">

- Client GranzChannel
<img width="695" alt="Screenshot 2023-12-05 at 10 54 04" src="https://github.com/afsulthon/Jarkom-Modul-4-E07-2023/assets/91003946/8176fc98-fb51-475d-bbdd-e8b05bbebd7c">


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

### Konfigurasi dan Routing
Berikut adalah konfigurasi jaringan tiap node pada topologi.
- Aura
```bash
auto eth0
iface eth0 inet dhcp

auto eth1
iface eth1 inet static
	address 10.40.65.1
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.40.66.34
	netmask 255.255.255.252

auto eth3
iface eth3 inet static
	address 10.40.192.9
	netmask 255.255.255.252
```
- Frieren
```bash
auto eth0
iface eth0 inet static
	address 10.40.66.33
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 10.40.16.2
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.40.66.1
	netmask 255.255.255.224
```
- Flamme
```bash
auto eth0
iface eth0 inet static
	address 10.40.16.1
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 10.40.8.2
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.40.36.9
	netmask 255.255.255.252

auto eth3
iface eth3 inet static
	address 10.40.32.1
	netmask 255.255.252.0
```
- Fern
```bash
auto eth0
iface eth0 inet static
	address 10.40.8.1
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 10.40.0.1
	netmask 255.255.248.0
```
- Himmel
```bash
auto eth0
iface eth0 inet static
	address 10.40.36.10
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 10.40.36.1
	netmask 255.255.255.248
```
- Denken
```bash
auto eth0
iface eth0 inet static
	address 10.40.65.2
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 10.40.64.1
	netmask 255.255.255.0
```
- Eisen
```bash
auto eth0
iface eth0 inet static
	address 10.40.192.10
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 10.40.146.1
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.40.168.1
	netmask 255.255.255.252

auto eth3
iface eth3 inet static
	address 10.40.176.1
	netmask 255.255.255.252

auto eth4
iface eth4 inet static
	address 10.40.192.1
	netmask 255.255.255.248
```
- Lugner
```bash
auto eth0
iface eth0 inet static
	address 10.40.168.2
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 10.40.160.1
	netmask 255.255.252.0

auto eth2
iface eth2 inet static
	address 10.40.164.1
	netmask 255.255.255.0
```
- Linie
```bash
auto eth0
iface eth0 inet static
	address 10.40.146.2
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 10.40.136.1
	netmask 255.255.252.0

auto eth2
iface eth2 inet static
	address 10.40.144.1
	netmask 255.255.254.0
```
- Lawine
```bash
auto eth0
iface eth0 inet static
	address 10.40.136.2
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 10.40.132.1
	netmask 255.255.255.192
```
- Heiter
```bash
auto eth0
iface eth0 inet static
	address 10.40.132.2
	netmask 255.255.255.192

auto eth1
iface eth1 inet static
	address 10.40.128.1
	netmask 255.255.252.0
```
- Stark
```bash
auto eth0
iface eth0 inet static
	address 10.40.176.2
	netmask 255.255.255.252
	gateway 10.40.176.1
```
- Richter
```bash
auto eth0
iface eth0 inet static
	address 10.40.192.2
	netmask 255.255.255.248
	gateway 10.40.192.1
```
- Revolte
```bash
auto eth0
iface eth0 inet static
	address 10.40.192.3
	netmask 255.255.255.248
	gateway 10.40.192.1
```
- Sein
```bash
auto eth0
iface eth0 inet static
	address 10.40.128.2
	netmask 255.255.252.0
	gateway 10.40.128.1
```
- LaubHills (397 host)
```bash
auto eth0
iface eth0 inet static
	address 10.40.0.2
	netmask 255.255.248.0
	gateway 10.40.0.1
```
- AppetitRegion (625 host)
```bash
auto eth0
iface eth0 inet static
	address 10.40.3.0
	netmask 255.255.248.0
	gateway 10.40.0.1
```
- LakeKorridor (24 host)
```bash
auto eth0
iface eth0 inet static
	address 10.40.66.3
	netmask 255.255.255.224
	gateway 10.40.66.1
```
- RohrRoad (1000 host)
```bash
auto eth0
iface eth0 inet static
	address 10.40.32.2
	netmask 255.255.252.0
	gateway 10.40.32.1
```
- RoyalCapital (63 host)
```bash
auto eth0
iface eth0 inet static
	address 10.40.64.64
	netmask 255.255.255.0
	gateway 10.40.64.1
```
- WilleRegion (63 host)
```bash
auto eth0
iface eth0 inet static
	address 10.40.64.65
	netmask 255.255.255.0
	gateway 10.40.64.1
```
- TurkRegion (1000 host)
```bash
auto eth0
iface eth0 inet static
	address 10.40.160.2
	netmask 255.255.252.0
	gateway 10.40.160.1
```
- GrobeForest (250 host)
```bash
auto eth0
iface eth0 inet static
	address 10.40.164.2
	netmask 255.255.252.0
	gateway 10.40.164.1
```
- GranzChannel (254 host)
```bash
auto eth0
iface eth0 inet static
	address 10.40.144.2
	netmask 255.255.254.0
	gateway 10.40.144.1
```
- BredtRegion (29 host)
```bash
auto eth0
iface eth0 inet static
	address 10.40.132.3
	netmask 255.255.255.192
	gateway 10.40.132.1
```
- RiegelCanyon (510 host)
```bash
auto eth0
iface eth0 inet static
	address 10.40.128.3
	netmask 255.255.252.0
	gateway 10.40.128.1
```
Berikut adalah konfigurasi routing pada tiap node.
- Aura
```bash
# kiri (frieren)
route add -net 10.40.0.0 netmask 255.255.248.0 gw 10.40.66.33 # subnet A1
route add -net 10.40.8.0 netmask 255.255.255.252 gw 10.40.66.33 # subnet A2
route add -net 10.40.32.0 netmask 255.255.252.0 gw 10.40.66.33 # subnet A3
route add -net 10.40.36.8 netmask 255.255.255.252 gw 10.40.66.33 # subnet A4
route add -net 10.40.36.0 netmask 255.255.255.248 gw 10.40.66.33 # subnet A5
route add -net 10.40.16.0 netmask 255.255.255.252 gw 10.40.66.33 # subnet A6
route add -net 10.40.66.0 netmask 255.255.255.224 gw 10.40.66.33 # subnet A7

# kanan (denken)
route add -net 10.40.64.0 netmask 255.255.255.0 gw 10.40.65.2 # subnet A10

# bawah (eisen)
route add -net 10.40.176.0 netmask 255.255.255.252 gw 10.40.192.10 # subnet A12
route add -net 10.40.192.0 netmask 255.255.255.248 gw 10.40.192.10 # subnet A13
route add -net 10.40.168.0 netmask 255.255.255.252 gw 10.40.192.10 # subnet A14
route add -net 10.40.160.0 netmask 255.255.252.0 gw 10.40.192.10 # subnet A15
route add -net 10.40.164.0 netmask 255.255.255.0 gw 10.40.192.10 # subnet A16
route add -net 10.40.146.0 netmask 255.255.255.252 gw 10.40.192.10 # subnet A17
route add -net 10.40.136.0 netmask 255.255.255.252 gw 10.40.192.10 # subnet A18
route add -net 10.40.132.0 netmask 255.255.255.192 gw 10.40.192.10 # subnet A19
route add -net 10.40.128.0 netmask 255.255.252.0 gw 10.40.192.10 # subnet A20
route add -net 10.40.144.0 netmask 255.255.254.0 gw 10.40.192.10 # subnet A21
```
- Frieren
```bash
# bind everywhere
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.40.66.34

route add -net 10.40.0.0 netmask 255.255.248.0 gw 10.40.16.1 # subnet A1
route add -net 10.40.8.0 netmask 255.255.255.252 gw 10.40.16.1 # subnet A2
route add -net 10.40.32.0 netmask 255.255.252.0 gw 10.40.16.1 # subnet A3
route add -net 10.40.36.8 netmask 255.255.255.252 gw 10.40.16.1 # subnet A4
route add -net 10.40.36.0 netmask 255.255.255.248 gw 10.40.16.1 # subnet A5
```
- Flamme
```bash
# bind everyhere
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.40.16.2

route add -net 10.40.0.0  netmask 255.255.248.0 gw 10.40.8.1 # subnet A1
route add -net 10.40.36.0 netmask 255.255.255.248 gw 10.40.36.10 # subnet A5
```
- Fern
```bash
# bind everywhere
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.40.8.2
```
- Himmel
```bash
# bind everywhere
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.40.36.9
```
- Denken
```bash
# bind everywhere
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.40.65.1
```
- Eisen
```bash
# bind everywhere
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.40.192.9

route add -net 10.40.160.0 netmask 255.255.252.0 gw 10.40.168.2 # subnet A15
route add -net 10.40.164.0 netmask 255.255.255.0 gw 10.40.168.2 # subnet A16
route add -net 10.40.136.0 netmask 255.255.255.252 gw 10.40.146.2 # subnet A18
route add -net 10.40.132.0 netmask 255.255.255.192 gw 10.40.146.2 # subnet A19
route add -net 10.40.128.0 netmask 255.255.252.0 gw 10.40.146.2 # subnet A20
route add -net 10.40.144.0 netmask 255.255.254.0 gw 10.40.146.2 # subnet A21
```
- Lugner
```bash
# bind everywhere
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.40.168.1
```
- Linie
```bash
# bind everywhere
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.40.146.1

route add -net 10.40.132.0 netmask 255.255.255.192 gw 10.40.136.2 # subnet A19
route add -net 10.40.128.0 netmask 255.255.252.0 gw 10.40.136.2 # subnet A20
```
- Lawine
```bash
# bind everywhere
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.40.136.1

route add -net 10.40.128.0 netmask 255.255.252.0 gw 10.40.132.2 # subnet A20
```
- Heiter
```bash
# bind everywhere
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.40.132.1
```

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
