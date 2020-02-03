<h1 lang="fa" dir="rtl" align="right">راهنمای توسعه اصولی نرم افزار اندروید</h1>

<p lang="fa" dir="rtl" align="right">به جای serialize کردن data calss ها آن ها را parcelize کنید. Parcelable چندین برابر Serializable سریع است و مثل Serializable آبجکت های موقت بیشمار تولید نمیکند. همچنین کاتلین انوتیشن @Parcelize دارد که از نوشتن همه implementation کلاس Parcelable جلوگیری میکند.</p1>

<p lang="fa" dir="rtl" align="right">در حد امکان از room orm برای دسترسی به دیتابیس استفاده کنید.</p1>
<p lang="fa" dir="rtl" align="right">نام گذاری منابع موجود در res به شکل زیر نام گذاری شوند. (لازم به ذکر است که حتما باید از حروف کوچک و آندرلاین استفاده کرد و حروف بزرگ و دش  و فاصله مشکل سازند)</p1>
<img src="https://jeroenmols.com/img/blog/resourcenaming/resourcenaming_cheatsheet.png">
<p lang="fa" dir="rtl" align="right">برای استفاده از تایپ فیس میتوان از دو روش مرسوم استفاده کرد یکی لایبرری calligraphy که یک بار در کلاس App مقداردهی میشود و همه متن ها را بر اساس تایپ فیس موردنظر تغییر میدهد. دوم استفاده از CustomView به طور مثال IranSansTextView</p1>
<p lang="fa" dir="rtl" align="right">برای icon تا حد امکان از svg یا 9patch استفاده شود.</p1>
<p lang="fa" dir="rtl" align="right">از Template از پیش تعیین شده موجود در گیت برای ساختار و پکیج بندی پروژه استفاده کنید.</p1>
<p lang="fa" dir="rtl" align="right">به هیچ وجه context را static نکنید. (به جز android context)</p1>
<p lang="fa" dir="rtl" align="right">برای ساختن singleton از کلاس مورد نظر در کاتلین کافی است به جای کلیدواژه class از کلیدواژه object برای تعریف کردن کلاس استفاده کنید.</p1>
<p lang="fa" dir="rtl" align="right">کلاس های view به طور مثال activity,fragment,… باید تا حد امکان بی منطق باشند و لاجیک در  vm نوشته شود.</p1>
<p lang="fa" dir="rtl" align="right">برای data class هایی که دارای sub type هستند کلاس های sub type در همان کلاس به صورت inner class تعریف شوند مگر اینکه یک sub type جنرال باشد که حداقل در یک data class دیگر تعریف شود در این صورت باید یک فایل جدا باشد.</p1>
<p lang="fa" dir="rtl" align="right">در صورت نیاز به استفاده از سرویس ها بسته به عمل موردنظر از work manager یا forground service و... استفاده کنید.</p1>
<p lang="fa" dir="rtl" align="right">برای نوشتن ثابت ها (constants) تمام حروف uppercase باشند به همراه آندرلاین مثل: APP_ACCESS_TOKEN</p1>
<p lang="fa" dir="rtl" align="right">برای نامگذاری کلاس ها حروف اول هر کلمه uppercase باشد و از _ استفاده نشود مثل: ShowInfoActivity</p1>
<p lang="fa" dir="rtl" align="right">برای نامگذاری متغییرها و توابع حرف اول کلمه اول کوچک و حروف اول کلمه های بعدی uppercase باشد مثل: getData</p1>
