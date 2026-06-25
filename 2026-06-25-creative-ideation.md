# تحديث 2026-06-25: مهارة Creative Ideation

## المصدر
[@NousResearch على X](https://x.com/NousResearch) — 3 منشورات قبل 11 ساعة.

---

## 🎨 مهارة creative-ideation الجديدة (اختيارية)

### الملخص
أعلنت Nous Research عن مهارة اختيارية جديدة لـ Hermes Agent باسم **creative-ideation**، وهي مكتبة من 22 منهجية إبداعية مستوحاة من فنانين ومفكرين.

### كيفية العمل
- تحلل المهارة prompt المستخدم وتستخرج 3 إشارات: المرحلة (Phase)، المجال (Domain)، ومستوى التحديد (Specificity)
- توجّه الطلب عبر واحد من 22 منهج إبداعي لإيجاد توازن مثالي بين الإبداع والتطبيق العملي
- المناهج تشمل: lateral provocations، pataphysics، وغيرها من المدارس الإبداعية

### حالات الاستخدام
- توليد الأفكار ("أعطني فكرة لمشروع")
- توسيع الأفكار ("أعطني اقتراحات مشابهة")
- الاختيار بين الخيارات ("ساعدني في الاختيار")
- فك العوائق الإبداعية ("أنا عالق")
- التخريب الإبداعي ("اجعله أغرب")

### التثبيت
```bash
hermes skills config  # تفعيل المهارات الاختيارية
```

أو التثبيت المباشر:
```bash
hermes skills install "https://raw.githubusercontent.com/NousResearch/hermes-agent/main/optional-skills/creative/creative-ideation/SKILL.md"
```

### الرابط
[SKILL.md على GitHub](https://github.com/NousResearch/hermes-agent/blob/main/optional-skills/creative/creative-ideation/SKILL.md)

---

## 🔧 الإجراءات المتخذة على التثبيت المحلي

- ✅ تم محاولة تثبيت المهارة عبر `hermes skills install`
- 📌 هذا تحديث "مهارة اختيارية" وليس تحديثاً لنواة Hermes — لا حاجة لتحديث التثبيت الأساسي
- ℹ️ الإصدار الحالي: Hermes Agent v0.17.0 (2026.6.19)
