# MedicinasVeidlapaProject

Šis ir Java projekts, kas paredzēts medicīnisko veidlapu ģenerēšanai. Programma ļauj ievadīt datus, piemēram, pacienta informāciju, medikamentu nosaukumus un citus datus, un automātiski ģenerē standarta medicīnisko veidlapu.

## Projekta galvenās funkcijas
- Datu ievade no faila vai lietotāja saskarnes.
- Veidlapu ģenerēšana, izmantojot ievadītos datus.
- Iespēja pielāgot veidlapas laukus.
- Datu saglabāšana un ielāde.

## Projekta struktūra
MedicinasVeidlapaProject/
├── src/
│   └── Veidlapa/
│       ├── MedicinasVeidlapa.java
│       ├── app_preferences.txt
│       ├── arsti_psihiatri.txt
│       ├── gimenes_arsti.txt
│       ├── Medicina_slimnīcai.xlsx
│       └── medikamenti.txt
├── Jar faili/
│   ├── commons-collections4-4.4.jar
│   ├── commons-compress-1.19.jar
│   ├── commons-io-2.6.jar
│   ├── log4j-api-2.12.1.jar
│   ├── log4j-core-2.12.1.jar
│   ├── poi-4.1.2.jar
│   ├── poi-ooxml-4.1.2.jar
│   ├── poi-ooxml-schemas-4.1.2.jar
│   └── xmlbeans-3.1.0.jar
└── resources/
└── Medicina_slimnīcai.xlsx


## Tehnoloģijas un bibliotēkas
- **Java**: Galvenā programmēšanas valoda.
- **Apache POI**: Bibliotēka Excel (`.xlsx`) failu lasīšanai un rakstīšanai.
- **Log4j**: Izmantots, lai žurnālēšanai un kļūdu atskaitei.
- Citas atkarības:
    - `commons-collections4-4.4.jar`
    - `commons-compress-1.19.jar`
    - `commons-io-2.6.jar`
    - `log4j-api-2.12.1.jar`
    - `log4j-core-2.12.1.jar`
    - `poi-4.1.2.jar`
    - `poi-ooxml-4.1.2.jar`
    - `poi-ooxml-schemas-4.1.2.jar`
    - `xmlbeans-3.1.0.jar`

## Kā palaist projektu
1.  Klonējiet šo repozitoriju uz savu lokālo datoru:
    `git clone https://github.com/dawis86/MedicinaAplikacija.git`
2.  Atveriet projektu savā Java IDE (piemēram, Eclipse vai IntelliJ IDEA).
3.  Pievienojiet visus `Jar faili` mapē esošos failus kā ārējās bibliotēkas.
4.  Palaidiet `MedicinasVeidlapa.java` failu, kas atrodas `src/Veidlapa` mapē.

## Autors
- Dāvis Strazds
- GitHub: dawis86
