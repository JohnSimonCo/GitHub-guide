# GitHub Guide

TODO dricka cava och göra den här rolig
TODO vore skitkul om en av bilderna är på Simme som klickar på knappen

## Introduktion
GitHub är en gratis plattform för att hantera delade kodbaser som kan användas för allt från [hobbyprojekt](schema vgy) (och [skolprojekt](engelska sida)) till [stora företags projekt](angular eller swift). 

Fördelen med GitHub, utom att man kan dela kod med andra, är att alla projekt är versionshanterade. Detta innebär att gamla versioner av kod alltid finns kvar och det är därför lätt att gå tillbaka om man gjort något fel. Projekt på GitHub heter repositories (repos) och versionerna kallas för commits. En commit består av en titel och en uppsättning ändringar på olika filer. Titeln är bra för att komma ihåg vad man gjorde i just en version, vilket även gör det lättare att veta vart man ska gå tillbaka om man ändrar sig om något. 

## Installation
### Skapa konto
För att använda GitHub måste man först skapa ett konto. Du kan registrera dig på (GitHubs hemsida)[länk till register].
### Installera klienten
Nästa steg är att installera klienten för GitHub. Den finns både för Windows och OSX och går att ladda ner (här)[länk till client].

Ladda ner
Installera
Logga in

## Ditt första projekt
### Skapa projektet
För att göra ett nytt projekt klickar du på plussymbolen i det övre vänstra hörnet. Du kan välja var du vill att det ska skapas; default är Documents/GitHub. Här måste du ge projektet ett namn.

-- Bild på har klickat på plusset och skrivit in info

Nästa steg är att publicera projektet på GitHub. Detta gör du genom att trycka på publish knappen i övre högra hörnet.

Du kan nu hitta projektet på https://github.com/[ditt användarnamn]/[namnet på projektet], till exempel [https://github.com/johnrapp/schedule-parser](https://github.com/johnrapp/schedule-parser).

-- Bild på klickat på publish

Om du redan har skrivit kod för ett projekt kan du lägga in de i den nya mappen som skapats.

### Spara ändringar
När du har gjort ändringar till din kod och vill spara dem i GitHub måste du göra en commit. Börja med att skriva vad du gjort sedan förra commiten i textrutan, till exempel "Gjorde så att gubben kunde hoppa" eller "Gjorde about-sidan responsive".

-- Bild på fyllt i commit title

### Ladda upp ändringar
Eftersom commits bara sparas lokalt på din dator måste du ladda upp dem för att andra ska kunna se dem. Detta gör du genom att trycka på synkknappen i det övre högra hörnet.

-- Bild på ska precis klicka på synk

När du synkar laddar du samtidigt ner ändringar som andra gjort på projektet. Om man jobbar fler på samma projekt är det smart att synka ofta, speciellt om man jobbar i samma fil, så att alla utgår från samma kod. Att synka kan ta ett tag och ibland måste man trycka flera gånger. I värsta fall, om du ändrat på samma fil, på samma ställe, som någon annan på projektet, kan det bli en konflikt. Mer om detta kan du läsa i Avancerat.

### Lägg till medarbetare
För att lägga till medarbetare måste man gå in på GitHubs hemsida. Navigera till projektet, antingen genom att skriva det direkt i URLen (se ovan), genom att gå via din profil eller genom att trycka på "View on GitHub" under kugghjulsmenyn.

Gå sedan in på projektinställningarna och skrolla ner till rubriken "Contributors". Här kan du skriva in GitHub-användarnamnet på personen du vill lägga till och sedan trycka på lägg till.

-- Bild på ska precis klicka på synk

### Ladda ner projekt från GitHub
För att ladda ner ett projekt som du skapat själv eller som någon annan lagt till dig på måste du gå in på projektet på GitHubs hemsida. Klicka på sparaknappen, se bilden

-- Bild på kille som klickar på clone-knapp

Om du själv äger projektet kan du även lägga till det genom att klicka på plusknappen och välja "clone". Välj sedan projektet i listan och klicka på clone.

## Avancerat
### Ta bort ändringar från commit
Om du gjort ändringar som du ångrar eller som du inte vill inkludera i en commit kan du högerklicka på filen och klicka "Discard changes". Notera att detta kommer att ändra i filen så gör det inte om det är något du vill spara.

### Ångra en commit
Om du vill ångra en commit kan du högerklicka på den och klicka på "Revert" i detaljskärmen. Detta kommer skapa en ny commit som tar bort alla ändringar i den valda commiten. 

### Hantera filkonflikter
Om flera personer har ändrat i samma fil kan det ibland bli konflikter. Detta syns genom att filen visas i orange i listan över filer. GitHub ger en fil med bådas ändringar tillsammans. Du måste fixa konflikten manuellt genom att gå in i filen och välja vilka ändringar du vill ha kvar.

-- Bild på konflikt, exempelvis från Google

### Manuell commit AKA hacka i shellen 
Ibland kan man få ett felmedellande när man försöka commita eller synka. Oftast fungerar det att starta om GitHub annars måste man commita manuellt genom shellen. Öppna den först genom att klicka på "Open in Git Shell" i kugghjulsmenyn. Skriv sedan
```sh
$ npm install
```
Detta lägger till alla ändringar

Kommita genom shellen
### Ignorera vissa filer
Gitignore

Länk: [Node.js website](https://nodejs.org/en/download/).
Inline kod: `git clone`
Shellhack:
```sh
$ npm install
```
Länka till fil: [LICENCE](https://github.com/johnrapp/novasoftware-schedule-parser/blob/master/LICENSE)
