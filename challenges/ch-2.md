<a href="https://quera.org/problemset/9742/"><h1> click here to get challenge </h1> </a>


<div dir="rtl">
می‌خواهیم یک شبکه‌ی اجتماعی ایجاد کنیم که امکان افزودن و جست‌وجو کردن افراد در آن وجود داشته باشد. در این شبکه‌ی اجتماعی، اطلاعات هر شخص شامل نام، جنسیت، سن و شناسه‌ی آن شخص می‌باشد. شناسه‌ی هر شخص بین ۵ تا ۱۰ کاراکتر و شامل حروف کوچک و بزرگ الفبای انگلیسی و اعداد می‌باشد و شناسه‌ی افراد مختلف متفاوت است. دستورات این شبکه به شکل زیر هستند:

Add <username> <gender> <age> <id>
Find <id>
در دستور دوم ممکن است شناسه‌ی نوشته شده معرف یک شخص نباشد؛ در این صورت شما باید در صورت وجود، افرادی را که شناسه‌ی آن‌ها با کاراکترهای نوشته شده شروع می‌شود به عنوان نتیجه‌ی جست‌وجو گزارش کنید. اگر تعداد این افراد بیشتر از ۱۰ نفر بود، فقط ۱۰ نفر اول (به ترتیب لغت‌نامه‌ای) را گزارش کنید.

ورودی
در هر خط از ورودی برنامه، یکی دستورهای بالا وارد خواهد شد. تعداد دستورات از ۱۰۰۰۰۰ کمتر است.

خروجی
برای دستورهای Add عبارتی به شکل User <id> added successfully را در خروجی چاپ کنید.

برای دستورهای Find، نتایج به دست آمده را در خروجی چاپ کنید. برای اینکه نتایج دستورهای مختلف قابل تمایز باشند، در هر خط خروجی شماره‌ی دستور Find متناظر با آن را نیز چاپ کنید. همچنین اگر برای جست‌وجوی انجام شده نتیجه‌ای یافت نشد، عبارت No user found را در خروجی قرار دهید. برای روشن‌تر شدن خروجی‌ها به نمونه توجه کنید.

ورودی نمونه

Add Ali male 20 ali20ali
Add Mohammad male 21 mohammadm
Add Akbar male 30 akbar30
Find ali
Add Maryam female 20 maryam20
Find mohammad21
Add Mahtab female 13 mahtab13
Add Maziar male 40 maziarAk
Find ma


خروجی نمونه
User ali20ali added successfully
User mohammadm added successfully
User akbar30 added successfully
1 Ali male 20 ali20ali
User maryam20 added successfully
2 No user found
User mahtab13 added successfully
User maziarAk added successfully
3 Mahtab female 13 mahtab13
3 Maryam female 20 maryam20
3 Maziar male 40 maziarAk

</div>