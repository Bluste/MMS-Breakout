# MMS-Breakout
Dorada završnog projekta Breakout iz kolegija MMS
Igra je igriva, ali joj nedostaje dinamike. Kod samog testiranja sam uvidio neke probleme pa sam prije većih promjena dodao sljedeće promjene:


- Akceleracija loptice - suptilno a primjetno ukoliko igrač dugo igra bez gubljenja života
- Randomizacija pri odbijanju - kako još nije dodana opcija da igrač može utjecati na kretnju lopte, dodano je malo odstupanje od smjera pri odbijanju
- Promijenjen font i veličina teksta i poruka
- Ispis poruke na početku kako bi igrač znao kako započeti igru
- Ograničen kut početnog smjera kako bi se izbjegle horizontalne putanje lopte
- Refaktorizacija draw() funkcije

Potom sam odlučio učiniti igru zanimljivijom tako da uvedem PowerUp-ove koji ispadaju prilikom razbijanja određenih brick-ova:

- Dodan sustav za obradu PowerUp-ova
- Dodani PowerUpOvi za dobivanje života, povećanje i smanjenje ploče
- Nacrtane ikone za povećanje i smanjivanje ploče

Daljnja poboljšanja:

- Randomizacija PowerUp-ova, za sada su hardkodirani u određene brick-ove
- Dodati dodatne levele
- Zvučni efekti za PowerUp-ove
- Pozadinska glazba u igrici
- Napraviti hijerarhiju klasa i podijeliti kod u više datoteka
