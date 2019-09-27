# TanganyikaLED
This is a compilation of data used for a study on night-time, light-based fishing gears in Lake Tanganyika. The main aim of the research associated with the collection of these data was to assess the costs of potential consequences of switching from using kerosene lanterns to various types of LEDs systems in Lake Tanganyika. Our overall aim was 1) to understand factors that influence the adoption of this new LED lighting technology and 2) to determine whether LED systems influence overall fish catch and composition.

The "DATA_Light_v1.csv" file contains light measurements at the surface of Lake Tanganyika for each of the three light treatments in the fishing experiment from 400-700 nm. The variable names are as follows:
Wavelength=The wavelength associated with the light measurmeent in units of nanonmeters (nm)
LightKind=The type of light that was used
Light=The number of photons per area per time that were received by the phototmeter in units of micromol photons per square meter seconds (umol photons m^-2 s^-1).

The "DATA_Catches_v1.csv" file contains catch measurements from boats using three different fishing gears. The variable names are as follows:
ID = Sample ID that can be macthed with the "DATA_SpeciesSizes_v1.csv" file.
Date = Date when the fishing boats returned to shore
BoatPair=An annonomyzed name for the boatpair that did the fishing
LightKind=The type of light that was used
PullTime=The time of day (decimal dayfraction; e.g. 0.5=noon) when the nets were lifted
LightDuration=The length of time (decimal dayfraction;e.g. 0.2 = 4.8 hours) that the lights were illuminated before lifting the nets
Wind=the average windspeed during boat deployment
Shore distance=the distance from shore when the net was lifted
Moonlight=The amount of moonlight during the night of fishing
TotalCatches=The total amount of fish caught by the boat pair in one night of fishing. Units are kilograms (kg).
ClupCatch=The total amount of Clupeids caught by the boat pair in one night of fishing. Units are kilograms (kg).
StapCatch=The total amount of Stappersi caught by the boat pair in one night of fishing. Units are kilograms (kg).
StapSize=The average size of the Stappersi caught by the boat pair in one night of fishing. Units are in kilograms (kg).
LimnoSize=The average size of the Limnothrissa caught by the boat pair in one night of fishing. Units are in kilograms (kg).
LimnoSize=The average size of the Stolothrissa caught by the boat pair in one night of fishing. Units are in kilograms (kg).

The "DATA_SpeciesSizes_v1.csv" file contains measurmeents of the species, length and weight of each individual fish from a sample taken from the total fish catches. These data can be linked with the "DATA_Catches_v1.csv" file through the ID column. The variable names are as follows:
ID=Sample ID that can be macthed with the "DATA_Catches_v1.csv" file.
Species=The species of the indivudual fish
TotalLength=The length from the tip of the head to the end of the caudal (tail) fin.
