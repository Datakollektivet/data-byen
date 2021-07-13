# Data Byen
Den korte pitch er at se hvor mange data der kan samles for en by, eller rettere, et sogn. Hvorfor et sogn? Fordi det synes at være en passende enhed for at samle data med relation til et lokalområde. Niveauet over i det fleste danske databaser er kommunen, hvilket sjældent er passende fra et lokalt perspektiv.

Jeg ved ikke endnu hvordan jeg vil vise de her data, men nu starter vi lige med at indsamle data :)

## Datakilder

### Danmarks statistik

Her hedder sognet 8249 Hjortshøj (Aarhus Kommune)

Se script!

- [Gennemsnitsalder](https://www.statistikbanken.dk/KMGALDER)
- [Folketal og herkomst](https://www.statistikbanken.dk/KM1)
- [Befolkningens udvikling](https://www.statistikbanken.dk/KMSTA003)
- [Levendefødte og døde](https://www.statistikbanken.dk/KM3)
- [Ind- og udmeldelser af folkekirken](https://www.statistikbanken.dk/KM2)
- [Kirkelige handlinger](https://www.statistikbanken.dk/KM4)
- [Udannelsesniveau](https://www.statistikbanken.dk/10139)
- [socioøkonomisk status](https://www.statistikbanken.dk/KMSTA005)
- [Pendling](https://www.statistikbanken.dk/KMSTA009)
- [Kirkelige handlinger efter sogn](https://www.statistikbanken.dk/KM4)

### Åbne data
- [Socioøkonomiske data](https://www.opendata.dk/city-of-aarhus/sociooekonomiaarhus2021#resource-4a2e898c-180d-49ea-b6f7-d5e8bb9bb19c)
- [DMI vejrdata](https://www.dmi.dk/frie-data/)
- [Rejseplanen](https://help.rejseplanen.dk/hc/da/articles/214174465-Rejseplanens-API)
- [Besøgende bibliotek 5min](https://www.opendata.dk/city-of-aarhus/besogstal-og-abningstider-for-aarhus-kommunes-biblioteker)
- [Blipdata](https://www.opendata.dk/city-of-aarhus/realtids-trafikdata)
- [Aarhus bolig](https://www.opendata.dk/city-of-aarhus/aarhusbolig)
- [Trafiktal](https://www.aarhus.dk/om-kommunen/aarhus-i-tal/trafik-og-infrastruktur/)
- [Børn i dagsinstitution](https://www.opendata.dk/city-of-aarhus/born-i-dagtilbud)
- 

### Vandprøver
[Fra Hjortshøj Vandværk via Geus](http://data.geus.dk/JupiterWWW/anlaeg.jsp?anlaegid=80606)

### Grundskole

#### Hvor kommer data fra?
Børne- og Undervisningsministeriet vedligeholder deres site med uddannelsesstatistik. De specifikke data kommer fra deres [skoletal](https://uddannelsesstatistik.dk/Pages/Reports/1834.aspx) vist som et indlejret Excel ark.

Uddannelsstatistikken har også tal omkring daginstitutioner og gymnasier, men de synes enten ikke at kunne tilgås systematisk og/eller kobles til lokalitet.

#### Hvad indeholder datasættet?

- Institution (navn)
- Skoleår
- Karaktergennemsnit
- Socioøkonomisk reference: 
    - Forskel
    - Significant forskel
- Andel med højest trivsel
- Samlet elevfraværd
- Elevtal
- Klassekvotient
- Kompetencedækning
- Overgang til ungdsomudannelse fra 9. og 10. klassetrin efter 15 måneder

Der er ikke komplette data for alle institutione, fx er det ikke alle der har trivsel eller elevfraværd rapporteret. Se [Børne- og Undervisningsministeret egen beskrivelse af data](https://uddannelsesstatistik.dk/Documents/grundskole/Om%20tallene%20-%20Skoletal.pdf)

#### Hvordan henter jeg disse data?
I det indlejrede excel ark med [skoletal](https://uddannelsesstatistik.dk/Pages/Reports/1834.aspx) er det muligt at downloaded excelarket som .xlxs fil.

#### Hvilke licens er der på disse data?
Der synes ikke at være en licens tilkøblet statistikken. Derfor skal vi antage at de ikke er åbne data!
