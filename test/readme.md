# F�lj frukten

I denna uppgift ska du f� leka med koordinater i Scratch. Koordinater beh�vs f�r att ange n�gon eller n�gots position. Du ska f� animera en robot s� att den r�r sig runt p� scenen och �ter frukt.

> Anv�nder du Scratch 2.0 offline-version? <https://www.kodboken.se/start/kodaiskolan/aventyrxy/uppgifter-i-scratch/folj-frukten-offline?chpt=0">H�r hittar du samma instruktion anpassad utifr�n kodning med nedladdningsbara Scratch 2.0 offline</a>.

> Bl�ddra dig fram genom denna guide, steg f�r steg. <a href="https://scratch.mit.edu" target="_blank">
  �ppna �ven p�b�rjade Scratch-projektet av F�lj frukten genom att klicka p� l�nken bredvid katt-figuren ovan</a>. H�r kodar och skapar du vidare sj�lva spelet utifr�n instruktionerna nedan. 
  
Ett exempel p� hur det kan se ut hittar du h�r: <a href="https://scratch.mit.edu/projects/172523787/" target="_blank">https://scratch.mit.edu/projects/172523787/</a>

![image alt text](image_0.png)

## 1 - Remixa ett projekt

Vi b�rjar med att remixa projekt som redan finns p� Scratch. Detta g�r att det blir enklare att komma ig�ng. Dessutom f�r du tv� sprajtar och lite kod p� k�pet. Smart va?!

1. �ppna din webbl�sare och g� till

    <a href="https://scratch.mit.edu/projects/188767375/" target="_blank">https://scratch.mit.edu/projects/188767375/</a>

2. Klicka p� knappen **"Remix"** s� att du f�r din egen version av projektet.

    ![image alt text](image_1.png)

Nu kommer du komma in i Scratch studion d�r du kan koda din egen version.

3. D�p om projekt till n�got som passar b�ttre.

    ![image alt text](image_3.png)

*Namnet p� projektet har f�tt ordet "remix" p� slutet*

I projektet har du nu tv� sprajter: ![image alt text](image_4.png)

1. En robot-sprajt som �r din spelare

2. Koordinataxlar som visar x- och y-axeln.

Innan vi b�rjar koda ska vi f�rst titta lite n�rmare p� v�ra tv� sprajter och koordinatsystemet i Scratch.

1. Markerar sprajten **Koordinater** s� f�r du upp koden f�r denna sprajt. Det �r en enkel kod som helt enkelt placerar sprajten p� r�tt st�lle p� scenen.

    ![image alt text](image_5.png)*S� h�r ser en markerad sprajt ut*

2. Klicka p� fliken **Kl�dslar**. D�r finns koordinatsystemet uppritat p� olika s�tt.

    ![image alt text](image_6.png)

> Vi kommer anv�nda koordinatsystemet med ett rutn�t s� att du kan l�ra dig hur koordinater fungerar. N�r du l�rt dig detta kan du anv�nda en annan kl�dsel. En annan kl�dsel kan du ocks� anv�nda om krysset och rutn�tet �r i v�gen f�r andra sprajter.

**Nu ska vi kolla s� att placeringen av koordinatsystemet fungerar:**

1. Klicka p� sprajten **Robot** s� att den blir markerad. Koordinaten f�r en sprajt visas nedanf�r scenen. Vilka koordinater har sprajten?

    ![image alt text](image_9.png)

3. Flytta omkring **Robot-sprajten** p� scenen och se hur koordinaterna �ndrar sig

4. Placera **Robot**-sprajten ungef�r vid **x: 0, y:0**. Denna punkt kallas *origo*, och �r mitt p� scenen.

## 2 - Bakgrund och frukter

Du ska f� b�rja med att ladda en bakgrundsbild f�r spelet.

1. Markera scenen

2. Klicka p� fliken **Bakgrunder**

    ![image alt text](image_10.png)

3. Klicka p� **F�rgburken** och f�rgl�gg bakgrunden med en rolig f�rg. H�r i exemplet har jag anv�nt gr�nt.

    ![image alt text](image_11.png)

**Nu ska vi placera ut n�gra frukter p� scenen:**


1. Klicka p� "V�lj en sprajt" l�ngt ner till v�nster.

    ![image alt text](image_12.png)

2. Markera **�pplet** och klicka p� **Ok**

    ![image alt text](image_12b.png)

3. Placera **�pplet** i �vre v�nstra h�rnet p� scenen.

4. L�gg sj�lv till tre sprajter och placera ut dem p� scenen. H�r har vi valt att l�gga ut **Jordgubbe**, **Apelsin** och **Vattenmelon**.

Det kan se ut s� h�r:

![image alt text](image_13.png)

## 3 - Animera roboten

Nu ska vi animera roboten s� att den r�r sig mellan de olika frukterna: f�rst till �pplet, sedan till bananerna, sedan till vattenmelonen och till sist till apelsinen.

1. B�rja med att markera **Robot** sprajten:

    ![image alt text](image_14.png)

2. Skapa ett skript f�r roboten. B�rja med att dra in ett kodblock som heter **"N�r denna sprajt klickas p�"** till skriptytan.

    ![image alt text](image_15.png)

3. Under detta block f�ster du ett kodblock **"G� till x: y:"**

    ![image alt text](image_16.png)

4. I st�llet f�r koordinaterna som st�r i kodblocket skriver du vilka koordinater **du tror att �pplet har**. Anv�nd det utritade koordinatsystemet som hj�lp. Det kan se ut se h�r.

    ![image alt text](image_17.png)

5. Dra in sedan ett kodblock **"V�nta 1 sekund"** och f�st det underst i skriptet.

    ![image alt text](image_18.png)

6. Nu drar du in ett till **"g� till x: y:"** och anger koordinaterna f�r bananerna. Och sedan ett **�v�nta�**-block.

7. Forts�tt s� tills du har animerat **Roboten** att g� runt till alla frukterna.

> Testa programmet genom att klicka p� Roboten! G�r Roboten runt till alla frukterna?

Vi ska g�ra programmet lite b�ttre, s� att roboten kommer tillbaka till mitten n�r spelet startar. Vi vill ocks� g�ra s� att roboten inte d�ljs av frukterna. Detta kallas ett *startskript*.

* Skapa f�ljande skript f�r **Roboten**

    1. N�r START klickas p�

    2. G� till x:0 y:0

    3. G� till �versta lagret

    ![image alt text](image_19.png)

## F�rdig!

Grattis, nu har du skapat ett nytt program!

Gl�m inte att spara ditt projekt! Kom ih�g att ge spelet ett bra namn.

## Utmaningar

### Frukterna �ts upp

Du kan g�ra s� att frukterna f�rsvinner n�r roboten bes�ker dem. F�r varje skript beh�ver du skapa f�ljande skript

1. N�r START klickas p�

2. Visa

3. F�r alltid

    1. OM r�r vid **Robot**

        1. G�m

Kan du pussla ihop detta skript fr�n dessa kodblock ?

![image alt text](image_20.png)

> **Tips!** Du kan kopiera kod mellan sprajter genom att dra ett skript till en sprajt.

![image alt text](image_21.png)

### Snitslad bana

Du kan rita en bana p� bakgrunden som roboten m�ste r�ra sig innanf�r. P� detta s�tt blir det viktigare att ange exakta koordinater d�r **Roboten** ska r�ra sig. Det kan se ut s� h�r

![image alt text](image_22.png)

Skapa ett skript f�r **Roboten** som s�ger

1. N�r START klickas p�

2. F�r alltid

    1. OM r�r **gr�n** f�rg

        1. Stoppa alla

Dessa kodblock beh�ver du:

![image alt text](image_23.png)

## Fr�gest�llningar

Vad �r en koordinat?

Hur l�ng �r x�axeln i Scratch?

Hur l�ng �r y�axeln i Scratch?

Vilken koordinat har mitten p� scenen?

Vad inneb�r det att Remixa ett projekt?

Vad �r ett startskript? Varf�r �r det bra att anv�nda det?