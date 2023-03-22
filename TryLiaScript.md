<!--
author:   Britta

email:    b.petersen@rz.uni-kiel.de

version:  0.0.1

language: de

narrator: DE German Female

comment:  Just a demo for LiaScript

-->

# LiaScript ist gar nicht schwer

LiaScript ist relativ einfach zu erlernen. 

Es basiert auf Markdown und nutzt die bekannten Auszeichnungen.

## Kapitel/Überschriften

...werden mit **#** ausgezeichnet:

\# Überschrift 1

\#\# Überschrift 2

\#\#\# Überschrift 3

\#\#\#\# Überschrift 4

\#\#\#\#\# Überschrift 5

\#\#\#\#\#\# Überschrift 6

> LiaScript generiert neue Seiten für jede Überschrift.

## Texthervorhebungen

Wie in Markdown...

*So kann man Texte kursiv stellen:*

`_kursiv_ auch *kursiv*`

_kursiv_ auch *kursiv*

---

**So kann man Texte fett darstellen:**

`**fett** auch __fett__`

**fett** auch __fett__

---

***Kursiv und fett geht so:***

`___kursiv___ und ***fett***`

___kursiv___ und ***fett***

---

Durchstreichen:

`~durchgestrichen~`

~durchgestrichen~

---

Unterstreichen:

`~~unterstrichen~~`

~~unterstrichen~~

---

Durch- und Unterstreichen:

`~~~durch- & unterstrichen~~~`

~~~durch- & unterstrichen~~~

---

Hochstellung:

`^hochgestellt^`

Das folgende Wort ist ^hochgestellt^

---

Unformtierten Code erhält man durch \`Codeabschnitt\`

`unformatierter Code`

## Listen

Ebenfalls, wie in reinem Markdown:

* Einfache Listen werden mit einem vorangestellten: 
  `*`, `+` oder `-` markiert
  
  Und können mehrere Absätze enthalten.

* Liste mit Unterpunkten:

  - Es ist egal ob `-`
  + oder ![alt](https://...)
![alt](https://... "titel")

Projektinterne Bilder:

![alt](/pic/image.jpg)
![alt](/pic/image.jpg "titel")+`
  * oder `*` vorangestellten wurden

---

**Nummerierte Listen**

1. Sortierte Listen werden mit einer vorangestellten Zahl markiert

2. Hier Punkt 2

3. Es kann auch unter nummerierten Listen Unterpunkte geben:

   + Punkt 1
   + Punkt 2


## Verweise

Ganz einfach:

* unformatiert: https://LiaScript.github.io

oder 

* formatiert: [fdm\@studium.nrw TH Köln](https://www.th-koeln.de/informatik-und-ingenieurwissenschaften/fdmstudiumnrw_98785.php)

## Abbildungen, Audio, Video

Abbildungen werden durch folgende Auszeichnung eingebunden:

`![alt](https://...)`

**Beispiel:**

![Bild](https://fdm-nrw.coscine.de/logo/fdm-nrw_Logo_rgb_web.png) 

`![alt](https://... "titel")`

**Beispiel:**

![Bild](https://fdm-nrw.coscine.de/logo/fdm-nrw_Logo_rgb_web.png "Logo der Landesinitiative") 

---

**Projektinterne Bilder so:**

`![alt](/pic/image.jpg)`

`![alt](/pic/image.jpg "titel")![alt](https://...)`

**Beispiel**

![alt](Ordnung_und_Stuktur/Abbildungen/Icon_Tipp2_2022-02-24_cm_web.jpg)

![alt](Ordnung_und_Stuktur/Abbildungen/Icon_Puzzel_2022-03-23_web.jpg "Puzzel")


## Quizzes

> Quizzes in LiaScript sind ebenfalls einfach:

**Einfache Texteingabe:**

What is the name of the Markdown dialect that is used for education?

    [[LiaScript]]

**Single-Choice**

Can you think of a simpler way of creating Quizzes?

    [( )] yes
    [(X)] __NO of course not__
    [( )] maybe
     ***********************************************************************

    **Juhuuuu!**

    ***********************************************************************

**Multiple-Choice**

What is the derivative function of $f(x) = x^6$?

    [[ ]] $f'(x) = 6$
    [[X]] $f'(x) = 6x^5$
    [[ ]] $f'(x) = 5x^6$
    [[X]] this is only a random demo to highlight formulas
    ***********************************************************************

    ![MS-DOS Math Game](https://i.gifer.com/origin/0e/0edc716135c55552ed0f7aa673847e03.gif)

    ***********************************************************************

### German is weird

Man or woman is obvious, but you guess the remaining German grammatical genders?

    [[male (der<!-- class="notranslate"-->)]   (female [die<!-- class="notranslate"-->])   [neuter (das<!-- class="notranslate"-->)]]
    [    [X]           [ ]             [ ]     ]  Mann<!-- class="notranslate"--> - German for man
    [    ( )           (X)             ( )     ]  Frau<!-- class="notranslate"--> - German for woman
    [    [X]           [ ]             [ ]     ]  Junge<!-- class="notranslate"--> - German for boy
    [    ( )           ( )             (X)     ]  Mädchen<!-- class="notranslate"--> - German for girl
    [    [X]           [X]             [ ]     ]  Paprika<!-- class="notranslate"--> - German for bell pepper
    [    (X)           (X)             (X)     ]  Joghurt<!-- class="notranslate"--> - German for yogurt

