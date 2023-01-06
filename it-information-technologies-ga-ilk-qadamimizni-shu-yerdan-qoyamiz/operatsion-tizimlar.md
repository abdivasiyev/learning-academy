---
cover: ../.gitbook/assets/image.png
coverY: 0
---

# Operatsion tizimlar

Kundalik hayotda biz telefon, kompyuter kabi texnik qurilmalardan hech qanday qiyinchiliksiz foydalanamiz. Oddiygina tugmani bosib qo'yish, shunchaki qandaydir checkbox ni belgilab qo'yish unchalik qiyin ish emasa 😀

Lekin, lekin endi siz dasturchi bo'lmoqchisiz! Sizga esa oddiygina qilib tugmachani bosib qo'yish yarashmaydi axir 🥲

Keling, avvalo biz telefonimizni yoki kompyuterimizni qanday ishlashini tushunib olaylik 🤓

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption><p>Process of user interaction with hardware</p></figcaption></figure>

Ushbu suratda biz (siz, men, ular, hamma telefon yoki kompyuter ishlatuvchilar 🤪) eng yuqorida **User** qismida turibmiz. Xo'sh, biz yuqoridan turib nima qila olamiz?

Albatta, kompyuter/telefon (keyingi o'rinlarda **qurilma**) ning resurslaridan foydalanish uchun **so'rov/buyruq** jo'natamiz (biz xo'jayinmiz, iltimos qilmaymiz 😏). Bu qanday buyruqlar bo'lishi mumkin?

* Kimgadir telefon qilish
* Kontaktlar ro'yxatidan biz kiritgan raqam, ism yordamida kontaktni topish
* Videoga olish
* Rasmga tushirish
* Printerdan kerakli xujjatni bosib chiqarish
* va mana shunaqanggi oddiygina judaaaa ko'plab buyruqlar

Endi esa, **kompyuter bizga xo'p bo'ladi xo'jayin deydi va buyruqni qabul qiladi.** Lekin, shoshmang bu yerda kompyuter deb rasmda bizdan pastdagi barcha elementlarni aytdim. Xo'sh, u holda bizning buyrug'imizni kim oladi? Albatta dasturchilar tayyorlab qo'ygan **dasturlar (applications)**. U esa o'z navbatida Operatsion tizimga buyruqni jo'natadi.

Xo'sh, bu yerda qandaydir chalkashlik sezdingizmi? Agar sezmagan bo'lsangiz e'tibor qiling quyidagi misolga (do'stingizga telefon qilish jarayoni):

1. Siz, kontaktlar ro'yxatidan do'stingizni tanladingiz.
2. Qo'ng'iroq qilish tugmasini bosdingiz.
3. Tugmani bosganingizda, telefoningizdagi **Contacts** dasturi operatsion tizimga siz bergan telefon raqami bilan bog'lanish haqida buyruq beradi.
4. Operatsion tizim berilgan telefon raqamini qabul qiladi hamda qurilmadagi SimCard ga murojaat qiladi
5. SimCard esa o'z navbatida o'zi biriktirilgan provayderga berilgan raqam bilan o'zini ulashlari haqida buyruq jo'natadi

Endichi, tushungandirsiz 😌. Agar tushunmagan bo'lsangiz xafa bo'lishga hojat yo'q. Buni amaliyotda o'rganib ketasiz 🥸.

Shuncha, bema'ni gapdan so'ng biz, qanday turdagi operatsion tizimlar borligini bir ko'rib chiqsak ham bo'ladi 🥹.

*   Batch Operating System&#x20;

    <figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption><p>Batch operating system</p></figcaption></figure>

    Ushbu turdagi operatsion tizim, bir xil darajadagi buyruqlarni jamlaydi hamda CPU ga "batch" bilan ya'ni donalab emas, guruhlab jo'natadi
*   Time-Sharing Operating System

    <figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption><p>Time-Sharing operating system</p></figcaption></figure>

    Ushbu turdagi tizimlar esa, bir necha buyruqlarni bir vaqtda qabul qiladi va CPU ga jo'natadi. Bu turdagi tizimlar **MultiTasking Systems** deb ham nomlanadi
*   Distributed Operating System

    <figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption><p>Distributed operating system</p></figcaption></figure>

    Ushbu turdagi operatsion tizim, sizning bir tarmoqqa ulangan bir nechta kompyuteringizni boshqarish imkonini beradi, ya'ni bir-biridan alohida bo'lgan bir nechta telefon bor sizda, ularni esa biridan turib boshqarmoqchisiz. Sizga shunday turdagi operatsion tizim kerak bo'ladi.

Biz esa dasturchi sifatida Multitasking Operation System dan foydalanamiz albatta hech kim qarshi bo'lmasa 🙂

Bunday turdagi tizimlarni siz allaqachon bilasiz: Windows (7, 8, 10, 11), Linux (Debian, Ubuntu, Kali, Lubuntu, Monjaro va hk.)

Birinchi bo'lib esa Linuxni o'rganamiz (Windows menga yoqmaydi 🌚)
