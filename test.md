# 🎓 سیستم ثبت‌نام دوره‌های آموزشی به همراه گزارش‌گیری (Python + Tkinter + SQLite)

این پروژه یک سیستم ثبت‌نام و مدیریت دوره‌های آموزشی است که با استفاده از **Python**، رابط کاربری **Tkinter** و پایگاه داده **SQLite** پیاده‌سازی شده است.  
قابلیت‌های اصلی شامل مدیریت کاربران، دانشجویان و دوره‌ها، جستجو و فیلتر، صفحه‌بندی، و گزارش‌گیری (HTML و PDF با پشتیبانی کامل از زبان فارسی) می‌باشد.

---

## 👨‍💻 Created by
**Erfan Namaki**

---

## ✨ قابلیت‌ها
- مدیریت کاربران (افزودن، ویرایش، حذف، کاربر پیش‌فرض admin/admin)
- مدیریت دانشجویان (ثبت‌نام، ویرایش، حذف، انتخاب یا تغییر دوره)
- مدیریت دوره‌ها (ایجاد، ویرایش، حذف، جستجو و فیلتر)
- جستجو و مرتب‌سازی پیشرفته
- صفحه‌بندی (Pagination) با کنترل قبلی/بعدی
- گزارش‌گیری:
  - چاپ HTML راست‌چین با فونت فارسی
  - خروجی PDF با فونت Vazirmatn و پشتیبانی کامل از زبان فارسی
- رابط کاربری گرافیکی مدرن با Tkinter و استایل‌های سفارشی
- ذخیره‌سازی اطلاعات در SQLite (ایجاد خودکار جداول در اولین اجرا)

---

## ⚙️ نصب و راه‌اندازی
دانلود اخرین نسخه از [این لینک](https://github.com/ErfanNamaki/CourseRegistrationSystem/releases/latest/download/CourseRegistrationSystem.zip) 
1. نصب فونت فارسی:
   - فایل `Vazirmatn-Regular.ttf` را در پوشه‌ی نرم‌افزار قرار دهید.

2. اجرای برنامه:
   course-registration-system.exe

3. ورود به سیستم:
   - **Username:** `admin`  
   - **Password:** `admin`

---

## 🛠 وابستگی‌ها
در صورت دریافت خطای زیر:
ModuleNotFoundError: No module named '*******'

کتابخانه‌های مورد نیاز را نصب کنید:
pip install reportlab arabic-reshaper python-bidi
or
pip install -r requirements.txt


---

<div dir="lrt">
## 📂 ساختار پروژه <br/><br/>
course-registration-system_v2.1/<br/>
│<br/>
├── data/                                  # پوشه دیتابیس SQLite (registration.db اینجا ساخته می‌شود)<br/>
├── Vazirmatn-Regular.ttf                  # فونت فارسی برای گزارش PDF<br/>
├── How this program works.pptx            # فایل ارائه توضیح عملکرد برنامه<br/>
├── course-registration-system_v2.1.exe    # نسخه اجرایی آماده (Windows)<br/>
├── requirements.txt                       # لیست کتابخانه‌های مورد نیاز<br/>
└── README.md                              # توضیحات پروژه<br/>
</div>


