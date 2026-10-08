# Java III - Klinika e CSS

Kjo është detyra e javës së tretë ku kam rregulluar afishen e klubit të debatit me CSS.

## Çfarë kam rregulluar te `gabime.css`
1. **Teksti nuk shihej:** Te `#poster` ngjyra e tekstit ishte e bardhë mbi sfond të bardhë për shkak se ID-ja kishte peshë (specifikë) më të madhe se klasa `.poster`. E kam rregulluar duke përdorur vetëm klasa.
2. **Dalja nga ekrani:** Elementi dilte jashtë ekranit prej `width: 700px` dhe `padding: 80px`. E kam rregulluar duke përdorur `max-width: 100%` dhe `box-sizing: border-box`.

## Përgjigjet e pyetjeve
- **Kaskada:** Rregulli i `#poster` fitoi sepse selektorët me ID kanë specifikë më të lartë se klasat.
- **Box Model:** Me `box-sizing: border-box`, padding-u dhe kufijtë (border) llogariten brenda gjerësisë së elementit, kështu që nuk del jashtë në ekrane të vogla (si 360px).
