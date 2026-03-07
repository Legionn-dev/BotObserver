# 🤖 Line Tracker App (Beta)

Tento projekt je Android aplikácia určená na sledovanie pohybu robotov po dráhe (line follower), meranie ich času a počítanie kôl pomocou kamery smartfónu.

> **Beta Verzia:** Aplikácia je momentálne vo fáze testovania. Na novom používateľskom rozhraní (UI) a systéme vyhodnocovania sa aktívne pracuje.

---

## 📲 Inštalácia (Android)

Aplikácia je určená výhradne pre zariadenia s OS **Android**. Inštaluje sa manuálne pomocou súboru `.apk`.

1. **Stiahnutie:** Choďte do sekcie [Releases](https://github.com/Legionn-dev/Line-tracker/releases) v tomto repozitári.
2. **Výber verzie:** Stiahnite si najnovší súbor s názvom napr. `LineTracker_Beta.apk`.
3. **Povolenie inštalácie:** Po otvorení súboru vás Android môže upozorniť na "Neznámy zdroj". V nastaveniach telefónu povoľte inštaláciu z prehliadača alebo správcu súborov.
4. **Bezpečnostné upozornenie:** Ak sa objaví hláška **Google Play Protect**, kliknite na "Viac informácií" a následne na tlačidlo **"Inštalovať aj napriek tomu"**.

---

## ⚙️ Režimy aplikácie

Medzi módmi sa prepína pomocou tlačidla v **pravom hornom rohu** (ikona 🔄 - loading šípky).

### 1. Režim kontroly zakázaných farieb (Color Check)
Tento mód slúži na technickú kontrolu robotov pred štartom.
* **Účel:** Súťažiaci si týmto módom oskenujú svojho robota, aby zistili, či neobsahuje zakázané farby, ktoré by mohli rušiť senzory na dráhe.
* **Diagnostika:** Ak v tomto móde uvidíte na obrazovke (na tele robota) **biele miesta**, znamená to, že robot obsahuje farbu/odraz, ktorý tam nesmie byť a musí byť odstránený alebo prelepený.

### 2. Súťažný režim (Competition Mode)
Hlavný mód pre meranie výkonu a času kôl.
* **Možnosti:** Nastavenie počtu súťažiacich (1 alebo 2) a cieľového počtu kôl.
* **Príprava a zafixovanie:** 1. Namierte kameru na dráhu.
    2. Stlačte tlačidlo **Play** (▶️) v **ľavom hornom rohu**. Týmto sa zafixuje sledovanie bodov na dráhe.
* **Ovládanie (Dolné menu):** Po zafixovaní sa v spodnej časti obrazovky zobrazí menu:
    * **Tlačidlo Spustiť:** Aktivuje samotné meranie času a sledovanie robota.
    * **Tlačidlo Reset:** Ak potrebujete zrušiť zafixovanie a nastaviť body znova, použite tlačidlo v **hornom strede** obrazovky. Ak chcete resetovať priebeh merania v dolnom menu, použite tlačidlo **Reset** tam.

---

## 🛠️ Podpora a kompatibilita
* **Platforma:** Výhradne Android.
* **Hardvér:** Vyžaduje funkčnú zadnú kameru a povolenie prístupu k nej v systéme.

