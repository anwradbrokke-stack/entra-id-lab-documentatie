# entra-id-lab-documentatie
Lab Entra ID Access


# Lab: Set Up a Small Company's Identity and Access
 
Hoi! Ik ben begonnen in de IT en wil graag aan de slag in de IT. In deze repository staat de documentatie van mijn Microsoft Entra ID lab.
 
📄 **Documentatie:** [Lab_Documentatie_Identity_and_Access.pdf](Lab_Documentatie_Identity_and_Access.pdf)
 
## Scenario
 
Ik ben de nieuwe IT-beheerder van het bedrijf Contoso Lab, dit is een 10-mansbedrijf. Mijn focus is helpdesk en ICT support skills.
 
**Tools:** Free trial Azure account en Microsoft Entra Admin Center.
 
## Wat heb ik gedaan?
 
- Mijn tenant en primary domain opgezocht in het Entra admin center
- Security defaults aangezet
- 6 users aangemaakt met functie en afdeling (Anna Sales, Ben Sales, Carla HR, Dave IT, Eva Finance, Tom Intern)
- 3 security groups aangemaakt (Sales, HR, IT-Admins) en de juiste users erbij gezet
- Een password reset gedaan en ingelogd als user, met MFA via de Authenticator
- Tom Intern geblokkeerd voor sign-in (offboarding simulatie)
- Eva Finance verwijderd en weer hersteld via Deleted users
- Dave IT de User Administrator-rol gegeven, niet Global Admin, en getest wat hij wel en niet kan
- Een Enterprise application (Test App) aangemaakt en aan users toegewezen
Alle stappen staan met screenshots in de PDF.
 
## Support ticket scenario's
 
Ik heb ook 7 tickets uitgewerkt. Per ticket schrijf ik op: het incident, wat ik heb nagekeken, de oorzaak, de oplossing en de bevestiging van de oplossing.
 
1. Wachtwoord vergeten
2. Sales App kan niet geopend worden
3. Account geblokkeerd (Conditional Access en locatie)
4. Onboarding van een nieuwe medewerker
5. Offboarding van een medewerker
6. Waarom wordt er om extra verificatie (MFA) gevraagd?
7. Internet doet het niet (een echt probleem bij mij thuis, met de Wifi-adapter van een laptop)
## Wat heb ik geleerd?
 
- Het verschil tussen een user, een group en een rol
- Waarom niet iedereen zomaar Global Administrator-rechten mag krijgen
- Waar MFA bescherming tegen biedt, bijvoorbeeld phishing en gestolen wachtwoorden
- Hoe ik een password reset uitleg aan iemand met 0 kennis van IT
- Hoe ik de Sign-in logs en Audit logs gebruik om te kijken wat er is gebeurd en om te bevestigen dat mijn oplossing werkt
## Even eerlijk
 
- Conditional Access (ticket 3) heb ik niet volledig kunnen testen, omdat hiervoor een extra betaalde P1-licentie nodig is. Dit ticket heb ik zelf uitgewerkt.
- Ik kon de Test App niet aan een group toewijzen, omdat mijn plan dit niet toestaat. Aan users toewijzen kon wel.
- Ik heb af en toe hulp gehad van Claude AI en Google Gemini. Dit staat ook in de documentatie.
## Contact
 
Ik sta open voor een eerste baan in de IT. Wil je meer weten over mijn lab? Stuur me gerust een bericht.
 
<!-- Vul hier je naam en bijvoorbeeld je LinkedIn of e-mailadres in -->
 
