# DataViz-StudentsInCroatia

Project for Data Visualization

Map of Croatia, graphs for each county with percentage of students in population.

Prikazan je trend porasta studenata u udjelu stanovništva po
županijama. Statistički podaci broja studenata i broja stanovnika objedinjeni su te se kroz
linijske i stupčaste grafove prikazuje postotak broja studenata u društvu prema posljednja tri
popisa stanovništva.
Početna projekcija Republike Hrvatske nudi mogućnost odabira županije za koju se na klik
iscrtavaju dva grafa, linijski i stupčasti, sa podacima prema kojima se može vidjeti je li se broj
studenata u populaciji smanjivao ili rastao. Samo prelaskom preko županije ispod projekcije se
ispisuje njeno ime.
Ispod projekcije karte nalaze se tri gumba s kojima se može odabrati određeni popis (2001.,
2011., 2021.) te se odabirom popisa projekcija karte Republike Hrvatske boja, odnosno županije
se sjenčaju prema postotku studenata u njima. Domena prema kojoj se vrši sjenčanje je ista kao
i domena na grafovima kako bi izražene boje bile jasnije. Za ostvarenje opisanog zadatka korišteni su jezici HTML i CSS te JavaScript skriptni jezik za
bibliotekom D3. HTML i CSS korišteni su za sastavljanje sadržaja i određivanje njegovog
položaja i izgleda, dok JavaScript služi za dinamičnost. Biblioteka D3 (dana driven documents)
namjenjena je za vizualizacije podataka te nudi razne mogućnosti za dinamičko ponašanje i
animiranje objekata. U projektu je korištena d3 v3 verzija.
Podaci za izradu projekcije i statistički podaci o broju stanovnika i studenata prikazani su u json
formatu te su u istom formatu i uvezeni u projekt te se njima pune grafovi.
Programski kod pokreće se uz Web server za Chrome.
