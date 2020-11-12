js_env_for_training:
Jest to gotowo skonfigurowane środowisko do pisania zadań z "Prework Javascript" 
Dla studentów Akademii Localhost. Poniżej znajduję się krótka instrukcja jak rozpocząć pracę:

Step 1 - Musisz najpierw zainstalować 
1. Zainstalować środowisko uruchomieniowe node.js na swoim komputerze
2. Zainstalować menagera pakietów - npm 

Resztę potrzebnych Ci paczek będzie zawierał plik package.json
Który zainstaluje zależności po wpisaniu komendy w termianlu "npm install"


Step 2 - Tworzenie struktury wykonywanych zadań
Struktura jest modularna, to znaczy tyle, 
Że dzielimy logike na kilka plików aby łatwiej było nam zarządzać zadaniem i nie pogubić się w kodzie.

Struktura zadania:
// app.js - tutaj jest tworzona logika działania z taskiem
// index.js - tutaj jest tworzona logika taska
// example.js - tutaj jest tworzona pomocnicza logika do realizacji taska
// odpal środowisko poprzez terminal:
npm start
// strukturę taska możesz dowolnie zmieniać oraz dodawać kolejne foldery jako taski, wywołując je w app.js
