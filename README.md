# u02 Redesign

## Innehållsförteckning
1. Projektöversikt och Mål
2. Versionshantering och Projektstruktur
3. Designprocess och Användarstudier
4. Designimplementering och Landningssidor
5. Kodstruktur och Teknisk Implementering
6. Tillgänglighet och Responsivitet
7. Agila Metoder och Mötessammanfattningar

<hr>

## 1. Projektöversikt och Mål
Vi är 4 fullstackstudenter som tillsammans ska utveckla, skapa en prototyp, och genomföra en ny design för en webbplats som redan finns.
Målet med detta projekt är att redesigna den omoderna sidan - [Resto Culinair](https://restoculinair.be/nl) till en mer tilltalande, modern och användarvänlig design.

![Royal Catering logo](https://github.com/chas-academy/u02-redesign-grupp-6-0/assets/144438319/9fa39354-d045-4828-8eef-fb2ecf6cd4c7)

<hr>

## 2. Versionshantering och Projektstruktur
Vi har använt oss av git, github samt visual studio code.

Skapat branches för varje sida, committat regelbundet och mergeat de respektive branches i main branch vid slutförtarbete.

vi har använt kanban för att ha struktur och översikt över projektet:
- [Här är våran kanban](https://github.com/orgs/chas-academy/projects/58/views/1)

 <hr>

## 3. Designprocess och Användarstudier
Vi har intervjuat 3 personer som fick svara på några antal frågor.

- [Första intervjuen](https://cdn.discordapp.com/attachments/1054435217491886151/1166445750683713687/Arians_fragor_ux.pdf?ex=654a8442&is=65380f42&hm=e77154675005e093dd3526c36be5c7a1f4fb84bf9a7a78596049490b76dbb9ec&)

- [Andra intervjuen](https://docs.google.com/document/d/1eJp1A3TWhicnWWVaRqJFcnD8Cg21wfDsQpjAAH8uP_Q/edit)

- [Tredje intervjuen](https://docs.google.com/document/d/1eJp1A3TWhicnWWVaRqJFcnD8Cg21wfDsQpjAAH8uP_Q/edit)

Av intervjuerna kunde vi skapa User stories. User stories är korta, beskrivande berättelser som fokuserar på en specifik funktionalitet eller ett användarens behov i en mjukvaruprojekt. De hjälper till att kommunicera krav och mål på ett enkelt och förståeligt sätt och används ofta i agil utvecklingsmetodik för att förstå och prioritera arbetsuppgifter. En typisk user story innehåller en roll, en handling och en nytta och ser ut som "Som [roll], vill jag [handling] så att [nytta]."


---
Utav alla User stories så kunde vi skapa dessa två Personas
- [User stories](https://miro.com/app/board/uXjVNWqJRPM=/?track=true&utm_source=notification&utm_medium=email&utm_campaign=approve-request&utm_content=go-to-miro) 
![Screenshot 2023-10-30 181902](https://github.com/chas-academy/u02-redesign-grupp-6-0/assets/144438319/ae032117-58ba-460e-bd08-0a01c526cd62)
- [Persona 1](https://workspace67795933.xtensio.com/edit/wydf7i2h)
![persona1](https://github.com/chas-academy/u02-redesign-grupp-6-0/assets/123011945/a05e82e0-af8f-45af-812a-9a23d6ad045d)
- [Persona 2](https://workspace67795933.xtensio.com/edit/xyk7kxqh)
![persona2](https://github.com/chas-academy/u02-redesign-grupp-6-0/assets/123011945/5b54e89b-a076-4735-9c7f-3c6e3369694c)
---

Slutligen i användarprocessen så designade vi de respektive sidorna med underlag av userstories samt personas.

- [Här är länken till vår figma design](https://www.figma.com/file/WcCXvpwt1QwWMT6bBFuouz/U02-hemsida?type=design&node-id=0%3A1&mode=design&t=aCWfeevflPbFKy4G-1)
<hr>

## 4. Designimplementering och Landningssidor
Vi har redesignat sex landningssidor enligt kraven. Varje sida inkluderar de element som specificerats, och samma navigationsbar samt footer har implementerats för de samtliga sidorna.

 våra landningssidor som vi redesignat:
* [Startsidan](index.html)
* [Medlemslistan](medlemslista/medlemlista.html)
* [Nyheter sidan](nyheter/nyheter.html)
* [Kontakta oss](kontakt/kontakt.html)
* [Smulllbox sidan](Smullbox/smullbox.html)
* [Digitala Prislistor](priser/priser.html)

 [Här](main.css) är vår gemensamma kompilerad css kod som vi importerat in respektive partial sass filer.

<hr>

## 5. Kodstruktur och Teknisk Implementering
 Vi har använt oss av HTML och SASS.
  Vi har i vårt repo skapat en mapp för varje respektive sida.
 Där i mapparna har vi lagt till sass partial filer som vi länkat i den gemensamma sass filen som kompileras till css.
 I den gemensamma main sass filen har vi koden för header och footer som är återkommande på varje respektive sida.
 Samma HTML kod för header och footer har lagts till i alla html filerna.
## 6. Tillgänglighet och Responsivitet
I figma har vi designat för både desktop och mobil enheter. Varpå vi även implimerat detta i vår kod. Koden är Desktop-first och en specifierad mediaquires för iphone 12 enhet tillagd.
Vi har kontrollerat att sidorna fungerar i chrome, safari, firefox samt microsoft edge.
Vi har även tänkt och implimenterat så gott det går av de riktlinjer som rekommenderas av WCAG.

## 7. Agila Metoder och Mötessammanfattningar
Vi har använt kanban som den agila metoden.
- Det består av 4 sprintar (en i varje vecka)
- Ett stort möte varje tisdag
- Ett check-in möte varje söndagar
- Möte vid behov
- Samt regelbunden kontakt via whatsApp och slack

Här är våra dokument anteckningar från möten:
- [Möte ett](https://docs.google.com/document/d/1Ii5O4iHNKbJlBidY8R11sfKJEu95ktdEd6rpZLJS-Rc/edit#heading=h.nrnw03t7conb)
- [Möte två](https://docs.google.com/document/d/1HLRvN8M7a2Q-akOQSiLCHeMIXw5GPQFWINYcg2Fz_68/edit#heading=h.nrnw03t7conb)
- [Möte tre](https://docs.google.com/document/d/1fpHG7grNxRZRhMNS04G-JBhBUiMjP2vQVulDOTXVDrQ/edit#heading=h.nrnw03t7conb)
- [Möte fyra](https://docs.google.com/document/d/11W2PfY8PnTclS-jVXHEAUMJhMxdG4CEt8_fl5xCicKg/edit#heading=h.nrnw03t7conb)
-[Möte fem](https://docs.google.com/document/d/1dfor2vUBU0UmV_UCuzhn--m57-ZTr4gNdczOBqFtC3g/edit#heading=h.nrnw03t7conb)

<hr>
