# Structure Sensor 3D Scanner
Structure Sensoren er en super fed 3D Scanner som du kan bruge til at scanne noget fysisk, og derefter generere en 3D model baseret på scanningen. Du kan både scanne rum, objekter og personer. 3D Scanneren er oprindeligt lavet til iPad, men udviklerne af Scanneren har gjort det let for brugere at bruge den via din computer istedet - Uanset om du bruger Windows eller Mac. Det er let at sætte op, og kræver kun følgende:

* Én Structure Sensor 3D Scanner.
* Skanect: 3D Scanner software installeret på din Computer.
* Structure Sensor driver, så scanneren kan køre via din computer.

Derudover skal du ofte bruge et 3D modelleringsværktøj til at finpudse din model efter scanning. Dette kan for eksempel være:

* Fusion 360
* TinkerCad
* Maya (Kan kræve en omformatering af filtypen hvis din model skal 3D printes efterfølgende)

---

### Installation
Før du kan bruge 3D Scanneren skal du hente noget software og en driver på internettet. Du kan finde links til begge herunder.

#### Installation af Skanect
Hent skanect 3D Scanner software [HER.](https://skanect.occipital.com/download/#purchase)

#### Installation af driver til Windows & Mac
Hent driver så sensor og 3D Scanner software kan snakke sammen [HER.](https://s3.amazonaws.com/io.structure.assets/SDK/StructureCore-DriverAndFirmware-0.9.7.zip)

#### Installation af Structure Sensor
Sæt Structure Sensoren i computeren med USB. Hvis driveren og softwaren er installeret problemfrit så burde Skanect genkende sensoren efter et øjeblik.

---

### Workflow
#### 1. Scanning af objekt
Sørg for at hav god plads omkring dig når du skal optage dit objekt. For at få den bedste model skal du kunne gå 360 grader omkring det, imens du scanner. Forsøg at hav den samme afstand og højde for sensoren igennem hele scanningen. Så har sensoren lettere ved at scanne objektet og din model bliver bedre.

#### 2. Juster model i Skanect
Når du har optaget dit objekt har du mulighed for at kunne ændre i nogle af indstillingerne for modellen. Her kan du lappe eventuelle huller og andre ujævnheder. I dette repository er der vedlagt en [PDF](/structure-sensor-3d-scanner/raw/master/Skanect-Scanning-Guide.pdf) med en quickstart guide til hvordan du bruger Skanect softwaren og hvad de forskellige indstillinger gør.

#### 3. Fjern fejlelementer og print færdig model
Når du er færdig med at justere på indstillingerne i Skanect skal du eksportere modellen som .OBJ. Nogle gange kan scanneren finde på at tage loftet, gulvet eller andre elementer fra baggrunden med i den endelige model. Afhængig af hvordan optagelsen gik, kan det være du skal fjerne nogle fejlelementer i [Tinkercad](https://www.tinkercad.com/) eller [Fusion 360] (https://www.autodesk.com/products/fusion-360/overview) efter du har eksporteret modellen fra Skanect. 

Hvis du er tilfreds med scanningen kan du også åbne modellen direkte i [Cura](https://ultimaker.com/software/ultimaker-cura) til 3D Print. Hvis modellen ikke skal printes, men skal bruges i et 3D space, kan du også importere den direkte ind i Maya eller lignende 3D modelleringssoftware.
