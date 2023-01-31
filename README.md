Verschillen Cypress vs Testcafe

***Installatie en draaien van een eerste basistest, waarbij alleen Wikipedia bezocht wordt***

Installatie
npm install cypress vs npm install testcafe
Cypress bevat 172 packages, kost 26 seconden om te auditen. Geen problemen.
Testcafe bevat 489 packages, kost 17 seconden om te auditen. 5 waarschuwingen over depracated packages.

Na het opstarten van Cypress geeft Cypress de mogelijkheid om via een UI tool in de browser de basis
klaar te zetten. Een voorbeeld test draait vrijwel direct.
Testcafe gaat moeizamer, een aantal pogingen nodig om een extreem simpele test te laten draaien. Anders dan Cypress legt Testcafe niet uit dat je nog 'npx' moet zetten voor het command 'testcafe chrome (testfile)'. Ook dat er nog --hostname localhost achter moet om het lokaal te kunen draaien wordt er niet bij gezet. 

Conclusie: installatie en draaien van de eerste test is gemakkelijker en gebruikersvriendelijker in Cypress. Cypress is up-to-date en maakt geen gebruik van deprecated packages. Cypress heeft een toegankelijke interface om te helpen met het opzetten van je tests. Voor Testcafe ben je afhankelijk van de website, die bovendien geen volledige informatie geeft.

***Bouwen van een test waarbij het vogelbekdier wordt opgezocht op de Engelse wikipedia***

Bouwen in Cypress gaat redelijk, de shoulds zijn niet altijd even intuitief. Na het draaien blijft
Cypress het einde van je test in beeld houden. Alle losse stappen kunnen teruggekeken worden en dan kun je precies zien wat op dat moment de staat van het testobject was. Wel duurt het wat langer om Cypress op te starten. Eigenlijk moet je dit tussendoor ook niet afsluiten, maar tijdens het bouwen van je tests open laten staan. Bij wijzigingen zal hij dan opnieuw je suite gaan draaien.

