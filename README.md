# Practicum Machinaal Leren

## 1. neuraal netwerk

In dit practicum gaan jullie een tweelagig neuraal netwerk implementeren in Python en dit testen op de klassieke "Iris" dataset enerzijds en de MNIST dataset voor handschrift herkenning anderzijds.

Twee uur is wat kort om alles van nul te implementeren, bovendien willen we niet te veel tijd verliezen met boilerplate te schrijven en dingen te installeren, dus voorzien we een startpunt onder de vorm van een [jupyter notebook](https://en.wikipedia.org/wiki/Project_Jupyter#Jupyter_Notebook)

We gaan deze notebooks uitvoeren binnen de 'google colab' omgeving (je hebt dus een google account nodig).

De eerste oefening kan je via de volgende link starten: [neurale netwerken notebook](https://colab.research.google.com/github/Pieter-hogent/AI-labo/blob/master/practicum_neurale_netwerken.ipynb)

Zo een notebook bevat verschillende 'cellen', enerzijds stukken code (die je deels dient aan te vullen), anderzijds extra uitleg en de resultaten van deze code.

Je voert zo een cell uit door telkens op de 'play' knop te drukken.
![](/img/ailabo-play.png)

Blokken code die je dient aan te vullen staan telkens aangegeven als volgt:

```
  ### BEGIN CODE HIER (n regels)
  ### EINDE CODE HIER
```

Een indicatie van het aantal code regels die je nodig hebt is ook gegeven.

Als je code errors bevat, zullen deze getoond worden na het uitvoeren van zo een cell

![](/img/ailabo_error.png)

De bedoeling is natuurlijk om geen enkele error te hebben, en een werkend neuraal netwerk dat voor beide test data sets een goed resultaat oplevert.

## 1.1 voorbeeld

Laat ons als voorbeeld de eerste stap uitwerken, gevraagd wordt om de sigmoide functie te implementeren.

![](http://www.sciweavers.org/tex2img.php?eq=%5Cfrac%7B1%7D%7B1%20%2B%20e%5E%7B-Z%7D%7D&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0)

Met behulp van numpy (reeds geimport in de vorige cell als 'np'), kan dit binnen python als volgt geschreven worden.

```
def sigmoid(Z):
  return 1/(1+np.exp(-Z))
```

Deze code op de juiste plaats toevoegen in de cell en uitvoeren doet de error verdwijnen.

![](/img/ailabo-code.png)

Als je alle stappen correct implementeert, zal je zien dat je een goed werkend neuraal netwerk gecreëerd hebt, proficiat!

# 2. Lineaire regressie

Voor de snelle python programmeurs is er nog een tweede practicum, hier gaan we lineaire regressie toepassen: [lineaire regressie notebook](https://colab.research.google.com/github/Pieter-hogent/AI-labo/blob/master/practicum-lineaire-regressie.ipynb)

Concept is net hetzelfde, vul de regels code aan waar nodig
