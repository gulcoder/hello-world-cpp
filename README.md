# <span style="color:blue">Hello World C++ Project</span>

## <span style="color:green">Beskrivning</span>
Det här är ett enkelt **Hello World-program** skrivet i **C++**. Programmet är en grundläggande introduktion till hur man sätter upp ett C++-projekt med **CMake** och **Make** för att bygga och köra programmet. Projektet innehåller en grundläggande mappstruktur som kan användas som en mall för framtida C++-projekt.

## <span style="color:green">Innehåll</span>
- **src/** - Innehåller källkoden för projektet, inklusive `main.cpp`.
- **include/** - Här kan du lägga till header-filer (om det behövs i framtiden).
- **tests/** - Här kan du lägga till enhetstester (om du planerar att skapa tester).
- **lib/** - Här kan du lägga till externa bibliotek (om du använder några).
- **CMakeLists.txt** - CMake-konfigurationsfilen som styr hur projektet byggs.

## <span style="color:green">Komma igång</span>

### <span style="color:orange">Förutsättningar</span>
Innan du börjar behöver du installera följande verktyg:

- **CMake** – För att konfigurera projektet.
- **Make** – För att bygga projektet.
- **En C++-kompilator** (t.ex. GCC) – För att kompilera koden.

### <span style="color:orange">Installationssteg</span>

Följ dessa steg för att komma igång med projektet:

#### 1.
 **Klona repositoryt**

Klonar projektet till din lokala dator:
```bash
git clone https://github.com/<your-username>/<your-repository>.git
cd <your-repository>

```
**Lägg till alla filer till staging area**
```bash
git add .

```

**Commit:a ändringar**
```bash
git commit -m "Initial commit"

```

**Push till remote repository**
```bash
git push -u origin main

```
#### 2. **Skapa byggkatalogen och kör CMake**

Skapa en ny katalog för byggfiler och kör CMake:

```bash
mkdir build
cd build
cmake ..

```

#### 3. **Bygg projektet**

Bygg projektet med make:

```bash
make

```

#### 4. **Kör programmet**

Kör ditt Hello-World program:

```bash
./bin/hello

```
Du bör se följande utmatning:

```bash
Hello,World!

```
