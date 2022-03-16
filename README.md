# OpenSCAD-Getriebebibliothek
Ein Bibliothek für Getriebe in OpenSCAD

Bibliothek für Evolventen-Zahnräder, Schnecken und Zahnstangen

Enthält die Module
- zahnstange(modul, laenge, hoehe, breite, eingriffswinkel=20, schraegungswinkel=0)
- stirnrad(modul, zahnzahl, breite, bohrung, eingriffswinkel=20, schraegungswinkel=0, optimiert=true)
- pfeilrad(modul, zahnzahl, breite, bohrung, eingriffswinkel=20, schraegungswinkel=0, optimiert=true)
- zahnstange_und_rad (modul, laenge_stange, zahnzahl_rad, hoehe_stange, bohrung_rad, breite, eingriffswinkel=20, schraegungswinkel=0, zusammen_gebaut=true, optimiert=true)
- hohlrad(modul, zahnzahl, breite, randbreite, eingriffswinkel=20, schraegungswinkel=0)
- pfeilhohlrad(modul, zahnzahl, breite, randbreite, eingriffswinkel=20, schraegungswinkel=0)
- planetengetriebe(modul, zahnzahl_sonne, zahnzahl_planet, anzahl_planeten, breite, randbreite, bohrung, eingriffswinkel=20, schraegungswinkel=0, zusammen_gebaut=true, optimiert=true)
- kegelrad(modul, zahnzahl,  teilkegelwinkel, zahnbreite, bohrung, eingriffswinkel=20, schraegungswinkel=0)
- pfeilkegelrad(modul, zahnzahl, teilkegelwinkel, zahnbreite, bohrung, eingriffswinkel=20, schraegungswinkel=0)
- kegelradpaar(modul, zahnzahl_rad, zahnzahl_ritzel, achsenwinkel=90, zahnbreite, bohrung, eingriffswinkel = 20, schraegungswinkel=0, zusammen_gebaut=true)
- pfeilkegelradpaar(modul, zahnzahl_rad, zahnzsahl_ritzel, achsenwinkel=90, zahnbreite, bohrung, eingriffswinkel = 20, schraegungswinkel=0, zusammen_gebaut=true)
- schnecke(modul, gangzahl, laenge, bohrung, eingriffswinkel=20, steigungswinkel=10, zusammen_gebaut=true)
- schneckenradsatz(modul, zahnzahl, gangzahl, breite, laenge, bohrung_schnecke, bohrung_rad, eingriffswinkel=20, steigungswinkel=0, optimiert=true, zusammen_gebaut=true)

Beispiele für jedes Modul befinden sich auskommentiert am Ende dieser Datei

Autor:		Dr Jörg Janssen
Stand:		29. Oktober 2018
Version:	2.3
Lizenz:		Creative Commons - Attribution, Non Commercial, Share Alike

Erlaubte Module nach DIN 780:
0.05 0.06 0.08 0.10 0.12 0.16
0.20 0.25 0.3  0.4  0.5  0.6
0.7  0.8  0.9  1    1.25 1.5
2    2.5  3    4    5    6
8    10   12   16   20   25
32   40   50   60
