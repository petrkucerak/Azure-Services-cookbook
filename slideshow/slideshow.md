---
marp: true
theme: gaia
_class: lead
style: |
  section {
    font-family: 'Segoe UI', monospace;
    color: #fff;
  }
  code {
   font-family: 'Roboto Mono', monospace;
  }
  a {
   color: gray;
  }
  h2 {
    font-size: 1.1rem;
  }
  li{
    font-size: 0.9rem;
  }
  ul {
    margin: 0;
  }
  footer a {
   color: gray;
   font-size: .5rem;
  }
  header {
   font-size: .5rem;
   color: grey;
  }

  /* Styling page number */
  section::after {
    color: grey;
    font-weight: normal;
    font-size: 1.2rem;
  }
header: 'Kuchařka služeb Microsoft Azure'
footer: '[petrkucerak/Azure-Services-cookbook](https://github.com/petrkucerak/Azure-Services-cookbook)'
paginate: true
backgroundColor: "#000"
size: 16:9
---

# 🎥 Spusť nahrávání!

---

![bg 20%](../assets/azure.png)
<!-- ../assets/Image source: https://swimburger.net/media/ppnn3pcl/azure.png -->

---

<!--
header: 'Kuchařka služeb Microsoft Azure'
footer: '[petrkucerak/Azure-Services-cookbook](https://github.com/petrkucerak/Azure-Services-cookbook)'
paginate: true
-->

# Plán

- rychlé nakouknutí na služby z dané oblasti
- otázka po téměř každé sekci
  - tužka + papír / něco na poznámky

---

# Azure Pricing Calculator

- rychlý přehled služeb
- rychlá cenová kalkulace
- [Pricing Calculator](https://azure.microsoft.com/en-gb/pricing/calculator/)

---

<!-- backgroundColor: #F9FAFE -->

![bg fit](../assets/image.png)

---

<!-- backgroundColor: #000 -->

# Obchodní dům

Přišel za vámi obchodní dům, že chce abyste do jejich aplikace přidali featuru, která bude umožňovat jejich zákazníkům naskenovat účtenku a rozdělit jednoltivé položky mezi více lidí. Jakou službu využijete?

---

<!-- backgroundColor: #F9FAFE -->

![bg fit](../assets/image-1.png)

---

<!-- backgroundColor: #000 -->

# Otužilcův deník

Jste vášnivým otužilcem. Chcete si vést pravidelné záznamy o tom, jaká je teplota vody v řece, kam se chodíte každý den otužovat. Bohužel ale ČHMU nemá v daném místě ždnou sondu. Vyrobíte si tedy zařízení, které pomocí LoRa odesílá data na váš server. Vy je chcete ale nějako analyzovat. Jaký produkt byste pro to využili?

---

<!-- backgroundColor: #F9FAFE -->

![bg fit](../assets/image-2.png)

---

<!-- backgroundColor: #000 -->

# Vánoční videopřání

Tvoříte platformu, která umožňuje vašim zákazníkům natáčet videa s využitím rozšířené reality. Funguje tím způsobem, že vás ve videu oblékne do produktu, který zakoupíte a vyexportuje video, které můžete odeslat. Jakou služby byste využili pro hostování takové aplikace?

---

<!-- backgroundColor: #F9FAFE -->

![bg fit](../assets/image-3.png)

---

<!-- backgroundColor: #000 -->

# Kdykoliv a kdekoliv

Vytváříte wordpress pluginy. Pro vývoj si ale musíte neusátále spuštět lokální server. To je ale strašlivá otrava a to především, když chce s vývojem začít někdo noví a to jak na lokálním severu nebo třeba na nějakém jiném. Jakou službu byste využili? Ideálně aby stačilo naklonovat repostář a spustit commnad, který vše několika způsoby rozjede?

---

<!-- backgroundColor: #F9FAFE -->

![bg fit](../assets/image-4.png)

---

<!-- backgroundColor: #000 -->

# Velký počet - není problém

Provozujete službu, která zažívá obrosvký rozmach. Vaše datové analýzy ukazují, že do několika dnů využití vašeho produkutu zažije enormní nárust až od 700%. Na pozadí používáte databázi. Bojíte se, že ale nezvládne obsloužit veliké množství zařízení a jejich dotazů. Jakou službu byste doporučili využít?

---

<!-- backgroundColor: #F9FAFE -->

![bg fit](../assets/image-5.png)

---

<!-- backgroundColor: #000 -->

# Nová infrastruktura za pár minut?

Staráte se o infrastrukturu bance. Chce expandovat do nového regionu. Ten má ale specifika, že musejí všechna data být pouze na serverech v jejich oblati. Musíte tedy vytvořit celou infrastrukutur automatizovaně a co nejdříve. Jaké služby z oblasti DevOps byste využili?

---

<!-- backgroundColor: #F9FAFE -->

![bg fit](../assets/image-6.png)

---

<!-- backgroundColor: #000 -->

# Data pro otužilce podruhé

Chodité se pravidelně otužovat. Ve místě kam chodíte má ČHMU stanici. Ta ovšem zobrazuje data pouze za poslední den. Vy si chcete ale ukládat celou historii. Jaký produkt z nabízených nástrojů využijete?

---

<!-- backgroundColor: #F9FAFE -->

![bg fit](../assets/image-13.png)

---

<!-- backgroundColor: #F9FAFE -->

![bg fit](../assets/image-14.png)

---

<!-- backgroundColor: #F9FAFE -->

![bg fit](../assets/image-7.png)

---

<!-- backgroundColor: #000 -->

# Bezpečnost na Univerzitě

Spravujte velkou inverzitní síť. Využíváte jak vlastních výpočetních zdrojů, tak externách cloudových služeb jako Azure, AWS, ... Vyšlo ale nové nařízení od EU a musíte zabezpečit celý váš hybdriní systém. Jaké služby využijtete?

---

<!-- backgroundColor: #F9FAFE -->

![bg fit](../assets/image-8.png)

---

<!-- backgroundColor: #F9FAFE -->

![bg fit](../assets/image-9.png)

---

<!-- backgroundColor: #000 -->

# Otužilci potřetí

Provozujte obrovskou síť IoT zařízení pro otužilce, které na různých úsecích měří kvalitu vody a teplotu vody. Vlhkost vzduchu a teplotu vzduchu. Data jsou na sondě zpracovávány a odesílány pomocí prokolu MQQT do cloudu. Chybí vám ale určítý aplikační interface, který by zajitil komunikační vrstvu mezi sondou a serverem vytočeným v cloudu. Jakou služby využijete?

---

<!-- backgroundColor: #F9FAFE -->

![bg fit](../assets/image-10.png)

---

<!-- backgroundColor: #000 -->

# Průmysl načas

Jste ředitelem optimalalizace výroby v veliké firmě speciialujzící se na součástky ve sféře automotive. Potřebujte navrhnout linku, která bude splňovat bezpečnostní podmínky a uspokojí vaše potřeby, tedy zrychlení procu výroby. K tomu budete využívat čimu ST32. Jakého řešení využijte k tomu, aby mohla v rálném čase komunikovat mezi sebou i s nadřazenou infrastrukuturou? 

---

<!-- backgroundColor: #F9FAFE -->

![bg fit](../assets/image-11.png)

---

<!-- backgroundColor: #F9FAFE -->

![bg fit](../assets/image-12.png)

---

<!-- backgroundColor: #F9FAFE -->

![bg fit](../assets/image-15.png)

---

<!-- backgroundColor: #000 -->

# Nezapomeň

Vyrábíte online brožuru cílenou na mobilní telfony, která bude fungovat jako PWA s četením na každý den. Chcete umžnit uživatelům, aby nezapomněli na to si každý den čtení přečíst. Jakou službu využijte?

---

<!-- backgroundColor: #F9FAFE -->

![bg fit](../assets/image-16.png)

---

<!-- backgroundColor: #000 -->

# Jak voda v přehradě

Vaše služba se rozrostal a musíte zvětšit vaši infrastrukut. Proto jste z jedné instance serveru škálovali na více. S tím ale nastává problém toho, že musíte být schopni požadvky od klinetů rozdělit mezi více instancí tak, abyste je zvládli rovnoměrné odbavovat. Jakou službu zvolíte?

---

<!-- backgroundColor: #F9FAFE -->

![bg fit](../assets/image-17.png)

---

<!-- backgroundColor: #000 -->

# Automatizace forever

Ve svém automatizovaném procesu pro nasazování aplikací, potřebujte přistupovat k zabezpečeným klíčům. Jakou službu byste pro tento problém zvolili?

---

<!-- backgroundColor: #F9FAFE -->

![bg fit](../assets/image-18.png)

---

<!-- backgroundColor: #000 -->

# Kde jen mám teplate

Vytváříte automatický skript, který má běžet na infrastuktuře u vaši zákazníků. Jeho běh ale vyžaduje stažení *teplate* souboru. Na něho ale máte požadavek takový, že ho chcete být shcopni měnit v čase a všem zákazníkům poskytovat nejnovější verzi aniž byste museli zasahovat do skriptu, který mají u sebe. Zároveň chcete být schpni monitorovat využítí *template* jednotlivými zákazníky. Jaké služby využijete k uložení souboru.

---

<!-- backgroundColor: #F9FAFE -->

![bg fit](../assets/image-19.png)

---

<!-- backgroundColor: #000 -->

# Zase je to pomalé

Provozujte webovou aplikaci, kteá je využívaná po celém světe. Vaše servery ovšem po celém světe distribuované nejsou. Vaše aplikace navíc obashuje spoutu statických dat. Jakou službu byste využili pro zrychlení načítání aplikace?

---

<!-- backgroundColor: #F9FAFE -->

![bg fit](../assets/image-20.png)

---

<!-- backgroundColor: #000 -->

![bg 30%](../assets/image-21.png)