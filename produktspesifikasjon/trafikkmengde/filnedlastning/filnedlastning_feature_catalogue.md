#### Trafikkmengde

Gir informasjon om representativ trafikkmengde for en strekning

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Gir linje/kurve som geometrisk representerer objektet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kurve</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>ådtTotal</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Angir total årsdøgntrafikk.  Representativt for gitt strekning.  Gjennomsnittsverdi.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>ådtAndelLangeKjøretøy</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Angir hvor stor andel (i prosent) av kjøretøyene som er definert som lange.  Kjøretøy med lengde større eller lik 5,6 meter defineres som lange kjøretøy.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>årGjelderFor</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Angir hvilket år trafikkdataene gjelder for</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>grunnlagForÅDT</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Angir hva som er grunnlag for ÅDT-verdien</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GrunnlagForÅDT</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- NorTraf<br />- NorTraf Kommune – Fra NorTraf Kommune<br />- Ferjedatabanken<br />- Telling og skjønn – Basert på telling og skjønn<br />- Skjønn – Basert på skjønn<br />- Vegorama</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>ådtStart</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Angir årsdøgntrafikk i start av gitt strekning.  Inkl tunge kjøretøy</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>ådtSlutt</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Angir årsdøgntrafikk i slutt av gitt strekning.  Inkl tunge kjøretøy</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
Veglenke

#### Veglenke (abstrakt)

Objekttype som representerer lenker i vegnettet

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>vegident</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sammensatt identifikator for en vegrute</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Vegident</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>vegident.vegkategori</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir hvilken type veg veglenken beskriver</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Vegkategori</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Europaveg<br />- Riksveg<br />- Fylkesveg<br />- Kommunal veg<br />- Privat veg<br />- Skogsbilveg</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>vegident.vegstatus</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir veglenkens status</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>VegStatus</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- vedtattVeg – Planlagt veg vedtatt. (Kun én vegtrasé er tillatt; ingen alternativer.)<br />- anleggsveg – Veg under bygging<br />- eksisterendeVeg – Veg som er del av operativt vegnett (tatt opp til vedlikehold)<br />- midlertidigStatusBilveg – Midlertidig status inntil ny status er bestemt for veg­strek­ningen. Denne skal brukes i de tilfeller hvor det formelt ikke er avklart hvilken status den gamle vegen skal ha.<br />- midlertidigVeg – Midlertidig eksisterende veg. Brukes i de tilfeller hvor annen veg, riks-, fylkes-, kommunal, privat veg eller anleggsveg blir brukt for avvikling av trafikk for vedkom­mende veg uten at den er formelt opptatt. Denne statusen benyttes dersom denne vegen har en lengde på min. 20 m, og situasjonen har en varighet på over ett år.<br />- eksisterendeFerjestrekning – Eksisterende ferjestrekning<br />- beredskapsveg – Beredskapsveg, ikke åpen for allmenn ferdsel<br />- gangSykkelveg – Gang-/sykkelveg<br />- rømningstunnel – Rømningstunnel, ikke åpen for allmenn ferdsel<br />- midlertidigStatusGangSykkelveg – Midlertidig status inntil ny kategori er bestemt for gang- og sykkelvegstrekningen. Denne skal brukes i de tilfeller hvor det formelt ikke er avklart hvem som skal forvalte strekningen, og med det hvilken kategori strekningen skal ha.</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>vegident.vegnummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir nummeret til en vegrute</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
Fellesegenskaper

#### Fellesegenskaper (abstrakt)

abstrakt objekt som bærer en rekke egenskaper som er fagområde-uavhengige og kan benyttes for alle objekttyper<br /><br />Merknad:<br />Spesielt i produktspesifikasjonsarbeid vil en velge egenskaper og av grensningslinjer fra denne klassen.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik identifikasjon av et objekt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Identifikasjon</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon.lokalId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokal identifikator, tildelt av dataleverandør/dataforvalter. Den lokale identifikatoren er unik innenfor navnerommet, ingen andre objekter har samme identifikator.<br /><br />NOTE: Det er data leverandørens ansvar å sørge for at denne lokale identifikatoren er unik innenfor navnerommet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon.navnerom</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnerom som unikt identifiserer datakilden til objektet, starter med tobokstavers kode jfr ISO 3166. Benytter understreking  ("_") dersom dataprodusenten ikke er assosiert med bare et land.<br /><br />NOTE 1 : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og vil registreres i "INSPIRE external  Object Identifier Namespaces Register"<br /><br />Eksempel: NO for Norge.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon.versjonId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>identifikasjon av en spesiell versjon av et geografisk objekt (instans), maksimum lengde på 25 karakterer. Dersom spesifikasjonen av et geografisk objekt med en identifikasjon inkludererer livsløpssyklusinformasjon, benyttes denne versjonId for å skille mellom ulike versjoner av samme objekt. versjonId er en unik  identifikasjon av versjonen.<br /><br />NOTE Maksimum lengde er valgt for å tillate tidsregistrering i henhold til  ISO 8601, slik som  "2007-02-12T12:12:12+05:30" som versjonId.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>datauttaksdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for uttak fra en database<br /><br />Merknad:<br />Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>opphav</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>referanse til opphavsmaterialet, kildematerialet, organisasjons/publiseringskilde<br /><br />Merknad:<br />Kan også beskrive navn på person og årsak til oppdatering</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

### Kodelister

#### «Enumeration» GrunnlagForÅDT

**Definisjon:** Angir hva som er grunnlag for ÅDT-verdien

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>false</td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>NorTraf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>NorTraf Kommune</td>
      <td>Fra NorTraf Kommune</td>
      <td></td>
    </tr>
    <tr>
      <td>Ferjedatabanken</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Telling og skjønn</td>
      <td>Basert på telling og skjønn</td>
      <td></td>
    </tr>
    <tr>
      <td>Skjønn</td>
      <td>Basert på skjønn</td>
      <td></td>
    </tr>
    <tr>
      <td>Vegorama</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Vegkategori

**Definisjon:** angir hvilken type veg veglenken beskriver. (Kilde: Statens vegvesen Håndbok 273 Nasjonalt vegreferansesystem, april 2010, kap 6.3.3.)

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Europaveg</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Riksveg</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Fylkesveg</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kommunal veg</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Privat veg</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Skogsbilveg</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» VegStatus

**Definisjon:** angir veglenkens status (Kilde: Statens vegvesen Håndbok  273 Nasjonalt vegreferansesystem, april 2010, kap 6.3.4.)

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>vedtattVeg</td>
      <td>Planlagt veg vedtatt. (Kun én vegtrasé er tillatt; ingen alternativer.)</td>
      <td></td>
    </tr>
    <tr>
      <td>anleggsveg</td>
      <td>Veg under bygging</td>
      <td></td>
    </tr>
    <tr>
      <td>eksisterendeVeg</td>
      <td>Veg som er del av operativt vegnett (tatt opp til vedlikehold)</td>
      <td></td>
    </tr>
    <tr>
      <td>midlertidigStatusBilveg</td>
      <td>Midlertidig status inntil ny status er bestemt for veg­strek­ningen. Denne skal brukes i de tilfeller hvor det formelt ikke er avklart hvilken status den gamle vegen skal ha.</td>
      <td></td>
    </tr>
    <tr>
      <td>midlertidigVeg</td>
      <td>Midlertidig eksisterende veg. Brukes i de tilfeller hvor annen veg, riks-, fylkes-, kommunal, privat veg eller anleggsveg blir brukt for avvikling av trafikk for vedkom­mende veg uten at den er formelt opptatt. Denne statusen benyttes dersom denne vegen har en lengde på min. 20 m, og situasjonen har en varighet på over ett år.</td>
      <td></td>
    </tr>
    <tr>
      <td>eksisterendeFerjestrekning</td>
      <td>Eksisterende ferjestrekning</td>
      <td></td>
    </tr>
    <tr>
      <td>beredskapsveg</td>
      <td>Beredskapsveg, ikke åpen for allmenn ferdsel</td>
      <td></td>
    </tr>
    <tr>
      <td>gangSykkelveg</td>
      <td>Gang-/sykkelveg</td>
      <td></td>
    </tr>
    <tr>
      <td>rømningstunnel</td>
      <td>Rømningstunnel, ikke åpen for allmenn ferdsel</td>
      <td></td>
    </tr>
    <tr>
      <td>midlertidigStatusGangSykkelveg</td>
      <td>Midlertidig status inntil ny kategori er bestemt for gang- og sykkelvegstrekningen. Denne skal brukes i de tilfeller hvor det formelt ikke er avklart hvem som skal forvalte strekningen, og med det hvilken kategori strekningen skal ha.</td>
      <td></td>
    </tr>
  </tbody>
</table>
