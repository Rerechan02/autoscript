# AUTOSCRIPT FN
- Untuk script nya belum di buat, harap bersabar ya

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?color=%2336BCF7&center=true&vCenter=true&lines=FN+PROJECT" />
</p>

![Rerechan02 card name](https://cardivo.vercel.app/api?name=F%20Store&description=Hi,%20everyone!%20and%20Nice%20to%20meet%20you%20%F0%9F%91%8B&image=https://raw.githubusercontent.com/Rerechan02/simple-xray/main/funny1.jpg?v=4&backgroundColor=%23ecf0f1&telegram=/&github=Rerechan02&pattern=leaf&colorPattern=%23eaeaea)

<h2 align="center">VPN</h2>

[![Hits](https://img.shields.io/badge/SSH-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)](https://github.com/fisabiliyusri/MANTAPV3)
[![Hits](https://img.shields.io/badge/XRAY-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)](https://github.com/fisabiliyusri/MANTAPV3)
[![Hits](https://img.shields.io/badge/SLOWDNS-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)](https://github.com/fisabiliyusri/MANTAPV3)
</h2>
<h2 align="center">Protokol Tunneling SSH</h2>

[![Hits](https://img.shields.io/badge/SSH-WEBSOCKET_&_SLOWDNS-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)](https://github.com/fisabiliyusri/MANTAPV3)
</h2>
<h2 align="center">Protokol Tunneling XRAY</h2>

[![Hits](https://img.shields.io/badge/XRAY_VLESS/VMESS/TROJAN/GRPC-WEBSOCKET_&_DNSTT-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)](https://github.com/fisabiliyusri/MANTAPV3)
</h2>

# Cara Install Script FN
- Login ke VPS kamu (VPS WAJIB PAKE AKSES ROOT )
- Login to your vps (VPS MUST ROOT)
- VPS Yang harus root ya bukan hp/pc/laptop nya
- what you have to root is your VPS, not your device

***1. MASUK KE VPS LALU COMAND***
```
sudo su
```
atau
```
sudo -i
```

***2. UPDATE TOOLS DI DALAM VPS***

```
apt-get update && apt-get upgrade -y && update-grub && sleep 2 && apt install curl -y && apt install wget -y && reboot
```
- VPS Otomatis Akan Reboot/ Hidupkan Ulang VPS

***3. Login/Masuk Lagi Ke VPS***
- Aktifkan Akses ROOT
```
sudo su
```
atau
```
sudo -i
```
***4. INSTALL SCRIPT***
- Instalasi Script FN MultiPort
- HARAP DI BACA
- VPS WAJIB PUNYA AKSES ROOT
```
Sabar ya :v
```

# SERVICE PORT SSH WEBSOCKET
- BadVPN/UDPGW     : **7300**
- SlowDNS          : **53, 5300**
- SSH WS HTTPS     : **443, 2096**
- SSH WS HTTP      : **80, 8080, 8000**


# SERVICE PORT XRAY WEBSOCKET
- Nginx            : **81**
- GRPC             : **443**
- TROJAN WS HTTP   : **80, 8080**
- VMESS  WS HTTP   : **80, 8080**
- VLESS  WS HTTP   : **80, 8080**
- TROJAN WS HTTPS  : **443, 2096**
- VMESS  WS HTTPS  : **443, 2096**
- VLESS  WS HTTPS  : **443, 2096**

# Payload Websocket Examples
- ***Payload HTTPS***
```
GET ws://[host]/ HTTP/1.1[crlf]Host: [host][crlf]Upgrade: websocket[crlf]Connection: @Rerechan02[crlf][crlf]
```

- ***Payload HTTP***
```
GET / HTTP/1.1[crlf]Host: [host][crlf]Upgrade: websocket[crlf]Connection: @Rerechan02[crlf][crlf]
```
![image](https://raw.githubusercontent.com/Rerechan02/simple-xray/main/funny2.png)<br></html>
