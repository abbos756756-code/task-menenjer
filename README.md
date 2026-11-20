# 🚀 TaskFlow - Zamonaviy Mukammal Task Menejer

Bu loyiha foydalanuvchilarning kundalik reja va vazifalarini to'liq nazorat qilish, yangi vazifalar qo'shish, o'zgartirish, o'chirish va unumdorlikni oshirish uchun yaratilgan zamonaviy web dasturdir.

---

## ✨ Asosiy Imkoniyatlar va Funksiyalar

0. **🤖 Aqlli Reja Tuzuvchi (Smart / AI Task Breakdown):**
   - Ixtiyoriy katta ish yoki maqsadni kiriting (masalan: *"Osh qilmoqchiman"*, *"Uy tozalash"*, *"Sayt yaratish"*, *"Imtihonga tayyorlanish"*, *"Sayohat rejalashtirish"* va h.k.).
   - Tizim ushbu ishni darhol mantiqiy, qadam-baqadam vazifalarga (1-qadam, 2-qadam...) ajratib beradi.
   - Har bir qadamga sarlavha, batafsil tavsif, tavsiya etilgan vaqt (5 minut), kategoriya va ustuvorlik beriladi.
   - "Barcha vazifalarni ro'yxatga qo'shish" tugmasini bosishingiz bilan barcha bosqichlar to'g'ridan-to'g'ri task ro'yxatiga qo'shiladi va 1-bosqich taymeri avtomatik yurgiziladi!

1. **Vazifa Qo'shish (Create):**
   - Vazifa nomi, batafsil izoh/tavsifi.
   - Kategoriyalar (*Ish, Shaxsiy, O'qish, Sog'liq va b.*).
   - Ustuvorlik darajasi (*🔴 Yuqori, 🟡 O'rta, 🟢 Past*).
   - Muddat (Deadline) belgilash.
   - **⏱️ Bajarish vaqti (Taymer):** Har bir vazifaga vaqt (standart 5 minut yoki istalgan daqiqa) beriladi.
   - Vazifa qo'shilganda jonli **yashil Toast bildirishnoma** chiqadi va ro'yxatda darhol paydo bo'ladi.

2. **🔔 Ovozli Signal va Eslatma (Alarm & Timer):**
   - Kiritilgan vazifa uchun ortga hisoblash (Countdown) avtomatik boshlanadi.
   - Kartochkada jonli soniyalar (masalan, `04:59`, `04:58`) ko'rinib turadi, to'xtatib turish (Pause) yoki qayta yurgizish (Reset) mumkin.
   - **Vaqt tugagach (5 minut o'tgach):**
     - Brauzerning **Web Audio API** orqali baland, chiroyli va ritmik ovozli signal yangraydi.
     - Ekranda **"⏰ VAQT TUGADI!"** eslatma oynasi ochiladi va qo'ng'iroq tebranadi.
     - "✅ Bajarildi deb belgilash", "⏳ Yana 5 minut qo'shish (Snooze)" yoki "🔕 Signalni to'xtatish" tugmalari mavjud.
     - Kompyuter ekraniga brauzer bildirishnomasi (Notification) chiqadi.

2. **Vazifani O'zgartirish / Tahrirlash (Update):**
   - Har bir vazifadagi qalamcha tugmasi orqali istalgan ma'lumotni tahrirlash.
   - Holatini o'zgartirish (*Bajarilmoqda* yoki *Bajarildi*).
   - O'zgartirilganda **ko'k rangli bildirishnoma** chiqadi hamda kartochkada **"tahrirlangan"** belgisi ko'rsatiladi.

3. **Vazifani O'chirish (Delete):**
   - Xavfsizlik uchun maxsus tasdiqlash modali (*Confirm Dialog*).
   - O'chirilgach darhol qizil bildirishnoma chiqadi va ro'yxatdan o'chiriladi.

4. **Ko'rinishlar (Views):**
   - **Ro'yxat ko'rinishi (List View):** Qulay va ixcham ro'yxat.
   - **Doska ko'rinishi (Kanban Board):** Trello uslubidagi ustunlar (Bajarilmoqda / Bajarilgan).

5. **Filtrlash va Qidiruv:**
   - Jonli qidiruv tizimi (Search).
   - Holat bo'yicha filtrlar (*Barchasi, Bajarilayotgan, Bajarilgan, Muhim*).
   - Kategoriya va Ustuvorlik bo'yicha alohida filtrlar.
   - Saralash (*Yangi, Eski, Muddati yaqin, Muhimlik va Alifbo tartibida*).

6. **Qo'shimcha Qulayliklar:**
   - 🌙 **Dark / Light Mode:** Tungi va kunduzgi rejim (tanlangan rejim eslab qolinadi).
   - 💾 **Doimiy Xotira (LocalStorage):** Brauzer yopilib ochilganda ham hamma ma'lumotlar saqlanib turadi.
   - 📁 **Eksport va Import (JSON):** Barcha vazifalarni kompyuterga fayl qilib yuklab olish va boshqa qurilmaga tiklash imkoniyati.
   - 📊 **Statistika va Unumdorlik bari:** Vazifalarning umumiy va foizdagi ko'rsatkichi.

---

## 🖥 Qanday Ishga Tushirish Mumkin?

Hech qanday qo'shimcha o'rnatishlar talab qilinmaydi!

1. Papka ichidagi [index.html](file:///c:/Users/Abbos/Desktop/Task-Menenjer/index.html) faylini bosing yoki ikki marta chertib istalgan brauzerda (Chrome, Edge, Firefox, Opera) oching.
2. Ilova darhol to'liq quvvat bilan ishlashga tayyor!
