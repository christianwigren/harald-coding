# Haralds Coding

Saker vi pratade om samt lite länkar:


## Blandat om saker som finns på internet

- För att testa ChatGPT<br />
Skapa konto för att testa är gratis. https://chat.openai.com

- Du surfar nu på en plats på github som jag skapat åt dig gratis.<br />
Github är ett bra ställe att spara, dela och diskutera kod. Även hitta MASSOR med gratis-kod att kopiera och använda till eget bruk. https://github.com/


## För att komma igång med programmering på sin dator

Jag föreslår att man börjar med kod-språket python för att skapa program. För att skapa webbsidor behöver vi lägga html samt eventuelt CSS och Javascript men man kommer en bra bit med bara html också.

### 1. Installera Text-editor för programmering
För att programmera behöver man ett text redigerare som hjälper en med att koda. Ett Word för programmering. Microsoft har skapa en som är populär och fungerar bra på windows m.fl. <br />
[https://code.visualstudio.com](https://code.visualstudio.com/docs/?dv=win64user)

- Tips:
När man använder Visual Code föreslår den rätt ofta att man skall installera "extentions". Gör det, det brukar vara bra saker!

### 2. Installera python-exekverare för att kunna programmera python
Anaconda är rätt bra för underlätta installation av python på windows. 
<br />
https://www.anaconda.com/download/


### 3. Skapa webbsida
För att lära sig grunderna av html samt mycket annat är w3schools en bra webbplats där allt också är gratis att använda. För att komma igång med html så klicka på länken: https://www.w3schools.com/html/

Vill du istället testa att köra själv på din egen dator är här de stegen vi gjorde tillsammans.


#### För att testa att göra en webbsida behövs:
1. Ladda hem koden vi gjorde, klicka på länken: [Haralds kod](https://github.com/christianwigren/harald-coding/archive/refs/heads/main.zip)
2. Packa upp zip-filen på ett ställa ni tycker passa. Kanske under Mina Dokument.
3. Starta Visual Studio Code
4. Välj under Arkiv (File) -> Öppna Mapp (Open Folder) och välj mappen du nyss packat upp.
2. I menyn högst upp i visual code finns ett menyval som heter terminal. Välj där att starta en terminal. Detta för att kunna starta en lite webbserver.
3. Skriv följande kommando: `python3 -m http.server 9000`
(kräver att du har installerat python (anacoda) på din dator)
4. Öppna Edge och surfa till http://localhost:9000/html och du skall förhoppningsvis se din hemsida.
5. Nu kan du redigera html, text och lägga till bilder etc. och spara din html-fil.
6. Ladda om din webbläsare och se dina förändingar.


#### Nästa steg
- För att ändra färger, typsnitt och annat utseende ett till progamspråk som heter CSS.<br /> https://www.w3schools.com/css/


- För att skapa mer avancerade funktioner som t.ex. skapa menyer som fälls ut osv ett till programspråk som heter JavaScript.<br />https://www.w3schools.com/js/default.asp
<br />(En fråga du hade... javascrpt är ett helt annat språk än Java. De snodde "Java" för de trodde att JavaScript skulle bli mer poplärt då, vilket nog lyckades).


- Lär dig använda Webbläsarens utvecklarvertyg vilken du starta med F12. Genom denna kan du undersöka och göra det mesta med webbläsaren och vad den gör med html-koden, CSS och Javascript.


- För att slippa programmera allt från grunden kan man ladda hem och utnyttja färdiga kod-paket. Ett sådan vi pratade om är "HTML, CSS och JavaScript"-paketet Bootstrap.<br /> Detta är från början skapat av Twitter och snällt har delat med sig av detta till världen utan att ta betalt. Idag är ca: 20% av alla världens hemsidor byggda med detta. :)<br />
https://getbootstrap.com/ <br />


### 4. Testa python
Program: Hello World
1. I menyn högst upp i visual code finns ett menyval som heter terminal. Välj där att starta en terminal.
2. Skriv `python3 helloworld.py` i terminalen.
3. Nu skall det skrivas ut "Hello World"
----
Program: Hangman
1. I menyn högst upp i visual code finns ett menyval som heter terminal. Välj där att starta en terminal.
2. Skriv `python3 hangman.py` i terminalen.
3. Nu skall det skrivas ut "Hello World"
----
Program: Snake
1. I menyn högst upp i visual code finns ett menyval som heter terminal. Välj där att starta en terminal.
2. Skriv `pip3 install pygame` i terminalen.
2. Skriv `python3 snake.py` i terminalen.
3. Nu skall det skrivas ut "Hello World"