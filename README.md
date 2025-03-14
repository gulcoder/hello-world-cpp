# Hello World C++ Project

## Beskrivning

Det här är ett enkelt Hello World-program skrivet i C++. Programmet är en grundläggande introduktion till hur man sätter upp ett C++-projekt med CMake och Make för att bygga och köra programmet.

Projektet innehåller också en grundläggande mappstruktur som kan användas som en mall för framtida C++-projekt.

### Innehåll

src/ - Innehåller källkoden för projektet, inklusive main.cpp.
include/ - Här kan du lägga till header-filer (om det behövs i framtiden).
tests/ - Här kan du lägga till enhetstester (om du planerar att skapa tester).
lib/ - Här kan du lägga till externa bibliotek (om du använder några).
CMakeLists.txt - CMake-konfigurationsfilen som styr hur projektet byggs.
Komma igång

Följ dessa steg för att bygga och köra projektet på din maskin.

### Förutsättningar
Innan du börjar behöver du installera följande verktyg:

CMake – För att konfigurera projektet.
Make – För att bygga projektet.
En C++-kompilator (t.ex. GCC) – För att kompilera koden.

#### Installationssteg
1. Klona repositoryt

Först klonar du repositoryt:

git clone https://github.com/<your-username>/<your-repository>.git
cd <your-repository>

2. Skapa byggkatalogen och kör CMake

Skapa en katalog för att hålla byggfilerna och kör CMake:

mkdir build
cd build
cmake ..

3. Bygg projektet

Bygg projektet med make:

make

4. Kör programmet

Efter att bygget är klart, kör programmet:

./bin/hello
Du bör se följande utmatning:

Hello, World!

