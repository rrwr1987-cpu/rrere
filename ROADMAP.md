# ROADMAP — مصاريفي

آخر تحديث: 2026-09-13
الحالة العامة: IN PROGRESS
المرجع: هذه الوثيقة هي مصدر الحقيقة لحالة المشروع.

## قواعد الحالة

- TODO: لم تبدأ المهمة.
- IN PROGRESS: قيد التنفيذ.
- BLOCKED: متوقفة بسبب عائق موثق.
- DONE: نُفذت واختُبرت ووُثقت حسب Definition of Done.
- لا تُستخدم DONE لمهمة لم يتم التحقق منها فعليًا.

## ملخص الحالة

| المرحلة | الاسم | الحالة | المخرج الرئيسي |
|---|---|---|---|
| 0 | Project Initialization | IN PROGRESS | مستودع ووثائق Bootstrap |
| 1 | Requirements & Product Definition | TODO | نطاق MVP وقصص الاستخدام |
| 2 | Architecture & Technical Design | TODO | تصميم تقني قابل للتنفيذ |
| 3 | Design System & UI/UX | TODO | نظام تصميم وشاشات أساسية |
| 4 | Database & Domain Model | TODO | نموذج بيانات وRoom |
| 5 | Core Transaction Engine | TODO | محرك حسابات موثوق |
| 6 | Income & Expense | TODO | تسجيل الدخل والمصروف |
| 7 | Debt Management | TODO | الديون والسداد |
| 8 | Dashboard | TODO | ملخص مالي سريع |
| 9 | Transaction History | TODO | بحث وفلترة وتعديل وحذف |
| 10 | Reports & Analytics | TODO | تقارير قابلة لاتخاذ القرار |
| 11 | Settings & Data Management | TODO | إعدادات وبيانات المستخدم |
| 12 | Security & Privacy | TODO | حماية وخصوصية |
| 13 | Testing & Quality Assurance | TODO | تغطية واختبارات موثقة |
| 14 | Performance & Stability | TODO | أداء واستقرار |
| 15 | Release Preparation | TODO | Release APK/AAB ومتطلبات المتجر |
| 16 | Final Regression | TODO | اختبار المستخدم الجديد من البداية للنهاية |
| 17 | Production Release | TODO | إصدار موثق وقابل للنشر |
| 18 | Post-Release Monitoring | TODO | مراقبة ما بعد الإطلاق |

## PHASE 0 — Project Initialization

الحالة: IN PROGRESS

### الهدف
تهيئة مستودع منظم وقابل للتطوير قبل كتابة ميزات التطبيق.

### المهام

- [x] فحص المستودع الحالي.
- [x] التأكد من الفرع الرئيسي والـ commit الابتدائي.
- [x] إنشاء الوثائق الأساسية.
- [x] إنشاء خارطة الطريق.
- [x] إنشاء سجل القرارات والاختبارات والمشاكل.
- [x] إنشاء Backlog وسجل المشروع.
- [ ] اختيار وإنشاء Android project structure.
- [ ] تنفيذ أول اختبار بيئي فعلي.
- [ ] إنشاء Commit موثق لهذا الـ Bootstrap.
- [ ] توثيق Push بعد نجاحه.

### Definition of Done

- توجد كل وثائق Bootstrap المطلوبة.
- تم توثيق حالة المستودع قبل التغيير.
- تم تحديد الـ Stack والحدود المعمارية مبدئيًا.
- تم تشغيل اختبار بيئي فعلي بعد إضافة المشروع.
- تم تسجيل commit hash والنتائج في هذه الوثيقة.

### سجل التنفيذ

- الحالة قبل التغيير: README.md فقط.
- الفرع: main.
- آخر commit قبل Bootstrap: 2b9c5be38d29a41e2e9afe588c4ebe3639100771 — Initial commit.
- Push قبل Bootstrap: غير معروف من واجهة المحادثة.
- Build قبل Bootstrap: لم يُنفذ.
- Tests قبل Bootstrap: لم تُنفذ.
- Commit Bootstrap: يُملأ بعد تنفيذ commit.
- Push Bootstrap: يُملأ بعد التحقق من push.

## PHASE 1 — Requirements & Product Definition

الحالة: TODO

### الهدف
تحويل الفكرة إلى MVP واضح للمستخدم العربي دون توسيع غير منضبط.

### المهام

- [ ] تعريف Personas وسيناريوهات الاستخدام الأساسية.
- [ ] تحديد الحقول المطلوبة لكل نوع عملية.
- [ ] تحديد معنى الرصيد والدخل والمصروف والديون.
- [ ] تحديد MVP وما يدخل في Backlog.
- [ ] تعريف معايير قبول كل ميزة.
- [ ] توثيق متطلبات RTL واللغة العربية والعملة الافتراضية.

### Definition of Done

- كل ميزة MVP لها هدف، مدخلات، مخرجات، وحالات خطأ.
- لا توجد قاعدة مالية غير موثقة.
- تمت مراجعة النطاق ومنع Feature Creep.

## PHASE 2 — Architecture & Technical Design

الحالة: TODO

### المهام

- [ ] تثبيت بنية المشروع والـ modules عند الحاجة.
- [ ] تثبيت الحدود بين UI وDomain وData.
- [ ] تحديد Navigation وState management.
- [ ] تحديد سياسة dependencies وإصداراتها بعد التحقق.
- [ ] توثيق قرارات تغير التصميم.
- [ ] تحديد استراتيجية migrations والنسخ الاحتياطي.

### Definition of Done

- يمكن تنفيذ كل ميزة MVP دون قرار معماري مجهول.
- كل dependency لها سبب موثق.
- توجد خطة لتطور schema دون فقد البيانات.

## PHASE 3 — Design System & UI/UX

الحالة: TODO

### المهام

- [ ] إنشاء Design System موحد.
- [ ] تصميم RTL والألوان والخطوط والمسافات.
- [ ] تصميم Dashboard وAdd Transaction وDebts وHistory وReports.
- [ ] تصميم حالات Empty وLoading وError وValidation.
- [ ] مراجعة قابلية الاستخدام على شاشة صغيرة.

### Definition of Done

- كل شاشة أساسية لها حالات النجاح والفشل والفراغ.
- المكونات متسقة وقابلة لإعادة الاستخدام.
- التنقل واضح للمستخدم غير المتخصص.

## PHASE 4 — Database & Domain Model

الحالة: TODO

### المهام

- [ ] تصميم Transaction وDebt وDebtPayment وCategory.
- [ ] تحديد أنواع البيانات الدقيقة للمبالغ والتواريخ.
- [ ] إنشاء Room entities وDAO وrepositories.
- [ ] كتابة migrations واختبارات persistence.
- [ ] منع الحذف أو التعديل الذي يسبب فسادًا ماليًا.

### Definition of Done

- النموذج يغطي MVP دون خلط الرصيد بالديون.
- اختبارات الإدخال والتعديل والحذف والاسترجاع ناجحة.
- migration strategy موثقة.

## PHASE 5 — Core Transaction Engine

الحالة: TODO

### المهام

- [ ] تنفيذ قواعد حساب الرصيد.
- [ ] تنفيذ قواعد صافي التدفق.
- [ ] تنفيذ validation للمبالغ والتواريخ.
- [ ] تنفيذ عمليات حساب الديون والمتبقي.
- [ ] كتابة unit tests للحالات العادية والحدية.

### Definition of Done

- الحسابات deterministic ودقيقة.
- لا تُستخدم Floating Point للمبالغ.
- كل قاعدة في FINANCIAL_RULES.md لها اختبار.

## PHASE 6 — Income & Expense

الحالة: TODO

### المهام

- [ ] إضافة الدخل.
- [ ] إضافة المصروف.
- [ ] التصنيفات والملاحظات والتاريخ.
- [ ] تعديل وحذف آمنان.
- [ ] رسائل validation مفهومة بالعربية.

### Definition of Done

- يستطيع المستخدم إضافة دخل ومصروف محليًا دون إنترنت.
- البيانات تبقى بعد إعادة تشغيل التطبيق.
- الاختبارات والـ UI flow موثقة.

## PHASE 7 — Debt Management

الحالة: TODO

### المهام

- [ ] إنشاء دين لي.
- [ ] إنشاء دين علي.
- [ ] عرض المتبقي والحالة.
- [ ] السداد الجزئي والكامل.
- [ ] منع السداد الأكبر من المتبقي.
- [ ] سجل السداد وتاريخ الاستحقاق.

### Definition of Done

- الدين لا يُغلق عند السداد الجزئي.
- الرصيد والديون منفصلة حسابيًا.
- كل تعديل بعد وجود دفعات له سلوك موثق ومختبر.

## PHASE 8 — Dashboard

الحالة: TODO

### المهام

- [ ] عرض الرصيد الحالي.
- [ ] دخل اليوم ومصروف اليوم وصافي اليوم.
- [ ] لي عند الناس وعليّ للناس.
- [ ] أزرار الإضافة السريعة.
- [ ] Empty state أول استخدام.

### Definition of Done

- يفهم المستخدم وضعه المالي خلال ثوانٍ.
- الأرقام تعكس محرك الحسابات دون منطق مكرر في الواجهة.

## PHASE 9 — Transaction History

الحالة: TODO

### المهام

- [ ] قائمة كل العمليات.
- [ ] البحث والفلترة حسب النوع والتاريخ والتصنيف والشخص.
- [ ] تعديل العملية.
- [ ] حذف مع حماية من الحذف العرضي.
- [ ] pagination أو lazy loading عند الحاجة.

### Definition of Done

- النتائج صحيحة بعد كل تعديل وحذف.
- لا تضيع البيانات عند تغيير الفلاتر أو إعادة فتح التطبيق.

## PHASE 10 — Reports & Analytics

الحالة: TODO

### المهام

- [ ] تقارير اليوم والأسبوع والشهر والفترة المخصصة.
- [ ] إجمالي الدخل والمصروف وصافي التدفق.
- [ ] التصنيفات الأعلى صرفًا.
- [ ] اتجاهات مالية مفهومة.
- [ ] حالات عدم وجود بيانات.

### Definition of Done

- التقارير تساعد على قرار واضح ولا تكرر أرقامًا بلا معنى.
- كل تجميع مرتبط بقاعدة مالية واختبار.

## PHASE 11 — Settings & Data Management

الحالة: TODO

### المهام

- [ ] العملة والإعدادات المحلية.
- [ ] إدارة التصنيفات.
- [ ] تصدير واستيراد عند اعتمادهما.
- [ ] حذف كل البيانات مع تحذير واضح.
- [ ] معلومات الإصدار.

### Definition of Done

- العمليات الخطرة لها تحذير وتوثيق.
- لا يحدث فقد بيانات صامت.

## PHASE 12 — Security & Privacy

الحالة: TODO

### المهام

- [ ] فحص الأسرار والـ credentials.
- [ ] تقليل logs الحساسة.
- [ ] مراجعة الصلاحيات.
- [ ] حماية التخزين المحلي حسب الحاجة.
- [ ] تقييم App Lock كميزة مستقلة.
- [ ] إعداد متطلبات Privacy Policy وData Safety.

### Definition of Done

- لا توجد أسرار في repository.
- تم توثيق البيانات المحلية وأي نقل خارجي.
- نتائج الفحص الأمني مسجلة.

## PHASE 13 — Testing & Quality Assurance

الحالة: TODO

### المهام

- [ ] Unit tests لمحرك الحسابات والديون والفلاتر.
- [ ] Database tests للـ DAO والمigrations.
- [ ] UI tests للتدفقات الأساسية.
- [ ] Integration tests عند الحاجة.
- [ ] Regression checklist.
- [ ] تشغيل lint وstatic analysis.

### Definition of Done

- كل اختبار مسجل في TESTING.md.
- لا توجد نتيجة PASS بلا أمر ونتيجة فعلية.
- المشاكل المفتوحة مسجلة في BUGS.md.

## PHASE 14 — Performance & Stability

الحالة: TODO

### المهام

- [ ] قياس زمن فتح الشاشة الرئيسية.
- [ ] مراجعة إعادة التركيب والذاكرة.
- [ ] اختبار قاعدة بيانات أكبر.
- [ ] اختبار إغلاق التطبيق أثناء الحفظ.
- [ ] معالجة crash وANR المعروفة.

### Definition of Done

- لا توجد مشكلة حرجة معروفة غير موثقة.
- القياسات والحدود المسجلة قابلة للتكرار.

## PHASE 15 — Release Preparation

الحالة: TODO

### المهام

- [ ] Release build.
- [ ] Android App Bundle.
- [ ] icon وsplash وversioning.
- [ ] وصف المتجر وscreenshots.
- [ ] Privacy Policy وData Safety.
- [ ] signing strategy.

### Definition of Done

- تم بناء artifact فعليًا والتحقق منه.
- متطلبات Google Play الحالية تمت مراجعتها.
- CHANGELOG وrelease notes محدثان.

## PHASE 16 — Final Regression

الحالة: TODO

### السيناريو الإلزامي

1. تثبيت التطبيق.
2. فتحه كمستخدم جديد.
3. إنشاء دخل.
4. إنشاء مصروف.
5. إنشاء دين لي.
6. إنشاء دين علي.
7. تسجيل سداد.
8. تعديل عملية.
9. حذف عملية.
10. البحث والفلترة.
11. فتح التقارير.
12. إغلاق التطبيق وإعادة فتحه.
13. اختبار الحالات الخاصة.
14. اختبار Release build.

### Definition of Done

- كل خطوة لها نتيجة مسجلة في TESTING.md.
- أي فشل ينتقل إلى BUGS.md ولا يُخفى.

## PHASE 17 — Production Release

الحالة: TODO

### المهام

- [ ] اعتماد الإصدار النهائي.
- [ ] إنشاء release tag.
- [ ] نشر الإصدار وفق صلاحيات المستودع والمتجر.
- [ ] توثيق commit وartifact وrelease notes.

### Definition of Done

- الإصدار منشور أو سبب عدم النشر موثق بوضوح.
- لا يُستخدم PROJECT COMPLETE قبل تحقق كل شروط الإصدار.

## PHASE 18 — Post-Release Monitoring

الحالة: TODO

### المهام

- [ ] متابعة crashes وANR.
- [ ] جمع feedback دون جمع بيانات مالية غير لازمة.
- [ ] تسجيل bugs والإصدارات التصحيحية.
- [ ] مراجعة backlog بناءً على الاستخدام الفعلي.

### Definition of Done

- توجد آلية متابعة وقرار واضح لكل مشكلة ما بعد الإطلاق.

## بوابة الانتقال بين المراحل

لا تنتقل المرحلة التالية إلا بعد:

1. تنفيذ المهام.
2. تشغيل الاختبارات المناسبة.
3. إصلاح الفشل.
4. إعادة الاختبار.
5. تحديث الوثائق.
6. تحديث ROADMAP وPROJECT_LOG.
7. مراجعة diff.
8. إنشاء commit.
9. التحقق من commit.
10. توثيق push إن حدث.

## سجل التغييرات على الخارطة

- 2026-09-13: إنشاء خارطة أولية بعد فحص مستودع شبه فارغ.
