<!--

author:   Nancy Brinkmann, Ronny Stolze

email:    nancy.brinkmann@hs-magdeburg.de, ronny.stolze@hs-magdeburg.de

version:  1.0.0

language: de_DE

narrator: DE FEMALE

-->

# **Lernzielkontrolle**

Überprüfen Sie hier Ihren Wissensstand.

<br>

<!--
style="color: red;"
-->
Beschreibung, welche Leistungen von den Studierenden zu erbringen sind, bevor sie das Praktikum antreten!

Um am Praktikum "Drehen" teilnehmen zu können, sind folgende Vorbereitungen zu treffen:

Ermitteln Sie mit Hilfe des [Oberflächenmodells](#19) und den vorgebenen zu erzielenden Oberflächengüten geeignete Bearbeitungsparameter. Diese benötigen Sie für Ihre praktischen Untersuchungen und sind in der Maschinensteuerung anzuwählen. (Bzw.<!--style="color: red;"--> werden<!--style="color: red;"--> sie<!--style="color: red;"--> über<!--style="color: red;"--> die<!--style="color: red;"--> Webumgebung<!--style="color: red;"--> an<!--style="color: red;"--> die<!--style="color: red;"--> Maschinensteuerung<!--style="color: red;"--> gesendet?)<!--style="color: red;"-->


Des Weiteren berechnen Sie für Ihre Technologieparameter mit Hilfe des [Zerspankraftmodells](#22) die theoretisch auftretenden Zerspankraftkomponenten. Diese vergleichen Sie später mit den Werten aus der Praxis!


<!--
style="color: red;"
-->
Beschreibung, welche Leistungen von den Studierenden zu erbringen sind, bevor sie das Praktikum antreten!
xxxxxyyyyyzzzz

<!--
style="color: red;"
-->
Fragen aus den Fach- und Lehrbüchern zur Zerspanungstechnik wie zum Beispiel "Denkena" durcharbeiten. Vielleicht sind noch passende dabei.



##Grundlagen der Zerspanungstechnik

{{0-28}}
***
**Frage 1**

Welche fünf wesentlichen Kriterien werden zur Beurteilung eines Zerspanprozesses herangezogen? Welche Aussagen lassen sich jeweils aus Ihnen ableiten?

***

{{1-2}}
***

> ~~Antwort Frage 1~~
>
> **Zerspankraft**
>
> * Auslegung von Werkzeugmaschine, Spannmittel u. Zerspanungsparametern
>
> * Aussage zu erzielbaren Genauigkeiten, Verformungen sowie der Zerspanbarkeit von Werkstoffen
>
> **Verschleiß des Werkzeugs**
>
> * Standgrößen: Standzeit, Standweg, Standmenge
>
> * Eignung Paarung Werkstoff-Schneidstoff
>
> * Wirtschaftlichkeit des Prozesses
>
> * Reproduzierbarkeit der Qualität
>
> **Oberflächenausbildung des Werkstücks**
>
> * Werkstückqualität: Maß, Form, Lage, Rauheit, Randzoneneigenschaft
>
> **Spanform**
>
> * WZ-Konstruktion u. Arbeitsraumgestaltung in WZM
>
> * Spanabführung und Schüttgutbedarf - sicherer, ungestörter Prozessablauf
>
> **Zeitspanvolumen / Materialabtrag**
>
> * Prodiktivität
>
> * Wirtschaftlichkeit

***

{{2-28}}
***
**Frage 2**

Was sind die wesentlichen Bewegungen und deren abgeleitete Geschwindigkeiten bei einem Zerspanvorgang und wie erfolgt die Umsetzung dieser Bewegungen an der Werkzeugmaschine? <br/> Wie beeinflussen die Geschwindigkeiten den Zerspanvorgang?

***

{{3-4}}
***
> ~~Antwort Frage 2~~
>
> ![image](images/Bewegungen-Richtungen-Drehen.png)<!--
style = "width: 50%; "
-->
>
> <!--
style="font-size: 14px; width: 100%; margin: 0.25em 1;"
-->
> ***Abbildung:*** *Bewegungen, Richtungen und Geschwindigkeiten beim Drehen (Quelle: Fritz/ Schulze)*
>
> <br/>
>
> ~~**Schnittbewegung**~~
>
> * wichtigste Bewegung beim Spanen
>
> * gekennzeichnet für einen Schneidenpunkt zwischen Werkzeug und Werksück
>
> * für einmalige Spanabnahme während einer Umdrehung (Hub)
>
> * beim Drehen rotatorisch
>
> * Schnittgeschwindigkeit $v_c$ <br/>
>  * momentane Geschwindigkeit des Schneidenpunktes in Schnittrichtung
>
> * Die technische Realisierung der Schnittgeschwindigkeit im Drehprozess erfolgt an der Werkzeugmaschine über die Drehzahl.
>
> * Schnittgeschwindigkeit beeinflusst in großem Maße: <br/>
>  * Arbeitsproduktivität <br/>
>  * Oberflächenqualität <br/>
>  * Zerspanprozess (Kräfte, Temperaturen, Verschleiß etc.) <br/>
>
> * Schnittgeschwindigkeit wird beeinflusst durch: <br/>
>  * Schneidstoff (Entwicklung maßgebend für Technologiesprung!) <br/>
>  * Werkstückwerkstoff <br/>
>  * Werkzeug (Geometrie, Verschleiß etc.) <br/>
>  * Werkzeugmaschine (Leistung, Steifigkeit etc.) <br/>
>  * Trockenbearbeitung / Kühlschmierstoffeinsatz <br/>
>  * Wahl der weiteren Arbeitswerte (Schnitttiefe, Vorschub etc.) <br/>
>
> <br/>
>
> ~~**Vorschubbewegung**~~
>
> * bewirkt zusammen mit Schnittbewegung eine mehrmalige oder stetige Spanabnahme
>
> * Zusammensetzung auch aus mehreren Komponenten möglich
>
> * Vorschubgeschwindigkeit $v_f$ <br/>
>  * momentane Geschwindigkeit des Werkstückes bzw. Werkzeuges in Vorschubrichtung <br/>
>  * häufig nur mit Vorschub f gearbeitet, f entspricht dem Weg je Umdrehung oder je Hub <br/>
>  * Aufteilung/ Verteilung des Vorschub bei mehrschneidigen Werkzeugen (Bohren, Senken, Reiben, Fräsen etc.) auf mehrere Schneiden <br/>
>
> * Technisch wird die Vorschubbewegung von den translatorischen Achsen der Werkzeugmaschine ausgeführt. Vorschub f in mm/U oder Vorschubgeschwindigkeit $v_f$ in mm/min.
>
> <br/>
>
> ~~**Wirkbewegung**~~
>
> * resultierende Bewegung aus Schnitt- und Vorschubbewegung
>
> * bewirkt den Zerspanvorgang
>
> * Wirkgeschwindigkeit $v_e$ <br/>
>  * momentane Geschwindigkeit des betrachteten Schneidenpunktes in Wirkrichtung <br/>
>  * Summe aus Vorschubgeschwindigkeitsvektor und Schnittgeschwindigkeitsvektor <br/>
>
***


{{4-28}}
***
**Frage 3**

Was sind Schnitt- bzw. Spanungsgrößen? Was verstehen Sie unter dem Zeitspanvolumen?

***

{{5-6}}
***

> ~~Antwort Frage 3~~
>
> **Schnitt- und Spanungsgrößen beim Längsdrehen:**
>
> ![image](images/Schnitt-und-Spanungsgroessen.png)<!--
style = "width: 50%; margin: 0em 5em;"
-->
>
> <!--
style="font-size: 14px; width: 100%; margin: 0em 5em;"
-->
> ***Abbildung:*** *Drehen: Schnitt- und Spanungsgrößen (Denkena: 2011)*
>
> <br/>
>
> Schnittgrößen (auch Eingriffsgrößen) sind die technologisch-physikalischen Größen, die aus den Bewegungen zwischen Werkzeug und Werkstück abgeleitet sind und zur Spanabnahme an der Maschine eingestellt werden müssen. Hierbei handelt es sich um die Schnitttiefe (Zustellung) $a_p$ und den Vorschub $f$.
>
> Spanungsgrößen, für die Kennzeichnung des Spanbildungsvorgangs wesentlich, sind aus den Schnittgrößen über den Einstellwinkel $ \kappa_r $ abgeleitet und beschreiben die Form und Größe der vom Werkstück abzuspanenden Schichten. Hierbei handelt es sich um die Spanungsbreite b und die Spanungsdicke h.
>
> $ b = \frac{a_p}{sin \kappa_r} $
>
> $ h = f \cdot sin \kappa_r $
>
> Aus den Schnitt- oder Spanungsgrößen wird der Spanungsquerschnitt A errechnet!
>
> $ A = a_p \cdot f $
>
> $ A = b \cdot h $
>
> <br/>
>
> **Zeitspanungsvolumen $Q_w$:**
>
> Ist das in einer bestimmten Zeiteinheit vom Werkstück abgespante Werkstoffvolumen (Spanungsvolumen).
>
> * wichtige Spanungsgröße, besonders für den Vergleich von spanenden Fertigungsverfahren
>
> * Maß für die Effektivität bzw. Leistungsfähigkeit
>
> $ \qquad Q_w = A \cdot v_c = a_p \cdot f\cdot v_c = b \cdot h \cdot v_c \qquad \qquad  mm^3/s $

***


{{6-28}}
***
**Frage 4**

In der nachfolgenden Abbildung sehen Sie einen Drehhalter mit Wendeschneidplatte. Es sind die Schneiden, Flächen, Ecken und Bewegungsrichtungen zu bestimmen!.

***

{{6-7}}
***

![image](images/Schneiden-Flaechen-Schneidkeil-ohne.png)<!--
style = "width: 60%; margin: 0em 2em;"
-->

<!--
style="font-size: 14px; width: 100%; margin: 0em 2em;"
-->
***Abbildung:*** *Schneiden und Flächen am Schneidkeil (Klocke 2018)*

***

{{7-8}}
***

> ~~Antwort Frage 4~~
>
> ![image](images/Schneiden-Flaechen-Schneidkeil-mit.png)<!--
style = "width: 75%; margin: 0em 1em;"
-->
>
> <!--
style="font-size: 14px; width: 100%; margin: 0em 1em;"
-->
> ***Abbildung:*** *Schneiden und Flächen am Schneidkeil (Klocke 2018)*

***


{{8-28}}
***
**Frage 5**

In der nachfolgenden Abbildung sind Ebenen, Bewegungen, Geschwindigkeiten und Winkel in der dargestellten Ebene zu bestimmen! Welche Ebene ist aufgespannt und wie ist diese definiert?

***

{{8-9}}
***

![image](images/Arbeitsebene-Winkel_ohne.png)<!--
style = "width: 60%; margin: 0em 2em;"
-->

<!--
style="font-size: 14px; width: 100%; margin: 0em 1em;"
-->
***Abbildung:*** *Ebene, Winkel und Bewegungen (Quelle: DIN 6580; Fritz, Schulze)*

***

{{9-10}}
***
> ~~Antwort Frage 5~~
>
> In der Abbildung ist die Arbeitsebene $ P_{fe} $ dargestellt. Diese wird durch die Schnitt- und Vorschubrichtung aufgespannt.
>
> ![image](images/Arbeitsebene-Winkel_mit.png)<!--
style = "width: 75%; margin: 0em 1em;"
-->
>
> <!--
style="font-size: 14px; width: 100%; margin: 0em 1em;"
-->
> ***Abbildung:*** *Arbeitsebene, Vorschub- und Wirkrichtungswinkel (Quelle: DIN 6580; Fritz, Schulze)*

***



{{10-28}}
***
**Frage 6**

Welches Bezugssystem ist in der nachfolgenden Abbildung dargestellt? Es sind die eingezeichneten Ebenen in diesem Bezugssystem zu bestimmen!

***

{{10-11}}
***

![image](images/Werkzeugbezugssystem_ohne.png)<!--
style = "width: 60%; margin: 0em 2em;"
-->

<!--
style="font-size: 14px; width: 100%; margin: 0em 1em;"
-->
***Abbildung:*** *Bezugssystem am Beispiel Drehen (Quelle: Klocke 2018)*

***

{{11-12}}
***
> ~~Antwort Frage 6~~
>
> In der Abbildung ist das Werkzeug-Bezugssystem mit den Ebenen: Arbeitsebene, Werkzeug-Bezugsebene und Werkzeug-Rückebene dargestellt.
>
> ![image](images/Werkzeugbezugssystem_mit.png)<!--
style = "width: 75%; margin: 0em 1em;"
-->
>
> <!--
style="font-size: 14px; width: 100%; margin: 0em 1em;"
-->
> ***Abbildung:*** *Werkzeug-Bezugssystem nach DIN 6581 (Quelle: Klocke 2018)*

***


{{12-28}}
***
**Frage 7**

In der nachfolgenden Abbildung sind die Ebenen im Werkzeug-Bezugssystem einzutragen!

***

{{12-13}}
***

![image](images/Ebenen-Werkzeugbezugssystem_ohne.png)<!--
style = "width: 60%; margin: 0em 2em;"
-->

<!--
style="font-size: 14px; width: 100%; margin: 0em 1em;"
-->
***Abbildung:*** *Ebenen im Werkzeug-Bezugssystem nach DIN 6581 (Quelle: Spur 2014)*

***

{{13-14}}
***
> ~~Antwort Frage 7~~
>
> ![image](images/Ebenen-Werkzeugbezugssystem_mit.png)<!--
style = "width: 75%; margin: 0em 1em;"
-->
>
> <!--
style="font-size: 14px; width: 100%; margin: 0em 1em;"
-->
> ***Abbildung:*** *Ebenen im Werkzeug-Bezugssystem nach DIN 6581 (Quelle: Spur 2014)*

***


{{14-28}}
***
**Frage 8**

In der nachfolgenden Abbildung sind die Winkel und Beziehungen in der im Werkzeug-Bezugssystem einzutragen!

***

{{14-15}}
***

![image](images/Beziehungen-WZ-BE_ohne.png)<!--
style = "width: 60%; margin: 0em 2em;"
-->

<!--
style="font-size: 14px; width: 100%; margin: 0em 1em;"
-->
***Abbildung:*** *Winkel und Beziehungen in der Werkzeug-Bezugsebene nach DIN 6581*

***


{{15-16}}
***
> ~~Antwort Frage 8~~
>
> ![image](images/Beziehungen-WZ-BE_mit.png)<!--
style = "width: 75%; margin: 0em 1em;"
-->
>
> <!--
style="font-size: 14px; width: 100%; margin: 0em 1em;"
-->
> ***Abbildung:*** *Winkel und Beziehungen in der Werkzeug-Bezugsebene nach DIN 6581*
>
> <br/>
>
> $v_f \qquad$ Vorschubgeschwindigkeit
>
> $v_c \qquad$ Schnittgeschwindigkeit
>
> $r_\varepsilon \qquad$ Eckenradius
>
> $\kappa_r \qquad$ Werkzeugeinstellwinkel: Winkel zwischen Arbeitsebene $P_f$ und Schneidenebene $P_S$
>
> $\kappa^{'}_r \qquad$ Werkzeugeinstellwinkel der Nebenschneide: Winkel zwischen Arbeitsebene $P_f$  und Schneidenebene der Nebenschneide $P^{'}_S$
>
> $\varepsilon_r \qquad$ Eckenwinkel: Winkel zwischen der Schneidenebene $P_S$ und der Schneidenebene der Nebenschneide $P^{'}_S$

***




{{16-28}}
***
**Frage 9**

Winkel in der Werkzeugschneidenebene?


***

{{17-18}}
***
> ~~Antwort Frage 9~~
>

***



{{18-28}}
***
**Frage 10**

Winkel in der Werkzeugorthogonalebene?


***

{{19-20}}
***
> ~~Antwort Frage 10~~
>

***



{{20-28}}
***
**Frage 11**

Wie können Sie durch die Auswahl der Werkzeugwinkel den Zerspanprozess beeinflussen?

***

{{21-22}}
***

> ~~Antwort Frage 11~~
>
> xxxxxyyyyyzzzz
>
> xxxxxyyyyyzzzz
>
> <!--
style="color: red;"
-->
> Antwort muss noch ausgearbeitet werden!

***

{{22-28}}
***
**Frage 12**

Erläutern Sie die spanungstechnischen Ursachen für die Rauheit einer Werkstückoberfläche am Beispiel Drehen!
***

{{23-24}}
***

> ~~Antwort Frage 12~~
>
> <!--
style="color: red;"
-->
> Antwort muss noch ausgearbeitet werden!

***


{{24-28}}
***
**Frage 13**

Beschreiben Sie das Rauheitsmodell zur rechnerischen Auslegung der Werkstückoberfläch beim Drehen! Gehen Sie auf die maßgebenden Einflussgrößen ein!
***

{{25-26}}
***
> ~~Antwort Frage 13~~
>
> xxxxxyyyyyzzzz
>
> xxxxxyyyyyzzzz
>
> <!--
style="color: red;"
-->
> Antwort muss noch ausgearbeitet werden!

***


{{26-28}}
***
**Frage 14**

Was bedeuten die Begriffe „Schruppdrehen“ und „Schlichtdrehen“? Beschreiben Sie die konventionelle Vorgehensweise für das Drehen eines Passsitzes z.B. 60 h6?

***

{{27-28}}
***
> ~~Antwort Frage 14~~
>
> xxxxxyyyyyzzzz
>
> xxxxxyyyyyzzzz
>
> <!--
style="color: red;"
-->
> Antwort muss noch ausgearbeitet werden!

***


##Spanart, Spanform und Spanformbeeinflussung

{{0-20}}
***
**Frage 1**

Erklären Sie den Begriff Spanart und grenzen Sie diesen gegen die Spanformen ab! Nennen Sie die vier auftretenden Spanarten!

***

{{1-2}}
***

> ~~Antwort Frage 1~~

> * Die **Spanart** hängt vom Verformungsverhalten des Werkstückwerkstoffes ab.
>
> * Sie ist die Spangestalt, die sich in Abhängigkeit von der Spanbildung ergibt, während
>
> * die **Spanform** die Beschreibung der Späne nach Form und Größe und das Ergebnis der Spanbildung ist.
>
> * Man unterscheidet in: **Fließspan, Lamellenspan, Scherspan und Reißspan**.
***

{{2-20}}
***
**Frage 2**

Wie lässt sich die Spanbildung beeinflussen?
***

{{3-4}}
***

> ~~Antwort Frage 2~~
>
> Die Spanbildung lässt sich durch folgende Kriterien beeinflussen:
>
> * Werkstückstoffeigenschaften
>
> * Schnittgeschwindigkeiten
>
> * Spanwinkel
>
> * Spanungsdicken
>

***


{{4-20}}
***
**Frage 3**

Erklären Sie den Begriff Spanform! Wonach werden Spanformen eingeteilt (klassifiziert)? Welche Spanformen werden den Klassen zugeordnet? Beurteilen Sie die Zweckmäßigkeit der einzelnen Spanformen!

***

{{5-6}}
***
> ~~Antwort Frage 3~~
>
> Spanform ist die Beschreibung der Späne nach Form und Größe.
>
> Die Einteilung der Späne nach Spanformklassen erfolgt in:
>
> * ungünstig (1-3): Band-, Wirr-, Flachwendelspäne
>
> * brauchbar (4-5): Schrägwendelspäne, lange Wendelspäne
>
> * gut (6-8): kurze und konische Wendelspäne, Spiralspäne
>
> * brauchbar (9-10): Spanlocken, Bröckelspäne
>
> <br/>
>
> ![image](images/Spanformen_nach-Klocke-2008.png)<!--
style = "width: 75%; "
-->
>
><!--
style="color: red;"
-->
> Antwort muss noch vernünftig ausgearbeitet werden.
>
***


{{6-20}}
***
**Frage 4**

Aus welchen Gründen sind kurzgebrochene Späne erwünscht?

***

{{7-8}}
***
> ~~Antwort Frage 4~~
>
> kurzgebrochene Späne:
>
> * Sicherheitsaspekt (Personal, Maschine, Werkzeug, Werkstück)
>
> * Kleiner Raumbedarf/Schüttdichte; ausgedrückt durch kleine Spanraumzahl
>
> * günstigerer Spanabtransport als lange Späne
>
> <!--
style="color: red;"
-->
> Antwort muss noch vernünftig ausgearbeitet werden.

***

{{8-20}}
***
**Frage 5**

Erläutern Sie die Funktion einer Spanformstufe!

***

{{9-10}}
***
> ~~Antwort Frage 5~~
>
><!--
style="color: red;"
-->
> Antwort muss noch vernünftig ausgearbeitet werden.
>
***



{{10-20}}
***
**Frage 6**

Was drückt die Spanraumzahl R aus und welche Bedeutung hat diese?

***
{{11-12}}
***
> ~~Antwort Frage 6~~
>
> Die Spanraumzahl R drückt das Verhältnis von Spänevolumen zu Werkstoffvolumen aus.
>
> $\bold {R=\frac{Q_{SP}}{Q_W}}$
>
> mit
>
><!--
style="font-size: 16px; width: 660px; margin: 0.25em 1;"
-->
> $\quad R\qquad Spanraumzahl\quad [-]$
>
> $\quad Q_{SP}\quad Spänevolumen\quad [mm^3 / min]$
>
> $\quad Q_W\quad WSt-Volumen\quad [mm^3 / min]$
>
> <br/>
>
> Günstig: R = 5…25
>
> <!--
style="color: red;"
-->
> Antwort muss noch vernünftig ausgearbeitet werden.

***

{{12-20}}
***
**Frage 7**

Welcher Zusammenhang besteht zwischen Zeitspanungsvolumen (Volumenrate) und Spanraumzahl?
***

{{13-14}}
***
> ~~Antwort Frage 7~~
>
> <!--
style="color: red;"
-->
> *Die Antwort auf diese Frage muss noch ausgearbeitet werden*

***


{{14-20}}
***
**Frage 8**

Welche Maßnahmen einer Spanformbeeinflussung können beim Drehen ergriffen werden? Wie wirken sich diese positiv oder negativ auf die Spanform aus?

***

{{15-16}}
***
> ~~Antwort Frage 8~~
>
> Möglichkeiten der Spanformbeeinflussung:
>
> * Schnittwerte und Prozessparameter (vc, f, ap)
>
> * Werkzeuggeometrie (Spanwinkel und Einstellwinkel, Eckenradius)
>
> * Spanleitstufen (Beeinflussung Fließrichtung)
>
> * Werkstoff (Gehalt an C, S, P, Pb) und Wärmebehandlung (Korngröße, Homogenität)
>
> * Schneidstoff und dessen Beschichtung (Reibungsverhalten)
>
> * Kühlschmierstoff (Reibung und Temperaturbeeinflussung)
>
> <!--
style="color: red;"
-->
> *Der erste Teil der Frage muss noch überarbeitet werden*
>
> <!--
style="color: red;"
-->
> *Der zweite Teil der Frage muss noch ausgearbeitet werden*
***


{{16-20}}
***
**Frage 9**

Wie lässt sich erklären, dass bei großen Spanungsdicken günstigere Spanformen auftreten als bei geringen Spanungsdicken?
***

{{17-18}}
***
> ~~Antwort Frage 9~~
>
> <!--
style="color: red;"
-->
> *Die Antwort auf diese Frage muss noch ausgearbeitet werden*

***


{{18-20}}
***
**Frage 10**

Welche Möglichkeit besteht, unter Anwendung desselben Werkzeugs die Spanform zu verbessern?
***

{{19-20}}
***
> ~~Antwort Frage 10:~~
>
> <!--
style="color: red;"
-->
> Antwort muss noch ausgearbeitet werden.
***


##Systemgrößen WSWW+H am Beispiel Drehen

{{0-16}}
***
**Frage 1**

Der Zerspanprozess als System: Was ist unter System zu verstehen? Warum ist eine Systembetrachtung sinnvoll und welche Systemkomponenten lassen sich am Beispiel Drehprozess zuordnen? Was ist unter System-, Stell-, Prozess- und Wirkgrößen zu verstehen?

***

{{1-2}}
***
> ~~Antwort Frage 1~~
>
> <!--
style="color: red;"
-->
> *Die Antwort auf diese Frage muss noch ausgearbeitet werden*
***


{{2-16}}
***
**Frage 2**

In der nachfolgenden Abbildung sind die Komponeten der Drehmaschine EMCO Emcomat E300 zu benennen.

***

{{2-3}}
***

![image](images/Aufbau-EMCO-E300_ohne.png)<!--
style = "width: 60%; "
-->

***

{{3-4}}
***
> ~~Antwort Frage 2~~
>
> <!--
style="color: red;"
-->
> *Sollten noch mehr Komponenten hinzugefügt werden?*

> ![image](images/Aufbau-EMCO-E300_mit.png)<!--
style = "width: 60%; "
-->

***


{{4-16}}
***
**Frage 3**

Welche Anforderungen werden an eine moderne Drehmaschine gestellt?

***

{{5-6}}
***
> ~~Antwort Frage 3~~
>
> <!--
style="color: red;"
-->
> *Die Antwort auf diese Frage muss noch ausgearbeitet werden*

***


{{6-16}}
***
**Frage 4**

Fragen zur Werkstückspannung

<!--
style="color: red;"
-->
*Die Frage muss noch ausgearbeitet werden*

Anforderungen an Werkstückspannmittel; Was gibt es für Werkstückspannmittel für die Drehbearbeitung? Bewertung der Spannsituation bei der Drehbearbeitung?

Welche wesentlichen Anforderungen werden an Werkstückaufnahmen und Spannmittel gestellt? Nennen Sie jeweils drei Beispiele für die Werkstück- und Werkzeugspannung beim Drehen!

***

{{7-8}}
***
> ~~Antwort Frage 4~~
>
> <!--
style="color: red;"
-->
> *Die Antwort auf diese Frage muss noch ausgearbeitet werden*

***


{{8-16}}
***
**Frage 5**

Fragen zur Werkzeugaufnahme, Werkzeugspannung

<!--
style="color: red;"
-->
*Die Frage muss noch ausgearbeitet werden*

Was gibt es für Spannmittlel und Aufnahmen für Werkzeuge? Vergleich, Bewertung...

***

{{9-10}}
***
> ~~Antwort Frage 5~~
>
> <!--
style="color: red;"
-->
> *Die Antwort auf diese Frage muss noch ausgearbeitet werden*

***



{{10-16}}
***
**Frage 6**

Fragen zu Schneidstoffen

<!--
style="color: red;"
-->
*Die Frage muss noch ausgearbeitet werden*

Anforderungen an moderne Schneidstoffe?; Welche wesentlichen Schneidstoffe kommen in der Zerspantechnik zum Einsatz und was sind jeweilige Vorzüge und Grenzen? Welche Schneidstoffgruppe hat die größte Bedeutung in der Zerspantechnik und warum?; Schneidkeramik und deren Einsatzgebiete; CBN: Vorteile, Nachteile, Einsatzgebiete; Beschichtung von Zerspanwerkzeugen? Schneidstoffe und deren Eigenschaften!

***

{{11-12}}
***
> ~~Antwort Frage 6~~
>
> <!--
style="color: red;"
-->
> *Die Antwort auf diese Frage muss noch ausgearbeitet werden*

***


{{12-16}}
***
**Frage 7**

Fragen zur Zerspanbarkeit von Werkstoffen
Wie wirken sich die wichtigsten Eisenbegleiter (Legierungsbestandteile) auf die Spanformung von Stahl aus?

<!--
style="color: red;"
-->
*Die Frage muss noch ausgearbeitet werden*

***

{{13-14}}
***
> ~~Antwort Frage 7~~
>
> <!--
style="color: red;"
-->
> *Die Antwort auf diese Frage muss noch ausgearbeitet werden*

***



{{14-16}}
***
**Frage 8**

Fragen zum Kühlschmierstoff

<!--
style="color: red;"
-->
*Die Frage muss noch ausgearbeitet werden*

zum Beispiel:

Welche wesentlichen Aufgaben werden an Kühlschmierstoffe gestellt?
Wie werden Kühlschmierstoffe eingeteilt?
Beschreiben Sie die Motivation zur Trockenbearbeitung! Was ist bei der Umstellung auf die Trockenbearbeitung zu beachten?
Was verstehen Sie unter Mindermengenschmierung und Minimalmengen-kühlschmierung?

***

{{15-16}}
***
> ~~Antwort Frage 8~~
>
> <!--
style="color: red;"
-->
> *Die Antwort auf diese Frage muss noch ausgearbeitet werden*

***


##Zerspankraft, Leistung, Arbeit und Energie

{{0-18}}
***
**Frage 1**

Wozu benötigt der Ingenieur Kenntnisse über die Zerspankräfte und Leistungen?

***

{{1-2}}
***
> ~~Antwort Frage 1:~~
>
> **Die Zerspankraft wird benötigt für:**
>
> * Konstruktion und Auslegung von WZM (Dimensionierung Grundgestell, Anbauten, Maschinenantriebe)
>
> * Festlegung der Schnittbedingungen / Schneidstoffauswahl
>
> * notwendigen Werkstück- und Werkzeugspannungen
>
> * Bestimmung des Energie- und Leistungsbedarfs
>
> * erzielbare Genauigkeiten
>
> * Analyse der Zerspanvorgänge (z.B. Verformungen von WSt und WZ)
>
> * Beurteilung der Zerspanbarkeit von Werkstoffen
>
> * Erkennen von WZ-Verschleiß (Prozess- und Qualitätsüberwachung)
>
> * Optimierung der Werkzeuges
>

***


{{2-18}}
***
**Frage 2**

In welche Komponenten wird die Zerspankraft zerlegt?

***

{{2-3}}
***
![image](images/Zerspankraftkomponenten-leer.png)<!--
style = "width: 60%; "
-->

<!--
style="font-size: 14px; width: 100%; margin: 0.25em 0;"
-->
***Abbildung:*** *Zerspankraft und ihre Komponenten beim Drehen nach DIN 6585 (Spur2014)*

***

{{3-4}}
***
> ~~Antwort Frage 2:~~
>
> <br/>
>
> ![image](images/Zerspankraftkomponenten.png)<!--
style = "width: 80%; "
-->
>
> <!--
style="font-size: 14px; width: 100%; margin: 0.25em 0;"
-->
> ***Abbildung:*** *Zerspankraft und ihre Komponenten beim Drehen nach DIN 6585 (Spur2014)*

***

{{4-18}}
***
**Frage 3**

Welche Haupteinflüsse gehen grundlegend in das Zerspankraftmodell ein (einfache Grundgleichung nach Kienzle/Victor) und welche Einflüsse können über Korrekturfaktoren berücksichtigt werden (erweiterte oder allgemeine Grundgleichung nach Kienzle/Victor)?
***

{{5-6}}
***
> ~~Antwort Frage 3:~~
>
> **Zerspanungsquerschnitt**
>
> * Schnitttiefe $a_p$ x Vorschub $f$ bzw. Spanungsbreite $b$ x Spanungsdicke $h$
>
> * Die Form des Spanungsquerschnittes ist vom Werkzeugeinstellwinkel $\kappa_r$ abhängig. Aus diesem Grund ist es zweckmäßig, mit der Spanungsdicke und Spanungsbreite zu rechnen.
>
> **Werkstoff**
>
> * Der Werkstoffeinfluss kommt in der spezifischen Zerspankraft $k_c$ zum Ausdruck. Der Werkstoff mit seinen physikalischen Eigenschaften ist bestimmend für dessen Zerspanbarkeit. Die spezifische Zerspankraft gibt an, wieviel Arbeit (Energie) aufgebracht werden muss, um einen Kubikmillimeter eines bestimmten Werkstoffes zu zerspanen. Eine andere Ausdrucksweise lautet: Wieviel Kraft muss aufgebracht werden, um einen Spanungsquerschnitt von $h = 1 mm$ und $b = 1 mm$ zu zerspanen. Die spezifische Zersponkraft ist selbst für einen bestimmten Werkstoff keine konstante Größe. Sie ist zusätzlich von der Technologie (Spanungsdicke, Schnittgeschwindigkeit,...), von der Werkzeuggeometrie, vom Verschleißzustand des Werkzeuges, vom Kühlschmierstoff und weiteren Einflüssen abhängig. Untersuchungen haben gezeigt, dass die spezifische Zerspankraft $k_c$ kaum von der Spanungsbreite $b$, sondern fast ausschließlich von der Spanungsdicke $h$ abhängt
>
> **Werkzeuggeometrie**
>
> * Grundwerte für die spezifische Zerspankraft gelten immer nur für konkrete Werkzeuggeometrien. Darin enthalten sind: Spanwinkel $\gamma$, Freiwinkel $\alpha$, Werkzeug-Einstellwinkel $\kappa_r$, Neigungswinkel $\lambda_s$ und Eckenradius $r_{\varepsilon}$.
>
> * *Spanwinkel:* Ein positiver Spanwinkel führt zu geringeren Schnittkräften, da mit steigendem positiven Spanwinkel der Span leichter über die Spanfläche gleitet. Die spezifische Zerspanenergie für das abheben und trennen eines Span verringert sich. Bei ansonsten konstanten Bedingungen, sinken die spezifische Zerspankraft und demzufolge auch die Schnittkraft.
>
> ![image](images/Einfluss-Span-und-Neigungswinkel.png)<!--
style = "width: 50%; margin: 0em 5em;"
-->
>
> <!--
style="font-size: 14px; margin: 1em 5em;"
-->
> ***Abbildung:*** *Einfluss des Span- / Neigungswinkels auf die Zerspankraftkomponenten (Quelle: Klocke, König)*
>
> * Die Werkzeuggeometrie wird über einen Korrekturfaktor berücksichtigt.
>
> **Schnittgeschwindigkeit**
>
> * Die Schnittgeschwindigkeit geht nicht direkt in die Berechnung der Zerspankraft ein. Sie wird ebenso über einen Korrekturfaktor berücksichtigt.
>
> * Der Einfluss der Schnittgeschwindigkeit hat zwei Ursachen: Mit zunehmender Schnittgeschwindigkeit sinkt die spezifische Zerspankraft. Mit steigender Schnittgeschwindigkeit nimmt die Temperatur zu. Der Widerstand gegen das Trennen eines Spanes sinkt. Dies führt zu einer Reduzierung der Schnittkraft.
>
> * Im Bereich geringer Schnittgeschwindigkeiten kann es zur Aufbauschneidenbildung kommen. Ein dadurch veränderter Spanwinkel bewirkt eine Veränderung der Schnittkraft.
>
> **Kühlschmierstoff**
>
> * Der Einfluss des Kühlschmierstoffes beruht auf der Veränderung des Reibungszustandes im Eingriff (an der Spanfläche) zwischen Werkzeug und Werkstück in Abhängigkeit der Art der Kühlschmierung. Öle haben eine höhere Schmierwirkung als Kühlemulsion. Die Reibung wird stärker verringert und die Schnittkraft sinkt.

***


{{6-18}}
***
**Frage 4**

Wie lautet die allgemeine Grundgleichung für die Schnittkraft $ F_c $ nach KIENZLE/VICTOR?

***

{{7-8}}
***
> ~~Antwort Frage 4:~~
>
> $\bold{F_c = k_{c1.1} \cdot b \cdot h^{1-m_c} \cdot K_{3c} \cdot K_{4c}} $
>
> * $ F_c $ : Schnittkraft in N
>
> * $ k_{c1.1} $ : Spezifische Schnittkraft $ k_{c1.1} $ in $ \frac{N}{mm^2}$ - gibt die auf $ b = 1 mm $ und $ h = 1 mm $ bezogene Schnittkraft an
>
> * $ b $ : Spanungsbreite in mm
>
> * $ h $ : Spanungsdicke in mm
>
> * $ m_c $ : Exponent $ m_c = tan \alpha $ bezeichnet Geradensteigung $ k_c = f (h) $
>
> * $ K_{3c} $ : Korrekturfaktor zur Berücksichtigung von Einflüssen wie: Spanwinkel des Werkzeuges, Verschleiß am Werkzeug, Schnittgeschwindigkeit, Schneidstoff, Kühlschmierstoff...
>
> * $ K_{4c} $ : Korrekturfaktor zur Berücksichtigung des Vorschubrichtungswinkels in Abhängigkeit des Fertigungsverfahrens. Beim Drehen beträgt der Vorschubrichtungswinkel $\phi = 90 \degree$.

***


{{8-18}}
***
**Frage 5**

Skizzieren Sie den Einfluss von:

Vorschub $f$, Schnitttiefe $a_p$ , Schnittgeschwindigkeit $v_c$ und Werkzeug-Einstellwinkel $\kappa_r$ auf die Zerspankraftkomponenten $F_c$, $F_f$ und $F_p$!
***

{{8-9}}
***
![image](images/Einfluss-vc_ap_f_kr_auf-spez-Schnittkraft-ohne.png)<!--
style = "width: 75%; margin: 0em 5em;"
-->

<!--
style="font-size: 14px; margin: 1em 0em;"
-->
***Abbildung:*** *Einfluss von Vorschub, Schnitttiefe, Schnittgeschwindigkeit und Einstellwinkel auf die Zerspankraftkomponenten*
***


{{9-10}}
***
> ~~Antwort Frage 5:~~
>
> ![image](images/Einfluss-vc_ap_f_kr_auf-spez-Schnittkraft-mit.png)<!--
style = "width: 100%; "
-->
>
> <!--
style="font-size: 14px; width: 100%; margin: 1em 0em;"
-->
> ***Abbildung:*** *Einfluss von Vorschub, Schnitttiefe, Schnittgeschwindigkeit und Einstellwinkel auf die Zerspankraftkomponenten (Quelle: Klocke, König)*

***


{{10-18}}
***
**Frage 6**

Erläutern Sie die Zerspankraftmessung mit piezoelektrischen Kraftaufnehmern!

<!--
style="color: red;"
-->
*Die Frage muss noch überarbeitet werden!*

***


{{11-12}}
***
> ~~Antwort Frage 6:~~
>
> <!--
style="color: red;"
-->
>  *Die Antwort muss noch ausgearbeitet werden!*


***


{{12-18}}
***
**Frage 7**

Skizzieren und Erläutern Sie den Einfluss der Spanungstiefe h auf die spezifische Zerspanenergie!

***

{{13-14}}
***
> ~~Antwort Frage 7:~~
>
> <!--
style="color: red;"
-->
>  *Die Antwort muss noch ausgearbeitet werden!*

***


{{14-18}}
***
**Frage 8**

Wozu dient die Ermittlung der Schnittleistung und wie erfolgt diese?

***

{{15-16}}
***
> ~~Antwort Frage 8:~~
>
> **Leistung beim Spanen**
>
> Leistungsermittlung dient zur:
>
> * Auslegung der Antriebe der WZM
>
> * Beantwortung der Frage, welche Bearbeitung auf welcher Maschine in der Produktion ausgeführt werden kann
>
> * Allgemeine Berechnung der Zerspanleistung: Produkt der jeweiligen Geschwindigkeitskomponente und der in ihrer Richtung wirkenden Kraftkomponente:
>
> <!--
style="color: red;"
-->
> *Die Antwort muss noch weiter ausgearbeitet werden!*
***



{{16-18}}
***
**Frage 9**

Warum ist die Vorschubleistung wesentlich kleiner als die Schnittleistung?

***

{{17-18}}
***
> ~~Antwort Frage 9:~~
>
> <!--
style="color: red;"
-->
>  *Die Antwort muss noch ausgearbeitet werden!*

***



##Verschleiß

{{0-14}}
***
**Frage 1**

Welche wesentlichen Verschleißmechanismen treten beim Spanen auf? Was beeinflusst den Verschleiß!

***

{{1-2}}
***
> ~~Antwort Frage 1:~~
>
> Verschleißmechanismen:
>
> * Mechanischer Verschleiß / Abrasion
>
> * Diffusion
>
> * Adhäsionsverschleiß
>
> * Oxidation
>
> * Plastische Verformung  und Rissbildung
>
> <!--
style="color: red;"
-->
>  *Die Antwort muss noch ausgearbeitet werden!*

***

{{2-14}}
***
**Frage 2**

Was ist unter dem Begriff Aufbauschneide zu verstehen und welche Auswirkungen hat diese auf das Arbeitsergebnis am Werkstück und auf das Werkzeug?

***

{{3-4}}
***
> ~~Antwort Frage 2:~~
>
> Begriff Aufbauschneide:
>
> * Die Aufbauschneide ist eine Ansammlung kleinster Werkstoffteilchen des bearbeiteten Materials, die sich durch Pressschweißung und Klebeerscheinungen aufbaut.
>
> * Kann bei der Fließspanbildung aufkommen.
>
> * Dabei lagern sich Werkstoffpartikel auf der Spanfläche und an der Schneidkante ab.
>
> * Diese Partikel sind so stark verformt, kaltverfestigt und deutlich härter als der Grundwerkstoff, sodass sie die Funktion der Schneide übernehmen können.
>
> * Wird die Aufbauschneide instabil, gleitet sie ab und wird in die Werkstückrandschicht eingedrückt.
>
> * Aufbauschneidenbildung ist i. d. R. unerwünscht
>
> ![image](images/Aufbauschneidenbildg.png)<!--
style = "width: 50%; margin: 0em 2em; "
-->
>
> <!--
style = "font-size: 14px; width: 100%; margin: 0em 2em; "
-->
> ***Abbildung:*** *Aufbauschneidenbildung*
>
> <br/>
> Das folgende Video zeigt die Aufbauschneidenbildung bei einer Drehbearbeitung. Hier wird zudem die Gefügeveränderung des Werkstückwerkstoffes sichtbar.
>
> <br/>
>
> <!--
style = "width: 50%; margin: 0em 2em; "
-->
> <iframe width="540" height="305" src="https://www.youtube.com/embed/mRuSYQ5Npek" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
>
> <!--
style = "font-size: 14px; width: 100%; margin: 1em 2em; "
-->
> ***Video:*** *Aufbauschneidenbildung bei der Drehbearbeitung (Quelle: Werkstatt + Betrieb)*
>
> <br/>
> Auswirkung der Aufbauschneide:
>
> * Erleichtern i.d.R. die Spanbildung (geringere Kräfte)
>
> * fortlaufende Veränderung der Schneidkeilgeometrie $\implies$ führt zu Maßfehlern am Werkstück, die Werkzeugeinstellung muss korrigiert werden.
>
> * Entstehung periodischer Kraftschwankungen
>
> * Abwandern bei gewisser Größe und z.T. Mitreißen von Werkzeug-Partikeln
>
> * adhäsiver WZ-Verschleiß
>
> * Einlagern von harten, kaltverfestigten Partikeln in entstehende Oberfläche $\implies$ schlechte Werkstückoberflächen
>
***

{{4-14}}
***
**Frage 3**

Was sind die wesentlichen Voraussetzungen zur Aufbauschneidenbildung und durch welche Maßnahmen kann sie vermieden werden? Warum treten Aufbauschneiden nur im Fließspanbereich auf?
***

{{5-6}}
***
> ~~Antwort Frage 3~~
>
> Voraussetzungen zur Aufbauschneidenbildung
>
> * Fähigkeit zur Kaltverfestigung des Werkstückwerkfstoffes
>
> * stabile, weitgehend stationäre Spanbildung
>
> * eine Stauzone im Stofffluss vor der Schneidkante sowie
>
> * ausreichend geringe Temperaturen in der Spanbildungszone, die keine Rekristallisation zulassen
>
> <br/>
> Gegenmaßnahmen
>
> * Erhöhung der Schnittgeschwindigkeit
>
> * Einsatz von beschichteten Werkstoffen
>
> * Erhöhung des Einsatzes von Kühlschmierstoff
>
> * Vergrößerung des Spanungsquerschnittes
>
> <br/>
> Aufbauschneiden treten nur im Fließspanbereich auf, weil
>
> <!--
style="color: red;"
-->
>  *Die Antwort muss noch ergänzt werden!*
***



{{6-14}}
***
**Frage 4**

Wie wirkt sich Kolkverschleiß, wie Schneidkantenverschleiß auf die Spanformen aus?
***

{{7-8}}
***
> ~~Antwort Frage 4~~
>
> xxxxxyyyyyzzzz
>
> xxxxxyyyyyzzzz
>
> <!--
style="color: red;"
-->
>  *Die Antwort muss noch ausgearbeitet werden!*

***



{{8-14}}
***
**Frage 5**

Was ist unter dem Begriff Standzeit eines Werkzeugs zu verstehen? Welche Größen haben wesentlichen Einfluss auf die Standzeit?
***

{{9-10}}
***
> ~~Antwort Frage 5~~
>
> <!--

style="color: red;"
-->
>  *Die Antwort muss noch ausgearbeitet werden!*

***


{{10-14}}
***
**Frage 6**

Erläutern Sie an einem einfachen Drehversuch die prinzipielle Herleitung der einfachen Standzeitfunktion nach Taylor!
***

{{11-12}}
***
> ~~Antwort Frage 6~~
>
> <!--
style="color: red;"
-->
>  *Die Antwort muss noch ausgearbeitet werden!*

***


{{12-14}}
***
**Frage 7**

Nennen Sie die drei wesentlichen Stellgrößen für die Zerspanung mit geometrisch bestimmter Schneide und ordnen Sie deren Einfluss auf die Standzeit zu! Was verstehen Sie unter kosten- bzw. zeitoptimaler Standzeit?
***

{{13-14}}
***
> ~~Antwort Frage 7~~
>
> <!--
style="color: red;"
-->
>  *Die Antwort muss noch ausgearbeitet werden!*

***


##Quiz

<!--
style="font-size: 16px;"
-->
**Wie groß ist die Richtwertstandzeit einer Wendeschneidplatte aus Hartmetall bei der Drehbearbeitung?**

[(X)] ca. 15 Minuten
[( )] ca. 180 Minuten
[( )] ca. 60 Minuten

<br/>
<br/>

<!--
style="font-size: 16px;"
-->
**Was sind *~~keine~~* Spanformen?**

[[ ]] Wirrspan
[[ ]] Flachwendelspan
[[ ]] Spiralspan
[[X]] Fließspan
[[ ]] Bandspan
[[ ]] Bröckelspan
[[ ]] Wendelspanstücke
[[X]] Lamellenspan
[[ ]] Spiralspanstücke
[[ ]] Schrägwendelspan
[[X]] Reißspan
[[ ]] Spiralwendelspan
[[X]] Scherspan
[[ ]] Spanlocken
[[ ]] langer zylindrischer Wendelspan
***
Fließspan, Lamellenspan, Scherspan und Reißspan sind Spanarten, die sich in Abhängigkeit der Spanbildung ergeben.
Alle anderen beschreiben die Form und Größe eines Spans.

***

<br/>
<br/>

<!--
style="font-size: 16px;"
-->
**Wie groß ist der Schnittgeschwindigkeitsbereich (Richtwert) für das CNC-Drehen von Stahl mit Hartmetall?**

[( )] 20 - 100 m/s
[(X)] 250 - 500 m/min
[( )] 2000 - 4000 mm/min

<br/>
<br/>

<!--
style="font-size: 16px;"
-->
**Was ist ~~*kein*~~ Schneidstoff?**

[( )] CBN
[( )] PKD
[(X)] BKT
***
CBN: Kubisch kristallines Bornitrid

PKD: Polykristalliner Diamant
***

<br/>
<br/>

<!--
style="font-size: 16px;"
-->
**Was sind Werkzeugaufnahmen (Werkzeugschnittstellen) für Drehwerkzeuge**

[[X]] Polygonhalter ("Capto")
[[ ]] Weldon-Aufnahme
[[ ]] Morsekegel
[[X]] VDI-Aufnahme
[[X]] Schnellwechselhalter
[[ ]] Steilkegel
***
Weldon-Aufnahme, Morsekegel und Steilkegel sind Werkzeugaufnahmen (Werkzeugschnittstellen) für Bohr- und Fräsewerkzeuge.
***

<br/>
<br/>


<!--
style="font-size: 16px;"
-->
**Wie lautet die allgemeine Grundgleichung für die Schnittkraft $\ F_c $ nach KIENZLE/VICTOR?**

[( )] $ F_c = k_{c1.1} \cdot b \cdot h^{1+m_c^2} \cdot K_{3c} \cdot K_{4c} $
[( )] $ F_c = b \cdot (\frac{f}{sin \kappa_r})^2 \cdot k_{c1.1} \cdot K_{3c} \cdot K_{4c} $
[(X)] $ F_c = k_{c1.1} \cdot b \cdot h^{1-m_c} \cdot K_{3c} \cdot K_{4c} $

<br/>
<br/>


<!--
style="font-size: 16px;"
-->
**Welches Modell der Zerspantechnik gibt es?**

[[X]] Zerspankraftmodell
[[ ]] Spandickenmodell
[[ ]] Zerspanungsleistungsmodell
[[X]] Verschleiß-Standzeit-Modell
[[X]] Oberflächenmodell
[[ ]] Zeitspanungsvolumenmodell
[[ ]] Spanraummodell
***
<!--
style="color: red;"
-->
Erklärung einfügen!
***

<br/>
<br/>


##Berechnungsaufgaben

{{0-1}}
***

<!--
style="font-size: 24px;"
-->
**Aufgabe 1**

Ein Absatz an einer Welle aus dem Einsatzstahl 16MnCr5 soll auf d = 45mm vorgedreht werden. Folgende Eingangsgrößen sind bekannt:
* Schnnittgeschwindigkeit $\ v_c = 300 \space m/min $ (WSP Hartmetall)
* Schnitttiefe $\ a_p = 3 \space mm $
* Vorschub $\ f = 0,3 \space mm $
* spezifische Schnittkraft $\ k_c = 2350 \space N/mm^2 $

<br/>

![image](images/Berechnungsaufgabe-1.png)

<br/>

**Wie groß ist die Drehzahl n in U/min?** *(keine Nachkommastelle)*
[[2122]]
***
$ v_c = \pi \cdot d \cdot n $

$\ n = \frac{v_c}{\pi \cdot d} = \frac{300 \space \frac{m}{min}}{\pi \cdot 0,045 \space m} = 2122 \space min^{-1} $
***

<br/>

**Vorschubgeschwindigkeit $v_f$ in mm/min?** *(eine Nachkommastelle)*
[[636,6]]
***
$\ v_f = f \cdot n = 0,3 \space mm \cdot 2122 \space min^{-1}  = 636,6 \space \frac{mm}{min} $
***

<br/>

**Wie lange ist die Hauptzeit $t_h$ in Sekunden bei einer Absatzlänge von L = 80mm?** *(eine Nachkommastelle)*
[[7,5]]
***
$\ t_h = \frac{L}{v_f} = \frac{80 \space mm}{636,6 \space \frac{mm}{min}} = 0,1257 \space min = 7,5 \space s $
***

<br/>


**Wie groß ist die Schnittkraft Fc in N?** *(keine Nachkommastelle)*
[[2115]]
***
$\ F_c = A \cdot k_c =  b \cdot h \cdot k_c = a_p \cdot f \cdot k_c = 0,3 \space mm \cdot 3 \space mm \cdot 2350 \frac{N}{mm^2} = 2115 \space N $
***

<br/>

**Wie groß ist die Schnittleistung Pc in W für diesen Zerspanprozess?** *(keine Nachkommastelle)*
[[10575]]
***
$\ P_c = F_c \cdot v_c = 2115 \space N \cdot 5 \space \frac{m}{s} = 10575 \space W $
***

***


{{1-2}}
***

<!--
style="font-size: 24px;"
-->
**Aufgabe 2**

Für eine Längsdrehoperation ist die Antriebsleistung einer Drehmaschine nachzurechnen! Folgende Angaben sind bekannt:

* Durchmesser der Welle $\ d_{Welle} = 80 \space mm $
* Schnitttiefe $\ a_p = 6 \space mm $
* Vorschub je Umdrehung $\ f = 0,5 \space mm $
* Schnittgeschwindigkeit $\ v_c = 275 \space m/min $
* spezifische Schnittkraft $\ k_c = 2350 \space N/mm^2 $
* Wirkungsgrad $\eta = 0,85$

Ist eine Drehmaschine mit einer Antriebsleistung von Pa = 40 kW ausreichend? Begründen Sie Ihre Entscheidung anhand einer Rechnung!

<br/>

**Wie groß ist der Spanungsquerschnitt A in mm²?** *(keine Nachkommastelle)*
[[3]]
***
$\ A = a_p \cdot f = 6 \space mm \cdot 0,5 \space mm = 3 \space mm $
***

<br/>

**Wie groß ist die Schnittkraft Fc in N** *(keine Nachkommastelle)*
[[7050]]
***
$\ F_c = A \cdot k_c = 3 \space mm^2 \cdot 2350 \space \frac{N}{mm^2} = 7050 \space N $
***

<br/>

**Wie groß ist die Schnittleistung Pc in W** *(keine Nachkommastelle)*
[[32312]]
***
$\ P_c = F_c \cdot v_c = 7050 \space N \cdot 4,583 \space \frac{m}{s} = 32312 \space W $
***

<br/>

**Wie groß ist die erforderliche Antriebsleistung Pa in W?** *(keine Nachkommastelle)*
[[38014]]
***
$\ P_a = \frac{P_c}{\eta} = \frac{32312 \space W}{0,85} = 38014 \space W $
***

<br/>

**Ist die Antriebsleistung der Drehmaschine (Pa = 40 kW) ausreichend?**
[(X)] ja
[( )] nein
***
Ja, die Antriebsleistung der Drehmaschine ist ausreichend!
***

***


{{2-3}}
***

<!--
style="font-size: 24px;"
-->
**Aufgabe 3**

Welchen Wert darf der Vorschub f in mm bei einer Längsdrehoperation nicht überschreiten, wenn die Wendeschneidplatte einen Eckenradius von

a) $r_\varepsilon = 0,8\space mm$ <br/>
b) $r_\varepsilon = 1,2\space mm$

aufweist und die gemittelte Rautiefe

a) $Rz\le12\space \mu m$ <br/>
b) $Rz\le6,3\space \mu m$

sein soll? Der Vorschubwert ist auf die zweite Nachkommastelle zu runden!

<br/>

**Antwort a)**
[[0,28]]
***
$f\approx\sqrt{8\space\cdot\space Rz_{theor}\space\cdot\space r_\varepsilon} \space\implies\space f\le\sqrt{8\space\cdot\space 0,012\space mm\space\cdot\space 0,8\space mm} $
***

<br/>

**Antwort b)**
[[0,25]]
***
$f\approx\sqrt{8\space\cdot\space Rz_{theor}\space\cdot\space r_\varepsilon} \space\implies\space f\le\sqrt{8\space\cdot\space 0,0063\space mm\space\cdot\space 1,2\space mm}$
***

***

{{3-4}}
***

<!--
style="font-size: 24px;"
-->
**Aufgabe 4**

Nach einer Eingriffszeit von 15 min soll das Standzeitende einer Hartmetallschneide eines Drehwerkzeuges erreicht werden. Technologische Versuche für den vorliegenden Werkstoff eines Untersuchungswerkstückes haben die folgende Abhängigkeit ergeben: <br/>

Versuch 1: $\qquad v_{c1}\space = \space 320 \space m/min \qquad T_1\space=\space 0,5\space \space h$ <br/>
Versuch 2: $\qquad v_{c2}\space = \space 7 \quad\space m/s \space\quad \qquad T_2\space=\space 10\quad min$

Welche Schnittgeschwindigkeit $v_c$ in **m/min** ist einzustellen, damit nach 15 min das Standzeitende erreicht wird und das Werkzeug gewechselt werden kann? Der Wert ist ohne Nachkommastelle anzugeben!

Gegebene Formel: $\qquad v_c\space=\space C_T\space \cdot \space T^\frac{1}{k}$

mit

$\ \qquad \quad C_T: Schnittgeschwindigkeit\space bei\space T\space =\space 1\space min$

$\ \qquad \quad \space T: \space Standzeit$

$\ \qquad \quad \space k: \space Steigung\space der\space Standzeitgeraden$


<br/>
**Schnittgeschwindigkeit $v_c$ in m/min**
[[380]]
***
|Nr.|$v_c\space [m/min]$|$T\space [min]$ |$log\space v_c$ | $log\space T$ |
|:---:|:---:|:---:|:---:|:---:|
|**1**|320|30|2,505|1,477|
|**2**|420|10|2,623|1,000|

<br/>

* $k\space =\space \frac{log\space T_1\space - \space log\space T_2}{log\space v_{c1}\space - \space log\space v_{c2}} \implies k\space =\space \frac{1,477\space -\space 1}{2,505\space -\space 2,623}\space =\space -4,040 \qquad \frac{1}{k}\space =\space -0,247$
* $C_T\space =\space \frac{v_c}{T^\frac{1}{k}} \qquad\quad\implies C_T\space =\space \frac{320\space m/min}{30^{-0,247}}\space \approx\space 741\space m/min$
* $v_c\space =\space C_T\space \cdot\space T^\frac{1}{k} \quad\implies v_c\space =\space 741\space m/min\space \cdot\space 15^{-0,247}\space \approx\space \space 380\space m/min$

<br/>
~~Erläuterung zur Herleitung der Gleichungen~~

Zunächst sind folgende zwei Gleichungen aufzustellen:

$C_T\space=\space \frac{v_{c1}}{T_1^{\frac{1}{k}}} \qquad bzw. \qquad C_T\space=\space \frac{v_{c2}}{T_2^{\frac{1}{k}}}$

gleichzusetzen:

$\implies \quad \frac{v_{c1}}{T_1^{\frac{1}{k}}}\space=\space \frac{v_{c2}}{T_2^{\frac{1}{k}}}$

und zu logarithmieren:

$\implies \quad log\space v_{c1}\space - \space \frac{1}{k}\space log\space T_1\space =\space log\space v_{c2}\space -\space \frac{1}{k}\space log\space T_2$

Nach Umstellen der Gleichung erhält man:

$k\space =\space \frac{log\space T_1\space - \space log\space T_2}{log\space v_{c1}\space - \space log\space v_{c2}}$
***

***

{{4-5}}
***

<!--
style="font-size: 24px;"
-->
**Aufgabe 5**

Für eine Werkstoff-Schneidstoffpaarung ist für eine vorgegebene Schnittgeschwindigkeit die Standzeit zu berechnen. Technologische Versuche für den Untersuchungswerkstückwerkstoff haben die folgende Abhängigkeit ergeben:

Versuch 1: $\qquad v_{c1}\space = \space 5 \quad\space m/s \qquad\qquad T_1\space=\space 50\space min$ <br/>
Versuch 2: $\qquad v_{c2}\space = \space 400 \space m/min \qquad\space\space T_2\space=\space 10\space min$

Welche Standzeit wird mit einer eingestellten Schnittgeschwindigkeit von $v_c$ = 350m/min erreicht?

Gegebene Formel: $\qquad T\space=\space C_v\space \cdot \space v_c^k$

mit

$\ \qquad \quad \space T: \space Standzeit$

$\ \qquad \quad C_v:\space Standzeit\space bei\space vc\space =\space 1\space m/min$

$\ \qquad \quad \space k: \space Steigung\space der\space Standzeitgeraden$

<br/>
**Standzeit T in min**
[[21]]
***
|Nr.|$v_c\space [m/min]$|$T\space [min]$ |$log\space v_c$ | $log\space T$ |
|:---:|:---:|:---:|:---:|:---:|
|**1**|300|50|2,477|1,699|
|**2**|400|10|2,602|1,000|

<br/>

* $k\space =\space \frac{log\space T_1\space - \space log\space T_2}{log\space v_{c1}\space - \space log\space v_{c2}} \implies k\space =\space \frac{1,699\space -\space 1}{2,477\space -\space 2,602}\space =\space -5,592 \qquad \frac{1}{k}\space =\space -0,179$
* $C_v\space = \frac{T}{{v_c}^k} \qquad\quad\space\implies C_v\space =\space \frac{50\space min}{300^{-5,592}}\space\approx\space3,557\space \cdot\space 10^{15}\space min$
* $T\space =\space C_v\space \cdot\space {v_c}^k \quad\space\implies T\space =\space 3,557\space \cdot\space 10^{15}\space min\space \cdot\space350^{-5,592}\space \approx\space 21\space min$

<br/>
~~Erläuterung zur Herleitung der Gleichungen~~

Zunächst sind folgende zwei Gleichungen aufzustellen:

$C_v\space=\space \frac{T_1}{{v_{c1}}^k} \qquad bzw. \qquad C_v\space=\space \frac{T_2}{{v_{c2}}^k}$

gleichzusetzen:

$\implies \quad \frac{T_1}{{v_{c1}}^k}\space=\space \frac{T_2}{{v_{c2}}^k}$

und zu logarithmieren:

$\implies \quad log\space T_1\space - \space k\space log\space v_{c1}\space =\space log\space T_2\space -\space k\space log\space v_{c2}$

Nach Umstellen der Gleichung erhält man:

$k\space =\space \frac{log\space T_1\space - \space log\space T_2}{log\space v_{c1}\space - \space log\space v_{c2}}$
***

***

{{5-6}}
***
<!--
style="font-size: 24px;"
-->
**Aufgabe 6**

Eine in der Praxis übliche Methode zur Spanformung beim Drehen ist der Einsatz von Spanleitstufen. Ihre Aufgabe ist es, den abfließenden Span gegen ein Hindernis in Fließrichtung zu leiten und somit durch eine zusätzliche Materialbeanspruchung, den Span brechen zu lassen.

<!--
style="font-size: 16px; color: blue;"
-->
**Ist beim Einsatz einer eingesinterten Spanleitstufe *(Abb. a)* ein sicherer Spanbruch beim Drehen des Werkstoffs C45 gewährleistet, wenn angenommen wird, dass der Span von einem Krümmungsradius $R_0$ auf R = ∞ aufgebogen wird *(Abb. b)?***

Der Einstellwinkel beträgt $\kappa = 90\degree$ *(Abb. c)*.

Der Vorschub beträgt $f = 0,1 \space mm$ *(Abb. c)*.

Der Spanwinkel beträgt $\gamma = 10\degree$.

Der Scherwinkel beträgt $\phi = 35\degree$.

Für den Spanformer gilt: $b_L = 1,0\space mm,\space t_L = 0,3\space mm$.

Die gegen die gekerbte Spanoberseite des Spans gemessene Bruchdehnung von C45 beträgt $\varepsilon_b = 7,1\%$.


![image](images/Einsatz_von_Spanleitstufen.png)<!--
style = "width: 75%; "
-->

<!--
style="font-size: 14px; width: 100%; margin: 0.25em 0;"
-->
***Abbildung:*** *Einsatz von Spanleitstufen. __a__ Eingesinterte Spanleitstufe. __b__ Annahme: Span wird von Krümmungsradius R auf R→∞ aufgebogen. __c__ Spanungsgrößen beim Drehen***

<br/>

Beantworten Sie die Frage mit "ja" oder "nein"!
[[nein]]
***
<!--
style="color: red;"
-->
*Begründung, Rechenweg mus noch ausgearbeitet werden!*

***

***
