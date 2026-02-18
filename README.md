# Remaked Bot Unofficial🤖<sub><sub>v3.0.0🚀</sub></sub>
<p align="center">
    <a href="https://nodejs.org/dist/v20.17.0"><img src="https://img.shields.io/badge/Nodejs%20Support-20.x-brightgreen.svg?style=flat-square" alt="Nodejs Support v20.x"></a>
    <img alt="size" src="https://img.shields.io/github/repo-size/LunarKrystal/Mirai.svg?style=flat-square&label=size">
    <img alt="code-version" src="https://img.shields.io/badge/dynamic/json?color=red&label=code%20version&prefix=v&query=%24.version&url=https://raw.githubusercontent.com/LunarKrystal/Mirai/refs/heads/main/package.json&style=flat-square">
    <a href="https://github.com/LunarKrystal/Mirai/commits"><img alt="Commits" src="https://img.shields.io/github/commit-activity/m/LunarKrystal/Mirai.svg?label=commit&style=flat-square"></a>
<img alt="Visitors" src="https://visitor-badge.laobi.icu/badge?page_id=LunarKrystal.Mirai">
<img alt="size" src="https://img.shields.io/badge/license-GPL--3.0-green?style=flat-square&color=brightgreen">

## 📜 **Installation**

Sau đây là các bước cơ bản để có thể cài đặt và vận hành.

### 💡 **Yêu cầu**

- Dung lượng của máy phải trống tầm 1-2gb.
- Ưu tiên acc cơlồn cờlôn tránh bị cấm acc chính lại kêu tại bố m
- Cần mấy cái ngôn lồn để sửa cái lệnh hót ửa cho nó tap nổ con mẹ nó thông báo!
- Đối với:(TẤT CẢ PHẢI LÀ ARMHF,VÀO TERMUX ĐẦU TIÊN PHẢI NHẬP
  ```
  uname -a
  ```
  XONG GỬI TAO,KHÔNG GỬI LÀ KHÔNG CÓ HD VẬN HÀNH BOT
  https://facebook.com/lov3nse
    - Linux: Cần cài đặt python3, Node 20.19.0 (Chắc đéo gì mn đã có linux hâh)
    - Android Sử dụng termux để vận hành bot(hoặc root con mẹ nó máy rồi mount fs của kali vào là ngon luôn hâhha)

### ⚙️ **Cài Đặt (ĐÉO DÀNH CHO WINDOWS,CHỈ DÀNH CHO ARMHF ANDROID HOẶC LINUX)*
***LẤY APPSTATE VÀ COOKIE:***
-Lên Google Play Store cài kiwi browser về,mở lên đăng nhập fb,xong mở chrome web store cài cái gì c3c ufc utility(để lấy appstate) và get cookie token cho fb(chọn cái nào đều dc) xong tự nghiên cứu đi vì là free fix
***CÀI ĐẶT CHO TERMUX CHO MẤY BỌN ANDROID QUÈN:*** 
### Dán cái này lúc mới vào Termux (lưu ý phải cấp quyền truy cập file cho Termux nhé)
- ```apt update && apt upgrade -y && apt install proot-distro -y && proot-distro install ubuntu && proot-distro login ubuntu```
### sau khi đã vào root@localhost#:~# 
- ```
  apt update
  apt upgrade -y
  apt-get install -y git curl sudo
  curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
  sudo apt-get install -y nodejs
  wget https://www.mediafire.com/file/rc683nnabbqs43e/RemakedBot.zip/file?dkey=jbhigdjgwdm&r=1307
  #ĐOẠN WGET MÀ KHÔNG ĐƯỢC THÌ NHẮN LÊN NHÓM DIỆT ỬA ĐỂ T GIÚP
  unzip RemakedBot.zip
  cd RemakedBot
  nano cookie.txt
  #LÚC NÀH CMAY DÁN COOKIE VÀO RỒI LƯU LẠI,CÁI DẤU ^ LÀ CTRL NÊN ĐỪNG HỎI NHIỀU SCLSCLSCL=))
  #LƯU XONG CÒN CÁI NÀY NỮA CHỨ CHƯA XONG ĐÂU HÂHHA
  nano appstate.json
  #DÁN APPSTATE VÀO RỒI LƯU LẠI GIỐNG CÁCH LƯU COOKIE
  ```
  -Chỉnh sửa file config:Tự đi mà thay:))
  Trêu xíu hoyy,thay mấy cái số lồn mà 11 10 số gì gì ở BOXADMIN NDH này nọ bằng id fb của mn,link fb thay luôn cũng được
  ```
   nano config.json
  #thay các kiểu thông tin của cmay vào rồi lưu lại như cách lưu 2 cái lồn cookie appstate
  ```
  -Lưu xong bật con mẹ bot lên chơi thôi hâhhah
  ```
  node index
  ```
### Đối với lần chạy bot tiếp theo
- `proot-distro login ubuntu`
- Sau đó `cd` vào file bot của bạn và nhập `node index` là được
