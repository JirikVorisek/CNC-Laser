# CNC Laser
CNC laser postavený z komponentů vymontovaných z nefunkčních multifunkčních tiskáren (Bipolární krokové motory, převody, řemeny a napínací kolečka), Arduino UNO + CNC shield V3.0 jako kontroler a NEJE Laser modul - 30W elektrický příkon (7,5W optický výkon).

# Software
1. GRBL - firmware pro Arduino UNO. Překládá G-CODE posílaný z počítače přes seriovou linku do Arduino Uno do elektrických signálů pro Bipolární krokové motory a Laserový modul.
2. LaserGRBL - software slouží zejména jako G-CODE sender. Posílá přes seriovou linku G-CODE do Arduino Uno. Software umí také vektorizovat bitmapový obrázek a vygenerovat G-CODE.
3. Fusion 360 - CAM program kde lze modelovat 3D objekty. Součástí je i Manufactoring, který umožňuje generovat z modelu G-CODE.

# Nastavení Paramtrů LaserGRBL
Pro správný chod je nutné nastavit parametry zařízení
- Rozsah otáček/intensity laser (řízeno pomocí PWM)
- Počet kroků na 1 mm pro osy X, Y
- Rychlost pro rychlo posuv pro osy X, Y
- Hodnota akcelerace os X, Y
- Limity pracovní plochy
