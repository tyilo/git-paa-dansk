# Git på dansk

## Introduktion

Det danske omgangssprog for begreberne og kommandoerne i versionskontrolsystemet `git` er cirkussprog.
Man anvender enkle fordanskninger af de engelske begreber, som f x _"Kan du pushe branchen?"_ eller _"Jeg puller!"_.
Udtalen foregår typisk med anvendelse af amerikansk engelsk med stærk østdansk accent.
Sig derfor /bwæːnɕ/, ikke /bɹɑːntʃ/.

Dette dokument forsøger at etablere en ren dansk fagjargon, som kan anvendes ikke mindst i skriftlig fremstilling.
Det er underforstået, at kommunikation i kampens hede blandt udviklere bedst foregår på cirkussprog.
Man skal desuden være opmærksom på, at man ved anvendelse af dansk terminologi kan udsætte sig for et betydeligt tab af social status bland fagfæller. 

## Forslag


| Udsagnsord  | Nuværende brug | Forslag       |
|-------------|----------------|---------------|
| pull        | pulle          | hale          |
| push        | pushe          | puffe         |
| fetch       | fetche         | hente         |
| branch      | branche        | forgrene         |
| commit      | committe       | fastlægge     |
| rebase      | rebase         | genbasere      |
| merge       | merge          | flette        |
| squash      | squashe        | kvase          |
| stash       | stashe         | gemme         |
| tag         | tagge          | opmærke       |
| cherry-pick | cherry-picke   | håndplukke    |
| amend       | amende         | tilrette      |
| blame       | blame          | klandre       |

| Navneord     | Nuværende brug | Forslag      |
|--------------|----------------|--------------|
| repository   | repository     | repositorium |
| branch       | branch         | gren         |
| commit       | commit         | fastlæggelse |
| pull request | pull request   | haleanmodning|
| stash        | stash          | gemme        |
| tag          | tag            | mærke     |

## Eksempler

    - Gider I hale fra den gren, jeg lige har genbaseret og puffet til GitHub?

    - Jeg har lige skudt en gren og har fastlagt ændringerne fra mit gemme der.

    - Send lige en haleanmodning, når du er færdig med fletningen!

    - Det håndplukker vi da bare fra udviklergrenen.
    
    - Hov, jeg tvangspuffede vistnok til hovedgrenen!

    - Husk at kvase dine fastlæggelser, inden du fletter.


# Ordliste

## fastlægge

`BØJNING` -r, …lagde, …lagt  
`GRAMMATIK` verbum, *nogen* fastlægger *nogle ændringer*  eller *nogen* lægger *nogle ændringer* fast.  
`ENGELSK` *commit*  (vb.)  
`OPRINDELSE`  alm. brugt som »at bestemme, beslutte noget«  


## fastlæggelse

`BØJNING` -n, -r, -erne  
`ENGELSK` *commit* (sb.)  
`OPRINDELSE`  konstrukeret, substantivering af fastlæggelse; i alm. brug betegnes »det at fastlægge noget«, altså handlingen i stedet for resultatet.  

## fjern-

I sammensætninger.

`ENGELSK` *remote* adj.

`SAMMENSÆTNINGER` fjernrepos, fjerngren

## fjernen

Et fjernrepos.

`ENGELSK` *remote* sb.  
`OPRINDELSE`  konstrueret   
`ALTERNATIV`  fjerneren    

`SAMMENSÆTNINGER` fjernrepos, fjerngren

## flette (ind)

optage ændringer, fx fra en anden gren, i den aktuelle gren.

`BØJNING` -r, -de, -et  
`GRAMMATIK` verbum, *nogen* fletter, eller *nogen* indfletter *nogle ændringer* eller *nogen* indfletter *nogle ændringer*  
`ENGELSK` *merge*    
`OPRINDELSE`  alm. i betydningen »bevirke, at noget indgår i en samlet helhed«, helt konrket brugt i biltrafik (*fletteregel*).  
`ALTERNATIVER` sammenflette, når det ikke er af betydning, hvilken gren, der flettes ind.  
 
>Husk lige at flette fra Lisbet.

>Vi regner med at flette udviklergrenen ind i mesteren om to dage.

`SAMMENSÆTNINGER` flettekonflikt

## forgrene

dele en udviklingslinje i to ved at anlægge en ny gren.

`BØJNING` -r, -de, -et  
`UDTALE` [fʌˈgʁεˀnə]  
`GRAMMATIK` verbum, *nogen* forgrener *en gren*, et repo *forgrenes* eller *forgrener sig*   
`ENGELSK` *branch* vb.  
`OPRINDELSE`  alm. i betydningen »dele sig i mindre grene«, bruges dog kun i passive vendinger  

`SAMMENSÆTNINGER` forgreningsstrategi


## gemme¹


`BØJNING` -r, -de, -t  
`UDTALE` [ˈhɑlə]  
`GRAMMATIK` verbum, *nogen* gemner *sine ændringer*    
`ENGELSK` *stash* vb.  

>Hvis man står med en beskidt arbejdsmappe er det hurtigste er ofte bare at gemme sine ændringer i »rod« eller whatever.

## gemme²

`BØJNING` -r, -de, -t    
`UDTALE` [ˈhɑlə]   
`GRAMMATIK` sb.  
`ENGELSK` *stash* sb.  
`ALTERNATIV` gemmested  

## gren

`BØJNING` -e, -ene  
`GRAMMATIK` verbum, *nogen* gafler *noget*  
`ENGELSK` *branch* sb.  

>Er vi på samme gren?

`SAMMENSÆTNINGER` mestergren, udviklingsgren

## hale

`BØJNING` -r, -de, -t  
`UDTALE` [ˈhɑlə]  
`GRAMMATIK` verbum, *nogen* gafler *noget*  
`ENGELSK` *pull*  
`OPRINDELSE`  alm. i betydningen »trække langsomt og jævnt«, fra middelnedertysk *halen*, beslægtet med hole »hente hjem«  
`ALTERNATIV` trække  

> Novra. Det kunne jeg jo lige så godt have halet
> fra Simones repos.

`SAMMENSÆTNINGER` haleanmodning

# hente

`BØJNING` -r, -de, -t  
`GRAMMATIK` verbum, *nogen* henger *nogle ændringer*  
`ENGELSK` *fetch*  

>Jeg foretrækker hente og så genbasere fra fjerngrenen. 

>Følgende eksempel viser, hvordan man henter en fjerngren og opdaterer sine lokale arbejdstilstand til fjernerens indhold.

`SAMMENSÆTNINGER` haleanmodning

## håndplukke

`BØJNING` -r, -de, -t  
`GRAMMATIK` verbum, *nogen* håndplukker *nogle ændringer*   
`ENGELSK` *cherry pick*  

> Jeg håndplukker 54ae13. Men resten må du lige refaktorisere inden jeg kigger på dem.

## klandre

`BØJNING` -r, -de, -t   
`GRAMMATIK` verbum, *nogen* klandrer *nogen*   
`ENGELSK` *blame*   

## kvase

`BØJNING` -r, -de, -t    
`GRAMMATIK` vb. *nogen* kvaser *nogle ændringer*    
`ENGELSK` *squash* vb.  
`OPRINDELSE`  alm. i betydningen »trykke, mase eller træde på noget så det går i stykker«  

> Du kan lige så godt kvase hele grenen til en enkelt fastlæggelse og så genbasere. Det ser pænere ud i udviklingshistorien.


## mærke

en reference, oftest til en fastlæggelse for at beskrive et bestemt punkt i udviklingshistorien.

`BØJNING` -r, -t, -rne  
`UDTALE` [ˈmæɐ̯gə]  
`GRAMMATIK` sb.  
`ENGELSK` *tag* sb.,  
`OPRINDELSE`  alm.  


## opmærke

= mærke op

forsyne en fastlæggelse med ett mærke.

`BØJNING` -r, -de, -t   
`GRAMMATIK` verbum, *nogen* opmærker *en fastlæggelse*  
`ENGELSK` *tag* vb.  
`OPRINDELSE`  alm. i betydningen »anbringe mærker«  

>Vi opmærker med versionsnumre for hver udgave. 

## puffe

Kopier ændringer til et fjernrepos, typisk ved at udvide en eksisterene gren på fjernreposet med fastlæggelser fra en længere lokal gren.

`BØJNING` -r, -de, -t   
`UDTALE` [ˈpɔfə]  
`GRAMMATIK` verbum, *nogen* puffer *ændringer* til  *et repos*  
`ENGELSK` *push*  
`OPRINDELSE`  alm. i betydningen »give et kontrolleret eller let skub«  
`ALTERNATIV` skubbe  

>Hold på hat og briller! Jeg tvangspuffer altså lige til hovedgrenen.

>Puffet bliver afvist, hvis den fulgte gren på fjernreposet har divergeret.

`SAMMENSÆTNINGER` tvangspuf

## genbasere

gennemføre ændringerne fra en gren påny, men fra en andet udgangspunkt end det oprindelige.

`BØJNING` -r, -de, -t  
`UDTALE`  [ˈgεnˌbaˈseˀʌ]  
`GRAMMATIK` verbum, *nogen* genbaserer *noget*  
`ENGELSK` *rebase*  
`OPRINDELSE`  konstruktion, fra *basere* »danne på grundlag af«, i symmetri med *genbruge* eller *gendanne*  
`ALTERNATIVER` ombasere, rebasere  

> Jeg synes, at genbasering burde være forvalget for `git pull`.

> Det ser nydeligt ud. Hvis du genbaserer på 513ae2, så kan jeg bare spole mestergrenen frem.


## repos

`BØJNING` -et, -er, -erne  
`UDTALE` [ʁεˈpo] eller ['ʁεpo]  
`GRAMMATIK` substantiv  
`ENGELSK` *repo*, *repository*   
`OPRINDELSE`  konstrueret; homofon og homonym til det danske substantiv *repos* [ʁεˈpo] »trappeafsats«, der kommer fra fransk *repos* »hvile«.  
`ALTERNATIVER` repot (jf. *depot*), måske med udtale [ʁεˈpoˀd]; repositorium.  

> Novra. Det kunne jeg jo lige så godt have halet
> fra Simones repos.

## spore

`ENGELSK` *track* vb.

`SAMMENSÆTNINGER` sporegren, fjernsporegren

## tilrette

= rette til

`BØJNING` -r, -de, -t    
`UDTALE` [ˈtelˌʁadə]  
`GRAMMATIK` verbum, *nogen* tilrætter *en fastlæggelse*  
`ENGELSK` *amend*  
`OPRINDELSE`  alm. i betydningen »at ændre noget, til det passer«  
`ALTERNATIV` trække  

> Jeg retter lige min sidste fastlæggelse til, inden jeg puffer.


