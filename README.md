#### 💡 آپدیت: به دلیل به روز رسانی های API ولیکس و تغییر در endpoint های API، این پروژه در دو نسخه منتشر میشه. یک نسخه برای Wallix Bastion 9.x و نسخه دیگر، برای Wallix Bastion 12.x ورژن در خصوص ورژن 10 به زودی اعلام خواهد شد! یا میتونید با هر دو فایل HTML که اینجا هست تست کنید!

با تشکر از دوستی که این مورد رو متذکر شدن و باعث اصلاح کد شدن! 🌹

متاسفانه با توجه به محدودیت ها، امکان آپلو فایل وجود نداره. برای ورژن 9 باید این تغییر رو در سورس کد بدید، هر جا دیدید:
```
path:'/api/v3.12/
```
تغییرش بدید به:
```
path:'/api/
```
که کلا 5 جا این مورد هست. برای گرفتن لیست کاربران و دیوایس ها و ...
مثلا:
```
{name:'Target Groups',key:'targetsgroup',path:'/api/v3.12/targetgroups?limit=-1'}
```
باید بشه:
```
{name:'Target Groups',key:'targetsgroup',path:'/api/targetgroups?limit=-1'}
```

# فارسی
این صفحه مربوط به پروژه زیر هست، از این نسخه به بعد این پروژه بر پایه API ها گسترش پیدا خواهد کرد و پروژه قبلی دیگه به روز نخواهد شد. اولین نسخه این پروژه یعنی 2.6.0 همون ویژگی های پروژه قبلی با نسخه 2.5.10 رو دارا هست. ویژگی های جدید که فقط در API ها قابل دسترس هست، به این پروژه کم کم افزوده خواهد شد. داکیومنت های این پروژه تا نسخه فعلی یعنی 2.6.0 رو از لینک پایین مطالعه کنید. تنها تفاوت نسخه 2.6.0 این پروژه با نسخه 2.5.10 پروژه قبلی فقط در دریافت اطلاعات ورودی هست. 2.5.10 با فایل های CSV و 2.6.0 از طریق API ها.


لینک پروژه قبلی (نسخه 2.5.10):

https://github.com/sMohammad14/WABACL-wallix-bastion-access-control-list-viewer

---

#### 💡 آپدیت 2.8.0:
##### ✅ قابلیت دانلود جدول خروجی با وضعیت فعلی جدول به صورت زنده، در دو فرمت JSON و CSV اضافه شد. توضیح اینکه فایل های قابل دانلود دقیقا وضعیت فعلی که کاربر هم اکنون در حال مشاهده هست رو شامل میشه، یعنی sorting اعمال شده، ستون های در حال مشاهده یا مخفی شده در فایل های دانلودی، قابل دسترسی هست. به طور دقیق، کاربر هر آنچه اکنون در جدول مشاهده میکند، همان اطلاعات در فایل های ذکر شده به همان شکل در دسترس خواهد بود. 

---
#### 💡 Update: Due to Wallix API updates and changes to API endpoints, this project is released in two versions. One for Wallix Bastion 9.x and the other for Wallix Bastion 12.x. A version for version 10 will be announced soon! Or you can test with both HTML files here!

Thanks to a friend who pointed this out and fixed the code! 🌹

# English
This page relates to the following project. From this version onward, this project will be expanded based on APIs, and the previous project will no longer be updated. The first version of this project, i.e., 2.6.0, includes the same features as the previous project version 2.5.10. New features, which are only accessible via APIs, will be gradually added to this project.
Documentation for this project up to the current version (2.6.0) can be found at the link below. The only difference between version 2.6.0 of this project and version 2.5.10 of the previous project is in how input data is received: 2.5.10 uses CSV files, while 2.6.0 uses APIs.

Link to previous project (version 2.5.10):

https://github.com/sMohammad14/WABACL-wallix-bastion-access-control-list-viewer

---

Unfortunately, due to limitations, it is not possible to upload files. For version 9, you need to make this change in the source code, wherever you see:
```
path:'/api/v3.12/
```
Change it to:
```
path:'/api/
```
There are 5 places in total. To get a list of users and devices and ...
For example:
```
{name:'Target Groups',key:'targetsgroup',path:'/api/v3.12/targetgroups?limit=-1'}
```
It should be:
```
{name:'Target Groups',key:'targetsgroup',path:'/api/targetgroups?limit=-1'}
```

#### 💡Update 2.8.0:
##### ✅Added the ability to download the output table with the current live table state in both JSON and CSV formats. The downloadable files exactly reflect the current state the user is viewing, meaning applied sorting, visible or hidden columns are accessible in the downloaded files. In short, whatever the user currently sees in the table, the same information is available in the mentioned files in the same form.
