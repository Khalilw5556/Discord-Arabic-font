# 🖋️ Discord Arabic Font for Linux

هذا المشروع يوفر ملف CSS بسيط لتغيير الخطوط الافتراضية إلى خط **Noto Sans Arabic/Noto Sans Arabic UI** الجميل والواضح. تم تصميمه خصيصاً لمستخدمي Linux و Discord عبر (Vencord/BetterDiscord).

## 🚀 المميزات
- **خط Noto Sans Arabic UI:** محسّن لواجهات المستخدم.
- **تنسيق موحد:** يتم تطبيق الخط على جميع العناصر (`*`) لضمان التناسق.
- **وضوح عالي:** تم ضبط وزن الخط (Font Weight) على 500 لإعطاء مظهر احترافي وسهل القراءة.
- **خفيف وسريع:** يعتمد على Google Fonts مباشرة.

## 🛠️ كيفية الاستخدام

### 1. في تطبيقات Discord (Vencord / BetterDiscord)
قم بنسخ الكود الموجود في ملف `arabic-font.css` ولصقه في قسم **Quick CSS/Custom CSS** في إعدادات التطبيق, 
او قم بتحميل ملف `arabic-font.css` وضعه في ملف Themes.

### 2. في متصفحات الويب (عبر إضافة Stylus)
1. قم بتثبيت إضافة **Stylus**.
2. أنشئ ستايل جديد.
3. الصق الكود وقم بتطبيقه على المواقع التي ترغب بها.

## 📄 محتوى الكود (CSS)
```css
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+Arabic:wght@500&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+Arabic+UI:wght@500&display=swap');

* {
    font-family: "Noto Sans Arabic UI", "Noto Sans Arabic", sans-serif !important;
    font-weight: 500 !important;
}
