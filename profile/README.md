# ZuydUniversity GitHub Organisatie

Welkom bij de GitHub organisatie van de Academie ICT van Zuyd Hogeschool. Deze organisatie dient als centrale hub voor alle softwareontwikkelingsprojecten, onderwijsmaterialen en samenwerkingsplatforms binnen onze academie.


## Rechtenstructuur

### Organisatie niveau

#### Admins (owner) 
- Rob
- Viktor

De admins zijn verantwoordelijk voor de inrichting, het onderhoud en het beantwoorden van technische vragen betreffende de GitHub organisatie.

#### Members
- Docenten ICT Academie

Docenten mogen repositories aanmaken voor vakken, studentgroepen en projecten binnen de organisatie. Rechten op repository niveau worden door de betreffende docent ingedeeld op basis van de specifieke vereisten van het project of de cursus. Wil je member worden neem dan contact op met één van de beheerders.

#### Outside collaborators
- Studenten
- Externen

Outside collaborators hebben in principe geen rechten binnen de organisatie zelf, maar kunnen wel toegang krijgen tot specifieke repositories waar ze zijn toegevoegd.

## Repositories

Docenten kunnen repositories aanmaken voor verschillende doeleinden binnen de academie:

### Software voor Bedrijfsvoering
Repositories voor software die gebruikt wordt voor de bedrijfsvoering van de academie.

### Voorbeeldprojecten
Repositories met voorbeeldcode of opdrachtcode die dienen als referentie en leermateriaal voor studenten.

### Studentprojecten
- **Groepsprojecten**: Wanneer meerdere studenten aan een opdracht werken, werken ze binnen de ZuydUniversity organisatie met specifieke rechten op de betreffende repository.
- **Individuele opdrachten**: Voor individuele opdrachten kunnen studenten een fork aanmaken naar hun eigen GitHub omgeving om zelfstandig te werken.

## Repository Workflow

```mermaid
flowchart TD
    A[Nieuw Project] --> B{Wie gaat werken?}
    
    B -->|Docent| C{Type Project?}
    B -->|Student(en)| D{Individueel of Groep?}
    
    C -->|Bedrijfsvoering| E[ZuydUniversity Repo<br/>Software Bedrijfsvoering]
    C -->|Onderwijs| F[ZuydUniversity Repo<br/>Voorbeeldproject]
    C -->|Vak/Cursus| G[ZuydUniversity Repo<br/>Cursusmateriaal]
    
    D -->|Individueel| H[Student forkt naar<br/>eigen omgeving]
    D -->|Groepswerk| I[ZuydUniversity Repo<br/>met groepsrechten]
    
    E --> J[Docent beheert rechten]
    F --> J
    G --> J
    I --> J
    
    H --> K[Student beheert zelf]
    
    J --> L{Na 1.5 jaar inactiviteit}
    K --> M{Student verantwoordelijk}
    
    L --> N[Automatische archivering]
    M --> O[Student archiveert zelf]
    
    style E fill:#e1f5fe
    style F fill:#e1f5fe
    style G fill:#e1f5fe
    style I fill:#e1f5fe
    style H fill:#fff3e0
    style N fill:#ffebee
    style O fill:#ffebee
```

## Archivering

### Automatische Archivering
Repositories met 1,5 jaar geen activiteit worden automatisch gearchiveerd.

### Persoonlijke Repositories
Persoonlijke repositories (die zijn geforked) zijn aan de gebruiker zelf te archiveren.

### Verwijdering
Repositories die niet aan de voorwaarden voldoen worden verwijderd. Dit betreft bijvoorbeeld:
- Individueel werk dat niet in de organisatie thuishoort
- Projecten die niet gerelateerd zijn aan de academie

### Member Archivering
Oude werknemers en studenten die niet meer nodig zijn worden uit repositories verwijderd:
- Reguliere controle of ze niet meer ingeschreven staan bij de academie
- Verwijdering van toegang tot repositories waar ze niet meer actief aan werken

