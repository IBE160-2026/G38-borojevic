---
title: "Felleklar — Produktbrief"
status: final
created: 2026-09-08
updated: 2026-09-08
---

# Produktbrief: Felleklar

## Sammendrag

**Felleklar** er en interaktiv webapplikasjon som lærer en person hvordan man feller et tre med motorsag på en trygg måte, tester at vedkommende har forstått det, og som deretter blir med videre som en KI-assistent når personen skal gjøre det i virkeligheten. Applikasjonen har to sammenkoblede deler: et **lær-og-bevis-kurs** — illustrert, trinnvis opplæring som dekker hele felleprosessen, etterfulgt av en quiz som må bestås — og, låst opp ved bestått quiz, en **felthjelper for planlegging før kutt**, der brukeren fotograferer situasjonen sin, beskriver hva de er usikre på, og en KI går gjennom risikoene sammen med dem før de gjør kuttet.

Problemet applikasjonen løser er et reelt hull i Norge. Alle som bruker motorsag kommersielt må ha dokumentert sikkerhetsopplæring (Arbeidstilsynets *Forskrift om utførelse av arbeid*, 2013), men **privatpersoner som feller trær på egen eiendom har ikke noe slikt krav** — og det er nettopp denne gruppen som oftest blir skadet: grunneiere som tar ned noen få trær i året, folk som nettopp har kjøpt sag, og folk som skal ta et kurs og vil ha et forsprang. Formelle kurs går over to dager, foregår fysisk, og har plass til 5–6 personer. Felleklar erstatter dem ikke og hevder ikke å gjøre det. Det er en **oppfriskning og en forberedelse** — gratis, alltid tilgjengelig, og ærlig om sine egne begrensninger — som hever en persons grunnleggende forståelse før de i det hele tatt drar i startsnora, og som gir dem en ekstra vurdering når de står foran treet.

Felleklar bygges som gruppeprosjektet i **IBE160 Programmering med KI** (Høgskolen i Molde, høsten 2026). KI-en er ikke et påheng: den forklarer *hvorfor* hver sikkerhetsregel finnes, svarer på brukerens oppfølgingsspørsmål i kurset, og driver den fotobaserte felthjelperen.

## Problemet

- **Hullet for privat bruk.** Ingen opplæring er lovpålagt for å felle trær på egen grunn i Norge. Grunneiere spør i økende grad etter dokumentert kompetanse, men det finnes ikke noe lettvint å henvise folk til mellom «se en YouTube-video» og «book et todagerskurs».
- **Friksjon ved oppfriskning.** Folk som ble opplært for år siden, eller som bare gjør dette av og til, glemmer detaljene som betyr noe — fluktvei, bredde på brytekanten, når man skal bruke kile, hvordan man leser hellingen. Det finnes ingen rask, strukturert måte å sjekke seg selv på før en jobb.
- **Nervøsitet før kurs.** Folk som har meldt seg på motorsagkurs møter ofte opp uten noen mental modell i det hele tatt, noe som sinker hele gruppa. De vil komme allerede med forståelse for begrepene og rekkefølgen.
- **Kostnaden ved å gjøre feil.** Ulykker ved motorsagfelling er alvorlige: kast, oppsplitting av stammen («barberstol»), å bli truffet av stammen eller av et fastkjørt tre, kutt i beina. Dette kan nesten alltid spores tilbake til et hoppet steg eller en feiltolket situasjon — akkurat den typen ting en sjekkliste og en ekstra vurdering ville ha fanget opp.

I dag klarer folk seg med spredte YouTube-videoer, bruksanvisningen fra sagprodusenten, forum, og det å spørre en mer erfaren venn. Ingenting av det er strukturert, ingenting bekrefter at du faktisk forsto, og ingenting er der sammen med deg ved treet.

## Løsningen

**Del 1 — Lær-og-bevis-kurs.** En veiledet, illustrert gjennomgang av hele felleprosessen: personlig verneutstyr og kontroll før bruk; trygg oppstart av sagen; vurdering av treet (art, helling, råte, vind, hindringer); planlegging av felleretning og rydding av fluktvei; styrekuttet (forkuttet); brytekanten; bakkuttet; bruk av kiler; og håndtering av de vanlige dårlige utfallene (fastkjøring, oppsplitting, fastklemt sverd). Hvert steg bæres av et **enkelt visuelt element** — en håndtegnet skisse eller et stillbilde som viser den ene tingen som betyr noe, f.eks. den tryggeste måten å holde sagen på ved oppstart. Ved siden av innholdet svarer en **KI-veileder** på «hvorfor gjøres det slik?» og på alle oppfølgingsspørsmål brukeren stiller. Delen avsluttes med en **quiz** som må bestås for å gå videre.

**Del 2 — Felthjelper for planlegging før kutt.** Låses opp når quizen er bestått. Applikasjonen åpner med **blokkerende sikkerhetsadvarsler som brukeren må bekrefte** — særlig *«SLÅ AV MOTORSAGEN FØR DU BRUKER DETTE»* og *«Dette er ikke pålitelig støtte — jeg er en maskin. Alt du gjør skjer på eget ansvar.»* Brukeren legger så til inntil fem bilder av treet og omgivelsene, beskriver planen sin eller tvilen sin med egne ord, og KI-en svarer: den peker på risikoer den kan se, stiller oppklarende spørsmål (Hvor er fluktveien din? Hvilken vei heller det? Hva er bak det?), og gjentar planen tilbake. Det rammes hele veien inn som en **planleggingssjekk gjort på trygg avstand før kutt**, aldri som direkte veiledning under kuttet, og det forteller aldri brukeren at de er «klarert» til å fortsette.

## Hva som gjør dette annerledes

- **Det lukker sløyfa.** Lær → bevis at du forsto → få hjelp i det virkelige øyeblikket. Videoer og bruksanvisninger gjør bare det første steget, og svakt.
- **KI-en er en veileder og en ekstra vurdering, ikke en foreleser.** Den forklarer resonnementet og forholder seg til brukerens konkrete situasjon og bilde — noe statisk innhold ikke kan.
- **Ærlig om sine begrensninger.** Felleklars posisjonering *er* sikkerhetsfunksjonen: den kanaliserer alltid seriøse brukere mot formell opplæring og gir seg aldri ut for å sertifisere noen. Den ærligheten er også det som gjør produktet forsvarlig.
- **Riktig dimensjonert produksjon.** Bevisst enkle visuelle elementer (skisser, bilder) betyr at innholdet faktisk kan bli ferdigstilt av et lite team i løpet av et semester, og forblir billig å rette opp og utvide.
- Det hevdes ingen urettferdig teknisk fordel. Fordelen ligger i kombinasjonen og innrammingen, godt utført.

## Hvem dette er for

Hvem som helst som er **18 år eller eldre** i en av tre situasjoner:

1. **Den kommende selv-felleren** — eier eller har tilgang til en sag og vurderer å ta ned et tre selv. Vil vite om de har tatt seg vann over hodet, og hvordan de unngår å bli skadet. Suksess: de føler seg enten forberedt på et lite, greit tre, eller de innser at akkurat dette treet trenger en fagperson.
2. **Den rustne brukeren** — ble opplært eller har gjort det før, men er usikker på én bestemt ting i dag. Vil ha en rask, strukturert oppfriskning og en fornuftssjekk. Suksess: de bekrefter rekkefølgen på nytt og fanger opp det de var i ferd med å gjøre feil.
3. **Kursdeltakeren som forbereder seg** — er påmeldt et motorsag-/skogbrukskurs og vil komme med en mental modell på plass. Suksess: de møter opp allerede med kjennskap til begrepene og stegene, og får mer ut av den praktiske opplæringen.

**Sekundært:** en kursinstruktør kan bruke Felleklars kurs + quiz som en oppgave før oppmøte eller som del av en teorivurdering.

## Suksesskriterier

- **Innholdet er komplett:** kurset dekker hele felleprosessen fra ende til ende, hvert steg med et visuelt element, gjennomgått mot vanlig norsk/skandinavisk praksis.
- **Sløyfa fungerer:** i uformell testing kan de fleste førstegangsbrukere fullføre kurset, bestå quizen, og gjennomføre en felthjelper-økt på egne bilder uten hjelp eller forvirring.
- **Quizen skiller:** folk som leser innholdet består (beståttgrense ~80 %, nye forsøk tillatt); folk som hopper over det gjør det stort sett ikke.
- **KI-en er nyttig og trygg:** ved gjennomgang av eksempeløkter fra felthjelperen er rådene i tråd med kursinnholdet, den spør om fluktvei og helling når de mangler, og den gir aldri en «du er klarert til å kutte»-dom.
- **Leveranse for emnet:** oppfyller kravene i IBE160 — fungerende applikasjon pluss dokumentasjon av hvordan KI ble brukt i utvikling, testing og kvalitetssikring.

## Omfang

**Med (første versjon):**
- Webapplikasjon, responsiv slik at felthjelperen er brukbar på mobil.
- Kursinnhold som dekker hele felleprosessen, hvert steg med én skisse eller ett bilde.
- KI-veileder i kurset: svarer på «hvorfor» og på fritekst-oppfølgingsspørsmål.
- Quiz med beståttgrense (~80 %) og nye forsøk; bestått låser opp felthjelperen.
- Felthjelper: bekreft-for-å-fortsette-advarsler, opplasting av inntil 5 bilder, fritekstbeskrivelse, KI-svar med risikopåpekninger og oppklarende spørsmål.
- Applikasjonsinnhold på norsk.
- Ingen brukerkontoer; fremdrift lagres lokalt i nettleseren.

**Uten (uttrykkelig, foreløpig):**
- Enhver påstand om sertifisering, juridisk kompetanse, eller «du er klar / klarert til å kutte».
- Direkte veiledning mens sagen går eller kuttet pågår.
- Sanntidsvideo, 3D-scener, eller animerte sekvenser (kun stillbilder).
- Kvisting, kapping, og bearbeiding etter at treet er nede (kun felling).
- Profesjonelle teknikker / arboristteknikker: rigging, klatring, seksjonsvis nedtaking, store eller svekkede trær.
- Brukerkontoer, synkronisering på tvers av enheter, flerspråklighet, offline-modus, betaling.

## Visjon

Hvis det fungerer, blir Felleklar det folk henvises til før de tar i en motorsag for første gang — den gratis, norskspråklige forberedelsen en grunneier sender til en nabo, og en oppvarming som kurstilbydere anbefaler for å redusere friksjon på dag én. Felthjelperen vokser til en genuint betrodd sjekkliste før kutt som har snakket tusenvis av mennesker bort fra en dårlig felling og mot ordentlig opplæring. Den forblir gratis, forblir ærlig om at den er en maskin, og forteller aldri én eneste gang noen at de er klarert til å kutte.
