# Structure Sensor 3D Scanner
Structure Sensoren er en super fed 3D Scanner som du kan bruge til at scanne noget fysisk, og derefter generere en 3D model baseret på scanningen. Du kan både scanne rum, objekter og personer. 3D Scanneren er oprindeligt lavet til iPad, men udviklerne af Scanneren har gjort det let for brugere at bruge den via din computer istedet - Uanset om du bruger windows eller mac. Det er let at sætte op, og kræver kun følgende:

* Én Structure Sensor 3D Scanner.
* Skanect: 3D Scanner software installeret på din Computer.
* Structure Sensor driver, så scanneren kan køre via din computer.

---

### Installation
Før du kan bruge 3D Scanneren skal du lige hente noget software og en driver på internettet. Du kan finde links til begge herunder.

#### Installation af Skanect
Hent skanect 3D Scanner software [HER.](https://skanect.occipital.com/download/#purchase)

#### Installation af driver til windows & Mac
Hent driver så sensor og 3D Scanner software kan snakke sammen [HER.](https://s3.amazonaws.com/io.structure.assets/SDK/StructureCore-DriverAndFirmware-0.9.7.zip)

#### Installation af Structure Sensor
Sæt Structure Sensoren i computeren med USB. Hvis driveren og softwaren er installeret problemfrit så burde Skanect genkende sensoren efter et øjeblik.

---

### Workflow
Optag dit objekt. For at få den bedste model skal du gå 360 grader omkring det. Forsøg at hav den samme afstand og højde for sensoren igennem hele optagelsen. Så har sensoren lettere ved at scanne objektet og din model bliver bedre.

Når du har optaget dit objekt har du mulighed for at kunne ændre i nogle af indstillingerne for modellen. Her kan du lappe eventuelle huller og andre ujævnheder. I dette repository er der vedlagt en pdf med en quickstart guide til hvordan du bruger Skanect softwaren og hvad de forskellige indstillinger gør.

Når du er færdig med at justere på indstillingerne i Skanect skal du eksportere modellen som .OBJ. Nogle gange kan scanneren finde på at tage loftet, gulvet eller andre elementer fra baggrunden med i den endelige model. Afhængig af hvordan optagelsen gik, kan det være du skal fjerne nogle fejlelementer i tinkercad eller fusion efter du har eksporteret modellen. 

Hvis du er tilfreds med scanningen kan du også åbne modellen direkte i Cura til 3dprint.
