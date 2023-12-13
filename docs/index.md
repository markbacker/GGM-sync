# GGM data-objecten


Report generated at: 2023-12-13  09:01:12

---
## Inhoudsopgave

* [Gemeentelijk Gegevensmodel in ArchiMate](#gemeentelijk-gegevensmodel-in-archimate)
  * [Afval (GGM)](#afval-ggm)
  * [Archeologie (GGM)](#archeologie-ggm)
  * [Archief (GGM)](#archief-ggm)
  * [BAG (GGM)](#bag-ggm)
  * [Beheer Openbare Ruimte (GGM)](#beheer-openbare-ruimte-ggm)
  * [Bouwen en Wonen (GGM)](#bouwen-en-wonen-ggm)
  * [Complex datatype (GGM)](#complex-datatype-ggm)
  * [Dienstverlening (GGM)](#dienstverlening-ggm)
  * [Dimensies (GGM)](#dimensies-ggm)
  * [Economie (GGM)](#economie-ggm)
  * [Enumeratiesoort (GGM)](#enumeratiesoort-ggm)
  * [Financien (GGM)](#financien-ggm)
  * [Gemeentebegrafenissen (GGM)](#gemeentebegrafenissen-ggm)
  * [Generiek (GGM)](#generiek-ggm)
  * [Generieke Entiteiten Erfgoed (GGM)](#generieke-entiteiten-erfgoed-ggm)
  * [Generiek Jeugd en Wmo (GGM)](#generiek-jeugd-en-wmo-ggm)
  * [Griffie (GGM)](#griffie-ggm)
  * [Groepattribuutsoort (GGM)](#groepattribuutsoort-ggm)
  * [HR (GGM)](#hr-ggm)
  * [ICT (GGM)](#ict-ggm)
  * [Inburgering (GGM)](#inburgering-ggm)
  * [Inkoop (GGM)](#inkoop-ggm)
  * [Leerplicht en Leerlingenvervoer (GGM)](#leerplicht-en-leerlingenvervoer-ggm)
  * [Meldingen Openbare Ruimte (GGM)](#meldingen-openbare-ruimte-ggm)
  * [Metagegevens (GGM)](#metagegevens-ggm)
  * [Monumenten  (GGM)](#monumenten-ggm)
  * [Museum (GGM)](#museum-ggm)
  * [Omgevingswet (GGM)](#omgevingswet-ggm)
  * [Onderwijs (GGM)](#onderwijs-ggm)
  * [Organisatie (GGM)](#organisatie-ggm)
  * [Parkeren (GGM)](#parkeren-ggm)
  * [Participatie (GGM)](#participatie-ggm)
  * [Referentielijsten (GGM)](#referentielijsten-ggm)
  * [Relatieklasse (GGM)](#relatieklasse-ggm)
  * [RGBZ Model (GGM)](#rgbz-model-ggm)
  * [RSGB Model (GGM)](#rsgb-model-ggm)
  * [Schuldhulpverlening (GGM)](#schuldhulpverlening-ggm)
  * [Sociale Teams (GGM)](#sociale-teams-ggm)
  * [Sport (GGM)](#sport-ggm)
  * [Subsidies (GGM)](#subsidies-ggm)
  * [Tekenwijze (GGM)](#tekenwijze-ggm)
  * [Union (GGM)](#union-ggm)
  * [Vastgoed (GGM)](#vastgoed-ggm)
  * [Veiligheid en Vergunningen (GGM)](#veiligheid-en-vergunningen-ggm)
  * [Verkeer (GGM)](#verkeer-ggm)

<div style="page-break-before: always;"></div>

---

## Gemeentelijk Gegevensmodel in ArchiMate

Dit model bevat een ArchiMate weergave van het GGM UML informatiemodel. De GGM UML classes, enumeraties en relations zijn ingelezen en omgezet naar ArchiMate objecten. Vervolgens zijn er met een script views per iv3-domein gegenereerd.

**Wat kun je doen met dit model?**
Dit model wordt gebruikt als basis voor de GEMMA bedrijfsobjectmodellen. Nadat het model is ingelezen wordt beoordeeld welke data-objecten gebruikt kunnen worden als basis voor een bedrijfsobject. Hiervoor krijgen de data-objecten een extra eigenschap archimate-type. In deze eigenschap wordt aangegeven dat het data-object een kandidaat bedrijfsobject is.

### Legenda views

- Kandidaat GEMMA bedrijfsobjecten zijn geel gekleurd.
- Specialization-relationships zijn groen gekleurd om deze beter te laten opvallen




### Afval (GGM)

<figure align="center">
  <img width="1273" src="2023-12-13_GGM_data-objecten/Afval__GGM_.svg" alt="Afval (GGM)">
  <figcaption><i>Afval (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Afval</td>
      <td><p>706</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Prijsafspraak</td>
      <td><p>Overeenkomst tussen concurrenten met betrekking tot de prijs van goederen of diensten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Prijsregel</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Categorie</td>
      <td><p>Categorie waarop leveranciers zich voor de levering van personeel voor kunnen kwalificeren</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Pas</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Milieustraat</td>
      <td><p>Een locatie die specifiek bestemd is voor het brengen van gescheiden huishoudelijk afval en grofvuil.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Storting</td>
      <td><p>Activiteit, inhoudende a. het zich ontdoen van stoffen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Fractie</td>
      <td><p>Onderdeel, deeltje</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Route</td>
      <td><p>Routes die gereden worden om bepaalde fracties vuilnis op te halen. Routes gaan langs locaties, waar afhankelijk van de routesoort een containers, bepaalde plekken of adressen worden aangedaan.</p>
<ul>
 <li>huis-aan-huis: er worden locaties met adressen aangedaan</li>
 <li>illegale dumping, grofvuil: er worden locaties aangedaan (evt met adres)</li>
 <li>containters: er worden locaties met containers aangedaan</li>
</ul></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Rit</td>
      <td><p>Verplaatsing van een wegvoertuig over een wegpad</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Melding</td>
      <td><p>De betekenisvolle formulering van een waargenomen feit, waaraan een waarde kan worden toegekend</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Locatie</td>
      <td><p>Locaties die worden aangedaan tijdens het rijden van een route. Dit kunnen adressen zijn en/of GML-punten met een x- en y-coordinaat. Avalex hanteert op het moment van schrijven alleen adressen, ook voor de containers.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Ophaalmoment</td>
      <td><p>Een stop die een vuilniswagen maakt tijdens het doen van een rit. Bijgehouden wordt de gewichtstoename van de lading</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Container</td>
      <td><p>Container voor het gescheiden inzamelen van huishoudelijke afvalstoffen dwz afvalstoffen afkomstig uit particuliere huishoudens behoudens voor zover het ingezamelde bestanddelen van die afvalstoffen betreft die zijn aangewezen als gevaarlijke afvalstoffen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vuilniswagen</td>
      <td><p>Een vrachtwagen die gebruikt wordt om afval in te zamelen bij bedrijven en huishoudens (huisvuil)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Containertype</td>
      <td><p>Typologie van container</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vulgraadmeting</td>
      <td><p>Mate waarin een (afval)container gevuld is</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Routesoort</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">AanvraagOfMelding</td>
      <td><p>Komt overeen met een VJV</p>
<p>Bron: GEM<em>VJV (Distinct op REQ</em>ID)
ID: REQ_ID</p></td>
    </tr>
  </tbody>
</table>

### Archeologie (GGM)

<figure align="center">
  <img width="1153" src="2023-12-13_GGM_data-objecten/Archeologie__GGM_.svg" alt="Archeologie (GGM)">
  <figcaption><i>Archeologie (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Archeologie</td>
      <td><p>583</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vindplaats</td>
      <td><p>Een plek waar men iets gevonden heeft.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Project</td>
      <td><p>Geheel van activiteiten uitgevoerd in een tijdelijk samenwerkingsverband gericht op het binnen bepaalde randvoorwaarden (bv. tijd, geld) bereiken van een vooraf gedefinieerd resultaat.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Archeologiebesluit</td>
      <td><p>Een professioneel oordeel dat gebaseerd is op algemeen aanvaarde wetenschap ten aanzien van de archeologie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">boring</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Put</td>
      <td><p>Grondspoor, veelal verstevigd en gefundeerd aangelegd, bedoeld voor de tijdelijke opslag van danwel water (waterput) danwel uitwerpselen en afval (beerput).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">locatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vlak</td>
      <td><p>Plat, oneindig oppervlak of variëteit zonder enige kromming.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Spoor</td>
      <td><p>Een blijk van eerdere aanwezigheid.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vulling</td>
      <td><p>Dunne wegeringsplank gebruikt om de ruimte tussen de bovenste kimweger en de onderste balkweger op te vullen (Sopers, 1974).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vondst</td>
      <td><p>Overblijfsel, voorwerp of ander spoor van menselijke aanwezigheid in het verleden afkomstig van een archeologisch monument</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Artefact</td>
      <td><p>De benaming voor ieder verplaatsbaar object dat door de mens is vervaardigd, bewerkt en/of gebruikt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Artefactsoort</td>
      <td><p>Typering van artefacten</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Magazijnplaatsing</td>
      <td><p>Het ergens neerzetten van een object in een magazijn.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Doos</td>
      <td><p>Een afsluitbaar object waar iets in wordt opgeborgen of verpakt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Stelling</td>
      <td><p>Een systeem om goederen op te slaan die worden vervoerd en opgeslagen op pallets, in bundels of per stuk.(Wikipedia)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Magazijnlocatie</td>
      <td><p>Locatie van een magazijn</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Kaart</td>
      <td><p>De geografische weergave van een gedeelte van het aardoppervlak</p></td>
    </tr>
  </tbody>
</table>

### Archief (GGM)

<figure align="center">
  <img width="2983" src="2023-12-13_GGM_data-objecten/Archief__GGM_.svg" alt="Archief (GGM)">
  <figcaption><i>Archief (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">RECHTSPERSOON</td>
      <td><p>Een NATUURLIJK PERSOON of een NIET-NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Historisch Persoon</td>
      <td><p>Natuurlijk persoon waarvan informatie beschikbaar is uit het verleden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">NATUURLIJK PERSOON</td>
      <td><p>Een INGESCHREVEN PERSOON of ANDER NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Archief</td>
      <td><p>601</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Archiefcategorie</td>
      <td><p>Typologie van een archief conform landelijke indeling</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Rechthebbende</td>
      <td><p>Een rechthebbende is iemand die rechten heeft op een goed.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Ordeningsschema</td>
      <td><p>Ordening om archief en collecties beter vindbaar en bruikbaar voor betrokkenen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Uitgever</td>
      <td><p>Iemand die iets op de markt brengt; iemand die iets uitgeeft</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Auteur</td>
      <td><p>De persoon die verantwoordelijk is voor de inhoud van een (digitaal) document</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Indeling</td>
      <td><p>Onderwerpen groeperen in samenhangende categorie√´n.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Archief</td>
      <td><p>De bewaarplaats van belangrijke gegevens die zijn vastgelegd in documentvorm alsook de verzameling van documenten die voor een bepaald doel vervaardigd zijn.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Archiefstuk</td>
      <td><p>Bijeengebrachte informatie, ongeacht het medium, die wordt gecre√´erd, ontvangen en gearchiveerd door een bureau, een instelling, een organisatie of een individu met het oog op het nakomen van wettelijke verplichtingen of het uitvoeren van zakelijke transacties.(AAT)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Digitaal Bestand</td>
      <td><p>Bestand dat uitsluitend met behulp van besturingsprogrammatuur of toepassingsprogrammatuur geraadpleegd kunnen worden</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Nadere Toegang</td>
      <td><p>De bevoegdheid om gegevens te raadplegen, bepaalde plaatsen te betreden of een bepaalde taak uit te oefenen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Index</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vindplaats</td>
      <td><p>Een plek waar men iets gevonden heeft.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Stelling</td>
      <td><p>Een systeem om goederen op te slaan die worden vervoerd en opgeslagen op pallets, in bundels of per stuk.(Wikipedia)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Plank</td>
      <td><p>Deel, plaat; stuk hout breder dan het dik is en langer dan breed.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bezoeker</td>
      <td><p>Een persoon die iemand of iets bezoekt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Aanvraag</td>
      <td><p>(officieel) verzoek, iets (officieel) vragen aan een bevoegde macht.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Depot</td>
      <td><p>Plaats waar iets bewaard wordt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Kast</td>
      <td><p>Object met een permanent karakter dat dient om iets in te bergen en te beschermen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">DOCUMENT</td>
      <td><p><font color="#610e6a">Geheel van gegevens met een eigen identiteit ongeacht zijn vorm, met de bijbehorende metadata ontvangen of opgemaakt door een natuurlijke en/of rechtspersoon bij de uitvoering van taken, zijnde een ENKELVOUDIG DOCUMENT of een SAMENGESTELD DOCUMENT.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Periode</td>
      <td><p>bepaalde tijdsduur.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Erfgoed Object</td>
      <td><p>Uit het verleden ge√´rfde materi√´le en immateri√´le objecten</p></td>
    </tr>
  </tbody>
</table>

### BAG (GGM)

<figure align="center">
  <img width="2317" src="2023-12-13_GGM_data-objecten/BAG__GGM_.svg" alt="BAG (GGM)">
  <figcaption><i>BAG (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">BAG</td>
      <td><p>375</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">NUMMERAANDUIDING</td>
      <td><p>Een nummeraanduiding is een door het bevoegde gemeentelijke orgaan als zodanig toegekende aanduiding van een verblijfsobject, een standplaats of een ligplaats. Het is het samenstel van postcode, huisnummer, huisletter en huisnummertoevoeging.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">OPENBARE RUIMTE</td>
      <td><p>Definitie
Een openbare ruimte is een door het bevoegde gemeentelijke orgaan als zodanig aangewezen en van een naam voorziene buitenruimte die binnen &#233;&#233;n woonplaats is gelegen.</p>
<p>Beschrijving
Een buitenruimte die door de gemeente als openbare ruimte is aangewezen en waaraan de gemeente een naam heeft gegeven. Een openbare ruimte ligt binnen 1 woonplaats. De BAG kent 7 soorten openbare ruimten: weg, water, spoorbaan, terrein, kunstwerk, landschappelijk gebied en administratief gebied. Een openbare ruimte is meestal een straat(naam).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">BUURT</td>
      <td><p>Een aaneengesloten gedeelte van een wijk, waarvan de grenzen zo veel mogelijk gebaseerd zijn op topografische elementen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">WIJK</td>
      <td><p>Een aaneengesloten gedeelte van het grondgebied van een gemeente, waarvan de grenzen zo veel mogelijk zijn gebaseerd op sociaal-geografische kenmerken.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">WOONPLAATS</td>
      <td><p>Definitie
Een woonplaats is een door het bevoegde gemeentelijke orgaan als zodanig aangewezen en van een naam voorzien gedeelte van het grondgebied van de gemeente</p>
<p>Beschrijving
Een stuk grond binnen de gemeente dat als woonplaats is aangewezen en waaraan de gemeente ook een naam heeft gegeven.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">GEMEENTE</td>
      <td><p>Een gedeelte van het grondgebied van Nederland, ingesteld op basis van artikel 123 van de Grondwet.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Boolean</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">ADRESSEERBAAR OBJECT</td>
      <td><p>Definitie
Een adresseerbaar object is een object waaraan formeel adressen kunnen en moeten worden toegekend: een verblijfsobject, standplaats of ligplaats.</p>
<p>Is generalisatie van
ligplaats
standplaats
verblijfsobject</p>
<p>Toelichting
Een object dat een adres heeft of krijgt. Adresseerbare objecten zijn: een verblijfsobject, een standplaats en een ligplaats.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">TypeAdresseerbaarObject</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">ontsluitingswijzeVerdieping</td>
      <td><p>De verschillende waarden die de ontsluiting van een verdieping kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">soortWoonobject</td>
      <td><p><font color="#0f0f0f">De verschillende waarden die een soort woonobject kan aannemen.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">statusLigplaats</td>
      <td><p>Een aanduiding van alle waarden die de status van een lig- of standplaats<br />
kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">LIGPLAATS</td>
      <td><p>Definitie
Een ligplaats is een door het bevoegde gemeentelijke orgaan als zodanig aangewezen plaats in het water al dan niet aangevuld met een op de oever aanwezig terrein of een gedeelte daarvan, die bestemd is voor het permanent afmeren van een voor woon-, bedrijfsmatige of recreatieve doeleinden geschikt drijvend object</p>
<p>Beschrijving
Een plaats in het water met soms ook een (deel van een) terrein op de oever. Deze plaats moet kunnen worden gebruikt door een drijvend object dat langere tijd daar wordt vastgemaakt. Het drijvende object moet geschikt zijn om in te wonen, om een bedrijf in te hebben of om voor plezier in te verblijven. Bijvoorbeeld een woonboot. De gemeente mag zeggen of er voor de BAG ergens een ligplaats komt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">statusStandplaats</td>
      <td><p>Een aanduiding van alle waarden die de status van een lig- of standplaats<br />
kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">VERBLIJFSOBJECT</td>
      <td><p>Definitie
Een verblijfsobject is een kleinste binnen &#233;&#233;n of meer panden gelegen en voor woon-, bedrijfsmatige, of recreatieve doeleinden geschikte eenheid van gebruik die ontsloten wordt via een eigen afsluitbare toegang vanaf de openbare weg, een erf of een gedeelde verkeersruimte, onderwerp kan zijn van goederenrechtelijke rechtshandelingen en in functioneel opzicht zelfstandig is.</p>
<p>Beschrijving
Een verblijfsobject is een ruimte in 1 of meer panden en voldoet aan de volgende eisen: kan worden gebruikt om in te wonen, een bedrijf in te hebben of om voor plezier in te verblijven, is bereikbaar via een eigen afsluitbare toegang vanaf de openbare weg, een erf of een gedeelde verkeersruimte, kan worden gekocht en verkocht, kan helemaal zelf worden gebruikt voor het doel dat ervoor is gegeven. Deze eisen voor verblijfsobjecten worden toegelicht in de Catalogus BAG 2018. Een verblijfsobject krijgt een adres.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">PAND</td>
      <td><p>Definitie
Een pand is een kleinste bij de totstandkoming functioneel en bouwkundig-constructief zelfstandige eenheid die direct en duurzaam met de aarde is verbonden en betreedbaar en afsluitbaar is.</p>
<p>Beschrijving
Een zelfstandig bouwwerk, zowel zelfstandig in de manier hoe het is gebouwd als waarvoor het is bedoeld om te gebruiken. Een pand voldoet ook aan de volgende eisen: een pand is direct en voor lange tijd met de aarde verbonden (een pand is niet makkelijk te verplaatsen) en een pand kun je binnengaan en afsluiten. Een eenheid kan alleen een pand zijn als het voldoet aan alle eisen uit de Catalogus BAG 2018.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">statusNummeraanduiding</td>
      <td><p>Een aanduiding van alle  fases van de levenscyclus  die een  nummeraanduiding kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">statusOpenbareRuimte</td>
      <td><p>Een aanduiding van alle fasen van de levenscyclus die een openbare ruimte kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">gebruiksdoel</td>
      <td><p>Een aanduiding va alle waarden waarmee het gebruiksdoel van een object kan 
worden verbijzonderd.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">STANDPLAATS</td>
      <td><p>Definitie
Een standplaats is een door het bevoegde gemeentelijke orgaan als zodanig aangewezen terrein of gedeelte daarvan dat bestemd is voor het permanent plaatsen van een niet direct en niet duurzaam met de aarde verbonden en voor woon-, bedrijfsmatige, of recreatieve doeleinden geschikte ruimte.</p>
<p>Beschrijving
Een terrein of een deel daarvan dat moet kunnen worden gebruikt om langere tijd een object neer te zetten. Dit object moet geschikt zijn om in te wonen, om een bedrijf in te hebben of om voor plezier in te verblijven. Het moet verplaatsbaar zijn en mag dus niet helemaal vastgemaakt worden aan de grond. Bijvoorbeeld een woonwagen of strandtent. De gemeente mag zeggen of er voor de BAG ergens een standplaats komt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">statusPand</td>
      <td><p>De verschillende waarden die de status van een pand kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">statusVerblijfsobject</td>
      <td><p>Een aanduiding van alle waarden die de status van een verblijfsobject kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">statusVoortgangBouw</td>
      <td><p>Een aanduiding van alle fases die de voortgang bouw pand kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">statusWoonplaats</td>
      <td><p>Een aanduiding van alle waarden die de status van een woonplaats 
kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">typeringOpenbareRuimte</td>
      <td><p>De verschillende waarden die de typering van een openbare ruimte kan aannemen.</p></td>
    </tr>
  </tbody>
</table>

### Beheer Openbare Ruimte (GGM)

<figure align="center">
  <img width="2983" src="2023-12-13_GGM_data-objecten/Beheer_Openbare_Ruimte__GGM_.svg" alt="Beheer Openbare Ruimte (GGM)">
  <figcaption><i>Beheer Openbare Ruimte (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">BEGROEID TERREINDEEL</td>
      <td><p>Kleinste functioneel onafhankelijk stukje van een terrein dat er binnen het objecttype Terrein van NEN 3610 wordt onderscheiden, met aaneengesloten homogene vegetatie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">V-Log-Info</td>
      <td><p>V-log is een open standaard voor datalogging van een verkeersregelinstallatie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">FUNCTIONEEL GEBIED</td>
      <td><p>Begrensd en benoemd gebied dat door een functionele eenheid beschreven wordt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">GEBOUWINSTALLATIE</td>
      <td><p>Een component aan de buitenzijde van een gebouw, die het aanzicht van het gebouw mede bepaalt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">INRICHTINGSELEMENT</td>
      <td><p>Ruimtelijk object al dan niet ter detaillering dan wel ter inrichting van de
overige benoemde ruimtelijke objecten of een ander inrichtingselement.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">MEDEWERKER</td>
      <td><p><font color="#610e6a">Een medewerker van de organisatie die zaken behandelt uit hoofde van zijn of haar functie binnen een ORGANISATORISCHE EENHEID.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">KUNSTWERKDEEL</td>
      <td><p>Onderdeel van een civiel-technisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Leverancier</td>
      <td><p>Een niet-natuurlijk persoon die een product of dienst levert aan de organisatie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">ONBEGROEID TERREINDEEL</td>
      <td><p>Kleinste functioneel onafhankelijk stukje van een terrein, dat er binnen het objecttype Terrein van NEN 3610 wordt onderscheiden, zonder aaneengesloten vegetatie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Verkeerstelling</td>
      <td><p>Een onderzoek om inzicht te krijgen in het verkeer, in de hoeveelheid verkeer, de verdeling en de gereden snelheid.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">NATUURLIJK PERSOON</td>
      <td><p>Een INGESCHREVEN PERSOON of ANDER NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">BUURT</td>
      <td><p>Een aaneengesloten gedeelte van een wijk, waarvan de grenzen zo veel mogelijk gebaseerd zijn op topografische elementen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Beheer Openbare Ruimte</td>
      <td><p>791</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bak</td>
      <td><p>Object met een permanent karakter dat dient om iets in te bergen of te verzamelen. (bron: definities.geostandaarden.nl)
Synoniemen: Bak</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Afvalbak</td>
      <td><p>Inzamelobject voor afval in de openbare ruimte dat handmatig kan worden leeggemaakt.
Toelichting: Inzamelobject voor afval in de openbare ruimte dat handmatig kan worden leeggemaakt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Sensor</td>
      <td><p>Apparaat voor de meting van een fysieke grootheid (bijv. temperatuur, licht, druk, elektriciteit).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Putdeksel</td>
      <td><p>Deksel met als functie het afdekken van een put (GWSW). Dekt meestal de opening van een rioolput af, is meestal rond,  van zwaar metaal, soms van kunststof.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verkeersdrempel</td>
      <td><p>Verhoging in de rijbaan, bedoeld om het gemotoriseerde verkeer met een lage(re) snelheid te laten rijden. Toelichting: Sinds ongeveer 2000 beschikt de Nederlandse wegenbouw over technische mogelijkheden om drempels uit te voeren in een doorlopende asfaltverharding en dan zodanig dat deze een specifieke snelheid uitlokken bij circa 80 procent van het gemotoriseerde verkeer.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Boom</td>
      <td><p>Een houtachtig gewas (loofboom of conifeer) met een wortelgestel en een enkele, stevige, houtige stam, die zich boven de grond vertakt.
Toelichting: Een houtachtig gewas (loofboom of conifeer) met een wortelgestel en een enkele, stevige, houtige stam, die zich boven de grond vertakt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Deelplan/Veld</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Fase/Oplevering</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Actie</td>
      <td><p>Kleinst mogelijke eenheid van werk die zinvol onderscheiden kan worden, uitgevoerd door een persoon of machine op 1 plek op 1 moment.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Kwaliteitskenmerken</td>
      <td><p>Aanduiding van de hoedanigheid van uitvoering, bewerking en representativiteit van een meting, volgens een overeengekomen waarderingsschaal.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Logboek</td>
      <td><p>Registratie waarin gebeurtenissen worden bijgehouden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Klimplant</td>
      <td><p>Plant met buigzame stengels die zich op diverse manieren aan muren, bomen of constructies hecht en zodoende omhoog klimt.
Toelichting: Plant met buigzame stengels die zich op diverse manieren aan muren, bomen of constructies hecht en zodoende omhoog klimt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Proces-verbaal-MOOR-melding</td>
      <td><p>Officieel op papier gesteld verslag met betrekking tot heen MOOR-melding</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Weginrichtingsobject</td>
      <td><p>Een ruimtelijk object dat dient voor de inrichting van de openbare weg.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">SolitairePlant</td>
      <td><p>Plant, heester of siergras, te beheren als solitair beplantingselement.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Areaal</td>
      <td><p>Het verspreidingsgebied van een een soort, een levensgemeenschap of een biotooptype.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">MOOR-melding</td>
      <td><p>Meldingsproces rondom werkzaamheden aan kabels en leidingen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Waterobject</td>
      <td><p>Kleinste functioneel onafhankelijk stukje water met gelijkblijvende, homogene eigenschappen en relaties dat er binnen het objecttype Water van NEN 3610 wordt onderscheiden en dat permanent met water bedekt is. (imgeo.geostandaarden.nl)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Geluidsscherm</td>
      <td><p>Een scheiding bedoeld om geluidshinder in de buitenlucht te verminderen. (IMGeo)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">CROW-Melding</td>
      <td><p>BOR-MELD is een CROW-standaard voor het vastleggen van meldingen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Waterinrichtingsobject</td>
      <td><p>Een ruimtelijk object ter inrichting van het water.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Kademuur</td>
      <td><p>Verticale wand ter scheiding van land en water, opgebouwd uit een muur van gemetselde stenen of gestort beton. (bron: definities.geostandaarden.nl)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Inspectie</td>
      <td><p>het inwinnen, verwerken en interpreteren van informatie met het doel om de momentane toestand van de boezemkade vast te stellen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Paal</td>
      <td><p>Langwerpig stuk hout, ijzer, steen enz., dat in de grond staat.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Keermuur</td>
      <td><p>Muur die door vorm, gewicht en fundering zonder verankering de grond keert, vaak van beton met L-vormige doorsnede.  Een keermuur of keerwand is een stijf, grond- of waterkerend kunstwerk dat door een groot gewicht en een brede voet een grote standzekerheid kan bereiken. Een keermuur is meestal van gewapend beton, maar er kan ook ander materiaal gebruikt worden. (IMGeo)
Synoniemen: Keerwand, klip</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verlichtingsobject</td>
      <td><p>Paal of mast waaraan openbare verlichting is bevestigd.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Aansluitput</td>
      <td><p>Type put met de functie aansluitleidingen aansluiten</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verhardingsobject</td>
      <td><p>Verharde lagen van een weglichaam, speel- en sportondergronden en onbegroeid terreindelen inclusief de fundering.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Drainageput</td>
      <td><p>Put welke toegang geeft naar een poreuze of geperforeerde buisleiding, aangebracht onder de grond om de afwatering van de grond te verbeteren.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vegetatieobject</td>
      <td><p>Verzamelobject van alle vegetatieobjecten - niveau 2</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Filterput</td>
      <td><p>Put met een filterconstructie voor het onttrekken van grondwater. Kan ook beschouwd worden als een soort drainagevoorziening.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Kast</td>
      <td><p>Object met een permanent karakter dat dient om iets in te bergen en te beschermen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Infiltratieput</td>
      <td><p>Een put met waterdoorlatende wanden bestemd voor de inzameling van hemelwater, waarbij het hemelwater door middel van infiltratie door de wanden kan worden afgevoerd</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Kolk</td>
      <td><p>Een reservoir bestemd voor de opvang van hemelwater afkomstig van erop aangesloten oppervlakken, het laten bezinken van in dit water meegevoerde bezinkbare stoffen en de afvoer van dit water naar een rioolstelsel of naar de ondergrond.
Synoniemen: Afvoerput</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Tunnelobject</td>
      <td><p>Onderdeel van een kunstmatig aangelegde, kokervormige onderdoorgang dat essentieel is voor de constructie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Rioolput</td>
      <td><p>Constructie toegang gevend tot het rioolstelselÂ&nbsp;Â</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Beheerobject</td>
      <td><p>Verzamelobject - niveau 1</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Terreindeel</td>
      <td><p>Kleinste functioneel onafhankelijk stukje van een terrein, dat er binnen het objecttype Terrein van NEN 3610 wordt onderscheiden, met of zonder aaneengesloten vegetatie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Brug</td>
      <td><p>Kunstwerk over een waterweg, watergang of waterloop, bestaande uit een brugdek gesteund door pijlers en/of landhoofden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Scheiding</td>
      <td><p>Kunstmatig, meestal lineair obstakel met een werende functie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Put</td>
      <td><p>Verticale waterdichte constructie, toegepast om leidingen aan te sluiten, van richting of niveau te veranderen, om toegang te verschaffen aan personeel en/of apparatuur voor inspectie en onderhoud, en om beluchting en ventilatie mogelijk te maken</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Schouwronde</td>
      <td><p>Activiteit om te controleren of de opdrachtnemer aan de afspraken voldoet.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Melding</td>
      <td><p>De betekenisvolle formulering van een waargenomen feit, waaraan een waarde kan worden toegekend</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Uitvoerder Graafwerkzaamheden</td>
      <td><p>Degene die op de bouwlocatie van een project de leiding heeft met betrekking tot de graafwerkzaamheden</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Opbreking</td>
      <td><p>Vorm van wegwerkzaamheid</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Overbruggingsobject</td>
      <td><p>Onderdeel van een beweegbare of vaste verbinding tussen twee punten, die door water, een weg of anderszins gescheiden zijn, dat essentieel is voor de constructie .</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Kwaliteitscatalogus Openbare Ruimte</td>
      <td><p>zie https://www.crow.nl/publicaties/kwaliteitscatalogus-openbare-ruimte-2018</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Geo-Object</td>
      <td><p>Abstractie van een fenomeen in de werkelijkheid, dat direct of indirect is geassocieerd met een locatie relatief ten opzichte van de aarde. [NEN 3610:2011]</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Meubilair</td>
      <td><p>De verzameling van ruimtelijke objecten ter inrichting van de openbare ruimte of terreinen.
Een ruimtelijk object ter inrichting van de openbare ruimte.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Mast</td>
      <td><p>Draagconstructie, bestaande uit een verticale buispaal, die wordt gebruikt om iets op hoogte te brengen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Leidingelement</td>
      <td><p>Een object dat bij een leiding behoort.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Leiding</td>
      <td><p>Een geheel van geleiders welke voorzien zijn van Ã©Ã©n ommanteling en bestemd is voor transport van materie GWSW</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Kunstwerk</td>
      <td><p>Civiel-technisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen en niet bedoeld voor permanent menselijk verblijf. http://definities.geostandaarden.nl</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Installatie</td>
      <td><p>Samenhangend systeem dat een bepaald doel dient.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Ecoduct</td>
      <td><p>Wildwissel in de vorm van een viaduct voor passages van dieren over een weg of spoorweg. IMGeo
Synoniemen: Natuurbrug, Faunabrug, Ecobrug, Ecopassage, Natuurpassage
Toelichting: Opheffen van barriÃ¨res en de migratie van fauna mogelijk maken tussen of binnen leefgebieden en populaties.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Groenobject</td>
      <td><p>Kleinste functioneel onafhankelijk stukje van een terrein dat er binnen het objecttype Terrein van NEN 3610 wordt onderscheiden, met aaneengesloten vegetatie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Flyover</td>
      <td><p>Kunstwerk in de vorm van een viaduct dat deel uitmaakt van een verkeersbaan en waarmee een verkeersstroom over twee of meer ongelijkvloerse verkeersstromen wordt geleid.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Viaduct</td>
      <td><p>Kunstwerk over een weg, spoorweg of terreinverdieping, bestaande uit een dek gesteund door pijlers en/of landhoofden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bank</td>
      <td><p>Aaneengesloten zitplaats voor verscheidene personen, bedoeld voor openbaar gebruik en geplaatst in de openbare ruimte (vnl. in parken, plantsoenen, bossen en langs wegen).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">FunctioneelGebied</td>
      <td><p>Begrensd en benoemd gebied dat door een functionele eenheid beschreven wordt.   (bron: definities.geostandaarden.nl)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Fietsparkeervoorziening</td>
      <td><p>Een duurzaam verankerd rek in de openbare ruimte voor het stallen van fietsen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bouwwerk</td>
      <td><p>Met de aarde verbonden duurzaam bouwwerk, dat niet valt onder de definities van een pand of kunstwerk  (bron: definities.geostandaarden.nl)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Storing</td>
      <td><p>Verlies van de mogelijkheid om volgens een specificatie te werken of om het vereiste resultaat te leveren.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bord</td>
      <td><p>Paneel waarop (statische) informatie wordt afgebeeld, verwoord in tekst, pictogram of code.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Speeltoestel</td>
      <td><p>Toestel en structuren, met inbegrip van componenten en constructieve onderdelen, waarmee of waarop kinderen binnen of buiten kunnen spelen, individueel of gezamenlijk, volgens hun eigen spelregels of beweegredenen, die te allen tijde kunnen worden gewijzi
Synoniemen: Speelvoorziening</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">MeldingOngeval</td>
      <td><p>Aangifte vna een ongeval</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Gemaal</td>
      <td><p>Een constructie ten behoeve van het verplaatsen van waterÂ&nbsp;Â&nbsp;GWSW</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Uitlaatconstructie</td>
      <td><p>Het eindpunt van een rioolleiding waar uitstroming van afvalwater uit het rioolstelsel naar het oppervlaktewater mogelijk is.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Grondbeheerder</td>
      <td><p>Beheerder van grondgrondbeheer., oplossing voor duurzaam landbeheer en voedselproductie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Omgevingsvergunning</td>
      <td><p>Vergunning als bedoeld in afdeling 5.1 van de Omgevingswet</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Overstortconstructie</td>
      <td><p>Een constructie voorzien van een overstortdrempel met een ontworpen drempelbreedte en -hoogte.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Onderhoud</td>
      <td><p>Maatregelen om de functionele kwaliteit in stand te houden of te herstellen en dus de levensduur van een (object)onderdeel te realiseren c.q. te verlengen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Pomp</td>
      <td><p>Een technische installatie die het (afval) water onder druk transporteert.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Taak</td>
      <td><p>Een samenhangende set activiteiten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bemalingsgebied</td>
      <td><p>Een rioleringsgebied waaruit het afvalwater door een gemaal wordt verwijderd.
Toelichting: Een rioleringsgebied waaruit het afvalwater door een gemaal wordt verwijderd</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">KadastraleMutatie</td>
      <td><p>Wijziging in de kadatrale registratie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verkeerslicht</td>
      <td><p>Lichten die aangeven dat je moet stoppen, dat je mag doorrijden, of die je waarschuwen voor gevaar.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Stuwgebied</td>
      <td><p>Een deelgebied van een bemalingsgebied waarvan de afvoer via een stuwput of stuwriool wordt beperkt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">CROW-Kwaliteitsniveaus</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Sportterrein</td>
      <td><p>Terrein mogelijk met groenvoorziening, verharding en bebouwing bestemd voor sportbeoefening.
Synoniemen: Sportveld</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Energielabel</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Speelterrein</td>
      <td><p>Geheel van begroeiing verharding opstallen en speelwerktuigen bedoeld als speelplaats voor kinderen.
Synoniemen: Speelplek, Speelgelegenheid</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Oppervlakte Woning</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Rioleringsgebied</td>
      <td><p>Het gebied waarbinnen Ã©Ã©n of meerdere inliggende rioolstelsel(s) het afvalwater naar Ã©Ã©n gemaal of overnamepunt transporteert/teren. Een rioleringsgebied kan een enkelvoudig gebied zijn, maar kan ook meerdere rioleringsgebieden omvatten. Een gebied is zodanig gekozen dat het voldoende inzicht geeft in de belasting van oppervlaktewater en overnamepunt.
Toelichting: Het gebied waarbinnen Ã©Ã©n of meerdere inliggende rioolstelsel(s) het afvalwater naar Ã©Ã©n gemaal of overnamepunt transporteert/teren. Een rioleringsgebied kan een enkelvoudig gebied zijn, maar kan ook meerdere rioleringsgebieden omvatten. Een gebied is zodanig gekozen dat het voldoende inzicht geeft in de belasting van oppervlaktewater en overnamepunt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bergingsbassin</td>
      <td><p>Een gesloten reservoir waarin het afvalwater tijdelijk wordt opgevangen
Synoniemen: Retentiebassin, bufferbassin</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">DOCUMENT</td>
      <td><p><font color="#610e6a">Geheel van gegevens met een eigen identiteit ongeacht zijn vorm, met de bijbehorende metadata ontvangen of opgemaakt door een natuurlijke en/of rechtspersoon bij de uitvoering van taken, zijnde een ENKELVOUDIG DOCUMENT of een SAMENGESTELD DOCUMENT.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Plan</td>
      <td><p>Project waarin woningen worden gerealiseerd</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">ONDERSTEUNEND WATERDEEL</td>
      <td><p>Object dat in het kader van de waterhuishouding periodiek gedeeltelijk of geheel met water is bedekt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">RECHTSPERSOON</td>
      <td><p>Een NATUURLIJK PERSOON of een NIET-NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">WIJK</td>
      <td><p>Een aaneengesloten gedeelte van het grondgebied van een gemeente, waarvan de grenzen zo veel mogelijk zijn gebaseerd op sociaal-geografische kenmerken.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">ONDERSTEUNEND WEGDEEL</td>
      <td><p>Een deel van de weg dat niet primair bedoeld is voor gebruik door het verkeer.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">KADASTRALE ONROERENDE ZAAK</td>
      <td><p>Een geregistreerd goed waarvoor bij overdracht of vestiging van rechten inschrijving in de openbare registers van het Kadaster is vereist zijnde een KADASTRAAL PERCEEL of een APPARTEMENTSRECHT.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">OVERBRUGGINGSDEEL</td>
      <td><p>Onderdeel van een beweegbare of vaste verbinding tussen twee punten, die door water, een weg of anderszins gescheiden zijn, dat essentieel is voor de constructie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">ZAKELIJK RECHT</td>
      <td><p>Het eigendom van, of een beperkt recht van een natuurlijk of niet-natuurlijk persoon (PERSOON) op, een onroerende zaak (met uitzondering van hypotheken en beslagen).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">OVERIG BENOEMD TERREIN</td>
      <td><p>Een door het bevoegde gemeentelijke orgaan als zodanig aangewezen onbebouwd terrein of een gedeelte daarvan, geen standplaats of gedeelte van een ligplaats zijnde, dat bestemd is voor het gedurende langere tijd verrichten van een maatschappelijke activiteit.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">OVERIG BOUWWERK</td>
      <td><p>Met de aarde verbonden duurzaam bouwwerk, dat niet valt onder de definities van een pand of kunstwerk.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">OVERIGE SCHEIDING</td>
      <td><p>Kunstmatig, meestal lineair obstakel met een werende functie, met kleinere afmetingen dan toegestaan voor opname in de BGT.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">PAND</td>
      <td><p>De kleinste bij de totstandkoming functioneel en bouwkundig-constructief zelfstandige eenheid die direct en duurzaam met de aarde is verbonden en betreedbaar en afsluitbaar is.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">SCHEIDING</td>
      <td><p>Kunstmatig, meestal lineair obstakel met een werende functie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">SPOOR</td>
      <td><p>De as van het spoor, dat wil zeggen het midden van twee stalen staven op een onderling vaste afstand, waarover trein, tram, of sneltram rijdt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">TUNNELDEEL</td>
      <td><p>Onderdeel van een kunstmatig aangelegde, kokervormige onderdoorgang, dat essentieel is voor de constructie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">VEGETATIEOBJECT</td>
      <td><p>Solitair vegetatieobject of lijn- of vlakvormige groep gelijksoortige vegetatieobjecten met een beperkte omvang.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">WATERDEEL</td>
      <td><p>Kleinste functioneel onafhankelijk stukje water met gelijkblijvende, homogene eigenschappen en relaties dat er binnen het objecttype Water van NEN 3610 wordt onderscheiden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">WEGDEEL</td>
      <td><p>Kleinste functioneel onafhankelijk stukje van een NEN 3610 Weg,  met gelijkblijvende homogene eigenschappen en relaties en primair bedoeld voor gebruik door weg-, spoor- en vliegverkeer te land</p></td>
    </tr>
  </tbody>
</table>

### Bouwen en Wonen (GGM)

<figure align="center">
  <img width="1591" src="2023-12-13_GGM_data-objecten/Bouwen_en_Wonen__GGM_.svg" alt="Bouwen en Wonen (GGM)">
  <figcaption><i>Bouwen en Wonen (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">NIET NATUURLIJK PERSOON</td>
      <td><p>Een INGESCHREVEN NIET-NATUURLIJK PERSOON of een ANDER BUITENLANDS NIET-NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">NATUURLIJK PERSOON</td>
      <td><p>Een INGESCHREVEN PERSOON of ANDER NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Bouwen en Wonen</td>
      <td><p>798</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Projectontwikkelaar</td>
      <td><p>Een persoon of een firma die een project ontwikkelt voor financieel gewin.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Studentenwoningen</td>
      <td><p>Een woning waar uitsluitend (meerdere) studenten (of soms ook werkende jongeren) een woongemeenschap vorme</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Projectleider</td>
      <td><p>De persoon die een project aanstuurt</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Plan</td>
      <td><p>Project waarin woningen worden gerealiseerd</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Gebouw</td>
      <td><p>Een complex van ruimten uitsluitend bedoeld voor de huisvesting van een afzonderlijk huishouden</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Koopwoningen</td>
      <td><p>Een woning die eigendom is van een particulier (in het algemeen de bewoner van de woning).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Huurwoningen</td>
      <td><p>Wen woning die de bewoner huurt van de eigenaar, veelal een woningcorporatie of een particulier.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Programma</td>
      <td><p>Een tijdelijke, flexibele organisatiestructuur, die is opgezet om de implementatie van een verzameling met elkaar samenhangende projecten en activiteiten te co√∂rdineren, te sturen en te controleren teneinde te zorgen voor de realisatie van de eindresultaten en benefits die zijn gerelateerd aan de strategische doelstellingen van de organisatie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Omgevingsvergunning</td>
      <td><p>Vergunning als bedoeld in afdeling 5.1 van de Omgevingswet</p></td>
    </tr>
  </tbody>
</table>

### Complex datatype (GGM)

<figure align="center">
  <img width="229" src="2023-12-13_GGM_data-objecten/Complex_datatype__GGM_.svg" alt="Complex datatype (GGM)">
  <figcaption><i>Complex datatype (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Complex datatype</td>
      <td><p>846</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">BAGObjectnummering</td>
      <td><p>Unieke objectaanduiding van een object uit de BAG binnen een gemeente.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">CompositeID</td>
      <td><p>Unieke identificatie door het Kadaster toegekend. De identificatie heeft een opbouw conform NEN3610:2011 maar 
namespaces zijn onder beheer van kadaster (CDMKAD, delen van IMKAD) of Geonovum/NEN3610 (IMKAD).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">TypeBedrag</td>
      <td><p>Een hoeveelheid geld in cijfers in een bepaalde valuta.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">TypeBreuk</td>
      <td><p>De uitkomst van een deling van een geheel getal (de teller) door een ander geheel getal (de noemer).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">TypeKadastraleAanduiding</td>
      <td><p>De typering van de kadastrale aanduiding van een onroerende zaak conform Kadaster.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">TypeKadastraleAanduiding - Copy</td>
      <td><p>De typering van de kadastrale aanduiding van een onroerende zaak conform Kadaster.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">TypeKoopsom</td>
      <td><p>Hetbedrag, waarvoor één of meer onroerende zaken zijn verkregen, het koopjaar en een indicator of het meerdere onroerende goederen betreft.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">TypeLabel</td>
      <td><p>De tekst en positie van een label.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">TypeLabelpositie</td>
      <td><p>De positie van een label op de kaart, samengesteld uit plaatsingspunt en rotatiehoek.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">TypeLandinrichtingsrente</td>
      <td><p>De rente die berekend is over de percelen die in een herverkavelingblok van een landinrichtingsproject hebben 
gelegen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">TypeLandinrichtingsrente - Copy</td>
      <td><p>De rente die berekend is over de percelen die in een herverkavelingblok van een landinrichtingsproject hebben 
gelegen.</p></td>
    </tr>
  </tbody>
</table>

### Dienstverlening (GGM)

<figure align="center">
  <img width="1969" src="2023-12-13_GGM_data-objecten/Dienstverlening__GGM_.svg" alt="Dienstverlening (GGM)">
  <figcaption><i>Dienstverlening (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Dienstverlening</td>
      <td><p>13</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Afspraakstatus</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Aanvraagdata</td>
      <td><p>Bron: GEN<em>REQ</em>DATA
ID: REQ<em>DATA icm VELD</em>NAAM</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Formuliersoortveld</td>
      <td><p>Bron: GEM<em>VELD
ID: FORM</em>ID en VELD_NAAM</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Telefoonstatus</td>
      <td><ul>
 <li>ABANDONEDALERTING: “Opgehangen tijdens overgaan telefoon”</li>
 <li>DROPPEDCANCELED: “Opgehangen door systeem”</li>
 <li>ABANDONEDQUEUED: “Opgehangen tijdens wachten, zonder boodschap. ”</li>
 <li>CONNECTEDDIRECT: “Direct verbonden”</li>
 <li>CONNECTEDQUEUEDANNOUNCE: “Verbonden na wachtrij met boodschap”</li>
 <li>AbandonedQUEUEDANNOUNCE: “Opgehangen in wachtrij met boodschap”</li>
 <li>DroppedBusy: “Opgehangen door systeem, te druk”</li>
 <li>REJECTED: “Geweigerd door systeem”</li>
 <li>Droppedoverload: “Opgehangen door systeem vanwege overbelasting”</li>
</ul></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Onderwerp</td>
      <td><p>Bron: GEM<em>VJV</em>ONDERWERP
ID: ONDERWERP_ID</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Balieafspraak</td>
      <td><p>Balieafspraken zijn afspraken voor een klantcontact. Dit ongeacht of deze werkelijk heeft plaatsgevonden of gaat plaatsvinden, soms liggen deze in de toekomst of is iemand niet op komen dagen, of iets anders waardoor het klantcontact nog niet heeft plaatsgevonden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Formuliersoort</td>
      <td><p>Bron: GEM<em>FORM
ID: FORM</em>ID</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Artikel</td>
      <td><p>Tekst die is gemaakt om gepubliceerd te worden als een onafhankelijk deel van een tijdschrift, krant, encyclopedie of ander werk</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Telefoontje</td>
      <td><p>De telefoontjes zijn alle keren dat iemand naar de gemeente belt en het telefoonsysteem neemt deze telefoontjes aan. Ongeacht of iemand daarna ophangt, door het systeem uit de wachtrij wordt gezet, doorverbonden wordt met een derde partij of er werkelijk wordt opgenomen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">ProductOfDienst</td>
      <td><p>Bron: QP<em>CALENDAR.CFM</em>SERVICES</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Externe Bron</td>
      <td><p>Bron buiten de eigen organisatie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Telefoononderwerp</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">AanvraagOfMelding</td>
      <td><p>Komt overeen met een VJV</p>
<p>Bron: GEM<em>VJV (Distinct op REQ</em>ID)
ID: REQ_ID</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">MORAanvraagOfMelding</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">MEDEWERKER</td>
      <td><p><font color="#610e6a">Een medewerker van de organisatie die zaken behandelt uit hoofde van zijn of haar functie binnen een ORGANISATORISCHE EENHEID.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">ZAAK</td>
      <td><p><font color="#610e6a">Een samenhangende hoeveelheid werk met een welgedefinieerde aanleiding en een welgedefinieerd eindresultaat, waarvan kwaliteit en doorlooptijd bewaakt moeten worden.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">ZAAKTYPE</td>
      <td><p><font color="#610e6a">Generieke aanduiding van de aard van een zaak</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">VESTIGING VAN ZAAKBEHANDELENDE ORGANISATIE</td>
      <td><p><font color="#610e6a">Een VESTIGING van een onderneming of rechtspersoon zijnde de zaakbehandelende organisatie.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">DOCUMENT</td>
      <td><p><font color="#610e6a">Geheel van gegevens met een eigen identiteit ongeacht zijn vorm, met de bijbehorende metadata ontvangen of opgemaakt door een natuurlijke en/of rechtspersoon bij de uitvoering van taken, zijnde een ENKELVOUDIG DOCUMENT of een SAMENGESTELD DOCUMENT.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Klantcontact</td>
      <td><p>Klantcontacten zijn contactmomenten die werkelijk hebben plaatsgevonden, terwijl Balieafspraken afspraken zijn voor een klantcontact. Dit ongeacht of deze werkelijk heeft plaatsgevonden, soms liggen deze in de toekomst of is iemand niet op komen dagen, of iets anders waardoor het klantcontact nog niet heeft plaatsgevonden.</p>
<p>Hetzelfde geldt voor de telefoontjes, de klantcontacten komen uit levelOneData, dat zijn alle telefoontjes die werkelijk met een medewerker (of een gedelegeerde) hebben plaatsgevonden (soms zelfs meerdere binnen 1 telefoontje).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Indiener</td>
      <td><p>Persoon die meldiing of aanvraag doet</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">AOMstatus</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Melding</td>
      <td><p>De betekenisvolle formulering van een waargenomen feit, waaraan een waarde kan worden toegekend</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">AOM_MeldingWmoJeugd</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">AOM_AanvraagWmoJeugd</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">VTH-Melding</td>
      <td><p>Melding met betrekking tot Vergunningen, Toezicht en Handhaving</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">WoonoverlastAanvraagOfMelding</td>
      <td><p>Melding of aanvraag met betrekking tot Woonoverlast</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">WoonfraudeAanvraagOfMelding</td>
      <td><p>Melding of aanvraag van woonfraude</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">VOMAanvraagOfMelding</td>
      <td><p>VOM staat voor Vergunning, Ontheffing of Melding. Het betreft hier een melding of een aanvraag voor een vergunning of een ontheffing.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">MORAanvraagOfMelding</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Batch</td>
      <td><p>Verzameling van posten die in het kader van automatische verwerking een logisch geheel vormen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">AanvraagOfMelding</td>
      <td><p>Komt overeen met een VJV</p>
<p>Bron: GEM<em>VJV (Distinct op REQ</em>ID)
ID: REQ_ID</p></td>
    </tr>
  </tbody>
</table>

### Dimensies (GGM)

<figure align="center">
  <img width="547" src="2023-12-13_GGM_data-objecten/Dimensies__GGM_.svg" alt="Dimensies (GGM)">
  <figcaption><i>Dimensies (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Archiefstuk</td>
      <td><p>Bijeengebrachte informatie, ongeacht het medium, die wordt gecre√´erd, ontvangen en gearchiveerd door een bureau, een instelling, een organisatie of een individu met het oog op het nakomen van wettelijke verplichtingen of het uitvoeren van zakelijke transacties.(AAT)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Archief</td>
      <td><p>De bewaarplaats van belangrijke gegevens die zijn vastgelegd in documentvorm alsook de verzameling van documenten die voor een bepaald doel vervaardigd zijn.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Begroting</td>
      <td><p>Een overzicht van de verwachte ontvangsten en voorziene uitgaven voor een bepaalde (meestal toekomstige) periode zodat hier een afstemming tussen plaats kan vinden om eventuele tekorten en overschotten vroegtijdig in kaart te kunnen brengen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Hoofdstuk</td>
      <td><p>Onderdeel van een langere tekst.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Dimensies</td>
      <td><p>376</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Periode</td>
      <td><p>bepaalde tijdsduur.</p></td>
    </tr>
  </tbody>
</table>

### Economie (GGM)

<figure align="center">
  <img width="1273" src="2023-12-13_GGM_data-objecten/Economie__GGM_.svg" alt="Economie (GGM)">
  <figcaption><i>Economie (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Economie</td>
      <td><p>535</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Hotel</td>
      <td><p>Gebouw waar je tegen betaling kunt logeren.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Hotelbezoek</td>
      <td><p>Verblijf in een hotel</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Contact</td>
      <td><p>Persoon waarmee communicatie plaatsvindt</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verkooppunt</td>
      <td><p>Locatie waar iets wordt verkocht</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Werkgelegenheid</td>
      <td><p>De vraag naar arbeid, te berekenen door de totale productie te delen door de arbeidsproductiviteit per persoon.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Winkelvloeroppervlak</td>
      <td><p>Gemeten oppervlakte in vierkante meters van een winkel</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">NATUURLIJK PERSOON</td>
      <td><p>Een INGESCHREVEN PERSOON of ANDER NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">GEBOUWD OBJECT</td>
      <td><p>Een VERBLIJFSOBJECT of een OVERIG GEBOUWD OBJECT</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">VESTIGING</td>
      <td><p>Een gebouw of complex van gebouwen waar duurzame uitoefening van de activiteiten van een onderneming of rechtspersoon plaatsvindt.</p></td>
    </tr>
  </tbody>
</table>

### Enumeratiesoort (GGM)

<figure align="center">
  <img width="547" src="2023-12-13_GGM_data-objecten/Enumeratiesoort__GGM_.svg" alt="Enumeratiesoort (GGM)">
  <figcaption><i>Enumeratiesoort (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Klantcontact</td>
      <td><p>Klantcontacten zijn contactmomenten die werkelijk hebben plaatsgevonden, terwijl Balieafspraken afspraken zijn voor een klantcontact. Dit ongeacht of deze werkelijk heeft plaatsgevonden, soms liggen deze in de toekomst of is iemand niet op komen dagen, of iets anders waardoor het klantcontact nog niet heeft plaatsgevonden.</p>
<p>Hetzelfde geldt voor de telefoontjes, de klantcontacten komen uit levelOneData, dat zijn alle telefoontjes die werkelijk met een medewerker (of een gedelegeerde) hebben plaatsgevonden (soms zelfs meerdere binnen 1 telefoontje).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">GEBOUWD OBJECT</td>
      <td><p>Een VERBLIJFSOBJECT of een OVERIG GEBOUWD OBJECT</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Enumeratiesoort</td>
      <td><p>1038</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Geslachtsaanduiding MEDEWERKER</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Soorten Klantcontact</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vertrouwelijk aanduiding DOCUMENT</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vervalreden BESLUIT</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Boolean</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Gezinsrelatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Huishoudensoort</td>
      <td><p><b>Definitie</b>:</p>
<p>Typering van het huishouden naar grootte en verbondenheid.</p>
<p><b>Toelichting</b>:</p>
<p>Voor de definities van institutioneel huishouden en particulier huishouden: zie de toelichting bij het objecttype Huishouden. Onder Thuiswonende kinderen wordt verstaan: alle in het huishouden van hun ouder(s) aanwezige eigen, pleeg-, stief- of adoptiekinderen die ongehuwd zijn en zelf geen kinderen hebben (CBS, Huishoudensprognose 1996). In een adresseerbaar object kunnen één of meer huishoudens wonen. In de tabel worden de huishoudens gekarakteriseerd, uitgaande van de CBS-Huishoudensprognose. Tot de categorie Overig particulier huishouden behoren bijvoorbeeld: een woongroep, studenten die gezamenlijk een huishouden vormen, een kamerbewoner die in zijn eigen onderhoud voorziet, twee zussen die samenwonen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">aanduidingEigenaarGebruiker</td>
      <td><p>Een aanduiding van alle waarden waarmee soort belang van een eigenaar / gebruiker wordt aangeduid.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">aanduidingInhoudingVermissingReisdocument</td>
      <td><p>De mogelijke waarden van de aanduiding van inhouding of vermissing van een Nederlands reisdocument. 
Zie logisch ontwerp BRP bij de stamtabellen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">aangever</td>
      <td><p>De aangever adreshouding mag alleen een binnen de centrale voorzieningen voorgedefinieerde waarde hebben. Zie logisch ontwerp BRP bij de stamtabellen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">burgelijkeStaat</td>
      <td><p>Een aanduiding van alle waarden die een burgelijke staat kan aannemen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">adelijkeTitel</td>
      <td><p>Zie logisch ontwerp BRP bij de stamtabellen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">bouwkundigeBestemming</td>
      <td><p>Een aanduiding van alle waarden waarmee de bouwkundige bestemming van een gebouwd object kan worden verbijzonderd</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">bronAdresBuitenland</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">codeExploitant</td>
      <td><p>De verschillende rechten voor exploitatie van een perceel in eigendom van de gemeenten</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">functieOndersteunendWegdeel</td>
      <td><p>Een aanduiding van alle waarden waarmee de functie van een ondersteunend wegdeel kan worden verbijzonderd</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">functieOndersteunendWegdeelPlus</td>
      <td><p>De verschillende  waarden waarmee een nadere classificatie van de functie van een ondersteunend wegdeel kan worden aangegeven.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">functieSpoor</td>
      <td><p>Een aanduiding van alle waarden waarmee de functie van een spoor kan worden verbijzonderd</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">functieWeg</td>
      <td><p>Een aanduiding van alle waarden waarmee het hoofdgebruiksdoel van een weg kan worden verbijzonderd</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">functieWegPlus</td>
      <td><p>De verschillende waarden waarmee een nadere categorisering van het gebruiksdoel van een weg kan worden verbijzonderd</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">fysiekVoorkomenBegroeidTerrein</td>
      <td><p>Een aanduiding van alle waarden waarmee het fysiek voorkomen van een begroeid terrein kan worden verbijzonderd</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">fysiekVoorkomenBegroeidTerreinPlus</td>
      <td><p>De verschillende waarden waarmee een nadere categorisering van het fysiek voorkomen van een begroeid terrein kan worden verbijzonderd</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">fysiekVoorkomenOnbegroeidTerrein</td>
      <td><p>Een aanduiding van alle waarden waarmee het fysiek voorkomen van een onbegroeid terrein kan worden verbijzonderd</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">fysiekVoorkomenOnbegroeidTerreinPlus</td>
      <td><p>Een aanduiding van alle waarden waarmee een nadere categorisering van het fysiek voorkomen van een onbegroeid terrein kan worden verbijzonderd</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">fysiekVoorkomenOndersteunendWegdeel</td>
      <td><p>Een aanduiding van alle waarden die de mate waarin een ondersteunend wegdeel al of niet verhard is weergeven</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">fysiekVoorkomenOndersteunendWegdeelPlus</td>
      <td><p>De verschillend waarden die een nadere classificatie van de mate waarin een ondersteunend wegdeel al of niet verhard is, kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">fysiekVoorkomenWeg</td>
      <td><p>Een aanduiding van alle waarden waarmee het fysiek voorkomen van een weg kan worden verbijzonderd</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">fysiekVoorkomenWegPlus</td>
      <td><p>De verschillende waarden die een nadere classificatie van de mate waarin een wegdeel al of niet verhard is, kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">gebruiksdoel</td>
      <td><p>Een aanduiding va alle waarden waarmee het gebruiksdoel van een object kan 
worden verbijzonderd.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">geslacht</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">inwinningsmethodeOppervlakte</td>
      <td><p>Een codering van de verschillende waarden die de inningswijze van een verkrijging oppervlakte kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">inwinningsmethodeGeometrie</td>
      <td><p>Een codering van de verschillende waarden die de inwinning geometrie kan aannemen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">naamgebruik</td>
      <td><p>De voorgedefinieerde waarden van naamgebruik volgens de centrale voorzieningen. Zie attribuut <i>Naamgebruik</i> van groep A.1.12 Naamgebruik van BRP.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">ontsluitingswijzeVerdieping</td>
      <td><p>De verschillende waarden die de ontsluiting van een verdieping kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">predicaat</td>
      <td><p>Een erenaam of betiteling van een persoon zoals die voorkomen in de centrale voorzieningen. Zie logisch ontwerp BRP bij de stamtabellen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">redenEindeRelatie</td>
      <td><p>De mogelijke redenen voor het beëindigen van een huwelijk of geregistreerd partnerschap. Zie logisch ontwerp BRP bij de stamtabellen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">redenWijzigingAdres</td>
      <td><p>De aanduiding waarom het adres is gewijzigd.Zie logisch ontwerp BRP bij de stamtabellen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">soortBewind</td>
      <td><p>Een aanduiding van de soorten bewind  waaronder een niet natuurlijke persoon kan staan.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">soortBijzondereRechtstoestandNatuurlijkPersoon</td>
      <td><p>Een aanduiding van de bijzondere rechtstoestanden waarin een natuurlijke persoon kan verkeren</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">soortBijzondereRechtstoestandNietNatuurlijkPersoon</td>
      <td><p>Een aanduiding van de bijzondere rechtstoestanden waarin een niet natuurlijke persoon kan verkeren</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">soortGebruik</td>
      <td><p>Typering van het WOZ-object naar soorten gebruik</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">soortMigratie</td>
      <td><p>A.1.23. Soort migratie van BRP</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">soortPubliekrechtelijkRechtsvorm</td>
      <td><p>Door de Kamers van Koophandel vastgestelde publiekrechtelijk rechtsvormen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">soortRechtsvorm</td>
      <td><p>Door de Kamers van Koophandel vastgestelde rechtsvormen van binnenlandse rechtspersonen (in oprichting), samenwerkingsverbanden en buitenlandse vennootschap met een onderneming of vestiging in Nederland</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">soortWoonobject</td>
      <td><p><font color="#0f0f0f">De verschillende waarden die een soort woonobject kan aannemen.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">statusWOZ-Beschikking</td>
      <td><p><font color="#0f0f0f">De verschillende waarden die de status van een beschikking waarmee de waarde is vastgesteld, kan aannemen.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">statusGeoObject</td>
      <td><p>Een aanduiding van alle waarden van de status  die een geo-object kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">StatLigplaatsStandplaats</td>
      <td><p>Een aanduiding van alle waarden die de status van een lig- of standplaats<br />
kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">statusNummeraanduiding</td>
      <td><p>Een aanduiding van alle  fases van de levenscyclus  die een  nummeraanduiding kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">statusOpenbareRuimte</td>
      <td><p>Een aanduiding van alle fasen van de levenscyclus die een openbare ruimte kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">statusPand</td>
      <td><p>De verschillende waarden die de status van een pand kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">statusVerblijfsobject</td>
      <td><p>Een aanduiding van alle waarden die de status van een verblijfsobject kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">statusVoortgangBouw</td>
      <td><p>Een aanduiding van alle fases die de voortgang bouw pand kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">statusWoonplaats</td>
      <td><p>Een aanduiding van alle waarden die de status van een woonplaats 
kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">statusWOZ(Deel)Object</td>
      <td><p>Een aanduiding van alle  fasen van de levenscyclus van WOZ-(deel)objecten</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">typeOverbrugging</td>
      <td><p>Een codering van de verschillende waarden die de typering van een overbrugging kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">typeringAppartementsrechtsplitsing</td>
      <td><p>De verschillende waarden die de typering van appartementsrechtsplitsingen kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">typeringFunctie</td>
      <td><p>De verschillende waarden die een type functie conform KvK kan aannemen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">typeringFunctionaris</td>
      <td><p>De verschillende waarden die een type functionaris conform KvK kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">typeringFunctioneelGebied</td>
      <td><p>De verschillende waarden die de typering  van het functioneel gebied kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">typeringGebouwinstallatie</td>
      <td><p>De verschillende waarden die de typering van een gebouwinstallatie kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">typeringIngeschrevenNietNatuurlijkPersoon</td>
      <td><p>De verschillende waarden die de typering van een ingeschreven niet natuurlijk personen conform KvK kan aannemen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">typeringInrichtingselement</td>
      <td><p><font color="#0f0f0f">De verschillende waarden die de typering van het inrichtingselement kan aannemen.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">typeringKunstwerk</td>
      <td><p>De verschillende waarden die de typering van het kunstwerk kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">typeringInrichtingselementPlus</td>
      <td><p>De verschillende waarden die een nadere categorisering van een type inrichtingselement kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">typeObjectcode</td>
      <td><p>Codering van de binnen de BAG onderscheiden objecttypen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">typeringOndersteunendWater</td>
      <td><p>De verschillende waarden die de typeringen van het  ondersteunend water kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">typeringOndersteunendWaterPlus</td>
      <td><p>De verschillende waarden die een nadere classificatie van de typering van het ondersteunend water kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">typeringOpenbareRuimte</td>
      <td><p>De verschillende waarden die de typering van een openbare ruimte kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">typeringOverbruggingsdeel</td>
      <td><p>De verschillende waarden die de typering van een  onderdeel van een brugconstructie kan aannemen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">typeringOverigBouwwerk</td>
      <td><p>De verschillende waarden die de typering van een overig bouwwerk kan aannemen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">typeringOverigeScheiding</td>
      <td><p>De verschillende waarden die de typering van een overige scheiding kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">typeringScheiding</td>
      <td><p>De verschillende waarden die de typering van een  scheiding kan aannemen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">typeringVegetatieobject</td>
      <td><p>De verschillende waarden die de typeringen van een  vrijstaande vegetatieobject kan aannemen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">typeringWater</td>
      <td><p>De verschillende waarden die de typering van het water kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">typeringWaterPlus</td>
      <td><p>De verschillende waarden die een nadere categorisering van een type water kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">typeringZekerheidsrecht</td>
      <td><p>De verschillende waarden die de typering van het zekerheidsrecht kan aannemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_AanOfVrijliggend</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Afmeting</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Bedienaar</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Beheergebied</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_BeheerobjectGebruiksfunctie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Belasting</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_BelastingklasseNieuw</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_BelastingklasseOud</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Beleidsstatus</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_BeoogdeOmlooptijd</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Bereikbaarheid</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_BereikbaarheidKolk</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Boombeeld</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Boomgroep</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_BoomhoogteklasseActueel</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_BoomTypeBeschermingsstatusPlus</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Boomveiligheidsklasse</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Boomvoorziening</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_BreedteklasseHaag</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Certificeringsinstantie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Constructielaagsoort</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Constructietype</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Controlefrequentie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_CultuurhistorischWaardevol</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Doelsoort</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Fabrikant</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Formaat</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_FunderingLeiding</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Gebiedstype</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_GewenstSluitingspercentage</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Groeifase</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_GroenobjectBereikbaarheidPlus</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Grondsoort</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_GrondsoortPlus</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_HoogteklasseHaag</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_IMKLThema</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Installateur</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Kleur</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_KroondiameterklasseActueel</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_KwaliteitsniveauGewenst</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Kweker</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_LengteKunstgras</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Leverancier</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_LiningType</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Markeringsbreedte</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Markeringsoort</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Markeringspatroon</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Materiaal</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Ondergroei</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Onderhoudsplichtige</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Onderhoudsregime</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Ondersteuningsvorm</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_OriÃ«ntatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_OverbruggingsobjectModaliteit</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_PlaatsoriÃ«ntatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_RioolputConstructieonderdeel</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Snoeifase</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Soortnaam</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_SoortPlantenbak</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_SoortVoeg</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_SpeelterreinLeeftijdDoelgroep</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_SpeeltoestelToestelonderdeel</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_SportterreinTypeSport</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Stamdiameterklasse</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Status</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TakvrijeStam</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Taludsteilte</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Toestelgroep</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Type</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeAfdekking</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeAsbesthoudend</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeBediening</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeBeheerder</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeBeheerderPlus</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeBeschermingsstatus</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeBewerking</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeBouwdeel</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeBovenkantKademuur</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeCommunicatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeConstructie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeDeurbediening</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeEigenaar</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeEigenaarPlus</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeElement</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeFundering</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeLigging</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeMantel</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeMonument</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeNivelleerschijf</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeOmgevingsrisicoklasse</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeOnderdeelMetPomp</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypePlus</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeSlot</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeStandplaats</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeStandplaatsPlus</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeTeerhoudend</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeVaarwater</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeVermeerderingsvorm</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeVoeg</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeVoegvulling</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeWaaier</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_TypeWaterplant</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Vegen</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Verbindingstype</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_VerhardingsobjectWegfunctie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Vorm</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_VrijeDoorrijhoogte</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_VrijeTakval</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_VulmateriaalKunstgras</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Waterdoorlatendheid</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_WegasTypeRoute</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_WegcategorieDV</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_WegtypeBestaand</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_Zettingsgevoeligheid</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">enum_ZettingsgevoeligheidPlus</td>
      <td></td>
    </tr>
  </tbody>
</table>

### Financien (GGM)

<figure align="center">
  <img width="2983" src="2023-12-13_GGM_data-objecten/Financien__GGM_.svg" alt="Financien (GGM)">
  <figcaption><i>Financien (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Leverancier</td>
      <td><p>Een niet-natuurlijk persoon die een product of dienst levert aan de organisatie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Betaling</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Periode</td>
      <td><p>bepaalde tijdsduur.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Functie</td>
      <td><p>Een samenhangende verzameling van rollen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">RECHTSPERSOON</td>
      <td><p>Een NATUURLIJK PERSOON of een NIET-NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Financien</td>
      <td><p>71</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bankrekening</td>
      <td><p>Een rekening-courant bij een bank</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bankafschrift</td>
      <td><p>Overzicht van de bij- en afschrijvingen van een rekening</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bankafschriftregel</td>
      <td><p>Een item op het bankafschrift</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bedrijf</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Begroting</td>
      <td><p>Een overzicht van de verwachte ontvangsten en voorziene uitgaven voor een bepaalde (meestal toekomstige) periode zodat hier een afstemming tussen plaats kan vinden om eventuele tekorten en overschotten vroegtijdig in kaart te kunnen brengen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Begrotingregel</td>
      <td><p>Een item op de begroting</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Activa</td>
      <td><p>Bezittingen van een onderneming op een boekhoudkundige balans</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Activasoort</td>
      <td><p>Typering van activa</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Doelstelling</td>
      <td><p>Een op korte of middellange termijn nagestreefde situatie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Opdrachtgever</td>
      <td><p>Persoon die een opdracht verstrekt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Hoofdrekening</td>
      <td><p>is kostensoort</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Subrekening</td>
      <td><p>Ondergeschikte rekening van een hoofdrekening</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Debiteur</td>
      <td><p>Iemand aan wie een dienst of product geleverd is waardoor recht op een vergoeding is ontstaan</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Factuur</td>
      <td><p>Schriftelijke rekening of nota voor de geleverde zaken of verrichte diensten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Hoofdstuk</td>
      <td><p>Onderdeel van een langere tekst.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Werkorder</td>
      <td><p>Opdracht voor de uitvoering van een activiteit of een stap in een proces.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Product</td>
      <td><p>Het resultaat van een proces dat in het economisch verkeer een waarde bezit.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Opdrachtnemer</td>
      <td><p>Partij die een opdracht aanvaardt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Mutatie</td>
      <td><p>Wijziging van een situatie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Inkooporder</td>
      <td><p>Een opdracht (gezien vanuit de klant) voor √©√©n of meer leveringen door de leverancier aan die klant van een bepaalde hoeveelheid gespecificeerde goederen en/of diensten onder overeengekomen leveringsvoorwaarden en prijzen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Factuurregel</td>
      <td><p>Een item op de factuur</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Batch</td>
      <td><p>Verzameling van posten die in het kader van automatische verwerking een logisch geheel vormen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Batchregel</td>
      <td><p>Een item uit een batch</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Kostenplaats</td>
      <td><p>Rekening waaraan boekingen in een financi√´le administratie samen worden toegeschreven.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Taakveld</td>
      <td><p>Een samenhangend geheel van activiteiten en taken en hangt onder een programma.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Applicatie</td>
      <td><p>Een applicatiecomponent die gericht is op het ondersteunen van eindgebruikers.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Externe Bron</td>
      <td><p>Bron buiten de eigen organisatie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Programma</td>
      <td><p>Een tijdelijke, flexibele organisatiestructuur, die is opgezet om de implementatie van een verzameling met elkaar samenhangende projecten en activiteiten te co√∂rdineren, te sturen en te controleren teneinde te zorgen voor de realisatie van de eindresultaten en benefits die zijn gerelateerd aan de strategische doelstellingen van de organisatie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Formulier Verlenging Inhuur</td>
      <td><p>Formulier ten behoeve van verlenging inhuur personeel</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Vastgoedobject</td>
      <td><p>Perceel of vastgoed waar de gemeente een zakelijk recht heeft, en optioneel verhuurd, verpacht of anderzinds aan een derde partij.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Contract</td>
      <td><p>Bindende overeenkomst</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">ORGANISATORISCHE EENHEID</td>
      <td><p><font color="#610e6a">Het deel van een functioneel afgebakend onderdeel binnen de organisatie dat haar activiteiten uitvoert binnen een VESTIGING VAN ZAAKBEHANDELENDE ORGANISATIE en die verantwoordelijk is voor de behandeling van zaken.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Aanvraag Inkooporder</td>
      <td><p>het betreft hier het formulier 'Aanvraag Inkooporder'</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Inkooppakket</td>
      <td><p>Standaard indeling om de werken, diensten en leveringen die de aanbestedende dienst helpt bij het structureren van haar uitgaven. Samenhangende leveringen, diensten en producten zijn hierin gegroepeerd.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Subsidie</td>
      <td><p>Aan derden toegekende financiele middelen, bestemd voor het uitvoeren van bepaalde activiteiten</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Werkbon</td>
      <td><p>Document waarin een heoveelheid werk is beschreven</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Subsidiecomponent</td>
      <td><p>Onderdeel van een subisidie met een eigen kostenplaats.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Verplichting WMO Jeugd</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Formulier Inhuur</td>
      <td><p>Formulier ten behoeve van inhuur personeel</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Project</td>
      <td><p>Geheel van activiteiten uitgevoerd in een tijdelijk samenwerkingsverband gericht op het binnen bepaalde randvoorwaarden (bv. tijd, geld) bereiken van een vooraf gedefinieerd resultaat.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Zakelijk Recht</td>
      <td><p>Geeft een recht op een goed, zoals een onroerende zaak of een roerende zaak.</p></td>
    </tr>
  </tbody>
</table>

### Gemeentebegrafenissen (GGM)

<figure align="center">
  <img width="547" src="2023-12-13_GGM_data-objecten/Gemeentebegrafenissen__GGM_.svg" alt="Gemeentebegrafenissen (GGM)">
  <figcaption><i>Gemeentebegrafenissen (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Gemeentebegrafenissen</td>
      <td><p>406</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Gemeentebegrafenis</td>
      <td><p>Teraardebestelling onder verantwoordelijjkheid van de gemeente.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">NATUURLIJK PERSOON</td>
      <td><p>Een INGESCHREVEN PERSOON of ANDER NATUURLIJK PERSOON</p></td>
    </tr>
  </tbody>
</table>

### Generiek (GGM)

<figure align="center">
  <img width="1561" src="2023-12-13_GGM_data-objecten/Generiek__GGM_.svg" alt="Generiek (GGM)">
  <figcaption><i>Generiek (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Beschermde Status</td>
      <td><p>Status van de bescherming van een monument. Een monument / erfgoed is een overblijfsel van kunst, cultuur, architectuur of nijverheid dat van algemeen belang wordt geacht vanwege de historische, volkskundige, artistieke, wetenschappelijke, industrieel-archeologische of andere sociaal-culturele waarde. Vormen van monument / erfgoed met de status rijks- provinciaal- of gemeentelijke monument / erfgoed zijn beschermd op grond van een besluit van respectievelijk het Ministerie OCW, de provincie of de gemeente,</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">VTH-Melding</td>
      <td><p>Melding met betrekking tot Vergunningen, Toezicht en Handhaving</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Toepasbare Regel</td>
      <td><p><i>Vanwege de leesbaarheid wordt gewerkt met de term Toepasbare regel ipv regelbeheersobject</i>
<i>
</i><i>Een regelbeheerobject heeft een koppeling met een samenhangende set met regels om een afleiding te kunnen doen. Het regelbeheerobject ‘conclusie gevelaanpassing’ kan een vraag beantwoorden zoals: “Heb ik een vergunning nodig voor het veranderen van een kozijn, kozijninvulling of gevelpaneel”. Het regelbeheerobject ‘melding lozing’ beantwoordt de vraag “Wat moet ik aan informatie (gegevens en documenten) aanleveren als ik ga lozen vanuit particuliere huishoudens”. Het regelbeheerobject “Opslaan van gasolie smeerolie of afgewerkte olie in een bovengrondse opslagtank” </i>geeft aan welke maatregelen genomen dienen te worden.
Het regelbeheerobject is onderdeel van de functionele structuur. De set met regels is gedefinieerd in het Toepasbare regelbestand<sup>2</sup>.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Juridische Regel</td>
      <td><p>De beschrijving van een regel met juridische werkingskracht. Een regel betreft binnen de Omgevingswet veelal activiteiten, en/of normen en/of functies en/of beperkingengebieden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Verzoek</td>
      <td><p>Een vraag aan het bevoegd gezag om een speficieke product of dienst te leveren.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Normwaarde</td>
      <td><p>√â√©n van de kwantitatieve of kwalitatieve waarden van een norm. De normwaarde geeft aan wat de specifieke kwantitatieve of kwalitatieve eisen zijn, inclusief de toewijzing ervan aan de specifieke locatie(s) waar de normwaarde voor geldt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Generiek</td>
      <td><p>385</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Foto</td>
      <td><p>Afbeelding op een plat vlak vervaardigd door middel van fotografie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Gebiedengroep</td>
      <td><p>Verzameling van gebieden</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Gebied</td>
      <td><p>Een aaneengesloten gedeelte van een wijk, waarvan de grenzen zo veel mogelijk gebaseerd zijn op topografische elementen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Locatie</td>
      <td><p>De locatie beschrijft middels co√∂rdinaten de ruimtelijke dimensie of ruimtelijke afbakening van een regel of van een objecttype die in de regel beschreven wordt. (CIMOW)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Lijn</td>
      <td><p>Denkbeeldige streep op de aardoppervlakte</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Lijnengroep</td>
      <td><p>Verzameling van lijnen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Puntengroep</td>
      <td><p>Verzameling van punten</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Punt</td>
      <td><p>Plaats in de ruimte</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Video-opname</td>
      <td><p>Opnametechniek om bewegende beelden als een elektronisch signaal te registreren en weer te geven.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Erfgoed Object</td>
      <td><p>Uit het verleden ge√´rfde materi√´le en immateri√´le objecten</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Activiteit</td>
      <td><p>Ieder menselijk handelen waarbij, of ieder menselijk nalaten waardoor een verandering of effect in de (fysieke) leefomgeving wordt of kan worden bewerkstelligd.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Regeltekst</td>
      <td><p>De kleinste zelfstandige eenheid van (een of meer) bij elkaar horende juridische regels: een artikel en lid.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Projectlocatie</td>
      <td><p>Fysieke locatie waar een project betrekking op heeft of wordt uitgevoerd.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Gebiedsaanwijzing</td>
      <td><p>Functie of een Beperkingengebied, met een verwijzing naar locatie, veelal een gebied, waarbij aangegeven wordt hoe het gebied beschouwd wordt vanuit de bijbehorende regels.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Agendapunt</td>
      <td><p>Een onderwerp dat in de vergadering wordt behandeld.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Vergadering</td>
      <td><p>Een bijeenkomst van meerdere mensen (meestal van eenzelfde organisatie) die met elkaar spreken en/of afspraken maken over de gemeenschappelijke toekomst.</p></td>
    </tr>
  </tbody>
</table>

### Generieke Entiteiten Erfgoed (GGM)

<figure align="center">
  <img width="1561" src="2023-12-13_GGM_data-objecten/Generieke_Entiteiten_Erfgoed__GGM_.svg" alt="Generieke Entiteiten Erfgoed (GGM)">
  <figcaption><i>Generieke Entiteiten Erfgoed (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">NATUURLIJK PERSOON</td>
      <td><p>Een INGESCHREVEN PERSOON of ANDER NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Tentoonstelling</td>
      <td><p>Een uitstalling van voorwerpen om door het grote publiek bekeken te worden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Archiefstuk</td>
      <td><p>Bijeengebrachte informatie, ongeacht het medium, die wordt gecre√´erd, ontvangen en gearchiveerd door een bureau, een instelling, een organisatie of een individu met het oog op het nakomen van wettelijke verplichtingen of het uitvoeren van zakelijke transacties.(AAT)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Foto</td>
      <td><p>Afbeelding op een plat vlak vervaardigd door middel van fotografie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Video-opname</td>
      <td><p>Opnametechniek om bewegende beelden als een elektronisch signaal te registreren en weer te geven.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Generieke Entiteiten Erfgoed</td>
      <td><p>605</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Erfgoed Object</td>
      <td><p>Uit het verleden ge√´rfde materi√´le en immateri√´le objecten</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">ObjectClassificatie</td>
      <td><p>Systematische identificatie en ordening van objecten in categorie√´n overeenkomstig logisch gestructureerde conventies, methoden en procedureregels weergegeven in een classificatiesysteem.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Historisch Persoon</td>
      <td><p>Natuurlijk persoon waarvan informatie beschikbaar is uit het verleden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Historische Rol</td>
      <td><p>Rol waarvan informatie beschikbaar is uit het verleden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Auteur</td>
      <td><p>De persoon die verantwoordelijk is voor de inhoud van een (digitaal) document</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Museumobject</td>
      <td><p>Beschrijving van een fenomeen in de werkelijkheid met een zekere cultuurhistorische waarde die deel uitmaakt van de culthuurhistorisch object index. Een museum object kan gedifini√´erd worden als een object met betrekking tot gebouwd, archeologisch, roerend of cultuurlandschappelijk erfgoed. Denk hierbij bijvoorbeeld aan een gebouwd of archeologisch rijksmonument, een schilderij of een beschermd stads- of dorpsgezicht.</p></td>
    </tr>
  </tbody>
</table>

### Generiek Jeugd en Wmo (GGM)

<figure align="center">
  <img width="5071" src="2023-12-13_GGM_data-objecten/Generiek_Jeugd_en_Wmo__GGM_.svg" alt="Generiek Jeugd en Wmo (GGM)">
  <figcaption><i>Generiek Jeugd en Wmo (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">AanvraagOfMelding</td>
      <td><p>Komt overeen met een VJV</p>
<p>Bron: GEM<em>VJV (Distinct op REQ</em>ID)
ID: REQ_ID</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">RECHTSPERSOON</td>
      <td><p>Een NATUURLIJK PERSOON of een NIET-NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Contract</td>
      <td><p>Bindende overeenkomst</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Inkooporder</td>
      <td><p>Een opdracht (gezien vanuit de klant) voor √©√©n of meer leveringen door de leverancier aan die klant van een bepaalde hoeveelheid gespecificeerde goederen en/of diensten onder overeengekomen leveringsvoorwaarden en prijzen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Generiek Jeugd en Wmo</td>
      <td><p>448</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Beperkingscategorie</td>
      <td><p>Een categorisering van beperkingen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">AOM_MeldingWmoJeugd</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">AanvraagDelftpas</td>
      <td><p>Te specifiek. AanvraagGemeentepas</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Score</td>
      <td><p>Het aantal behaalde punten</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Beperking</td>
      <td><p>Een stoornis of conditie ‚Äì lichamelijk, zintuiglijk en-of geestelijk ‚Äì die een normaal maatschappelijk functioneren belemmert en nadelige sociale gevolgen met zich meebrengt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Beperkingscore</td>
      <td><p>Getalsmatige duiding van een beperking</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Beperkingscoresoort</td>
      <td><p>Typering van beperkingscores</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Leveringsvorm</td>
      <td><p>Een van de vormen waarin Wlz-zorg geleverd kan worden, namelijk verblijf in een instelling of zorg thuis via een Volledig Pakket Thuis (VPT) of een Modulair Pakket Thuis (MPT) als zorg in natura (ZIN), via een persoonsgebonden budget (pgb) of via een combinatie van pgb en MPT.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Beschikkingsoort</td>
      <td><p>Typering van een beschikking</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Leefgebied</td>
      <td><p>Gebied waarin alle activiteiten van een inwoner zich kunnen afspelen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Delftpas</td>
      <td><p>Te specifiek, voorstel "gemeentepas"?</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Zelfredzaamheidmatrix</td>
      <td><p>Een geordend systeem waarbij aan elf domeinen van het dagelijks leven (zoals inkomen en dagbesteding; zie figuur) een waarde voor zelfredzaamheid wordt toegekend.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Scoresoort</td>
      <td><p>Typologie van score</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Team</td>
      <td><p>Een groep personen die door middel van samenwerking een gezamenlijk doel nastreeft, waarbij de teamleden afhankelijk van elkaar zijn om het doel te bereiken.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">PGB-Toekenning</td>
      <td><p>Betreft alleen toegekende voorzieningen met als leveringsvorm PGB
Opgebouwd op basis van het TKB (Toekenninsgbericht) aan het SVB, en het BAB-bericht (budgetafsluiting). zie: https://istandaarden.nl/istandaarden/ipgb</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Budgetuitputting</td>
      <td><p>Overzicht van de te verwachte inkomsten en uitgaven over een bepaalde periode</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Huishouden</td>
      <td><p>persoon of groep personen die een huishouden voert waarbij sprake is van een onderlinge verbondenheid en continu√Øteit in de samenstelling ervan, die binnen een woning gebruik maakt van dezelfde voorzieningen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Beschikte Voorziening</td>
      <td><p>Een voorziening waarover een beschikking is gedaan.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">AOM_AanvraagWmoJeugd</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Melding Eigen bijdrage</td>
      <td><p>Aangifte van de evetuele eigen bijdrage</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Beschikking</td>
      <td><p>In het bestuursrecht: Een beslissing van een overheidsorgaan in een concreet geval, bijvoorbeeld het verlenen van een bouwvergunning. In het civiele recht: een rechterlijke uitspraak in een procedure die begint met een verzoekschrift.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Relatie</td>
      <td><p>Betrekking waarin personen, zaken, begrippen of grootheden van nature tot elkaar staan.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Relatiesoort</td>
      <td><p>De typering van het structurele verband tussen een object van een objecttype en een (ander) object van een ander (of hetzelfde) objecttype.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Declaratieregel</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Declaratie</td>
      <td><p>Een opgave van te vergoeden kosten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Leverancier</td>
      <td><p>Een niet-natuurlijk persoon die een product of dienst levert aan de organisatie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verplichting WMO Jeugd</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Clientbegeleider</td>
      <td><p>De persoon die verantwoordelijk is voor het opstellen en uitvoeren van het  ondersteuningsplan in samenwering met de client en personen uit zijn/haar omgeving .</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Toewijzing</td>
      <td><p>Toewijzing die door gemeente aan zorgaanbieder wordt gestuurd. zie https://informatiemodel.istandaarden.nl/2019/views/view_274300.html</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Levering</td>
      <td><p>Levering van zorg door leverancier. Is in het geval van resultaatverplichting steeds: 1 stuk</p>
<p>In PxQ uren maal tarief</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Voorziening</td>
      <td><p>Middel om services/maatregelen in te vullen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Tarief</td>
      <td><p>Hoogte van een bedrag voor een bepaald product of dient</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verzoek om Toewijzing</td>
      <td><p>Verzoek tot toewijzing dat vanuit leverancier (via H10-portal) aan de gemeente wordt gestuurd. Zie https://informatiemodel.istandaarden.nl/2019/views/view_274300.html</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Tarief</td>
      <td><p>Hoogte van een bedrag voor een bepaald product of dient</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Voorzieningsoort</td>
      <td><p>Typering van een voorziening</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Doelgroep</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Client</td>
      <td><p>Een ingeschreven persoon die gebruik maakt van producten en diensten van de gemeente.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Eenheid</td>
      <td><p>Eenheden uit WMO756, zie https://www.istandaarden.nl/ibieb/functionele-uitwerking-release-iwmo-20</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Frequentie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Leveringsvorm</td>
      <td><p>Een van de vormen waarin Wlz-zorg geleverd kan worden, namelijk verblijf in een instelling of zorg thuis via een Volledig Pakket Thuis (VPT) of een Modulair Pakket Thuis (MPT) als zorg in natura (ZIN), via een persoonsgebonden budget (pgb) of via een combinatie van pgb en MPT.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Soort Verwijzer</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Wet</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">INGESCHREVEN PERSOON</td>
      <td><p>Een INGEZETENE of NIET-INGEZETENE</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Uitstroomreden</td>
      <td><p>Motivatie voor uitstroom</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Inkomensvoorziening</td>
      <td><p>Een regeling die zorg draag voor een inkomen confom de landelijke wetgeving</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Financiele Situatie</td>
      <td><p>Verhouding in inkomsten en uitgaven van een persoon of bedrijf</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Traject</td>
      <td><p>Samenstel van achtereenvolgens uit te voeren en onderling samenhangende deelhandelingen of van opeenvolgende stadia in een proces, voorgesteld als een route die via opeenvolgende bestemmingen naar de eindbestemming voert.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Traject</td>
      <td><p>Samenstel van achtereenvolgens uit te voeren en onderling samenhangende deelhandelingen of van opeenvolgende stadia in een proces, voorgesteld als een route die via opeenvolgende bestemmingen naar de eindbestemming voert.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">NATUURLIJK PERSOON</td>
      <td><p>Een INGESCHREVEN PERSOON of ANDER NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Doelgroep</td>
      <td><p>Een groep mensen of klanten die een bedrijf of organisatie wil benaderen om een product, dienst of informatie onder de aandacht te brengen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">SociaalTeamDossier</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Fraudegegevens</td>
      <td><p>Gegevens met betrekking tot fraude</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Informatie Dakloosheid</td>
      <td><p>Informatie met betrekking tot dakloosheid</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Regeling</td>
      <td><p>Verzamelnaam voor AMvB‚Äôs, Ministeri√´le regelingen, lokale verordeningen, etc. De regeling is de meest concrete uitleg van de wet.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Taalniveau</td>
      <td><p>Het duiden van bepaald gebruik en begrijpelijkheid van een taal. Het is er om verschil in taalvaardigheid te kunnen meten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Tegenprestatie</td>
      <td><p>Verplichting die tegenover een prestatie staat</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">MEDEWERKER</td>
      <td><p><font color="#610e6a">Een medewerker van de organisatie die zaken behandelt uit hoofde van zijn of haar functie binnen een ORGANISATORISCHE EENHEID.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Participatiedossier</td>
      <td><p>Overzicht van alle informatie over integratie en participatie betreffende een inwoner</p></td>
    </tr>
  </tbody>
</table>

### Griffie (GGM)

<figure align="center">
  <img width="1969" src="2023-12-13_GGM_data-objecten/Griffie__GGM_.svg" alt="Griffie (GGM)">
  <figcaption><i>Griffie (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">RECHTSPERSOON</td>
      <td><p>Een NATUURLIJK PERSOON of een NIET-NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Video-opname</td>
      <td><p>Opnametechniek om bewegende beelden als een elektronisch signaal te registreren en weer te geven.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Griffie</td>
      <td><p>529</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Indiener</td>
      <td><p>Persoon die meldiing of aanvraag doet</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Taakveld</td>
      <td><p>Een samenhangend geheel van activiteiten en taken en hangt onder een programma.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Stemming</td>
      <td><p>Stem (openbaring van iemands mening (voor of tegen)),  uitbrengen bij verkiezingen of bij een vergadering</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Categorie</td>
      <td><p>Categorie waarop leveranciers zich voor de levering van personeel voor kunnen kwalificeren</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Dossier</td>
      <td><p>Samenhangende set gegevens en informatie voor een specifiek doel</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Raadsstuk</td>
      <td><p>Stuk dat door de gemeenteraad wordt behandeld</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Agendapunt</td>
      <td><p>Een onderwerp dat in de vergadering wordt behandeld.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Programma</td>
      <td><p>Een tijdelijke, flexibele organisatiestructuur, die is opgezet om de implementatie van een verzameling met elkaar samenhangende projecten en activiteiten te co√∂rdineren, te sturen en te controleren teneinde te zorgen voor de realisatie van de eindresultaten en benefits die zijn gerelateerd aan de strategische doelstellingen van de organisatie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Raadslid</td>
      <td><p>Iemand die behoort de gemeenteraad</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Commissie</td>
      <td><p>Een groep mensen die is samengesteld om een specifieke taak, opdracht of onderzoek uit te voeren</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vergadering</td>
      <td><p>Een bijeenkomst van meerdere mensen (meestal van eenzelfde organisatie) die met elkaar spreken en/of afspraken maken over de gemeenschappelijke toekomst.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Aanwezige Deelnemer</td>
      <td><p>iemand die meedoet aan eencollege- of raadsvergadering</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Collegelid</td>
      <td><p>Iemand die behoort het college van burgemeester en wethouders</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Deelnemersrol</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Stemmingsresultaattype</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Stemmingstype</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">INGEZETENE</td>
      <td><p>Een individueel menselijk wezen, ingeschreven in het Nederlands Bevolkingsregister.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">NATUURLIJK PERSOON</td>
      <td><p>Een INGESCHREVEN PERSOON of ANDER NATUURLIJK PERSOON</p></td>
    </tr>
  </tbody>
</table>

### Groepattribuutsoort (GGM)

<figure align="center">
  <img width="865" src="2023-12-13_GGM_data-objecten/Groepattribuutsoort__GGM_.svg" alt="Groepattribuutsoort (GGM)">
  <figcaption><i>Groepattribuutsoort (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">ZAAK</td>
      <td><p><font color="#610e6a">Een samenhangende hoeveelheid werk met een welgedefinieerde aanleiding en een welgedefinieerd eindresultaat, waarvan kwaliteit en doorlooptijd bewaakt moeten worden.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Groepattribuutsoort</td>
      <td><p>318</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Afwijkend buitenlands correspondentieadres ROL</td>
      <td><p><font color="#610e6a">De gegevens van het adres in het buitenland waarop BETROKKENE in zijn/haar ROL in de ZAAK in de regel schriftelijk bereikbaar is indien dat afwijkt van het reguliere buitenlandse correspondentieadres van BETROKKENE</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Afwijkend correspondentie postadres ROL</td>
      <td><p><font color="#610e6a">De gegevens die tezamen een postbusadres of antwoordnummeradres vormen waarvan BETROKKENE, geen ORGANISATORISCHE EENHEID en MEDEWERKER ziinde, heeft aangegeven schriftelijk bereikbaar te zijn in verband met zijn/haar ROL in de ZAAK en dat afwijkt van de reguliere correspondentiegegevens van BETROKKENE.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Ander zaakobject ZAAK</td>
      <td><p><font color="#610e6a">Aanduiding van het object (of de objecten) waarop de ZAAK betrekking heeft indien dat object (of die objecten) niet aangeduid kan worden met de relatie &lsquo;heeft betrekking op ZAAKOBJECT&rsquo;.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Contactpersoon ROL</td>
      <td><p><font color="#610e6a">De gegevens van de persoon die anderen desgevraagd in contact brengt met medewerkers van de BETROKKENE, een NIET-NATUURLIJK PERSOON of VESTIGING zijnde, of met BETROKKENE zelf, een NATUURLIJK PERSOON zijnde, vanuit het belang van BETROKKENE in haar ROL bij een ZAAK,.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Kenmerken ZAAK</td>
      <td><p><font color="#610e6a">Identificatie-gegevens over de zaak in andere administraties</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Opschorting ZAAK</td>
      <td><p><font color="#610e6a">Gegevens omtrent het tijdelijk opschorten van de behandeling van de ZAAK</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verlenging ZAAK</td>
      <td><p><font color="#610e6a">Gegevens omtrent het verlengen van de doorlooptijd van de behandeling van de ZAAK</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Adresaanduiding</td>
      <td><p>De adresaanduiding van het WOZ-OBJECT</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Correspondentieadres buitenland</td>
      <td><p>De gegevens over het buitenlands correspondentie (-post)adres in het buitenland</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Geboorte ingeschreven natuurlijk persoon</td>
      <td><p>Gegevens over de geboorte van de INGESCHREVEN NATUURLIJK PERSOON.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Geboorte INGESCHREVEN PERSOON</td>
      <td><p>Gegevens over de geboorte van de ingeschreven persoon.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Handelsnamen MAATSCHAPPELIJKE ACTIVITEIT</td>
      <td><p>{nog niet in NHR uitgewerkt}</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Handelsnamen VESTIGING</td>
      <td><p>{nog niet in NHR uitgewerkt}</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Koopsom kadastrale onroerende zaak</td>
      <td><p>Het in een ter inschrijving aangeboden stuk vermelde bedrag, waarvoor 1 of meer onroerende zaken zijn verkregen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Locatie kadastrale onroerende zaak</td>
      <td><p>Deze wordt gebruikt om één of meer locatieaanduiding(en) van een onroerende zaak weer te geven.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Migratie ingeschreven natuurlijk persoon</td>
      <td><p>Om gegevens vast te leggen over immigratie en emigratie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Naam aanschrijving NATUURLIJK PERSOON</td>
      <td><p>De naamgegevens waarmee de persoon heeft aangegeven aangeschreven te willen worden</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Naam NATUURLIJK PERSOON</td>
      <td><p>Gegevens over de naam van de natuurlijk persoon</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Naamgebruik natuurlijk persoon</td>
      <td><p>De naamgegevens waarmee de persoon heeft aangegeven aangeschreven te willen worden</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Nationaliteit ingeschreven natuurlijk persoon</td>
      <td><p>Gegevens over de nationaliteit.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Nederlandse nationaliteit INGESCHREVEN PERSOON</td>
      <td><p>Gegevens over de nationaliteit.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Ontbinding huwelijk/geregistreerd partnerschap</td>
      <td><p>Gegevens over het ontbonden huwelijk of geregistreerd partnerschap.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Overlijden ingeschreven natuurlijk persoon</td>
      <td><p>Gegevens over het overlijden van de ingeschreven natuurlijk persoon.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Overlijden INGESCHREVEN PERSOON</td>
      <td><p>Gegevens over het overlijden van de ingeschreven persoon.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Postadres</td>
      <td><p>De gegevens die tezamen een postbusadres of antwoordnummeradres vormen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Rekeningnummer</td>
      <td><p>De gegevens inzake de bankrekening waarmee het SUBJECT in de regel financieel communiceert.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Samengestelde naam natuurlijk persoon</td>
      <td><p>Gegevens over de naam van de NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">SBI activiteit vestiging</td>
      <td><p>Aanduiding van de activiteit (en) van een vestiging  conform de Standaard BedrijfsIndeling</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Sluiting/aangaan huwelijk/geregistreerd partnerschap</td>
      <td><p>Gegevens over het gesloten huwelijk of het aangegane geregistreerd partnerschap.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Soort functioneel gebied</td>
      <td><p>Gegevens over het soort functioneel gebied.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Soort kunstwerk</td>
      <td><p>Gegevens over het soort kunstwerk.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Soort overig bouwwerk</td>
      <td><p>Gegevens over het soort overig bouwwerk.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Soort scheiding</td>
      <td><p>Gegevens over de soort scheiding</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Soort spoor</td>
      <td><p>Gegevens over het soort spoor.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Splitsingstekeningreferentie</td>
      <td><p><font color="#0f0f0f">Verwijzing naar de splitsingstekening behorende bij de APPARTEMENTSRECHTSPLITSING</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verblijf buitenland</td>
      <td><p>De gegevens over het verblijf in het buitenland</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verblijf buitenland SUBJECT</td>
      <td><p>De gegevens over het verblijf in het buitenland</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verblijfadres ingeschreven natuurlijk persoon</td>
      <td><p>De gegevens over het verblijf en adres van de INGESCHREVEN NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verblijfadres INGESCHREVEN PERSOON</td>
      <td><p>De gegevens over het verblijf en adres van de INGESCHREVEN PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verblijfsrecht ingeschreven natuurlijk persoon</td>
      <td><p>De gegevens om het verblijfsrecht vast te leggen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verstrekkingsbeperking  partieel ingeschreven natuurlijk persoon</td>
      <td><p>Een INGESCHREVEN NATUURLIJK PERSOON kan voor één of meerdere partijen kiezen voor wie een verstrekkingsbeperking geldt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">NUMMERAANDUIDING</td>
      <td><p>Een door het bevoegde gemeentelijke orgaan als zodanig toegekende aanduiding van een VERBLIJFSOBJECT, een STANDPLAATS of een LIGPLAATS.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">KADASTRALE ONROERENDE ZAAK</td>
      <td><p>Een geregistreerd goed waarvoor bij overdracht of vestiging van rechten inschrijving in de openbare registers van het Kadaster is vereist zijnde een KADASTRAAL PERCEEL of een APPARTEMENTSRECHT.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">WOONPLAATS</td>
      <td><p>Een door het bevoegde gemeentelijke orgaan als zodanig aangewezen en van een naam voorzien gedeelte van het grondgebied van de gemeente.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">VESTIGING</td>
      <td><p>Een gebouw of complex van gebouwen waar duurzame uitoefening van de activiteiten van een onderneming of rechtspersoon plaatsvindt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">FUNCTIONEEL GEBIED</td>
      <td><p>Begrensd en benoemd gebied dat door een functionele eenheid beschreven wordt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">KUNSTWERKDEEL</td>
      <td><p>Onderdeel van een civiel-technisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">OVERIG BOUWWERK</td>
      <td><p>Met de aarde verbonden duurzaam bouwwerk, dat niet valt onder de definities van een pand of kunstwerk.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">SCHEIDING</td>
      <td><p>Kunstmatig, meestal lineair obstakel met een werende functie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">SPOOR</td>
      <td><p>De as van het spoor, dat wil zeggen het midden van twee stalen staven op een onderling vaste afstand, waarover trein, tram, of sneltram rijdt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">VERBLIJFSOBJECT</td>
      <td><p>De kleinste binnen één of meer panden gelegen en voor woon -, bedrijfsmatige, of recreatieve doeleinden geschikte eenheid van gebruik die ontsloten wordt via een eigen afsluitbare toegang vanaf de openbare weg, een erf of een gedeelde verkeersruimte, onderwerp kan zijn van goederenrechtelijke rechtshandelingen en in functioneel opzicht zelfstandig is.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">APPARTEMENTSRECHTSPLITSING</td>
      <td><p>Het recht op een stuk grond of op een gebouw met toebehoren op de daarbij behorende grond met toebehoren is gesplitst in appartementsrechten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">STANDPLAATS</td>
      <td><p>Een door het bevoegde gemeentelijke orgaan als zodanig aangewezen terrein of gedeelte daarvan dat bestemd is voor het permanent plaatsen van een niet direct en niet duurzaam met de aarde verbonden en voor woon -, bedrijfsmatige, of recreatieve doeleinden geschikte ruimte.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">ADRESSEERBAAR OBJECT AANDUIDING</td>
      <td><p>Een door het bevoegde gemeentelijke orgaan als zodanig toegekende aanduiding van een VERBLIJFSOBJECT, een STANDPLAATS of een LIGPLAATS.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">LIGPLAATS</td>
      <td><p>Een door het bevoegde gemeentelijke orgaan als zodanig aangewezen plaats in het water al dan niet aangevuld met een op de oever aanwezig terrein of een gedeelte daarvan, die bestemd is voor het permanent afmeren van een voor woon-, bedrijfsmatige of recreatieve doeleinden geschikt vaartuig.</p></td>
    </tr>
  </tbody>
</table>

### HR (GGM)

<figure align="center">
  <img width="1621" src="2023-12-13_GGM_data-objecten/HR__GGM_.svg" alt="HR (GGM)">
  <figcaption><i>HR (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">MEDEWERKER</td>
      <td><p><font color="#610e6a">Een medewerker van de organisatie die zaken behandelt uit hoofde van zijn of haar functie binnen een ORGANISATORISCHE EENHEID.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">NIET NATUURLIJK PERSOON</td>
      <td><p>Een INGESCHREVEN NIET-NATUURLIJK PERSOON of een ANDER BUITENLANDS NIET-NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">HR</td>
      <td><p>103</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Anciennteit</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Fomatieplaats</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Formatieplaats</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Genoten Opleiding</td>
      <td><p>Afgeronde opleiding, een samenhangend geheel van vakken, gericht op de verwezenlijking van welomschreven doelstellingen op het gebied van kennis, inzicht en vaardigheden</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Opleiding</td>
      <td><p>Een samenhangend geheel van vakken, gericht op de verwezenlijking van welomschreven doelstellingen op het gebied van kennis, inzicht en vaardigheden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Normprofiel</td>
      <td><p>Normprofiel</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Beoordeling</td>
      <td><p>Beoordeling is het oordeel van de professional over het functioneren van een leerling</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">OrgModelEenheid</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Individueel Keuzebudget</td>
      <td><p>Bedrag dat feitelijk beschikbaar gesteld wordt voor een individu om een bepaalde keus te kunnen maken</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Keuzebudgetbesteding</td>
      <td><p>De daadwerkelijk uitgave van een keuzebudget</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Declaratie</td>
      <td><p>Een opgave van te vergoeden kosten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Declaratiesoort</td>
      <td><p>Typering van een declaratie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Schaal</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Werknemer</td>
      <td><p>De contractuele wederpartij van de werkgever bij de arbeidsovereenkomst.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Disciplinaire Maatregel</td>
      <td><p>Een besluit dat wordt opgelegd wanneer een persoon zijn verplichtingen niet of niet op de juiste wijze nakomt, of zich op andere wijze misdraagt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Soort Disciplinaire Maatregel</td>
      <td><p>Typering van een disciplinaire maatregel</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Onderwijsinstituut</td>
      <td><p>Een instituut waar onderwijs wordt gegeven.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Uren</td>
      <td><p>Aantal besteedde uren aan een activiteit</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Sollicitatiegesprek</td>
      <td><p>Onderhoud tussen sollicitant en werkgever met betrekking tot een sollicatie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Geweldsincident</td>
      <td><p>Een gebeurtenis met betrekking tot agressie en omvat het veroorzaken van verwondingen of schade bij mensen, dieren, of voorwerpen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Keuzebudgetbestedingsoort</td>
      <td><p>Typering van een keuzebudgetbesteding</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Dienstverband</td>
      <td><p>De rechtsbetrekking tussen werkgever en werknemer zoals vastgelegd in een arbeidsovereenkomst.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Relatie</td>
      <td><p>Betrekking waarin personen, zaken, begrippen of grootheden van nature tot elkaar staan.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Aanstelling</td>
      <td><p>De rechtsbetrekking tussen werkgever en werknemer zoals vastgelegd in een arbeidsovereenkomst.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Sollicitatie</td>
      <td><p>Verzoek om in een functie te worden aangesteld.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vacature</td>
      <td><p>Een arbeidsplaats binnen een bedrijf of organisatie die nog gevuld dient te worden door werkzoekenden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Sollicitant</td>
      <td><p>Persoon die werk zoekt</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Functiehuis</td>
      <td><p>Model waarin functies van een organisatie worden beschreven.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verlof</td>
      <td><p>Een periode waarin iemand toestemming heeft om iets te doen, in het bijzonder om afwezig te zijn.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verlofsoort</td>
      <td><p>Typering van verlof</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verzuim</td>
      <td><p>Een afwezigheid van een werknemer van werk.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verzuimsoort</td>
      <td><p>Typologie van verzuim</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">NATUURLIJK PERSOON</td>
      <td><p>Een INGESCHREVEN PERSOON of ANDER NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">VESTIGING VAN ZAAKBEHANDELENDE ORGANISATIE</td>
      <td><p><font color="#610e6a">Een VESTIGING van een onderneming of rechtspersoon zijnde de zaakbehandelende organisatie.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">ORGANISATORISCHE EENHEID</td>
      <td><p><font color="#610e6a">Het deel van een functioneel afgebakend onderdeel binnen de organisatie dat haar activiteiten uitvoert binnen een VESTIGING VAN ZAAKBEHANDELENDE ORGANISATIE en die verantwoordelijk is voor de behandeling van zaken.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Functie</td>
      <td><p>Een samenhangende verzameling van rollen</p></td>
    </tr>
  </tbody>
</table>

### ICT (GGM)

<figure align="center">
  <img width="2635" src="2023-12-13_GGM_data-objecten/ICT__GGM_.svg" alt="ICT (GGM)">
  <figcaption><i>ICT (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">ICT</td>
      <td><p>171</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Externe Bron</td>
      <td><p>Bron buiten de eigen organisatie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Aanvraag</td>
      <td><p>(officieel) verzoek, iets (officieel) vragen aan een bevoegde macht.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Attribuutsoort</td>
      <td><p><b>Attribuutsoort </b>– <i>Stereotype «Attribuutsoort»</i>: De UML-representatie van een attribuutsoort, uitgedrukt in een stereotype van UML-Property<sup>3 </sup>(metaclass).
Er zijn verschillende modelelementen die gebaseerd zijn op UML-property, zoals aangegeven in §2.1.2. Wanneer een UML-property in het informatiemodel de betekenis heeft van een attribuut van een objecttype, dan heeft deze het stereotype «Attribuutsoort».
Een attribuutsoort is een type van gelijksoortige attributen of gegevens. Daartoe kijken we eerst naar het begrip ‘gegeven’.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Datatype</td>
      <td><p><b>Attribuutsoort </b>– <i>Stereotype «Attribuutsoort»</i>: De UML-representatie van een attribuutsoort, uitgedrukt in een stereotype van UML-Property<sup>3 </sup>(metaclass).
Er zijn verschillende modelelementen die gebaseerd zijn op UML-property, zoals aangegeven in §2.1.2. Wanneer een UML-property in het informatiemodel de betekenis heeft van een attribuut van een objecttype, dan heeft deze het stereotype «Attribuutsoort».
Een attribuutsoort is een type van gelijksoortige attributen of gegevens. Daartoe kijken we eerst naar het begrip ‘gegeven’.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Objecttype</td>
      <td><p>De typering van een groep objecten (in de werkelijkheid) die binnen een domein relevant zijn en als gelijksoortig worden beschouwd.
<i>Toelichting</i>
Jan, Piet en Marie zijn mensen die vanuit het Burgerzaken-domein beschouwd worden als objecten van het type ‘natuurlijk persoon’. In een ander domein, ‘de volksmond’, noemen we dit ‘mens’ wat ook een objecttype is. In weer een ander domein is Jan van het type ‘vergunninghouder’ en Piet en Marie niet, omdat aan hen (nog) nooit een vergunning verleend is. Objecttypen zijn een abstractie van de werkelijkheid oftewel we beogen hiermee de werkelijkheid zo getrouw mogelijk te beschrijven, binnen de context van het domein. Dit staat geheel los van het vastleggen van gegevens over objecten van een type in een registratie. Daartoe is veelal een interpretatie nodig (van die werkelijkheid cq. die objecttypen) naar eenheden die in een registratie vastgelegd kunnen worden (records, entiteiten e.d.) op basis van andere overwegingen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Prijzenboek</td>
      <td><p>Beschrijving van gangbare onderhoudsactiviteiten met de bijbehorende, actuele prijzen en normen voor de uitvoering.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Gegeven</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Generalisatie</td>
      <td><p>De typering van het hiërarchische verband tussen een meer generiek object van een objecttype en een meer specifiek object van een ander objecttype waarbij het laatstgenoemde object eigenschappen van het eerstgenoemde object overerft.
<i>Toelichting</i>
Een generalisatierelatie geeft aan dat bepaalde eigenschappen van een objecttype (vaak attribuutsoorten en/of relatiesoorten) ook gelden voor de gerelateerde objecttypen, én dat deze qua semantiek, structuur en syntax gelijk zijn. We spreken dan van een supertype met subtypen. De modelelementen die generiek gelden worden in een generiek objecttype, het supertype, gemodelleerd en deze worden overerft door elk subtype (minimaal twee) die de generalisatie relatie legt naar dit generieke objecttype.
<i>Voorbeeld: PERCEEL is specialisatie van KADASTRAAL ONROERENDE ZAAK, APPARTEMENTSRECHT is specialisatie van KADASTRAAL ONROERENDE ZAAK. PERCEEL en APPARTEMENTSRECHT hebben beide ‘Kadastrale aanduiding’ en een ‘relatie met ONROERENDE ZAAK FILIATIE’.</i></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Versie</td>
      <td><p>De versie-aanduiding van een object.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Classificatie</td>
      <td><p>Ordening van informatieobjecten in een logisch verband, zoals vastgelegd in een classificatieschema.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Relatiesoort</td>
      <td><p>De typering van het structurele verband tussen een object van een objecttype en een (ander) object van een ander (of hetzelfde) objecttype.
<i>Toelichting</i>
Objecten hebben eigenschappen die gemodelleerd kunnen worden met attribuutsoorten maar ook met relatiesoorten naar andere objecttypen. Als het voor het desbetreffende domein van belang is om die eigenschap te modelleren als onderdeel van een ander objecttype, dan maakt de relatiesoort die eigenschap beschikbaar voor het eerstgenoemde objecttype. Bijvoorbeeld, een attribuutsoort van het objecttype PERSOON zou kunnen zijn ‘Naam geregistreerd partner’ (naast de attribuutsoort ‘Naam’ van PERSOON). De naam van de geregistreerde partner komt evenwel ook beschikbaar met een relatiesoort van PERSOON naar PERSOON: “heeft geregistreerd partnerschap met”. Zie ook het eerder genoemde voorbeeld van SCHIP en MOTOR.
Voorbeeld: relatiesoorten “VERBLIJFSOBJECT is gelegen in een PAND” en “SUBJECT heeft als correspondentieadres WOONPLAATS”, of korter, “gelegen in”, “postadres”.
Wanneer een relatie (UML-assocation) gebruikt wordt om objecten aan elkaar te verbinden, zonder dat er eigenschappen over deze relatie worden vastgelegd, dan heeft deze het stereotype «Relatiesoort».</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Product</td>
      <td><p>Het resultaat van een proces dat in het economisch verkeer een waarde bezit.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Package</td>
      <td><p>Een samengesteld bestand of een directory die een aantal bestanden bevat, maar welke als √©√©n bestand aan de gebruiker getoond word</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Dienst</td>
      <td><p>Het uitvoeren van werkzaamheden met een continu of periodiek karakter om waarde te realiseren voor een afnemer.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Domein/Taakveld</td>
      <td><p>Kennisgebied of activiteit gekarakteriseerd door een verzameling van concepten, begrippen en/of waarden</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Onderwerp</td>
      <td><p>Op de meest karakteristieke elementen gebaseerde en in woord of eenvoudige zinstructuur samengevatte aanduiding van de inhoud van een document</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Applicatie</td>
      <td><p>Een applicatiecomponent die gericht is op het ondersteunen van eindgebruikers.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Notitie</td>
      <td><p>Korte, zakelijke uiteenzetting op schrift</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Gebruikerrol</td>
      <td><p>Een samenhangende set van taken, bevoegdheden en verantwoordelijkheden van een gebruiker.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Linkbaar CMDB-item</td>
      <td><p>Niet opnemen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Melding</td>
      <td><p>De betekenisvolle formulering van een waargenomen feit, waaraan een waarde kan worden toegekend</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Log</td>
      <td><p>Registratie van gegevens.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Koppeling</td>
      <td><p>Verbinding tussen twee systemen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Server</td>
      <td><p>Computer die in een netwerk een ondersteunende taak vervult.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Storing</td>
      <td><p>Verlies van de mogelijkheid om volgens een specificatie te werken of om het vereiste resultaat te leveren.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vervoersmiddel</td>
      <td><p>Een voertuig dat zich over het land verplaatst.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Telefoniegegevens</td>
      <td><p>Gegevens die worden bewaard van telefoongesprekken</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Toegangsmiddel</td>
      <td><p>Een middel waarmee men zich toegang tot iets kan verschaffen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Wijzigingsverzoek</td>
      <td><p>Een aanvraag voor wijziging</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">CMDB-item</td>
      <td><p>Item in een Configuratie Management DataBase</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Software</td>
      <td><p>Een geheel van computerprogramma's met bijbehorende data, die bewerkingen en taken uitvoeren</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Applicatiecategorie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Nertwerkcomponent</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Database</td>
      <td><p>Een applicatiecomponent die een dataset bevat.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Beheerstatus</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Licentie</td>
      <td><p>Een gebruiksrecht en autorisatie om van een product of dienst gebruik te maken binnen bepaalde voorwaarden</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Gebruikerrol</td>
      <td><p>Een samenhangende set van taken, bevoegdheden en verantwoordelijkheden van een gebruiker.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Inventaris</td>
      <td><p>Een inboedel of een opsomming van voorwerpen op een bepaalde plaats, gemaakt volgens een vaste procedure.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Packagingstatus</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Hardware</td>
      <td><p>Alle fysieke componenten of onderdelen die in een computer een rol spelen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Servertypes</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">ZAAKTYPE</td>
      <td><p><font color="#610e6a">Generieke aanduiding van de aard van een zaak</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">DOCUMENT</td>
      <td><p><font color="#610e6a">Geheel van gegevens met een eigen identiteit ongeacht zijn vorm, met de bijbehorende metadata ontvangen of opgemaakt door een natuurlijke en/of rechtspersoon bij de uitvoering van taken, zijnde een ENKELVOUDIG DOCUMENT of een SAMENGESTELD DOCUMENT.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">MEDEWERKER</td>
      <td><p><font color="#610e6a">Een medewerker van de organisatie die zaken behandelt uit hoofde van zijn of haar functie binnen een ORGANISATORISCHE EENHEID.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Batch</td>
      <td><p>Verzameling van posten die in het kader van automatische verwerking een logisch geheel vormen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Leverancier</td>
      <td><p>Een niet-natuurlijk persoon die een product of dienst levert aan de organisatie</p></td>
    </tr>
  </tbody>
</table>

### Inburgering (GGM)

<figure align="center">
  <img width="1429" src="2023-12-13_GGM_data-objecten/Inburgering__GGM_.svg" alt="Inburgering (GGM)">
  <figcaption><i>Inburgering (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Inburgering</td>
      <td><p>467</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">KNM?</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Leerroute</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">ParticipatieComponent</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">B1</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">PIP</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Examenonderdeel</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Z</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Onderwijs</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Brede Intake</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Examen</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">MAP</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">PVT</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Inburgeringstraject</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vreemdeling</td>
      <td><p>Een Vreemdeling is een Natuurlijk Persoon die de Nederlandse Nationaliteit niet bezit en niet op grond van een wettelijke bepaling als Nederlander wordt behandeld.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Inburgeraar</td>
      <td><p>De gemeente gaat inburgeringsplichtige nieuwkomers begeleiden bij hun inburgering. Voor asielstatushouders doen zij dit vanaf het moment van koppeling  aan een gemeente</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Asielstatushouder</td>
      <td><p>De Inburgeringsplichtige die rechtmatig verblijf heeft</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Gezinsmigrant en Overige migrant</td>
      <td><p>Object Inburgeraar is gespecialiseerd in Asielstatushouder en Gezinsmigrant en Overige Migrant.</p>
<p>Gezinsmigrant en Overige Migrant heeft geen kenmerken en is bedoeld om relaties te leggen met objecten die alleen van toepassing zijn voor Gezinsmigrant en Overige Migrant zoals bijvoorbeeld: object Aanvraag Sociale Lening. Hetzelfde geldt ook voor object Asielstatushouder, deze heeft overigens wel kenmerken.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verblijfplaats</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verblijfplaats AZC</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">NATUURLIJK PERSOON</td>
      <td><p>Een INGESCHREVEN PERSOON of ANDER NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">GEMEENTE</td>
      <td><p>Een gedeelte van het grondgebied van Nederland, ingesteld op basis van artikel 123 van de Grondwet.</p></td>
    </tr>
  </tbody>
</table>

### Inkoop (GGM)

<figure align="center">
  <img width="3361" src="2023-12-13_GGM_data-objecten/Inkoop__GGM_.svg" alt="Inkoop (GGM)">
  <figcaption><i>Inkoop (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">ZAAK</td>
      <td><p><font color="#610e6a">Een samenhangende hoeveelheid werk met een welgedefinieerde aanleiding en een welgedefinieerd eindresultaat, waarvan kwaliteit en doorlooptijd bewaakt moeten worden.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Inkoop</td>
      <td><p>127</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Aanbesteding</td>
      <td><p>Kan een (enkel of meervoudige) onderhandse aanbesteding, of een nationale of Europese aanbesteding</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Uitnodiging</td>
      <td><p>Een verzoek om iets bij te wonen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Offerteaanvraag</td>
      <td><p>Aanbesteding bij inschrijving</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Formulier Inhuur</td>
      <td><p>Formulier ten behoeve van inhuur personeel</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Aankondiging</td>
      <td><p>Aankondiging van een Nationale of Europese aanbesteding</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Gunning</td>
      <td><p>Gunning van een (enkel of meervoudige) onderhandse aanbesteding, of een nationale of Europese aanbesteding 
Of voor levering personeel</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Formulier Verlenging Inhuur</td>
      <td><p>Formulier ten behoeve van verlenging inhuur personeel</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Startformulier Aanbesteden</td>
      <td><p>Formulier voor het starten van een aanbeseding</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Aanbesteding Inhuur</td>
      <td><p>Aanbesteding voor inhuur van personen of diensten</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Categorie</td>
      <td><p>Categorie waarop leveranciers zich voor de levering van personeel voor kunnen kwalificeren</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Inschrijving</td>
      <td><p>Inschrijving op een nationale of Europese aanbesteding</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">CPV-code</td>
      <td><p>De Common Procurement Vocabulary (CPV-codes) is een gemeenschappelijke woordenlijst van de EU, alle mogelijke soorten overheidsopdrachten voor diensten, leveringen en werken hebben een eigen code gekregen. Aanbestedende diensten moeten bij Europese aanbestedingen dit classificatiesysteem toepassen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Offerte</td>
      <td><p>Aanbod, aanbieding of voorstel van goederen of diensten waarin opgave is gedaan van de prijs.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Aanvraag Inkooporder</td>
      <td><p>het betreft hier het formulier 'Aanvraag Inkooporder'</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Kwalificatie</td>
      <td><p>Kwalifificatie voor een nationale of europese aanbesteding</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Selectietabel Aanbesteding</td>
      <td><p>Gebaseerd op het procedureoverzicht inkoop. Hierin kan de tabel met drempelbedragen en bijbehorende procedures worden opgeslagen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Leverancier</td>
      <td><p>Een niet-natuurlijk persoon die een product of dienst levert aan de organisatie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Kandidaat</td>
      <td><p>Iemand die een bepaalde baan of functie wil</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Aanbestedingsoort</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Contract</td>
      <td><p>Bindende overeenkomst</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Inkooprol</td>
      <td><p>Toevoeging Gemeente Schiedam</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Opdrachtcategorie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Inkooppakket</td>
      <td><p>Standaard indeling om de werken, diensten en leveringen die de aanbestedende dienst helpt bij het structureren van haar uitgaven. Samenhangende leveringen, diensten en producten zijn hierin gegroepeerd.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Opdrachtsoort</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">MEDEWERKER</td>
      <td><p><font color="#610e6a">Een medewerker van de organisatie die zaken behandelt uit hoofde van zijn of haar functie binnen een ORGANISATORISCHE EENHEID.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">RECHTSPERSOON</td>
      <td><p>Een NATUURLIJK PERSOON of een NIET-NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Leverancier</td>
      <td><p>Een niet-natuurlijk persoon die een product of dienst levert aan de organisatie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Aanbesteding</td>
      <td><p>Een procedure waarbij een opdrachtgever bekendmaakt dat hij een opdracht of concessie wil laten uitvoeren en bedrijven uitnodigt om een offerte in te dienen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">NATUURLIJK PERSOON</td>
      <td><p>Een INGESCHREVEN PERSOON of ANDER NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Kostenplaats</td>
      <td><p>Rekening waaraan boekingen in een financi√´le administratie samen worden toegeschreven.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Melding</td>
      <td><p>De betekenisvolle formulering van een waargenomen feit, waaraan een waarde kan worden toegekend</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Werkbon</td>
      <td><p>Document waarin een heoveelheid werk is beschreven</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Tarief</td>
      <td><p>Hoogte van een bedrag voor een bepaald product of dient</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Product</td>
      <td><p>Het resultaat van een proces dat in het economisch verkeer een waarde bezit.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Uitvoerder Graafwerkzaamheden</td>
      <td><p>Degene die op de bouwlocatie van een project de leiding heeft met betrekking tot de graafwerkzaamheden</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Applicatie</td>
      <td><p>Een applicatiecomponent die gericht is op het ondersteunen van eindgebruikers.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Vervoerder</td>
      <td><p>Degene die openbaar vervoer of besloten busvervoer verricht, niet in de hoedanigheid van bestuurder van een auto, bus, trein, metro, tram of een via een geleidesysteem voortbewogen voertuig.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Server</td>
      <td><p>Computer die in een netwerk een ondersteunende taak vervult.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Belprovider</td>
      <td><p>Leverancier of dienstverlener van modiele beldiensten</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Productie-eenheid</td>
      <td><p>Een (deel van een) productiemiddel, dat zelfstandig (ofwel onafhankelijk van de andere delen van het desbetreffende productiemiddel) kan worden ingezet.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Factuur</td>
      <td><p>Schriftelijke rekening of nota voor de geleverde zaken of verrichte diensten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Inkooporder</td>
      <td><p>Een opdracht (gezien vanuit de klant) voor √©√©n of meer leveringen door de leverancier aan die klant van een bepaalde hoeveelheid gespecificeerde goederen en/of diensten onder overeengekomen leveringsvoorwaarden en prijzen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">ORGANISATORISCHE EENHEID</td>
      <td><p><font color="#610e6a">Het deel van een functioneel afgebakend onderdeel binnen de organisatie dat haar activiteiten uitvoert binnen een VESTIGING VAN ZAAKBEHANDELENDE ORGANISATIE en die verantwoordelijk is voor de behandeling van zaken.</font></p></td>
    </tr>
  </tbody>
</table>

### Leerplicht en Leerlingenvervoer (GGM)

<figure align="center">
  <img width="1591" src="2023-12-13_GGM_data-objecten/Leerplicht_en_Leerlingenvervoer__GGM_.svg" alt="Leerplicht en Leerlingenvervoer (GGM)">
  <figcaption><i>Leerplicht en Leerlingenvervoer (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Leverancier</td>
      <td><p>Een niet-natuurlijk persoon die een product of dienst levert aan de organisatie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Leerplicht en Leerlingenvervoer</td>
      <td><p>553</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Aanvraag Leerlingenvervoer</td>
      <td><p>Een aanvraag voor een leerling die recht heeft op vervoer van en naar onderwijs.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verlofaanvraag</td>
      <td><p>Een verzoek om toestemming te krijgen iets te doen, bijvoorbeeld vakantie of studie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Beschikking Leerlingenvervoer</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Aanvraagvrijstelling</td>
      <td><p>Vrijstelling van een aanvraag voor leerlingenvervoer</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">HALT-verwijzing</td>
      <td><p>Jongeren van 12 tot 18 jaar die strafbare feiten plegen, zoals bijvoorbeeld: winkeldiefstal, vernieling, openbaar dronkenschap of oplichting kunnen naar Halt worden verwezen. In sommige gevallen is daarvoor toestemming nodig van het Openbaar Ministerie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vervoerder</td>
      <td><p>Degene die openbaar vervoer of besloten busvervoer verricht, niet in de hoedanigheid van bestuurder van een auto, bus, trein, metro, tram of een via een geleidesysteem voortbewogen voertuig.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">AanvraagOfMelding</td>
      <td><p>Komt overeen met een VJV</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verzuimmelding</td>
      <td><p>Een melding dat een leerling niet op school verschijnt. De school moet actie ondernemen naar de leerling (en zijn ouders). Een school moet het verzuim melden bij de gemeente.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vrijstelling</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Ziekmelding Leerlingenvervoer</td>
      <td><p>Een melding van een zieke leerling die recht heeft op vervoer van en naar onderwijs.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Beslissing</td>
      <td><p>Selectie van een voorstelbare werkelijkheid (voorkeursvariant) uit een aantal mogelijke werkelijkheden (varianten) op basis van een verzameling van criteria.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Sanctiesoort</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verzuimsoort</td>
      <td><p>Typologie van verzuim</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vrijstellingsoort</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Doorgeleiding OM</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Klacht Leerlingenvervoer</td>
      <td><p>Een uiting van ontevredenheid over het vervoer van leerlingen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Leerplichtambtenaar</td>
      <td><p>Ambtenaar die toezicht houdt op de uitvoering van de leerplichtwet.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Procesverbaal Onderwijs</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">School</td>
      <td><p>Gebouw in gebruik voor basis, middelbaar of hoger onderwijs.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Ouder Of Verzorger</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">MEDEWERKER</td>
      <td><p><font color="#610e6a">Een medewerker van de organisatie die zaken behandelt uit hoofde van zijn of haar functie binnen een ORGANISATORISCHE EENHEID.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Leerling</td>
      <td><p>Mens die een opleiding volgt, heeft gevolgd of gaat volgen of opgaat of is opgegaan voor een toets. (Bron: KOI)</p></td>
    </tr>
  </tbody>
</table>

### Meldingen Openbare Ruimte (GGM)

<figure align="center">
  <img width="577" src="2023-12-13_GGM_data-objecten/Meldingen_Openbare_Ruimte__GGM_.svg" alt="Meldingen Openbare Ruimte (GGM)">
  <figcaption><i>Meldingen Openbare Ruimte (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Meldingen Openbare Ruimte</td>
      <td><p>800</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">AanvraagOfMelding</td>
      <td><p>Komt overeen met een VJV</p>
<p>Bron: GEM<em>VJV (Distinct op REQ</em>ID)
ID: REQ_ID</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">RECHTSPERSOON</td>
      <td><p>Een NATUURLIJK PERSOON of een NIET-NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">MORAanvraagOfMelding</td>
      <td></td>
    </tr>
  </tbody>
</table>

### Metagegevens (GGM)

<figure align="center">
  <img width="229" src="2023-12-13_GGM_data-objecten/Metagegevens__GGM_.svg" alt="Metagegevens (GGM)">
  <figcaption><i>Metagegevens (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Metagegevens</td>
      <td><p>218</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Brondocumenten</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Formele historie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">In onderzoek</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Materiële historie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Strijdigheid / nietigheid</td>
      <td></td>
    </tr>
  </tbody>
</table>

### Monumenten  (GGM)

<figure align="center">
  <img width="577" src="2023-12-13_GGM_data-objecten/Monumenten___GGM_.svg" alt="Monumenten  (GGM)">
  <figcaption><i>Monumenten  (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Monumenten</td>
      <td><p>612</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Ambacht</td>
      <td><p>Beroep waarbij een handwerker met gereedschap eindproducten maakt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bouwactiviteit</td>
      <td><p>Het bouwen van een bouwwerk.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bouwstijl</td>
      <td><p>Trant van bouwen met bepaalde kenmerken in een bepaalde periode. In de betrokken tijdperken waren het geen levende voorstellingen; het zijn later geformuleerde (generaliserende) geschiedkundige constructies. Doelbewust komt deze tendens op sedert c. 1830. (Haslinghuis)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Oorspronkelijke Functie</td>
      <td><p>De functie van een object na bouw of oplevering</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Beschermde Status</td>
      <td><p>Status van de bescherming van een monument. Een monument / erfgoed is een overblijfsel van kunst, cultuur, architectuur of nijverheid dat van algemeen belang wordt geacht vanwege de historische, volkskundige, artistieke, wetenschappelijke, industrieel-archeologische of andere sociaal-culturele waarde. Vormen van monument / erfgoed met de status rijks- provinciaal- of gemeentelijke monument / erfgoed zijn beschermd op grond van een besluit van respectievelijk het Ministerie OCW, de provincie of de gemeente,</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bouwtype</td>
      <td><p>Typering van een bouwstijl</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">TypeMonument</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">KADASTRALE ONROERENDE ZAAK</td>
      <td><p>Een geregistreerd goed waarvoor bij overdracht of vestiging van rechten inschrijving in de openbare registers van het Kadaster is vereist zijnde een KADASTRAAL PERCEEL of een APPARTEMENTSRECHT.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">OPENBARE RUIMTE</td>
      <td><p>Een door het bevoegde gemeentelijke orgaan als zodanig aangewezen en van een naam voorziene buitenruimte die binnen één woonplaats is gelegen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">PAND</td>
      <td><p>De kleinste bij de totstandkoming functioneel en bouwkundig-constructief zelfstandige eenheid die direct en duurzaam met de aarde is verbonden en betreedbaar en afsluitbaar is.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Foto</td>
      <td><p>Afbeelding op een plat vlak vervaardigd door middel van fotografie</p></td>
    </tr>
  </tbody>
</table>

### Museum (GGM)

<figure align="center">
  <img width="1621" src="2023-12-13_GGM_data-objecten/Museum__GGM_.svg" alt="Museum (GGM)">
  <figcaption><i>Museum (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">RECHTSPERSOON</td>
      <td><p>Een NATUURLIJK PERSOON of een NIET-NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Museum</td>
      <td><p>645</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Balieverkoop</td>
      <td><p>Verkoop aan de balie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Balieverkoop Entreekaart</td>
      <td><p>Verkoop van een entreekaart aan de balie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Prijs</td>
      <td><p>De te betalen hoeveelheid geld</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Activiteitsoort</td>
      <td><p>Typering van een activiteit</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Belangtype</td>
      <td><p>Sort van belang</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Entreekaart</td>
      <td><p>Bewijs van toegang tot een gebouw of voorstelling</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Winkelvoorraaditem</td>
      <td><p>Onderdeel in de winkelvoorraad</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Product</td>
      <td><p>Het resultaat van een proces dat in het economisch verkeer een waarde bezit.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Factuur</td>
      <td><p>Schriftelijke rekening of nota voor de geleverde zaken of verrichte diensten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Lener</td>
      <td><p>Iemand die iets te leen krijgt, met name iemand die boeken, digitale bestanden of apparatuur leent bij een museum, bibliotheek, mediatheek of een andere uitleeninstantie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bruikleen</td>
      <td><p>Lening voor tijdelijk gebruik</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Omzetgroep</td>
      <td><p>Artikelen worden gebruikt om omzet te registreren in de shop, de horeca of elders. De omzet wordt vervolgens getotaliseerd op rapportages. Om de artikelen te groeperen moet ieder artikel tot een omzetgroep behoren.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Collectie</td>
      <td><p>Een verzameling van verworven voorwerpen die is samengesteld op grond van vastgestelde criteria.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Belanghebbende</td>
      <td><p>Een persoon wiens belang rechtstreeks bij een besluit is betrokken.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Productgroep</td>
      <td><p>Groepering van producten</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Reservering</td>
      <td><p>Het vooraf bespreken van een plaats in een openbare gelegenheid, vervoermiddel, restaurant e.d.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Programmasoort</td>
      <td><p>Typering van een programma</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Activiteit</td>
      <td><p>Ieder menselijk handelen waarbij, of ieder menselijk nalaten waardoor een verandering of effect in de (fysieke) leefomgeving wordt of kan worden bewerkstelligd.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Doelgroep</td>
      <td><p>Een groep mensen of klanten die een bedrijf of organisatie wil benaderen om een product, dienst of informatie onder de aandacht te brengen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Voorziening</td>
      <td><p>Middel om services/maatregelen in te vullen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Standplaats</td>
      <td><p>vanaf een vaste locatie te koop aanbieden, verkopen of afleveren van goederen of aanbieden van diensten, gebruikmakend van fysieke middelen zoals een kraam, een wagen of een tafel</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Zaal</td>
      <td><p>Grote ruimte in een gebouw</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Incident</td>
      <td><p>Niet-gepland(e) gebeurtenis die of voorval dat tot schade of verlies leidt</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Mailing</td>
      <td><p>Per post verstuurde inhoud</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Museumobject</td>
      <td><p>Beschrijving van een fenomeen in de werkelijkheid met een zekere cultuurhistorische waarde die deel uitmaakt van de culthuurhistorisch object index. Een museum object kan gedifini√´erd worden als een object met betrekking tot gebouwd, archeologisch, roerend of cultuurlandschappelijk erfgoed. Denk hierbij bijvoorbeeld aan een gebouwd of archeologisch rijksmonument, een schilderij of een beschermd stads- of dorpsgezicht.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Rondleiding</td>
      <td><p>Bezichtiging met toelichting</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Tentoonstelling</td>
      <td><p>Een uitstalling van voorwerpen om door het grote publiek bekeken te worden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Programma</td>
      <td><p>Een tijdelijke, flexibele organisatiestructuur, die is opgezet om de implementatie van een verzameling met elkaar samenhangende projecten en activiteiten te co√∂rdineren, te sturen en te controleren teneinde te zorgen voor de realisatie van de eindresultaten en benefits die zijn gerelateerd aan de strategische doelstellingen van de organisatie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Museumrelatie</td>
      <td><p>Betrekking waarin het museum en personen tot elkaar staan</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Samensteller</td>
      <td><p>Iemand die stukken informatie samenbrengt in tentoonstelingen, presentaties en naslagwerken.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Productie-eenheid</td>
      <td><p>Een (deel van een) productiemiddel, dat zelfstandig (ofwel onafhankelijk van de andere delen van het desbetreffende productiemiddel) kan worden ingezet.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Rol</td>
      <td><p>Een samenhangende set van taken, bevoegdheden en verantwoordelijkheden van een gebruiker.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Winkelverkoopgroep</td>
      <td><p>Groepering van winkelverkopen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Erfgoed Object</td>
      <td><p>Uit het verleden ge√´rfde materi√´le en immateri√´le objecten</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">MEDEWERKER</td>
      <td><p><font color="#610e6a">Een medewerker van de organisatie die zaken behandelt uit hoofde van zijn of haar functie binnen een ORGANISATORISCHE EENHEID.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Kostenplaats</td>
      <td><p>Rekening waaraan boekingen in een financi√´le administratie samen worden toegeschreven.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Historisch Persoon</td>
      <td><p>Natuurlijk persoon waarvan informatie beschikbaar is uit het verleden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Leverancier</td>
      <td><p>Een niet-natuurlijk persoon die een product of dienst levert aan de organisatie</p></td>
    </tr>
  </tbody>
</table>

### Omgevingswet (GGM)

<figure align="center">
  <img width="2953" src="2023-12-13_GGM_data-objecten/Omgevingswet__GGM_.svg" alt="Omgevingswet (GGM)">
  <figcaption><i>Omgevingswet (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">MEDEWERKER</td>
      <td><p><font color="#610e6a">Een medewerker van de organisatie die zaken behandelt uit hoofde van zijn of haar functie binnen een ORGANISATORISCHE EENHEID.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">RECHTSPERSOON</td>
      <td><p>Een NATUURLIJK PERSOON of een NIET-NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Omgevingswet</td>
      <td><p>834</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bevoegd Gezag</td>
      <td><p>Bestuursorgaan dat bevoegd is tot het geven van een beschikking of het nemen van een ander besluit.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Initiatiefnemer</td>
      <td><p>Een Natuurlijk Persoon of een Niet Natuurlijk Persoon die het initiatief neemt tot (fysieke) ingrepen in de (leef)omgeving en daartoe een Verzoek bij het Bevoegd Gezag indient. (IMAM)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Uitvoerende instantie</td>
      <td><p>Onderdeel van het bevoegd gezag dat uitvoering geeft aan wetten en besluiten</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Doel verzoek</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Instructieregel</td>
      <td><p><font color="#032547"><b>Objecttype Instructieregel</b></font>
Naam Definitie
Toelichting
Instructieregel
De beschrijving van een juridische regel die een instructie is voor een extern omgevingsdocument of een orgaan.
Het betreft hier juridische regel die instructie geeft aan andere overheden, gericht op externe omgevingsdocumenten, of een taakuitoefening.
Een ander omgevingsdocument is bijvoorbeeld een Omgevingsplan, Omgevingsverordening en Waterschapsverordening.
Een taakuitoefening is voor bijvoorbeeld een gemeentebestuur of een wildbeheereenheid.
Een instructieregel is alleen gericht op een Omgevingsnorm of een Gebiedsaanduiding, zoals een Functie of een Beperkingengebied (en eventueel meerdere).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Type Verzoek</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vraag Classificatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Gebiedsaanwijzing</td>
      <td><p>Functie of een Beperkingengebied, met een verwijzing naar locatie, veelal een gebied, waarbij aangegeven wordt hoe het gebied beschouwd wordt vanuit de bijbehorende regels.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Beperkingsgebied</td>
      <td><p>Een bij of krachtens de wet aangewezen gebied, waar vanwege de aanwezigheid van een werk of object regels gelden, ten aanzien van het beperken van activiteiten die gevolgen hebben of kunnen hebben voor dat werk of object.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Thema</td>
      <td><p>Kernachtige weergave van de grondgedachte achter een regel.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Functie</td>
      <td><p>Een samenhangende verzameling van rollen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Idealisatie</td>
      <td><p>Vastlegging van de manier de begrenzing van Locatie voor deze Juridische regel ge√Ønterpreteerd moet worden en door het bevoegd gezag bedoeld is.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Juridische Regel</td>
      <td><p>De beschrijving van een regel met juridische werkingskracht. Een regel betreft binnen de Omgevingswet veelal activiteiten, en/of normen en/of functies en/of beperkingengebieden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Normwaarde</td>
      <td><p>√â√©n van de kwantitatieve of kwalitatieve waarden van een norm. De normwaarde geeft aan wat de specifieke kwantitatieve of kwalitatieve eisen zijn, inclusief de toewijzing ervan aan de specifieke locatie(s) waar de normwaarde voor geldt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Conclusie</td>
      <td><p>Conclusie van de check. Antwoord op de vraag of ik een melding moet doen of een vergunning aan moet vragen voor een bepaalde activiteit.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Indieningsvereisten</td>
      <td><p>Dat wat de initiatiefnemer moet aanleveren om het bevoegd gezag een aanvraag te kunnen laten beoordelen. De indieningsvereisten is de set aan informatie (gegevens en / of bijlagen) die aan een aanvraag moet worden toegevoegd voor een bepaalde vergunning of melding.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Regel voor Iedereen</td>
      <td><p>Een Juridische regel die voor eenieder werking heeft</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Toepasbare Regel</td>
      <td><p><i>Vanwege de leesbaarheid wordt gewerkt met de term Toepasbare regel ipv regelbeheersobject</i>
<i>
</i><i>Een regelbeheerobject heeft een koppeling met een samenhangende set met regels om een afleiding te kunnen doen. Het regelbeheerobject ‘conclusie gevelaanpassing’ kan een vraag beantwoorden zoals: “Heb ik een vergunning nodig voor het veranderen van een kozijn, kozijninvulling of gevelpaneel”. Het regelbeheerobject ‘melding lozing’ beantwoordt de vraag “Wat moet ik aan informatie (gegevens en documenten) aanleveren als ik ga lozen vanuit particuliere huishoudens”. Het regelbeheerobject “Opslaan van gasolie smeerolie of afgewerkte olie in een bovengrondse opslagtank” </i>geeft aan welke maatregelen genomen dienen te worden.
Het regelbeheerobject is onderdeel van de functionele structuur. De set met regels is gedefinieerd in het Toepasbare regelbestand<sup>2</sup>.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Maatregelen</td>
      <td><p>Beschrijft welke handelingen iemand moet uitvoeren om aan Voorschriften te kunnen voldoen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Omgevingsdocument</td>
      <td><p>In artikel 16.2 van de Omgevingswet aangemerkt instrument te weten: Omgevingsvisie, programma, omgevingsplan, waterschapsverordening, omgevingsverordening, projectbesluit of bij Algemene Maatregel van Bestuur (Omgevingsbesluit) aangewezen ander besluit of ander rechtsfiguur.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Regeltekst</td>
      <td><p>De kleinste zelfstandige eenheid van (een of meer) bij elkaar horende juridische regels: een artikel en lid.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">ToepasbareRegelBestand</td>
      <td><p>Bestand met aangeleverde toepasbare regels</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Uitvoeringsregel</td>
      <td><p>De uitvoeringsregels bepalen hoe de benodigde gegevens (input data) wordt uitgevraagd. Dit kan op verschillende manieren gebeuren zoals een vraag aan een initiatiefnemer of een bevraging van een registratie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Omgevingswaarde</td>
      <td><p>Een norm die voor (een onderdeel van) de fysieke leefomgeving de gewenste staat of kwaliteit, de toelaatbare belasting door activiteiten en/of de toelaatbare concentratie of depositie van stoffen als beleidsdoel vastlegt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Norm</td>
      <td><p>Omgevingswaarde of een omgevingsnorm, met een normatief karakter, die beschreven worden middels normwaarden. Een normwaarde kan kwalitatief of kwantitatief zijn.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Omgevingsnorm</td>
      <td><p>Een norm over de fysieke leefomgeving die in een kwantitatieve of kwalitatieve waarde wordt uitgedrukt en geen omgevingswaarde is.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Omgevingswaarderegel</td>
      <td><p>Omgevingswaarderegel
De beschrijving van een juridische regel gericht op een gestelde omgevingswaarde.
Het betreft hier een juridische regel die verplichtingen oplegt aan het bevoegd gezag dat deze regel opstelt.
Een omgevingswaarderegel is alleen gericht op een Omgevingswaarde (eventueel meerdere).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Activiteit</td>
      <td><p>Ieder menselijk handelen waarbij, of ieder menselijk nalaten waardoor een verandering of effect in de (fysieke) leefomgeving wordt of kan worden bewerkstelligd.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verzoek</td>
      <td><p>Een vraag aan het bevoegd gezag om een speficieke product of dienst te leveren.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Specificatie</td>
      <td><p>Gesplitste opgave, vermelding van de afzonderlijke onderdelen waaruit een verzameling of een totaal bestaat</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Gemachtigde</td>
      <td><p>Een Natuurlijk Persoon of een Niet Natuurlijk Persoon die als vertegenwoordiger van een Initiatiefnemer optreedt. (uit: IMAM)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Project</td>
      <td><p>Geheel van activiteiten uitgevoerd in een tijdelijk samenwerkingsverband gericht op het binnen bepaalde randvoorwaarden (bv. tijd, geld) bereiken van een vooraf gedefinieerd resultaat.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Projectactiviteit</td>
      <td><p>Activiteit binnen het project</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Projectlocatie</td>
      <td><p>Fysieke locatie waar een project betrekking op heeft of wordt uitgevoerd.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Locatie</td>
      <td><p>De locatie beschrijft middels co√∂rdinaten de ruimtelijke dimensie of ruimtelijke afbakening van een regel of van een objecttype die in de regel beschreven wordt. (CIMOW)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">ZAAK</td>
      <td><p><font color="#610e6a">Een samenhangende hoeveelheid werk met een welgedefinieerde aanleiding en een welgedefinieerd eindresultaat, waarvan kwaliteit en doorlooptijd bewaakt moeten worden.</font></p></td>
    </tr>
  </tbody>
</table>

### Onderwijs (GGM)

<figure align="center">
  <img width="1591" src="2023-12-13_GGM_data-objecten/Onderwijs__GGM_.svg" alt="Onderwijs (GGM)">
  <figcaption><i>Onderwijs (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Doorgeleiding OM</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Procesverbaal Onderwijs</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">INGESCHREVEN PERSOON</td>
      <td><p>Een INGEZETENE of NIET-INGEZETENE</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">AanvraagOfMelding</td>
      <td><p>Komt overeen met een VJV</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Klacht Leerlingenvervoer</td>
      <td><p>Een uiting van ontevredenheid over het vervoer van leerlingen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Beslissing</td>
      <td><p>Selectie van een voorstelbare werkelijkheid (voorkeursvariant) uit een aantal mogelijke werkelijkheden (varianten) op basis van een verzameling van criteria.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Onderwijs</td>
      <td><p>566</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Leerjaar</td>
      <td><p>Is de codering van het jaar of het niveau waarin de leerling onderwijs volgt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Startkwalificatie</td>
      <td><p>Diploma van een opleiding als bedoeld in de WEB of een diploma hoger algemeen voortgezet onderwijs of voorbereidend wetenschappelijk onderwijs als bedoeld in de WVO;</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Uitschrijving</td>
      <td><p>Beeindiging van een inschrijving van een leerling bij een school</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Ouder Of Verzorger</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Leerling</td>
      <td><p>Mens die een opleiding volgt, heeft gevolgd of gaat volgen of opgaat of is opgegaan voor een toets. (Bron: KOI)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Onderwijsloopbaan</td>
      <td><p>Loopbaan als leerling in het onderwijs; loopbaan als leerling op school; tijd die iemand als leerling heeft doorgebracht op school, vaak met de bijgedachte aan de daarbij opgedane kennis en ervaring; tijd die men schoolgegaan heeft; onderwijscarri√®re; schoolloopbaan; schoolcarri√®re; schooltijd; de schooljaren</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Inschrijving</td>
      <td><p>Deelname van iemand aan een opleiding bij een onderwijsinstelling.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Locatie</td>
      <td><p>De locatie beschrijft middels coördinaten de ruimtelijke dimensie of ruimtelijke afbakening van een regel of van een objecttype die in de regel beschreven wordt. (CIMOW)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Loopbaanstap</td>
      <td><p>Een logische en ook uitdagende stap naar een volgende functie binnen dezelfde functiefamilie of een andere, op hetzelfde schaalniveau of op een schaalniveau hoger.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">School</td>
      <td><p>Gebouw in gebruik voor basis, middelbaar of hoger onderwijs.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Onderwijsniveau</td>
      <td><p>De hoogte van een soort onderwijs in relatie tot andere soorten onderwijs</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Onderwijssoort</td>
      <td><p>Typologie voor onderwijs</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Onderwijstype</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Ziekmelding Leerlingenvervoer</td>
      <td><p>Een melding van een zieke leerling die recht heeft op vervoer van en naar onderwijs.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Vastgoedobject</td>
      <td><p>Perceel of vastgoed waar de gemeente een zakelijk recht heeft, en optioneel verhuurd, verpacht of anderzinds aan een derde partij.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Sportlocatie</td>
      <td><p>Locatie waar de betreffende sport plaatsvindt</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">NIET NATUURLIJK PERSOON</td>
      <td><p>Een INGESCHREVEN NIET-NATUURLIJK PERSOON of een ANDER BUITENLANDS NIET-NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Verzuimmelding</td>
      <td><p>Een melding dat een leerling niet op school verschijnt. De school moet actie ondernemen naar de leerling (en zijn ouders). Een school moet het verzuim melden bij de gemeente.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Vrijstelling</td>
      <td></td>
    </tr>
  </tbody>
</table>

### Organisatie (GGM)

<figure align="center">
  <img width="865" src="2023-12-13_GGM_data-objecten/Organisatie__GGM_.svg" alt="Organisatie (GGM)">
  <figcaption><i>Organisatie (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Opdrachtgever</td>
      <td><p>Persoon die een opdracht verstrekt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Opdrachtnemer</td>
      <td><p>Partij die een opdracht aanvaardt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Dienstverband</td>
      <td><p>De rechtsbetrekking tussen werkgever en werknemer zoals vastgelegd in een arbeidsovereenkomst.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Plan</td>
      <td><p>Project waarin woningen worden gerealiseerd</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Vacature</td>
      <td><p>Een arbeidsplaats binnen een bedrijf of organisatie die nog gevuld dient te worden door werkzoekenden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Organisatie</td>
      <td><p>130</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Functie</td>
      <td><p>Een samenhangende verzameling van rollen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Programma</td>
      <td><p>Een tijdelijke, flexibele organisatiestructuur, die is opgezet om de implementatie van een verzameling met elkaar samenhangende projecten en activiteiten te co√∂rdineren, te sturen en te controleren teneinde te zorgen voor de realisatie van de eindresultaten en benefits die zijn gerelateerd aan de strategische doelstellingen van de organisatie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Project</td>
      <td><p>Geheel van activiteiten uitgevoerd in een tijdelijk samenwerkingsverband gericht op het binnen bepaalde randvoorwaarden (bv. tijd, geld) bereiken van een vooraf gedefinieerd resultaat.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">ORGANISATORISCHE EENHEID</td>
      <td><p><font color="#610e6a">Het deel van een functioneel afgebakend onderdeel binnen de organisatie dat haar activiteiten uitvoert binnen een VESTIGING VAN ZAAKBEHANDELENDE ORGANISATIE en die verantwoordelijk is voor de behandeling van zaken.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Functiehuis</td>
      <td><p>Model waarin functies van een organisatie worden beschreven.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Kostenplaats</td>
      <td><p>Rekening waaraan boekingen in een financi√´le administratie samen worden toegeschreven.</p></td>
    </tr>
  </tbody>
</table>

### Parkeren (GGM)

<figure align="center">
  <img width="2317" src="2023-12-13_GGM_data-objecten/Parkeren__GGM_.svg" alt="Parkeren (GGM)">
  <figcaption><i>Parkeren (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Leverancier</td>
      <td><p>Een niet-natuurlijk persoon die een product of dienst levert aan de organisatie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Parkeren</td>
      <td><p>502</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Mulder Feit</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Belprovider</td>
      <td><p>Leverancier of dienstverlener van modiele beldiensten</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Parkeerrecht</td>
      <td><p>Het onder bepaalde voorwaarden (zoals betaling parkeerbelasting of parkeergeld) ontstane recht om een voertuig gedurende een bepaalde of onbepaalde periode op een daartoe benoemde parkeerplaats of in/op een daartoe benoemde parkeervoorziening te parkeren.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Parkeergarage</td>
      <td><p>Open constructie die geheel of gedeeltelijk in gebruik is als voorziening voor het parkeren van voertuigen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Parkeerscan</td>
      <td><p>Waarneming van een parkeeractie door een scanauto</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Naheffing</td>
      <td><p>Het achteraf vorderen van te weinig betaalde belasting</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Voertuig</td>
      <td><p>Vervoermiddel bestemd voor het verkeer over wegen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Parkeervlak</td>
      <td><p>Parkeergelegenheid bestemd voor het parkeren van √©√©n of meerdere voertuigen direct langs de doorgaande weg gelegen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Productsoort</td>
      <td><p>Typologie van een product</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Parkeervergunning</td>
      <td><p>Offici√´le toestemming dat je op een bepaalde plek mag parkeren</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Perkeerzone</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Productgroep</td>
      <td><p>Groepering van producten</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Straatsectie</td>
      <td><p>Gedeelte van een straat</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Doelgroepenplaatsen</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Zonesoort</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">MEDEWERKER</td>
      <td><p><font color="#610e6a">Een medewerker van de organisatie die zaken behandelt uit hoofde van zijn of haar functie binnen een ORGANISATORISCHE EENHEID.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">INGEZETENE</td>
      <td><p>Een individueel menselijk wezen, ingeschreven in het Nederlands Bevolkingsregister.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">RECHTSPERSOON</td>
      <td><p>Een NATUURLIJK PERSOON of een NIET-NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">OBJECT</td>
      <td><p><font color="#610e6a">Het OBJECT waarop een ZAAK betrekking kan hebben zijnde één of meer voorkomens van de in het RSGB en het RGBZ onderscheiden objecttypen.</font></p></td>
    </tr>
  </tbody>
</table>

### Participatie (GGM)

<figure align="center">
  <img width="2287" src="2023-12-13_GGM_data-objecten/Participatie__GGM_.svg" alt="Participatie (GGM)">
  <figcaption><i>Participatie (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">INGESCHREVEN PERSOON</td>
      <td><p>Een INGEZETENE of NIET-INGEZETENE</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Client</td>
      <td><p>Een ingeschreven persoon die gebruik maakt van producten en diensten van de gemeente.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Participatie</td>
      <td><p>405</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Fraudegegevens</td>
      <td><p>Gegevens met betrekking tot fraude</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Fraudesoort</td>
      <td><p>Typering van een fraude</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Informatie Dakloosheid</td>
      <td><p>Informatie met betrekking tot dakloosheid</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Trajectsoort</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">UitkeringsRun</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Regeling</td>
      <td><p>Verzamelnaam voor AMvB‚Äôs, Ministeri√´le regelingen, lokale verordeningen, etc. De regeling is de meest concrete uitleg van de wet.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Regelingsoort</td>
      <td><p>Typologie van een regeling</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Taalniveau</td>
      <td><p>Het duiden van bepaald gebruik en begrijpelijkheid van een taal. Het is er om verschil in taalvaardigheid te kunnen meten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Tegenprestatie</td>
      <td><p>Verplichting die tegenover een prestatie staat</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Tegenprestatiehoogte</td>
      <td><p>De hoogte van de tegenprestatie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">ComponentSoort</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Inkomensvoorzieningsoort</td>
      <td><p>Typering van een inkomensvoorziening</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Inkomensvoorziening</td>
      <td><p>Een regeling die zorg draag voor een inkomen confom de landelijke wetgeving</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Component</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Traject</td>
      <td><p>Samenstel van achtereenvolgens uit te voeren en onderling samenhangende deelhandelingen of van opeenvolgende stadia in een proces, voorgesteld als een route die via opeenvolgende bestemmingen naar de eindbestemming voert.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Reden Beeindiging</td>
      <td><p>argumentatie voor stopzetting</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Doelgroep</td>
      <td><p>Een groep mensen of klanten die een bedrijf of organisatie wil benaderen om een product, dienst of informatie onder de aandacht te brengen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Participatiedossier</td>
      <td><p>Overzicht van alle informatie over integratie en participatie betreffende een inwoner</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">TrajectActiviteit</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">TrajectActiviteitsoort</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Clientbegeleider</td>
      <td><p>De persoon die verantwoordelijk is voor het opstellen en uitvoeren van het  ondersteuningsplan in samenwering met de client en personen uit zijn/haar omgeving .</p></td>
    </tr>
  </tbody>
</table>

### Referentielijsten (GGM)

<figure align="center">
  <img width="229" src="2023-12-13_GGM_data-objecten/Referentielijsten__GGM_.svg" alt="Referentielijsten (GGM)">
  <figcaption><i>Referentielijsten (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Referentielijsten</td>
      <td><p>343</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">AANDUIDING VERBLIJFSRECHT</td>
      <td><p>Aanduiding in verband met het verblijfsrecht van de vreemdeling.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">AUTORITEIT AFGIFTE NEDERLANDS REISDOCUMENT</td>
      <td><p>Een opsomming van de diverse coderingen van de autoriteiten die een Nederlands reisdocument kunnen afgegeven</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verblijfstitel</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">AARD AANTEKENING</td>
      <td><p>Een opsomming van de diverse aarden van de aantekeningen zoals door de Dienst Kadaster is onderscheiden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">AARD ZAKELIJK RECHT</td>
      <td><p>Een opsomming van de diverse aarden van het zakelijk rechten zoals door de Dienst Kadaster is onderscheiden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">AARD FILIATIE</td>
      <td><p>Een opsomming van redenen waarom kadastrale onroerende zaken aan elkaar gerelateerd kunnen zijn</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">ACADEMISCHE TITEL</td>
      <td><p>Een formeel via het Staatsblad gepubliceerde aanduiding van een wetenschappelijke of andere graad van opleiding welke bij aanschrijving voorafgaat aan de voornamen (dan wel de daarvan afgeleide naamgegevens) dan wel volgt op de achternaam.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">AKR KADASTRALE GEMEENTECODE</td>
      <td><p>De door de Dienst Kadaster onderkende AKR codes voor  kadastrale gemeenten</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">CULTUURCODE BEBOUWD</td>
      <td><p>De mogelijke cultuurcodes bebouwd conform de waardelijst Cultuurcode Bebouwd van het Kadaster</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">CULTUURCODE ONBEBOUWD</td>
      <td><p>De mogelijke cultuurcodes bebouwd conform de waardelijst Cultuurcode Bebouwd van het Kadaster</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">WOZ DEELOBJECTCODE</td>
      <td><p>De mogelijke codes  waarin een soort object kan worden uitgedrukt conform de uniforme deelobjectcodelijst van de Waarderingskamer</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">KADASTRALE GEMEENTE</td>
      <td><p>De mogelijke onderscheiden gedeeltes van het grondgebied van Nederland, volgens de Dienst Kadaster en de Openbare Registers, zoals nader omschreven in het Kadasterbesluit</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">LAND/GEBIED</td>
      <td><p>Een gedeelte van de wereld met een eigen bestuur, waarvan de soevereiniteit in ieder geval door Nederland is erkend.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Provincie</td>
      <td><p>Een gedeelte van de wereld met een eigen bestuur, waarvan de soevereiniteit in ieder geval door Nederland is erkend.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">PARTIJ</td>
      <td><p>Een PARTIJ die bij de centrale voorzieningen van de BRP bekend is.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">REDEN VERKRIJGING NATIONALITEIT</td>
      <td><p>Tabel waarin de redenen staan voor opname van de Nederlandse nationaliteit.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">REDEN VERLIES NATIONALITEIT</td>
      <td><p>Tabel waarin de redenen staan voor beëindiging van de Nederlandse nationaliteit.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">REISDOCUMENTSOORT</td>
      <td><p>Een opsomming van de modellen van de Nederlandse reisdocumenten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">SBI ACTIVITEIT</td>
      <td><p>De hiërarchische indeling van economische activiteiten conform SBI (Standaard Bedrijfsindeling).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">SOORT GROOTTE</td>
      <td><p>Een opsomming van de  soorten grootte zoals die kunnen voorkomen in een aktetekst van het Kadaster  en aanduiden op welke wijze de grootte van een perceel is vastgesteld conform de waardelijst SoortGrootte van het Kadaster</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">SOORT WOZ-OBJECT</td>
      <td><p>De mogelijke codes  waarin een soort object kan worden uitgedrukt conform de uniforme soort objectcodelijst van de Waarderingskamer</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">VALUTASOORT</td>
      <td><p>De mogelijke munteenheden waarin een geldbedrag kan worden uitgedrukt conform de waardelijst Valutasoort van het Kadaster</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">LAND</td>
      <td><p>Een gedeelte van de wereld met een eigen bestuur, waarvan de soevereiniteit in ieder geval door Nederland is erkend.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">NATIONALITEIT</td>
      <td><p>De hoedanigheid van tot een bepaalde natie te behoren.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">VALUTA</td>
      <td><p>De hoedanigheid van tot een bepaalde natie te behoren.</p></td>
    </tr>
  </tbody>
</table>

### Relatieklasse (GGM)

<figure align="center">
  <img width="229" src="2023-12-13_GGM_data-objecten/Relatieklasse__GGM_.svg" alt="Relatieklasse (GGM)">
  <figcaption><i>Relatieklasse (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Relatieklasse</td>
      <td><p>284</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">LOCATIEAANDUIDING ADRES WOZ OBJECT</td>
      <td><p>Nadere aanduiding van het WOZ-object middels een locatieomschrijving van ADRESSEERBAAR OBJECT AANDUIDING.</p></td>
    </tr>
  </tbody>
</table>

### RGBZ Model (GGM)

<figure align="center">
  <img width="2983" src="2023-12-13_GGM_data-objecten/RGBZ_Model__GGM_.svg" alt="RGBZ Model (GGM)">
  <figcaption><i>RGBZ Model (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Verkeersbesluit</td>
      <td><p>Een besluit van een wegbeheerder om een bepaald verkeersteken te plaatsen, te wijzigen of in te trekken of een bepaalde fysieke maatregel te treffen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Bankafschriftregel</td>
      <td><p>Een item op het bankafschrift</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Proces-verbaal-MOOR-melding</td>
      <td><p>Officieel op papier gesteld verslag met betrekking tot heen MOOR-melding</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Rapportagemoment</td>
      <td><p>Een vantevoren bepaald tijdstip waarom een gegevensanalyse wordt uitgevoerd</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">RECHTSPERSOON</td>
      <td><p>Een NATUURLIJK PERSOON of een NIET-NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">AanvraagOfMelding</td>
      <td><p>Komt overeen met een VJV</p>
<p>Bron: GEM<em>VJV (Distinct op REQ</em>ID)
ID: REQ_ID</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Bankrekening</td>
      <td><p>Een rekening-courant bij een bank</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Subsidie</td>
      <td><p>Aan derden toegekende financiele middelen, bestemd voor het uitvoeren van bepaalde activiteiten</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Telefoononderwerp</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Balieafspraak</td>
      <td><p>Balieafspraken zijn afspraken voor een klantcontact. Dit ongeacht of deze werkelijk heeft plaatsgevonden of gaat plaatsvinden, soms liggen deze in de toekomst of is iemand niet op komen dagen, of iets anders waardoor het klantcontact nog niet heeft plaatsgevonden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Telefoontje</td>
      <td><p>De telefoontjes zijn alle keren dat iemand naar de gemeente belt en het telefoonsysteem neemt deze telefoontjes aan. Ongeacht of iemand daarna ophangt, door het systeem uit de wachtrij wordt gezet, doorverbonden wordt met een derde partij of er werkelijk wordt opgenomen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">VTH-Melding</td>
      <td><p>Melding met betrekking tot Vergunningen, Toezicht en Handhaving</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">RGBZ Model</td>
      <td><p>206</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Betaling</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Identificatiekenmerk</td>
      <td><p>Nodig voor archivering om verschillende typen identificatie te kunnen onderscheiden:</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">ENKELVOUDIG DOCUMENT</td>
      <td><p><font color="#610e6a">Een DOCUMENT waarvan aard, omvang en/of vorm aanleiding geven het als één geheel te behandelen en te beheren.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">DOCUMENTTYPE</td>
      <td><p><font color="#610e6a">Aanduiding van de aard van een DOCUMENT zoals gehanteerd door de zaakbehandelende organisatie</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">SAMENGESTELD DOCUMENT</td>
      <td><p><font color="#610e6a">Een DOCUMENT waarbinnen twee of meer ENKELVOUDIGe DOCUMENTen onderscheiden worden die vanwege gezamenlijke vervaardiging en/of ontvangst en/of vanwege aard en/of omvang als één geheel beschouwd moeten worden dan wel behandeld worden.,</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Offerte</td>
      <td><p>Aanbod, aanbieding of voorstel van goederen of diensten waarin opgave is gedaan van de prijs.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">STATUS</td>
      <td><p><font color="#610e6a">Een aanduiding van de stand van zaken van een zaak op basis van betekenisvol behaald resultaat voor de initiator van de zaak.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">BESLUITTYPE</td>
      <td><p><font color="#610e6a">Generieke aanduiding van de aard van een besluit</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">STATUSTYPE</td>
      <td><p><font color="#610e6a">Generieke aanduiding van de aard van een STATUS</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">BESLUIT</td>
      <td><p><font color="#610e6a">Een na overweging of beraadslaging vastgestelde beslissing voor een individueel of concreet geval.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">VESTIGING VAN ZAAKBEHANDELENDE ORGANISATIE</td>
      <td><p><font color="#610e6a">Een VESTIGING van een onderneming of rechtspersoon zijnde de zaakbehandelende organisatie.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">DOCUMENT</td>
      <td><p><font color="#610e6a">Geheel van gegevens met een eigen identiteit ongeacht zijn vorm, met de bijbehorende metadata ontvangen of opgemaakt door een natuurlijke en/of rechtspersoon bij de uitvoering van taken, zijnde een ENKELVOUDIG DOCUMENT of een SAMENGESTELD DOCUMENT.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Deelproces</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Deelprocestype</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bedrijfsprocestype</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bedrijfsproces</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">ORGANISATORISCHE EENHEID</td>
      <td><p><font color="#610e6a">Het deel van een functioneel afgebakend onderdeel binnen de organisatie dat haar activiteiten uitvoert binnen een VESTIGING VAN ZAAKBEHANDELENDE ORGANISATIE en die verantwoordelijk is voor de behandeling van zaken.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">ZAAKTYPE</td>
      <td><p><font color="#610e6a">Generieke aanduiding van de aard van een zaak</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Heffing</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Klantcontact</td>
      <td><p>Klantcontacten zijn contactmomenten die werkelijk hebben plaatsgevonden, terwijl Balieafspraken afspraken zijn voor een klantcontact. Dit ongeacht of deze werkelijk heeft plaatsgevonden, soms liggen deze in de toekomst of is iemand niet op komen dagen, of iets anders waardoor het klantcontact nog niet heeft plaatsgevonden.</p>
<p>Hetzelfde geldt voor de telefoontjes, de klantcontacten komen uit levelOneData, dat zijn alle telefoontjes die werkelijk met een medewerker (of een gedelegeerde) hebben plaatsgevonden (soms zelfs meerdere binnen 1 telefoontje).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">ZAAK - Origineel</td>
      <td><p><font color="#610e6a">Een samenhangende hoeveelheid werk met een welgedefinieerde aanleiding en een welgedefinieerd eindresultaat, waarvan kwaliteit en doorlooptijd bewaakt moeten worden.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">BETROKKENE</td>
      <td><p><font color="#610e6a">Een SUBJECT, zijnde een NATUURLIJK PERSOON, NIET-NATUURLIJK PERSOON of VESTIGING, ORGANISATORISCHE EENHEID (binnen een vestiging van de zaak-behandelende niet-natuurlijk persoon), of MEDEWERKER (van die organisatorische eenheid) die een rol kan spelen bij een ZAAK.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">ZAAK</td>
      <td><p><font color="#610e6a">Een samenhangende hoeveelheid werk met een welgedefinieerde aanleiding en een welgedefinieerd eindresultaat, waarvan kwaliteit en doorlooptijd bewaakt moeten worden.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">MEDEWERKER</td>
      <td><p><font color="#610e6a">Een medewerker van de organisatie die zaken behandelt uit hoofde van zijn of haar functie binnen een ORGANISATORISCHE EENHEID.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">OBJECT</td>
      <td><p><font color="#610e6a">Het OBJECT waarop een ZAAK betrekking kan hebben zijnde één of meer voorkomens van de in het RSGB en het RGBZ onderscheiden objecttypen.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Soorten Klantcontact</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">NIET NATUURLIJK PERSOON</td>
      <td><p>Een INGESCHREVEN NIET-NATUURLIJK PERSOON of een ANDER BUITENLANDS NIET-NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Project</td>
      <td><p>Geheel van activiteiten uitgevoerd in een tijdelijk samenwerkingsverband gericht op het binnen bepaalde randvoorwaarden (bv. tijd, geld) bereiken van een vooraf gedefinieerd resultaat.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Uitvoerende instantie</td>
      <td><p>Onderdeel van het bevoegd gezag dat uitvoering geeft aan wetten en besluiten</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Formuliersoort</td>
      <td><p>Bron: GEM<em>FORM
ID: FORM</em>ID</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Heffingsverordening</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">ProductType</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">ProductOfDienst</td>
      <td><p>Bron: QP<em>CALENDAR.CFM</em>SERVICES</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">NATUURLIJK PERSOON</td>
      <td><p>Een INGESCHREVEN PERSOON of ANDER NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Kenmerken ZAAK</td>
      <td><p><font color="#610e6a">Identificatie-gegevens over de zaak in andere administraties</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Schouwronde</td>
      <td><p>Activiteit om te controleren of de opdrachtnemer aan de afspraken voldoet.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Dienst</td>
      <td><p>Het uitvoeren van werkzaamheden met een continu of periodiek karakter om waarde te realiseren voor een afnemer.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Archiefstuk</td>
      <td><p>Bijeengebrachte informatie, ongeacht het medium, die wordt gecre√´erd, ontvangen en gearchiveerd door een bureau, een instelling, een organisatie of een individu met het oog op het nakomen van wettelijke verplichtingen of het uitvoeren van zakelijke transacties.(AAT)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Heffinggrondslag</td>
      <td><p>De maatstaf waarop een belasting is gebaseerd, het bedrag op basis waarvan een bepaalde belasting wordt geheven of de premie voor sociale zekerheid wordt vastgesteld.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">BUURT</td>
      <td><p>Een aaneengesloten gedeelte van een wijk, waarvan de grenzen zo veel mogelijk gebaseerd zijn op topografische elementen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Applicatie</td>
      <td><p>Een applicatiecomponent die gericht is op het ondersteunen van eindgebruikers.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">VTHzaak</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Stremming</td>
      <td><p>Situatie waarbij de doorstroming van het (vaar)wegverkeer plaatselijk is geblokkeerd als gevolg van een incident</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Product</td>
      <td><p>Het resultaat van een proces dat in het economisch verkeer een waarde bezit.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Kostenplaats</td>
      <td><p>Rekening waaraan boekingen in een financi√´le administratie samen worden toegeschreven.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Heffingsoort</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">PAND</td>
      <td><p>De kleinste bij de totstandkoming functioneel en bouwkundig-constructief zelfstandige eenheid die direct en duurzaam met de aarde is verbonden en betreedbaar en afsluitbaar is.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Melding</td>
      <td><p>De betekenisvolle formulering van een waargenomen feit, waaraan een waarde kan worden toegekend</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Leverancier</td>
      <td><p>Een niet-natuurlijk persoon die een product of dienst levert aan de organisatie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">OPENBARE RUIMTE</td>
      <td><p>Een door het bevoegde gemeentelijke orgaan als zodanig aangewezen en van een naam voorziene buitenruimte die binnen één woonplaats is gelegen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Parkeerscan</td>
      <td><p>Waarneming van een parkeeractie door een scanauto</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Startformulier Aanbesteden</td>
      <td><p>Formulier voor het starten van een aanbeseding</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">KADASTRALE ONROERENDE ZAAK</td>
      <td><p>Een geregistreerd goed waarvoor bij overdracht of vestiging van rechten inschrijving in de openbare registers van het Kadaster is vereist zijnde een KADASTRAAL PERCEEL of een APPARTEMENTSRECHT.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Formulier Verlenging Inhuur</td>
      <td><p>Formulier ten behoeve van verlenging inhuur personeel</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Samensteller</td>
      <td><p>Iemand die stukken informatie samenbrengt in tentoonstelingen, presentaties en naslagwerken.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">INGEZETENE</td>
      <td><p>Een individueel menselijk wezen, ingeschreven in het Nederlands Bevolkingsregister.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Aanbesteding Inhuur</td>
      <td><p>Aanbesteding voor inhuur van personen of diensten</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Leerplichtambtenaar</td>
      <td><p>Ambtenaar die toezicht houdt op de uitvoering van de leerplichtwet.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Voertuig</td>
      <td><p>Vervoermiddel bestemd voor het verkeer over wegen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Formulier Inhuur</td>
      <td><p>Formulier ten behoeve van inhuur personeel</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Clientbegeleider</td>
      <td><p>De persoon die verantwoordelijk is voor het opstellen en uitvoeren van het  ondersteuningsplan in samenwering met de client en personen uit zijn/haar omgeving .</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">STANDPLAATS</td>
      <td><p>Een door het bevoegde gemeentelijke orgaan als zodanig aangewezen terrein of gedeelte daarvan dat bestemd is voor het permanent plaatsen van een niet direct en niet duurzaam met de aarde verbonden en voor woon -, bedrijfsmatige, of recreatieve doeleinden geschikte ruimte.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Gunning</td>
      <td><p>Gunning van een (enkel of meervoudige) onderhandse aanbesteding, of een nationale of Europese aanbesteding 
Of voor levering personeel</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Werknemer</td>
      <td><p>De contractuele wederpartij van de werkgever bij de arbeidsovereenkomst.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">LIGPLAATS</td>
      <td><p>Een door het bevoegde gemeentelijke orgaan als zodanig aangewezen plaats in het water al dan niet aangevuld met een op de oever aanwezig terrein of een gedeelte daarvan, die bestemd is voor het permanent afmeren van een voor woon-, bedrijfsmatige of recreatieve doeleinden geschikt vaartuig.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Notitie</td>
      <td><p>Korte, zakelijke uiteenzetting op schrift</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Dienstverband</td>
      <td><p>De rechtsbetrekking tussen werkgever en werknemer zoals vastgelegd in een arbeidsovereenkomst.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">MAATSCHAPPELIJKE ACTIVITEIT</td>
      <td><p>Een verband tussen één of meer personen met voldoende mate van zelfstandigheid, inbreng van arbeid of middelen, winstoogmerk en extern optreden (i.g.v. een onderneming) dan wel een in een organisatorisch verband, dat toebehoort aan een niet-natuurlijk persoon welke registratieplichtig is, uitgeoefende activiteit die niet valt onder de criteria voor onderneming of bedrijfsmatigheid welke adresseerbaar is middels ofwel een vestiging ofwel het adres van een bepaalde vertegenwoordiger (i.g.v. een niet-ondernemings-activiteit).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Aanvraag Inkooporder</td>
      <td><p>het betreft hier het formulier 'Aanvraag Inkooporder'</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Vaartuig</td>
      <td><p>Een zee- of binnenvaartuig, tot de vaart gebruikt of bestemd, daaronder begrepen drijvende werktuigen, zoals baggerwerktuigen, kranen, bokken, elevators, alsmede woonschepen, glijboten en ponten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Functie</td>
      <td><p>Een samenhangende verzameling van rollen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">KADASTRAAL PERCEEL</td>
      <td><p>Een KADASTRALE ONROERENDE ZAAK dat een kadastraal geïdentificeerd en met kadastrale grenzen begrensd deel van het Nederlands grondgebied betreft (art. 1 lid 1 Kadasterwet).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Subsidieprogramma</td>
      <td><p>Programma waarin meerdere subsidies worden verleend vanuit een bepaalde samenhang</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">WATERDEEL</td>
      <td><p>Kleinste functioneel onafhankelijk stukje water met gelijkblijvende, homogene eigenschappen en relaties dat er binnen het objecttype Water van NEN 3610 wordt onderscheiden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">HUISHOUDEN</td>
      <td><p>Een duurzame samenlevingsvorm van een of meer natuurlijke personen binnen een VERBLIJFSOBJECT, STANDPLAATS of LIGPLAATS.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">INRICHTINGSELEMENT</td>
      <td><p>Ruimtelijk object al dan niet ter detaillering dan wel ter inrichting van de
overige benoemde ruimtelijke objecten of een ander inrichtingselement.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">KUNSTWERKDEEL</td>
      <td><p>Onderdeel van een civiel-technisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">BENOEMD OBJECT</td>
      <td><p>Een GEBOUWD OBJECT of een BENOEMD TERREIN</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">NUMMERAANDUIDING</td>
      <td><p>Een door het bevoegde gemeentelijke orgaan als zodanig toegekende aanduiding van een VERBLIJFSOBJECT, een STANDPLAATS of een LIGPLAATS.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Onbestemd Adres</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Verzoek</td>
      <td><p>Een vraag aan het bevoegd gezag om een speficieke product of dienst te leveren.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Grondslag</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Aanbesteding</td>
      <td><p>Kan een (enkel of meervoudige) onderhandse aanbesteding, of een nationale of Europese aanbesteding</p></td>
    </tr>
  </tbody>
</table>

### RSGB Model (GGM)

<figure align="center">
  <img width="5419" src="2023-12-13_GGM_data-objecten/RSGB_Model__GGM_.svg" alt="RSGB Model (GGM)">
  <figcaption><i>RSGB Model (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Inkomensvoorziening</td>
      <td><p>Een regeling die zorg draag voor een inkomen confom de landelijke wetgeving</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Adresaanduiding</td>
      <td><p>De adresaanduiding van het WOZ-OBJECT</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">LocatieOnroerendeZaak</td>
      <td><p>Locatie van een geregistreerd goed</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Regeling</td>
      <td><p>Verzamelnaam voor AMvB‚Äôs, Ministeri√´le regelingen, lokale verordeningen, etc. De regeling is de meest concrete uitleg van de wet.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Fraudegegevens</td>
      <td><p>Gegevens met betrekking tot fraude</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">WOZ-Belang</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Leerling</td>
      <td><p>Mens die een opleiding volgt, heeft gevolgd of gaat volgen of opgaat of is opgegaan voor een toets. (Bron: KOI)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Winkelvloeroppervlak</td>
      <td><p>Gemeten oppervlakte in vierkante meters van een winkel</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">kp_betrokken_bij</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Objectrelatie</td>
      <td><p>Relatie tot een object</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Client</td>
      <td><p>Een ingeschreven persoon die gebruik maakt van producten en diensten van de gemeente.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Raadslid</td>
      <td><p>Iemand die behoort de gemeenteraad</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">LOCATIEAANDUIDING WOZ OBJECT</td>
      <td><p>Nadere aanduiding van het WOZ-object</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">gebruiksdoel</td>
      <td><p>Een aanduiding va alle waarden waarmee het gebruiksdoel van een object kan 
worden verbijzonderd.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">kp_onstaan_uit</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">OBJECT</td>
      <td><p><font color="#610e6a">Het OBJECT waarop een ZAAK betrekking kan hebben zijnde één of meer voorkomens van de in het RSGB en het RGBZ onderscheiden objecttypen.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Ouder Of Verzorger</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Collegelid</td>
      <td><p>Iemand die behoort het college van burgemeester en wethouders</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">NAD_AanvullingBRP</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Gebruiksdoel</td>
      <td><p>Een aanduiding va alle waarden waarmee het gebruiksdoel van een object kan worden verbijzonderd.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Areaal</td>
      <td><p>Het verspreidingsgebied van een een soort, een levensgemeenschap of een biotooptype.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Splitsingstekeningreferentie</td>
      <td><p><font color="#0f0f0f">Verwijzing naar de splitsingstekening behorende bij de APPARTEMENTSRECHTSPLITSING</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Adresaanduiding</td>
      <td><p>De adresaanduiding van het WOZ-OBJECT</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Parkeervergunning</td>
      <td><p>Offici√´le toestemming dat je op een bepaalde plek mag parkeren</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Indiener</td>
      <td><p>Persoon die meldiing of aanvraag doet</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Vastgoed Contract</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Taak</td>
      <td><p>Een samenhangende set activiteiten in het kader van een subsidie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">RSGB Model</td>
      <td><p>283</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">PersoonAlleenNaam</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Onbestemd Adres</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">PersoonNAW</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">APPARTEMENTSRECHTSPLITSING</td>
      <td><p>Het recht op een stuk grond of op een gebouw met toebehoren op de daarbij behorende grond met toebehoren is gesplitst in appartementsrechten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">PersoonBSN</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">PersoonBSNenNaw</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">WOZ-DEELOBJECT</td>
      <td><p>Aanduiding van afzonderlijke elementen (delen van het object, bijzondere waarderelevante factoren) die voor de onderbouwing van de vastgestelde waarde van belang zijn.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">WOZ-WAARDE</td>
      <td><p>De op grond van de Wet WOZ vastgestelde waarde van het WOZ-object naar de genoemde waardepeildatum.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">WOZ-OBJECT</td>
      <td><p>De onroerende zaak waarvan op grond van de Wet WOZ de waarde moet worden bepaald en vastgesteld.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">WIJK</td>
      <td><p>Een aaneengesloten gedeelte van het grondgebied van een gemeente, waarvan de grenzen zo veel mogelijk zijn gebaseerd op sociaal-geografische kenmerken.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">BENOEMD OBJECT</td>
      <td><p>Een GEBOUWD OBJECT of een BENOEMD TERREIN</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">GEBOUWD OBJECT</td>
      <td><p>Een VERBLIJFSOBJECT of een OVERIG GEBOUWD OBJECT</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">BENOEMD TERREIN</td>
      <td><p>Een STANDPLAATS, LIGPLAATS, of een OVERIG BENOEMD TERREIN.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">BUURT</td>
      <td><p>Een aaneengesloten gedeelte van een wijk, waarvan de grenzen zo veel mogelijk gebaseerd zijn op topografische elementen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Briefadres</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">NUMMERAANDUIDING</td>
      <td><p>Een door het bevoegde gemeentelijke orgaan als zodanig toegekende aanduiding van een VERBLIJFSOBJECT, een STANDPLAATS of een LIGPLAATS.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Gebied</td>
      <td><p>Een aaneengesloten gedeelte van een wijk, waarvan de grenzen zo veel mogelijk gebaseerd zijn op topografische elementen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">HUISHOUDEN</td>
      <td><p>Een duurzame samenlevingsvorm van een of meer natuurlijke personen binnen een VERBLIJFSOBJECT, STANDPLAATS of LIGPLAATS.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">INGESCHREVEN PERSOON</td>
      <td><p>Een INGEZETENE of NIET-INGEZETENE</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">REISDOCUMENT</td>
      <td><p>Een document dat vereist is voor reizen naar het buitenland</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">OVERIG GEBOUWD OBJECT</td>
      <td><p>De kleinste eenheid van gebruik, geen verblijfsobject zijnde, binnen een bij de totstandkoming functioneel en bouwkundig constructief zelfstandige eenheid die direct en duurzaam met de aarde is verbonden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">VERBLIJFSTITEL</td>
      <td><p>Rechtsgrond op basis waarvan men bevoegd is in een land te verblijven.
Opmerkingen obv Key2Burgerzaken:
De verblijfstitel heeft een ingangs- en vervaldatum, datum geldig en een opname datum
RSGB3.0 onderkent alleen Datum einde en Datum ingang. Dat is onvoldoende om volgorde en geldigheid in tijd correct te bepalen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">ZEKERHEIDSRECHT</td>
      <td><p>Een zekerheidsrecht is een beperkt recht (hypotheek) of een beperking (beslag).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">KADASTRALE ONROERENDE ZAAK AANTEKENING</td>
      <td><p>Aanduiding van het feit, genoemd in een Stuk, dat betrekking heeft op een onroerende zaak en dat gevolgen kan hebben voor de uitoefening van rechten op de onroerende zaak.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">INGEZETENE</td>
      <td><p>Een individueel menselijk wezen, ingeschreven in het Nederlands Bevolkingsregister.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">APPARTEMENTSRECHT</td>
      <td><p>Een KADASTRALE ONROERENDE ZAAK dat een aandeel is in de 
goederen die in de splitsing zijn betrokken, dat de bevoegdheid omvat tot het uitsluitend gebruik van bepaalde gedeelten van het gebouw die blijkens hun inrichting bestemd zijn of worden om als afzonderlijk geheel te worden 
gebruikt (art. 5:106 lid 4 BW).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">OPENBARE RUIMTE</td>
      <td><p>Een door het bevoegde gemeentelijke orgaan als zodanig aangewezen en van een naam voorziene buitenruimte die binnen één woonplaats is gelegen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">ZAKELIJK RECHT</td>
      <td><p>Het eigendom van, of een beperkt recht van een natuurlijk of niet-natuurlijk persoon (PERSOON) op, een onroerende zaak (met uitzondering van hypotheken en beslagen).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">KADASTRALE ONROERENDE ZAAK</td>
      <td><p>Een geregistreerd goed waarvoor bij overdracht of vestiging van rechten inschrijving in de openbare registers van het Kadaster is vereist zijnde een KADASTRAAL PERCEEL of een APPARTEMENTSRECHT.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">TENAAMSTELLING</td>
      <td><p>Een TENAAMSTELLING  vormt de relatie tussen een Recht en een Persoon en geeft aan welk recht, met uitzondering van hypotheek en beslag, door een Persoon wordt uitgeoefend op een Kadastraal object.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Aantekening</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">ADRESSEERBAAR OBJECT AANDUIDING</td>
      <td><p>Een door het bevoegde gemeentelijke orgaan als zodanig toegekende aanduiding van een VERBLIJFSOBJECT, een STANDPLAATS of een LIGPLAATS.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">LIGPLAATS</td>
      <td><p>Een door het bevoegde gemeentelijke orgaan als zodanig aangewezen plaats in het water al dan niet aangevuld met een op de oever aanwezig terrein of een gedeelte daarvan, die bestemd is voor het permanent afmeren van een voor woon-, bedrijfsmatige of recreatieve doeleinden geschikt vaartuig.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">OVERIGE ADRESSEERBAAR OBJECT AANDUIDING</td>
      <td><p>Een door de gemeenteraad als zodanig toegekende aanduiding van een overig gebouwd object of een overig benoemd terrein.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">STANDPLAATS</td>
      <td><p>Een door het bevoegde gemeentelijke orgaan als zodanig aangewezen terrein of gedeelte daarvan dat bestemd is voor het permanent plaatsen van een niet direct en niet duurzaam met de aarde verbonden en voor woon -, bedrijfsmatige, of recreatieve doeleinden geschikte ruimte.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">OVERIG BOUWWERK</td>
      <td><p>Met de aarde verbonden duurzaam bouwwerk, dat niet valt onder de definities van een pand of kunstwerk.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Adres Buitenland</td>
      <td><p>Toevoeging uit stelselcatalogus</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Nationaliteit</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">INRICHTINGSELEMENT</td>
      <td><p>Ruimtelijk object al dan niet ter detaillering dan wel ter inrichting van de
overige benoemde ruimtelijke objecten of een ander inrichtingselement.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">NIET NATUURLIJK PERSOON</td>
      <td><p>Een INGESCHREVEN NIET-NATUURLIJK PERSOON of een ANDER BUITENLANDS NIET-NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">NATUURLIJK PERSOON</td>
      <td><p>Een INGESCHREVEN PERSOON of ANDER NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">PAND</td>
      <td><p>De kleinste bij de totstandkoming functioneel en bouwkundig-constructief zelfstandige eenheid die direct en duurzaam met de aarde is verbonden en betreedbaar en afsluitbaar is.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">MAATSCHAPPELIJKE ACTIVITEIT</td>
      <td><p>Een verband tussen één of meer personen met voldoende mate van zelfstandigheid, inbreng van arbeid of middelen, winstoogmerk en extern optreden (i.g.v. een onderneming) dan wel een in een organisatorisch verband, dat toebehoort aan een niet-natuurlijk persoon welke registratieplichtig is, uitgeoefende activiteit die niet valt onder de criteria voor onderneming of bedrijfsmatigheid welke adresseerbaar is middels ofwel een vestiging ofwel het adres van een bepaalde vertegenwoordiger (i.g.v. een niet-ondernemings-activiteit).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">VERBLIJFSOBJECT</td>
      <td><p>De kleinste binnen één of meer panden gelegen en voor woon -, bedrijfsmatige, of recreatieve doeleinden geschikte eenheid van gebruik die ontsloten wordt via een eigen afsluitbare toegang vanaf de openbare weg, een erf of een gedeelde verkeersruimte, onderwerp kan zijn van goederenrechtelijke rechtshandelingen en in functioneel opzicht zelfstandig is.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">VESTIGING</td>
      <td><p>Een gebouw of complex van gebouwen waar duurzame uitoefening van de activiteiten van een onderneming of rechtspersoon plaatsvindt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">KUNSTWERKDEEL</td>
      <td><p>Onderdeel van een civiel-technisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">WOONPLAATS</td>
      <td><p>Een door het bevoegde gemeentelijke orgaan als zodanig aangewezen en van een naam voorzien gedeelte van het grondgebied van de gemeente.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">BEGROEID TERREINDEEL</td>
      <td><p>Kleinste functioneel onafhankelijk stukje van een terrein dat er binnen het objecttype Terrein van NEN 3610 wordt onderscheiden, met aaneengesloten homogene vegetatie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">KADASTRAAL PERCEEL</td>
      <td><p>Een KADASTRALE ONROERENDE ZAAK dat een kadastraal geïdentificeerd en met kadastrale grenzen begrensd deel van het Nederlands grondgebied betreft (art. 1 lid 1 Kadasterwet).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">RECHTSPERSOON</td>
      <td><p>Een NATUURLIJK PERSOON of een NIET-NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">FUNCTIONEEL GEBIED</td>
      <td><p>Begrensd en benoemd gebied dat door een functionele eenheid beschreven wordt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">GEBOUWINSTALLATIE</td>
      <td><p>Een component aan de buitenzijde van een gebouw, die het aanzicht van het gebouw mede bepaalt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">WATERDEEL</td>
      <td><p>Kleinste functioneel onafhankelijk stukje water met gelijkblijvende, homogene eigenschappen en relaties dat er binnen het objecttype Water van NEN 3610 wordt onderscheiden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">GEMEENTE</td>
      <td><p>Een gedeelte van het grondgebied van Nederland, ingesteld op basis van artikel 123 van de Grondwet.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">OVERIG BENOEMD TERREIN</td>
      <td><p>Een door het bevoegde gemeentelijke orgaan als zodanig aangewezen onbebouwd terrein of een gedeelte daarvan, geen standplaats of gedeelte van een ligplaats zijnde, dat bestemd is voor het gedurende langere tijd verrichten van een maatschappelijke activiteit.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">ONBEGROEID TERREINDEEL</td>
      <td><p>Kleinste functioneel onafhankelijk stukje van een terrein, dat er binnen het objecttype Terrein van NEN 3610 wordt onderscheiden, zonder aaneengesloten vegetatie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">ONDERSTEUNEND WATERDEEL</td>
      <td><p>Object dat in het kader van de waterhuishouding periodiek gedeeltelijk of geheel met water is bedekt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">ONDERSTEUNEND WEGDEEL</td>
      <td><p>Een deel van de weg dat niet primair bedoeld is voor gebruik door het verkeer.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">OVERBRUGGINGSDEEL</td>
      <td><p>Onderdeel van een beweegbare of vaste verbinding tussen twee punten, die door water, een weg of anderszins gescheiden zijn, dat essentieel is voor de constructie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">OVERIGE SCHEIDING</td>
      <td><p>Kunstmatig, meestal lineair obstakel met een werende functie, met kleinere afmetingen dan toegestaan voor opname in de BGT.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">SCHEIDING</td>
      <td><p>Kunstmatig, meestal lineair obstakel met een werende functie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">SPOOR</td>
      <td><p>De as van het spoor, dat wil zeggen het midden van twee stalen staven op een onderling vaste afstand, waarover trein, tram, of sneltram rijdt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">TUNNELDEEL</td>
      <td><p>Onderdeel van een kunstmatig aangelegde, kokervormige onderdoorgang, dat essentieel is voor de constructie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">VEGETATIEOBJECT</td>
      <td><p>Solitair vegetatieobject of lijn- of vlakvormige groep gelijksoortige vegetatieobjecten met een beperkte omvang.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">WEGDEEL</td>
      <td><p>Kleinste functioneel onafhankelijk stukje van een NEN 3610 Weg,  met gelijkblijvende homogene eigenschappen en relaties en primair bedoeld voor gebruik door weg-, spoor- en vliegverkeer te land</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Rapportagemoment</td>
      <td><p>Een vantevoren bepaald tijdstip waarom een gegevensanalyse wordt uitgevoerd</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Contact</td>
      <td><p>Persoon waarmee communicatie plaatsvindt</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Projectontwikkelaar</td>
      <td><p>Een persoon of een firma die een project ontwikkelt voor financieel gewin.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Melding</td>
      <td><p>De betekenisvolle formulering van een waargenomen feit, waaraan een waarde kan worden toegekend</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Projectleider</td>
      <td><p>De persoon die een project aanstuurt</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Verblijfadres ingeschreven natuurlijk persoon</td>
      <td><p>De gegevens over het verblijf en adres van de INGESCHREVEN NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Geo-Object</td>
      <td><p>Abstractie van een fenomeen in de werkelijkheid, dat direct of indirect is geassocieerd met een locatie relatief ten opzichte van de aarde. [NEN 3610:2011]</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Beschermde Status</td>
      <td><p>Status van de bescherming van een monument. Een monument / erfgoed is een overblijfsel van kunst, cultuur, architectuur of nijverheid dat van algemeen belang wordt geacht vanwege de historische, volkskundige, artistieke, wetenschappelijke, industrieel-archeologische of andere sociaal-culturele waarde. Vormen van monument / erfgoed met de status rijks- provinciaal- of gemeentelijke monument / erfgoed zijn beschermd op grond van een besluit van respectievelijk het Ministerie OCW, de provincie of de gemeente,</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Geboorte ingeschreven natuurlijk persoon</td>
      <td><p>Gegevens over de geboorte van de INGESCHREVEN NATUURLIJK PERSOON.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Soort overig bouwwerk</td>
      <td><p>Gegevens over het soort overig bouwwerk.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Asielstatushouder</td>
      <td><p>De Inburgeringsplichtige die rechtmatig verblijf heeft</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">CultuurOnbebouwd</td>
      <td><p>Een aanduiding voor de soort cultuur van het onbebouwde gedeelte van de onroerende zaak.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Initiatiefnemer</td>
      <td><p>Een Natuurlijk Persoon of een Niet Natuurlijk Persoon die het initiatief neemt tot (fysieke) ingrepen in de (leef)omgeving en daartoe een Verzoek bij het Bevoegd Gezag indient. (IMAM)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Sportvereniging</td>
      <td><p>Organisatievorm waarin sport bedreven kan worden</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Aanwezige Deelnemer</td>
      <td><p>iemand die meedoet aan eencollege- of raadsvergadering</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Historisch Persoon</td>
      <td><p>Natuurlijk persoon waarvan informatie beschikbaar is uit het verleden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Sportpark</td>
      <td><p>Geheel van terreinen, gebouwen en voorzieningen voor verschillende takken van sport.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Ontbinding huwelijk/geregistreerd partnerschap</td>
      <td><p>Gegevens over het ontbonden huwelijk of geregistreerd partnerschap.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Vastgoedobject</td>
      <td><p>Perceel of vastgoed waar de gemeente een zakelijk recht heeft, en optioneel verhuurd, verpacht of anderzinds aan een derde partij.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Koopsom kadastrale onroerende zaak</td>
      <td><p>Het in een ter inschrijving aangeboden stuk vermelde bedrag, waarvoor 1 of meer onroerende zaken zijn verkregen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Gemachtigde</td>
      <td><p>Een Natuurlijk Persoon of een Niet Natuurlijk Persoon die als vertegenwoordiger van een Initiatiefnemer optreedt. (uit: IMAM)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">School</td>
      <td><p>Gebouw in gebruik voor basis, middelbaar of hoger onderwijs.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Gemeentebegrafenis</td>
      <td><p>Teraardebestelling onder verantwoordelijjkheid van de gemeente.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Bezoeker</td>
      <td><p>Een persoon die iemand of iets bezoekt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Veld</td>
      <td><p>Een stuk land dat speciaal voor het bedrijven van een veldsport gereedgemaakt is</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Overlijden ingeschreven natuurlijk persoon</td>
      <td><p>Gegevens over het overlijden van de ingeschreven natuurlijk persoon.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Locatie kadastrale onroerende zaak</td>
      <td><p>Deze wordt gebruikt om één of meer locatieaanduiding(en) van een onroerende zaak weer te geven.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Museumrelatie</td>
      <td><p>Betrekking waarin het museum en personen tot elkaar staan</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Onderwijsinstituut</td>
      <td><p>Een instituut waar onderwijs wordt gegeven.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Kandidaat</td>
      <td><p>Iemand die een bepaalde baan of functie wil</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Relatie</td>
      <td><p>Betrekking waarin personen, zaken, begrippen of grootheden van nature tot elkaar staan.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Binnenlocatie</td>
      <td><p>Locatie binnen een gebouw</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Postadres</td>
      <td><p>De gegevens die tezamen een postbusadres of antwoordnummeradres vormen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Lener</td>
      <td><p>Iemand die iets te leen krijgt, met name iemand die boeken, digitale bestanden of apparatuur leent bij een museum, bibliotheek, mediatheek of een andere uitleeninstantie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Werkgelegenheid</td>
      <td><p>De vraag naar arbeid, te berekenen door de totale productie te delen door de arbeidsproductiviteit per persoon.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Vreemdeling</td>
      <td><p>Een Vreemdeling is een Natuurlijk Persoon die de Nederlandse Nationaliteit niet bezit en niet op grond van een wettelijke bepaling als Nederlander wordt behandeld.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Stremming</td>
      <td><p>Situatie waarbij de doorstroming van het (vaar)wegverkeer plaatselijk is geblokkeerd als gevolg van een incident</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Sluiting/aangaan huwelijk/geregistreerd partnerschap</td>
      <td><p>Gegevens over het gesloten huwelijk of het aangegane geregistreerd partnerschap.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Leverancier</td>
      <td><p>Een niet-natuurlijk persoon die een product of dienst levert aan de organisatie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">SBI activiteit vestiging</td>
      <td><p>Aanduiding van de activiteit (en) van een vestiging  conform de Standaard BedrijfsIndeling</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Relatie</td>
      <td><p>Betrekking waarin personen, zaken, begrippen of grootheden van nature tot elkaar staan.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Soort kunstwerk</td>
      <td><p>Gegevens over het soort kunstwerk.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Bevoegd Gezag</td>
      <td><p>Bestuursorgaan dat bevoegd is tot het geven van een beschikking of het nemen van een ander besluit.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Hotel</td>
      <td><p>Gebouw waar je tegen betaling kunt logeren.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Sollicitant</td>
      <td><p>Persoon die werk zoekt</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">KadastraleMutatie</td>
      <td><p>Wijziging in de kadatrale registratie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Grondbeheerder</td>
      <td><p>Beheerder van grondgrondbeheer., oplossing voor duurzaam landbeheer en voedselproductie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Verkooppunt</td>
      <td><p>Locatie waar iets wordt verkocht</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Soort functioneel gebied</td>
      <td><p>Gegevens over het soort functioneel gebied.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Indiener</td>
      <td><p>Persoon die meldiing of aanvraag doet</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Soort scheiding</td>
      <td><p>Gegevens over de soort scheiding</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Belanghebbende</td>
      <td><p>Een persoon wiens belang rechtstreeks bij een besluit is betrokken.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Soort spoor</td>
      <td><p>Gegevens over het soort spoor.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Subsidie</td>
      <td><p>Aan derden toegekende financiele middelen, bestemd voor het uitvoeren van bepaalde activiteiten</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Uitgever</td>
      <td><p>Iemand die iets op de markt brengt; iemand die iets uitgeeft</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Rechthebbende</td>
      <td><p>Een rechthebbende is iemand die rechten heeft op een goed.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Eigenaar</td>
      <td><p>Eigenaar is een persoon die de eigenaar is van een gebouw of stuk grond en ook alle rechten daarvan bezit.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Huurder</td>
      <td><p>Een partij die een zaak of een gedeelte daarvan in gebruik verstrekt heeft gekregen en zich heeft verbonden tot een tegenprestatie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Pachter</td>
      <td><p>Een persoon die een pachtovereenkomst heeft met de eigenaar van een perceel voor het gebruik als landbouwgrond.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Debiteur</td>
      <td><p>Iemand aan wie een dienst of product geleverd is waardoor recht op een vergoeding is ontstaan</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Leverancier</td>
      <td><p>Een niet-natuurlijk persoon die een product of dienst levert aan de organisatie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">BETROKKENE</td>
      <td><p><font color="#610e6a">Een SUBJECT, zijnde een NATUURLIJK PERSOON, NIET-NATUURLIJK PERSOON of VESTIGING, ORGANISATORISCHE EENHEID (binnen een vestiging van de zaak-behandelende niet-natuurlijk persoon), of MEDEWERKER (van die organisatorische eenheid) die een rol kan spelen bij een ZAAK.</font></p></td>
    </tr>
  </tbody>
</table>

### Schuldhulpverlening (GGM)

<figure align="center">
  <img width="1591" src="2023-12-13_GGM_data-objecten/Schuldhulpverlening__GGM_.svg" alt="Schuldhulpverlening (GGM)">
  <figcaption><i>Schuldhulpverlening (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Client</td>
      <td><p>Een ingeschreven persoon die gebruik maakt van producten en diensten van de gemeente.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Schuldhulpverlening</td>
      <td><p>478</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Financiele Situatie</td>
      <td><p>Verhouding in inkomsten en uitgaven van een persoon of bedrijf</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Traject</td>
      <td><p>Samenstel van achtereenvolgens uit te voeren en onderling samenhangende deelhandelingen of van opeenvolgende stadia in een proces, voorgesteld als een route die via opeenvolgende bestemmingen naar de eindbestemming voert.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Notariele Status</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Project</td>
      <td><p>Geheel van activiteiten uitgevoerd in een tijdelijk samenwerkingsverband gericht op het binnen bepaalde randvoorwaarden (bv. tijd, geld) bereiken van een vooraf gedefinieerd resultaat.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Resultaat</td>
      <td><p>De uitkomst van iets, bijvoorbeeld een berekening of een onderzoek. een gevolg.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Resultaatsoort</td>
      <td><p>Typering van een resultaat</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">ResultaatSHV</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Uitstroomreden</td>
      <td><p>Motivatie voor uitstroom</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Uitstroomredensoort</td>
      <td><p>Typering van een uitstroomreden</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Projectsoort</td>
      <td><p>Typering van een project</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">UitstroomredenSHV</td>
      <td></td>
    </tr>
  </tbody>
</table>

### Sociale Teams (GGM)

<figure align="center">
  <img width="1243" src="2023-12-13_GGM_data-objecten/Sociale_Teams__GGM_.svg" alt="Sociale Teams (GGM)">
  <figcaption><i>Sociale Teams (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Client</td>
      <td><p>Een ingeschreven persoon die gebruik maakt van producten en diensten van de gemeente.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Clientbegeleider</td>
      <td><p>De persoon die verantwoordelijk is voor het opstellen en uitvoeren van het  ondersteuningsplan in samenwering met de client en personen uit zijn/haar omgeving .</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Sociale Teams</td>
      <td><p>487</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Behandeling</td>
      <td><p>Een verzameling van interventies om bepaalde behandeldoelen te bewerkstelligen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Behandelsoort</td>
      <td><p>Typering van een behandeling</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bijzonderheid</td>
      <td><p>Kenmerkende eigenschap</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bijzonderheidsoort</td>
      <td><p>Typering van een bijzonderheid</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">SociaalTeamDossier</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Caseaanmelding</td>
      <td><p>Verzoek tot toelating</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Doelstelling</td>
      <td><p>Een op korte of middellange termijn nagestreefde situatie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Doelstellingsoort</td>
      <td><p>Typering van een doelstellig</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">SociaalTeamDossierSoort</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Relatie</td>
      <td><p>Betrekking waarin personen, zaken, begrippen of grootheden van nature tot elkaar staan.</p></td>
    </tr>
  </tbody>
</table>

### Sport (GGM)

<figure align="center">
  <img width="1939" src="2023-12-13_GGM_data-objecten/Sport__GGM_.svg" alt="Sport (GGM)">
  <figcaption><i>Sport (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">VERBLIJFSOBJECT</td>
      <td><p>De kleinste binnen één of meer panden gelegen en voor woon -, bedrijfsmatige, of recreatieve doeleinden geschikte eenheid van gebruik die ontsloten wordt via een eigen afsluitbare toegang vanaf de openbare weg, een erf of een gedeelde verkeersruimte, onderwerp kan zijn van goederenrechtelijke rechtshandelingen en in functioneel opzicht zelfstandig is.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">NIET NATUURLIJK PERSOON</td>
      <td><p>Een INGESCHREVEN NIET-NATUURLIJK PERSOON of een ANDER BUITENLANDS NIET-NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Sport</td>
      <td><p>656</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Sportvereniging</td>
      <td><p>Organisatievorm waarin sport bedreven kan worden</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Sport</td>
      <td><p>Een fysieke bezigheid met vaste regels en waarbij vaak sprake is van competitieverband. Sporten kunnen ook recreatief beoefend worden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Aantal</td>
      <td><p>Een onbepaalde maar telbare hoeveelheid</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Binnenlocatie</td>
      <td><p>Locatie binnen een gebouw</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Sportmateriaal</td>
      <td><p>Materieel om sport mee te beoefenen of ter odnersteuning van de sportuitvoering.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bezetting</td>
      <td><p>Aantal deelnemers aan een activiteit</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Sportlocatie</td>
      <td><p>Locatie waar de betreffende sport plaatsvindt</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Veld</td>
      <td><p>Een stuk land dat speciaal voor het bedrijven van een veldsport gereedgemaakt is</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Belijning</td>
      <td><p>Op of in het oppervlak van de verharding aangebrachte tekens ter geleiding, waarschuwing, regeling of informatie van het verkeer</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Sportpark</td>
      <td><p>Geheel van terreinen, gebouwen en voorzieningen voor verschillende takken van sport.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Onderhoudskosten</td>
      <td><p>Kosten voor het onderhoud van iemand of iets, hetzij om te voorzien in de levensbehoeften van personen, hetzij voor de instandhouding en verzorging van zaken.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">School</td>
      <td><p>Gebouw in gebruik voor basis, middelbaar of hoger onderwijs.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">WIJK</td>
      <td><p>Een aaneengesloten gedeelte van het grondgebied van een gemeente, waarvan de grenzen zo veel mogelijk zijn gebaseerd op sociaal-geografische kenmerken.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">OVERIG BENOEMD TERREIN</td>
      <td><p>Een door het bevoegde gemeentelijke orgaan als zodanig aangewezen onbebouwd terrein of een gedeelte daarvan, geen standplaats of gedeelte van een ligplaats zijnde, dat bestemd is voor het gedurende langere tijd verrichten van een maatschappelijke activiteit.</p></td>
    </tr>
  </tbody>
</table>

### Subsidies (GGM)

<figure align="center">
  <img width="1591" src="2023-12-13_GGM_data-objecten/Subsidies__GGM_.svg" alt="Subsidies (GGM)">
  <figcaption><i>Subsidies (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Kostenplaats</td>
      <td><p>Rekening waaraan boekingen in een financi√´le administratie samen worden toegeschreven.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">ORGANISATORISCHE EENHEID</td>
      <td><p><font color="#610e6a">Het deel van een functioneel afgebakend onderdeel binnen de organisatie dat haar activiteiten uitvoert binnen een VESTIGING VAN ZAAKBEHANDELENDE ORGANISATIE en die verantwoordelijk is voor de behandeling van zaken.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">MEDEWERKER</td>
      <td><p><font color="#610e6a">Een medewerker van de organisatie die zaken behandelt uit hoofde van zijn of haar functie binnen een ORGANISATORISCHE EENHEID.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Subsidies</td>
      <td><p>181</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Subsidieprogramma</td>
      <td><p>Programma waarin meerdere subsidies worden verleend vanuit een bepaalde samenhang</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Subsidiecomponent</td>
      <td><p>Onderdeel van een subisidie met een eigen kostenplaats.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Betaalmoment</td>
      <td><p>Moment waarop er een bepaald deel van de subsidie betaald moet worden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Subsidiebeschikking</td>
      <td><p>Besluit over het al dan niet toekennen van een subsidie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Subsidieaanvraag</td>
      <td><p>Aanvraag voor een subsidie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Subsidie</td>
      <td><p>Aan derden toegekende financiele middelen, bestemd voor het uitvoeren van bepaalde activiteiten</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Taak</td>
      <td><p>Een samenhangende set activiteiten in het kader van een subsidie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Sector</td>
      <td><p>Sector is de verzameling van werkzaamheden, gericht op de productie van bepaalde goederen en diensten. Het gaat hierbij niet alleen om activiteiten van het bedrijfsleven, maar ook om activiteiten van niet op winst gerichte instellingen en de overheid.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Subsidieniveau</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Rapportagemoment</td>
      <td><p>Een vantevoren bepaald tijdstip waarom een gegevensanalyse wordt uitgevoerd</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">DOCUMENT</td>
      <td><p><font color="#610e6a">Geheel van gegevens met een eigen identiteit ongeacht zijn vorm, met de bijbehorende metadata ontvangen of opgemaakt door een natuurlijke en/of rechtspersoon bij de uitvoering van taken, zijnde een ENKELVOUDIG DOCUMENT of een SAMENGESTELD DOCUMENT.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">RECHTSPERSOON</td>
      <td><p>Een NATUURLIJK PERSOON of een NIET-NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">ZAAK</td>
      <td><p><font color="#610e6a">Een samenhangende hoeveelheid werk met een welgedefinieerde aanleiding en een welgedefinieerd eindresultaat, waarvan kwaliteit en doorlooptijd bewaakt moeten worden.</font></p></td>
    </tr>
  </tbody>
</table>

### Tekenwijze (GGM)

<figure align="center">
  <img width="925" src="2023-12-13_GGM_data-objecten/Tekenwijze__GGM_.svg" alt="Tekenwijze (GGM)">
  <figcaption><i>Tekenwijze (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Tekenwijze</td>
      <td><p>350</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Objecttype C</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Objecttype A</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Objecttype D</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Objecttype B</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Objecttype E</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Objecttype G</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Objecttype F</td>
      <td></td>
    </tr>
  </tbody>
</table>

### Union (GGM)

<figure align="center">
  <img width="229" src="2023-12-13_GGM_data-objecten/Union__GGM_.svg" alt="Union (GGM)">
  <figcaption><i>Union (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Union</td>
      <td><p>835</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">MultiPuntLijn(Multi)Vlak</td>
      <td><p>Een samengesteld geometrie datatype waarbij wordt afgedwongen dat één van de voorkomens van de attributen geometrieMultiPunt, geometrieLijn, geometrieVlak of geometrieMultivlak moet worden toegepast.</p></td>
    </tr>
  </tbody>
</table>

### Vastgoed (GGM)

<figure align="center">
  <img width="3997" src="2023-12-13_GGM_data-objecten/Vastgoed__GGM_.svg" alt="Vastgoed (GGM)">
  <figcaption><i>Vastgoed (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">KADASTRALE ONROERENDE ZAAK</td>
      <td><p>Een geregistreerd goed waarvoor bij overdracht of vestiging van rechten inschrijving in de openbare registers van het Kadaster is vereist zijnde een KADASTRAAL PERCEEL of een APPARTEMENTSRECHT.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">GEBOUWD OBJECT</td>
      <td><p>Een VERBLIJFSOBJECT of een OVERIG GEBOUWD OBJECT</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Leverancier</td>
      <td><p>Een niet-natuurlijk persoon die een product of dienst levert aan de organisatie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Vastgoed</td>
      <td><p>46</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Aanbesteding</td>
      <td><p>Een procedure waarbij een opdrachtgever bekendmaakt dat hij een opdracht of concessie wil laten uitvoeren en bedrijven uitnodigt om een offerte in te dienen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Adresaanduiding</td>
      <td><p>De adresaanduiding van het WOZ-OBJECT</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">CultuurOnbebouwd</td>
      <td><p>Een aanduiding voor de soort cultuur van het onbebouwde gedeelte van de onroerende zaak.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">NAD_AanvullingBRP</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bouwdeel</td>
      <td><p>Zelfstandig en aanwijsbaar deel van een element, onderscheiden naar samenstelling of constructiewijze, bestaande uit √©√©n of meer componenten waaraan technische eigenschappen en een onderhoudshistorie kunnen worden gerelateerd (bron: Conditiemeting gebouwde omgeving - Deel 1: Methodiek, code: 3.3)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Inspectie</td>
      <td><p>het inwinnen, verwerken en interpreteren van informatie met het doel om de momentane toestand van de boezemkade vast te stellen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">MJOP</td>
      <td><p>Meerjaren Onderhoudsplanning</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Werkbon</td>
      <td><p>Document waarin een heoveelheid werk is beschreven</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">LocatieOnroerendeZaak</td>
      <td><p>Locatie van een geregistreerd goed</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">MJOP-Item</td>
      <td><p>Onderdeel van een MJOP</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Prijzenboekitem</td>
      <td><p>Onderdeel van een prijzenboek</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bouwdeelelement</td>
      <td><p>Onderdeeel van een bouwdeel</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Eigenaar</td>
      <td><p>Eigenaar is een persoon die de eigenaar is van een gebouw of stuk grond en ook alle rechten daarvan bezit.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Gebruiksdoel</td>
      <td><p>Een aanduiding va alle waarden waarmee het gebruiksdoel van een object kan worden verbijzonderd.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Objectrelatie</td>
      <td><p>Relatie tot een object</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">kp_betrokken_bij</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">WOZ-Belang</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">kp_onstaan_uit</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Offerte</td>
      <td><p>Aanbod, aanbieding of voorstel van goederen of diensten waarin opgave is gedaan van de prijs.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Huurder</td>
      <td><p>Een partij die een zaak of een gedeelte daarvan in gebruik verstrekt heeft gekregen en zich heeft verbonden tot een tegenprestatie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Pachter</td>
      <td><p>Een persoon die een pachtovereenkomst heeft met de eigenaar van een perceel voor het gebruik als landbouwgrond.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vastgoedobject</td>
      <td><p>Perceel of vastgoed waar de gemeente een zakelijk recht heeft, en optioneel verhuurd, verpacht of anderzinds aan een derde partij.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Zakelijk Recht</td>
      <td><p>Geeft een recht op een goed, zoals een onroerende zaak of een roerende zaak.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Energielabel Gebouwen</td>
      <td><p><font color="#1a1a1a"><b>Gebouwen (geen woningen in particulier bezit)</b></font><font color="#42474b">[</font><a href="https://nl.wikipedia.org/w/index.php?title=Energielabel&amp;action=edit&amp;section=11"><font color="#092f9d"><u>bewerken</u></font></a><font color="#42474b">]</font>
<font color="#1a1a1a">In 2002 heeft het Europese Parlement de EPBD-richtlijn aangenomen. Deze richtlijn is gericht op het terugdringen van het energiegebruik van </font><a href="https://nl.wikipedia.org/wiki/Gebouw"><font color="#092f9d"><u>gebouwen</u></font></a><font color="#1a1a1a">, met het oog op vermindering van de uitstoot van o.a. CO<sub>2</sub> en om de afhankelijkheid van fossiele brandstoffen te verkleinen. Op basis van deze Europese richtlijn is het in Nederland sinds 1 januari 2008 verplicht gesteld dat bij iedere transactie van utiliteitsgebouw ouder dan 10 jaar een energielabel aan de nieuwe gebruiker overhandigd moet worden. Sinds 2010 zijn de regels voor toekenning sterk versimpeld: "Er wordt geschat hoeveel </font><a href="https://nl.wikipedia.org/wiki/Giga"><font color="#092f9d"><u>giga</u></font></a><a href="https://nl.wikipedia.org/wiki/Joule"><font color="#092f9d"><u>joule</u></font></a><font color="#1a1a1a"> energie de woning elk jaar per vierkante meter gebruikt voor verwarming, warm water en verlichting". Hiervan wordt afgetrokken de geschatte warmteterugwinning uit rioolwater en ventilatie, en de geschatte energieproductie via zonnecollectoren (zowel elektrisch als warm water). Er wordt uitgegaan van gemiddelde bewoning, gemiddeld buitenklimaat en gemiddeld stookgedrag.</font>
<font color="#1a1a1a">
</font><font color="#1a1a1a">Bron Wikipedia</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Monumenttypering</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verhuurbaar Eenheid</td>
      <td><p>Een Verhuurbare Eenheid (VHE) is een eenheid die individueel verhuurbaar is. Verhuurbaar komt voort uit 'exploitatie'</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vastgoedcontractregel</td>
      <td><p>ONderdeel van een vastgoedcontract</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vastgoed Contract</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">NEN2767 Conditiescore</td>
      <td><p><font color="#262626">NEN 2767 zorgt voor het uniform inspecteren en in kaart brengen van de technische staat van alle bouw- en installatie delen m.b.t. gebouwen en/of infrastructuur. Door middel van conditiescores maakt u gemakkelijk vergelijkingen tussen de verschillende onderhoudstoestanden van objecten. Zo heeft u met de resultaten inzicht in onderhoudskosten en mogelijke risico’s en zo kunt u meerjarige onderhoudsplanningen opstellen. Kortom, met deze norm kunt u de kwaliteit waarborgen.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">LOCATIEAANDUIDING WOZ OBJECT</td>
      <td><p>Nadere aanduiding van het WOZ-object</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Objectrelatierol</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">TypeAdresseerbaarObject</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Zakelijkrecht</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">ZAKELIJK RECHT</td>
      <td><p>Het eigendom van, of een beperkt recht van een natuurlijk of niet-natuurlijk persoon (PERSOON) op, een onroerende zaak (met uitzondering van hypotheken en beslagen).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">APPARTEMENTSRECHTSPLITSING</td>
      <td><p>Het recht op een stuk grond of op een gebouw met toebehoren op de daarbij behorende grond met toebehoren is gesplitst in appartementsrechten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Inkooporder</td>
      <td><p>Een opdracht (gezien vanuit de klant) voor √©√©n of meer leveringen door de leverancier aan die klant van een bepaalde hoeveelheid gespecificeerde goederen en/of diensten onder overeengekomen leveringsvoorwaarden en prijzen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">VERBLIJFSOBJECT</td>
      <td><p>De kleinste binnen één of meer panden gelegen en voor woon -, bedrijfsmatige, of recreatieve doeleinden geschikte eenheid van gebruik die ontsloten wordt via een eigen afsluitbare toegang vanaf de openbare weg, een erf of een gedeelde verkeersruimte, onderwerp kan zijn van goederenrechtelijke rechtshandelingen en in functioneel opzicht zelfstandig is.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">BENOEMD OBJECT</td>
      <td><p>Een GEBOUWD OBJECT of een BENOEMD TERREIN</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">NUMMERAANDUIDING</td>
      <td><p>Een door het bevoegde gemeentelijke orgaan als zodanig toegekende aanduiding van een VERBLIJFSOBJECT, een STANDPLAATS of een LIGPLAATS.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">RECHTSPERSOON</td>
      <td><p>Een NATUURLIJK PERSOON of een NIET-NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Kostenplaats</td>
      <td><p>Rekening waaraan boekingen in een financi√´le administratie samen worden toegeschreven.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">PAND</td>
      <td><p>De kleinste bij de totstandkoming functioneel en bouwkundig-constructief zelfstandige eenheid die direct en duurzaam met de aarde is verbonden en betreedbaar en afsluitbaar is.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">WOZ-OBJECT</td>
      <td><p>De onroerende zaak waarvan op grond van de Wet WOZ de waarde moet worden bepaald en vastgesteld.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">KADASTRAAL PERCEEL</td>
      <td><p>Een KADASTRALE ONROERENDE ZAAK dat een kadastraal geïdentificeerd en met kadastrale grenzen begrensd deel van het Nederlands grondgebied betreft (art. 1 lid 1 Kadasterwet).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Locatie</td>
      <td><p>De locatie beschrijft middels coördinaten de ruimtelijke dimensie of ruimtelijke afbakening van een regel of van een objecttype die in de regel beschreven wordt. (CIMOW)</p></td>
    </tr>
  </tbody>
</table>

### Veiligheid en Vergunningen (GGM)

<figure align="center">
  <img width="1273" src="2023-12-13_GGM_data-objecten/Veiligheid_en_Vergunningen__GGM_.svg" alt="Veiligheid en Vergunningen (GGM)">
  <figcaption><i>Veiligheid en Vergunningen (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">Foto</td>
      <td><p>Afbeelding op een plat vlak vervaardigd door middel van fotografie</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">ZAAK</td>
      <td><p><font color="#610e6a">Een samenhangende hoeveelheid werk met een welgedefinieerde aanleiding en een welgedefinieerd eindresultaat, waarvan kwaliteit en doorlooptijd bewaakt moeten worden.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">OBJECT</td>
      <td><p><font color="#610e6a">Het OBJECT waarop een ZAAK betrekking kan hebben zijnde één of meer voorkomens van de in het RSGB en het RGBZ onderscheiden objecttypen.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Veiligheid en Vergunningen</td>
      <td><p>689</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vaartuig</td>
      <td><p>Een zee- of binnenvaartuig, tot de vaart gebruikt of bestemd, daaronder begrepen drijvende werktuigen, zoals baggerwerktuigen, kranen, bokken, elevators, alsmede woonschepen, glijboten en ponten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">BOA</td>
      <td><p>Een buitengewoon opsporingsambtenaar (boa) is een ambtenaar met een specifieke opsporingsbevoegdheid.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Grondslag</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Activiteit</td>
      <td><p>Ieder menselijk handelen waarbij, of ieder menselijk nalaten waardoor een verandering of effect in de (fysieke) leefomgeving wordt of kan worden bewerkstelligd.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Ligplaatsontheffing</td>
      <td><p>Tijdelijke toestemming voor het innemen van een ligplaats op een locatie in een gebied met een verbod op ligplaatsen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Leges_Grondslag</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">OpenbareActiviteit</td>
      <td><p>Activiteit in het publieke domein</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Bevinding</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Inspectie</td>
      <td><p>het inwinnen, verwerken en interpreteren van informatie met het doel om de momentane toestand van de boezemkade vast te stellen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Precario</td>
      <td><p>Belasting die specifiek wordt geheven voor het plaatsen van voorwerpen onder, op of boven voor de openbare dienst bestemde gemeentegrond.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">VTHzaak</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vordering</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Waarneming</td>
      <td><p>Handhavende taak in het kader van VTH</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">VTH-Melding</td>
      <td><p>Melding met betrekking tot Vergunningen, Toezicht en Handhaving</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Fietsregistratie</td>
      <td><p>Adminstreren van fietsen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Combibon</td>
      <td><p>Arjen deze  is voor jou</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Vorderingregel</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Kosten</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">WoonoverlastAanvraagOfMelding</td>
      <td><p>Melding of aanvraag met betrekking tot Woonoverlast</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">WoonfraudeAanvraagOfMelding</td>
      <td><p>Melding of aanvraag van woonfraude</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">SubProductType</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">VOMAanvraagOfMelding</td>
      <td><p>VOM staat voor Vergunning, Ontheffing of Melding. Het betreft hier een melding of een aanvraag voor een vergunning of een ontheffing.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">MORAanvraagOfMelding</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">ProductType</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">AOMstatus</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">VTHAanvraagOfMelding</td>
      <td><p>VTH staat voor Vergunning, Toezicht en Handhaving. Het betreft hier een melding of een aanvraag voor een vergunning of een melding voor Toezicht en/of Handhaving.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Indiener</td>
      <td><p>Persoon die meldiing of aanvraag doet</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Heffingsverordening</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">WABOAanvraagOfMelding</td>
      <td><p>Aanvraag of medling in het kader van de Wet algemene bepalingen omgevingsrecht (WABO)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Beoordelingsoort</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Heffingsoort</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">StatusOpenbareActiviteit</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Heffinggrondslag</td>
      <td><p>De maatstaf waarop een belasting is gebaseerd, het bedrag op basis waarvan een bepaalde belasting wordt geheven of de premie voor sociale zekerheid wordt vastgesteld.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">AanvraagOfMelding</td>
      <td><p>Komt overeen met een VJV</p>
<p>Bron: GEM<em>VJV (Distinct op REQ</em>ID)
ID: REQ_ID</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Heffing</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">DOCUMENT</td>
      <td><p><font color="#610e6a">Geheel van gegevens met een eigen identiteit ongeacht zijn vorm, met de bijbehorende metadata ontvangen of opgemaakt door een natuurlijke en/of rechtspersoon bij de uitvoering van taken, zijnde een ENKELVOUDIG DOCUMENT of een SAMENGESTELD DOCUMENT.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">ZAAKTYPE</td>
      <td><p><font color="#610e6a">Generieke aanduiding van de aard van een zaak</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">RECHTSPERSOON</td>
      <td><p>Een NATUURLIJK PERSOON of een NIET-NATUURLIJK PERSOON</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Bedrijfsprocestype</td>
      <td></td>
    </tr>
  </tbody>
</table>

### Verkeer (GGM)

<figure align="center">
  <img width="1243" src="2023-12-13_GGM_data-objecten/Verkeer__GGM_.svg" alt="Verkeer (GGM)">
  <figcaption><i>Verkeer (GGM)</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="2" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="2">MEDEWERKER</td>
      <td><p><font color="#610e6a">Een medewerker van de organisatie die zaken behandelt uit hoofde van zijn of haar functie binnen een ORGANISATORISCHE EENHEID.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Verkeer</td>
      <td><p>513</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Strooiroute Uitvoering</td>
      <td><p>De route die uiteindelijk is gevolgd voor het strooien</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Strooidag</td>
      <td><p>Dag waarop op wegen gestrooid wordt ter voorkoming van gladheid</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Strooiroute</td>
      <td><p>Traject waarop het strooien plaatsvindt</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verkeersbesluit</td>
      <td><p>Een besluit van een wegbeheerder om een bepaald verkeersteken te plaatsen, te wijzigen of in te trekken of een bepaalde fysieke maatregel te treffen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Verkeerstelling</td>
      <td><p>Een onderzoek om inzicht te krijgen in het verkeer, in de hoeveelheid verkeer, de verdeling en de gereden snelheid.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Aantal Gehinderden</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">V-Log-Info</td>
      <td><p>V-log is een open standaard voor datalogging van een verkeersregelinstallatie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Stremming</td>
      <td><p>Situatie waarbij de doorstroming van het (vaar)wegverkeer plaatselijk is geblokkeerd als gevolg van een incident</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Hindercategorie</td>
      <td><p>De totale impact van hinder voor alle weggebruikers. Dit is op basis van de hinderklasse en het aantal gehinderde weggebruikers bepaald. Zie 'Werkwijze Minder Hinder' van Ministerie van Infrastructuur en Milieu. </p>
<p>URL: https://www.rijkswaterstaat.nl/zakelijk/zakendoen-met-rijkswaterstaat/werkwijzen/werkwijze-in-gww/communicatie-bij-werkzaamheden/werkwijzers-minder-hinder.aspx</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Hinderklasse</td>
      <td><p>Op basis van "Werkwijzer MinderHinder Deel B, de uitwerking" van Ministerie van Infrastructuur en Milieu.
zie https://www.rijkswaterstaat.nl/zakelijk/zakendoen-met-rijkswaterstaat/werkwijzen/werkwijze-in-gww/communicatie-bij-werkzaamheden/werkwijzers-minder-hinder.aspx</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="1">Stremmingstatus</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">DOCUMENT</td>
      <td><p><font color="#610e6a">Geheel van gegevens met een eigen identiteit ongeacht zijn vorm, met de bijbehorende metadata ontvangen of opgemaakt door een natuurlijke en/of rechtspersoon bij de uitvoering van taken, zijnde een ENKELVOUDIG DOCUMENT of een SAMENGESTELD DOCUMENT.</font></p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Kast</td>
      <td><p>Object met een permanent karakter dat dient om iets in te bergen en te beschermen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">WEGDEEL</td>
      <td><p>Kleinste functioneel onafhankelijk stukje van een NEN 3610 Weg,  met gelijkblijvende homogene eigenschappen en relaties en primair bedoeld voor gebruik door weg-, spoor- en vliegverkeer te land</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Paal</td>
      <td><p>Langwerpig stuk hout, ijzer, steen enz., dat in de grond staat.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2">Sensor</td>
      <td><p>Apparaat voor de meting van een fysieke grootheid (bijv. temperatuur, licht, druk, elektriciteit).</p></td>
    </tr>
  </tbody>
</table>

