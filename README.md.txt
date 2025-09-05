# 💻 Miskolc Számítógép & Laptop Szerviz – Elementor + WooCommerce sablon csomag

Ez a repository egy **WordPress + WooCommerce** alapú weboldal sablont tartalmaz, kifejezetten számítógép- és laptop szerviz, valamint alkatrész webáruház indításához.

## 📦 Mit tartalmaz?
- `elementor-template.json`  
  Elementor importálható sablon, amely tartalmazza a főoldal fő blokkjait:
  - Hero szekció (nagy kép, cím, CTA gomb)  
  - Szolgáltatások blokk (ikonok + leírások)  
  - Termék slider (WooCommerce widget)  
  - Kapcsolat blokk (Google Térkép + űrlap)  

- `products-mintak.csv`  
  WooCommerce termékimport fájl 10 minta termékkel:  
  - Új alkatrészek (SSD, RAM, GPU)  
  - Használt laptop alkatrészek  
  - Kiegészítők (egér, kábel stb.)  

- `README.md`  
  Használati útmutató a sablon és a CSV fájl importálásához.

---

## 🚀 Használati útmutató

### 1. Elementor sablon importálása
1. WordPress admin → **Elementor → Templates → Import Templates**  
2. Válaszd ki a `elementor-template.json` fájlt  
3. A sablont alkalmazhatod bármely oldalhoz (pl. főoldalhoz)

### 2. WooCommerce termékek importálása
1. WordPress admin → **WooCommerce → Termékek → Importálás**  
2. Töltsd fel a `products-mintak.csv` fájlt  
3. Kövesd a lépéseket → Import kész  

### 3. Fizetési beállítások
- **Barion**:  
  - Regisztráció: [https://www.barion.com/hu/](https://www.barion.com/hu/)  
  - Merchant fiók → API kulcs → WooCommerce Barion pluginba illesztve  

- **Stripe**:  
  - Regisztráció: [https://stripe.com](https://stripe.com)  
  - Dashboard → API kulcsok → WooCommerce Stripe pluginba illesztve  

---

## 📌 Javasolt bővítmények
- Elementor (vizuális szerkesztő)  
- Astra vagy Blocksy téma (gyors és reszponzív)  
- WooCommerce (webshop motor)  
- RankMath vagy Yoast SEO (SEO optimalizálás)  
- LiteSpeed Cache (gyorsítás)  
- WPForms (kapcsolati űrlap)  

---

## ✨ Készítette
WordPressGPT – AI Weboldalépítő  
👉 Ha szeretnél hasonló professzionális weboldalt építeni AI segítségével, nézd meg: [10Web.io](https://bit.ly/10web_ai)
