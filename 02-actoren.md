# Actoren van het BimBonBon systeem

## Wat zijn actoren?

In een systeemontwikkeling onderscheiden we **stakeholders** en **actoren**:

- **Stakeholders** zijn alle betrokkenen bij het project: ze hebben belang bij het succes ervan, maar werken niet altijd direct met het systeem.
- **Actoren** zijn de mensen of systemen die daadwerkelijk **interactie hebben met de app** of andere onderdelen van het systeem. Ze voeren handelingen uit of ontvangen informatie.

In dit document beschrijven we de belangrijkste **actoren** van het te ontwikkelen SolMate systeem: wie ze zijn, wat hun rol is en wat ze nodig hebben om goed met het systeem te kunnen werken.

graph TD
    %% Het systeem zelf
    APP[BimBonBon App]

    %% Actoren rondom het systeem
    Kunde[Klant / Eindgebruiker]
    CS[Klantenservice medewerker]
    PM[Projectmanager / App-team]
    PO[Product Owner / Business Analyst]
    ERP[ERP-systeem]
    CRM[CRM-systeem]
    BI[BI-tool]
    Chat[AI-chatbot]
    MKT[Marketing & Communicatie team]

    %% Relaties naar het systeem
    Kunde --> APP
    CS --> APP
    PM --> APP
    PO --> APP
    ERP --> APP
    CRM --> APP
    BI --> APP
    Chat --> APP
    MKT --> APP

    %% Optioneel: extra beschrijving van interactie
    APP --> Kunde["Dashboard, notificaties, bestellingen, community"]
    APP --> CS["Klachten, status tracking, feedback"]
    APP --> ERP["Realtime voorraad & bestellingstracking"]
    APP --> CRM["Klantprofielen & personalisatie"]
    APP --> BI["Geanonimiseerde gebruiksdata voor inzichten"]
    APP --> Chat["24/7 ondersteuning, productinfo, FAQ"]
    APP --> MKT["Promoties, content, events"]
