# SMTP

| Content    | 
| -------- | 
| [Defenitie](#Defenitie)  |
| [Veiligheid](#Veiligheid) |
| [Gebruik](#Gebruik) |
| [Verschil](#Verschil)    |
|[Bronnen](SMPT1.md)|
|[Presentatie](presentie.html)


#### SMPT : Simple Mail Transfer Protocol

### Defenitie

**SMTP** is een protocol dat gebrikt word voor het sturen en ontvangen van emails. Het wordt gebruikt door: Gmail, Outlook, Apple Mail en Yahoo Mail.

>Als **SMTP** niet zou bestaan, zou het emailsysteem ernstig verstoord worden. SMTP is het protocol dat verantwoordelijk is voor het verzenden en ontvangen van e-mails via internet. Zonder dit protocol zouden e-mails dus niet opq dezelfde manier kunnen worden verzonden of ontvangen.

### Veiligheid

**SMTP** speelt een grote rol in de veiligheid van het internet.
BV: SMTP heeft ingebouwde mechanismen voor het detecteren en filteren van spam-e-mails. Dit helpt voorkomen dat ongewenste en mogelijk kwaadaardige e-mails de inbox van gebruikers bereiken. 

- Spamfiltering: SMTP heeft ingebouwde mechanismen voor het detecteren en filteren van spam-e-mails. Deze mechanismen helpen voorkomen dat ongewenste en potentieel kwaadaardige e-mails de inbox van gebruikers bereiken. Door spam te identificeren en te blokkeren helpt SMTP de integriteit en veiligheid van e-mailcommunicatie te behouden.

- Authenticatie en autorisatie: SMTP ondersteunt authenticatie- en autorisatiemechanismen om de identiteit van de afzender te verifiëren en ervoor te zorgen dat alleen geautoriseerde gebruikers e-mails kunnen verzenden. Dit helpt ongeautoriseerde toegang en misbruik van e-maildiensten te voorkomen.

- Encryptie: SMTP ondersteunt encryptieprotocollen zoals Transport Layer Security (TLS) om de verzending van e-mails via internet te beveiligen. Door de communicatie tussen e-mailservers te versleutelen, helpt SMTP de vertrouwelijkheid en integriteit van e-mailinhoud te beschermen, waardoor ongeoorloofde onderschepping of manipulatie wordt voorkomen.

- Betrouwbaarheid en foutafhandeling: SMTP omvat foutafhandelingsmechanismen om een ​​betrouwbare e-mailbezorging te garanderen. Het geeft feedback over de bezorgstatus, zodat     afzenders op de hoogte kunnen worden gesteld van eventuele problemen die zich voordoen tijdens het e-mailverzendingsproces. Dit helpt bij het identificeren en oplossen van potentiële problemen, waardoor de algehele betrouwbaarheid van e-mailcommunicatie wordt verbeterd.

### Gebruik

Om **SMTP** te gebruiken, moet je de SMTP-serverinstellingen configureren in je e-mailclient of -toepassing. Deze instellingen omvatten het adres van de SMTP-server, de poort, het type beveiliging (indien van toepassing), de gebruikersnaam en het wachtwoord.

Hier is een voorbeeld van SMTP-serverinstellingen voor Gmail:

- SMTP-server: smtp.gmail.com
- Poort: 587 (of 465 voor SSL/TLS)
- Beveiliging: STARTTLS (of SSL/TLS)
- Gebruikersnaam: jouw Gmail-e-mailadres
- Wachtwoord: jouw Gmail-wachtwoord

Zodra de SMTP-serverinstellingen zijn geconfigureerd, kun je e-mails verzenden via de SMTP-server van je e-mailprovider. Dit kan worden gedaan met behulp van een e-mailclient zoals Microsoft Outlook, Apple Mail of Thunderbird, of via een programmeertaal zoals Python met behulp van een SMTP-bibliotheek.

Hier is een voorbeeld van het verzenden van een e-mail met behulp van Python en de `smtplib`-bibliotheek:



### Verschil

>**SMTP** wordt gebruikt voor het verzenden van e-mails, IMAP wordt gebruikt voor toegang tot e-mails op de server vanaf meerdere apparaten en POP3 wordt gebruikt voor het downloaden van e-mails van de server naar een apparaat.

![SMTP Diagram](img/smtp-protocol.png)

