#### BmArt

Forekomster/observasjoner av et kriteriebasert utvalg arter som er spesielt viktig for biologisk mangfold, samt fremmede arter som er en trussel mot naturlig biologisk mangfold. Alt innhold hentes fra Artsdatabankens infrastruktur, basert på arten og nærmere definerte tekniske kvalitetskriterier (geografisk presisjon mv.).

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på - artsdata punkt, kan være enkeltobservasjoner eller registreringer</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Punkt</td>
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
      <td><strong>område</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>objektets utstrekning - artsdata område, for eksempel</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Flate</td>
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
      <td><strong>bmTakson</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir hvilket takson som finnes i området, jf dynamisk kodeliste fra Artsdatabanken</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>BmTakson</td>
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
      <td><strong>bmTakson.bmGruppe</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir typen organisme i henhold til en forvaltningsmessig fornuftig inndeling</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>BmGruppe</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Fugl<br />- Karplanter<br />- Sopp<br />- Insekter<br />- Lav<br />- Fisk<br />- Krepsdyr<br />- Moser<br />- Pattedyr<br />- Øvrige dyr<br />- Alger<br />- Edderkoppdyr<br />- Amfibier og reptiler</td>
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
      <td><strong>bmTakson.bmForvaltningskategori</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>kategorisering i ulike grader av forvaltningsinteresse. inndelingen følger av utvalgskriteriene, slik at hvert utvalgskriterium medfører en bestemt forvaltningskategori.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>BmForvaltningskategori</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Arter av særlig stor forvaltningsinteresse<br />- Arter av stor forvaltningsinteresse<br />- Fremmede arter</td>
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
      <td><strong>bmTakson.bmUtvalgskriterium</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>kriterier for utvalg av arter med forvaltningsstatus</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>BmUtvalgskriterium</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Annen spesielt hensynskrevende art – art som det er knyttet spesielle forvaltningsmessige problemstillinger til.<br />- Ansvarsart – arter der man finner mer enn 25 % av europeisk bestand i Norge. flere av disse artene er relativt vanlige i Norge.<br />- Fredet art – art som er fredet ved Kongelig resolusjon<br />- Fremmed art – arter som er fremmed for Norge og med høy eller svært høy økologisk risiko, samt arter som er internt spredd i Norge med høy økologisk risiko, ihht svartelister<br />- Nær trua art – art i som er plassert i kategorien NT-nær truet i gjeldende norsk rødliste<br />- Prioritert art – art som har status som prioritert art ihht naturmangfolddloven<br />- Spesiell økologisk form – angir økologisk form av en art som må ivaretas særskilt. f.eks. namdalsbleke i Namsen<br />- Trua art – art som er plassert i en av følgende kategorier i gjeldende norsk rødliste: CR-kritisk truet, EN-truet, VU-sårbar</td>
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
      <td><strong>bmTakson.taksonID</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>ID på art - Artsdatabanken sin navneservice</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>TaksonID</td>
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
      <td><strong>bmTakson.taksonNorskNavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på art - Artsdatabanken sin navneservice</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>TaksonNorskNavn</td>
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
      <td><strong>bmTakson.taksonVitNavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>vitenskaplig navn på art - Artsdatabanken sin navneservice</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>TaksonVitNavn</td>
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
      <td><strong>funnetAr</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir hvilket år funnet er gjort</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
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
      <td><strong>funndato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato når objektet siste gang ble registrert/observert/målt i terrenget</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>funnsted</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på stedet hvor funnet er gjort, eventuelt et områdenavn</td>
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
      <td><strong>funksjonsperiode</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir hvilken eller hvilke årstider angitt funksjon gjelder for</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>BmFunksjonsperiode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Vår<br />- Sommer<br />- Høst<br />- Vinter<br />- Vår/høst<br />- Hele året<br />- Udefinert</td>
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
      <td><strong>okologiskFunksjonsomrade</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir om et område har juridisk status som økologisk funksjonsområde for en prioritert art</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Boolean</td>
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
      <td><strong>habitat</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>observatørens beskrivelse av naturen på funnstedet</td>
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
      <td><strong>bmAktivitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir type aktivitet som er knyttet til observasjonen/forekomsten. Er bare aktuelt for arter som er mobile og kan ha flere ulike aktiviteter, f.eks. fugl.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>BmAktivitet</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Fødesøkende<br />- I bevegelse<br />- Reproduserende<br />- Stasjonær<br />- I dvale<br />- Ikke registrert</td>
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
      <td><strong>geografiskPresisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Angis i hele meter og kan representere forskjellige forståelser av geografisk presisjon, avhengig av hvordan originaldata er etablert. Generelt for flater vil gjelde at presisjon er et uttrykk for observatørens oppfatning av hvor nøyaktig objektet er geografisk avgrenset/omsluttet på kart i forhold til de faktiske forhold i terrenget. Dette vil også gjelde punktdata i en rekke tilfeller. For punktdata er presisjonen avstanden (radius) mellom midtpunktkoordinatene for det observerte objektet og yttergrensa for det arealet (sirkelflaten) som punktet representerer.</td>
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
      <td><strong>bmFunntype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir hvilket grunnlag oppføringen bygger på, jf basisOfRecord i Darwin Core</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>BmFunntype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Objekt – angir at et konkret objekt kan knyttes til funnet, så som innsamlet materiale, fossil etc.<br />- Observasjon – angir en observasjon av en art<br />- Bilde – angir at fotomateriale er knyttet til funnet<br />- Beregnet – angir vurdering/bedømmelse av ekspert eller basert på lokal kunnskap<br />- Litteratur – angir at opplysninger er hentet fra litteratur<br />- Lyd – angir at lydopptak er knyttet til funnet<br />- Ukjent</td>
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
      <td><strong>finner</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på den som har gjort observasjonen</td>
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
      <td><strong>artsbestemtAv</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir hvem som har bestemt funnet og bekreftet hvilken art det gjelder, eller som har bekreftet at et område benyttes av arten til en eller flere aktiviteter</td>
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
      <td><strong>bmKjonn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>gir informasjon om kjønn på observerte individer. Feltet er et fritekstfelt i Darwin core standarden og vil inneholde forskjellige betegnelser og skrivemåter for kjønn. er flere individer observert, kan kjønnsfordeling være angitt med ulike skrivemåter, inkludert engelsk (M-male, F-female)</td>
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
      <td><strong>artsdatabankID</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>artsdatabankens ident for denne forekomsten.<br /><br />Merknad: Dette datasettet er satt sammen og publisert av Miljødirektoratet, på grunnlag av observasjoner i Artsdatabanken. Egenskapen "artsdatabankID" gjør det mulig å finne originalobservasjonen.</td>
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

Relasjoner

**Arv**
FellesegenskaperBmArt

**Assosiasjoner**
BmArtGrense – rolle: artsAvgrensning – kardinalitet: 1

#### BmArtGrense

avgrensning av en artslokalitet

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>grense</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
FellesegenskaperBmArtGrense

#### FellesegenskaperBmArtGrense (abstrakt)

abstrakt objekt som bærer en rekke egenskaper som er fagområde-uavhengige og benyttes for objekttypen BmArt

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>datafangstdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato når objektet siste gang ble registrert/observert/målt i terrenget<br /><br />Merknad: I mange tilfeller er denne forskjellig fra Oppdateringsdato, da registrerte endringer kan bufres i en kortere eller lengre periode før disse legges inn i databasen.<br />Ved førstegangsregistrering settes Datafangstdato lik førsteDatafangstdato.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>kvalitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskrivelse av kvaliteten på stedfestingen<br /><br />Merknad: Denne er identisk med ..KVALITET i tidligere versjoner av SOSI.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Posisjonskvalitet</td>
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
      <td><strong>kvalitet.målemetode</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Målemetode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Terrengmålt: Uspesifisert måleinstrument – Målt i terrenget , uspesifisert metode/måleinstrument<br />- Terrengmålt: Totalstasjon – Målt i terrenget med totalstasjon<br />- Terrengmålt: Teodolitt og el avstandsmåler – Målt i terrenget med teodolitt og elektronisk avstandsmåler<br />- Terrengmålt: Teodolitt og målebånd – Målt i terrenget med teodolitt og målebånd<br />- Terrengmålt: Ortogonalmetoden – Målt i terrenget, ortogonalmetoden<br />- Utmål – Punkt beregnet på bakgrunn av måling mot andre punkter, slik som to avstander eller avstand og retning<br />- Tatt fra plan – Tatt fra plan eller godkjent tiltak<br />- Annet  (denne har ingen mening, bør fjernes?) – Annet<br />- Stereoinstrument – Målt i stereoinstrument, uspesifisert instrument<br />- Aerotriangulert – Punkt beregnet ved aerotriangulering<br />- Stereoinstrument: Analytisk plotter – Målt i stereoinstrument, analytisk plotter<br />- Stereoinstrument: Autograf – Målt i stereoinstrument, autograf, analogt instrument<br />- Stereoinstrument: Digitalt – Målt i stereoinstrument, digitalt instrument<br />- Scannet fra kart – Geometri overført fra kart maskinelt ved hjelp av skanner, uspesifisert kartmedium<br />- Skannet fra kart: Blyantoriginal – Geometri overført fra kart maskinelt ved hjelp av skanner. Kartmedium er blyantoriginal<br />- Skannet fra kart: Rissefolie – Geometri overført fra kart maskinelt ved hjelp av skanner. Kartmedium er rissefolie<br />- Skannet fra kart: Transparent folie, god kvalitet – Geometri overført fra kart maskinelt ved hjelp av skanner. Kartmedium er transparent folie av  god kvalitet.<br />- Skannet fra kart: Transparent folie, mindre god kvalitet – Geometri overført fra kart maskinelt ved hjelp av skanner. Kartmedium er transparent folie av mindre god kvalitet<br />- Skannet fra kart: Papirkopi – Geometri overført fra kart maskinelt ved hjelp av skanner. Kartmedium er papirkopi.<br />- Flybåren laserscanner – Målt med laserskanner fra fly<br />- Bilbåren laser – Målt med laserskanner plassert i kjøretøy<br />- Lineær referanse – brukes for objekter som er stedfestet med lineær referanse, enten disse leveres med stedfesting kun som lineære referanser, eller med koordinatgeometri avledet fra lineære referanser<br />- Digitaliseringbord: Ortofoto eller flybilde – Geometri overført fra ortofoto eller flybilde ved hjelp av manuell registrering på et digitaliseringsbord, uspesifisert bildemedium<br />- Digitaliseringbord: Ortofoto, film – Geometri overført fra ortofoto ved hjelp av manuell registrering på et digitaliseringsbord. Bildemedium er film<br />- Digitaliseringbord: Ortofoto, fotokopi – Geometri overført fra ortofoto ved hjelp av manuell registrering på et digitaliseringsbord. Bildemedium er fotokopi<br />- Digitaliseringbord: Flybilde, film – Geometri overført fra flybilde ved hjelp av manuell registrering på et digitaliseringsbord. Bildemedium er film<br />- Digitaliseringbord: Flybilde, fotokopi – Geometri overført fra flybilde ved hjelp av manuell registrering på et digitaliseringsbord. Bildemedium er fotokopi<br />- Digitalisert på skjerm fra ortofoto – Geometri overført fra ortofoto ved hjelp av manuell registrering på skjerm<br />- Digitalisert på skjerm fra satellittbilde – Geometri overført fra satellittbilde ved hjelp av manuell registrering på skjerm<br />- Digitalisert på skjerm fra andre digitale rasterdata<br />- Digitalisert på skjerm fra tolkning av seismikk<br />- Vektorisering av laserdata – Vektorisering fra laserdata, brukes også der vektoriseringen støttes av ortofoto<br />- Digitaliseringsbord: Kart – Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord, medium uspesifisert<br />- Digitaliseringsbord: Kart, blyantoriginal – Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord. Kartmedium er blyantoriginal<br />- Digitaliseringsbord: Kart, rissefoile – Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord. Kartmedium er rissefolie<br />- Digitaliseringsbord: Kart, transparent foile, god kvalitet – Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord. Kartmedium er transparent folie av god kvalitet, samkopi<br />- Digitaliseringsbord: Kart, transparent foile, mindre god kvalitet – Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord. Kartmedium er transparent folie av mindre god kvalitet, samkopi<br />- Digitaliseringsbord: Kart, papirkopi – Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord. Kartmedium er papirkopi<br />- Digitalisert på skjerm fra skannet kart – Geometri overført fra kart ved hjelp av manuell registrering på skjerm, medium skannet kart (raster), samkopi<br />- Genererte data (interpolasjon) – Genererte data, interpolasjonsmetode. Ikke nærmere spesifisert<br />- Genererte data (interpolasjon): Terrengmodell – Genererte data, interpolasjonsmetode, fra terrengmodell<br />- Genererte data (interpolasjon): Vektet middel – Genererte data, interpolasjonsmetode, vektet middel<br />- Genererte data: Fra annen geometri – Genererte data: Sirkelgeometri, korridor eller annen geometri generert ut fra f.eks et punkt eller en linje (f.eks midtlinje veg)<br />- Genererte data: Generalisering<br />- Genererte data: Sentralpunkt<br />- Genererte data: Sammenknytningspunkt, randpunkt – Genererte data: Sammenknytningspunkt (f.eks mellom ulike kartlegginger), randpunkt (f.eks mellom ulike kilder til kart)<br />- Koordinater hentet fra GAB – Koordinater hentet fra GAB, forløperen til registerdelen av matrikkelen<br />- Koordinater hentet fra JREG – Koordinater hentet fra JREG, jordregisteret<br />- Beregnet – Beregnet, uspesifisert hvordan<br />- Spesielle metoder – Spesielle metoder, uspesifisert<br />- Spesielle metoder: Målt med stikkstang<br />- Spesielle metoder: Målt med waterstang<br />- Spesielle metoder: Målt med målehjul<br />- Spesielle metoder: Målt med stigningsmåler<br />- Fastsatt punkt – Punkt fastsatt ut fra et grunnlag (kart, bilde), f.eks ved partenes enighet ved en oppmålingsforretning<br />- Fastsatt ved dom eller kongelig resolusjon – Geometri fastsatt ved dom, lov, traktat eller kongelig resolusjon<br />- Annet (spesifiseres i filhode) ( bør vel fjernes, blir borte ved overføring mellom systemer) – Annet (spesifiseres i filhode)<br />- Frihåndstegning – Digitalisert ut fra frihåndstegning.  Frihåndstegning er basert på svært grovt grunnlag eller ikke noe grunnlag<br />- Frihåndstegning på kart – Digitalisert fra krokering på kart, dvs grovt skissert på kart<br />- Frihåndstegning på skjerm – Digitalisert ut fra frihåndstegning (direkte på skjerm). Frihåndstegning er basert på svært grovt grunnlag eller ikke noe grunnlag<br />- Treghetsstedfesting<br />- GNSS: Kodemåling, relative målinger – Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO): Kodemåling, relative målinger.<br />- GNSS: Kodemåling, enkle målinger – Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO): Kodemåling, enkle målinger.<br />- GNSS: Fasemåling, statisk måling – Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO): Fasemåling statisk måling.<br />- GNSS: Fasemåling, andre metoder – Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO): Fasemåling andre metoder.<br />- Kombinasjon av GNSS/Treghet – Kombinasjon av GPS/Treghet<br />- GNSS: Fasemåling RTK – Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO).: Fasemåling RTK (realtids kinematisk måling)<br />- GNSS: Fasemåling , float-løsning – Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO). Fasemåling float-løsning<br />- Ukjent målemetode – Målemetode er ukjent</td>
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
      <td><strong>kvalitet.nøyaktighet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br /><br />Merknad:<br />Oppgitt i cm</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
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
      <td><strong>kvalitet.synbarhet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvor godt den kartlagte detalj var synbar ved kartleggingen</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Synbarhet</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Fullt ut synlig/gjenfinnbar i terrenget – Default<br />- Dårlig gjenfinnbar i terreng – Forøvrig grei å innmåle. (Benyttes bl.a. for innmåling av ledninger på lukket grøft)<br />- Middels synlig i flybilde/modell<br />- Dårlig/ikke synlig i flybilde/modell</td>
    </tr>
  </tbody>
</table>

#### FellesegenskaperBmArt (abstrakt)

abstrakt objekt som bærer en rekke egenskaper som er fagområde-uavhengige og benyttes for objekttypen BmArt

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>faktaark</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>faktaark er en egen tjeneste som gir alle egenskapsdata pr objekt og et kartgrensesnitt med observasjonen eller området markert.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Link</td>
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
      <td>lokal identifikator, tildelt av dataleverandør/dataforvalter. Den lokale identifikatoren er unik innenfor navnerommet, ingen andre objekter har samme identifikator.<br /><br />Datasettet distribueres med en lokalID som definerer en unik identifikasjon innenfor distribusjonsbasen fra Miljødirektoratet. LokalID er basert på ArtsdatabankID og bygget opp av kilden til data (institusjon, database, unik identifikator)</td>
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
      <td>navnerom som unikt identifiserer datakilden til objektet, starter med to bokstavs kode Eksempel: NO for Norge. jfr ISO 3166.<br /><br />For distribusjons-datasettet brukes navnerom:<br />NO.MILJODIREKTORATET.ARTNASJONAL</td>
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
      <td><strong>institusjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir hvilken institusjon/organisasjon som eier og har det faglige ansvaret for observasjonen og kvalitetsparametere som er lagt inn</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Geodataeier</td>
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
      <td><strong>fylke</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>nummerering av kommuner i henhold til SSB sin offisielle liste</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Fylkesnummer</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- 01 – Østfold<br />- 02 – Akershus<br />- 03 – Oslo<br />- 04 – Hedmark<br />- 05 – Oppland<br />- 06 – Buskerud<br />- 07 – Vestfold<br />- 08 – Telemark<br />- 09 – Aust-Agder<br />- 10 – Vest-Agder<br />- 11 – Rogaland<br />- 12 – Hordaland<br />- 13 – Bergen (utgått)<br />- 14 – Sogn og Fjordane<br />- 15 – Møre og Romsdal<br />- 16 – Sør-Trøndelag<br />- 17 – Nord-Trøndelag<br />- 18 – Nordland<br />- 19 – Troms - Romsa<br />- 20 – Finnmark - Finnmárku<br />- 21 – Svalbard<br />- 22 – Jan Mayen<br />- 23 – Kontinentalsokkelen</td>
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
      <td><strong>kommune</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>nummerering av kommuner i henhold til SSB sin offisielle liste<br /><br />For denne produktspesifikasjonen:<br />alle  kommuner som berøres av et område må tas med.  Ellers blir ingen kommuner med.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kommunenummer</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- 0101 – Halden<br />- 0102 – Sarpsborg (utgått)<br />- 0103 – Fredrikstad (utgått)<br />- 0104 – Moss<br />- 0105 – Sarpsborg<br />- 0106 – Fredrikstad<br />- 0111 – Hvaler<br />- 0113 – Borge (utgått)<br />- 0114 – Varteig (utgått)<br />- 0115 – Skjeberg (utgått)<br />- 0118 – Aremark<br />- 0119 – Marker<br />- 0121 – Rømskog<br />- 0122 – Trøgstad<br />- 0123 – Spydeberg<br />- 0124 – Askim<br />- 0125 – Eidsberg<br />- 0127 – Skiptvet<br />- 0128 – Rakkestad<br />- 0130 – Tune (utgått)<br />- 0131 – Rolvsøy (utgått)<br />- 0133 – Kråkerøy (utgått)<br />- 0134 – Onsøy (utgått)<br />- 0135 – Råde<br />- 0136 – Rygge<br />- 0137 – Våler i Østfold<br />- 0138 – Hobøl<br />- 0211 – Vestby<br />- 0213 – Ski<br />- 0214 – Ås<br />- 0215 – Frogn<br />- 0216 – Nesodden<br />- 0217 – Oppegård<br />- 0219 – Bærum<br />- 0220 – Asker<br />- 0221 – Aurskog-Høland<br />- 0226 – Sørum<br />- 0227 – Fet<br />- 0228 – Rælingen<br />- 0229 – Enebakk<br />- 0230 – Lørenskog<br />- 0231 – Skedsmo<br />- 0233 – Nittedal<br />- 0234 – Gjerdrum<br />- 0235 – Ullensaker<br />- 0236 – Nes i Akershus<br />- 0237 – Eidsvoll<br />- 0238 – Nannestad<br />- 0239 – Hurdal<br />- 0301 – Oslo<br />- 0401 – Hamar (utgått)<br />- 0402 – Kongsvinger<br />- 0403 – Hamar<br />- 0412 – Ringsaker<br />- 0414 – Vang (utgått)<br />- 0415 – Løten<br />- 0417 – Stange<br />- 0418 – Nord-Odal<br />- 0419 – Sør-Odal<br />- 0420 – Eidskog<br />- 0423 – Grue<br />- 0425 – Åsnes<br />- 0426 – Våler i Hedmark<br />- 0427 – Elverum<br />- 0428 – Trysil<br />- 0429 – Åmot<br />- 0430 – Stor-Elvdal<br />- 0432 – Rendalen<br />- 0434 – Engerdal<br />- 0436 – Tolga<br />- 0437 – Tynset<br />- 0438 – Alvdal<br />- 0439 – Folldal<br />- 0441 – Os i Hedmark<br />- 0501 – Lillehammer<br />- 0502 – Gjøvik<br />- 0511 – Dovre<br />- 0512 – Lesja<br />- 0513 – Skjåk<br />- 0514 – Lom<br />- 0515 – Vågå<br />- 0516 – Nord-Fron<br />- 0517 – Sel<br />- 0519 – Sør-Fron<br />- 0520 – Ringebu<br />- 0521 – Øyer<br />- 0522 – Gausdal<br />- 0528 – Østre Toten<br />- 0529 – Vestre Toten<br />- 0532 – Jevnaker<br />- 0533 – Lunner<br />- 0534 – Gran<br />- 0536 – Søndre Land<br />- 0538 – Nordre Land<br />- 0540 – Sør-Aurdal<br />- 0541 – Etnedal<br />- 0542 – Nord-Aurdal<br />- 0543 – Vestre Slidre<br />- 0544 – Øystre Slidre<br />- 0545 – Vang<br />- 0602 – Drammen<br />- 0604 – Kongsberg<br />- 0605 – Ringerike<br />- 0612 – Hole<br />- 0615 – Flå<br />- 0616 – Nes i Buskerud<br />- 0617 – Gol<br />- 0618 – Hemsedal<br />- 0619 – Ål<br />- 0620 – Hol<br />- 0621 – Sigdal<br />- 0622 – Krødsherad<br />- 0623 – Modum<br />- 0624 – Øvre Eiker<br />- 0625 – Nedre Eiker<br />- 0626 – Lier<br />- 0627 – Røyken<br />- 0628 – Hurum<br />- 0631 – Flesberg<br />- 0632 – Rollag<br />- 0633 – Nore og Uvdal<br />- 0701 – Horten<br />- 0702 – Holmestrand<br />- 0703 – Horten (utgått)<br />- 0704 – Tønsberg<br />- 0705 – Tønsberg (utgått)<br />- 0706 – Sandefjord<br />- 0707 – Larvik (utgått)<br />- 0708 – Stavern (utgått)<br />- 0709 – Larvik<br />- 0711 – Svelvik<br />- 0713 – Sande i Vestfold<br />- 0714 – Hof<br />- 0716 – Re<br />- 0717 – Borre (utgått)<br />- 0718 – Ramnes (utgått)<br />- 0719 – Andebu<br />- 0720 – Stokke<br />- 0721 – Sem (utgått)<br />- 0722 – Nøtterøy<br />- 0723 – Tjøme<br />- 0725 – Tjølling (utgått)<br />- 0726 – Brunlanes (utgått)<br />- 0727 – Hedrum (utgått)<br />- 0728 – Lardal<br />- 0805 – Porsgrunn<br />- 0806 – Skien<br />- 0807 – Notodden<br />- 0811 – Siljan<br />- 0814 – Bamble<br />- 0815 – Kragerø<br />- 0817 – Drangedal<br />- 0819 – Nome<br />- 0821 – Bø i Telemark<br />- 0822 – Sauherad<br />- 0826 – Tinn<br />- 0827 – Hjartdal<br />- 0828 – Seljord<br />- 0829 – Kviteseid<br />- 0830 – Nissedal<br />- 0831 – Fyresdal<br />- 0833 – Tokke<br />- 0834 – Vinje<br />- 0901 – Risør<br />- 0903 – Arendal (utgått)<br />- 0904 – Grimstad<br />- 0906 – Arendal<br />- 0911 – Gjerstad<br />- 0912 – Vegårshei<br />- 0914 – Tvedestrand<br />- 0918 – Moland (utgått)<br />- 0919 – Froland<br />- 0920 – Øyestad (utgått)<br />- 0921 – Tromøy (utgått)<br />- 0922 – Hisøy (utgått)<br />- 0926 – Lillesand<br />- 0928 – Birkenes<br />- 0929 – Åmli<br />- 0935 – Iveland<br />- 0937 – Evje og Hornnes<br />- 0938 – Bygland<br />- 0940 – Valle<br />- 0941 – Bykle<br />- 1001 – Kristiansand<br />- 1002 – Mandal<br />- 1003 – Farsund<br />- 1004 – Flekkefjord<br />- 1014 – Vennesla<br />- 1017 – Songdalen<br />- 1018 – Søgne<br />- 1021 – Marnardal<br />- 1026 – Åseral<br />- 1027 – Audnedal<br />- 1029 – Lindesnes<br />- 1032 – Lyngdal<br />- 1034 – Hægebostad<br />- 1037 – Kvinesdal<br />- 1046 – Sirdal<br />- 1101 – Eigersund<br />- 1102 – Sandnes<br />- 1103 – Stavanger<br />- 1106 – Haugesund<br />- 1111 – Sokndal<br />- 1112 – Lund<br />- 1114 – Bjerkreim<br />- 1119 – Hå<br />- 1120 – Klepp<br />- 1121 – Time<br />- 1122 – Gjesdal<br />- 1124 – Sola<br />- 1127 – Randaberg<br />- 1129 – Forsand<br />- 1130 – Strand<br />- 1133 – Hjelmeland<br />- 1134 – Suldal<br />- 1135 – Sauda<br />- 1141 – Finnøy<br />- 1142 – Rennesøy<br />- 1144 – Kvitsøy<br />- 1145 – Bokn<br />- 1146 – Tysvær<br />- 1149 – Karmøy<br />- 1151 – Utsira<br />- 1154 – Vindafjord ((utgått)<br />- 1159 – Ølen (utgått)<br />- 1160 – Vindafjord<br />- 1201 – Bergen<br />- 1211 – Etne<br />- 1214 – Ølen (utgått)<br />- 1216 – Sveio<br />- 1219 – Bømlo<br />- 1221 – Stord<br />- 1222 – Fitjar<br />- 1223 – Tysnes<br />- 1224 – Kvinnherad<br />- 1227 – Jondal<br />- 1228 – Odda<br />- 1231 – Ullensvang<br />- 1232 – Eidfjord<br />- 1233 – Ulvik<br />- 1234 – Granvin<br />- 1235 – Voss<br />- 1238 – Kvam<br />- 1241 – Fusa<br />- 1242 – Samnanger<br />- 1243 – Os i Hordaland<br />- 1244 – Austevoll<br />- 1245 – Sund<br />- 1246 – Fjell<br />- 1247 – Askøy<br />- 1251 – Vaksdal<br />- 1252 – Modalen<br />- 1253 – Osterøy<br />- 1256 – Meland<br />- 1259 – Øygarden<br />- 1260 – Radøy<br />- 1263 – Lindås<br />- 1264 – Austrheim<br />- 1265 – Fedje<br />- 1266 – Masfjorden<br />- 1401 – Flora<br />- 1411 – Gulen<br />- 1412 – Solund<br />- 1413 – Hyllestad<br />- 1416 – Høyanger<br />- 1417 – Vik<br />- 1418 – Balestrand<br />- 1419 – Leikanger<br />- 1420 – Sogndal<br />- 1421 – Aurland<br />- 1422 – Lærdal<br />- 1424 – Årdal<br />- 1426 – Luster<br />- 1428 – Askvoll<br />- 1429 – Fjaler<br />- 1430 – Gaular<br />- 1431 – Jølster<br />- 1432 – Førde<br />- 1433 – Naustdal<br />- 1438 – Bremanger<br />- 1439 – Vågsøy<br />- 1441 – Selje<br />- 1443 – Eid<br />- 1444 – Hornindal<br />- 1445 – Gloppen<br />- 1449 – Stryn<br />- 1502 – Molde<br />- 1504 – Ålesund<br />- 1505 – Kristiansund<br />- 1511 – Vanylven<br />- 1514 – Sande i Møre og Romsdal<br />- 1515 – Herøy i  Møre og Romsdal<br />- 1516 – Ulstein<br />- 1517 – Hareid<br />- 1519 – Volda<br />- 1520 – Ørsta<br />- 1523 – Ørskog<br />- 1524 – Norddal<br />- 1525 – Stranda<br />- 1526 – Stordal<br />- 1528 – Sykkylven<br />- 1529 – Skodje<br />- 1531 – Sula<br />- 1532 – Giske<br />- 1534 – Haram<br />- 1535 – Vestnes<br />- 1537 – Rindal<br />- 1539 – Rauma<br />- 1543 – Nesset<br />- 1545 – Midsund<br />- 1546 – Sandøy<br />- 1547 – Aukra<br />- 1548 – Fræna<br />- 1551 – Eide<br />- 1554 – Averøy<br />- 1557 – Gjemnes<br />- 1560 – Tingvoll<br />- 1563 – Sunndal<br />- 1566 – Surnadal<br />- 1567 – Rindal<br />- 1569 – Aure (utgått)<br />- 1571 – Halsa<br />- 1572 – Tustna (utgått)<br />- 1573 – Smøla<br />- 1576 – Aure<br />- 1601 – Trondheim<br />- 1612 – Hemne<br />- 1613 – Snillfjord<br />- 1617 – Hitra<br />- 1620 – Frøya<br />- 1621 – Ørland<br />- 1622 – Agdenes<br />- 1624 – Rissa<br />- 1627 – Bjugn<br />- 1630 – Åfjord<br />- 1632 – Roan<br />- 1633 – Osen<br />- 1634 – Oppdal<br />- 1635 – Rennebu<br />- 1636 – Meldal<br />- 1638 – Orkdal<br />- 1640 – Røros<br />- 1644 – Holtålen<br />- 1648 – Midtre Gauldal<br />- 1653 – Melhus<br />- 1657 – Skaun<br />- 1662 – Klæbu<br />- 1663 – Malvik<br />- 1664 – Selbu<br />- 1665 – Tydal<br />- 1702 – Steinkjer<br />- 1703 – Namsos<br />- 1711 – Meråker<br />- 1714 – Stjørdal<br />- 1717 – Frosta<br />- 1718 – Leksvik<br />- 1719 – Levanger<br />- 1721 – Verdal<br />- 1723 – Mosvik (utgått)<br />- 1724 – Verran<br />- 1725 – Namdalseid<br />- 1729 – Inderøy (utgått)<br />- 1736 – Snåase - Snåsa<br />- 1738 – Lierne<br />- 1739 – Røyrvik<br />- 1740 – Namsskogan<br />- 1742 – Grong<br />- 1743 – Høylandet<br />- 1744 – Overhalla<br />- 1748 – Fosnes<br />- 1749 – Flatanger<br />- 1750 – Vikna<br />- 1751 – Nærøy<br />- 1755 – Leka<br />- 1756 – Inderøy<br />- 1804 – Bodø<br />- 1805 – Narvik<br />- 1811 – Bindal<br />- 1812 – Sømna<br />- 1813 – Brønnøy<br />- 1815 – Vega<br />- 1816 – Vevelstad<br />- 1818 – Herøy i Nordland<br />- 1820 – Alstahaug<br />- 1822 – Leirfjord<br />- 1824 – Vefsn<br />- 1825 – Grane<br />- 1826 – Hattfjelldal<br />- 1827 – Dønna<br />- 1828 – Nesna<br />- 1832 – Hemnes<br />- 1833 – Rana<br />- 1834 – Lurøy<br />- 1835 – Træna<br />- 1836 – Rødøy<br />- 1837 – Meløy<br />- 1838 – Gildeskål<br />- 1839 – Beiarn<br />- 1840 – Saltdal<br />- 1841 – Fauske<br />- 1842 – Skjerstad (utgått)<br />- 1845 – Sørfold<br />- 1848 – Steigen<br />- 1849 – Hamarøy - Hábmer<br />- 1850 – Divtasvuodna - Tysfjord<br />- 1851 – Lødingen<br />- 1852 – Tjeldsund<br />- 1853 – Evenes<br />- 1854 – Ballangen<br />- 1856 – Røst<br />- 1857 – Værøy<br />- 1859 – Flakstad<br />- 1860 – Vestvågøy<br />- 1865 – Vågan<br />- 1866 – Hadsel<br />- 1867 – Bø i Nordland<br />- 1868 – Øksnes<br />- 1870 – Sortland<br />- 1871 – Andøy<br />- 1874 – Moskenes<br />- 1901 – Harstad (utgått)<br />- 1902 – Tromsø<br />- 1903 – Harstad<br />- 1911 – Kvæfjord<br />- 1913 – Skånland<br />- 1915 – Bjarkøy (utgått)<br />- 1917 – Ibestad<br />- 1919 – Gratangen<br />- 1920 – Lavangen<br />- 1922 – Bardu<br />- 1923 – Salangen<br />- 1924 – Målselv<br />- 1925 – Sørreisa<br />- 1926 – Dyrøy<br />- 1927 – Tranøy<br />- 1928 – Torsken<br />- 1929 – Berg<br />- 1931 – Lenvik<br />- 1933 – Balsfjord<br />- 1936 – Karlsøy<br />- 1938 – Lyngen<br />- 1939 – Storfjord - Omasvuotna - Omasvuono<br />- 1940 – Gáivuotna - Kåfjord<br />- 1941 – Skjervøy<br />- 1942 – Nordreisa<br />- 1943 – Kvænangen<br />- 2001 – Hammerfest (utgått)<br />- 2002 – Vardø<br />- 2003 – Vadsø<br />- 2004 – Hammerfest<br />- 2011 – Guovdageaidnu - Kautokeino<br />- 2012 – Alta<br />- 2014 – Loppa<br />- 2015 – Hasvik<br />- 2016 – Sørøysund (utgått)<br />- 2017 – Kvalsund<br />- 2018 – Måsøy<br />- 2019 – Nordkapp<br />- 2020 – Porsá?gu - Porsanger - Porsanki<br />- 2021 – Kárášjohka - Karasjok<br />- 2022 – Lebesby<br />- 2023 – Gamvik<br />- 2024 – Berlevåg<br />- 2025 – Deatnu - Tana<br />- 2027 – Unjárga - Nesseby<br />- 2028 – Båtsfjord<br />- 2030 – Sør-Varanger<br />- 2111 – Spitsbergen<br />- 2121 – Bjørnøya<br />- 2131 – Hopen<br />- 2211 – Jan Mayen<br />- 2311 – Sokkelen sør for 62 grader Nord<br />- 2321 – Sokkelen nord for 62 grader Nord</td>
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
      <td><strong>samling</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>referanse til opphavsmaterialet, kildematerialet, organisasjons/publiseringskilde.  Angir i dette datasettet hvilken samling objektet kommer fra. Begrepet kan både vise til en vitenskapelig samling og til en database, for eksempel Artsobservasjoner.<br /><br />Merknad:<br />Kan også beskrive navn på person og årsak til oppdatering</td>
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
      <td><strong>datasettNavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir hvilket datasett funnet er hentet fra. Et datasett kan være en nærmere spesifisert del av en samling.</td>
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

#### «Enumeration» BmGruppe

**Definisjon:** angir typen organisme i henhold til en forvaltningsmessig fornuftig inndeling

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a></td>
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
      <td>Fugl</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Karplanter</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sopp</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Insekter</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Lav</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Fisk</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Krepsdyr</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Moser</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Pattedyr</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Øvrige dyr</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Alger</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Edderkoppdyr</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Amfibier og reptiler</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» BmForvaltningskategori

**Definisjon:** kategorisering i ulike grader av forvaltningsinteresse. Inndelingen følger av utvalgskriteriene, slik at hvert utvalgskriterium medfører en bestemt forvaltningskategori.

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a></td>
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
      <td>Arter av særlig stor forvaltningsinteresse</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Arter av stor forvaltningsinteresse</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Fremmede arter</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» BmUtvalgskriterium

**Definisjon:** kriterier for utvalg av arter med forvaltningsstatus

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a></td>
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
      <td>Annen spesielt hensynskrevende art</td>
      <td>art som det er knyttet spesielle forvaltningsmessige problemstillinger til.</td>
      <td></td>
    </tr>
    <tr>
      <td>Ansvarsart</td>
      <td>arter der man finner mer enn 25 % av europeisk bestand i Norge. flere av disse artene er relativt vanlige i Norge.</td>
      <td></td>
    </tr>
    <tr>
      <td>Fredet art</td>
      <td>art som er fredet ved Kongelig resolusjon</td>
      <td></td>
    </tr>
    <tr>
      <td>Fremmed art</td>
      <td>arter som er fremmed for Norge og med høy eller svært høy økologisk risiko, samt arter som er internt spredd i Norge med høy økologisk risiko, ihht svartelister</td>
      <td></td>
    </tr>
    <tr>
      <td>Nær trua art</td>
      <td>art i som er plassert i kategorien NT-nær truet i gjeldende norsk rødliste</td>
      <td></td>
    </tr>
    <tr>
      <td>Prioritert art</td>
      <td>art som har status som prioritert art ihht naturmangfolddloven</td>
      <td></td>
    </tr>
    <tr>
      <td>Spesiell økologisk form</td>
      <td>angir økologisk form av en art som må ivaretas særskilt. f.eks. namdalsbleke i Namsen</td>
      <td></td>
    </tr>
    <tr>
      <td>Trua art</td>
      <td>art som er plassert i en av følgende kategorier i gjeldende norsk rødliste: CR-kritisk truet, EN-truet, VU-sårbar</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «CodeList» TaksonID

**Definisjon:** kodelisten eies og vedlikeholdes av Artsdatabanken og er tilgjengelig som tjeneste "WS_Artsnavnebase" på <a href="http://www2.artsdatabanken.no/artsnavn/Contentpages/Webservices.aspx">http://www2.artsdatabanken.no/artsnavn/Contentpages/Webservices.aspx</a>

#### «CodeList» TaksonNorskNavn

**Definisjon:** kodelisten eies og vedlikeholdes av Artsdatabanken og er tilgjengelig som tjeneste "WS_Artsnavnebase" på <a href="http://www2.artsdatabanken.no/artsnavn/Contentpages/Webservices.aspx">http://www2.artsdatabanken.no/artsnavn/Contentpages/Webservices.aspx</a>

#### «CodeList» TaksonVitNavn

**Definisjon:** kodelisten eies og vedlikeholdes av Artsdatabanken og er tilgjengelig som tjeneste "WS_Artsnavnebase" på <a href="http://www2.artsdatabanken.no/artsnavn/Contentpages/Webservices.aspx">http://www2.artsdatabanken.no/artsnavn/Contentpages/Webservices.aspx</a>

#### «Enumeration» BmFunksjonsperiode

**Definisjon:** angir årstiden som registreringen gjelder for

Eksempel: Rasteplass for fugler på trekk høst/vår

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
      <td>Vår</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sommer</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Høst</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Vinter</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Vår/høst</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hele året</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Udefinert</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» BmAktivitet

**Definisjon:** angir type aktivitet som er knyttet til observasjonen/forekomsten. Er bare aktuelt for arter som er mobile og kan ha flere ulike aktiviteter, f.eks. fugl.

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a></td>
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
      <td>Fødesøkende</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>I bevegelse</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Reproduserende</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Stasjonær</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>I dvale</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ikke registrert</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» BmFunntype

**Definisjon:** angir hvilket grunnlag oppføringen bygger på, jf basisOfRecord i Darwin Core

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a></td>
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
      <td>Objekt</td>
      <td>angir at et konkret objekt kan knyttes til funnet, så som innsamlet materiale, fossil etc.</td>
      <td></td>
    </tr>
    <tr>
      <td>Observasjon</td>
      <td>angir en observasjon av en art</td>
      <td></td>
    </tr>
    <tr>
      <td>Bilde</td>
      <td>angir at fotomateriale er knyttet til funnet</td>
      <td></td>
    </tr>
    <tr>
      <td>Beregnet</td>
      <td>angir vurdering/bedømmelse av ekspert eller basert på lokal kunnskap</td>
      <td></td>
    </tr>
    <tr>
      <td>Litteratur</td>
      <td>angir at opplysninger er hentet fra litteratur</td>
      <td></td>
    </tr>
    <tr>
      <td>Lyd</td>
      <td>angir at lydopptak er knyttet til funnet</td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Målemetode

**Definisjon:** metode som ligger til grunn for registrering av posisjon

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
      <td>Terrengmålt: Uspesifisert måleinstrument</td>
      <td>Målt i terrenget , uspesifisert metode/måleinstrument</td>
      <td></td>
    </tr>
    <tr>
      <td>Terrengmålt: Totalstasjon</td>
      <td>Målt i terrenget med totalstasjon</td>
      <td></td>
    </tr>
    <tr>
      <td>Terrengmålt: Teodolitt og el avstandsmåler</td>
      <td>Målt i terrenget med teodolitt og elektronisk avstandsmåler</td>
      <td></td>
    </tr>
    <tr>
      <td>Terrengmålt: Teodolitt og målebånd</td>
      <td>Målt i terrenget med teodolitt og målebånd</td>
      <td></td>
    </tr>
    <tr>
      <td>Terrengmålt: Ortogonalmetoden</td>
      <td>Målt i terrenget, ortogonalmetoden</td>
      <td></td>
    </tr>
    <tr>
      <td>Utmål</td>
      <td>Punkt beregnet på bakgrunn av måling mot andre punkter, slik som to avstander eller avstand og retning</td>
      <td></td>
    </tr>
    <tr>
      <td>Tatt fra plan</td>
      <td>Tatt fra plan eller godkjent tiltak</td>
      <td></td>
    </tr>
    <tr>
      <td>Annet  (denne har ingen mening, bør fjernes?)</td>
      <td>Annet</td>
      <td></td>
    </tr>
    <tr>
      <td>Stereoinstrument</td>
      <td>Målt i stereoinstrument, uspesifisert instrument</td>
      <td></td>
    </tr>
    <tr>
      <td>Aerotriangulert</td>
      <td>Punkt beregnet ved aerotriangulering</td>
      <td></td>
    </tr>
    <tr>
      <td>Stereoinstrument: Analytisk plotter</td>
      <td>Målt i stereoinstrument, analytisk plotter</td>
      <td></td>
    </tr>
    <tr>
      <td>Stereoinstrument: Autograf</td>
      <td>Målt i stereoinstrument, autograf, analogt instrument</td>
      <td></td>
    </tr>
    <tr>
      <td>Stereoinstrument: Digitalt</td>
      <td>Målt i stereoinstrument, digitalt instrument</td>
      <td></td>
    </tr>
    <tr>
      <td>Scannet fra kart</td>
      <td>Geometri overført fra kart maskinelt ved hjelp av skanner, uspesifisert kartmedium</td>
      <td></td>
    </tr>
    <tr>
      <td>Skannet fra kart: Blyantoriginal</td>
      <td>Geometri overført fra kart maskinelt ved hjelp av skanner. Kartmedium er blyantoriginal</td>
      <td></td>
    </tr>
    <tr>
      <td>Skannet fra kart: Rissefolie</td>
      <td>Geometri overført fra kart maskinelt ved hjelp av skanner. Kartmedium er rissefolie</td>
      <td></td>
    </tr>
    <tr>
      <td>Skannet fra kart: Transparent folie, god kvalitet</td>
      <td>Geometri overført fra kart maskinelt ved hjelp av skanner. Kartmedium er transparent folie av  god kvalitet.</td>
      <td></td>
    </tr>
    <tr>
      <td>Skannet fra kart: Transparent folie, mindre god kvalitet</td>
      <td>Geometri overført fra kart maskinelt ved hjelp av skanner. Kartmedium er transparent folie av mindre god kvalitet</td>
      <td></td>
    </tr>
    <tr>
      <td>Skannet fra kart: Papirkopi</td>
      <td>Geometri overført fra kart maskinelt ved hjelp av skanner. Kartmedium er papirkopi.</td>
      <td></td>
    </tr>
    <tr>
      <td>Flybåren laserscanner</td>
      <td>Målt med laserskanner fra fly</td>
      <td></td>
    </tr>
    <tr>
      <td>Bilbåren laser</td>
      <td>Målt med laserskanner plassert i kjøretøy</td>
      <td></td>
    </tr>
    <tr>
      <td>Lineær referanse</td>
      <td>brukes for objekter som er stedfestet med lineær referanse, enten disse leveres med stedfesting kun som lineære referanser, eller med koordinatgeometri avledet fra lineære referanser</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitaliseringbord: Ortofoto eller flybilde</td>
      <td>Geometri overført fra ortofoto eller flybilde ved hjelp av manuell registrering på et digitaliseringsbord, uspesifisert bildemedium</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitaliseringbord: Ortofoto, film</td>
      <td>Geometri overført fra ortofoto ved hjelp av manuell registrering på et digitaliseringsbord. Bildemedium er film</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitaliseringbord: Ortofoto, fotokopi</td>
      <td>Geometri overført fra ortofoto ved hjelp av manuell registrering på et digitaliseringsbord. Bildemedium er fotokopi</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitaliseringbord: Flybilde, film</td>
      <td>Geometri overført fra flybilde ved hjelp av manuell registrering på et digitaliseringsbord. Bildemedium er film</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitaliseringbord: Flybilde, fotokopi</td>
      <td>Geometri overført fra flybilde ved hjelp av manuell registrering på et digitaliseringsbord. Bildemedium er fotokopi</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert på skjerm fra ortofoto</td>
      <td>Geometri overført fra ortofoto ved hjelp av manuell registrering på skjerm</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert på skjerm fra satellittbilde</td>
      <td>Geometri overført fra satellittbilde ved hjelp av manuell registrering på skjerm</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert på skjerm fra andre digitale rasterdata</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert på skjerm fra tolkning av seismikk</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Vektorisering av laserdata</td>
      <td>Vektorisering fra laserdata, brukes også der vektoriseringen støttes av ortofoto</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitaliseringsbord: Kart</td>
      <td>Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord, medium uspesifisert</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitaliseringsbord: Kart, blyantoriginal</td>
      <td>Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord. Kartmedium er blyantoriginal</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitaliseringsbord: Kart, rissefoile</td>
      <td>Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord. Kartmedium er rissefolie</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitaliseringsbord: Kart, transparent foile, god kvalitet</td>
      <td>Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord. Kartmedium er transparent folie av god kvalitet, samkopi</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitaliseringsbord: Kart, transparent foile, mindre god kvalitet</td>
      <td>Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord. Kartmedium er transparent folie av mindre god kvalitet, samkopi</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitaliseringsbord: Kart, papirkopi</td>
      <td>Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord. Kartmedium er papirkopi</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert på skjerm fra skannet kart</td>
      <td>Geometri overført fra kart ved hjelp av manuell registrering på skjerm, medium skannet kart (raster), samkopi</td>
      <td></td>
    </tr>
    <tr>
      <td>Genererte data (interpolasjon)</td>
      <td>Genererte data, interpolasjonsmetode. Ikke nærmere spesifisert</td>
      <td></td>
    </tr>
    <tr>
      <td>Genererte data (interpolasjon): Terrengmodell</td>
      <td>Genererte data, interpolasjonsmetode, fra terrengmodell</td>
      <td></td>
    </tr>
    <tr>
      <td>Genererte data (interpolasjon): Vektet middel</td>
      <td>Genererte data, interpolasjonsmetode, vektet middel</td>
      <td></td>
    </tr>
    <tr>
      <td>Genererte data: Fra annen geometri</td>
      <td>Genererte data: Sirkelgeometri, korridor eller annen geometri generert ut fra f.eks et punkt eller en linje (f.eks midtlinje veg)</td>
      <td></td>
    </tr>
    <tr>
      <td>Genererte data: Generalisering</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Genererte data: Sentralpunkt</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Genererte data: Sammenknytningspunkt, randpunkt</td>
      <td>Genererte data: Sammenknytningspunkt (f.eks mellom ulike kartlegginger), randpunkt (f.eks mellom ulike kilder til kart)</td>
      <td></td>
    </tr>
    <tr>
      <td>Koordinater hentet fra GAB</td>
      <td>Koordinater hentet fra GAB, forløperen til registerdelen av matrikkelen</td>
      <td></td>
    </tr>
    <tr>
      <td>Koordinater hentet fra JREG</td>
      <td>Koordinater hentet fra JREG, jordregisteret</td>
      <td></td>
    </tr>
    <tr>
      <td>Beregnet</td>
      <td>Beregnet, uspesifisert hvordan</td>
      <td></td>
    </tr>
    <tr>
      <td>Spesielle metoder</td>
      <td>Spesielle metoder, uspesifisert</td>
      <td></td>
    </tr>
    <tr>
      <td>Spesielle metoder: Målt med stikkstang</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Spesielle metoder: Målt med waterstang</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Spesielle metoder: Målt med målehjul</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Spesielle metoder: Målt med stigningsmåler</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Fastsatt punkt</td>
      <td>Punkt fastsatt ut fra et grunnlag (kart, bilde), f.eks ved partenes enighet ved en oppmålingsforretning</td>
      <td></td>
    </tr>
    <tr>
      <td>Fastsatt ved dom eller kongelig resolusjon</td>
      <td>Geometri fastsatt ved dom, lov, traktat eller kongelig resolusjon</td>
      <td></td>
    </tr>
    <tr>
      <td>Annet (spesifiseres i filhode) ( bør vel fjernes, blir borte ved overføring mellom systemer)</td>
      <td>Annet (spesifiseres i filhode)</td>
      <td></td>
    </tr>
    <tr>
      <td>Frihåndstegning</td>
      <td>Digitalisert ut fra frihåndstegning.  Frihåndstegning er basert på svært grovt grunnlag eller ikke noe grunnlag</td>
      <td></td>
    </tr>
    <tr>
      <td>Frihåndstegning på kart</td>
      <td>Digitalisert fra krokering på kart, dvs grovt skissert på kart</td>
      <td></td>
    </tr>
    <tr>
      <td>Frihåndstegning på skjerm</td>
      <td>Digitalisert ut fra frihåndstegning (direkte på skjerm). Frihåndstegning er basert på svært grovt grunnlag eller ikke noe grunnlag</td>
      <td></td>
    </tr>
    <tr>
      <td>Treghetsstedfesting</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>GNSS: Kodemåling, relative målinger</td>
      <td>Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO): Kodemåling, relative målinger.</td>
      <td></td>
    </tr>
    <tr>
      <td>GNSS: Kodemåling, enkle målinger</td>
      <td>Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO): Kodemåling, enkle målinger.</td>
      <td></td>
    </tr>
    <tr>
      <td>GNSS: Fasemåling, statisk måling</td>
      <td>Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO): Fasemåling statisk måling.</td>
      <td></td>
    </tr>
    <tr>
      <td>GNSS: Fasemåling, andre metoder</td>
      <td>Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO): Fasemåling andre metoder.</td>
      <td></td>
    </tr>
    <tr>
      <td>Kombinasjon av GNSS/Treghet</td>
      <td>Kombinasjon av GPS/Treghet</td>
      <td></td>
    </tr>
    <tr>
      <td>GNSS: Fasemåling RTK</td>
      <td>Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO).: Fasemåling RTK (realtids kinematisk måling)</td>
      <td></td>
    </tr>
    <tr>
      <td>GNSS: Fasemåling , float-løsning</td>
      <td>Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO). Fasemåling float-løsning</td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent målemetode</td>
      <td>Målemetode er ukjent</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Synbarhet

**Definisjon:** hvor godt den kartlagte detalj var synbar ved kartleggingen

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
      <td>Fullt ut synlig/gjenfinnbar i terrenget</td>
      <td>Default</td>
      <td></td>
    </tr>
    <tr>
      <td>Dårlig gjenfinnbar i terreng</td>
      <td>Forøvrig grei å innmåle. (Benyttes bl.a. for innmåling av ledninger på lukket grøft)</td>
      <td></td>
    </tr>
    <tr>
      <td>Middels synlig i flybilde/modell</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Dårlig/ikke synlig i flybilde/modell</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Fylkesnummer

**Definisjon:** nummerering av fylker i henhold til Statistisk sentralbyrå sin offisielle liste

Merknad:
Det presiseres at fylkesnummer alltid skal ha 2 sifre, dvs. eventuelt med ledende null. Fylkesnummer benyttes for kopling mot en rekke andre registre som også benytter 2 sifre.

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
      <td></td>
      <td>Østfold</td>
      <td>01</td>
    </tr>
    <tr>
      <td></td>
      <td>Akershus</td>
      <td>02</td>
    </tr>
    <tr>
      <td></td>
      <td>Oslo</td>
      <td>03</td>
    </tr>
    <tr>
      <td></td>
      <td>Hedmark</td>
      <td>04</td>
    </tr>
    <tr>
      <td></td>
      <td>Oppland</td>
      <td>05</td>
    </tr>
    <tr>
      <td></td>
      <td>Buskerud</td>
      <td>06</td>
    </tr>
    <tr>
      <td></td>
      <td>Vestfold</td>
      <td>07</td>
    </tr>
    <tr>
      <td></td>
      <td>Telemark</td>
      <td>08</td>
    </tr>
    <tr>
      <td></td>
      <td>Aust-Agder</td>
      <td>09</td>
    </tr>
    <tr>
      <td></td>
      <td>Vest-Agder</td>
      <td>10</td>
    </tr>
    <tr>
      <td></td>
      <td>Rogaland</td>
      <td>11</td>
    </tr>
    <tr>
      <td></td>
      <td>Hordaland</td>
      <td>12</td>
    </tr>
    <tr>
      <td></td>
      <td>Bergen (utgått)</td>
      <td>13</td>
    </tr>
    <tr>
      <td></td>
      <td>Sogn og Fjordane</td>
      <td>14</td>
    </tr>
    <tr>
      <td></td>
      <td>Møre og Romsdal</td>
      <td>15</td>
    </tr>
    <tr>
      <td></td>
      <td>Sør-Trøndelag</td>
      <td>16</td>
    </tr>
    <tr>
      <td></td>
      <td>Nord-Trøndelag</td>
      <td>17</td>
    </tr>
    <tr>
      <td></td>
      <td>Nordland</td>
      <td>18</td>
    </tr>
    <tr>
      <td></td>
      <td>Troms - Romsa</td>
      <td>19</td>
    </tr>
    <tr>
      <td></td>
      <td>Finnmark - Finnmárku</td>
      <td>20</td>
    </tr>
    <tr>
      <td></td>
      <td>Svalbard</td>
      <td>21</td>
    </tr>
    <tr>
      <td></td>
      <td>Jan Mayen</td>
      <td>22</td>
    </tr>
    <tr>
      <td></td>
      <td>Kontinentalsokkelen</td>
      <td>23</td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Kommunenummer

**Definisjon:** nummerering av kommuner i henhold til Statistisk sentralbyrå sin offisielle liste samt et utvalg av utgåtte numre

Merknad: Det presiseres at kommune alltid skal ha 4 sifre, dvs. eventuelt med ledende null. Kommune benyttes for kopling mot en rekke andre registre som også benytter 4 sifre.

Merknad 2: Modelleringsverktøyet Enterprise Architect håndterer ikke samiske tegn eller tankestrek. Det betyr at det vil forekomme avvik mellom definisjonene i denne lista i SOSI modellregister og definisjonene i offisielt standarddokument.

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
      <td></td>
      <td>Halden</td>
      <td>0101</td>
    </tr>
    <tr>
      <td></td>
      <td>Sarpsborg (utgått)</td>
      <td>0102</td>
    </tr>
    <tr>
      <td></td>
      <td>Fredrikstad (utgått)</td>
      <td>0103</td>
    </tr>
    <tr>
      <td></td>
      <td>Moss</td>
      <td>0104</td>
    </tr>
    <tr>
      <td></td>
      <td>Sarpsborg</td>
      <td>0105</td>
    </tr>
    <tr>
      <td></td>
      <td>Fredrikstad</td>
      <td>0106</td>
    </tr>
    <tr>
      <td></td>
      <td>Hvaler</td>
      <td>0111</td>
    </tr>
    <tr>
      <td></td>
      <td>Borge (utgått)</td>
      <td>0113</td>
    </tr>
    <tr>
      <td></td>
      <td>Varteig (utgått)</td>
      <td>0114</td>
    </tr>
    <tr>
      <td></td>
      <td>Skjeberg (utgått)</td>
      <td>0115</td>
    </tr>
    <tr>
      <td></td>
      <td>Aremark</td>
      <td>0118</td>
    </tr>
    <tr>
      <td></td>
      <td>Marker</td>
      <td>0119</td>
    </tr>
    <tr>
      <td></td>
      <td>Rømskog</td>
      <td>0121</td>
    </tr>
    <tr>
      <td></td>
      <td>Trøgstad</td>
      <td>0122</td>
    </tr>
    <tr>
      <td></td>
      <td>Spydeberg</td>
      <td>0123</td>
    </tr>
    <tr>
      <td></td>
      <td>Askim</td>
      <td>0124</td>
    </tr>
    <tr>
      <td></td>
      <td>Eidsberg</td>
      <td>0125</td>
    </tr>
    <tr>
      <td></td>
      <td>Skiptvet</td>
      <td>0127</td>
    </tr>
    <tr>
      <td></td>
      <td>Rakkestad</td>
      <td>0128</td>
    </tr>
    <tr>
      <td></td>
      <td>Tune (utgått)</td>
      <td>0130</td>
    </tr>
    <tr>
      <td></td>
      <td>Rolvsøy (utgått)</td>
      <td>0131</td>
    </tr>
    <tr>
      <td></td>
      <td>Kråkerøy (utgått)</td>
      <td>0133</td>
    </tr>
    <tr>
      <td></td>
      <td>Onsøy (utgått)</td>
      <td>0134</td>
    </tr>
    <tr>
      <td></td>
      <td>Råde</td>
      <td>0135</td>
    </tr>
    <tr>
      <td></td>
      <td>Rygge</td>
      <td>0136</td>
    </tr>
    <tr>
      <td></td>
      <td>Våler i Østfold</td>
      <td>0137</td>
    </tr>
    <tr>
      <td></td>
      <td>Hobøl</td>
      <td>0138</td>
    </tr>
    <tr>
      <td></td>
      <td>Vestby</td>
      <td>0211</td>
    </tr>
    <tr>
      <td></td>
      <td>Ski</td>
      <td>0213</td>
    </tr>
    <tr>
      <td></td>
      <td>Ås</td>
      <td>0214</td>
    </tr>
    <tr>
      <td></td>
      <td>Frogn</td>
      <td>0215</td>
    </tr>
    <tr>
      <td></td>
      <td>Nesodden</td>
      <td>0216</td>
    </tr>
    <tr>
      <td></td>
      <td>Oppegård</td>
      <td>0217</td>
    </tr>
    <tr>
      <td></td>
      <td>Bærum</td>
      <td>0219</td>
    </tr>
    <tr>
      <td></td>
      <td>Asker</td>
      <td>0220</td>
    </tr>
    <tr>
      <td></td>
      <td>Aurskog-Høland</td>
      <td>0221</td>
    </tr>
    <tr>
      <td></td>
      <td>Sørum</td>
      <td>0226</td>
    </tr>
    <tr>
      <td></td>
      <td>Fet</td>
      <td>0227</td>
    </tr>
    <tr>
      <td></td>
      <td>Rælingen</td>
      <td>0228</td>
    </tr>
    <tr>
      <td></td>
      <td>Enebakk</td>
      <td>0229</td>
    </tr>
    <tr>
      <td></td>
      <td>Lørenskog</td>
      <td>0230</td>
    </tr>
    <tr>
      <td></td>
      <td>Skedsmo</td>
      <td>0231</td>
    </tr>
    <tr>
      <td></td>
      <td>Nittedal</td>
      <td>0233</td>
    </tr>
    <tr>
      <td></td>
      <td>Gjerdrum</td>
      <td>0234</td>
    </tr>
    <tr>
      <td></td>
      <td>Ullensaker</td>
      <td>0235</td>
    </tr>
    <tr>
      <td></td>
      <td>Nes i Akershus</td>
      <td>0236</td>
    </tr>
    <tr>
      <td></td>
      <td>Eidsvoll</td>
      <td>0237</td>
    </tr>
    <tr>
      <td></td>
      <td>Nannestad</td>
      <td>0238</td>
    </tr>
    <tr>
      <td></td>
      <td>Hurdal</td>
      <td>0239</td>
    </tr>
    <tr>
      <td></td>
      <td>Oslo</td>
      <td>0301</td>
    </tr>
    <tr>
      <td></td>
      <td>Hamar (utgått)</td>
      <td>0401</td>
    </tr>
    <tr>
      <td></td>
      <td>Kongsvinger</td>
      <td>0402</td>
    </tr>
    <tr>
      <td></td>
      <td>Hamar</td>
      <td>0403</td>
    </tr>
    <tr>
      <td></td>
      <td>Ringsaker</td>
      <td>0412</td>
    </tr>
    <tr>
      <td></td>
      <td>Vang (utgått)</td>
      <td>0414</td>
    </tr>
    <tr>
      <td></td>
      <td>Løten</td>
      <td>0415</td>
    </tr>
    <tr>
      <td></td>
      <td>Stange</td>
      <td>0417</td>
    </tr>
    <tr>
      <td></td>
      <td>Nord-Odal</td>
      <td>0418</td>
    </tr>
    <tr>
      <td></td>
      <td>Sør-Odal</td>
      <td>0419</td>
    </tr>
    <tr>
      <td></td>
      <td>Eidskog</td>
      <td>0420</td>
    </tr>
    <tr>
      <td></td>
      <td>Grue</td>
      <td>0423</td>
    </tr>
    <tr>
      <td></td>
      <td>Åsnes</td>
      <td>0425</td>
    </tr>
    <tr>
      <td></td>
      <td>Våler i Hedmark</td>
      <td>0426</td>
    </tr>
    <tr>
      <td></td>
      <td>Elverum</td>
      <td>0427</td>
    </tr>
    <tr>
      <td></td>
      <td>Trysil</td>
      <td>0428</td>
    </tr>
    <tr>
      <td></td>
      <td>Åmot</td>
      <td>0429</td>
    </tr>
    <tr>
      <td></td>
      <td>Stor-Elvdal</td>
      <td>0430</td>
    </tr>
    <tr>
      <td></td>
      <td>Rendalen</td>
      <td>0432</td>
    </tr>
    <tr>
      <td></td>
      <td>Engerdal</td>
      <td>0434</td>
    </tr>
    <tr>
      <td></td>
      <td>Tolga</td>
      <td>0436</td>
    </tr>
    <tr>
      <td></td>
      <td>Tynset</td>
      <td>0437</td>
    </tr>
    <tr>
      <td></td>
      <td>Alvdal</td>
      <td>0438</td>
    </tr>
    <tr>
      <td></td>
      <td>Folldal</td>
      <td>0439</td>
    </tr>
    <tr>
      <td></td>
      <td>Os i Hedmark</td>
      <td>0441</td>
    </tr>
    <tr>
      <td></td>
      <td>Lillehammer</td>
      <td>0501</td>
    </tr>
    <tr>
      <td></td>
      <td>Gjøvik</td>
      <td>0502</td>
    </tr>
    <tr>
      <td></td>
      <td>Dovre</td>
      <td>0511</td>
    </tr>
    <tr>
      <td></td>
      <td>Lesja</td>
      <td>0512</td>
    </tr>
    <tr>
      <td></td>
      <td>Skjåk</td>
      <td>0513</td>
    </tr>
    <tr>
      <td></td>
      <td>Lom</td>
      <td>0514</td>
    </tr>
    <tr>
      <td></td>
      <td>Vågå</td>
      <td>0515</td>
    </tr>
    <tr>
      <td></td>
      <td>Nord-Fron</td>
      <td>0516</td>
    </tr>
    <tr>
      <td></td>
      <td>Sel</td>
      <td>0517</td>
    </tr>
    <tr>
      <td></td>
      <td>Sør-Fron</td>
      <td>0519</td>
    </tr>
    <tr>
      <td></td>
      <td>Ringebu</td>
      <td>0520</td>
    </tr>
    <tr>
      <td></td>
      <td>Øyer</td>
      <td>0521</td>
    </tr>
    <tr>
      <td></td>
      <td>Gausdal</td>
      <td>0522</td>
    </tr>
    <tr>
      <td></td>
      <td>Østre Toten</td>
      <td>0528</td>
    </tr>
    <tr>
      <td></td>
      <td>Vestre Toten</td>
      <td>0529</td>
    </tr>
    <tr>
      <td></td>
      <td>Jevnaker</td>
      <td>0532</td>
    </tr>
    <tr>
      <td></td>
      <td>Lunner</td>
      <td>0533</td>
    </tr>
    <tr>
      <td></td>
      <td>Gran</td>
      <td>0534</td>
    </tr>
    <tr>
      <td></td>
      <td>Søndre Land</td>
      <td>0536</td>
    </tr>
    <tr>
      <td></td>
      <td>Nordre Land</td>
      <td>0538</td>
    </tr>
    <tr>
      <td></td>
      <td>Sør-Aurdal</td>
      <td>0540</td>
    </tr>
    <tr>
      <td></td>
      <td>Etnedal</td>
      <td>0541</td>
    </tr>
    <tr>
      <td></td>
      <td>Nord-Aurdal</td>
      <td>0542</td>
    </tr>
    <tr>
      <td></td>
      <td>Vestre Slidre</td>
      <td>0543</td>
    </tr>
    <tr>
      <td></td>
      <td>Øystre Slidre</td>
      <td>0544</td>
    </tr>
    <tr>
      <td></td>
      <td>Vang</td>
      <td>0545</td>
    </tr>
    <tr>
      <td></td>
      <td>Drammen</td>
      <td>0602</td>
    </tr>
    <tr>
      <td></td>
      <td>Kongsberg</td>
      <td>0604</td>
    </tr>
    <tr>
      <td></td>
      <td>Ringerike</td>
      <td>0605</td>
    </tr>
    <tr>
      <td></td>
      <td>Hole</td>
      <td>0612</td>
    </tr>
    <tr>
      <td></td>
      <td>Flå</td>
      <td>0615</td>
    </tr>
    <tr>
      <td></td>
      <td>Nes i Buskerud</td>
      <td>0616</td>
    </tr>
    <tr>
      <td></td>
      <td>Gol</td>
      <td>0617</td>
    </tr>
    <tr>
      <td></td>
      <td>Hemsedal</td>
      <td>0618</td>
    </tr>
    <tr>
      <td></td>
      <td>Ål</td>
      <td>0619</td>
    </tr>
    <tr>
      <td></td>
      <td>Hol</td>
      <td>0620</td>
    </tr>
    <tr>
      <td></td>
      <td>Sigdal</td>
      <td>0621</td>
    </tr>
    <tr>
      <td></td>
      <td>Krødsherad</td>
      <td>0622</td>
    </tr>
    <tr>
      <td></td>
      <td>Modum</td>
      <td>0623</td>
    </tr>
    <tr>
      <td></td>
      <td>Øvre Eiker</td>
      <td>0624</td>
    </tr>
    <tr>
      <td></td>
      <td>Nedre Eiker</td>
      <td>0625</td>
    </tr>
    <tr>
      <td></td>
      <td>Lier</td>
      <td>0626</td>
    </tr>
    <tr>
      <td></td>
      <td>Røyken</td>
      <td>0627</td>
    </tr>
    <tr>
      <td></td>
      <td>Hurum</td>
      <td>0628</td>
    </tr>
    <tr>
      <td></td>
      <td>Flesberg</td>
      <td>0631</td>
    </tr>
    <tr>
      <td></td>
      <td>Rollag</td>
      <td>0632</td>
    </tr>
    <tr>
      <td></td>
      <td>Nore og Uvdal</td>
      <td>0633</td>
    </tr>
    <tr>
      <td></td>
      <td>Horten</td>
      <td>0701</td>
    </tr>
    <tr>
      <td></td>
      <td>Holmestrand</td>
      <td>0702</td>
    </tr>
    <tr>
      <td></td>
      <td>Horten (utgått)</td>
      <td>0703</td>
    </tr>
    <tr>
      <td></td>
      <td>Tønsberg</td>
      <td>0704</td>
    </tr>
    <tr>
      <td></td>
      <td>Tønsberg (utgått)</td>
      <td>0705</td>
    </tr>
    <tr>
      <td></td>
      <td>Sandefjord</td>
      <td>0706</td>
    </tr>
    <tr>
      <td></td>
      <td>Larvik (utgått)</td>
      <td>0707</td>
    </tr>
    <tr>
      <td></td>
      <td>Stavern (utgått)</td>
      <td>0708</td>
    </tr>
    <tr>
      <td></td>
      <td>Larvik</td>
      <td>0709</td>
    </tr>
    <tr>
      <td></td>
      <td>Svelvik</td>
      <td>0711</td>
    </tr>
    <tr>
      <td></td>
      <td>Sande i Vestfold</td>
      <td>0713</td>
    </tr>
    <tr>
      <td></td>
      <td>Hof</td>
      <td>0714</td>
    </tr>
    <tr>
      <td></td>
      <td>Re</td>
      <td>0716</td>
    </tr>
    <tr>
      <td></td>
      <td>Borre (utgått)</td>
      <td>0717</td>
    </tr>
    <tr>
      <td></td>
      <td>Ramnes (utgått)</td>
      <td>0718</td>
    </tr>
    <tr>
      <td></td>
      <td>Andebu</td>
      <td>0719</td>
    </tr>
    <tr>
      <td></td>
      <td>Stokke</td>
      <td>0720</td>
    </tr>
    <tr>
      <td></td>
      <td>Sem (utgått)</td>
      <td>0721</td>
    </tr>
    <tr>
      <td></td>
      <td>Nøtterøy</td>
      <td>0722</td>
    </tr>
    <tr>
      <td></td>
      <td>Tjøme</td>
      <td>0723</td>
    </tr>
    <tr>
      <td></td>
      <td>Tjølling (utgått)</td>
      <td>0725</td>
    </tr>
    <tr>
      <td></td>
      <td>Brunlanes (utgått)</td>
      <td>0726</td>
    </tr>
    <tr>
      <td></td>
      <td>Hedrum (utgått)</td>
      <td>0727</td>
    </tr>
    <tr>
      <td></td>
      <td>Lardal</td>
      <td>0728</td>
    </tr>
    <tr>
      <td></td>
      <td>Porsgrunn</td>
      <td>0805</td>
    </tr>
    <tr>
      <td></td>
      <td>Skien</td>
      <td>0806</td>
    </tr>
    <tr>
      <td></td>
      <td>Notodden</td>
      <td>0807</td>
    </tr>
    <tr>
      <td></td>
      <td>Siljan</td>
      <td>0811</td>
    </tr>
    <tr>
      <td></td>
      <td>Bamble</td>
      <td>0814</td>
    </tr>
    <tr>
      <td></td>
      <td>Kragerø</td>
      <td>0815</td>
    </tr>
    <tr>
      <td></td>
      <td>Drangedal</td>
      <td>0817</td>
    </tr>
    <tr>
      <td></td>
      <td>Nome</td>
      <td>0819</td>
    </tr>
    <tr>
      <td></td>
      <td>Bø i Telemark</td>
      <td>0821</td>
    </tr>
    <tr>
      <td></td>
      <td>Sauherad</td>
      <td>0822</td>
    </tr>
    <tr>
      <td></td>
      <td>Tinn</td>
      <td>0826</td>
    </tr>
    <tr>
      <td></td>
      <td>Hjartdal</td>
      <td>0827</td>
    </tr>
    <tr>
      <td></td>
      <td>Seljord</td>
      <td>0828</td>
    </tr>
    <tr>
      <td></td>
      <td>Kviteseid</td>
      <td>0829</td>
    </tr>
    <tr>
      <td></td>
      <td>Nissedal</td>
      <td>0830</td>
    </tr>
    <tr>
      <td></td>
      <td>Fyresdal</td>
      <td>0831</td>
    </tr>
    <tr>
      <td></td>
      <td>Tokke</td>
      <td>0833</td>
    </tr>
    <tr>
      <td></td>
      <td>Vinje</td>
      <td>0834</td>
    </tr>
    <tr>
      <td></td>
      <td>Risør</td>
      <td>0901</td>
    </tr>
    <tr>
      <td></td>
      <td>Arendal (utgått)</td>
      <td>0903</td>
    </tr>
    <tr>
      <td></td>
      <td>Grimstad</td>
      <td>0904</td>
    </tr>
    <tr>
      <td></td>
      <td>Arendal</td>
      <td>0906</td>
    </tr>
    <tr>
      <td></td>
      <td>Gjerstad</td>
      <td>0911</td>
    </tr>
    <tr>
      <td></td>
      <td>Vegårshei</td>
      <td>0912</td>
    </tr>
    <tr>
      <td></td>
      <td>Tvedestrand</td>
      <td>0914</td>
    </tr>
    <tr>
      <td></td>
      <td>Moland (utgått)</td>
      <td>0918</td>
    </tr>
    <tr>
      <td></td>
      <td>Froland</td>
      <td>0919</td>
    </tr>
    <tr>
      <td></td>
      <td>Øyestad (utgått)</td>
      <td>0920</td>
    </tr>
    <tr>
      <td></td>
      <td>Tromøy (utgått)</td>
      <td>0921</td>
    </tr>
    <tr>
      <td></td>
      <td>Hisøy (utgått)</td>
      <td>0922</td>
    </tr>
    <tr>
      <td></td>
      <td>Lillesand</td>
      <td>0926</td>
    </tr>
    <tr>
      <td></td>
      <td>Birkenes</td>
      <td>0928</td>
    </tr>
    <tr>
      <td></td>
      <td>Åmli</td>
      <td>0929</td>
    </tr>
    <tr>
      <td></td>
      <td>Iveland</td>
      <td>0935</td>
    </tr>
    <tr>
      <td></td>
      <td>Evje og Hornnes</td>
      <td>0937</td>
    </tr>
    <tr>
      <td></td>
      <td>Bygland</td>
      <td>0938</td>
    </tr>
    <tr>
      <td></td>
      <td>Valle</td>
      <td>0940</td>
    </tr>
    <tr>
      <td></td>
      <td>Bykle</td>
      <td>0941</td>
    </tr>
    <tr>
      <td></td>
      <td>Kristiansand</td>
      <td>1001</td>
    </tr>
    <tr>
      <td></td>
      <td>Mandal</td>
      <td>1002</td>
    </tr>
    <tr>
      <td></td>
      <td>Farsund</td>
      <td>1003</td>
    </tr>
    <tr>
      <td></td>
      <td>Flekkefjord</td>
      <td>1004</td>
    </tr>
    <tr>
      <td></td>
      <td>Vennesla</td>
      <td>1014</td>
    </tr>
    <tr>
      <td></td>
      <td>Songdalen</td>
      <td>1017</td>
    </tr>
    <tr>
      <td></td>
      <td>Søgne</td>
      <td>1018</td>
    </tr>
    <tr>
      <td></td>
      <td>Marnardal</td>
      <td>1021</td>
    </tr>
    <tr>
      <td></td>
      <td>Åseral</td>
      <td>1026</td>
    </tr>
    <tr>
      <td></td>
      <td>Audnedal</td>
      <td>1027</td>
    </tr>
    <tr>
      <td></td>
      <td>Lindesnes</td>
      <td>1029</td>
    </tr>
    <tr>
      <td></td>
      <td>Lyngdal</td>
      <td>1032</td>
    </tr>
    <tr>
      <td></td>
      <td>Hægebostad</td>
      <td>1034</td>
    </tr>
    <tr>
      <td></td>
      <td>Kvinesdal</td>
      <td>1037</td>
    </tr>
    <tr>
      <td></td>
      <td>Sirdal</td>
      <td>1046</td>
    </tr>
    <tr>
      <td></td>
      <td>Eigersund</td>
      <td>1101</td>
    </tr>
    <tr>
      <td></td>
      <td>Sandnes</td>
      <td>1102</td>
    </tr>
    <tr>
      <td></td>
      <td>Stavanger</td>
      <td>1103</td>
    </tr>
    <tr>
      <td></td>
      <td>Haugesund</td>
      <td>1106</td>
    </tr>
    <tr>
      <td></td>
      <td>Sokndal</td>
      <td>1111</td>
    </tr>
    <tr>
      <td></td>
      <td>Lund</td>
      <td>1112</td>
    </tr>
    <tr>
      <td></td>
      <td>Bjerkreim</td>
      <td>1114</td>
    </tr>
    <tr>
      <td></td>
      <td>Hå</td>
      <td>1119</td>
    </tr>
    <tr>
      <td></td>
      <td>Klepp</td>
      <td>1120</td>
    </tr>
    <tr>
      <td></td>
      <td>Time</td>
      <td>1121</td>
    </tr>
    <tr>
      <td></td>
      <td>Gjesdal</td>
      <td>1122</td>
    </tr>
    <tr>
      <td></td>
      <td>Sola</td>
      <td>1124</td>
    </tr>
    <tr>
      <td></td>
      <td>Randaberg</td>
      <td>1127</td>
    </tr>
    <tr>
      <td></td>
      <td>Forsand</td>
      <td>1129</td>
    </tr>
    <tr>
      <td></td>
      <td>Strand</td>
      <td>1130</td>
    </tr>
    <tr>
      <td></td>
      <td>Hjelmeland</td>
      <td>1133</td>
    </tr>
    <tr>
      <td></td>
      <td>Suldal</td>
      <td>1134</td>
    </tr>
    <tr>
      <td></td>
      <td>Sauda</td>
      <td>1135</td>
    </tr>
    <tr>
      <td></td>
      <td>Finnøy</td>
      <td>1141</td>
    </tr>
    <tr>
      <td></td>
      <td>Rennesøy</td>
      <td>1142</td>
    </tr>
    <tr>
      <td></td>
      <td>Kvitsøy</td>
      <td>1144</td>
    </tr>
    <tr>
      <td></td>
      <td>Bokn</td>
      <td>1145</td>
    </tr>
    <tr>
      <td></td>
      <td>Tysvær</td>
      <td>1146</td>
    </tr>
    <tr>
      <td></td>
      <td>Karmøy</td>
      <td>1149</td>
    </tr>
    <tr>
      <td></td>
      <td>Utsira</td>
      <td>1151</td>
    </tr>
    <tr>
      <td></td>
      <td>Vindafjord ((utgått)</td>
      <td>1154</td>
    </tr>
    <tr>
      <td></td>
      <td>Ølen (utgått)</td>
      <td>1159</td>
    </tr>
    <tr>
      <td></td>
      <td>Vindafjord</td>
      <td>1160</td>
    </tr>
    <tr>
      <td></td>
      <td>Bergen</td>
      <td>1201</td>
    </tr>
    <tr>
      <td></td>
      <td>Etne</td>
      <td>1211</td>
    </tr>
    <tr>
      <td></td>
      <td>Ølen (utgått)</td>
      <td>1214</td>
    </tr>
    <tr>
      <td></td>
      <td>Sveio</td>
      <td>1216</td>
    </tr>
    <tr>
      <td></td>
      <td>Bømlo</td>
      <td>1219</td>
    </tr>
    <tr>
      <td></td>
      <td>Stord</td>
      <td>1221</td>
    </tr>
    <tr>
      <td></td>
      <td>Fitjar</td>
      <td>1222</td>
    </tr>
    <tr>
      <td></td>
      <td>Tysnes</td>
      <td>1223</td>
    </tr>
    <tr>
      <td></td>
      <td>Kvinnherad</td>
      <td>1224</td>
    </tr>
    <tr>
      <td></td>
      <td>Jondal</td>
      <td>1227</td>
    </tr>
    <tr>
      <td></td>
      <td>Odda</td>
      <td>1228</td>
    </tr>
    <tr>
      <td></td>
      <td>Ullensvang</td>
      <td>1231</td>
    </tr>
    <tr>
      <td></td>
      <td>Eidfjord</td>
      <td>1232</td>
    </tr>
    <tr>
      <td></td>
      <td>Ulvik</td>
      <td>1233</td>
    </tr>
    <tr>
      <td></td>
      <td>Granvin</td>
      <td>1234</td>
    </tr>
    <tr>
      <td></td>
      <td>Voss</td>
      <td>1235</td>
    </tr>
    <tr>
      <td></td>
      <td>Kvam</td>
      <td>1238</td>
    </tr>
    <tr>
      <td></td>
      <td>Fusa</td>
      <td>1241</td>
    </tr>
    <tr>
      <td></td>
      <td>Samnanger</td>
      <td>1242</td>
    </tr>
    <tr>
      <td></td>
      <td>Os i Hordaland</td>
      <td>1243</td>
    </tr>
    <tr>
      <td></td>
      <td>Austevoll</td>
      <td>1244</td>
    </tr>
    <tr>
      <td></td>
      <td>Sund</td>
      <td>1245</td>
    </tr>
    <tr>
      <td></td>
      <td>Fjell</td>
      <td>1246</td>
    </tr>
    <tr>
      <td></td>
      <td>Askøy</td>
      <td>1247</td>
    </tr>
    <tr>
      <td></td>
      <td>Vaksdal</td>
      <td>1251</td>
    </tr>
    <tr>
      <td></td>
      <td>Modalen</td>
      <td>1252</td>
    </tr>
    <tr>
      <td></td>
      <td>Osterøy</td>
      <td>1253</td>
    </tr>
    <tr>
      <td></td>
      <td>Meland</td>
      <td>1256</td>
    </tr>
    <tr>
      <td></td>
      <td>Øygarden</td>
      <td>1259</td>
    </tr>
    <tr>
      <td></td>
      <td>Radøy</td>
      <td>1260</td>
    </tr>
    <tr>
      <td></td>
      <td>Lindås</td>
      <td>1263</td>
    </tr>
    <tr>
      <td></td>
      <td>Austrheim</td>
      <td>1264</td>
    </tr>
    <tr>
      <td></td>
      <td>Fedje</td>
      <td>1265</td>
    </tr>
    <tr>
      <td></td>
      <td>Masfjorden</td>
      <td>1266</td>
    </tr>
    <tr>
      <td></td>
      <td>Flora</td>
      <td>1401</td>
    </tr>
    <tr>
      <td></td>
      <td>Gulen</td>
      <td>1411</td>
    </tr>
    <tr>
      <td></td>
      <td>Solund</td>
      <td>1412</td>
    </tr>
    <tr>
      <td></td>
      <td>Hyllestad</td>
      <td>1413</td>
    </tr>
    <tr>
      <td></td>
      <td>Høyanger</td>
      <td>1416</td>
    </tr>
    <tr>
      <td></td>
      <td>Vik</td>
      <td>1417</td>
    </tr>
    <tr>
      <td></td>
      <td>Balestrand</td>
      <td>1418</td>
    </tr>
    <tr>
      <td></td>
      <td>Leikanger</td>
      <td>1419</td>
    </tr>
    <tr>
      <td></td>
      <td>Sogndal</td>
      <td>1420</td>
    </tr>
    <tr>
      <td></td>
      <td>Aurland</td>
      <td>1421</td>
    </tr>
    <tr>
      <td></td>
      <td>Lærdal</td>
      <td>1422</td>
    </tr>
    <tr>
      <td></td>
      <td>Årdal</td>
      <td>1424</td>
    </tr>
    <tr>
      <td></td>
      <td>Luster</td>
      <td>1426</td>
    </tr>
    <tr>
      <td></td>
      <td>Askvoll</td>
      <td>1428</td>
    </tr>
    <tr>
      <td></td>
      <td>Fjaler</td>
      <td>1429</td>
    </tr>
    <tr>
      <td></td>
      <td>Gaular</td>
      <td>1430</td>
    </tr>
    <tr>
      <td></td>
      <td>Jølster</td>
      <td>1431</td>
    </tr>
    <tr>
      <td></td>
      <td>Førde</td>
      <td>1432</td>
    </tr>
    <tr>
      <td></td>
      <td>Naustdal</td>
      <td>1433</td>
    </tr>
    <tr>
      <td></td>
      <td>Bremanger</td>
      <td>1438</td>
    </tr>
    <tr>
      <td></td>
      <td>Vågsøy</td>
      <td>1439</td>
    </tr>
    <tr>
      <td></td>
      <td>Selje</td>
      <td>1441</td>
    </tr>
    <tr>
      <td></td>
      <td>Eid</td>
      <td>1443</td>
    </tr>
    <tr>
      <td></td>
      <td>Hornindal</td>
      <td>1444</td>
    </tr>
    <tr>
      <td></td>
      <td>Gloppen</td>
      <td>1445</td>
    </tr>
    <tr>
      <td></td>
      <td>Stryn</td>
      <td>1449</td>
    </tr>
    <tr>
      <td></td>
      <td>Molde</td>
      <td>1502</td>
    </tr>
    <tr>
      <td></td>
      <td>Ålesund</td>
      <td>1504</td>
    </tr>
    <tr>
      <td></td>
      <td>Kristiansund</td>
      <td>1505</td>
    </tr>
    <tr>
      <td></td>
      <td>Vanylven</td>
      <td>1511</td>
    </tr>
    <tr>
      <td></td>
      <td>Sande i Møre og Romsdal</td>
      <td>1514</td>
    </tr>
    <tr>
      <td></td>
      <td>Herøy i  Møre og Romsdal</td>
      <td>1515</td>
    </tr>
    <tr>
      <td></td>
      <td>Ulstein</td>
      <td>1516</td>
    </tr>
    <tr>
      <td></td>
      <td>Hareid</td>
      <td>1517</td>
    </tr>
    <tr>
      <td></td>
      <td>Volda</td>
      <td>1519</td>
    </tr>
    <tr>
      <td></td>
      <td>Ørsta</td>
      <td>1520</td>
    </tr>
    <tr>
      <td></td>
      <td>Ørskog</td>
      <td>1523</td>
    </tr>
    <tr>
      <td></td>
      <td>Norddal</td>
      <td>1524</td>
    </tr>
    <tr>
      <td></td>
      <td>Stranda</td>
      <td>1525</td>
    </tr>
    <tr>
      <td></td>
      <td>Stordal</td>
      <td>1526</td>
    </tr>
    <tr>
      <td></td>
      <td>Sykkylven</td>
      <td>1528</td>
    </tr>
    <tr>
      <td></td>
      <td>Skodje</td>
      <td>1529</td>
    </tr>
    <tr>
      <td></td>
      <td>Sula</td>
      <td>1531</td>
    </tr>
    <tr>
      <td></td>
      <td>Giske</td>
      <td>1532</td>
    </tr>
    <tr>
      <td></td>
      <td>Haram</td>
      <td>1534</td>
    </tr>
    <tr>
      <td></td>
      <td>Vestnes</td>
      <td>1535</td>
    </tr>
    <tr>
      <td></td>
      <td>Rindal</td>
      <td>1537</td>
    </tr>
    <tr>
      <td></td>
      <td>Rauma</td>
      <td>1539</td>
    </tr>
    <tr>
      <td></td>
      <td>Nesset</td>
      <td>1543</td>
    </tr>
    <tr>
      <td></td>
      <td>Midsund</td>
      <td>1545</td>
    </tr>
    <tr>
      <td></td>
      <td>Sandøy</td>
      <td>1546</td>
    </tr>
    <tr>
      <td></td>
      <td>Aukra</td>
      <td>1547</td>
    </tr>
    <tr>
      <td></td>
      <td>Fræna</td>
      <td>1548</td>
    </tr>
    <tr>
      <td></td>
      <td>Eide</td>
      <td>1551</td>
    </tr>
    <tr>
      <td></td>
      <td>Averøy</td>
      <td>1554</td>
    </tr>
    <tr>
      <td></td>
      <td>Gjemnes</td>
      <td>1557</td>
    </tr>
    <tr>
      <td></td>
      <td>Tingvoll</td>
      <td>1560</td>
    </tr>
    <tr>
      <td></td>
      <td>Sunndal</td>
      <td>1563</td>
    </tr>
    <tr>
      <td></td>
      <td>Surnadal</td>
      <td>1566</td>
    </tr>
    <tr>
      <td></td>
      <td>Rindal</td>
      <td>1567</td>
    </tr>
    <tr>
      <td></td>
      <td>Aure (utgått)</td>
      <td>1569</td>
    </tr>
    <tr>
      <td></td>
      <td>Halsa</td>
      <td>1571</td>
    </tr>
    <tr>
      <td></td>
      <td>Tustna (utgått)</td>
      <td>1572</td>
    </tr>
    <tr>
      <td></td>
      <td>Smøla</td>
      <td>1573</td>
    </tr>
    <tr>
      <td></td>
      <td>Aure</td>
      <td>1576</td>
    </tr>
    <tr>
      <td></td>
      <td>Trondheim</td>
      <td>1601</td>
    </tr>
    <tr>
      <td></td>
      <td>Hemne</td>
      <td>1612</td>
    </tr>
    <tr>
      <td></td>
      <td>Snillfjord</td>
      <td>1613</td>
    </tr>
    <tr>
      <td></td>
      <td>Hitra</td>
      <td>1617</td>
    </tr>
    <tr>
      <td></td>
      <td>Frøya</td>
      <td>1620</td>
    </tr>
    <tr>
      <td></td>
      <td>Ørland</td>
      <td>1621</td>
    </tr>
    <tr>
      <td></td>
      <td>Agdenes</td>
      <td>1622</td>
    </tr>
    <tr>
      <td></td>
      <td>Rissa</td>
      <td>1624</td>
    </tr>
    <tr>
      <td></td>
      <td>Bjugn</td>
      <td>1627</td>
    </tr>
    <tr>
      <td></td>
      <td>Åfjord</td>
      <td>1630</td>
    </tr>
    <tr>
      <td></td>
      <td>Roan</td>
      <td>1632</td>
    </tr>
    <tr>
      <td></td>
      <td>Osen</td>
      <td>1633</td>
    </tr>
    <tr>
      <td></td>
      <td>Oppdal</td>
      <td>1634</td>
    </tr>
    <tr>
      <td></td>
      <td>Rennebu</td>
      <td>1635</td>
    </tr>
    <tr>
      <td></td>
      <td>Meldal</td>
      <td>1636</td>
    </tr>
    <tr>
      <td></td>
      <td>Orkdal</td>
      <td>1638</td>
    </tr>
    <tr>
      <td></td>
      <td>Røros</td>
      <td>1640</td>
    </tr>
    <tr>
      <td></td>
      <td>Holtålen</td>
      <td>1644</td>
    </tr>
    <tr>
      <td></td>
      <td>Midtre Gauldal</td>
      <td>1648</td>
    </tr>
    <tr>
      <td></td>
      <td>Melhus</td>
      <td>1653</td>
    </tr>
    <tr>
      <td></td>
      <td>Skaun</td>
      <td>1657</td>
    </tr>
    <tr>
      <td></td>
      <td>Klæbu</td>
      <td>1662</td>
    </tr>
    <tr>
      <td></td>
      <td>Malvik</td>
      <td>1663</td>
    </tr>
    <tr>
      <td></td>
      <td>Selbu</td>
      <td>1664</td>
    </tr>
    <tr>
      <td></td>
      <td>Tydal</td>
      <td>1665</td>
    </tr>
    <tr>
      <td></td>
      <td>Steinkjer</td>
      <td>1702</td>
    </tr>
    <tr>
      <td></td>
      <td>Namsos</td>
      <td>1703</td>
    </tr>
    <tr>
      <td></td>
      <td>Meråker</td>
      <td>1711</td>
    </tr>
    <tr>
      <td></td>
      <td>Stjørdal</td>
      <td>1714</td>
    </tr>
    <tr>
      <td></td>
      <td>Frosta</td>
      <td>1717</td>
    </tr>
    <tr>
      <td></td>
      <td>Leksvik</td>
      <td>1718</td>
    </tr>
    <tr>
      <td></td>
      <td>Levanger</td>
      <td>1719</td>
    </tr>
    <tr>
      <td></td>
      <td>Verdal</td>
      <td>1721</td>
    </tr>
    <tr>
      <td></td>
      <td>Mosvik (utgått)</td>
      <td>1723</td>
    </tr>
    <tr>
      <td></td>
      <td>Verran</td>
      <td>1724</td>
    </tr>
    <tr>
      <td></td>
      <td>Namdalseid</td>
      <td>1725</td>
    </tr>
    <tr>
      <td></td>
      <td>Inderøy (utgått)</td>
      <td>1729</td>
    </tr>
    <tr>
      <td></td>
      <td>Snåase - Snåsa</td>
      <td>1736</td>
    </tr>
    <tr>
      <td></td>
      <td>Lierne</td>
      <td>1738</td>
    </tr>
    <tr>
      <td></td>
      <td>Røyrvik</td>
      <td>1739</td>
    </tr>
    <tr>
      <td></td>
      <td>Namsskogan</td>
      <td>1740</td>
    </tr>
    <tr>
      <td></td>
      <td>Grong</td>
      <td>1742</td>
    </tr>
    <tr>
      <td></td>
      <td>Høylandet</td>
      <td>1743</td>
    </tr>
    <tr>
      <td></td>
      <td>Overhalla</td>
      <td>1744</td>
    </tr>
    <tr>
      <td></td>
      <td>Fosnes</td>
      <td>1748</td>
    </tr>
    <tr>
      <td></td>
      <td>Flatanger</td>
      <td>1749</td>
    </tr>
    <tr>
      <td></td>
      <td>Vikna</td>
      <td>1750</td>
    </tr>
    <tr>
      <td></td>
      <td>Nærøy</td>
      <td>1751</td>
    </tr>
    <tr>
      <td></td>
      <td>Leka</td>
      <td>1755</td>
    </tr>
    <tr>
      <td></td>
      <td>Inderøy</td>
      <td>1756</td>
    </tr>
    <tr>
      <td></td>
      <td>Bodø</td>
      <td>1804</td>
    </tr>
    <tr>
      <td></td>
      <td>Narvik</td>
      <td>1805</td>
    </tr>
    <tr>
      <td></td>
      <td>Bindal</td>
      <td>1811</td>
    </tr>
    <tr>
      <td></td>
      <td>Sømna</td>
      <td>1812</td>
    </tr>
    <tr>
      <td></td>
      <td>Brønnøy</td>
      <td>1813</td>
    </tr>
    <tr>
      <td></td>
      <td>Vega</td>
      <td>1815</td>
    </tr>
    <tr>
      <td></td>
      <td>Vevelstad</td>
      <td>1816</td>
    </tr>
    <tr>
      <td></td>
      <td>Herøy i Nordland</td>
      <td>1818</td>
    </tr>
    <tr>
      <td></td>
      <td>Alstahaug</td>
      <td>1820</td>
    </tr>
    <tr>
      <td></td>
      <td>Leirfjord</td>
      <td>1822</td>
    </tr>
    <tr>
      <td></td>
      <td>Vefsn</td>
      <td>1824</td>
    </tr>
    <tr>
      <td></td>
      <td>Grane</td>
      <td>1825</td>
    </tr>
    <tr>
      <td></td>
      <td>Hattfjelldal</td>
      <td>1826</td>
    </tr>
    <tr>
      <td></td>
      <td>Dønna</td>
      <td>1827</td>
    </tr>
    <tr>
      <td></td>
      <td>Nesna</td>
      <td>1828</td>
    </tr>
    <tr>
      <td></td>
      <td>Hemnes</td>
      <td>1832</td>
    </tr>
    <tr>
      <td></td>
      <td>Rana</td>
      <td>1833</td>
    </tr>
    <tr>
      <td></td>
      <td>Lurøy</td>
      <td>1834</td>
    </tr>
    <tr>
      <td></td>
      <td>Træna</td>
      <td>1835</td>
    </tr>
    <tr>
      <td></td>
      <td>Rødøy</td>
      <td>1836</td>
    </tr>
    <tr>
      <td></td>
      <td>Meløy</td>
      <td>1837</td>
    </tr>
    <tr>
      <td></td>
      <td>Gildeskål</td>
      <td>1838</td>
    </tr>
    <tr>
      <td></td>
      <td>Beiarn</td>
      <td>1839</td>
    </tr>
    <tr>
      <td></td>
      <td>Saltdal</td>
      <td>1840</td>
    </tr>
    <tr>
      <td></td>
      <td>Fauske</td>
      <td>1841</td>
    </tr>
    <tr>
      <td></td>
      <td>Skjerstad (utgått)</td>
      <td>1842</td>
    </tr>
    <tr>
      <td></td>
      <td>Sørfold</td>
      <td>1845</td>
    </tr>
    <tr>
      <td></td>
      <td>Steigen</td>
      <td>1848</td>
    </tr>
    <tr>
      <td></td>
      <td>Hamarøy - Hábmer</td>
      <td>1849</td>
    </tr>
    <tr>
      <td></td>
      <td>Divtasvuodna - Tysfjord</td>
      <td>1850</td>
    </tr>
    <tr>
      <td></td>
      <td>Lødingen</td>
      <td>1851</td>
    </tr>
    <tr>
      <td></td>
      <td>Tjeldsund</td>
      <td>1852</td>
    </tr>
    <tr>
      <td></td>
      <td>Evenes</td>
      <td>1853</td>
    </tr>
    <tr>
      <td></td>
      <td>Ballangen</td>
      <td>1854</td>
    </tr>
    <tr>
      <td></td>
      <td>Røst</td>
      <td>1856</td>
    </tr>
    <tr>
      <td></td>
      <td>Værøy</td>
      <td>1857</td>
    </tr>
    <tr>
      <td></td>
      <td>Flakstad</td>
      <td>1859</td>
    </tr>
    <tr>
      <td></td>
      <td>Vestvågøy</td>
      <td>1860</td>
    </tr>
    <tr>
      <td></td>
      <td>Vågan</td>
      <td>1865</td>
    </tr>
    <tr>
      <td></td>
      <td>Hadsel</td>
      <td>1866</td>
    </tr>
    <tr>
      <td></td>
      <td>Bø i Nordland</td>
      <td>1867</td>
    </tr>
    <tr>
      <td></td>
      <td>Øksnes</td>
      <td>1868</td>
    </tr>
    <tr>
      <td></td>
      <td>Sortland</td>
      <td>1870</td>
    </tr>
    <tr>
      <td></td>
      <td>Andøy</td>
      <td>1871</td>
    </tr>
    <tr>
      <td></td>
      <td>Moskenes</td>
      <td>1874</td>
    </tr>
    <tr>
      <td></td>
      <td>Harstad (utgått)</td>
      <td>1901</td>
    </tr>
    <tr>
      <td></td>
      <td>Tromsø</td>
      <td>1902</td>
    </tr>
    <tr>
      <td></td>
      <td>Harstad</td>
      <td>1903</td>
    </tr>
    <tr>
      <td></td>
      <td>Kvæfjord</td>
      <td>1911</td>
    </tr>
    <tr>
      <td></td>
      <td>Skånland</td>
      <td>1913</td>
    </tr>
    <tr>
      <td></td>
      <td>Bjarkøy (utgått)</td>
      <td>1915</td>
    </tr>
    <tr>
      <td></td>
      <td>Ibestad</td>
      <td>1917</td>
    </tr>
    <tr>
      <td></td>
      <td>Gratangen</td>
      <td>1919</td>
    </tr>
    <tr>
      <td></td>
      <td>Lavangen</td>
      <td>1920</td>
    </tr>
    <tr>
      <td></td>
      <td>Bardu</td>
      <td>1922</td>
    </tr>
    <tr>
      <td></td>
      <td>Salangen</td>
      <td>1923</td>
    </tr>
    <tr>
      <td></td>
      <td>Målselv</td>
      <td>1924</td>
    </tr>
    <tr>
      <td></td>
      <td>Sørreisa</td>
      <td>1925</td>
    </tr>
    <tr>
      <td></td>
      <td>Dyrøy</td>
      <td>1926</td>
    </tr>
    <tr>
      <td></td>
      <td>Tranøy</td>
      <td>1927</td>
    </tr>
    <tr>
      <td></td>
      <td>Torsken</td>
      <td>1928</td>
    </tr>
    <tr>
      <td></td>
      <td>Berg</td>
      <td>1929</td>
    </tr>
    <tr>
      <td></td>
      <td>Lenvik</td>
      <td>1931</td>
    </tr>
    <tr>
      <td></td>
      <td>Balsfjord</td>
      <td>1933</td>
    </tr>
    <tr>
      <td></td>
      <td>Karlsøy</td>
      <td>1936</td>
    </tr>
    <tr>
      <td></td>
      <td>Lyngen</td>
      <td>1938</td>
    </tr>
    <tr>
      <td></td>
      <td>Storfjord - Omasvuotna - Omasvuono</td>
      <td>1939</td>
    </tr>
    <tr>
      <td></td>
      <td>Gáivuotna - Kåfjord</td>
      <td>1940</td>
    </tr>
    <tr>
      <td></td>
      <td>Skjervøy</td>
      <td>1941</td>
    </tr>
    <tr>
      <td></td>
      <td>Nordreisa</td>
      <td>1942</td>
    </tr>
    <tr>
      <td></td>
      <td>Kvænangen</td>
      <td>1943</td>
    </tr>
    <tr>
      <td></td>
      <td>Hammerfest (utgått)</td>
      <td>2001</td>
    </tr>
    <tr>
      <td></td>
      <td>Vardø</td>
      <td>2002</td>
    </tr>
    <tr>
      <td></td>
      <td>Vadsø</td>
      <td>2003</td>
    </tr>
    <tr>
      <td></td>
      <td>Hammerfest</td>
      <td>2004</td>
    </tr>
    <tr>
      <td></td>
      <td>Guovdageaidnu - Kautokeino</td>
      <td>2011</td>
    </tr>
    <tr>
      <td></td>
      <td>Alta</td>
      <td>2012</td>
    </tr>
    <tr>
      <td></td>
      <td>Loppa</td>
      <td>2014</td>
    </tr>
    <tr>
      <td></td>
      <td>Hasvik</td>
      <td>2015</td>
    </tr>
    <tr>
      <td></td>
      <td>Sørøysund (utgått)</td>
      <td>2016</td>
    </tr>
    <tr>
      <td></td>
      <td>Kvalsund</td>
      <td>2017</td>
    </tr>
    <tr>
      <td></td>
      <td>Måsøy</td>
      <td>2018</td>
    </tr>
    <tr>
      <td></td>
      <td>Nordkapp</td>
      <td>2019</td>
    </tr>
    <tr>
      <td></td>
      <td>Porsá?gu - Porsanger - Porsanki</td>
      <td>2020</td>
    </tr>
    <tr>
      <td></td>
      <td>Kárášjohka - Karasjok</td>
      <td>2021</td>
    </tr>
    <tr>
      <td></td>
      <td>Lebesby</td>
      <td>2022</td>
    </tr>
    <tr>
      <td></td>
      <td>Gamvik</td>
      <td>2023</td>
    </tr>
    <tr>
      <td></td>
      <td>Berlevåg</td>
      <td>2024</td>
    </tr>
    <tr>
      <td></td>
      <td>Deatnu - Tana</td>
      <td>2025</td>
    </tr>
    <tr>
      <td></td>
      <td>Unjárga - Nesseby</td>
      <td>2027</td>
    </tr>
    <tr>
      <td></td>
      <td>Båtsfjord</td>
      <td>2028</td>
    </tr>
    <tr>
      <td></td>
      <td>Sør-Varanger</td>
      <td>2030</td>
    </tr>
    <tr>
      <td></td>
      <td>Spitsbergen</td>
      <td>2111</td>
    </tr>
    <tr>
      <td></td>
      <td>Bjørnøya</td>
      <td>2121</td>
    </tr>
    <tr>
      <td></td>
      <td>Hopen</td>
      <td>2131</td>
    </tr>
    <tr>
      <td></td>
      <td>Jan Mayen</td>
      <td>2211</td>
    </tr>
    <tr>
      <td></td>
      <td>Sokkelen sør for 62 grader Nord</td>
      <td>2311</td>
    </tr>
    <tr>
      <td></td>
      <td>Sokkelen nord for 62 grader Nord</td>
      <td>2321</td>
    </tr>
  </tbody>
</table>
