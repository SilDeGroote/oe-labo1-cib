# LaboReeks Git
## **Labo 1**

In dit eerste labo zorgen we ervoor dat alles wat we nodig hebben om aan de slag te gaan met git ook effectief aanwezig is!
Samen hiermee controleren we ook meteen de instellingen van je Github account.
Vervolgens gaan we ook al aan de slag met de basis git commando's (lokaal en remote).

### **Hoe werken de labo's?**
Elk labo in deze reeks heeft een aantal uit te voeren stappen.
Deze stappen zullen steeds in een takenlijst te volgen zijn.

Volg alle stappen in volgorde: het overslaan van een of meerdere stappen,
evenals het incorrect uitvoeren, kan er toe leiden dat je de rest van het labo niet langer succesvol kan afronden.

#### **Aanvullende toets op Leho**
Na het afwerken van een labo heb je steeds op Leho een aanvullende toets met betrekking tot het labo en de leerstof gekoppeld aan het labo.
Je mag de aanvullende toets steeds afleggen gebruik makend van alle bronnen (cursusmateriaal, labo, online bronnen, ...).
**Deze toets is verplicht en wordt gequoteerd als permanente evaluatie.**
Je kan de toets niet volledig invullen zonder eerst het labo te maken.

---

### **Deel 1: Installatie en configuratie van git**
- [x] Ga naar de [website van git](https://git-scm.com/) en download de laatste versie. _(De meest geschikte voor jouw OS)_
- [x] Volg de stappen onder *Git Installatie* in de cursus over Git en installeer Git op jouw computer. Deze kan je terugvinden op Leho.
- [x] Na de Git installatie controleer je je gebruikersinstellingen, gebruik hiervoor de volgende commando's:
```git
git config --global user.name
git config --global user.email
```
- [x] Indien je gebruikersinstellingen niet gekend zijn of verkeerd zijn, maak dan de nodige aanpassingen. Hiervoor kan je gebruik maken van volgende commando's:
```git
git config --global user.name "Jouw GitHub Gebruikersnaam"
git config --global user.email "voornaam.familienaam@student.howest.be"
```

- [x] Maak een screenshot van je gebruik van bovenstaande commando's. Geef deze screenshot de naam **deel1** (met extentie naar keuze—**GEEN hoofdletters**—bv. **deel1.png**).
      Bewaar de afbeelding ergens op je pc, je hebt ze verder in het labo weer nodig.

>**Tip!** Als windows gebruiker kan je dit snel en makkelijk doen door de toetsencombinatie _Win+Shift+S_.
Vervolgens sla je de screenshot op met de gevraagde naamgeving.
---
### **Deel 2: Van start met git!**

- [x] Open de Git Bash Console op de locatie waar je aan de slag wil/zal gaan voor dit labo.
>**Tip!** Indien deze optie niet beschikbaar is, dan heb je een stap in de aanbevolen installatie overgeslaan. Herneem deze dan eerst even!

- [x] Gebruik het gepaste git commando om een nieuwe folder aan te maken **met** git version control. Deze folder krijgt de naam **labo1**.
>**Tip!** Het git commando dat je nodig hebt, helpt je om een nieuwe git repository te *initialiseren* gelijktijdig bij het aanmaken van een nieuwe folder.

- [x] Ga vervolgens via de Console naar de nieuw aangemaakte folder.
>**Tip!** Het commando's dat je hiervoor nodig hebt, is **geen** git commando.

- [x] Voor we wijzigingen gaan aanbrengen in onze lokale repo, willen we deze eerst al koppelen aan de remote op GitHub.
      Gebruik hiervoor het gepaste git commando.

- [x] Zorg er nu eerst en vooral voor dat je de actuele inhoud van de remote repo binnentrekt in je lokale repo, met het gepaste git commando.
      In de GitHub repo die je van ons kreeg, staan immers al enkele bestanden die je lokaal nog niet hebt.

>**Tip!** Het comando dat je hier nodig hebt, synchroniseert de commit geschiedenis van de **remote** repo naar de **lokale** repo.

>**Tip!** Indien je hier foutmeldingen of andere errors tegenkomt dan is er iets foutgelopen in je lokale repository.
          Verwijder de folder waar je aan de slag bent en start even opnieuw, dat is de makkelijkste manier.

- [x] Maak via een passend console commando (of via de Windows verkenner) een nieuw bestand aan. Geef je bestand de naam **labo1.md**.
>**Tip!** Het commando's dat je hiervoor nodig hebt, is **geen** git commando.

- [x] Vul je naam en voornaam in in de file **labo1.md** met een teksteditor naar keuze. Sla je aanpassingen op.

- [x] Maak gebruik van passende git commando's om het aangemaakte bestand toe te voegen aan het versiebeheer van git. 
>**Tip!** Indien je twijfelt aan de syntax, raadpleeg dan je cursus. Je hebt twee commando's nodig.

- [x] Maak een screenshot waarop de uitgevoerde commando's uit de vorige stap, en hun parameters, zichtbaar zijn.
     Geef deze de naam **deel2** (extensie naar keuze) en bewaar de screenshot ergens **buiten de repo**, je hebt ze straks weer nodig.
     
---
### **Deel 3: Syncen naar de remote repo**

- [x] Lokaal heb je een commit staan (uit deel 2) die nog niet naar de remote werd doorgestuurd.
      Gebruik nu het gepaste git commando om deze commit naar de remote te sturen.
>**Tip!** Het commando dat je zoekt, synchroniseert de commit geschiedenis van de **lokale** repo naar de **remote** repo.

- [X] Plaats nu de twee screenshots die je maakte (in deel 1 en deel 2) in de **Screenshots** map van je lokale repo.
- [X] Gebruik het gepaste git commando om een statusoverzicht te krijgen van de bestanden in je lokale repo.
      Maak opnieuw een screenshot van het uitgevoerde commando samen met het resultaat.
      Plaats deze meteen in de **Screenshots** map onder de naam **deel3A** (met extensie naar keuze).

- [x] Maak één nieuwe commit die de drie screenshots tegelijk toevoegt aan het versiebeheer.
>**Tip!** Hiervoor heb je dezelfde commando's nodig die je al gebruikte in deel 2 om het bestand **labo1.md** op te nemen in het versiebeheer.

- [x] Synchroniseer een tweede keer de lokale commit geschiedenis naar de remote repo.
- [x] Gebruik een gepast git commando om de lokale geschiedenis te tonen (een overzicht van alle lokale commits).
- [x] Maak hiervan een screenshot (commando & resultaat) met de naam **deel3B** (extensie naar keuze) en plaats deze in de **Screenshots** map.
- [x] Commit deze vierde screenshot in je lokale repo en sync nog eens naar de remote.
- [x] Controleer of je vier screenshots nu allen zichtbaar zijn in de map **Screenshots** op GitHub.

---
#### **Afwerken van het labo**
- [x] Na het voltooien van alle taken editeer je deze **README.md** file (lokaal, in een editor naar keuze)
  en plaats je alle taken op voltooid door de markup te wijzigen van [ ] naar [x]. 
- [x] Commit deze wijziging in je lokale repo.
- [x] Synchroniseer een laatste keer de lokale geschiedenis naar de remote repo op GitHub.

>**Tip!** Je kan hier gerust VS Code gaan gebruiken. Deze heeft ook een preview mode om met markdown aan de slag te gaan.

>**Tip!** Controleer **op GitHub** nog even of je aangepaste opmaak ook wel degelijk goed verwerkt werd!
          Het vinkje wordt pas zichtbaar als er geen spaties rondom staan!
          Indien het niet gelukt is, kan je het bestand **README.md** nogmaals aanpassen en de wijzigingen nogmaals naar de remote sturen.
