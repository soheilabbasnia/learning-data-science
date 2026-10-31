<div dir="rtl">

# مخزن جامع یادگیری علم داده (Learning Data Science)

[![License: MIT](https://img.shields.io/badge/لایسنس-MIT-blue.svg)](LICENSE)
[![Python: 3.10+](https://img.shields.io/badge/پایتون-3.10%2B-3776AB.svg?logo=python&logoColor=white)](https://python.org)
[![Jupyter](https://img.shields.io/badge/نوت‌بوک-Jupyter-F37626.svg?logo=jupyter&logoColor=white)](https://jupyter.org)
[![Frameworks](https://img.shields.io/badge/تکنولوژی‌ها-Pandas%20%7C%20Scikit--Learn%20%7C%20PyTorch-orange.svg)](#)

[English](README.md) | فارسی

یک مسیر آموزشی و مرجع عملی و کاربردی شامل کدهای پروژه‌محور، الگوریتم‌های یادگیری ماشین، یادگیری عمیق، مبانی آمار و مصورسازی داده‌ها همراه با دیتاست‌های واقعی در قالب ژوپیتر نوت‌بوک‌های تعاملی.

---

## 🌟 نمای کلی پروژه

این مخزن به عنوان یک مرجع گام‌به‌گام و استاندارد برای علاقه‌مندان و متخصصان علم داده طراحی شده است و چرخه کامل تحلیل داده‌ها و مدلسازی پیش‌بینانه را پوشش می‌دهد؛ از درک اولیه داده‌ها و مصورسازی آماری تا پاکسازی پیشرفته داده‌ها، الگوریتم‌های یادگیری ماشین کلاسیک و شبکه‌های عصبی عمیق.

نکات برجسته:
- **پوشش چرخه کامل علم داده:** سازمان‌دهی سرفصل‌ها بر مبنای فرآیند استاندارد صنعتی (شناخت داده، پیش‌پردازش، مدل‌سازی ماشین لرنینگ و دیپ لرنینگ).
- **ژوپیتر نوت‌بوک‌های تعاملی و خودکفا:** شامل توضیحات مفهومی، نمودارهای تجسمی، بلوک‌های اجرایی کد و تحلیل خروجی‌ها.
- **مجموعه داده‌های واقعی:** همراه داشتن دیتاست‌های کاربردی (دیابت، تسهیلات بانکی، دسته‌بندی مشتریان) جهت تست و تمرین فوری.
- **یادگیری عمیق چند فریم‌ورکی:** ساخت شبکه‌های عصبی از صفر با کتابخانه ریاضی NumPy و پیاده‌سازی مدل‌ها در PyTorch و TensorFlow.

---

## 🧩 سرفصل‌ها و ماژول‌های آموزشی

| سرفصل | مفاهیم و مباحث کلیدی | ابزارها و نوت‌بوک‌ها |
| :--- | :--- | :--- |
| [`data-understanding`](data-understanding/) | تحلیل اکتشافی داده‌ها (EDA)، آمار توصیفی، آمار استنباطی، مصورسازی دوبعدی و چندمتغیره | Matplotlib, Seaborn, Pandas, SciPy |
| [`data-preparation`](data-preparation/) | مدیریت مقادیر گمشده (Missing Values)، شناسایی داده‌های پرت (Outliers)، تبدیل متغیرهای کیفی (Dummies)، نرمال‌سازی و پیش‌پردازش | Pandas, Scikit-Learn Preprocessing |
| [`machine-learning`](machine-learning/) | یادگیری نظارت‌شده (رگرسیون و طبقه‌بندی)، یادگیری نظارت‌نشده (خوشه‌بندی و کاهش ابعاد) | Scikit-Learn, XGBoost |
| [`deep-learning`](deep-learning/) | پیاده‌سازی شبکه عصبی از پایه با پایتون و نام‌پای، انتشار رو به جلو/عقب، فریم‌ورک‌های PyTorch و TensorFlow | NumPy, PyTorch, TensorFlow |

---

## 🚀 نحوه نصب و شروع به کار

### پیش‌نیازها

- پایتون نسخه ۳.۹ یا بالاتر
- ابزارهای `pip` و `venv`

### مراحل راه‌اندازی

۱. **کلون کردن مخزن:**
   ```bash
   git clone https://github.com/soheilabbasnia/learning-data-science.git
   cd learning-data-science
   ```

۲. **ساخت و فعال‌سازی محیط مجازی پایتون:**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

۳. **نصب کتابخانه‌ها و پیش‌نیازها:**
   ```bash
   pip install -r requirements.txt
   ```

۴. **اجرای ژوپیتر لب یا ژوپیتر نوت‌بوک:**
   ```bash
   jupyter lab
   ```

---

## 📁 ساختار پوشه‌های پروژه

```text
learning-data-science/
├── data-understanding/          # درک داده‌ها، آمار توصیفی و مصورسازی نمودارها
│   ├── data-visualization/
│   ├── descriptive-statistics/
│   └── inferential-statistics/
├── data-preparation/            # پیش‌پردازش، تمیزکاری داده‌ها و مهندسی ویژگی‌ها
│   ├── datasets/
│   ├── preprocessing/
│   └── *.ipynb                  # نوت‌بوک‌های مقادیر گمشده، پرت، انکودینگ و نرمال‌سازی
├── machine-learning/            # الگوریتم‌های سنتی یادگیری ماشین
│   ├── datasets/
│   ├── supervised-learning/
│   └── unsupervised-learning/
├── deep-learning/               # معماری‌های یادگیری عمیق
│   ├── datasets/
│   ├── tensorflow/
│   ├── torch/
│   └── nn-np.ipynb              # پیاده‌سازی شبکه عصبی از پایه با NumPy
├── requirements.txt             # لیست پکیج‌های پایتون
└── LICENSE                      # مجوز پروژه
```

---

## 🤝 مشارکت

از هرگونه مشارکت، اصلاح نوت‌بوک‌ها و اضافه کردن نمونه‌های جدید با کمال میل استقبال می‌شود!
۱. مخزن را فورک کنید.
۲. یک برنچ جدید برای قابلیت خود ایجاد کنید (`git checkout -b feature/new-ml-notebook`).
۳. تغییرات خود را کامیت کنید (`git commit -m 'Add notebook for Gradient Boosting'`).
۴. تغییرات را به برنچ خود پوش نمایید (`git push origin feature/new-ml-notebook`).
۵. یک پول ریکوئست (Pull Request) ارسال کنید.

---

## 📜 مجوز (License)

این پروژه تحت مجوز [MIT License](LICENSE) منتشر شده است. استفاده از کدها و نوت‌بوک‌ها برای اهداف آموزشی و پژوهشی کاملاً آزاد است.

</div>
