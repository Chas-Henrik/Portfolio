# Portfolio page from design sketch

This is a multi-page, mobile first portfolio site consisting of 5 pages:
- Home
- About
- Tech Stack
- Projects
- Contact

The design is responsive and is 'mobile first' and support Tablet & Desktop versions as well. Media Queries have been added at 768px for the Mobile version and 1200px for the Desktop version (using a content driven approach). As the site only use HTML & CSS, there is limited support for interaction. The mobile version do support hamburger menu button though, and the site supports ‘dark theme’ configured through the operating system settings as well. All images except 'project images' are 'svg formatted' to seamlessly scale to different resolutions. 

Known problems:
1. None

Notes:
1. The GitHub, Twitter & LinkedIn icons have not been linked to any profile.

## Frågor:
1. Vad är HTML och dess roll inom frontend? Vad menas med semantiskt html?

HTML är grunden för alla web platser och används av webläsare för att visa och presentera innehållet korrekt.
HTML står för 'Hyper Text Markup Language' och används för att skapa och struktur & innehåll på en webplats (rubriker, paragrafer, bilder, listor etc). En webläsare vill endast läsa in HTML filer initialt och sedan kan HTML sidan innehålla CSS och JavaScript, men det är HTML som utgör grunden till alla websidor.

Semantisk HTML innebär att man använder HTML-element som tydligt beskriver sitt innehåll och sin funktion på ett sätt som är meningsfullt både för människor och maskiner, särskilt sökmotorer och skärmläsare.
Icke semantiska HTML element som <div> och <span> ger ingen tydlig indikation på vad innehållet representerar medan semantiska element som <header>, <nav>, <article>, <section>, <footer>, <aside> och <main> ger en starkare struktur och förklaring till innehållet, vilket gör det lättare att förstå för både utvecklare och teknologier som bearbetar webbsidor (t.ex. sökmotorer och skärmläsare). 

2. Vad är CSS och dess roll inom frontend? 

CSS står för Cascading Style Sheet och är ett stilmalls-språk som beskriver utseendet & styling på en websida. Cascading betyder att när flera stilregler kan tillämpas på ett element, så finns det en specifik ordning och prioritering som avgör vilken stil som ska gälla.

CSS används för att förändra färg, form, typsnitt, layout, animation m.m. på en web sida.
CSS filen länkas in från HTML sidan med <link> elementet (t.ex. <link rel="stylesheet" href="./css/style.css">) och är valfri, medan HTML filen är ett krav och måste finnas på alla web platser.

3. Vad menas med responsiv design samt med vilka metoder man kan utveckla responsiva sidor?

En responsiv design anpassar layouten och innehållet (text, bilder etc.) till skärmstorleken.
Man kan anända följande metoder för att utveckla responsiva sidor:
1. Media Queries.
2. Använd relativa dimensioner (%, em, rem, vh, vw)
3. Använd rätt relativ enhet så att objektet skalar bra med skärmstorleken.
4. Designa utifrån innehållet (ibland behövs fler Media Queries för att innehållet ska vara 'läsbart' för alla skärm resolutioner)
5. Gör bilder responsiva så att de stretchar i förhållande till sin behållare och behåller sina proportioner.
6. Använd moderna layout tekniker (CSS Flexbox & Grid). I CSS Flexbox så kan t.ex. följande Flexbox egenskaper användas för att föra sidan responsiv:
   1. flex-direction: row/column
   2. flex-wrap: nowrap/wrap
   3. flex: (flex-grow, flex-shrink, flex-basis)
   4. flex-order

