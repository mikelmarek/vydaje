# 📱 Výdaje – jednoduchá aplikace pro sledování zůstatku z výplaty

Tato malá webová aplikace slouží pro jednoduché sledování, **kolik peněz vám zbývá na měsíc** po započítání pravidelných měsíčních výdajů.  
Funguje přímo v prohlížeči a **všechna data ukládá do vašeho zařízení** (LocalStorage) – nic se nikam neposílá.

Aplikace je optimalizovaná pro mobil (zejména iPhone), ideálně ji používat jako **web-appku z plochy**.

---

## 🚀 Funkce

### **1) Pravidelné měsíční výdaje (Setup)**
V části *setup* si nastavíte všechny vaše opakující se výdaje:

- 🔴 **NUTNÉ** – hypotéka, pojištění, daně, školka…
- 🟡 **DOBROVOLNÉ** – investice, sport, předplatná…
- 🟢 **PROMĚNLIVÉ** – benzín, data, kapesné, spotřeba…

U každé položky lze:

- **Přidat**
- **Upravit**
- **Smazat**

Každá sekce je **rozbalovací / sbalovací** a aplikace si pamatuje její stav.

---

### **2) Výpočet teoretického zůstatku**
Po zadání měsíčního příjmu aplikace automaticky vypočítá:

**Příjem – pravidelné výdaje = Teoreticky zbývá**

Jedním kliknutím lze tuto hodnotu převzít jako **reálný zůstatek**, se kterým chcete pracovat.

---

### **3) Denní zadávání výdajů**
V hlavní části aplikace:

- přidáváte jednotlivé výdaje (částka + popis)
- průběžně vidíte **aktuální zůstatek**
- zůstatek:
  - **zelený**, když jste v plusu  
  - **červený**, pokud jste v minusu
- můžete:
  - **smazat poslední výdaj**
  - **resetovat celý měsíc**
  - zobrazit seznam všech výdajů

Údaje se ukládají přímo v telefonu.

---

## 💾 Kde se data ukládají?

Aplikace používá **LocalStorage**, což znamená:

- vše se ukládá pouze lokálně ve vašem zařízení
- data se nikam neposílají
- přetrvají i po zavření prohlížeče
- vymažou se při resetu Safari dat / factory resetu

---

## 📲 Jak přidat aplikaci na plochu (iPhone)

1. Otevřete Safari  
2. Vložte adresu aplikace (např. `https://mikelmarek.github.io/vydaje/`)  
3. Tapněte na **Sdílet**  
4. Vyberte **Přidat na plochu**  
5. Pojmenujte (např. „Výdaje“)  
6. Hotovo – otevře se jako nativní aplikace

---

## 🛠 Použitá technologie

- **HTML**
- **CSS**
- **JavaScript**
- Úložiště: **LocalStorage**
- Hosting: **GitHub Pages**

Bez knihoven, bez frameworků – rychlé, jednoduché, spolehlivé.

---

## 🔒 Soukromí

Aplikace **neodesílá žádná data** nikam mimo vaše zařízení.  
Veškeré informace jsou pouze uloženy v úložišti vašeho prohlížeče.

---

