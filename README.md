<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=powershell,devto" />
  </a>
</p>

## Step 1. Kết nối cùng mạng với Gateway

<h1 align="center">🤜🏼 Do it yourself 🤛🏼 </h1>

## Step 2. Nạp Firmware vào Gateway

<h3 style="color:green;">1. Tại đường dẫn chứa file Firmware Gateway (.tar.gz) </h3>

```
scp <Firmware_Gateway>.tar.gz root@<IP_Gateway>:~
```

`<Firmware_Gateway>`: Tên file Firmware Gateway với đuôi .tar.gz

`<IP_Gateway>`: IP của Gateway

<h3 style="color:green;">2. Nhập mật khẩu của gateway </h3>

```
H0meGW@VnT3ch
```

## Step 3. Nạp firmware tại Gateway

<h3 style="color:green;">1. SSH tới gateway </h3>

```
ssh root@<IP_Gateway>
```

`<IP_Gateway>`: IP của Gateway

<h3 style="color:green;">2. Nhập mật khẩu của gateway </h3>

```
H0meGW@VnT3ch
```

<h3 style="color:green;">3. Nạp firmware tại gateway </h3>

_Backup firmware cũ_

```
mv FirmwareGateway FirmwareGateway_bkup
```

_Giải nén Firmware mới_

```
tar xvf <Firmware_Gateway>.tar.gz
```

_Xóa firmware backup_

```
rm -r FirmwareGateway_bkup
```

`<Firmware_Gateway>`: Tên file Firmware Gateway với đuôi .tar.gz
