# LINET Nursing Time Calculator

Interaktivní studentský prototyp pro odhad potenciálně uvolněného ošetřovatelského času.

## Funkce

Vlastní parametry oddělení, denní a roční čas, modelová hodnota času, citlivost scénářů, CSV export a tisk do PDF. Responzivní české rozhraní bez závislostí a bez odesílání dat.

## Spuštění

Otevřete `index.html` v prohlížeči. Instalace ani build nejsou potřeba.

## Metodika

`hodiny za den = lůžka × obsazenost × podíl relevantních pacientů × úkony za den × ušetřené osobominuty na úkon / 60`

Podíly se dosazují od 0 do 1. Výchozí hodnoty jsou ilustrační předpoklady. Ocenění času není automatická úspora výdajů a kalkulačka nepočítá ROI.

Inspirace: [LINET Hospital Operations Efficiency](https://www.linet.com/en-US/products/beds-stretchers/intensive-care/multicare-x/hospital-operations-efficiency-mcx).

Neoficiální studentský projekt. Nejde o schválený nástroj LINETu ani klinické doporučení.
