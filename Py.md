
# 🎓 برنامه آموزشی جامع لینوکس و مدیریت سرور

این دوره‌ی ۱۲ هفته‌ای برای علاقه‌مندان به لینوکس طراحی شده تا از سطح مبتدی تا پیشرفته، مهارت‌های لازم برای مدیریت سیستم و سرور را بیاموزند.

---

## 📅 سطح مبتدی (هفته‌های 1 تا 4)

### 🧭 هفته ۱: مقدمات ترمینال
- آشنایی با ساختار دستورات لینوکس
- دستورات پایه:
```bash
  pwd, ls, cd, mkdir, touch, cp, mv, rm
```
مدیریت فایل‌ها:

```bash
cat, less, head, tail, nano
```
کمک‌گیری:

```bash
man, --help, apropos
```

👥 هفته ۲: کاربران و مجوزها

مدیریت کاربران:
```bash
sudo, su, useradd, usermod, passwd
```

مدیریت مجوزها:
```bash
chmod, chown, chgrp
```
سیستم فایل:
```bash
df, du, mount, umount
```

📝 هفته ۳: پردازش متن

فیلترها:
```bash
grep, awk, sed, cut, sort, uniq
```
ویرایشگرها:
```bash
vi/vim, emacs
```

📦 هفته ۴: مدیریت بسته‌ها

دبیان/اوبونتو:
```bash
apt update, apt install, apt remove
```
RHEL/CentOS:
```bash
yum install, dnf install
```


---

⚙️ سطح متوسط (هفته‌های 5 تا 8)

🔄 هفته ۵: مدیریت فرآیندها

مانیتورینگ:
```bash
ps, top, htop, glances
```
کنترل فرآیندها:
```bash
kill, killall, pkill, nice, renice
```

🌐 هفته ۶: شبکه مقدماتی

ابزارهای شبکه:
```bash
ifconfig/ip, netstat/ss, ping, traceroute
```
اتصالات:
```bash
ssh, scp, rsync
```

⚡ هفته ۷: اسکریپت‌نویسی مقدماتی

ساختار اسکریپت:
```bash
#!/bin/bash
```
متغیرها و ورودی:
```bash
read, $1, $@
```
شرط‌ها:
```bash
if-then-else, case
```

⏰ هفته ۸: زمان‌بندی وظایف

با کرون:
```bash
crontab -e
```
با at:
```bash
at, atq, atrm
```


---

🧠 سطح پیشرفته (هفته‌های 9 تا 12)

🌐 هفته ۹: شبکه پیشرفته

دیباگ شبکه:
```bash
tcpdump, wireshark, nmap
```
فایروال:
```bash
iptables, ufw, firewalld
```

📊 هفته ۱۰: لاگ‌ها و مانیتورینگ

سیستم‌های لاگ:
```bash
journalctl, /var/log
```
ابزارهای مانیتورینگ:
```bash
sar, vmstat, iostat
```

📦 هفته ۱۱: مجازی‌سازی و کانتینر

Docker مقدماتی:
```bash
docker run, docker ps, docker build
```
LXC/LXD:
```bash
lxc launch, lxc list
```

🔒 هفته ۱۲: امنیت پایه

اسکن امنیتی:
```bash
lynis, rkhunter
```
احراز هویت:
```bash
ssh-keygen, openssl
```


---

🛠 پروژه‌های عملی

1. ساخت اسکریپت پشتیبان‌گیری خودکار


2. راه‌اندازی سرور وب ساده با Nginx


3. مانیتورینگ سیستم با اسکریپت Bash


4. خودکارسازی با Ansible




---

📚 منابع تکمیلی

کتاب: The Linux Command Line - William Shotts

دوره آنلاین: Linux Foundation Certified System Administrator

مستندات رسمی: man pages و --help

تمرین آنلاین: OverTheWire: Bandit



---

📈 ارزیابی

آزمون‌های هفتگی: تمرین دستوری و سناریوهای واقعی

پروژه نهایی: راه‌اندازی کامل سرور با سرویس‌های کاربردی



---

🧩 نکات مهم

قبل از اجرای هر دستور با sudo، کاملاً مطمئن شوید

از man برای یادگیری عمیق‌تر استفاده کنید

ابتدا دستورات جدید را در محیط آزمایشی تست کنید

یادداشت‌برداری مداوم و مستندسازی مراحل یادگیری فراموش نشود

