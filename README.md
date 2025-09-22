# Dårlig Sikt

Dårlig sikt er en værapplikasjon utvilket i et emnet ved UiO i samarbeid med MET (Metrologisk Institutt). Jeg, sammen med 5 andre, utviklet appen i henhold til casen "Case 3. Værvarsel for svaksynte" (https://in2000.met.no/2023/3-svaksynte). Vi jobbet smidig etter beste evne (scrum + kanban) gjennom et semester. Vi valgte denne casen fordi vi ville lære mer om, og ha litt mer praktisk utvikling, med fokus på universell utforming. 

Dårlig Sikt er utvilket for Android i Kotlin. Vi brukte, blant annet, MVVM-arkitektur og en lokal database for lagring av favoritter og innstillinger.

## Innholdsfortegnelse

- [Universell utfomring](#univsersell-utforming)
  - [1. Kontrast](#1-kontrast)
  - [2. Kartlegging av WCAG 2.1 krav](#2-kartlegging-av-wcag-21-krav)
  - [3. Universell utformet](#3-universell-utformet)
- [Overblikk over funksjonalitet](#overblikk-over-funksjonalitet)
  - [1. Hjermskjerm](#1-hjermskjerm)
  - [2. Korttidsvarsel](#2-korttidsvarsel)
  - [3. Langtidsvarsel](#3-langtidsvarsel)
  - [4. Søk](#4-søk)
  - [5. Instillinger](#5-instillinger)
  - [6. Favoritter](#6-favoritter)
 
<div align="center">
  <img src="bilder/logo.png" alt="logo" width="500">
</div>

## Univsersell utforming

Universell utforming har vært et hovedfokus gjennom hele utviklingen. Den har bestått i hovedsak av følgende deler:

### 1. Kontrast

Vi bruke en kontrastskjekker til å tilpasse fargene til WCAG 2.1 kravene.

<div align="center">
  <img src="bilder/kontrastsjekker.png" alt="kontrastsjekker" width="500">
</div>

Vi endte opp med følgende fargetema:

<div align="center">
  <img src="bilder/våre-farger-og-yr-sine-farger.png" alt="våre farger og yr sine farger" width="400">
</div>

Og lagde i den forbindelse helt egne ikoner:

<div align="center">
  <img src="bilder/ikoner.png" alt="ikoner" width="500">
</div>

### 2. Kartlegging av WCAG 2.1 krav

Vi gikk systematisk gjennom alle WCAG 2.1 kravene og prøvde etter beste evne å innføre kravet.

<div align="center">
  <img src="bilder/uu-oversikt-de1.png" alt="universell utforming oversikt de1" width="400">
  <img src="bilder/uu-oversikt-de2.png" alt="universell utforming oversikt de2" width="400">
</div>

### 3. Universell utformet 

Vi endte opp med følgende endringer etter at vi tok hensyn til universell utforming og WCAG 2.1 kravene.

<div align="center">
  <img src="bilder/universell-utforming-for-etter.png" alt="universell utforming før og etter" width="500">
</div>

## Overblikk over funksjonalitet

Dårlig sikt er full fungerende med Android sin talkback funksjon og har følgende funksjonaliteter. 

### 1. Hjermskjerm

Brukeren kan velge om å gi samtykke til posisjonen sin eller ikke. Stedsnavn vil enten være "Aker brygger" eller nåværende posisjon.

<div align="center">
  <img src="bilder/hjemskjerm.png" alt="hjemskjerm" width="300">
</div>

### 2. Korttidsvarsel

Her vil brukeren få et korttidsværvarsel. 

<div align="center">
  <img src="bilder/korttidsvarsel.png" alt="korttidsvarsel" width="300">
</div>

### 3. Langtidsvarsel

Her vil brukeren få et langtidsværvarsel. 

<div align="center">
  <img src="bilder/langtidsvarsel.png" alt="langtidsvarsel" width="300">
</div>

### 4. Søk

Her vil brukeren få muligheten til å søke etter en by eller sted, der man ønsker å se været fra. 

<div align="center">
  <img src="bilder/sokside.png" alt="søk side" width="300">
</div>

### 5. Instillinger

Her vil brukeren få muligheten til å velge mellom 1. celsius eller fahrenheit og 2. skriftstørrelse. 

<div align="center">
  <img src="bilder/instillinger.png" alt="instillinger" width="300">
</div>

I forbindelse med at en bruker kan ha ulik tekststørrelse har vi lagt inn tekst overflow. Hvis teksten blir for stor vil teksten bryte og endre layouten. Applikasjonen tilpasser seg dermed skjermstørrelse.

<div align="center">
  <img src="bilder/text-overflow.png" alt="tekst overflow" width="550">
</div>

### 6. Favoritter

Her vil brukeren få muligheten til å velge ulike favoritter. 

<div align="center">
  <img src="bilder/favoritter.png" alt="favoritter" width="700">
</div>
