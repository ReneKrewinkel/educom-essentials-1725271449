# Bestandsformaten - taak 7


## Markdown
Markdown is een eenvoudige opmaaktaal om een leesbare structuur aan te brengen in tekst.
Het wordt gebruikt voor de README bestanden in de Github Repositories. 

Markdown is leesbaar voor allerlei systemen en applicaties, en bepaalt alleen de hierarchie van de tekst. Hoe de vormgeving van de opmaak eruit komt te zien ligt aan de applicatie waarmee het markdown bestand geopend wordt, in tegenstellig tot volledig opgemaakt tekst uit bijvoorbeeld een Word bestand. 

Het vormt de basis voor webteksten, zoals blogs, forums, e-mails enz. 

## JSON
JSON, JavaScript Object Notation, is bedoeld voor communucatie tussen servers en webapplicaties. Het gebruikt tekst om data-objecten te creeëren. Deze bestaan uit attributen waar waardes aan toegewezen worden. 

Zo kan data gegroepeerd worden opgeslagen en overgedragen.

Dit kan gebruikt worden om bijvoorbeeld informatie in gebruikers accounts op te slaan. Iedere gebruiker zou dan als data-object beschreven worden, bestaande uit bijpassende attributen zoals naam, email, telefoonnummer etc. 

Andere toepassingen zouden bijvoorbeeld klantgegevens of productinfomatie kunnen zijn.

## XML
XML, eXtendend Markup Language, is een afgeleide van Standard Generalized Markup Language (SGML).
Beiden worden gebruikt om de structuur van documenten vast te leggen. 

HTML is ook afgeleid van SGML, maar kan alleen tekstuele structuur aangeven. XML kan zowel tekstuele structuur als semantische structuur aangeven. Met semantische structuur wordt betekenis gegeven aan informatie. Hiermee kan webtekst bijvoorbeeld gedefineerd worden als bijv. header, footer of body. Ook kan het soort informatie aangegeven worden, bijvoorbeeld of iets een datum of telefoonnummer is. 

Net als JSON wordt het gebruikt om data op te slaan en over te dragen tussen servers en webapplicaties. 
Het lijkt erop dat JSON meer focust op de inhoudelijke data, en XML meer gebruikt wordt voor het semantisch benoemen en organiseren van de verschillende data typen. 

Het kan bijvoorbeeld gebruikt worden om ervoor te zorgen dat data in verschillende applicaties op de correcte manier wordt weergegeven. Bijvoorbeeld datums die in verschillende apps op verschillende manieren geformatteerd worden. 

## CSV
CSV, Charachter Seperated Values, wordt gebruikt voor gestructureerde data die in tabel vorm wordt opgeslagen. 

Data bestaat uit rijen waarin de kolommen worden gescheiden door middel van scheidingstekens,en iedere regel een record vertegenwoordigd. 

Dit format is bedoeld voor het overbrengen van datasets met behoud van de structuur. 

Zelf heb ik dit format ooit gebruikt voor een database van gescrapete tweets. De kolommen gaven de gebuikersnaam, tweet, datum, tijd, locatie, aantal retweets, aantal likes en aantal comments weer. Iedere regel omvatte één tweet. 

Dit csv bestand kon vervolgens gebruikt worden om met OpenRefine de data te cleanen, sorteren en filteren alvorens de data verder te verwerken. 

## SVG
Scalable Vector Graphics is bedoeld voor het vastleggen van de verhoudingen en afstanden van objecten tot andere objecten. Hiermee kan ervoor gezorgd worden dat ze scherper weergegeven kunnen worden maar minder ruimte in beslag nemen bij het runnen van de website. 

SVG bestanden zijn geschreven in XML. 

SVG format wordt gebruikt voor afbeeldingen en vectors, waarmee de visuele uitstraling van een app of website o.i.d. wordt gebouwd. Door SVG te gebruiken blijft de applicatie of website snel laadbaar, scherp en in kloppende verhoudingen weer te geven in verschillende schermen. 

## YAML 
YAML brengt net als JSON en XML data over op een geordende manier, en wordt vergeleken als een verkiesbaar alternatief voor JSON vanwege de leesbaarheid en begrijpelijkheid. 

YAML maakt namelijk meer gebruik van woorden en indentaties, en minder van leestekens. Dit in tegenstelling tot JSON of XML, die juist veel syntax gebruiken. 


## TOML 
Nog een alternatief is TOML, ook een configuratiebestand net als JSON, XML en YAML. 
Tom's Obvious Minimal Language (Ok, Tom...) is bedoeld om minimaal, overzichtelijk en ondubbelzinnig te zijn. Net als YAMl focust het op leesbaarheid.

TOML heeft als voordeel dat het makkelijk tabellen met data uiteen kan zetten en zo in veel verschillende talen data structuren kan aangeven.  



