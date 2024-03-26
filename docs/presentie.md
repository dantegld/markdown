---
marp: true
theme: uncover
class: invert
header: '![width:100px](img/footer.png)'
footer: 'Dante Gallardo Ledon'
---

# **SMTP**
## Simple Mail Transfer Protocol


---
<style scoped>
    h1 {
       background-color:#202228;
       border-radius:10px;
        margin-left: auto;
        margin-right: auto;
        padding-left: 50px;
        padding-right: 50px;
        padding-top:5px;
        padding-bottom:5px;
    }

</style>
# Gebruik

![bg](img/SMTP-image-1024x682.jpg)

---
### Gebruik
![bg left](img/SMTP-image-1024x682.jpg)

- Verzenden van e-mails tussen servers
- Configureer je e-mailapplicatie met de SMTP-serverinstellingen
  
- Gebruik SMTP-commando's zoals MAIL FROM en DATA om e-mailberichten te verzenden.

---

# SMTP Werking

![bg](img/smtp-working.jpg)

---

### SMTP Werking

- SMTP werkt op basis van een client-server model.
- De client (afzender) maakt verbinding met de SMTP-server van de ontvanger.
- De client stuurt het e-mailbericht naar de server.
- De server controleert de ontvanger en stuurt het bericht door naar de juiste bestemming.

---

### SMTP Beveiliging

- SMTP kan beveiligd worden met behulp van SSL/TLS.
- Dit zorgt voor versleuteling van de communicatie tussen de client en server.
- Hierdoor worden gegevens zoals wachtwoorden en e-mailinhoud beschermd tegen afluisteren.

---

### SMTP Alternatieven

- Naast SMTP zijn er ook alternatieve protocollen zoals POP3 en IMAP.
- Deze protocollen worden gebruikt voor het ophalen van e-mails van een server.
- POP3 is een oudere en eenvoudigere variant, terwijl IMAP meer functionaliteit biedt.

---

### SMTP Samenvatting

- SMTP is het protocol voor het verzenden van e-mails tussen servers.
- Het werkt op basis van een client-server model.
- SMTP kan beveiligd worden met SSL/TLS.
- Er zijn ook alternatieve protocollen zoals POP3 en IMAP.


