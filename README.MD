# Jarkom-Modul-4-D16-2023

**Praktikum Jaringan Komputer Modul 4 Tahun 2023**

## Author

| Nama                  | NRP        | 
| --------------------- | ---------- | 
| Dicky Indra Kuncahyo| 5025201250|
| Widian Sasi Disertasiani | 5025211024| 

# Laporan Resmi

## Topologi

![topologi](https://media.discordapp.net/attachments/1170761960443347105/1181450764992909342/WhatsApp_Image_2023-12-02_at_11.35.55.jpeg?ex=65811ac4&is=656ea5c4&hm=a2d68df714ad2d7bbfbd246d3a99e452d94b6bfeb056aa981aa69bea31cc262f&=&format=webp&width=1215&height=700)

![topologi](https://media.discordapp.net/attachments/1170761960443347105/1181451586598342686/image.png?ex=65811b88&is=656ea688&hm=4ed39e75fedc557af0b923b2150c2508c31df5fa34f3b7810b7bc20bdcf8e24f&=&format=webp&quality=lossless&width=1215&height=700)

## VLSM - GNS
### Tree
![Alt text](treevlsm.jpg)

### Tabel
![Alt text](tabelvlsm.png)


### Config

#### >Aura

```
auto eth0
iface eth0 inet dhcp

auto eth1
iface eth1 inet static
	address 192.199.24.129
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 192.199.24.129
	netmask 255.255.255.252

auto eth3
iface eth3 inet static
	address 192.199.24.133
	netmask 255.255.255.252
```

#### >Frieren

```
auto eth0
iface eth0 inet static
	address 192.199.24.130
	netmask 255.255.255.252
	gateway 192.199.24.129

auto eth1
iface eth1 inet static
	address 192.199.24.125
	netmask 255.255.255.252
```


#### >Flamme

```
#A6

auto eth0
iface eth0 inet static
	address 192.199.24.126
	netmask 255.255.255.252
	gateway 192.199.24.125

#A3

auto eth1
iface eth1 inet static
	address 192.199.8.1
	netmask 255.255.252.0

auto eth2
iface eth2 inet static
	address 192.199.24.113
	netmask 255.255.255.252


auto eth2
iface eth2 inet static
	address 192.199.24.117
	netmask 255.255.255.252
```

#### >Fern

```
#A2
auto eth0
iface eth0 inet static
address 192.199.24.114
netmask 255.255.255.252
gateway 192.199.24.113

#A1
auto eth1
iface eth1 inet static
address 192.199.0.1
netmask 255.255.248.0
```


#### >LaubHills

```
auto eth0
iface eth0 inet static
address 192.199.0.5
netmask 255.255.248.0
gateway 192.199.0.1
```

#### >ApetiteRegion

```
auto eth0
iface eth0 inet static
address 192.199.0.55
netmask 255.255.248.0
gateway 192.199.0.1
```

#### >RohrRoad

```
auto eth0
iface eth0 inet static
	address 192.199.9.0
	netmask 255.255.252.0
	gateway 192.199.8.1
```

#### >Himmel

```
#A4

auto eth0
iface eth0 inet static
	address 192.199.24.118
	netmask 255.255.255.252
	gateway 192.199.24.117

#A5

auto eth1
iface eth1 inet static
	address 192.199.24.97
	netmask 255.255.255.248
```

#### >SchewerMountains

```
#A5

auto eth0
iface eth0 inet static
	address 192.199.24.100
	netmask 255.255.255.248
	gateway 192.199.24.97
```

#### >Denken

```
auto eth0
iface eth0 inet static
	address 192.199.24.130
	netmask 255.255.255.252
	gateway 192.199.24.129

auto eth1
iface eth1 inet static
	address 192.199.22.1
	netmask 255.255.255.0
```

#### >RoyalCapital
```
auto eth0
iface eth0 inet static
	address 192.199.24.25
	netmask 255.255.255.0
	gateway 192.199.24.1
```

#### >WilleRegion

```
auto eth0
iface eth0 inet static
	address 192.199.24.50
	netmask 255.255.255.0
	gateway 192.199.24.1
```

#### >Eisen

```
auto eth0
iface eth0 inet static
address 192.199.132
netmask 255.255.255.252
gateway 192.199.24.133

auto eth1
iface eth1 inet static
address 192.199.24.137
netmask 255.255.255.252

auto eth2
iface eth2 inet static
address 192.199.24.149
netmask 255.255.255.252

auto eth3
iface eth3 inet static
address 192.199.24.105
netmask 255.255.255.248
```

#### >Richter

```
auto eth0
iface eth0 inet static
address 192.199.107
netmask 255.255.255.248
gateway 192.199.24.105
```

#### >Revolte

```
auto eth0
iface eth0 inet static
address 192.199.109
netmask 255.255.255.248
gateway 192.199.24.105

```

#### >Stark

```
auto eth0
iface eth0 inet static
address 192.199.138
netmask 255.255.255.252
gateway 192.199.24.137
```


#### >Lugner

```
auto eth0
iface eth0 inet static
address 192.199.150
netmask 255.255.255.252
gateway 192.199.24.149

auto eth1
iface eth1 inet static
address 192.199.16.1
netmask 255.255.252.0

auto eth2
iface eth2 inet static
address 192.199.23.1
netmask 255.255.255.0
```

#### >TurkRegion

```
#A21

auto eth0
iface eth0 inet static
address 192.199.16.50
netmask 255.255.255.0
gateway 192.199.16.1
```

#### >GrobeForest

```
#A20

auto eth0
iface eth0 inet static
address 192.199.23.100
netmask 255.255.255.0
gateway 192.199.23.1
```

#### >Linie

```
auto eth0
iface eth0 inet static
address 192.199.24.106
netmask 255.255.255.252
gateway 192.199.24.105

auto eth1
iface eth1 inet static
address 192.199.20.1
netmask 255.255.254.0

auto eth2
iface eth2 inet static
address 192.199.24.145
netmask 255.255.255.252
```

#### >GranzChannel

```
#A18


auto eth0
iface eth0 inet static
address 192.199.20.50
netmask 255.255.254.0
gateway 192.199.20.1
```

#### >Lawine

```
auto eth0
iface eth0 inet static
address 192.199.24.146
netmask 255.255.255.252
gateway 192.199.24.145

auto eth1
iface eth1 inet static
address 192.199.24.1
netmask 255.255.255.192
```

#### >BredtRegion

```
auto eth0
iface eth0 inet static
address 192.199.24.10
netmask 255.255.255.192
gateway 192.199.24.1
```

#### >Heiter

```
auto eth0
iface eth0 inet static
address 192.199.24.10
netmask 255.255.255.192
gateway 192.199.24.1

auto eth1
iface eth1 inet static
address 192.199.12.1
netmask 255.255.252.0
```

#### >Sein

```
auto eth0
iface eth0 inet static
address 192.199.13.0
netmask 255.255.252.0
gateway 192.199.12.1
```

#### >RiegelCanyon

```
auto eth0
iface eth0 inet static
address 192.199.14.0
netmask 255.255.252.0
gateway 192.199.12.1
```


## CIDR - CISCO 
### Penggabungan

![topologi](https://media.discordapp.net/attachments/1170761960443347105/1181452039235063858/image.png?ex=65811bf4&is=656ea6f4&hm=4dbc124225e5f3f9eccb9d0ac1ef488dfa1e8f6edb15f4b801d7d720a581d99b&=&format=webp&quality=lossless&width=1002&height=588)

![topologi](https://media.discordapp.net/attachments/1170761960443347105/1181452134978441276/image.png?ex=65811c0b&is=656ea70b&hm=952112b9b9746cd7761ee2cc3d45de06afde24fcca1edb3a64791e745fcfe569&=&format=webp&quality=lossless&width=936&height=700)

![topologi](https://media.discordapp.net/attachments/1170761960443347105/1181452226393276426/image.png?ex=65811c21&is=656ea721&hm=8501f6bf67ecbfc52bf8f639603309041443d35ac2931e2fa779d26961fed0e3&=&format=webp&quality=lossless&width=998&height=512)

![topologi](https://media.discordapp.net/attachments/1170761960443347105/1181455932199280660/287452336-df220014-cfe3-4142-8c02-6c6fbf0d9710.png?ex=65811f94&is=656eaa94&hm=de9b58c7f67d83534aa252f18c336b942d01cef4e2ef8fb625e442b689648c79&=&format=webp&quality=lossless&width=1440&height=649)


### Tree
![topologi]( https://media.discordapp.net/attachments/1170761960443347105/1181456734250881144/image.png?ex=65812053&is=656eab53&hm=d7dc5acbe7c8f079c5b0f7e8dbdd16ea579cd6dc7317e8bbfc73531de84fa0dd&=&format=webp&quality=lossless&width=1440&height=618)


### Table
![topologi]( https://media.discordapp.net/attachments/1170761960443347105/1181457026975551569/image.png?ex=65812099&is=656eab99&hm=fc2a32d4cb244e2fb2c52f60d37a838e64ba0d7cba19a512e80a1166b91f8747&=&format=webp&quality=lossless&width=1369&height=649 )

### Setting Cisco
Contoh Setting pada Aura dan Frieren


Aura

![Alt text](image.png)
![Alt text](image-1.png)
![Alt text](image-2.png)
![Alt text](image-3.png)
![Alt text](image-4.png)
![Alt text](image-5.png)

Frieren

![Alt text](image-6.png)
![Alt text](image-7.png)
![Alt text](image-8.png)
![Alt text](image-9.png)

### Contoh apabila berhasil

![Alt text](image-10.png)
