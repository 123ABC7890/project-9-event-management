# Evenementbeheersysteem

## Projectoverzicht
Dit Laravel-project biedt een Evenementbeheersysteem met drie bestaande modellen: Evenement, Locatie en het standaard Laravel Gebruikersmodel. Het systeem is ontworpen om Laravel-vaardigheden te tonen in CRUD-operaties, relaties, validatie, routing en middleware.

## Kernfuncties

### 1. Kaartverkoop
#### Evenementorganisator
- Verschillende kaartsoorten maken met variërende prijzen
- Limieten voor kaartkwantiteit en verkoopperiodes instellen
- Promotiecodes en kortingen aanbieden
- Kaartverkoop en beschikbaarheid bijhouden

#### Deelnemer
- Beschikbare kaartsoorten voor evenementen bekijken
- Meerdere kaarten selecteren en kopen
- Promotiecodes toepassen voor kortingen
- Kaarten ontvangen via e-mail of mobiele app

### 2. Evenementregistratie
#### Deelnemer
- Registratieformulieren invullen met persoonlijke informatie
- Meerdere deelnemers tegelijk registreren
- Evenementvoorkeuren selecteren (workshops, maaltijdopties)
- Registratiebevestiging ontvangen

#### Evenementorganisator
- Lijst van alle geregistreerde deelnemers bekijken
- Registratieverzoeken goedkeuren of afwijzen
- Deelnemersgegevens exporteren voor rapportage
- Berichten sturen naar geregistreerde deelnemers

### 3. Sprekerbeheer
#### Evenementplanner
- Sprekersprofielen maken met bio's en foto's
- Sprekers toewijzen aan specifieke sessies
- Vereisten en accommodaties voor sprekers bijhouden
- Sprekersschema's en verplichtingen beheren

#### Spreker
- Profielinformatie en beschikbaarheid bijwerken
- Toegewezen sessies en schema bekijken
- Presentatiemateriaal uploaden
- Technische en logistieke vereisten communiceren

### 4. Agenda-opbouw
#### Evenementorganisator
- Evenementagenda's maken en beheren zodat deelnemers het schema kunnen zien.
- Ik kan meerdere sessies maken met tijden en locaties
- Ik kan sessies organiseren in tracks of categorieën
- Ik kan de agenda bijwerken als er wijzigingen optreden
- Ik kan de agenda publiceren voor deelnemers

#### Deelnemer
- De evenementagenda bekijken en personaliseren zodat ik mijn deelname kan plannen.
- Ik kan het volledige evenementschema bekijken
- Ik kan sessies filteren op tijd, track of spreker
- Ik kan mijn persoonlijke agenda maken van geselecteerde sessies
- Ik kan meldingen ontvangen over schemawijzigingen

### 5. Locatiebeheer
#### Evenementplanner
- Locaties en zalen beheren zodat ik de evenementruimte kan organiseren.
- Ik kan locatie-indelingen maken met meerdere zalen
- Ik kan zaalcapaciteiten en beschikbare apparatuur specificeren
- Ik kan sessies toewijzen aan geschikte zalen
- Ik kan locatiespecifieke logistiek en vereisten beheren

#### Locatiecoördinator
- Locatiegebruik bijhouden zodat ik de juiste opstelling en middelen kan garanderen.
- Ik kan alle geplande evenementen op mijn locatie bekijken
- Ik kan zaalopstellingen en configuraties beheren
- Ik kan vereisten coördineren met evenementorganisatoren
- Ik kan locatieproblemen of onderhoudsbehoefte melden

### 6. Exposantenbeheer
#### Evenementorganisator
- Exposanten beheren zodat ik het tentoonstellingsgebied kan organiseren.
- Ik kan exposantenprofielen en standplaatsen toewijzen
- Ik kan betalingen en contractstatus van exposanten bijhouden
- Ik kan specifieke vereisten communiceren naar exposanten
- Ik kan exposantenrapporten en plattegronden genereren

#### Exposant
- Mijn stand en deelname beheren zodat ik mijn producten of diensten effectief kan presenteren.
- Ik kan mijn bedrijfsprofiel bekijken en bijwerken
- Ik kan mijn standlocatie selecteren uit beschikbare opties
- Ik kan vereiste materialen en informatie indienen
- Ik kan aanvullende diensten of apparatuur bestellen

### 7. Deelnemersnetwerken
#### Deelnemer
- Netwerken met andere deelnemers zodat ik waardevolle connecties kan maken.
- Ik kan mijn deelnemersprofiel maken en aanpassen
- Ik kan zoeken naar andere deelnemers met vergelijkbare interesses
- Ik kan verbindingsverzoeken en berichten sturen
- Ik kan afspraken plannen met andere deelnemers

#### Evenementorganisator
- Deelnemersnetwerken faciliteren zodat ik de waarde van mijn evenement kan vergroten.
- Ik kan netwerkfuncties in- of uitschakelen
- Ik kan netwerksessies en ijsbrekers creëren
- Ik kan verbindingen suggereren op basis van interesses of rollen
- Ik kan netwerkactiviteit monitoren voor engagementstatistieken

### 8. Incheckbeheer
#### Evenementmedewerker
- Deelnemers inchecken zodat ik aanwezigheid kan bijhouden en toegang kan verlenen.
- Ik kan tickets of badges scannen om deelnemers in te checken
- Ik kan handmatig zoeken en deelnemers inchecken
- Ik kan registraties ter plaatse afhandelen
- Ik kan real-time incheckstatistieken bekijken

#### Deelnemer
- Efficiënt inchecken bij evenementen zodat ik snel kan beginnen met deelnemen.
- Ik kan inchecken met een mobiele app of QR-code
- Ik kan mijn badge of materialen ontvangen bij het inchecken
- Ik kan mijn incheckstatus voor verschillende sessies bekijken
- Ik kan hulp krijgen bij incheckproblemen

### 9. Sponsorbeheer
#### Evenementorganisator
- Sponsors beheren zodat ik financiële ondersteuners kan verzekeren en erkennen.
- Ik kan sponsorpakketten maken met verschillende voordelen
- Ik kan sponsortoezeggingen en betalingen bijhouden
- Ik kan sponsorlogo's en erkenning beheren
- Ik kan sponsorrapporten en ROI-statistieken genereren

#### Sponsor
- Mijn sponsordetails beheren zodat ik mijn zichtbaarheid en voordelen kan maximaliseren.
- Ik kan sponsorpakketten selecteren en aanschaffen
- Ik kan mijn bedrijfslogo en materialen uploaden
- Ik kan mijn sponsorvoordelen en resultaten bijhouden
- Ik kan toegang krijgen tot deelnemersgegevens volgens mijn pakket

### 10. Enquête en Feedback
#### Evenementorganisator
- Feedback verzamelen zodat ik mijn evenementen kan evalueren en verbeteren.
- Ik kan aangepaste enquêtes maken voor verschillende aspecten van het evenement
- Ik kan geautomatiseerde enquêtedistributie plannen
- Ik kan enquêteresultaten en feedback analyseren
- Ik kan rapporten genereren over deelnemerstevredenheid

#### Deelnemer
- Feedback geven zodat ik mijn ervaring en suggesties kan delen.
- Ik kan evenementenquêtes gemakkelijk invullen
- Ik kan individuele sessies en sprekers beoordelen
- Ik kan specifieke opmerkingen en suggesties geven
- Ik kan zien hoe mijn feedback bijdraagt aan verbeteringen

### 11. Budgetbeheer
#### Evenementplanner
- Evenementbudgetten beheren zodat ik uitgaven en inkomsten kan bijhouden.
- Ik kan gedetailleerde budgetcategorieën en items maken
- Ik kan werkelijke uitgaven vergelijken met gebudgetteerde bedragen
- Ik kan inkomsten uit kaartverkoop en sponsoring monitoren
- Ik kan financiële rapporten en prognoses genereren

#### Financieel Beheerder
- Evenementfinanciën beoordelen zodat ik fiscale verantwoordelijkheid kan garanderen.
- Ik kan uitgaven en budgetwijzigingen goedkeuren
- Ik kan betalingen en openstaande facturen bijhouden
- Ik kan evenementinkomsten en -uitgaven afstemmen
- Ik kan winst- en verliesrekeningen genereren

### 12. Evenementmarketing
#### Marketingmanager
- Evenementen promoten zodat ik deelnemers en sponsors kan aantrekken.
- Ik kan marketingcampagnes maken voor verschillende kanalen
- Ik kan campagneprestaties en conversies bijhouden
- Ik kan promotionele inhoud en materialen beheren
- Ik kan integreren met sociale mediaplatforms

#### Evenementorganisator
- Promotionele tools gebruiken zodat ik de aanwezigheid en zichtbaarheid kan vergroten.
- Ik kan deelbare evenementpagina's en registratielinks maken
- Ik kan verwijzingsprogramma's en stimulansen aanbieden
- Ik kan gerichte promotie-e-mails versturen
- Ik kan marketingeffectiviteit en ROI bijhouden

### 13. Inhoudsbeheer
#### Evenementcoördinator
- Evenementinhoud beheren zodat deelnemers toegang hebben tot informatie en materialen.
- Ik kan presentaties, video's en documenten uploaden
- Ik kan inhoud organiseren per sessie of onderwerp
- Ik kan toegang tot verschillende inhoudstypen beheren
- Ik kan inhoudsdownloads en -gebruik bijhouden

#### Deelnemer
- Toegang krijgen tot evenementinhoud zodat ik het meeste uit mijn deelname kan halen.
- Ik kan evenementmaterialen doorzoeken en bekijken
- Ik kan presentaties downloaden van sessies die ik heb bijgewoond
- Ik kan inhoud bladwijzeren voor latere raadpleging
- Ik kan feedback geven over inhoudskwaliteit

### 14. Mobiele App-integratie
#### Evenementorganisator
- Een mobiele app aanbieden zodat deelnemers toegang hebben tot evenementinformatie op hun apparaten.
- Ik kan de app aanpassen met merkidentiteit en inhoud
- Ik kan pushberichten sturen naar app-gebruikers
- Ik kan evenementinformatie in real-time bijwerken
- Ik kan app-gebruik en betrokkenheid bijhouden

#### Deelnemer
- Een mobiele app gebruiken zodat ik het evenement gemakkelijk kan navigeren.
- Ik kan het evenementschema bekijken en mijn agenda maken
- Ik kan locatiekaarten bekijken en sessies vinden
- Ik kan netwerken met andere deelnemers via de app
- Ik kan belangrijke updates en meldingen ontvangen

### 15. Virtueel Evenementplatform
#### Evenementproducent
- Virtuele evenementcomponenten beheren zodat externe deelnemers kunnen deelnemen.
- Ik kan livestreams opzetten voor sessies
- Ik kan virtuele netwerkruimtes creëren
- Ik kan online Q&A en polls beheren
- Ik kan technische ondersteuning bieden voor virtuele deelnemers

#### Virtuele Deelnemer
- Op afstand deelnemen zodat ik het evenement kan ervaren zonder fysiek aanwezig te zijn.
- Ik kan deelnemen aan live sessies en opnames bekijken
- Ik kan deelnemen aan Q&A en discussies
- Ik kan virtueel netwerken met andere deelnemers
- Ik kan evenementinhoud en -materialen online raadplegen

### 16. Badge-generatie
#### Evenementcoördinator
- Deelnemersbadges genereren zodat ik officiële identificatie kan bieden.
- Ik kan badge-ontwerpen en -layouts aanpassen
- Ik kan variabele gegevens zoals naam, bedrijf en rol toevoegen
- Ik kan badges in batches of individueel genereren
- Ik kan verloren of beschadigde badges snel vervangen

#### Deelnemer
- Een professionele badge ontvangen zodat ik geïdentificeerd kan worden bij het evenement.
- Ik kan mijn vooraf afgedrukte badge ophalen bij het inchecken
- Ik kan ervoor zorgen dat mijn badge accurate informatie weergeeft
- Ik kan mijn badge gebruiken om toegang te krijgen tot geschikte ruimtes
- Ik kan correcties aanvragen als mijn badge-informatie onjuist is

### 17. Evenementanalyse
#### Evenementorganisator
- Evenementgegevens analyseren om succes te meten en verbeteringen aan te brengen.
- Ik kan dashboards bekijken met belangrijke prestatie-indicatoren
- Ik kan aanwezigheid en betrokkenheid bijhouden
- Ik kan deelnemersdemografie en -gedrag analyseren
- Ik kan gedetailleerde evenementrapporten genereren

#### Deelnemer
- Evenementprestaties evalueren om investeringsrendement te beoordelen.
- Ik kan hoogwaardige statistieken en aanwezigheidscijfers bekijken
- Ik kan resultaten vergelijken met vorige evenementen
- Ik kan gedetailleerde rapporten over specifieke aspecten bekijken
- Ik kan datavisualisaties en samenvattingen raadplegen

### 18. Personeelstoewijzing
#### Evenementmanager
- Personeel toewijzen aan evenementtaken zodat alle verantwoordelijkheden worden gedekt.
- Ik kan personeelsrollen en verantwoordelijkheden creëren
- Ik kan personeel toewijzen aan specifieke diensten en locaties
- Ik kan beschikbaarheid en kwalificaties van personeel bijhouden
- Ik kan toewijzingen en instructies communiceren

#### Evenementmedewerker
- Mijn toewijzingen bekijken zodat ik weet wanneer en waar ik moet werken.
- Ik kan mijn schema en verantwoordelijkheden bekijken
- Ik kan details ontvangen over mijn toegewezen taken
- Ik kan mijn uren en activiteiten registreren
- Ik kan wijzigingen in mijn toewijzingen aanvragen indien nodig

### 19. Middelenbeheer
#### Logistiek Coördinator
- Evenementmiddelen beheren zodat alle benodigde items beschikbaar zijn.
- Ik kan inventaris bijhouden van beschikbare apparatuur en benodigdheden
- Ik kan middelen toewijzen aan specifieke sessies of gebieden
- Ik kan gebruik en teruggave van middelen bijhouden
- Ik kan middelenconflicten of tekorten identificeren

#### Presentator of Exposant
- Middelen aanvragen zodat ik heb wat ik nodig heb voor mijn deelname.
- Ik kan beschikbare middelen bekijken die ik kan aanvragen
- Ik kan middelenaanvragen indienen met specifieke vereisten
- Ik kan de status van mijn middelenaanvragen bijhouden
- Ik kan problemen melden met geleverde middelen

### 20. Evenementcommunicatie
#### Evenementorganisator
- Communicatie versturen naar deelnemers om belangrijke informatie te delen.
- Ik kan e-mailsjablonen maken voor verschillende doeleinden
- Ik kan deelnemers segmenteren voor gerichte communicatie
- Ik kan geautomatiseerde berichten plannen op belangrijke momenten
- Ik kan berichtbezorging en openingspercentages bijhouden

#### Deelnemer
- Evenementcommunicatie ontvangen zodat ik op de hoogte blijf van belangrijke details.
- Ik kan vooraf informatie en instructies over het evenement ontvangen
- Ik kan real-time updates krijgen tijdens het evenement
- Ik kan mijn communicatievoorkeuren beheren
- Ik kan alle communicatie op één plek raadplegen

## ERD
```mermaid
erDiagram
    Event ||--o{ Ticket : "biedt"
    Event ||--o{ Session : "heeft"
    Event ||--o{ Survey : "heeft"
    Event ||--o{ Budget : "heeft"
    Event ||--o{ MarketingCampaign : "heeft"
    Event ||--o{ Resource : "gebruikt"
    Event ||--o{ EventStaff : "heeft toegewezen"
    Event }|--|{ Sponsor : "heeft"
    Event }|--|{ Exhibitor : "heeft"
    Venue ||--o{ Event : "host"
    Venue ||--o{ Room : "heeft"
    Room ||--o{ Session : "vindt plaats in"
    User ||--o{ Ticket : "koopt"
    User ||--o{ Registration : "maakt"
    User ||--o{ Feedback : "geeft"
    User ||--o{ Connection : "maakt"
    User ||--o{ BadgeInfo : "heeft"
    User ||--o{ PersonalAgenda : "heeft"
    User }|--|{ EventStaff : "kan zijn"
    Speaker ||--o{ Session : "presenteert"
    Registration ||--|| Badge : "genereert"
    Registration }|--|| Event : "voor"
    Session }|--|{ Track : "behoort tot"
    Session ||--o{ Content : "heeft"
    Session ||--o{ Feedback : "ontvangt"
    Session ||--o{ Attendance : "heeft"
    Session ||--o{ Resource : "gebruikt"
    Ticket ||--|| TicketType : "is van"
    Exhibitor ||--o{ Booth : "heeft"
    Exhibitor ||--o{ ExhibitorResource : "vraagt"
    Sponsor ||--|| SponsorPackage : "kiest"
    CheckIn }|--|| Registration : "voor"
    Content }|--|| ContentAccess : "heeft"
    Communication }|--|| User : "ontvangt"
    Communication }|--|| Event : "voor"

    Event {
        int id PK
        string name
        string description
        datetime start_date
        datetime end_date
        boolean is_virtual
        int venue_id FK
        int organizer_id FK
        string status
        datetime created_at
        datetime updated_at
    }

    Venue {
        int id PK
        string name
        string address
        string city
        string country
        int capacity
        datetime created_at
        datetime updated_at
    }

    Room {
        int id PK
        int venue_id FK
        string name
        int capacity
        string setup_type
        string equipment
        datetime created_at
        datetime updated_at
    }

    User {
        int id PK
        string name
        string email
        string password
        string role
        string company
        string title
        string bio
        string profile_image
        string preferences
        datetime created_at
        datetime updated_at
    }

    Speaker {
        int id PK
        int user_id FK
        string bio
        string photo
        string requirements
        string status
        datetime created_at
        datetime updated_at
    }

    Session {
        int id PK
        int event_id FK
        int room_id FK
        int speaker_id FK
        int track_id FK
        string title
        string description
        datetime start_time
        datetime end_time
        int capacity
        string status
        datetime created_at
        datetime updated_at
    }

    Track {
        int id PK
        int event_id FK
        string name
        string description
        string color
        datetime created_at
        datetime updated_at
    }

    Ticket {
        int id PK
        int event_id FK
        int user_id FK
        int ticket_type_id FK
        string status
        datetime purchase_date
        string reference_code
        datetime created_at
        datetime updated_at
    }

    TicketType {
        int id PK
        int event_id FK
        string name
        float price
        int quantity
        datetime sales_start
        datetime sales_end
        string description
        datetime created_at
        datetime updated_at
    }

    Registration {
        int id PK
        int user_id FK
        int event_id FK
        string status
        json preferences
        datetime registered_at
        datetime created_at
        datetime updated_at
    }

    Badge {
        int id PK
        int registration_id FK
        string badge_number
        boolean printed
        datetime created_at
        datetime updated_at
    }

    Exhibitor {
        int id PK
        int event_id FK
        string company_name
        string description
        string logo
        string contact_name
        string contact_email
        string status
        datetime created_at
        datetime updated_at
    }

    Booth {
        int id PK
        int exhibitor_id FK
        string location
        int size
        string status
        datetime created_at
        datetime updated_at
    }

    Sponsor {
        int id PK
        int event_id FK
        int sponsor_package_id FK
        string company_name
        string logo
        string website
        string status
        datetime created_at
        datetime updated_at
    }

    SponsorPackage {
        int id PK
        int event_id FK
        string name
        float price
        string benefits
        int available_spots
        datetime created_at
        datetime updated_at
    }

    Connection {
        int id PK
        int requester_id FK
        int receiver_id FK
        string status
        datetime created_at
        datetime updated_at
    }

    CheckIn {
        int id PK
        int registration_id FK
        int staff_id FK
        datetime check_in_time
        string method
        datetime created_at
        datetime updated_at
    }

    Survey {
        int id PK
        int event_id FK
        string title
        string description
        json questions
        datetime distribution_date
        datetime created_at
        datetime updated_at
    }

    Feedback {
        int id PK
        int user_id FK
        int session_id FK
        int rating
        string comments
        datetime created_at
        datetime updated_at
    }

    Budget {
        int id PK
        int event_id FK
        string category
        string item
        float budgeted_amount
        float actual_amount
        string status
        datetime created_at
        datetime updated_at
    }

    MarketingCampaign {
        int id PK
        int event_id FK
        string name
        string channel
        string content
        datetime start_date
        datetime end_date
        float cost
        json metrics
        datetime created_at
        datetime updated_at
    }

    Content {
        int id PK
        int session_id FK
        string title
        string file_type
        string file_path
        datetime created_at
        datetime updated_at
    }

    ContentAccess {
        int id PK
        int content_id FK
        string access_level
        datetime created_at
        datetime updated_at
    }

    PersonalAgenda {
        int id PK
        int user_id FK
        int session_id FK
        datetime created_at
        datetime updated_at
    }

    Attendance {
        int id PK
        int session_id FK
        int user_id FK
        boolean attended
        datetime check_in_time
        datetime created_at
        datetime updated_at
    }

    EventStaff {
        int id PK
        int event_id FK
        int user_id FK
        string role
        string responsibilities
        json schedule
        datetime created_at
        datetime updated_at
    }

    Resource {
        int id PK
        int event_id FK
        int session_id FK
        string name
        string type
        int quantity
        string status
        datetime created_at
        datetime updated_at
    }

    ExhibitorResource {
        int id PK
        int exhibitor_id FK
        string resource_name
        int quantity
        string status
        datetime created_at
        datetime updated_at
    }

    Communication {
        int id PK
        int event_id FK
        string type
        string subject
        string content
        json recipients
        datetime scheduled_at
        boolean sent
        json metrics
        datetime created_at
        datetime updated_at
    }

    BadgeInfo {
        int id PK
        int user_id FK
        string name
        string company
        string title
        string custom_fields
        datetime created_at
        datetime updated_at
    }
```