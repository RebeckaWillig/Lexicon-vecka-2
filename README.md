# 📅 Schema Vecka 2: HTML/CSS

Fokus för veckan - Från att få saker att "bara se bra ut på skärmen" till att bygga robust, skalbar och lättläst CSS som håller i ett riktigt teamprojekt.

---

## 🎯 Mål för veckan

* Fortsätt med övningen med det som står under vecka 2 - fokus på ren, effektiv och tydlig kod

## 📚 Material

### 🛠️ Övningar
* [Receptsidan](https://github.com/Lexicon-Utbildning-Front-end-2026-2027/vecka-1/blob/main/ovning-1.md)

## 📅 Måndag: CSS reset, enheter och lite typografi (R)

Hur arbetar vi medvetet med både design och tillgänglighet. Kommer vår sida se lika bra ut när vi ställt in en större text pga nedsatt syn som den gör annars, eller går den sönder?

### 🎯 Mål för dagen

* Ren baseline - Förklara skillnaden mellan webbläsarens standardstilar och varför moderna projekt behöver en CSS reset.
* Fatta medvetna beslut - När är rem bättre än px och vilka andra enheter ska jag välja mellan
* Välja typsnittt - Grundläggande om typografi samt google fonts

### 📚 Material

#### 💻 E-Learning
* [(YT) Kevin Powell - 3 modern CSS properties to add to your reset](https://www.youtube.com/watch?v=qI5rXLJnxco)
* [(YT) Kevin Powell - CSS Units](https://www.youtube.com/watch?v=Utc_uhvTluk)

#### 📃 Läsning
* [Minimal reset](https://codepen.io/kevinpowell/pen/QWxBgZX)
* [Tailwinds reset](https://tailwindcss.com/docs/preflight)
* [Josh W Comeau Reset](https://www.joshwcomeau.com/css/custom-css-reset/)
* [Om olika enheter - whatunit](https://whatunit.com/)
* [Andy Bell - A (more) Modern CSS Reset](https://piccalil.li/blog/a-more-modern-css-reset/)

#### 🛠️ Övningar
* Öva på att gör er receptsida mer genomtänkt och effektiv med bättre enheter, fonter och reset

---

## 📅 Tisdag: Selectors med precision (P)

Behöver vi en klass för allt, eller kan vi använda relationer som has() eller where() för att skriva bättre kod?

### 🎯 Mål för dagen

* Skriva moderna, flexibla regler med moderna pseudoklasser som :has(), :is() och :where() för att skriva renare selectors som anpassar sig efter kontext.
* Träffa rätt utan !important. Förstå hur CSS räknar specificitet och hur du löser stilkrockar med arkitektur istället för råstyrka.
* Skapa interaktiva lägen. Säkerställa tydliga och korrekta tillstånd för tangenter och mus (:focus-visible, :hover).
* Skapa stilar för aktiva lägen med t ex li:has(:checked)
* Använd modern nestad CSS för att organisera koden utan att få problem med specificitet

### 📚 Material

#### 💻 E-Learning
* [(YT Kevin Powell) is(), where(), has() explained](https://www.youtube.com/watch?v=3ncFpP8GP4g)
* [(YT Kevin Powell)  HTML & CSS for Absolute Beginners: Specificity](https://www.youtube.com/watch?v=LUDkXMXf3P8)
* [(YT) Kevin Powell - Nesting CSS](https://www.youtube.com/watch?v=h4Xp1QgNkhU)

#### 📃 Läsning
* [(css-tricks) CSS Selectors](https://css-tricks.com/css-selectors/)
* [CSS Selectors](https://www.w3schools.com/CSSref/css_selectors.php)
* [CSS Combinators](https://www.w3schools.com/CSSref/css_ref_combinators.php)
* [(css-tricks) Specifics on CSS Specificity (frivillig)](https://css-tricks.com/specifics-on-css-specificity/)

#### 🛠️ Övningar
* [CSS Diner](https://flukeout.github.io/)

---

## 📅 Onsdag: Kodkvalitet och "clean CSS" (R)

Hur vi kan göra vår CSS mer läsbar/hanterbar och mer effektiv. Om vi läser vår kod om 6 månader eller lämnar till en kollega, kommer de fortfarande förstå och kunna arbeta vidare med den?

### 🎯 Mål för dagen

* Använda variabler i CSS för att skapa struktur, modularitet och tydlighet
* Skapa ett token baserat design system genom att använda variabler i CSS
* Förstå principerna bakom namngivningskonventioner i CSS (BEM-CUBE-Utility-First/Tailwind)
* Skriv hjälpsamma kommentarer, inte överflödiga

### 📚 Material

#### 💻 E-Learning
* [(Pluralsight) Clean Code and Accessibility](https://app.pluralsight.com/ilx/video-courses/clips/06125ef3-cc36-4490-a93d-e7147305a13b)

#### 📃 Läsning
* [Tailwind CSS - Styling with Utility Classes](https://tailwindcss.com/docs/styling-with-utility-classes)
* [BEM.info](https://en.bem.info/methodology/css/)
* [CUBE CSS](https://cube.fyi/)
* [(w3schools) CSS Variables](https://www.w3schools.com/css/css3_variables.asp)
* [(mdn) Using CSS custom properties (variables)](https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Cascading_variables/Using_custom_properties)
* [Beginner’s Guide to CSS Comments](https://zerotomastery.io/blog/css-comments/)
* [The Art of Comments](https://css-tricks.com/the-art-of-comments/)

#### 🛠️ Övningar
* Gå in och redigera er receptsida med en bra och genomtänkt namngivning och kodstruktur

---

## 📅 Torsdag: Eget arbete

Eget arbete och med kod, e-learning och läsning. Se till att jobba mot veckans mål nedan när ni förbättrar receptsidan ytterligare. 

### 🎯 Mål för dagen

* Inga hårdkodade färger (allt via CSS-variabler)
* Genomtänkt enhetsstrategi (rem vs px)
* Tydlig, förutsägbar klassnamnsstruktur
* Använd en CSS reset för att se till att semantiken styr, inte stilmallar
* Använd nestad CSS med smart användning av selectors

---

## 📅 Fredag: Kodsnack (P)

### Kodsnack i grupp
* Vi granskar varandras kod. Tillsammans identifierar vi dolda fällor och diskuterar hur det kan skrivas enligt modern standard.

* Diskutera veckans frågor: Vad kändes ovant? Vilka enheter vållade problem? Formulera tillsammans 3-5 principer alla i gruppen tycker definierar "ren CSS". 

* Samling - Vi sammanfattar gruppernas principer för bra kod inför kommande veckors arbete.



---



> Kom ihåg att gå tillbaka till tidigare veckor för material om ni behöver repetera.
