# الحاسبة الشمسية الاحترافية

هذا المشروع هو واجهة إلكترونية لحاسبة شمسية (واجهة HTML/JS) — تم تجهيزها لتُرفع إلى GitHub بسهولة.

**الملفات**
- `index.html` — الصفحة الرئيسية (تمت إعادة تسمية الملف الأصلي ليعمل مباشرة على GitHub Pages).

**نشر سريع على GitHub (خياران)**

1) **عن طريق واجهة الويب (سهل للملفات القليلة):**
   - سجّل دخولك في GitHub
   - افتح: https://github.com/new لإنشاء مستودع جديد (اختر اسمًا مثل `solar-calculator`)
   - بعد الإنشاء: اضغط "Add file" → "Upload files" ثم اسحب `index.html` (وأي ملفات أخرى)
   - Commit changes
   - لتمكين GitHub Pages: اذهب إلى Settings → Pages → Source → اختر `main` branch و `/ (root)` ثم Save
   - بعد دقيقة أو دقيقتين ستكون الصفحة متاحة على: `https://<your-username>.github.io/<repo-name>/`

2) **عن طريق Git (مستحسن للمشاريع المتكررة التحديث):**
   - افتح Terminal / PowerShell
   - نفّذ:
     ```bash
     mkdir solar-calculator
     cd solar-calculator
     # انسخ أو ضع index.html هنا
     git init
     git add .
     git commit -m "Initial commit: solar calculator"
     git branch -M main
     git remote add origin https://github.com/<your-username>/<repo-name>.git
     git push -u origin main
     ```
   - ثم فعّل GitHub Pages من إعدادات المستودع كما في الخيار أعلاه.

**ملاحظات**
- إذا أنشأت المستودع على GitHub مع README مُهيأ، استعمل `git clone` أولاً ثم انسخ الملفات داخل المجلد ثم `git add`/`commit`/`push`.
- عدّل `index.html` أو أضف مجلد `assets/` للصور و `css/` إذا أردت تنظيم المشروع لاحقًا.

