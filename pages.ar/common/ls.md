# ls

> إدراج محتويات مجلد.
> لمزيد من التفاصيل: <https://www.gnu.org/software/coreutils/manual/html_node/ls-invocation.html>.

- إدراج كل الملفات في أسطر منفصلة:

`ls -1`

- إدراج جميع الملفات بما فيها الملفات المخفية:

`ls {{[-a|--all]}}`

- إدراج جميع الملفات مع إضافة `/` لنهاية أسماء المللفات:

`ls {{[-F|--classify]}}`

- إدراج الملفات و معلموماتها لتشمل اللأذونات و الملكية و الحجم و تاريخ التغيير:

`ls {{[-la|--all -l]}}`

- إدراج اللملفات بصيغة طويلة مع حجم الملفات بوحدات مقروءة (KiB, MiB, GiB):

`ls {{[-lh|-l --human-readable]}}`

- صيغة طويلة للملفات مرتبة تنازليا حسب اللحجم:

`ls {{-lSR|-lS --recursive}}`

- صيغة طويلة للملفات مرتبة تنازليا حسب التاريخ الأقدم اولا:

`ls {{[-ltr|-lt --reverse]}}`

- إدراج المجلدات فقط:

`ls {{[-d|--directory]}} */`
