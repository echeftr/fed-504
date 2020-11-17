Opdracht : de "Superpowers" van .map .filter .reduce

Ondanks dat je wellicht zelf al favoriete array methods hebt gekozen, zijn .map .filter en .reduce de meest gebruikte array methods. Dit zijn de "superkrachten" die je later in de academy, en in je werkende leven(!) nog veel zult nodig hebben. Vandaar dat we hier in deze opdracht extra aandacht aan gaan geven.

Met array methods is het net als spierkracht: herhaling doet groeien!

Kopieer de data onderaan deze pagina in een js bestand en zet deze in een const variable genaamd superheroes
Voor elke van de onderstaande opdrachten mag je alleen gebruik maken van .map, .filter of .reduce
Pak de superheroes data en maak daarvan het volgende...

Maak een array van alle superhelden namen

Maak een array van alle "lichte" superhelden (< 190 pounds)

Maak een array met de namen van de superhelden die 200 pounds wegen

Extra: chaining ⛓️

Het mooie aan array methods is, je kunt ze chainen. Oftwel je kunt er een ketting van maken. Als je bijvoorbeeld eerst een .filter functie hebt uitgevoerd om de superhelden te filter die 200 pound wegen. Dan kun je daarna een .map functie eraan "vastplakken" die de namen van de superhelden returned. Bijvoorbeeld:

// Pseudo code (bijna echte code):
heroes.map(hero => {
return [doe iets met de hero]
}).filter(hero => {
return [doe iets met de array die zojuist al door de map functie heen is
geweest, en er dus anders uitziet dan die originele array]
}
Maak een array met alle comics waar de superhelden hun "first appearances" hebben gehad

Maak een array met alle superhelden van DC Comics. Is dat gelukt? Herhaal de bovenstaande functie dan en maak ook een array met alle superhelden van Marvel Comics.

Tel het gewicht van alle superhelden van DC Comics bij elkaar op. Let op! Conditionals to the rescue! Het gewicht dat je ziet in de movieDatabase, van welk datatype is dat? Een nummer? Of een string? Oh ja, en hebben alle superhelden wel een gewicht?

Doe hetzelfde met alle superhelden van Marvel Comics

Bonus: zoek de zwaarste superheld!

Gebruik de onderstaande array met superhelden:

[
{
"name": "Batman",
"publisher": "DC Comics",
"alter_ego": "Bruce Wayne",
"first_appearance": "Detective Comics #27",
"weight": "210"
},
{
"name": "Superman",
"publisher": "DC Comics",
"alter_ego": "Kal-El",
"first_appearance": "Action Comics #1",
"weight": "220"
},
{
"name": "Flash",
"publisher": "DC Comics",
"alter_ego": "Jay Garrick",
"first_appearance": "Flash Comics #1",
"weight": "195"
},
{
"name": "Green Lantern",
"publisher": "DC Comics",
"alter_ego": "Alan Scott",
"first_appearance": "All-American Comics #16",
"weight": "186"
},
{
"name": "Green Arrow",
"publisher": "DC Comics",
"alter_ego": "Oliver Queen",
"first_appearance": "All-American Comics #16",
"weight": "195"
},
{
"name": "Wonder Woman",
"publisher": "DC Comics",
"alter_ego": "Princess Diana",
"first_appearance": "The Incredible Hulk #180",
"weight": "165"
},
{
"name": "Blue Beetle",
"publisher": "DC Comics",
"alter_ego": "Dan Garret",
"first_appearance": "Mystery Men Comics #1",
"weight": "145"
},
{
"name": "Spider Man",
"publisher": "Marvel Comics",
"alter_ego": "Peter Parker",
"first_appearance": "Amazing Fantasy #15",
"weight": "167"
},
{
"name": "Captain America",
"publisher": "Marvel Comics",
"alter_ego": "Steve Rogers",
"first_appearance": "Captain America Comics #1",
"weight": "220"
},
{
"name": "Iron Man",
"publisher": "Marvel Comics",
"alter_ego": "Tony Stark",
"first_appearance": "Tales of Suspense #39",
"weight": "250"
},
{
"name": "Thor",
"publisher": "Marvel Comics",
"alter_ego": "Thor Odinson",
"first_appearance": "Journey into Myster #83",
"weight": "200"
},
{
"name": "Hulk",
"publisher": "Marvel Comics",
"alter_ego": "Bruce Banner",
"first_appearance": "The Incredible Hulk #1",
"weight": "1400"
},
{
"name": "Wolverine",
"publisher": "Marvel Comics",
"alter_ego": "James Howlett",
"first_appearance": "The Incredible Hulk #180",
"weight": "200"
},
{
"name": "Daredevil",
"publisher": "Marvel Comics",
"alter_ego": "Matthew Michael Murdock",
"first_appearance": "Daredevil #1",
"weight": "200"
},
{
"name": "Silver Surfer",
"publisher": "Marvel Comics",
"alter_ego": "Norrin Radd",
"first_appearance": "The Fantastic Four #48",
"weight": "unknown"
}
]
Naslagwerk
Hoe zat het ook alweer met .map?

JavaScript Array Map: https://www.youtube.com/watch?v=G3BS3sh3D8Q&t=1s

Hoe zat het ook alweer met .filter?

JavaScript Array Filter: https://www.youtube.com/watch?v=4_iT6EGkQfk

Hoe zat het ook alweer met .reduce?

JavaScript Array Reduce: https://www.youtube.com/watch?v=g1C40tDP0Bk
