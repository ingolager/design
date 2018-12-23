kmom06 - tema designelement
===========================
Jag har arbetat med åtminstone dessa designelement till mitt tema: färg, bild, form, genomskinlighet, djup, textur och rörelse. Temat har också ärvt element som grid och typografi från tidigare teman.

Så här har jag gjort:

##Bild
Jag lade in en bakgrundsbild över hela webbplatsens body. Bilden har background-attachment fixed.

##Färg
Jag skapade ett nytt färgtema, med det gula på cykelns ram som basfärg och med i övrigt mycket grönt för att anknyta till skogen på bilden. Jag har använt ett fyrfärgstema från färghjuet i paletton.com.

##Form
Jag rundade av kanterna i textfälten med hjälp av border-radius för att få ett mjukare intryck i samklang med skogen på bilden. Flash-regionen utgörs av en triangel skapad i CSS och med samma gula färg som cykelramen.

##Genomskinlighet
I elementen i main och sidebars har färgen en alfa-kanal med värdet 0,9 och släpper därmed genomen en antydan av bagkrundsbilden. Footerns färg har en alfa-kanal med värdet 0,8. Jag valde alfa-kanal i stället för opacity för att behålla läsbarheten i texten.

##Textur
Jag tog en bild av ett skrynkligt lakan från min garderob och lade som bakgrundsbild i footern under den gröna färgen. Footern får därmed en textil känsla. I både headern och footern är färgerna bakgrundsbilder med gradienter. I footern finns ingen färgskiftning i gradienten, jag valde denna teknik för att det var enda sättet jag lyckades kombinera ett lager färg med en bakgrundsbild.  

##Djup
Bakgrundsbilden skapar ett djup eftersom den ger intrycket av att ligga under övriga element. Även texturen i footern ger en känsla av djup.

##Rörelse
Den gula pilen ger rörelse på två sätt. Både bokstavligt genom animationen och bildligt genom att den pekar ner mot texten. Pilens riktning förstärks av träden i bakgrundsbilden.
