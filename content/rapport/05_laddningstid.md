TV-kanalernas laddningstid på nätet
===============================================================
Denna rapport analyserar hur lång tid det tar att ladda ned Sveriges största TV-kanalers webbplatser.

Urval
-------------
Urvalet är detsamma som i den föregående rapporten om färgscheman, det vill säga de tre största TV-kanalerna enligt branschorganisationen MMS. Dessa kanaler är SVT, TV4 och Kanal 5. Jag valde samma webbplatser som tidigare för att fördjupa kunskapen om dessa. Kanal 5 är en undersida till webbplatsen Dplay.

Metod
--------------
Jag har kört webbplatserna i Google Page Speed och sedan mätt tid, storlek och antal förfrågningar vid nedladdning i Firefox Devtools. Varje webbplats har testats tre gånger vardera på desktop och mobilläge. Eftersom de har samma webbadress på desktop och mobil finns ingen särskild mobilmätning i Google Page Speed.

Nedan visas skärmdumpar från de tre webbplatserna.

**[SVT:](https://www.svt.se/)**
[FIGURE src="image/svtny.png?w=400"]

**[TV4:](https://www.tv4.se/)**
[FIGURE src="image/tv4ny.png?w=400"]

**[Kanal 5:](https://www.dplay.se/kanaler/kanal5)**
[FIGURE src="image/kanal5ny.png?w=400"]

Resultat
---------------

[Här finns mina mätvärden (Google docs)](https://docs.google.com/spreadsheets/d/1jPHoX9dBuFBEdRXVfCoXclTYIc4wjlaGURMLsA_yotc/edit#gid=0)

Samtliga webbplatser får betyget långsam i Google Page speed. Nedladdningstiden enligt Firefox Devops ligger mellan 2 och 6 sekunder. Det var svårt att avgöra tiden eftersom sidorna fortsätter att ladda ner material till synes i det oändliga. Det mesta har laddats ner vid den tid jag har angivit. Sedan följer stora paket - sannolikt videoklipp och reklam - som dyker upp cirka var tredje sekund, och då kan det handla om 5 MB i taget som laddas ned. Merparten av det som laddas ned under den tidsrymd jag angivit utgörs av bilder, vissa av dem med en storlek på 100 KB men de flesta är kring 10-20 KB.


Analys
--------------
Alla tre webbplatserna har anmärkningsvärt långa nedladdningstider. Som användare upplever jag dem också som ganska sega, men inte så pass sega att de är avskräckande långsamma. Jag tror att man kan ha ett visst tålamod med webbplatser som man vet innehåller mycket stora mängder data, framför allt i form av videoklipp. Webbplatserna har också gemensamt att de går att använda långt innan allt material har laddats ned. TV4 har flera anmärkningsvärt stora bilder på flera hundra KB på sin webbplats i jpg- och png-format. SVT använder i stort sett enbart webp-bilder och endast en bild var över 100 KB (som jag inte lyckades hitta på webbplatsen). Kanal 5 utmärker sig med att Javascript-filer står för över hälften av den totala mängden nedladdad data.

Webbplatsernas många bilder och videofilmer är definitivt en orsak till deras långsamhet. Det ligger förstås i deras affärsidé att ha dessa, och de har hanterat detta genom att ladda ned de viktigaste först så att det snabbt går att komma igång. Klar vinnare är SVT och det gäller både nedladdningsdata och upplevelsen vid användning. Den känns helt enkelt snabbare än de båda andra webbplatserna. Kanal 5 kommer tvåa och TV4 trea, och det gäller både objektiva data och subjektiv upplevelse. Det är möjligen frånvaron av reklam som gör att SVT är snabbare, men det är inget jag har belägg för. Mitt antagande är att en bättre bildhantering av SVT är den avgörande faktorn.

Jag tycker det är svårt att sätta en gräns för vilken nedladdningstid som är acceptabel för användare. Jag tror att ca 1 sekund är vad man tål när man googlar och klickar på en länk, och det klarar ingen av de webbplatser jag har undersökt. På en webbplats som man går till där man vet att de har just det man efterfrågar är tiden av mindre betydelse, men de måste se upp för konkurrenter. Kan någon annan erbjuda samma sak men snabbare kommer den webbplatsen säkert att snabbt ta över marknaden.

Avslutning
-------------
Denna rapport är författad av Ingvar Lagerlöf.
