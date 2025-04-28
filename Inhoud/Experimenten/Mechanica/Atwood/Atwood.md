---
downloads:
    - file: Atwood SGO.docx
    - title: SGO
    - file: Atwood NB.ipynb
    - title: Notebook
---

<div style="text-align: right;">
  <button onclick="switchLanguage()">EN</button>
</div>

<script>
function switchLanguage() {
  var url = window.location.href;
  if (url.includes('/nl/')) {
    var newUrl = url.replace('/nl/', '/en/');
    window.location.href = newUrl;
  } else if (url.includes('/en/')) {
    var newUrl = url.replace('/en/', '/nl/');
    window.location.href = newUrl;
  } else {
    // fallback: ga naar Engelse homepage
    window.location.href = '/en/';
  }
}
</script>

# Atwood en Newton de tweede
Dit is een voorbeeld experiment zoals opgenomen zal worden in het boek Doe*de*Fysica. Het betreft metingen aan het toestel van Atwood.

## Experiment
Het toestel van Atwood is een klassiek experiment waarmee leerlingen op eenvoudige wijze de wetten van Newton kunnen onderzoeken. Door twee gewichten via een katrol met elkaar te verbinden, wordt inzichtelijk hoe krachten en versnellingen samenwerken. 

### Methode

#### Ontwerp
In dit experiment, zie {numref}`fig_Atwood_setup` wordt een karretje ($m_1$) versneld doordat er een zwaartekracht werkt op een massa ($m_2$). De versnelling aan het systeem wordt gegeven door:

$$
\begin{aligned}
F_{net} &= F_{z,m_2}\\
(m_1 + m_2) \cdot a &= m_2 \cdot g
\end{aligned}
$$

Leerlingen kunnen de tweede wet van Newton onderzoeken door de versnelling ($a$) van het karretje te bepalen als functie van de massa ($m_2$).

```{figure} Atwood.png
:width: 70%
:name: fig_Atwood_setup 
:alt: De Atwood-opstelling bestaat uit een luchtbaan met daarop een karretje en een gewicht dat met een klein draadje aan het karretje is bevestigd.

De opstelling van Atwood: een karretje op een luchtkussenbaan wordt versneld door een massa bevestigd aan het karretje via een draadje dat loopt over een lichtlopend katrol.
```

#### Benodigdheden
* Luchtkussenbaan
* Karretje 
* Verschillende massa's
* Lichtsluis / stopwatch / pocket voyager[^fn1] 

#### Uitvoering

| $m_2$ (g)| $t$ (s) | $v_{gem}$ (m/s) | $a$ (m/s$^2$) |
| --- | --- | --- | --- | 
| | | | |
| | | | |
| | | | |
| | | | |
| | | | |


### Resultaten


### Conclusie

## Didactiek
### Optie 1: CDC aanpak
Elke groepje bepaalt nauwkeurig de versnelling bij een enkele massa ($m_2$). De metingen worden gecombineerd door de docent: $a(m_2)$. Gezamenlijk wordt het resultaat besproken, de voorspelde grafiek is op het bord weergegeven m.b.v. [geogebra](https://geogebra.org). De metingen worden door de leerlingen toegevoegd.

### Optie 2: PO
Elk groepje bepaalt op basis van een éénpuntsmeting (welke afstand kun je het beste gebruiken en waarom?) de versnelling. Ze variëren zelf de massa van $m_2$. Welke massa's gebruik je en waarom?

[^fn1]: Verschillende mogelijkheden om de versnelling te bepalen

