# Übung 3 - Operatoren

Erstellen Sie sich für die Theorieaufgaben ein eigenes File und laden Sie dieses auch in Ihr Repository. 

**Achtung:** Die beiliegende Main-Klasse beinhaltet die Testfälle für die Aufgaben 1 und 2. 
Wenn Sie vorerst nur eine der beiden Aufgaben testen wollen, kommentieren Sie die Testfälle 
der anderen Aufgabe in der Main-Klasse aus.

## 1. Aufgabe - Wiederholung

In einer Klasse `Formel1` soll folgendes implementiert werden:

**Eigenschaften:**
- `pi` (π mit dem Wert 3): Überlegen Sie sich einen passenden Datentyp

**Methoden:**
- Defaultkonstruktor
- `flaecheRechteck(int a, int b)`: siehe Hinweis, Lösung schon vorgegeben
- `addition(int a, int b)`: liefert die Summe
- `division(int a, int b)`: liefert den Quotienten
- `berechneY( … )` mit folgenden Formeln:
    - x = 3a + 6b – a²
    - y = 5x – 2b
    - Überlegen Sie sich die Parameter und lokalen Variablen
- `berechneZylinder( … )` mit folgenden Formeln:
    - g = r²π
    - zylinder = gh
    - Überlegen Sie sich die Parameter und lokalen Variablen
- `berechneZ( … )` mit folgenden Formeln:
    - u = 3a + 6b – a²
    - o = 3a + 6 / (b – c²)
    - z = 5u – 2o
    - Überlegen Sie sich die Parameter und lokalen Variablen

**Hinweis:**

Eine Formel wie die Fläche eines Rechtecks: A = a * b wird in Java zu einer Methode.

<p align="center">
  <img src="/assets/images/Cod1.png" alt="Hinweis" />
</p>

- `flaecheRechteck` ist der Name der Methode (kann natürlich auch anders lauten)
- `a` und `b` sind die Parameter (Zusatzinformation die man braucht um rechnen zu können)
- `ergebnis` ist eine lokale Variable in der wir uns Zwischenergebnisse merken
- `return` liefert uns das Ergebnis zurück (Rückgabewert)

## 2. Aufgabe

In einer Klasse `Formel2` soll folgendes implementiert werden:

**Eigenschaften:**
- `pi` (π mit dem Wert 3): Überlegen Sie sich einen passenden Datentyp

**Methoden:**
- Defaultkonstruktor
- `getPi()`
- `berechneHoch3(int x)`: berechne x³
- `berechneHoch6(int x)`: berechne x6 mittels aufrufen von `berechneHoch3`
- `berechneKreisFlaeche(int r)`: die Formel lautet: r²π
- `berechneZylinderVolumen(int r, int h)`: die Formel lautet: r²πh. Rufen Sie `berechneKreisFlaeche` auf
- `berechneZ( … )` mit folgenden Formeln:
    - b = a³ + c * 5
    - u = 3a + 6b - a²
    - o = 3a + 6 / (b – c²)
    - z = 5u – 2o
    - Überlegen Sie sich die Parameter und lokalen Variablen
- `berechneZylinderOberflaeche(int r, int h)`: Finden Sie selbst eine Formel

**Probieren Sie die folgenden Aufgaben ohne Hilfe der IDE oder des Internets.**

## 3. Aufgabe

Welche Ausgabe liefert folgender Codeausschnitt?

<p align="center">
  <img src="/assets/images/Cod2.png" alt="Codeausschnitt" />
</p>

## 4. Aufgabe

Vervollständigen Sie die folgenden Wahrheitstabellen:

<table align="center">
<tr><td>

| A  | B  | A && B  |
|:---:|:---:|---|
| w  | w  |   |
| w  | f  |   |
| f  | w  |   |
| f  | f  |   |

</td><td>

| A  | B  | A &#124;&#124; B  |
|:---:|:---:|---|
| w  | w  |   |
| w  | f  |   |
| f  | w  |   |
| f  | f  |   |

</td></tr> </table>

Es gibt noch einen Operator, den wir uns noch nicht angeschaut haben. Das sogenannte 
Exklusiv-Oder. Dargestellt wird es als `^`. Wie könnte die Wahrheitstabelle dafür aussehen?

<table align="center">
<tr><td>

| A  | B  | A ^ B  |
|:---:|:---:|---|
| w  | w  |   |
| w  | f  |   |
| f  | w  |   |
| f  | f  |   |

</td></tr> </table>

## 5. Aufgabe

Welchen Wahrheitswert liefern die folgenden Ausdrücke?

<p align="center">
  <code>(3 == 3) && !(!true) || !(!(30 > 30) || (true))</code>
</p>

<p align="center">
  <code>!((589 > 1000/2) && (1 < 2) || (319 <= 319))</code>
</p>

<p align="center">
  <code>!((false) || (54 < 55) && !(0 > -4)) || (90 < 89) && (334 == 334)</code>
</p>
