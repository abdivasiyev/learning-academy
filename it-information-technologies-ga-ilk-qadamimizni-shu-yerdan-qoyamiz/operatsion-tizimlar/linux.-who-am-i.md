---
description: Linux OS da kimligimizga oydinlik kiritamiz 🫠
---

# Linux. Who am i?

Ushbu qismda biz Linux operatsion tizimini (keyingi o'rinlarda OS) o'rganishni boshlaymiz. Ushbu OS deyarli barcha joyda, telefonimizdan tortib, gigant serverlargacha joylashib olgan 👀. Bundan kelib chiqadiki, bu tizimni bilmaslik dasturchi uchun uyat bo'ladi 🥹.

Tizimni qanday o'rnatish haqida hech nima demoqchi emasman. Chunki bu haqida [Youtube](https://youtube.com) orqali ko'p narsa topishingiz mumkin. Yoki biror kuni o'rnatish haqida video ham tayyorlab qo'yarman :innocent:.

Xo'sh, linux bilan ishlash uchun bizga nima kerak? Birinchi o'rinda Terminal (agar Windows foydalanuvchisi bo'lsangiz, sizda bu Powershell yoki Cmd deya nomlangan). Undan so'ng esa bor yo'g'i Web-Browser kerak bo'ladi. Butun boshli OS ni oddiygina terminal orqali boshqarish mumkin. Keling, ko'p gapirmasdan birinchi komandamizni ishlatib ko'raylik. Buning uchun avvalo Terminal ni ochib olamiz. Ko'plab distributivlarda Ctrl-Alt-T klavishlarini birgalikda bosish orqali Terminalni ishga tushirish mumkin. Agar bu buyruq ish bermasa, Applications menyusi orqali Terminal ni ochib olasiz.

Terminal ishga tushganda quyidagicha ko'rinishda ochiladi:

<figure><img src="../../.gitbook/assets/image (5).png" alt=""><figcaption><p>Terminal ko'rinishi</p></figcaption></figure>

Bu yerda **asliddin** - bu mening foydalanuvchi nomim, **local-vm** esa kompyuterim nomi.

Linux bilan ishlashda biz terminal emulyatorlari bilan ishlashimiz kerak bo'ladi. Odatiy holda bular bash yoki sh terminal emulyatorlaridan biri bo'lishi mumkin. Hozirgi yangi versiyadagi OS larda zsh ommalashmoqda. Bu bizga nima beradi? Biz bu emulyatorlar orqali buyruqlarimizni OS ga bera olamiz.

<figure><img src="../../.gitbook/assets/image (11).png" alt=""><figcaption><p>Bash va sh terminal emulyatorlari</p></figcaption></figure>

Ularning bir-biridan farqi faqatgina sizga ko'rsatadigan ma'lumotlaridadir ya'ni bir-biridan deyarli farq qilmaydi.

Keling, terminalda turib bizning tizimga login qilgan foydalanuvchimiz nomini bilishga harakat qilaylik: &#x20;

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption><p>whoami buyrug'i</p></figcaption></figure>

`whoami` ushbu buyruq bizga kim ekanimizni ko'rsatib beradi. Bu buyruq inglizchadan "Men kimman?" degan ma'noni bildiradi. Ushbu buyruq haqida quyidagicha ma'lumot olishimiz mumkin:

<figure><img src="../../.gitbook/assets/image (6).png" alt=""><figcaption><p>whoami --help</p></figcaption></figure>

`--help` ushbu buyruq `flag` deb ataladi va deyarli barcha buyruqlarda mavjud bo'ladi. Bu `flag`ning vazifasi biz ishlatmoqchi bo'lgan buyruqning nima vazifa bajarishi haqida ma'lumot berish va qo'shimcha qanday `flag` larga ega ekanligini ko'rsatishdan iboratdir. Keling `--version` flagini ham ishlatib ko'ramiz:

<figure><img src="../../.gitbook/assets/image (8).png" alt=""><figcaption><p>whoami --version</p></figcaption></figure>

Ma'lumotga ko'ra biz `whoami` buyrug'ining 8.32 versiyasini ishlatyapmiz. Qo'shimcha ma'lumot sifatida esa, buyruq ishlab chiqaruvchisi `Richard Mlynarik` ekanligini berdi.

Keling, endi `--help` dan boshqa yo'sinda ham buyruq haqida ma'lumot olib ko'raylik:&#x20;

<figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption><p>man whoami</p></figcaption></figure>

`man <buyruq>`ushbu ko'rinishda biz Linux tizimining istalgan buyrug'ining manuallarini o'qib olishimiz mumkin bo'ladi. Buyruqni yozgach `<Enter>` tugmasini bosing va quyidagi ma'lumotlar Terminalda ko'rinadi:

<figure><img src="../../.gitbook/assets/image (4).png" alt=""><figcaption><p>man whoami &#x3C;Enter></p></figcaption></figure>

Ko'rib turibmizki, bu yerda nisbatan ancha ko'p ma'lumot berilmoqda. Sizga qanday usulda qulay bo'lsa, shu usulda foydalanish huquqiga egasiz. Hech kim urushmaydi ☺️. Bemalol foydalanish mumkin. Keyingi safar esa qanday qilib parolimizni o'zgartirish, yangi foydalanuvchilarni qo'shish haqida gaplashamiz 🥸
