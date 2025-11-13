# galerie-umelcu
Dokumentace postupu tvorby webové galerie slavných umělců
1. Cíl projektu

Vytvořit responzivní třístránkový web v češtině s tématem galerie světových umělců, který obsahuje:

Hlavní stránku s náhledy umělců
Detailní stránku s informacemi o umělcích
O nás sekci s popisem galerie


2. Použité nástroje a technologie

HTML5 – základní struktura webu
CSS3 – styly a responzivní design
Tailwind CSS (původně použito, později odstraněno ve prospěch čistého CSS)
Font Awesome – ikony
Picsum Photos – placeholder obrázky
VS Code – vývojové prostředí


3. Postup tvorby

Krok 1: Vytvoření základní struktury
Prompt:
„Vytvoř třístránkový web v češtině na téma galerie slavných umělců s hlavní stránkou, seznamem umělců a sekcí O nás.“
Výstup:
index.html – úvodní stránka s náhledy umělců
umelci.html – detailní informace o umělcích
o-nas.html – informace o galerii

Krok 2: Odstranění inline stylů (Tailwind) a přechod na čisté CSS
Prompt:
„Odeber všechny inline styly ze souborů index.html, umelci.html a o-nas.html a převeď je do externího CSS.“
Výstup:
Všechny třídy Tailwind nahrazeny sémantickými CSS třídami (artist-card, nav-link, footer-section apod.)
Vytvořen soubor styles.css s kompletním stylingem

Krok 3: Vytvoření CSS souboru
Prompt:
„Vytvoř soubor styles.css, který bude obsahovat styly pro všechny tři stránky.“
Výstup:
CSS proměnné (--primary-color, --shadow apod.) pro konzistenci
Responzivní grid a flexbox pro uspořádání obsahu
Animace (např. fade-in pro plynulé načítání)
Media queries pro mobilní zobrazení

Krok 4: Optimalizace pro mobilní zařízení
Prompt:
„Zajisti, aby byl web plně responzivní a dobře vypadal na mobilech.“
Výstup:
Skrytí desktopové navigace na mobilech (display: none)
Zobrazení hamburger menu (mobile-menu-button)
Úprava gridu na jednosloupcové zobrazení (grid-template-columns: 1fr)


4. Klíčové změny oproti původní verzi

Přechod od Tailwind CSS k čistému CSS – lepší udržovatelnost a menší závislosti
Sjednocení stylů napříč stránkami – konzistentní vzhled tlačítek, karet a navigace
Vylepšená responzivita – optimalizace pro mobily, tablety i desktopy


5. Návod na další rozšíření

Přidání JavaScriptu – interaktivní galerie, filtr umělců
Dark mode – přepínání světlého/tmavého vzhledu
Formulář pro kontakt – přidání PHP/Node.js backendu


6. Závěr

Web byl vytvořen pomocí CopyWeb AI s postupným zdokonalováním struktury a stylů. Výsledkem je plně responzivní třístránkový web s čistým kódem a sémantickým HTML.