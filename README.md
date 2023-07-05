# مساله‌ی طبقه‌بندی تصاویر x-ray
## سطح مسئله:
پردازش تصویر: سطح B
بینایی ماشین: سطح A
پیش پردازش: سطح B
:
## صورت مسئله: 
شهرام در بایگانی یک مرکز درمانی بین جاده ای کار می کند. او موظف است روزانه پرونده های پزشکی بیماران (که از بخش های مختلف مرکز جمع آوری شده، تعداد آنها بسیار زیاد است و میتواند شامل داده های نامرتبط باشد) را در دسته های از پیش تعریف شده دسته بندی کند. در ماه فروردین و همچنین فصل تابستان با توجه به افزایش سفر ها و تصادفات تعداد مراجعات به این مرکز درمانی به شدت افزایش پیدا می کند، در حالی که شهرام فرصت دسته بندی پرونده ها را به تنهایی ندارد. با توجه به این موضوع مرکز درمان تصمیم به هوشمند سازی طبقه بندی پرونده ها گرفته است. در این مساله قصد داریم بخشی از این طبقه بندی را انجام دهیم.

توضیح در مورد داده: داده های این مساله شامل 5 دسته برچسب گذاری شده از تصاویر x-ray (دندان(1)، جمجمه(2)، قفسه سینه(3)، دست(4)، پا(5)) می باشد، که در هر دسته درصد کمی از داده ها در زمان آموزش نسبت به برچسب نسبت داده شده به آنها نادرست می باشند. هدف از این مساله طبقه بندی داده های تست به 6 دسته ی (دندان(1)، جمجمه(2)، قفسه سینه(3)، دست(4)، پا(5) و داده های پرت(6)) می باشد. داده‌های این مساله از این لینک قابل دسترس می‌باشند.

## نحوه ارزیابی: 
به منظور ارزیابی مدل‌ها،‌ تعدادی تصویر تست (از دسته های تصاویر x-ray دندان(1)، جمجمه(2)، قفسه سینه(3)، دست(4)، پا(5) و داده های خارج از این دسته‌ها(6)) به مدل داده می‌شود و میزان accuracy برچسب استخراج شده در مقایسه با برچسب واقعی داده ارزیابی می‌گردد. (هر مرحله‌ی ارزیابی شامل دو تصویر است و در صورتی امتیاز آن مرحله را دریافت می کنید که برچسب هر دو تصویر به درستی تخمین زده شده باشد). در این مساله علاوه بر صحت (accuracy)، سرعت اجرای برنامه و همچنین میزان حافظه‌ی مصرف شده در زمان اجرا و تعداد خط کد نیز مورد ارزیابی قرار می‌گیرد (۸۰ درصد از امتیاز ارزیابی به صحت، ۱۰ درصد به سرعت اجرا، ۵ درصد میزان حافظه مصرف شده و ۵ درصد تعداد خط کد مورد نیاز اختصاص داده شده است).



## گام ها
(1)تشخیص و حذف داده های خارج از محدوده
(2) نرمالسازی
 (3)مدلسازی
 (4)بهینه‌سازی
(5)یادگیری مجموعه باز

## نشان ها
### گام اول: 
بینایی ماشین مقدماتی
گیت مقدماتی
پیش پردازش مقدماتی
مهندسی ویژگی مقدماتی

### گام دوم:
 بینایی ماشین متوسط
گیت مقدماتی
پیش پردازش مقدماتی
مهندسی ویژگی مقدماتی


