# Antennisuunaja mehitamata õhusõidukitele.
Siin lehel on Eesti Lennuakadeemias, 2024. aasta kevadsemestril, mehhatroonika aine raames arendatud antennisuunaja lähtekood ja kiirjuhend.

Antennisuunaja kasutamiseks on vaja mehitamata õhusõidukit, mis saadab telemeetria kaudu MAVLINK protokollis informatsiooni. Kõige halvemal juhul on vaja ka oma raadiot ja antenni, sest selle teksti kirjutamise hetkel pole veel kindel, mis raadio ja antenn suunajal peal on (praegu) 868 MHz.

## Mida on vaja?
- Antenn (kui suunajal pole)
- Raadio (kui suunajal pole)
- (Süle-) arvuti. Selles arvutisse ühendub nii antennisuunaja kui ka raadio.
- Droon (kui simulaatorit ei kasutata)
- Elekter (antennisuunajal on pingeregulaator, võtab sisse kuni 40 V).
## Kuidas kasutada?
Vaata [mavlink-telemeetria repost](https://github.com/ela-mehhatroonika-antennisuunaja/mavlink-telemeetria)
## To-do
- [ ] Joystickuga juhtimine
- [ ] Config.txt
- [ ] Kompass
- [ ] GPS
- [ ] requirements.txt
