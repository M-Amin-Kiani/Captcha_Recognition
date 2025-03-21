
# 🔐 Captcha Recognition with MLP

## 📌 درباره‌ی پروژه

پروژه‌ی **Captcha Recognition with MLP** به پیاده‌سازی سیستمی برای شناسایی و تشخیص CAPTCHA با استفاده از **شبکه‌های عصبی چندلایه (MLP)** می‌پردازد. هدف این پروژه، بهبود عملکرد سیستم‌های تشخیص CAPTCHA در مواجهه با تصاویر پیچیده‌تر و چالش‌برانگیز است.

---

## 🛠️ پیش‌نیازها

- زبان برنامه‌نویسی: Python
- کتابخانه‌های موردنیاز:
  - numpy
  - pandas
  - scikit-learn
  - tensorflow یا keras
  - matplotlib

برای نصب کتابخانه‌های موردنیاز:

```bash
pip install numpy pandas scikit-learn tensorflow matplotlib
```

---

## 📂 ساختار پوشه‌ها

```
Captcha_Recognition/
├── captcha_images2/
├── extracted_letter_images/
├── Captcha_Recognition_Project_Final.ipynb
├── Process.ipynb
├── Test & Train.ipynb
├── README.md
├── داک گزارش تمرین_ محمد امین کیانی 4003613052.pdf
└── داک گزارش پروژه_ محمد امین کیانی 4003613052.pdf
```

---

## 🚀 نحوه‌ی اجرا

1. کلون کردن ریپازیتوری:

```bash
git clone https://github.com/M-Amin-Kiani/Captcha_Recognition.git
cd Captcha_Recognition
```

2. نصب پیش‌نیازها:

```bash
pip install numpy pandas scikit-learn tensorflow matplotlib
```

3. اجرای نوت‌بوک‌ها:

- فایل‌های `Process.ipynb`, `Test & Train.ipynb` و `Captcha_Recognition_Project_Final.ipynb` را با Jupyter Notebook باز و اجرا کنید.

---

## ✍️ نویسنده

- GitHub: [M-Amin-Kiani](https://github.com/M-Amin-Kiani)

---

## 📄 مجوز

این پروژه تحت مجوز MIT منتشر شده است.

---

## 📬 پشتیبانی

در صورت وجود مشکل، لطفاً issue جدیدی در ریپازیتوری باز کنید یا با نویسنده تماس بگیرید.

![image](https://github.com/M-Amin-Kiani/Captcha_Recognition/assets/100538655/3c776a18-0384-4dec-8251-f7083d5fd56f)

progress the CAPTCHA Breaker of src cookbook with MLP: Machine-Learning-for-Cybersecurity-Cookbook//Chapter05/CAPTCHA Breaker


به طور خلاصه : 
داخل این پروژه عملکرد کپچای داخل کتاب منبع که فقط ریلی سیمپل بود و توی تمرین به این نتیجه رسیدیم که اگر یک کپچای سخت تر بگذاریم، آن کد دیگر بدرد نمیخورد را با یک شبکه عصبی قوی تر دارای اپتیمایزر و ایپوک بیشتر جایگزین و باعث شد یک دیتاست کپچاهای مثالا خط خطی شده( که اغلب سامانه ها به این صورت اند )  را مدلسازی و اموزش دهیم.
