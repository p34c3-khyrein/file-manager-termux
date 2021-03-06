# Termux File Manager
![Screenshot](img/1.jpg) ![Screenshot](img/2.jpg)

---

## My Information
[![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=p34c3-khyrein&theme=blue-green)](https://github.com/anuraghazra/github-readme-stats)
<br/>
![1](https://github-readme-stats.vercel.app/api/top-langs/?username=p34c3-khyrein&theme=blue-green)

## Sosial Media
[![Custom badge](https://img.shields.io/badge/whatsapp-%23C0C0C0.svg?&style=for-the-badge&logo=whatsapp&logoColor=#25D366)](https://wa.me/6282214252455/)

## Software
[![Custom badge](https://img.shields.io/badge/termux%20-%23000000.svg?&style=for-the-badge&logo=Termumx&logoColor=white)](https://termux.com/)
[![made-for-VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)](https://code.visualstudio.com/)

## Requirements
- PHP 5.5.0 or higher.
- Fileinfo, iconv, zip, tar and mbstring extensions are strongly recommended.

## Support
Termux File Manager has tested on:
* Termux

<br/>

## Installation
```shell
pkg install git -y && pkg install php -y && cd && git clone https://github.com/p34c3-khyrein/file-manager-termux .filemanager && wget https://raw.githubusercontent.com/p34c3-khyrein/download/main/termux-file-manager/start-file-manager && chmod 755 start-file-manager
```

<br/>

## Running File Manager (First!)
### default
```shell
./start-file-manager
```
### or
```shell
bash start-file-manager
```

<br/>

## How to use ~> default port (8003)
### # mobile browser
```shell
http://localhost:8003
```
### # outside mobile phone
#### 1. turn on tethring / wifi
#### 2. check your local IP
```shell
ifconfig
```
inside **wlan0**, look at the IP number on **inet**, it is your local ip.
#### 3. open outside
```shell
http://<YOUR LOCAL IP>:8003
```

<br/>

### :loudspeaker: Features
- :cd: Open Source, light and extremely simple
- :iphone: Mobile friendly view for touch devices
- :information_source: Basic features likes Create, Delete, Modify, View, Quick Preview, Download, Copy and Move files 
- :arrow_double_up: Ajax Upload, Ability to drag & drop, upload from URL, multiple files upload with file extensions filter 
- :file_folder: Ability to create folders and files
- :gift: Ability to compress, extract files (`zip`, `tar`)
- :sunglasses: Support user permissions - based on session and each user root folder mapping
- :floppy_disk: Copy direct file URL
- :pencil2: Cloud9 IDE - Syntax highlighting for over `150+` languages, Over `35+` themes with your favorite programming style
- :page_facing_up: Google/Microsoft doc viewer helps you preview `PDF/DOC/XLS/PPT/etc`. 25 MB can be previewed with the Google Drive viewer
- :zap: Backup files and IP blacklist and whitelist
- :mag_right: Search -  Search and filter files using `datatable js`
- :file_folder: Exclude folders and files from listing
- :globe_with_meridians: Multi-language(20+) support and for translations `translation.json` is file required
- :bangbang: lots more...
