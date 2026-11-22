---
title: "Valgt løsning nå"
linkTitle: "Valgt løsning nå"
weight: 30

---

{{< i-arbeid >}}

Piloten har valgt å utforske om en KI-modell kan hjelpe skolepersonalet med å velge ut hvilke dokumenter i elevmappa som skal sendes til den nye skolen. Det er ikke bygget noen løsning ennå. Innenfor pilotens tidsramme, ut november 2026, er arbeidet en juridisk utredning og kontakt med skolemiljøer. Det tekniske arbeidet forutsetter en videreføring, se [Veikart](/pilotering/pilot-3/loesningsvalg/veikart/).

## Hva piloten vil oppnå

- bedre kvalitet på utvalget av opplysninger som sendes, uten dokumenter som ikke er relevante
- beslutningsstøtte og mindre arbeid for personalet på skolen eleven flytter fra
- et mer oversiktlig utvalg for personalet på skolen eleven flytter til
- at eleven får en god overgang, og at behov for tilpasset opplæring blir fanget opp og fulgt opp raskt

Utover selve casen kan en kategorisering av dokumentene i elevmappa gi grunnlag for en standard, som vil være et løft for sammenhengende tjenester i utdanningssektoren. En risiko- og personvernvurdering (ROS og DPIA) for en slik løsning kan også ha nytte utover denne casen.

## Hvordan

- **Klassisk maskinlæring, ikke en stor språkmodell (LLM),** vurderes som best egnet. Modellen skal grovsortere og kategorisere dokumentene, ikke ta beslutninger.
- **Modellen må kjøres lokalt.** Dokumentene er sensitive personopplysninger om barn og kan ikke sendes til en ekstern tjeneste.
- **Skolepersonale med kunnskap om innholdet i elevmappene** må være med. De definerer kategoriene modellen trenes på, og kvalitetssikrer treningen.
- **Et menneske tar alltid den endelige avgjørelsen** om hva som sendes.

## Treningsdata

| Ekte elevmapper | Syntetiske data |
|---|---|
| Sensitive personopplysninger | Kan lages med KI, kombinert med domenekunnskap om innhold og kategorier |
| Dokumentene kan også nevne andre elever, for eksempel i mobbesaker, noen ganger bare med initialer. Det må tas hensyn til ved anonymisering og i den juridiske vurderingen | Krever en person med domenekunnskap |
| På små steder kan anonymiserte dokumenter likevel kunne knyttes til en person | Modellen kan trenes i KS Digitals sandkasse for KI-løsninger |

## Innspill fra workshop med KI-Norge

Piloten la fram casen på en workshop hos KI-Norge 7. oktober 2026. Viktige innspill:

- Begynn med det enkleste som fortsatt er nyttig, for eksempel antall dokumenter i elevmappa, historikk fra tidligere skolebytter, og en grovsortering i «krever samtykke» og «krever ikke samtykke». Forfin modellen etter hvert.
- Kategoriene kan lages på forhånd eller foreslås av modellen selv, gjerne i en vekselvis prosess. En kunnskapsgraf over kategoriene kan bygges opp underveis.
- Forsendelsen kan få med en beskrivelse av hvilke kriterier modellen har brukt for utvalget.
- Modellen må kjenne regelverket som avgjør hva som kan sendes.
- Datakvaliteten må vurderes. Hva skjer hvis en hendelse er registrert på feil elev?
- Det er uavklart om skolen eller skoleeieren eier dataene, og om foreldrene får se de faktiske dokumentene de blir bedt om å samtykke til at sendes.
