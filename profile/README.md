# Antennisuunaja MAVLINK-protokolli kasutatavatele mehitamata õhusõidukitele
Siin lehel on Eesti Lennuakadeemias, 2024. aasta kevadsemestril, mehhatroonika aine raames arendatud antennisuunaja lähtekood ja kiirjuhend.

Antennisuunaja kasutamiseks on vaja mehitamata õhusõidukit, mis saadab telemeetria kaudu MAVLINK protokollis informatsiooni. Kõige halvemal juhul on vaja ka oma raadiot ja antenni, sest selle teksti kirjutamise hetkel pole veel kindel, mis raadio ja antenn suunajal peal on (praegu 868 MHz).

## Mida on vaja?
- Antenn (kui suunajal pole)
- Raadio (kui suunajal pole)
- (Süle-) arvuti. Selles arvutisse ühendub nii antennisuunaja kui ka raadio.
- Droon (kui simulaatorit ei kasutata)
- Elekter (antennisuunajal on pingeregulaator, võtab sisse kuni 40 V).
## Kuidas kasutada?
- Kontrolli, et arvutis oleks Python. Seejärel installi `requirements.txt` kasutades käsku `pip install -r requirements.txt `
- Kontrolli config.txt failis olevad parameetrid.
- Jooksuta `main.py`.
- Jooskuta command promptis `mavproxy --master=COMx --out 127.0.0.1:14550`. `x` asendada pordi numbriga, millesse raadio on ühendatud (vt Device Managerist).
- Kui MAVPROXY saab MAVLINKi ühenduse kätte, peaks antennisuunaja tööle hakkama.
