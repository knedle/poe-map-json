# poe-map-json
dataset poe maps in json

rad bych si tu udelal full dataset na (neunikatni) mapy atlasu - ignoruji ligy, ignoruji tiery

## pozadovana data

- typ layoutu
 - linear = furt rovne až k bosovi, nejde uhnout (tunels, canyon)
 - semi-linear = mapa ma dany tvar, je mozne hned ihned urcit kde najdem bosse (park, atoll)
 - open - otevrena mapa - je mozne zvolit spatny smer, 
 - maze - bludiste
- seznam drahych divination card
- pocet bosu (jmena take, ale jsou podruzna)
- umisteni bose
- poznamky

mozno rozsirit o ruzne poznamky

cilem by bylo mit zdroj pro nejakou stranku, kde si muzu vyfiltrovat mapy za pouziti filtrace s vice parametry


```
      "boss": [    
      ],
      "bossCount": "",
      "bossLocation": "",
      "bossArena": "",
      "layout": "",
      "divinationCard": [
      ]
```


poznamky

pro sortovani pouzit 
https://www.coderstool.com/json-sort
kdy jsem si vzal jenom [] + sort critera: key value; key name: name; sort order: a-z
