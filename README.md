# -
المنتج هو تطبيق للهواتف المحمولة يجمع بين أقوال الإمام علي وأقوال المستخدمين الشخصية. يتيح التطبيق للمستخدمين استعراض وحفظ ومشاركة مئات الأقوال الملهمة على منصات التواصل الاجتماعي، مع إمكانية إضافة أقوالهم الخاصة والحصول على إشعارات يومية للحكمة والإلهام.

## لعبة تضمين جاهزة
تمت إضافة لعبة HTML كاملة باسم `game-embed.html` تعمل مباشرة دون أي مكتبات خارجية.

### طريقة التشغيل المحلية
```bash
python3 -m http.server 8000
```
ثم افتح:
- `http://localhost:8000/game-embed.html`

### كود التضمين (Embed)
استخدم هذا الكود داخل أي صفحة:

```html
<iframe
  src="https://your-domain.com/game-embed.html"
  width="860"
  height="560"
  style="border:0;border-radius:16px;overflow:hidden;max-width:100%;"
  loading="lazy"
  allow="fullscreen"
  title="لعبة حارس النجوم"
></iframe>
```
