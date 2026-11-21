# Connector smoke test

استخدم هذه الفحوصات للقراءة فقط بعد منح حساب GitHub صلاحية الوصول إلى المستودع:

1. عرض بيانات المستودع: `gh repo view OWNER/REPO`
2. عرض الملفات: `gh api repos/OWNER/REPO/contents`
3. قراءة CSV: افتح `data/sample_issues.csv` من تبويب Code أو API.
4. قراءة بيانات الإصدار: افتح `data/sample_release.json`.
5. إذا أُنشئت مسائل أو طلبات سحب اختبارية لاحقًا، يمكن فحصها باستخدام `gh issue list -R OWNER/REPO` و`gh pr list -R OWNER/REPO`.

البيانات في هذا المستودع ملفات توضيحية فقط؛ لا توجد مسائل أو طلبات سحب حقيقية تم إنشاؤها.