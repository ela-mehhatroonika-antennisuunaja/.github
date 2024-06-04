# Antennisuunaja mehitamata õhusõidukitele.
Siin lehel on Eesti Lennuakadeemias mehhatroonika aine raames arendatud antennisuunaja lähtekood ja kiirjuhend. Aine toimus 2024. aasta kevadsemestril.

Antennisuunaja kasutamiseks on vaja mehitamata õhusõidukit, mis saadab telemeetria kaudu MAVLINK protokollis informatsiooni. Arvatavasti läheb vaja ka oma **antenni ja raadiot**, praegu jätame suunajale külge sellega kaasa tulnud 2.4 GHz antenni (mida me proovisime muuta, seega see võib-olla enam ei tööta).

**NB!** Ärge tehke horisontaalse osaga täisringi ehk jätke alati sama sektori sisse (punasest noolest 114 kraadi mõlemale poole)! Kui ta teeb täisringi ära, siis liigub nullkoht paigast ära ning sisemised kaablid võivad katki minna. Kui ühendate masina vooluringi ning see ei keera ennast punase noolega kohakuti, siis on horistontaalset osa (käsitsi) liiga palju keeratud ning nullpunkt on paigast ära. Suunajat saab kasutada, võttes uueks nullpunktiks selle suuna, kuhu masin end käivitamisel keerab. Kui see peaks juhtuma, palun andke teada.
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
- [ ] Parem/kompassipõhine juhtimisalgoritm

## Muu info
Kui soovite oma programmiga suunajat liigutada või vaadata servode juhtimise koodi, vaata [servo juhtimise repot](https://github.com/ela-mehhatroonika-antennisuunaja/servo-juhtimine)

Küsimuste ja tagasiside korral kirjutage githubis metmetsale, markus.torpel@eava.ee või vastava repo _issues_ alla.
