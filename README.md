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
<img width="1381" 
<img width="1381" >

Home pagina:

<img width="1227" alt="Screenshot 2023-10-11 at 11 26 44 AM" src="https://github.com/zoepje/the-client-website/assets/144004461/a2d7c3c9-3a3c-418b-8e76-9c13c137071a">
<img width="1222" alt="Screenshot 2023-10-11 at 11 27 01 AM" src="https://github.com/zoepje/the-client-website/assets/144004461/8a159b5f-7121-4346-85bf-8bfcedbf2523">

Categorie pagina:
<img width="1227" alt="Screenshot 2023-10-11 at 11 56 02 AM" src="https://github.com/zoepje/the-client-website/assets/144004461/a055a698-3571-470e-96f8-03fdcae87318">

Initiatief pagina:
<img width="1227" alt="Screenshot 2023-11-03 at 10 29 36 AM" src="https://github.com/zoepje/the-client-website/assets/144004461/e485b647-108e-406f-8e94-9cbf55cc2386">
<img width="1227" alt="Screenshot 2023-11-03 at 10 29 42 AM" src="https://github.com/zoepje/the-client-website/assets/144004461/c294a435-8946-48fe-8f37-2deb2eff1905">

Contact pagina:
<img width="1227" alt="Screenshot 2023-11-3" src="https://github.com/zoepje/the-client-website/assets/144004461/a47fa06d-4a6c-4f0c-b978-4d6a207694a0">

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
