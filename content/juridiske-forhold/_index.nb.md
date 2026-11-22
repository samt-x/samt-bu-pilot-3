---
id: d6ae7205-9c7f-451c-b8d1-2d4c9c378019
title: "Juridiske forhold"
linkTitle: "Juridiske forhold"
weight: 60
lastmod: 2026-11-22T23:33:09+01:00
last_editor: Erik Hagen

---

{{< i-arbeid >}}

Hva skolene kan dele med hverandre når en elev bytter skole, når det trengs samtykke, og hvilke juridiske spørsmål en KI-løsning for elevmappa reiser. Grunnlaget er pilotens notat om samtykke. En sluttrapport om personvern og digital sikkerhet er under arbeid.

## Reglene stopper oss ikke, men verktøyene mangler

| Myte | Fakta |
|---|---|
| Vi må ha samtykke når vi skal behandle personopplysninger | Det offentlige har veldig ofte andre hjemler som lar oss behandle personopplysninger uten samtykke |
| Når vi trenger samtykke, er det på grunn av GDPR | Mange av lovene kommunene må følge, har egne krav om samtykke, for eksempel opplæringslova |

Kommunene etterlyser felles rutiner og en digital samtykkeløsning, slik at veien fra lovboka til praksis ikke blir så tung.

## Hva skolen kan dele uten samtykke

Både personvernregelverket og reglene om taushetsplikt i forvaltningen setter grenser for hva skolene kan dele. Utgangspunktet er at skolen ikke kan dele opplysninger om enkeltelever uten hjemmel.

Når en elev bytter til en annen skole på samme nivå, kan skolen dele disse opplysningene med den nye skolen uten samtykke, etter opplæringslova § 25-1 og opplæringsforskrifta § 20-3:

- tidligere gjennomført opplæring, med fagsammensetning
- karakterer som skal føres på vitnemål eller kompetansebevis
- fravær som skal føres på vitnemål eller kompetansebevis
- kartlegging av elever med rett til særskilt språkopplæring
- personopplysninger som er nødvendige for å forebygge oppførsel som i vesentlig grad går ut over skolemiljøet til medelevene eller arbeidsmiljøet til de ansatte (nytt fra 1. august 2026)

## Hva som krever samtykke

Alt annet krever samtykke fra eleven eller foreldrene. Skolen kan bare be om samtykke til å dele opplysninger som er nødvendige for å legge til rette opplæringen til eleven. Eksempler er opplysninger om lese- eller skrivevansker, sykdom eller allergier, vedtak om individuelt tilrettelagt opplæring og uttalelser fra pedagogisk-psykologisk tjeneste.

Deler skolen mer enn det er hjemmel for, krenker det elevens personvern. Det skal derfor håndteres som en risiko i personvernkonsekvensvurderingen (DPIA).

## Samtykket er ikke behandlingsgrunnlag etter GDPR

Det er viktig å skille mellom samtykke som behandlingsgrunnlag i personvernforordningen (GDPR) og samtykke etter andre regler.

GDPR artikkel 6, og for helseopplysninger og andre særlige kategorier også artikkel 9, krever et behandlingsgrunnlag for å dele opplysninger. Samtykke er bare ett av flere mulige grunnlag. Ved skolebytte er grunnlaget opplæringslova § 25-1, som er et supplerende rettsgrunnlag til artikkel 6 nr. 1 bokstav c og e og artikkel 9: det er lov å behandle personopplysninger når det er nødvendig for å oppfylle en rettslig plikt eller utføre en oppgave i allmennhetens interesse.

Skolen henter altså inn samtykke for å oppfylle vilkårene i opplæringslova og for ikke å bryte taushetsplikten, ikke som behandlingsgrunnlag etter GDPR. Disse samtykkene omfattes ikke av kravene GDPR stiller til samtykke, men må være gyldige etter alminnelig forvaltningsrett.

## Juridiske spørsmål for en KI-løsning

Det valgte sporet, en KI-modell som hjelper med å velge ut dokumenter i elevmappa (se [Valgt løsning nå](/pilotering/pilot-3/loesningsvalg/valgt-loesning-naa/)), krever en grundig juridisk utredning før det kan gå videre. Blant spørsmålene:

- **Behandlingsgrunnlag for å trene modellen:** hvilke data skal den trenes på, og hva er grunnlaget for det?
- **Behandlingsgrunnlag for å bruke modellen** på elevmappa, jf. GDPR artikkel 6 og 9. Prinsippene om dataminimering og formålsbegrensning kan tale imot, fordi det er en ryddebehandling som ikke hadde vært nødvendig hvis dokumentene var strukturert fra starten.
- **Automatiserte avgjørelser:** kan løsningen komme i konflikt med forbudet i GDPR artikkel 22, og hvor stor er effekten hvis et menneske uansett må gå gjennom alle dokumentene?
- **DPIA:** det må trolig gjøres en personvernkonsekvensvurdering, og utfallet kan bli at behandlingen ikke er lov.
- **Diskriminering:** se Likestillings- og diskrimineringsombudets veileder om innebygd diskrimineringsvern i KI.

KS Digitals jurist ser på behandlingsgrunnlaget for trening og bruk. Piloten har også spurt Skatteetaten om de har gjort vurderinger som kan gjenbrukes.

## Videre oppfølging

- avklare hvordan kravene til samtykke etter opplæringslova § 25-1 kan oppfylles i praksis, og hvilke samtykkeløsninger som kan brukes
- vurdere og dokumentere risiko knyttet til behandlingsgrunnlag og samtykke i DPIA-en
- ferdigstille sluttrapporten om personvern og digital sikkerhet ([samt-bu-pilot-3#25](https://github.com/samt-x/samt-bu-pilot-3/issues/25))

## Kilder

- [Forvaltningsloven § 13 (taushetsplikt)](https://lovdata.no/lov/1967-02-10/§13)
- [Opplæringslova § 25-1](https://lovdata.no/lov/2023-06-09-30/§25-1)
- [Likestillings- og diskrimineringsombudet: Innebygd diskrimineringsvern (PDF)](https://ldo.no/content/uploads/2024/06/Innebygd-diskrimineringsvern-2023.pdf)
