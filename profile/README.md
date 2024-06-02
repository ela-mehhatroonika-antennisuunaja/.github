# Antennisuunaja mehitamata õhusõidukitele.
Siin lehel on Eesti Lennuakadeemias 2024. aasta kevadsemestril mehhatroonika aine raames arendatud antennisuunaja lähtekood ja kiirjuhend.

Antennisuunaja kasutamiseks on vaja mehitamata õhusõidukit, mis saadab telemeetria kaudu MAVLINK protokollis informatsiooni. Arvatavasti läheb vaja ka oma **antenni ja raadiot**, praegu jätame suunajale külge sellega kaasa tulnud 2.4 GHz antenni (mida me proovisime muuta, seega see võib-olla enam ei tööta).

## Mida on vaja?
- Antenn (kui suunajal pole)
- Telemeetriaraadio/-vastuvõtja (kui suunajal pole)
- (Süle-) arvuti. Selles arvutisse ühendub nii antennisuunaja kui ka raadio (mõlemad USB-ga).
- Droon (kui simulaatorit ei kasutata)
- Elekter (antennisuunajal on pingeregulaator, võtab sisse kuni 40 V). 4S 5000mAh aku sobib hästi.
## Kuidas kasutada?
Vaata [mavlink-telemeetria repost](https://github.com/ela-mehhatroonika-antennisuunaja/mavlink-telemeetria)
## To-do
- [X] Config.txt
- [X] Kompass - vajab arendamist, kas leida uus või filtreerida vana tulemusi.
- [X] requirements.txt
- [ ] GPS - osaliselt okei, saab kasutada drooni GPS-i
- [ ] Joystickuga juhtimine
