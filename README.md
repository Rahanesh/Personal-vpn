# Https://t.me/Rahanesh
راه اندازی سرور فیلترشکن شخصی

لینک ویدیو آموزشی:  https://t.me/rahanesh/372 

ساخت یک سرور با سیستم عامل: Centos 7 x86 (or) Centos 7 x64

لاگین کردن به سرور با نرم افزار putty و اجرای دستور زیر:

cd /tmp/ && yum install git -y && git clone https://github.com/Rahanesh/Personal-vpn.git && cd Personal-vpn/ && sed -i -e 's/\r$//' centos7.sh && chmod 755 centos7.sh && ./centos7.sh 

دستورات زیر برای اضافه کردن کاربر به سرور:

useradd [username] - 
passwd [username]

گرفته شده از الف مدیا
رسانه آموزشی رهانش 
