<div dir="rtl" lang="fa">

# پروژه آمار — مسیر ج (NACC: UDS + MRI)

## اطلاعات دانشجو

- نام: ابوالفضل حاتمی
- شماره دانشجویی: 400106321
- مسیر پروژه: ج

## راهنمای مصحح

تحویل اصلی این مخزن GitHub است.

برای فاز اول، همه توضیحات، تحلیل‌ها، جدول‌ها و نمودارها داخل نوت‌بوک Jupyter نوشته شده‌اند و به‌صورت Markdown در همان فایل آمده‌اند. فایل PDF جداگانه برای فاز اول ساخته نشده است.

مسیر نوت‌بوک فاز اول:

<pre dir="ltr">
reports/phase_1/phase1.ipynb
</pre>

کارت ثبت موضوع:

<pre dir="ltr">
PROJECT_CARD.md
</pre>

## ساختار پروژه

<pre dir="ltr">
statistics/
├── PROJECT_CARD.md
├── README.md
├── requirements.txt
├── data/
│   ├── raw/
│   │   ├── udslong_imputed.csv
│   │   ├── mriscanclean.csv
│   │   └── combined_adjacency_matrix.csv
│   └── processed/
└── reports/
    └── phase_1/
        ├── phase1.ipynb
        └── figures/
</pre>

توضیح پوشه‌ها:

- `data/raw`: فایل‌های خام تحویلی تیم دستیاری
- `data/processed`: محل فایل‌های پردازش‌شده در صورت نیاز
- `reports/phase_1`: نوت‌بوک فاز اول و شکل‌های ذخیره‌شده
- `PROJECT_CARD.md`: کارت پروژه و چارچوب سؤال آماری

## اجرای فاز اول

<pre dir="ltr">
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
</pre>

سپس نوت‌بوک زیر را باز کنید و سلول‌ها را از بالا به پایین اجرا کنید:

<pre dir="ltr">
reports/phase_1/phase1.ipynb
</pre>

## برچسب تحویل فاز اول

پس از تکمیل فاز اول، برچسب Git مورد انتظار:

<pre dir="ltr">
phase-1
</pre>

</div>
