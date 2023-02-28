# Frumgerð í Inkscape (_Prototype_)

Við höfum tengirammann (_Wireframe_) til hliðsjónar við að búa til frumgerð að lokaverkefni áfangans. Inkscape teikniforritið hentar vel til að búa til frumgerð að litlum vef. 

UI Design in Inkscape (1)
https://manjitkarve.com/posts/inkscape-design-1/

#### Dæmi um frumgerð sem er unnin í Inkscape

Síðan búum við til síðu í _Inkscape_ sem sýnir uppbyggingu vefsins með réttri litasamsetningu. Myndir er tómir rammar og textinn er "_dummy_" texti. Í þeirri vinnu getum við breytt og bætt hönnunina þannig að þegar frumgerðin er tilbúin þá er útlit og skipulag vefsins klárt í mismunandi skjástærðum. 

![1280](prototype1280x3200-OUT.svg)

### Inkscape stillingar

Við búum til Inkscape skjöl sem eru sett upp í mismunandi stærðum og höfum stærð þeirra með sömu breidd og algengar skjástærðir eru. Við stillum einingamál (_Units_) Inkscape í **Pixel**.

![Inkscape document properties](vinnugogn/document-properties.jpg)

Hér er upptalning á stærðum sem hægt er að nota í Inkscape

1. Farsímar - lóðrétt staða (_Portrait_)
   * 360 x 3200 (skjástærð 360 x 640 - Galaxy S5) 

2. Farsímar - lárétt staða (_Landscape_)
   * 640 x 3200 (skjástærð 640 x 360 - Galaxy S5) 

3. Spjaldtölvur lóðrétt staða (_Portrait_)
   * 760 x 3200 (skjástærð 760 - 1024 - iPad) 

4. Spjaldtölvur lárétt staða (_Landscape_)
   * 1024 x 3200 (skjástærð 1024 - 760 iPad) 

5. Fartölvur 
   * 1280 x 3200 (skjástærð 1280 - 1024) 

6. Fartölvur og borðtölvur
   * 1600 x 3200 (skjástærð 1600 - 1050) 

Hæð skjalsin ræðst af innihaldi vefsins þannig að 3200px er bara tala sem gengur upp í 16.

## Grid - 16px = 1em

Til að auðvelda endanlega hönnun er skynsamlegt að nota sömu grunn eininguna 16px (1em) og er notuð í vefsíðugerð. Í Inkscape stillum við Grid eins og sýnt er hér á mynd.

![Grid 16px](grids-16px.jpg)

Með 16px grid er auðvelt að skilgreina stærðir.

![Grid 16px](Skjámynd1280x800.jpg)

[Bjargir](https://github.com/vefhonnun/21V/wiki/Bjargir#skipulagning-og-h%C3%B6nnun)