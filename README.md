# 🇩🇿 Wilaya-Of-Algeria

A **comprehensive JSON dataset** of all the Wilayas of Algeria. Each object includes:

- `code` – Unique code of the wilaya  
- `latin_name` – Latin name of the wilaya  
- `arabic_name` – Arabic name of the wilaya  
- `position` – Geographical coordinates (latitude & longitude)  

This dataset is useful for **web development, mapping applications, forms, and data analysis**.  

---

### ⚡ Features

- Complete list of all Algerian Wilayas  
- Ready-to-use JSON format  
- Includes geographic positions for each wilaya  
- Lightweight (~224 KB) and easy to integrate  
- Can be used for dropdowns, location selection, or GIS apps  

---

### 🛠 How to Use

You can use this JSON file in your project by either importing it directly (if using a frontend framework like Vue.js or React) or fetching it dynamically:

```javascript
// Importing directly
import wilayas from './Commune_Of_Algeria.json';

// OR fetching dynamically
fetch('./Commune_Of_Algeria.json')
  .then(res => res.json())
  .then(data => console.log(data));
```

---

### 🌐 Arabic Translation / النسخة العربية

هذا ملف **JSON شامل** يحتوي على جميع الولايات الجزائرية. كل كائن يحتوي على:

- `code` – الرمز الفريد للولاية  
- `latin_name` – الاسم اللاتيني للولاية  
- `arabic_name` – الاسم العربي للولاية  
- `position` – الإحداثيات الجغرافية (خط العرض وخط الطول)  

---

### ⚡ المميزات

- قائمة كاملة بجميع الولايات الجزائرية  
- جاهز للاستخدام بصيغة JSON  
- يتضمن المواقع الجغرافية لكل ولاية  
- حجم صغير (~224 كيلوبايت) وسهل الدمج  
- يمكن استخدامه في القوائم المنسدلة، اختيار المواقع، أو تطبيقات نظم المعلومات الجغرافية (GIS)  

---

### 🛠 طريقة الاستخدام

يمكنك استخدام هذا الملف في مشروعك إما بالاستيراد المباشر أو عن طريق جلبه ديناميكياً:

```javascript
// الاستيراد المباشر
import wilayas from './Commune_Of_Algeria.json';

// أو الجلب الديناميكي
fetch('./Commune_Of_Algeria.json')
  .then(res => res.json())
  .then(data => console.log(data));
```

---

<sub>Original work by @AbderrahmeneDZ Bouidia & Abdelaziz Belkadi</sub>
