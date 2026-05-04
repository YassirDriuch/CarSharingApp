# car-sharing

Een console-applicatie voor een autodeel systeem. Managers kunnen bedrijven en autos registreren. Klanten kunnen een beschikbare auto huren en later teruggeven.

## Functionaliteit

- Managermenu: bedrijven aanmaken en beheren, autos per bedrijf toevoegen
- Klantmenu: klant aanmaken, beschikbare auto huren, gehuurde auto teruggeven
- Gegevens worden opgeslagen in een embedded H2-database via JDBC

## Technologie

- Java
- JDBC met H2 embedded database
- DAO-patroon met interfaces per entiteit
- Gradle