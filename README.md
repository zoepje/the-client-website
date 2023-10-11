> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je, zoals altijd, in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# De hallen
De directie van De Hallen heeft ons gevraagt om een website te bouwenvanuit de nieuwe Stichting voor buurtinitiatieven. Het is de bedoeling om een online platform te maken waar buurtinitiatieven uit Oud-West verzameld en bekeken kunnen worden. 

## Inhoudsopgave
  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
Voor dit project heb ik de [user story](https://github.com/fdnd-agency/de-hallen/issues/1) die zegt: Als buurtbewoner van Amsterdam West wil ik een overzicht van alle buurtinitiatieven kunnen bekijken, zodat ik een indruk kan krijgen van wat er allemaal te doen is in de wijk.

**📸 Dit is hoe de website er uitziet.**

Home pagina:
<img width="1227" alt="Screenshot 2023-10-11 at 11 26 44 AM" src="https://github.com/zoepje/the-client-website/assets/144004461/fe7bcfb7-df9d-4b22-8a91-727520c48968">
<img width="1222" alt="Screenshot 2023-10-11 at 11 27 01 AM" src="https://github.com/zoepje/the-client-website/assets/144004461/c4892f07-4189-46ad-8bf4-c036296edb54">

Categorie pagina:
<img width="1227" alt="Screenshot 2023-10-11 at 11 56 02 AM" src="https://github.com/zoepje/the-client-website/assets/144004461/532b314f-72b0-4c2e-ac98-bf7aa44783c2">

Initiatief pagina:
<img width="1227" alt="Screenshot 2023-10-11 at 11 59 28 AM" src="https://github.com/zoepje/the-client-website/assets/144004461/d8ece3b4-742e-4b2d-86cc-a7eaf0cce103">
<img width="1227" alt="Screenshot 2023-10-11 at 11 59 34 AM" src="https://github.com/zoepje/the-client-website/assets/144004461/47bcb9a7-c3d8-451d-a94e-581d8b365433">

🌐 Link naar mijn live versie -  https://zoepje.github.io/the-client-website/ 

## Kenmerken
Ik heb deze website gemaakt met HTML en CSS. Voor elke pagina heb ik een ander HTML bestand aangemaakt. Ik heb gebruik gemaakt van een standaard HTML sturctuur: head en body. Per pagina ziet de body er iets anders uit. maar in het algemeen heb ik gebruik gemaakt van een header, nav, main, aside en footer. 

Ik heb één main css bestand voor alle paginas, waarin de standaard opmaak staat. En voor de initiatief pagina/categorie pagina heb ik nog extra css bestanden, waarin ik wat specefiekere elementen heb opgemaakt. Zoals bijvoorbeeld de grid van de categorie pagina.

```
/* Initiatieven */
.initiatief{
    padding: 0;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 300px)); /*Zorgt ervoor dat de grid automatisch verandert met het scherm*/
    justify-content: center;
    width: 100vw;
    list-style: none;
}


.initiatief li{
    padding: 1.5em;
    width: 300px;
    align-content: center;
}
```

Verdere uitleg over hoe ik deze website heb gebouwd kunt u [hier](https://github.com/zoepje/the-client-website/wiki/3.-Bouwen) vinden.

## Bronnen
* W3S - https://www.w3schools.com/
* MDN Web docs - https://developer.mozilla.org/en-US/

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
