# مشروع AWS للملاحظات الذكية

هذا المشروع مبني باستخدام خدمات AWS بدون خوادم (Serverless)، ويهدف إلى:
- رفع ملفات أو ملاحظات إلى خدمة S3
- استقبال إشعارات بريد إلكتروني من خلال خدمة SNS
- تسجيل البيانات باستخدام Lambda و DynamoDB

## الخدمات المستخدمة

- Lambda
- S3
- SNS
- IAM
- DynamoDB

## خطوات تنفيذ المشروع (مع الصور)

| الخطوة | الوصف | الصورة |
|--------|--------|---------|
| 1 | ربط Lambda مع S3 | ![connect s3](./connect%20s3%20with%20lambada.png) |
| 2 | إنشاء SNS من نوع Standard | ![sns](./creat%20amazon%20sns%20standard.png) |
| 3 | إنشاء Bucket في S3 | ![s3](./creat%20bucket%20s3.png) |
| 4 | تفعيل الاشتراك عبر البريد الإلكتروني | ![email](./creat%20email%20suscription%20.png) |
| 5 | إنشاء IAM Policy خاصة بـ Lambda | ![iam](./creat%20IAM%20policy%20ai%20not.png) |
| 6 | كود Lambda الخاص بالملاحظات | ![lambda code](./creat%20lambda%20dynmo%20code,%20ainote.png) |
| 7 | ربط SNS مع تطبيق Ainote | ![sns ai](./creat%20sns%20,%20ai%20note.png) |
| 8 | إنشاء جدول DynamoDB | ![ddb](./creating%20dynamoDB,%20dynamo.png) |
| 9 | نشر كود Lambda | ![lambda deploy](./lambda%20code%20ainote,%20deploying.png) |
| 10 | إكمال إنشاء دالة Lambda | ![lambda created](./lambda%20creation,%20anote.png) |
| 11 | رفع مجلد إلى S3 | ![folder](./upload%20folder%20to%20s3.png) |
| 12 | رفع ملف إلى S3 | ![file](./uploas%20file%20to%20s3.png) |
| 13 | مخطط سير النظام | ![diagram](./Peta%20Aliran%20Aplikasi%20Nota%20&%20Peringatan%20AI.png) |
