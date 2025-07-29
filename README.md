### **Next.js bo‘yicha intervyu savollari va javoblari – 2025**

#### **Next.js haqida umumiy ma’lumot**  
Next.js – bu React asosidagi eng kuchli framework’lardan biri bo‘lib, zamonaviy, tez va SEO’ga mos veb-ilovalarni yaratish uchun ishlatiladi. U server tomonida render qilish (SSR), statik sayt generatsiyasi (SSG), dinamik yo‘naltirish va API yo‘llari kabi xususiyatlarni taqdim etadi, bu esa uni kengaytiriladigan va samarali veb-saytlar yaratish uchun ideal qiladi.

---

### **Next.js bo‘yicha intervyu savollari – Yangi boshlovchilar uchun**

#### **1. Next.js nima?**  
**Javob:**  
Next.js – bu Vercel tomonidan ishlab chiqilgan ochiq kodli, React asosidagi veb-ilovalarni ishlab chiqish framework’i. U server tomonida render qilish, yaxshilangan SEO, ma’lumotlarni olish vositalari, dinamik API yo‘llari va optimallashtirilgan qurilmalarni taqdim etadi. Next.js React, Webpack va Babel’ga asoslanadi.  

---

#### **2. Next.js boshqa JavaScript framework’laridan qanday farq qiladi?**  
**Javob:**  
Next.js – bu React ilovalarini qurish uchun maxsus ishlab chiqilgan framework bo‘lib, quyidagi jihatlari bilan farqlanadi:  

- **Server tomonida render qilish (SSR):** Next.js server tomonida sahifalarni render qilishni qo‘llab-quvvatlaydi, bu esa SEO’ni yaxshilaydi va sahifaning dastlabki yuklanishini tezlashtiradi.  
- **Avtomatik kod bo‘linishi:** JavaScript kodi avtomatik ravishda kichik qismlarga bo‘linadi, faqat kerakli kod sahifa uchun yuklanadi.  
- **API yo‘llari:** Backend funksionalligini frontend bilan bir loyihada oson ishlab chiqish imkonini beradi.  
- **Rasm optimallashtirish:** `next/image` komponenti orqali rasmlarni avtomatik optimallashtirish, dangasa yuklash va moslashuvchan rasmlar.  
- **Oson joylashtirish:** Statik sayt hostingi, serverless joylashtirish va boshqa variantlar bilan oson integratsiya.  

---

#### **3. Next.js’ni qanday o‘rnatish mumkin?**  
**Javob:**  
Next.js’ni o‘rnatish uchun quyidagi qadamlar bajariladi:  

1. **Node.js o‘rnatilganligiga ishonch hosil qiling.**  
2. Terminalda quyidagi buyruqni bajaring:  
   ```bash
   npx create-next-app myapp
   ```  
3. Loyiha papkasiga o‘ting:  
   ```bash
   cd myapp
   ```  
4. `package.json` faylini yangilang:  
   ```json
   {
     "scripts": {
       "dev": "next",
       "build": "next build",
       "start": "next start"
     }
   }
   ```  

---

#### **4. Next.js’da “Salom, Dunyo!” dasturini qanday yozish mumkin?**  
**Javob:**  
Next.js’da oddiy “Salom, Dunyo!” dasturi `app` papkasidagi faylda React komponenti sifatida yaratiladi:  

```javascript
// app/page.js
import React from 'react';

const HomePage = () => {
  return (
    <div>
      <h1>Salom, Next.js!</h1>
    </div>
  );
};

export default HomePage;
```  

---

#### **5. Next.js’ning ba’zi xususiyatlarini sanab o‘ting.**  
**Javob:**  
Next.js veb-ilovalarni ishlab chiqishni osonlashtiradigan quyidagi xususiyatlarni taqdim etadi:  

- **Server tomonida render qilish (SSR):** Sahifalarni serverda render qilib, dastlabki yuklanishni tezlashtiradi va SEO’ni yaxshilaydi.  
- **Statik sayt generatsiyasi (SSG):** Qurilish vaqtida sahifalarni oldindan render qiladi, bu tezroq yuklanish va yaxshi SEO’ni ta’minlaydi.  
- **Fayl tizimiga asoslangan yo‘naltirish:** `pages` papkasidagi fayl tuzilmasiga asoslangan intuitiv yo‘naltirish.  
- **Avtomatik kod bo‘linishi:** Faqat kerakli kodni yuklash orqali samaradorlikni oshiradi.  
- **API yo‘llari:** Serverless funksiyalarni loyiha ichida oson yaratish imkoniyati.  

---

#### **6. SSR nima degani?**  
**Javob:**  
SSR (Server-Side Rendering) – bu veb-ilovada sahifaning HTML’ini server tomonida ishlab chiqarib, brauzerga to‘liq render qilingan holda yuborish texnikasi.  

**SSR jarayoni:**  
1. Foydalanuvchi sahifaga so‘rov yuboradi.  
2. Server JavaScript kodini ishga tushiradi, ma’lumotlarni oladi va HTML’ni yaratadi.  
3. To‘liq render qilingan HTML, CSS va JavaScript brauzerga yuboriladi.  
4. Brauzer HTML’ni oladi va interaktiv elementlar uchun JavaScript’ni “hidratsiya” qiladi.  

---

#### **7. Next.js’dan foydalanishning qanday afzalliklari bor?**  
**Javob:**  
Next.js quyidagi afzalliklarni taqdim etadi:  

- **Server tomonida render qilish (SSR):** Sahifalar serverda render qilinadi, bu SEO’ni yaxshilaydi va dastlabki yuklanishni tezlashtiradi.  
- **Statik sayt generatsiyasi (SSG):** Qurilish vaqtida sahifalarni oldindan yaratadi, bu esa samaradorlik va SEO’ni oshiradi.  
- **Avtomatik kod bo‘linishi:** Faqat kerakli kodni yuklaydi, bu sahifa yuklanishini tezlashtiradi.  
- **O‘rnatilgan CSS qo‘llab-quvvatlash:** CSS modullari, styled-jsx va CSS-in-JS kutubxonalarini qo‘llab-quvvatlaydi.  
- **API yo‘llari:** Backend logikasini loyiha ichida serverless funksiyalar orqali boshqarish imkonini beradi.  

---

#### **8. DOM nima?**  
**Javob:**  
DOM (Document Object Model) – veb-hujjatlar uchun dasturlash interfeysi. U hujjatning tuzilishini ob’ektlar daraxti sifatida ifodalaydi, bu yerda har bir ob’ekt (masalan, elementlar, atributlar, matn) daraxtning tuguni hisoblanadi.  

**DOM’ning asosiy xususiyatlari:**  
- **Daraxt tuzilishi:** HTML yoki XML hujjatini tugunlar daraxti sifatida ifodalaydi.  
- **Ob’ektga yo‘naltirilgan:** Har bir tugun ob’ekt bo‘lib, JavaScript orqali boshqariladi.  
- **Dinamik:** DOM’ni JavaScript orqali real vaqtda o‘zgartirish mumkin.  
- **Brauzer interfeysi:** Veb-sahifalarni ko‘rsatish va boshqarish uchun brauzerlar tomonidan ishlatiladi.  

---

#### **9. Next.js’da mijoz tomonida navigatsiya qanday boshqariladi?**  
**Javob:**  
Next.js HTML5 History API’dan foydalangan holda mijoz tomonida navigatsiyani amalga oshiradi, bu sahifani to‘liq qayta yuklamasdan silliq o‘tishlarni ta’minlaydi.  

**Navigatsiya usullari:**  
1. **Link komponenti:**  
   - `Link` komponenti sahifalar o‘rtasida navigatsiya uchun ishlatiladi. U foydalanuvchi kliklaganda sahifa resurslarini fon rejimida yuklaydi.  
   - Misol:  
     ```javascript
     import Link from 'next/link';

     const MyComponent = () => (
       <Link href="/another-page">
         <a>Boshqa sahifaga o‘tish</a>
       </Link>
     );
     ```  

2. **Dasturiy navigatsiya:**  
   - `useRouter` Hook yoki `router` ob’ekti yordamida dasturiy navigatsiya amalga oshiriladi.  
   - Misol:  
     ```javascript
     import { useRouter } from 'next/router';

     const MyComponent = () => {
       const router = useRouter();
       const handleClick = () => {
         router.push('/another-page');
       };

       return (
         <button onClick={handleClick}>
           Boshqa sahifaga o‘tish
         </button>
       );
     };
     ```  

---

#### **10. Next.js’da dinamik yo‘naltirish tushunchasini tushuntiring.**  
**Javob:**  
Dinamik yo‘naltirish – bu Next.js’da parametrlar asosida sahifalarni dinamik tarzda yaratish imkonini beruvchi mexanizm. Har bir parametr uchun alohida sahifa yaratish o‘rniga, bitta shablon sahifasi ishlatiladi va parametrlar asosida kontent generatsiya qilinadi.  

**Misol:**  
`pages/post/[id].js` fayli yaratilsa, `post/1`, `post/2` kabi URL’lar dinamik tarzda boshqariladi.  

---

#### **11. Next.js’da Styled JSX nima?**  
**Javob:**  
Styled JSX – bu Next.js’da komponentlarni stilize qilish uchun ishlatiladigan CSS-in-JS kutubxonasi. U komponent ichida yozilgan stillarni faqat o‘sha komponentga qo‘llaydi, bu esa stillarning boshqa komponentlarga ta’sirini oldini oladi.  

**Misol:**  
```javascript
const MyComponent = () => (
  <div>
    <p>Bu stilize qilingan matn</p>
    <style jsx>{`
      p {
        color: blue;
        font-size: 18px;
      }
    `}</style>
  </div>
);
```  

---

#### **12. Next.js frontend, backend yoki full-stack framework’imi?**  
**Javob:**  
Next.js – bu **full-stack** framework hisoblanadi. U mijoz tomonida va server tomonida render qilishni qo‘llab-quvvatlaydi, shuningdek, API yo‘llari orqali backend funksionalligini oson boshqarish imkonini beradi.  

---

#### **13. Next.js’dagi oldindan render qilish turlari o‘rtasidagi farqlar.**  

| **Xususiyat** | **Statik Generatsiya (SSG)** | **Server tomonida render qilish (SSR)** |
|---------------|-----------------------------|-----------------------------------------|
| **Generatsiya vaqti** | HTML qurilish vaqtida generatsiya qilinadi. | HTML har bir so‘rovda generatsiya qilinadi. |
| **HTML’dan qayta foydalanish** | Oldindan generatsiya qilingan HTML har bir so‘rovda ishlatiladi. | HTML har so‘rovda yangidan generatsiya qilinadi. |
| **Tavsiya** | Samaradorlik va tezlik uchun tavsiya etiladi. | Tez-tez o‘zgaradigan kontent uchun mos. |
| **Eksport metodlari** | `getStaticProps` yoki sahifa komponentini eksport qilish. | `getServerSideProps` ishlatiladi. |
| **Qurilish vaqtiga bog‘liqlik** | Server resurslariga kamroq bog‘liq. | Server resurslariga ko‘proq bog‘liq. |
| **Samaradorlik** | Oldindan generatsiya qilingani uchun tezroq. | Har so‘rovda yangilanish tufayli sekinroq. |
| **Keshlash** | Statik HTML’ni oson keshlash mumkin. | Server tomonida keshlash mexanizmlari talab qilinadi. |
| **Kengaytirilishi** | Statik kontentni samarali yetkazib beradi. | Dinamik kontent uchun qo‘shimcha server resurslari talab qilinadi. |

---

#### **14. Mijoz tomonida render qilish (CSR) nima va u SSR’dan qanday farq qiladi?**  
**Javob:**  
Mijoz tomonida render qilish (CSR) – bu JavaScript orqali brauzerda sahifani render qilish jarayoni bo‘lib, serverdan faqat minimal HTML, CSS va JavaScript yuboriladi.  

**SSR bilan farqlar:**  
- **SSR:** Server to‘liq render qilingan HTML’ni brauzerga yuboradi, bu esa SEO va dastlabki yuklanishni yaxshilaydi.  
- **CSR:** Dastlab bo‘sh HTML yuboriladi, so‘ngra JavaScript orqali brauzerda kontent render qilinadi.  

---

#### **15. Next.js ilovasida sahifalar o‘rtasida ma’lumotlarni qanday uzatish mumkin?**  
**Javob:**  
Next.js’da sahifalar o‘rtasida ma’lumotlarni uzatishning bir nechta usullari mavjud:  
- **URL so‘rov parametrlari:** `router.query` orqali ma’lumotlar uzatiladi.  
- **Router API:** `useRouter` Hook yoki `router.push` orqali dasturiy navigatsiya.  
- **Holat boshqaruvi kutubxonalari:** Redux yoki React Context orqali global holat boshqariladi.  
- **getServerSideProps:** Serverda ma’lumotlarni olib, sahifaga props sifatida uzatish.  

---

#### **16. Next.js’da `getServerSideProps` va `getStaticProps` o‘rtasidagi farqlar nimalardan iborat?**  

| **Xususiyat** | **getServerSideProps** | **getStaticProps** |
|---------------|-------------------------|---------------------|
| **Ishga tushirish vaqti** | Har bir so‘rovda ishlaydi. | Qurilish vaqtida ishlaydi. |
| **Render turi** | Server tomonida render qilish (SSR). | Statik sayt generatsiyasi (SSG). |
| **Kontent turi** | Tez-tez o‘zgaradigan dinamik kontent. | Nisbatan statik kontent. |
| **Tashqi ma’lumotlar** | Har so‘rovda ma’lumotlarni oladi. | Qurilish vaqtida ma’lumotlarni oladi. |
| **Kontekst ob’ekti** | So‘rov haqidagi ma’lumotlarni o‘z ichiga oladi. | Dinamik parametrlar uchun ishlatiladi. |
| **Xato boshqaruvi** | Har so‘rovda xatolarni boshqaradi. | Qurilish vaqtida xatolarni aniqlaydi. |
| **Samaradorlik** | Har so‘rovda ma’lumot olish tufayli sekinroq. | Qurilish vaqtida ma’lumot olingani uchun tezroq. |

---

### **Next.js bo‘yicha intervyu savollari – O‘rta daraja**

#### **17. `getStaticPaths` funksiyasining maqsadi nima?**  
**Javob:**  
`getStaticPaths` dinamik yo‘llarga ega sahifalar uchun yo‘llarni qurilish vaqtida generatsiya qilish uchun ishlatiladi. U dinamik parametrlarning ro‘yxatini aniqlaydi va har bir parametr uchun statik fayllarni yaratadi.  

**Misol:**  
```javascript
export async function getStaticPaths() {
  return {
    paths: [{ params: { id: '1' } }, { params: { id: '2' } }],
    fallback: false,
  };
}
```  

---

#### **18. React’dagi `useEffect` Hook’ning maqsadi nima va u Next.js bilan qanday bog‘liq?**  
**Javob:**  
`useEffect` Hook funksional komponentlarda yon ta’sirlarni (masalan, API’dan ma’lumot olish, hujjat sarlavhasini yangilash) amalga oshirish uchun ishlatiladi. Next.js’da `useEffect` mijoz tomonida ma’lumotlarni olish uchun `fetch` yoki `Axios`, `SWR` kabi kutubxonalar bilan ishlatiladi.  

---

#### **19. Next.js’da kod bo‘linishi nima?**  
**Javob:**  
Kod bo‘linishi – bu Webpack’ning eng muhim xususiyatlaridan biri bo‘lib, kodni kichikroq qismlarga bo‘lish imkonini beradi, bu qismlar talab bo‘yicha yoki parallel ravishda yuklanadi.  

**Yondashuvlar:**  
- **Kirish nuqtalari:** Qo‘lda kod bo‘linishi uchun kirish nuqtalari sozlanadi.  
- **Takrorlanishning oldini olish:** `SplitChunksPlugin` yordamida kod takrorlanishini kamaytirish.  
- **Dinamik importlar:** Modullarda inline funksiya chaqiruvlari orqali kod bo‘linadi.  

**Maqsad:** Keraksiz kodni yuklamaslik orqali sahifa yuklanish vaqtini yaxshilash.  

---

#### **20. Next.js’da ma’lumotlarni qanday olish mumkin?**  
**Javob:**  
Next.js’da ma’lumotlarni olish uchun quyidagi usullar ishlatiladi:  
- **`getStaticProps`:** Qurilish vaqtida ma’lumotlarni oladi va sahifaga props sifatida uzatadi (SSG uchun).  
- **`getServerSideProps`:** Har bir so‘rovda ma’lumotlarni oladi (SSR uchun).  
- **Mijoz tomonida olish:** `useEffect` yoki `useState` Hook’lar bilan `fetch` yoki `Axios` orqali ma’lumot olish.  

---

#### **21. Next.js ilovalarini stilize qilishning turli usullari qanday?**  
**Javob:**  
Next.js ilovalarini stilize qilish uchun quyidagi usullar mavjud:  

1. **CSS modullari:** Komponentlarga xos CSS fayllari yaratish, nomlarning to‘qnashuvini oldini oladi.  
   - Misol: `styles.module.css` fayli import qilinadi.  
2. **CSS-in-JS kutubxonalari:** `styled-components` yoki `emotion` yordamida stillarni JavaScript ichida yozish.  
3. **Global CSS fayllari:** Butun ilovaga ta’sir qiluvchi stillarni qo‘llash.  

**Tanlov:** Ilovaning ehtiyojlari, samaradorlik va dasturchilarning tajribasiga qarab usul tanlanadi.  

---

#### **22. Next.js’da maxsus server middleware’ni qanday ishlatish mumkin?**  
**Javob:**  
Maxsus server middleware’ni yaratish uchun Node.js serveri sozlanadi va `server.js` faylida `app.use` metodi orqali middleware qo‘shiladi. Bu so‘rov va javoblarni o‘zgartirish imkonini beradi.  

**Misol:**  
```javascript
const express = require('express');
const next = require('next');

const app = next({ dev: process.env.NODE_ENV !== 'production' });
const handle = app.getRequestHandler();

app.prepare().then(() => {
  const server = express();

  server.use((req, res, next) => {
    console.log('Middleware ishladi:', req.url);
    next();
  });

  server.all('*', (req, res) => {
    return handle(req, res);
  });

  server.listen(3000, (err) => {
    if (err) throw err;
    console.log('Server 3000-portda ishlamoqda');
  });
});
```  

---

#### **23. Next.js’da `_app.js` faylining maqsadi nima?**  
**Javob:**  
`_app.js` – bu Next.js ilovasining asosiy komponenti bo‘lib, barcha sahifalar uchun umumiy sozlamalarni o‘zgartirish imkonini beradi.  

**Foydalanish:**  
- Global stillarni qo‘shish.  
- Umumiy layout komponentlarini saqlash.  
- Uchinchi tomon kutubxonalarini ishga tushirish.  

**Misol:**  
```javascript
import '../styles/global.css';

function MyApp({ Component, pageProps }) {
  return <Component {...pageProps} />;
}

export default MyApp;
```  

---

#### **24. Next.js sahifasida server tomonida render qilishni (SSR) qanday amalga oshirish mumkin?**  
**Javob:**  
SSR `getServerSideProps` funksiyasi yordamida amalga oshiriladi.  

**Misol:**  
```javascript
import React from 'react';

const PageAbout = ({ dataFromServer }) => {
  return <div>{dataFromServer}</div>;
};

export async function getServerSideProps() {
  const dataFromServer = 'Bu sahifa uchun server tomonida render qilingan ma’lumot';

  return {
    props: {
      dataFromServer,
    },
  };
}

export default PageAbout;
```  

---

#### **25. Next.js’da “Serverless” joylashtirish tushunchasini tushuntiring. U qanday ishlaydi va qanday afzalliklari bor?**  
**Javob:**  
Serverless joylashtirish – bu Next.js ilovasini Vercel yoki Netlify kabi platformalarda server infratuzilmasini boshqarmasdan joylashtirish.  

**Qanday ishlaydi:**  
- Platforma server tomonida render qilish, yo‘naltirish va boshqa vazifalarni avtomatik boshqaradi.  
- Ilova serverless funksiyalar sifatida ishlaydi, resurslar talabga qarab kengayadi.  

**Afzalliklar:**  
- Oson kengaytirilishi.  
- Xarajatlarni optimallashtirish.  
- Joylashtirish jarayonini soddalashtirish.  

---

#### **26. Next.js ilovalarini nosozliklarni aniqlash va sinovdan o‘tkazish uchun qanday eng yaxshi amaliyotlar mavjud?**  
**Javob:**  
- **Nosozliklarni aniqlash:** Brauzer ishlab chiqaruvchi vositalari, `console` API va uchinchi tomon nosozlik aniqlash vositalaridan foydalanish.  
- **Sinov:** `Jest` va `React Testing Library` yordamida birlik va integratsion sinovlar yozish.  
- **Linting:** TypeScript yoki ESLint yordamida kod xatolarini erta aniqlash.  

---

#### **27. Nima uchun `create-next-app` ishlatiladi?**  
**Javob:**  
`create-next-app` – bu Next.js ilovasini tezda sozlash uchun rasmiy vosita.  

**Afzalliklari:**  
- **Interaktiv sozlash:** `npx create-next-app@latest` buyruqi loyihani sozlashni boshqaradi.  
- **Bog‘liqliksiz:** O‘rnatish jarayoni tez, chunki hech qanday bog‘liqlik yo‘q.  
- **Oflayn imkoniyatlar:** Oflayn rejimda mahalliy keshdan foydalanadi.  
- **Misol loyihalar:** Next.js misollar to‘plamidan loyihani ishga tushirish imkoniyati.  
- **Sinovlar:** Next.js bilan bir xil sinov to‘plamida sinovdan o‘tkaziladi.  

---

#### **28. Next.js’da Image komponenti va rasm optimallashtirish nima?**  
**Javob:**  
`next/image` – bu HTML `<img>` elementining zamonaviy versiyasi bo‘lib, rasmlarni optimallashtirish uchun o‘rnatilgan xususiyatlarni taqdim etadi.  

**Xususiyatlari:**  
- **Samaradorlik:** Har bir qurilma uchun mos o‘lchamdagi rasmlarni yetkazib beradi.  
- **Vizual barqarorlik:** Layout siljishini oldini oladi.  
- **Tez yuklanish:** Rasmlar faqat ko‘rinish maydoniga kirganda yuklanadi.  
- **Moslashuvchanlik:** Masofadagi serverlardagi rasmlarni dinamik o‘lchamini o‘zgartirish imkoniyati.  

---

#### **29. Next.js’da atrof-muhit o‘zgaruvchilari nima?**  
**Javob:**  
Next.js atrof-muhit o‘zgaruvchilarini boshqarish uchun o‘rnatilgan qo‘llab-quvvatlashni taqdim etadi:  
- **`.env.local`:** Atrof-muhit o‘zgaruvchilarini yuklash uchun ishlatiladi.  
- **Brauzerga ochiq o‘zgaruvchilar:** `NEXT_PUBLIC_` prefiksi bilan brauzerga ochiladi.  
- **Standart fayllar:** `.env` (barcha muhitlar uchun), `.env.development` (ishlab chiqish uchun), `.env.production` (ishlab chiqarish uchun).  
- **Ustuvorlik:** `.env.local` har doim standart sozlamalardan ustun turadi.  

---

#### **30. Next.js’da Docker tasviri nima?**  
**Javob:**  
Next.js Docker konteynerlarini qo‘llab-quvvatlaydigan hosting provayderlarida joylashtirilishi mumkin.  

**Amalga oshirish qadamlari:**  
1. Docker’ni o‘rnating.  
2. `with-docker` misolini klonlang.  
3. Konteynerni quring:  
   ```bash
   docker build -t nextjs-docker .
   ```  
4. Konteynerni ishga tushiring:  
   ```bash
   docker run -p 3000:3000 nextjs-docker
   ```  

---

#### **31. Next.js va React JS o‘rtasidagi farqlar nimalardan iborat?**  

| **Xususiyat** | **Next.js** | **React** |
|---------------|-------------|-----------|
| **Ishlab chiqaruvchi** | Vercel | Facebook |
| **Ta’rifi** | Node.js va Babel’ga asoslangan, React bilan birgalikda ishlaydigan framework. | Foydalanuvchi interfeyslarini qurish uchun JavaScript kutubxonasi. |
| **Render qilish** | SSR va SSG’ni qo‘llab-quvvatlaydi. | Asosan mijoz tomonida render qilish (CSR). |
| **Samaradorlik optimallashtirish** | Rasm optimallashtirish, SSR va avtomatik statik optimallashtirish. | O‘rnatilgan optimallashtirish yo‘q. |
| **SEO va tezlik** | SSR va SSG tufayli yaxshi SEO va tez yuklanish. | SEO optimallashtirish uchun qo‘shimcha sozlash talab qilinadi. |

---

### **Next.js bo‘yicha intervyu savollari – Ilg‘or**

#### **32. Next.js’da ma’lumotlarni qanday olish mumkin?**  
**Javob:**  
Ma’lumotlarni olish uchun quyidagi usullar qo‘llaniladi:  
- **SSR uchun `getServerSideProps`:** Har so‘rovda ma’lumotlarni oladi.  
- **CSR uchun `SWR` yoki `useEffect`:** Mijoz tomonida ma’lumot olish uchun ishlatiladi.  
- **SSG uchun `getStaticProps`:** Qurilish vaqtida ma’lumotlarni oladi.  
- **Inkremental statik regeneratsiya:** `getStaticProps` ichida `revalidate` xususiyati bilan.  

---

#### **33. Next.js’da “prefetching” tushunchasini tushuntiring va u samaradorlikka qanday ta’sir qiladi?**  
**Javob:**  
Prefetching – bu Next.js’ning bog‘langan sahifalar uchun JavaScript va resurslarni fon rejimida avtomatik yuklash mexanizmi. Bu navigatsiya vaqtini qisqartiradi va foydalanuvchi tajribasini yaxshilaydi.  

**Ta’siri:**  
- Sahifalar o‘rtasida tezroq o‘tish.  
- Foydalanuvchi tajribasini silliqlashtiradi.  

---

#### **34. Next.js ilovasini ko‘p tillarni qo‘llab-quvvatlash uchun qanday xalqarolashtirish mumkin?**  
**Javob:**  
Xalqarolashtirish (i18n) `next-i18next` kabi kutubxonalar yoki maxsus yechimlar orqali amalga oshiriladi.  

**Qadamlar:**  
- Matn va kontentni tarjima qilish.  
- Tilga asoslangan yo‘naltirishni boshqarish.  
- Foydalanuvchilarga tillar o‘rtasida almashish imkonini berish.  

---

#### **35. Next.js ilovasida boshqa domenlarga API so‘rovlarida CORS’ni qanday boshqarish mumkin?**  
**Javob:**  
CORS’ni boshqarish uchun:  
- **Server sozlamalari:** API’ni qabul qiluvchi serverda CORS sarlavhalari sozlanadi.  
- **Proksi serverless funksiyalari:** Next.js’da serverless funksiyalar orqali CORS sarlavhalari boshqariladi.  

---

#### **36. Serverless arxitektura nima va u Next.js bilan qanday bog‘liq?**  
**Javob:**  
Serverless arxitektura – bu bulutli hisoblash paradigmasi bo‘lib, infratuzilma boshqaruvini provayderga topshiradi va resurslar talabga qarab avtomatik kengayadi.  

**Next.js bilan bog‘liqligi:**  
- Next.js ilovasi AWS Lambda yoki Google Cloud Functions kabi serverless platformalarda joylashtiriladi.  
- Bu resurslardan samarali foydalanish va avtomatik kengayish imkonini beradi.  

---

#### **37. Next.js ilovasining samaradorligini qanday optimallashtirish mumkin?**  
**Javob:**  
Samaradorlikni oshirish uchun:  
- **Kod bo‘linishi:** Keraksiz kodni yuklamaslik.  
- **Dangasa yuklash:** Resurslarni talab bo‘yicha yuklash.  
- **Rasm optimallashtirish:** `next/image` orqali rasmlarni optimallashtirish.  
- **Keshlash:** Server va CDN keshlashdan foydalanish.  
- **Monitoring vositalari:** Lighthouse yoki WebPageTest yordamida tahlil qilish.  

---

#### **38. `getServerSideProps` funksiyasining maqsadi nima?**  
**Javob:**  
`getServerSideProps` dinamik sahifalar uchun server tomonida render qilishni (SSR) amalga oshiradi. U har bir so‘rovda ma’lumotlarni oladi va sahifaga props sifatida uzatadi, bu esa doimiy yangilangan kontentni ta’minlaydi.  

---

#### **39. `next.config.js` faylidagi `excludes` xususiyatining maqsadi nima?**  
**Javob:**  
`excludes` xususiyati Next.js’ning avtomatik kod bo‘linishi va yig‘ish jarayonidan ma’lum fayl yoki papkalarni chiqarib tashlash uchun ishlatiladi.  

**Misol:**  
```javascript
module.exports = {
  excludes: ['/path/to/excluded/file.js', /\/node_modules\//],
};
```  

---

#### **40. `next.config.js` faylidagi `headers` xususiyatining maqsadi nima?**  
**Javob:**  
`headers` xususiyati Next.js ilovasining javoblariga maxsus HTTP sarlavhalarini qo‘shish uchun ishlatiladi (masalan, keshlash siyosatlari, xavfsizlik sarlavhalari).  

**Misol:**  
```javascript
module.exports = {
  async headers() {
    return [
      {
        source: '/path/:slug',
        headers: [
          { key: 'Custom-Header', value: 'Custom-Header-Value' },
          { key: 'Cache-Control', value: 'public, max-age=3600' },
        ],
      },
    ];
  },
};
```  

---

#### **41. `next.config.js` faylidagi `experimental` xususiyatining maqsadi nima?**  
**Javob:**  
`experimental` xususiyati ikki maqsadda ishlatiladi:  
1. **Oldindan chiqarilgan xususiyatlarga kirish:** Next.js’ning barqaror bo‘lmagan yangi xususiyatlarini sinab ko‘rish.  
2. **Ilg‘or sozlamalar:** Past darajadagi optimallashtirishlar va Next.js’ning ichki xatti-harakatlarini nozik sozlash.  

---

#### **42. `next.config.js` faylidagi `redirects` xususiyatining maqsadi nima?**  
**Javob:**  
`redirects` server tomonida yo‘naltirishlarni sozlash uchun ishlatiladi, bu foydalanuvchilarni va qidiruv tizimlarini boshqa URL’ga yo‘naltiradi.  

**Misol:**  
```javascript
module.exports = {
  async redirects() {
    return [
      {
        source: '/old-page',
        destination: '/new-page',
        permanent: true,
      },
    ];
  },
};
```  

---

#### **43. `next.config.js` faylidagi `rewrites` xususiyatining maqsadi nima?**  
**Javob:**  
`rewrites` so‘rov yo‘llarini boshqa yo‘llarga server tomonida qayta yozish uchun ishlatiladi, lekin URL foydalanuvchi uchun o‘zgarmaydi.  

**Misol:**  
```javascript
module.exports = {
  async rewrites() {
    return [
      {
        source: '/blog/:slug',
        destination: '/posts/:slug',
      },
    ];
  },
};
```  

---

#### **44. `getServerSideProps` ishlatmasdan dinamik yo‘naltirish asosida kod bo‘linishini qanday amalga oshirish mumkin?**  
**Javob:**  
1. **`next/dynamic` bilan dinamik importlar:**  
   - Komponentlarni dangasa yuklash uchun ishlatiladi.  
   - Misol:  
     ```javascript
     import dynamic from 'next/dynamic';

     const BlogPost = dynamic(() => import('../components/BlogPost'), {
       loading: () => <p>Post yuklanmoqda...</p>,
     });

     function BlogPage({ postId }) {
       return <BlogPost post={postData} />;
     }

     export default BlogPage;
     ```  

2. **Mijoz tomonida yo‘naltirish (Router bilan):**  
   - `useRouter` Hook yordamida dinamik yo‘llarni boshqarish.  
   - Misol:  
     ```javascript
     import { useRouter } from 'next/router';

     function BlogPage() {
       const router = useRouter();
       const { postId } = router.query;

       return <div>...</div>;
     }

     export default BlogPage;
     ```  

---

#### **45. Qaysi holatlarda `getStaticProps` yoki `getServerSideProps` ishlatishni tanlaysiz?**  
**Javob:**  

**`getStaticProps` tanlash holatlari:**  
- Kontent statik va kamdan-kam o‘zgaradigan bo‘lsa (masalan, blog postlari).  
- Tezlik va SEO muhim bo‘lsa, chunki sahifalar qurilish vaqtida render qilinadi.  
- Server resurslarini tejash va xarajatlarni kamaytirish zarur bo‘lsa.  

**`getServerSideProps` tanlash holatlari:**  
- Kontent tez-tez o‘zgaradigan yoki dinamik bo‘lsa (masalan, yangiliklar, birja narxlari).  
- Foydalanuvchi autentifikatsiyasi yoki shaxsiylashtirish talab qilinsa (masalan, savat yoki foydalanuvchi interfeysi).  
- Tashqi API yoki ma’lumotlar bazasidan real vaqtda ma’lumot olish kerak bo‘lsa.  

---

#### **46. `next export` buyrug‘ining maqsadi nima? U qachon ishlatiladi va qanday cheklovlari bor?**  
**Javob:**  
**Maqsad:**  
`next export` (Next.js 12.2 versiyasida eskirgan) ilovaning statik versiyasini generatsiya qilish uchun ishlatilardi, ya’ni barcha sahifalar HTML, CSS va JavaScript fayllari sifatida `/out` papkasiga saqlanardi. Bu statik fayllarni har qanday veb-serverda joylashtirish imkonini berdi.  

**Ishlatiladigan holatlar:**  
- Tez joylashtirish va server xarajatlarini kamaytirish.  
- SEO’ni yaxshilash.  
- Dastlabki sahifa yuklanishini tezlashtirish.  

**Cheklovlar:**  
- Dinamik kontentni qo‘llab-quvvatlash cheklangan.  
- Qurilish vaqti ko‘proq talab qilinadi.  
- Moslashuvchanlik cheklangan.  

**Hozirgi yondashuv:**  
`next.config.js` faylida `output: 'export'` opsiyasi orqali statik eksport sozlanadi.  

---

#### **47. `pages` papkasidagi `_error.js` va `404.js` fayllarining ahamiyati nima va ularni xatolarni boshqarish uchun qanday sozlash mumkin?**  
**Javob:**  

1. **`_error.js`:**  
   - **Maqsad:** Ilovada ishlov berilmagan xatolarni ushlash uchun umumiy mexanizm.  
   - **Sozlash:** Maxsus `_error.js` fayli yaratiladi, unda foydalanuvchi uchun qulay xato sahifasi ko‘rsatiladi.  
   - **Misol:**  
     ```javascript
     import React from 'react';

     export default function Error({ statusCode }) {
       return (
         <div>
           <h1>Nimadir noto‘g‘ri ketdi!</h1>
           <p>Iltimos, keyinroq qayta urinib ko‘ring.</p>
           {statusCode !== 404 && (
             <p>Holat kodi: {statusCode}</p>
           )}
         </div>
       );
     }
     ```  

2. **`404.js`:**  
   - **Maqsad:** Mavjud bo‘lmagan sahifalarni aniqlash uchun maxsus 404 sahifasi.  
   - **Sozlash:** Maxsus `404.js` fayli orqali foydalanuvchiga ma’lumotli yoki jozibali sahifa ko‘rsatiladi.  
   - **Misol:**  
     ```javascript
     import React from 'react';

     export default function NotFound() {
       return (
         <div>
           <h1>Sahifa topilmadi</h1>
           <p>Siz qidirayotgan sahifa mavjud emas.</p>
           <p>
             Qidiruvdan foydalaning yoki
             <a href="/">bosh sahifaga</a> qayting.
           </p>
         </div>
       );
     }
     ```  

---

#### **48. Next.js’da foydalanuvchi autentifikatsiyasi yoki roliga qarab shartli yo‘naltirishni qanday amalga oshirish mumkin?**  
**Javob:**  

1. **`getServerSideProps` yoki `getStaticProps` ichida yo‘naltirish:**  
   - So‘rovlar ichida shartlarni tekshirib, `res.writeHead()` bilan yo‘naltirish.  
   - Misol:  
     ```javascript
     export async function getServerSideProps(context) {
       const isAuthenticated = await checkAuth(context.req);

       if (!isAuthenticated && context.resolvedUrl !== '/login') {
         context.res.writeHead(302, { Location: '/login' });
         context.res.end();
         return { props: {} };
       }

       return { props: {} };
     }
     ```  

2. **Mijoz tomonida `useEffect` va `router.push` bilan yo‘naltirish:**  
   - Komponent render qilingandan so‘ng yo‘naltirishni amalga oshirish.  
   - Misol:  
     ```javascript
     import { useEffect } from 'react';
     import { useRouter } from 'next/router';

     function MyPage() {
       const router = useRouter();

       useEffect(() => {
         const isAuthenticated = checkAuth();
         if (!isAuthenticated) {
           router.push('/login');
         }
       }, []);

       return <div>...</div>;
     }
     ```  

---

#### **49. `publicRuntimeConfig` va `serverRuntimeConfig` opsiyalarining maqsadi nima va ular oddiy atrof-muhit o‘zgaruvchilaridan qanday farq qiladi?**  
**Javob:**  

1. **`publicRuntimeConfig`:**  
   - **Maqsad:** Mijoz va server tomonida ishlatiladigan sozlamalarni saqlaydi (masalan, API manzillari, tema ma’lumotlari).  
   - **Kirish:** JavaScript to‘plamiga seriyalashtiriladi va mijoz tomonida ishlatiladi.  

2. **`serverRuntimeConfig`:**  
   - **Maqsad:** Faqat server tomonida ishlatiladigan maxfiy sozlamalarni saqlaydi.  
   - **Xavfsizlik:** Mijozga hech qachon ochilmaydi.  

**Atrof-muhit o‘zgaruvchilaridan farqlar:**  
- **Atrof-muhit o‘zgaruvchilari:** Tizim yoki joylashtirish darajasida sozlanadi va har ikkala tomon uchun ham ochiq.  
- **publicRuntimeConfig:** Mijoz tomonida boshqariladigan kirishni ta’minlaydi.  
- **serverRuntimeConfig:** Maxfiy ma’lumotlarni faqat serverda saqlaydi.  

---

#### **50. Next.js loyihasida maxsus xato chegaralarini qanday amalga oshirish mumkin?**  
**Javob:**  

1. **Maxsus xato chegarasi komponentini yaratish:**  
   - `React.Component` sinfini kengaytirgan holda komponent yaratiladi.  
   - `getDerivedStateFromError` va `componentDidCatch` metodlari ishlatiladi.  
   - Misol:  
     ```javascript
     import React from 'react';

     class ErrorBoundary extends React.Component {
       constructor(props) {
         super(props);
         this.state = { hasError: false };
       }

       static getDerivedStateFromError(error) {
         return { hasError: true };
       }

       componentDidCatch(error, errorInfo) {
         // Xatoni jurnalga yozish yoki xato xizmatiga yuborish
       }

       render() {
         if (this.state.hasError) {
           return <h1>Nimadir noto‘g‘ri ketdi.</h1>;
         }
         return this.props.children;
       }
     }
     ```  

2. **Komponentlarni xato chegarasi bilan o‘rash:**  
   - `<ErrorBoundary>` komponenti bilan himoyalanadigan komponentlar o‘raladi.  
   - Misol:  
     ```javascript
     <ErrorBoundary>
       <MyComponent />
     </ErrorBoundary>
     ```  

**Muhim eslatmalar:**  
- Xato chegaralari JavaScript va React xatolarini ushlaydi.  
- Xatolar eng yaqin ota xato chegarasiga o‘tadi.  
