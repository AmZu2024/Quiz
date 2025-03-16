# Quiz

## Kursmål 1: Utvecklingsprocesserna vid programmering


**Fråga 1:** *Vilken av följande är en typisk första fas i programutvecklingsprocessen?*

- [ ] Kodning 
- [ ] Testning  
- [x] Kravanalys  
- [ ] Implementering

 **Motivering:** Frågan testar om studenten vet vilken fas som inleder en programutvecklingscykel. De andra alternativen representerar senare faser i processen.



**Fråga 2:** *Vilken metod fokuserar på att snabbt utveckla en fungerande version av programmet för att få feedback och förbättra den över tid?*

- [ ] Vattenfallsmodellen 
- [ ] Iterativ utveckling   
- [ ] Big Bang.metoden  
- [x] Agil utveckling 

 **Motivering:** Frågan undersöker studentens förståelse för Agil utveckling, som betonar snabb feedback och kontinuerlig förbättring. De andra alternativen är metoder som inte fokuserar på den här typen av snabb iteration.

 

 **Fråga 3:** *Vad är Scrum inom mjukvaruutveckling?*

- [x] En agil arbetsmetod där utvecklingen sker i korta iterationer  
- [ ] En modell där hela systemet designas i detalj innan kod skrivs    
- [ ] En process där utveckling sker utan planering eller struktur 
- [ ] En metod som fokuserar enbart på testning och kvalitetssäkring
      
**Motivering:** Den här frågan testar förståelsen av Scrum i jämförelse med andra utvecklingsmetoder.

----------------------------------------------------------------------------------------------

## Kursmål 2: Lämpliga kontrollstrukturer och klasser vid testning av applikationer


**Fråga 1:** Vilken kontrollstruktur används mest effektivt för att testa olika fall av en funktion beroende på olika ingångsvärden i ett enhetstest?

- [ ] For-loop  
- [x] If-sats  
- [ ] Switch-sats  
- [ ] Try-catch-sats  

**Motivering:** If-satsen används ofta i tester för att kontrollera olika villkor eller ingångsvärden i en funktion. De andra alternativen används inte lika ofta för att testa specifika fall beroende på ingångsvärden.



**Fråga 2:** Vilken klass i .NET används för att skapa en instans av ett objekt som simulerar ett beteende vid enhetstestning?

- [x] Mock  
- [ ] Assert  
- [ ] TestContext  
- [ ] Exception  

**Motivering:** Frågan testar förståelsen för användningen av Mock-klassen i enhetstestning för att skapa objekt som simulerar beteende av andra objekt (så kallad "mocking"). De andra alternativen har olika användningsområden i testning men används inte för att skapa mockobjekt.



**Fråga 3:** Vilken metod används för att verifiera att ett test har lyckats genom att kontrollera om två värden är lika i ett enhetstest?

- [x] Assert.Equals()  
- [ ] Assert.Pass()  
- [ ] Assert.IsTrue()  
- [ ] Assert.AreNotEqual()  

**Motivering:** Frågan testar förståelsen för metoden som används för att jämföra två värden och bekräfta att de är lika under ett test. Assert.Equals() är den mest direkta metoden för detta, medan de andra alternativen används för andra ändamål.

----------------------------------------------------------------------------------------------

## Kursmål 3: Testdriven utveckling (TDD)

**Fråga 1:** Vad är det första steget i TDD?

- [ ] Implementera den faktiska funktionen  
- [x] Skriva ett test som misslyckas  
- [ ] Refaktorisera den befintliga koden  
- [ ] Skriva tester efter att koden är klar  

**Motivering:** Frågan testar förståelsen av TDD:s cykel. Ett vanligt misstag är att tro att man börjar med kod eller refaktorisering, men i TDD skriver man först ett test som misslyckas innan man implementerar funktionaliteten.



**Fråga 2:** Varför används TDD i mjukvaruutveckling?

- [ ] För att skriva färre tester och spara tid  
- [x] För att förbättra kodens kvalitet och säkerställa att funktionalitet testas tidigt  
- [ ] För att helt ersätta behovet av manuella tester  
- [ ] För att snabba upp utvecklingsprocessen genom att hoppa över testning  

**Motivering:** Den här frågan testar förståelsen av TDD:s syfte. Alternativen innehåller vanliga missuppfattningar, t.ex. att TDD skulle minska behovet av tester eller göra utvecklingen snabbare genom att hoppa över testning.



**Fråga 3:** Vilken av följande beskrivningar stämmer bäst in på TDD?

- [ ] Ett arbetssätt där tester skrivs efter att all kod är färdig  
- [ ] En metod där man testar kod manuellt innan den skrivs  
- [x] En teknik där tester skrivs innan kod, och koden utvecklas i små iterationer  
- [ ] En metod där man endast testar kritiska delar av applikationen för att spara tid  

**Motivering:** Frågan testar om studenten verkligen förstår hur TDD fungerar. De andra alternativen innehåller missuppfattningar, t.ex. att tester skrivs i efterhand (A), att man testar manuellt innan utveckling (B) eller att man bara testar vissa delar (D).

----------------------------------------------------------------------------------------------

## Kursmål 4: ASP.NET Blazor

**Fråga 1:** Vad är ASP.NET Blazor?

- [x] Ett ramverk för att bygga interaktiva webbapplikationer med C#
- [ ] Ett verktyg för att designa databaser i .NET
- [ ] En ersättare för HTML och CSS
- [ ] En teknik för att skapa Windows-applikationer

**Motivering:** Frågan testar studentens grundläggande förståelse för vad Blazor är. De andra alternativen är vanliga missuppfattningar – Blazor ersätter inte HTML/CSS (C) och används inte för Windows-applikationer (D).

**Fråga 2:** Vilken av följande tekniker används av Blazor WebAssembly?

- [ ] Det körs på en .NET-server och uppdaterar klienten via SignalR
- [ ] Det kompileras till JavaScript och körs i webbläsaren
- [x] Det använder WebAssembly för att köra .NET-kod direkt i webbläsaren
- [ ] Det använder endast backend-kod utan någon frontend

**Motivering:** Frågan testar förståelsen för hur Blazor WebAssembly fungerar. Alternativ A beskriver Blazor Server, medan B och D är felaktiga då Blazor WebAssembly inte kompileras till JavaScript och alltid har en frontend.

**Fråga 3:** Hur hanterar Blazor komponenter?

- [ ] Blazor använder en klassbaserad approach där varje komponent är en separat .NET-klass
- [ ] Blazor kräver att alla komponenter skrivs i ren HTML och JavaScript
- [x] Blazor använder en komponentbaserad arkitektur där varje komponent är en .razor-fil som kan innehålla både markup och C#-kod
- [ ] Blazor fungerar bara med MVC-struktur och använder Razor Pages

**Motivering:** Frågan testar förståelsen för Blazors komponentmodell. De andra alternativen beskriver antingen MVC-struktur (D), krav på JavaScript (B), eller en ren klassbaserad approach (A) som inte är korrekt för Blazor.

----------------------------------------------------------------------------------------------

## Kursmål 5: Redogöra för olika begrepp inom objektorientering

**Fråga 1:** Vad innebär inkapsling (encapsulation) i objektorienterad programmering?

- [ ] Att alla klassens variabler och metoder är publika
- [x] Att man kapslar in data och kontrollerar åtkomst via metoder
- [ ] Att en klass kan ärva från en annan klass
- [ ] Att ett objekt kan ha flera former och anpassa sin beteende baserat på sin typ

**Motivering:** Frågan testar förståelsen av inkapsling, en av de fyra grundpelarna i OOP. Distraktorerna representerar andra OOP-koncept: arv (C) och polymorfism (D), medan A är en vanlig missuppfattning.

**Fråga 2:** Vad är skillnaden mellan arv (inheritance) och gränssnitt (interface)?

- [x] Arv gör att en klass kan ärva kod från en basklass, medan ett gränssnitt bara specificerar metoder utan implementation
- [ ] Gränssnitt används bara för att skapa grafiska användargränssnitt
- [ ] Arv används endast i statiska klasser, medan gränssnitt används i dynamiska klasser
- [ ] Arv och gränssnitt är samma sak och används på exakt samma sätt

**Motivering:** Frågan testar förståelsen av arv vs. gränssnitt. Alternativ B är en vanlig missuppfattning om gränssnitt, C är felaktigt eftersom både arv och gränssnitt fungerar med dynamiska klasser, och D är direkt fel.

**Fråga 3:** Vad innebär polymorfism i objektorienterad programmering?

- [x] Att en metod kan ha olika implementationer beroende på vilken klass som anropar den
- [ ] Att en klass kan ha flera basklasser
- [ ] Att en variabel alltid har samma typ och aldrig kan byta beteende
- [ ] Att kod skrivs en gång och aldrig behöver ändras

**Motivering:** Frågan testar förståelsen av polymorfism, en av de viktigaste principerna inom OOP. Alternativ B är fel eftersom C# inte stöder multipelt arv, alternativ C motsäger polymorfismens idé, och D är en missuppfattning.

----------------------------------------------------------------------------------------------

