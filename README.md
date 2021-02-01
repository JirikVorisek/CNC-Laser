# CNC Laser
CNC laser postavený z komponentů vymontovaných z nefunkčních multifunkčních tiskáren (Bipolární krokové motory, převody, řemen a napínací kolečko), Arduino UNO + CNC shield V3.0 jako kontroler a NEJE Laser modul - 30W elektrický příkon (7,5W optický výkon).

# Software
1. GRBL - firmware pro Arduino UNO. Překládá G-CODE posílaný z počítače přes seriovou linku do Arduino Uno do elektrických signálů pro Bipolární krokové motory a Laserový modul.
2. LaserGRBL - software slouží zejména jako G-CODE sender. Posílá přes seriovou linku G-CODE do Arduino Uno. Software umí také vektorizovat bitmapový obrázek a vygenerovat G-CODE.
3. Fusion 360 - CAM program kde lze modelovat 3D objekty. Součástí je i Manufactoring, který umožňuje generovat z modelu G-CODE.
