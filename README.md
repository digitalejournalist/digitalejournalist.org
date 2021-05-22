# Over digitalejournalist.org
## Wat is digitalejournalist.org
Digitalejournalist.org vormt een verzamelplaats met best practices en verzameltools die privacybewuste alternatieven vormen voor gangbare tools. Denk bijvoorbeeld aan een beveiligde mailomgeving, veilige tekstverwerker, geëncrypteerde communicatietools en meer. Deze website wordt onderhouden door een [open community (Github)](https://github.com/yetimedia/digitalejournalist.org) en heeft als doel om ook minder technisch onderlegde mensen (voornamelijk journalisten) de tools aan te reiken om privacybewust te werk te gaan. 

## Wie zit er achter digitalejournalist.org
Deze website werd gestart door de Vlaamse technologie- en gaming journalist [Thibault Seynaeve](https://belgiangaming.org/wiki/Thibault_Seynaeve) in een poging om ook minder technisch onderlegde journalisten de tools en informatie aan te reiken om privacybewust hun job uit te oefenen. Toch vond hij het belangrijk dat er niet één persoon achter de site zit, maar dat iedereen die dit wil kan bijdragen aan de site. Iedereen wordt dan ook aangemoedigd om de inhoud op deze website in vraag te blijven stellen, te verbeteren en up-to-date te houden. Daarom is deze website volledig open source te vinden op Github. 

## Selectieproces tools 
Bij de keuze van de tools die we aanraden, baseren we ons in eerste instantie op het onderzoek en de community van [Privacytools.io](https://privacytools.io). Verder moedigen we iedereen aan om deze tools met een kritisch oog te blijven bekijken en eventuele zorgen of pijnpunten te melden via een [Github Issue](https://github.com/yetimedia/digitalejournalist.org/issues).

## Beleid
Een pagina die zich richt tot privacy, moet natuurlijk zelf het goede voorbeeld geven. Dat is waarom we deze pagina publieklijk hosten via Github Pages. De volledige broncode is openbaar te raadplegen via [open community (Github)](https://github.com/yetimedia/digitalejournalist.org). Ook gebruiken we bij onze links naar externe instanties geen affiliate links. Op die manier kunnen we onze onafhankelijkheid demonstreren. De tools die hier worden opgelijst, werden zorgvuldig uitgekozen zonder enige vorm van winstbelang. Ook verzamelen we geen analytics op deze pagina en worden er geen advertenties getoond. 

---

# Waarom privacy belangrijk is 
Privacy is belangrijk voor elke computergebruiker, maar voor journalisten is een doordacht gebruik van digitale middelen al helemaal onontbeerlijk. Je werkt met gevoelige gegevens, hebt bronnen te beschermen en bovendien wil je ongestoord onderzoek kunnen doen zonder het gevoel te hebben dat er iemand meegluurt. 

Toch wordt er maar weinig aandacht geschonken aan (digitale) privacy, omdat gebruikers zich er vaak niet van bewust zijn wie meegluurt (of wie kán meegluren). Bovendien gaan gebruiksgemak en privacy vaak niet hand in hand. Privacybewust te werk gaan betekent ook dat je er vrede mee neemt dat je soms wat omslachtiger te werk gaat (extra wachtwoorden, extra stappen om ergens in te loggen, bepaalde geliefkoosde applicaties laten vallen ten faveure van een privacybewust alternatief, etc.) Het ene sluit echter niet altijd het andere uit. Je hoeft niet élke tool op deze site te gebruiken. Privacybewust leven is geen eenmalige taak, maar een levensstijl. Neem kleine stapjes om jouw digitale privacy steeds te verbeteren. 

---

# Best practices 
* Gebruik voor elk account een afzonderlijk willekeurig gegenereerd wachtwoord (een password manager helpt je hierbij). 
* ...

---

# De digitale toolbox van de privacybewuste journalist 

**Inhoudstafel**
- [Two Factor Authentication](#2fa)
- [Hardware Authenticator](#hardware-authenticator)
- [Browser](#browser)
- [Zoekmachine](#zoekmachine)
- [VPN (Virtual Private Network)](#vpn)
- [Mail](#mail)
- [Instant Messaging (IM)](#im)
- [Notitieboek)](#notitieboek)
- [Password Manager)](#passwordmanager)
- [Bestanden versleutelen)](#bestanden-versleutelen)
- [Tekstverwerking & Office-alternatief)](#office)
- [Bestandssynchronisatie en File Storage (Dropbox-alternatief](#bestandssynchronisatie)
- [Blogging](#blogging)

<a name="2fa"></a>
## Two Factor Authentication
Yubikey, Bitwarden TOTP, Aegis(?)

<a name="hardware-authenticator"></a>
## Hardware Authenticator
Waarom is het beter dan een software authenticator 
Yubikey? 

<a name="browser"></a>
## Browser
Waarom is je browser belangrijk... 
- Firefox (mits enige add-ons en tools) 
- Tor

<a name="zoekmachine"></a>
## Zoekmachine
Waarom is Google niet goed...
- DuckDuckGo 

<a name="vpn"></a>
## VPN (Virtual Private Network)
Wat is het, waarom is het belangrijk, wanneer gebruik je het 
- ProtonVPN

<a name="mail"></a>
## Mail

Wanneer je via mail contact hebt met je bronnen, is het belangrijk om erbij stil te staan of er niemand anders is die jullie conversaties kan meelezen. Door te kiezen voor een e-mail provider die mails encrypteert, weet je zeker dat niemand anders kan meelezen. Ook voor je bron is het soms belangrijk om volledig anoniem te kunnen blijven. Dat kan niet wanneer je een Microsoft of Google-account gebruikt om mails uit te sturen. 

### Let op je headers
Het is belangrijk om te weten dat niet elk deel van je mail geëncrypteerd kan worden. Bij ProtonMail wordt bijvoorbeeld de body text wel geëncrypteerd (dus de effectieve inhoud van je mail), maar de onderwerpregel niet. Houd het onderwerp van de mail dus vrij algemeen en houd gevoelige gegevens voor de inhoud van de mail. 

### ProtonMail 

[Officiële website](https://protonmail.com)

Binnen het privacylandschap is ProtonMail ongetwijfeld de populairste provider van een beveiligde mailomgeving. Het gaat om een product van Proton Technologies, dat onder andere ook de gerenommeerde VPN-dienst ProtonVPN aanbiedt. Enkele feiten: 

* Gevestigd in Zwitserland (onder een strenge privacywetgeving)
* Gratis pakket met 500MB opslag
* Betalende pakketten bieden meer opslag, de mogelijkheid om een eigen domein te gebruiken, ondersteuning voor third-party e-mail clients (zoals Thunderbird)
* Zero access encryption: mails, contacten en kalenders kunnen enkel door jou worden bekeken. ProtonMail kan op geen enkele manier jouw mails lezen. 
* Geen persoonlijke informatie vereist om een (anoniem) account te maken. Er worden geen IP logs bewaard.
* Open source broncode

Enkel ProtonMail gebruiken als e-mailclient is echter **niet voldoende**. Ook al is jouw mailbox geëncrypteerd, daar ben je niets mee wanneer je een mail met gevoelige informatie stuurt naar een ontvanger die een mail provider zoals Outlook (Microsoft) of Gmail (Google) gebruikt. Enkel wanneer de ene ProtonMail-gebruiker naar een andere ProtonMail-gebruiker mailt, kan je erop vertrouwen dat de hele conversatie veilig verloopt. Bij het opstellen van een mail wordt aangegeven of deze persoon beschikt over ProtonMail. Wil je een mail sturen naar iemand die geen ProtonMail gebruikt, dan kan je dit bericht alsnog encrypteren. De ontvanger zal een link ontvangen waarmee hij/zij de mail kan lezen binnen de veilige omgeving van ProtonMail. 

![Protonmail screenshot](https://raw.githubusercontent.com/yetimedia/digitalejournalist.org/main/images/protonmail.jpg)


<a name="im"></a>
## Instant Messaging
Waarom geen WhatsApp, Telegram, Facebook messenger, etc.
- Signal

<a name="notitieboek"></a>
## Digitaal notitieboek
Waarom geen Evernote, Apple Notes, OneNote ... 
- StandardNotes

<a name="passwordmanager"></a>
## Password Manager
Het is belangrijk om voor elk account een sterk uniek wachtwoord te hebben. Al die honderden wachtwoorden onthouden is echter onmogelijk, maar een wachtwoordmanager biedt hulp. In deze virtuele kluis bewaar je al jouw wachtwoorden. Meer zelfs, de tool helpt je erbij om voor elk account een enorm sterk en uniek wachtwoord te genereren. 
- Bitwarden

<a name="bestanden-versleutelen"></a>
## Bestanden versleutelen
Perfect te gebruike in combinatie met cloud storage

<a name="office"></a>
## Tekstverwerking en Office-alternatief

- Cryptpad

<a name="bestandssynchronisatie"></a>
## Bestandssynchronisatie en File Storage (Dropbox-alternatief)
Maakt in feite niet veel uit welke service je gebruikt zolang je al je bestanden versleutelt alvorens ze naar de cloud te sturen. 

<a name="blogging"></a>
## Blogging

- Write.as

