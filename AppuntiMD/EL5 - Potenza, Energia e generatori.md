# Potenza ed energia assorbite da un resistore

[TOC]

## Potenza assorbita ed erogata

Per capire la potenza ed energia assorbite da un resistore dobbiamo analizzare come al solito un circuito che include il bipolo resistore; andiamo quindi ad applicare le solite convenzioni, adottando la convenzione dell'utilizzatore:

![156th23-214059](assets/156th23-214059.png)

Quando il prodotto è **maggiore di zero** vuol dire che il nostro resistore sta **assorbendo** energia dal circuito.

Allo stesso modo, la **potenza erogata** (ovvero potenza assorbita!) **dal resistore è sempre minore di zero**:

![156th23-214605](assets/156th23-214605.png)

Possiamo anche ricavare la corrente (dalla legge di ohm) e sostituirla nell'equazione della potenza assorbita/erogata:

![156th23-215105](assets/156th23-215105.png)

## Energia assorbita

Per calcolare l'energia assorbita (in generale) ci basta **integrare la potenza nell'intervallo di tempo**:

<img src="assets/156th23-215449.png" alt="156th23-215449" style="zoom:25%;" />

Nel nostro caso specifico ci basta sostituire a P<sub>a</sub>(t):

![156th23-215655](assets/156th23-215655.png)

## Potenza ed energia del dipolo cortocircuito

<img src="assets/156th23-215901.png" alt="156th23-215901" style="zoom: 25%;" />

## Potenza ed energia del dipolo circuito aperto

![156th23-220328](assets/156th23-220328.png)

# Concetto di Bipolo a-dinamico

## Bipolo a-dinamico Passivo

Dal punto di vista energetico, un bipolo adinamico (ovvero con caratteristica algebrica o istantanea) si dice **passivo** se la potenza assorbita è sempre maggiore o uguale a zero.

Inoltre, si dice **strettamente passivo** quando assorbe potenza maggiore, e la potenza assorbita è nulla solo se *tensione per corrente* sono <u>entrambi zero</u>.

Riassumendo:

- Il resistore con R>0 è **strettamente passivo.**
- Il cortocircuito ed il circuito aperto sono bipoli **non strettamente passivi**.

 Per spiegare il concetto, esaminiamo il piano cartesiano:

![156th23-221715](assets/156th23-221715.png)

- **Primo quadrante:** il prodotto v*i è **sempre maggiore di zero** ovvero nei **punti di funzionamento** (pallini in verde, ovvero punti appartenenti all'equazione caratteristica del dipolo) del primo quadrante.
  In questo quadrante **la potenza assorbita è maggiore di zero**.
- **Terzo quadrante:**  anche in questo caso la potenza assorbita è maggiore di zero.
- **Secondo e Quarto quadrante**: In questi quadranti non **<u>deve</u>** essere presente alcun punto!
  Infatti <u>l'unico punto</u> in cui l'equazione caratteristica del resistore dovrebbe essere zero, è proprio in zero!

# Bipolo Generatore reale di tensione

Anche il circuito è un bipolo; a questo circuito è connesso un altro bipolo: il generatore **reale** di tensione:

![156th23-222152](assets/156th23-222152.png)

Il **generatore reale di tensione** è costituito da **due elementi che abbiamo giù visto**:

1. Generatore ideale di tensione
2. Resistore

Come faremo con ogni dipolo, dobbiamo andare ad analizzarlo: la prima cosa che facciamo è stabilire una convenzione, in questo caso adottiamo quella del **generatore**: andiamo quindi a riportare differenza di potenziale e verso della corrente; facciamo lo stesso anche per **l'interno del generatore**:

![166th23-185910](assets/166th23-185910.png)

Per **ricavare l'equazione caratteristica** abbiamo diversi strumenti a nostra disposizione: **le leggi di Kirchhoff e le caratteristiche dei singoli bipoli.**

## Derivazione dell'equazione caratteristica del generatore reale

Possiamo trovare l'equazione caratteristica sfruttando sia le leggi di Kirchhoff sia grazie alle equazioni caratteristiche dei singoli componenti:

### LKT

Individuiamo la maglia del circuito e scriviamo la legge di Kirchhoff per le tensioni:

![166th23-190025](assets/166th23-190025.png)

### Equazioni caratteristiche dei dipoli coinvolti

 <img src="assets/166th23-190401.png" alt="166th23-190401" style="zoom:25%;" />

---

Possiamo mettere tutto insieme in modo da trovare finalmente l'equazione caratteristica:

![166th23-190711](assets/166th23-190711.png)

**N.B.** R è la resistenza interna del generatore.

## Esempio di applicazione

La formula E0/R è utilizzata per calcolare la corrente in un circuito quando la resistenza è costante e si applica una tensione E0.

La corrente di cortocircuito si riferisce alla corrente massima che può fluire attraverso un circuito quando i punti di tensione sono collegati direttamente insieme, creando un percorso di bassissima resistenza. In pratica, quando si verifica un cortocircuito, la resistenza del circuito diventa molto vicina allo zero, permettendo un flusso di corrente elevato.

![166th23-192302](assets/166th23-192302.png)

- Nel **secondo quadrante** il bipolo **assorbe corrente**.
- Nel **primo quadrante** il bipolo **eroga corrente**.
  Quindi in ogni momento (nel primo quadrante) la potenza erogata è maggiore di zero.

Nel grafico, il **valore della potenza erogata** è **l'area sottesa al grafico**:

![166th23-192359](assets/166th23-192359.png)

- **A vuoto** P<sub>e</sub> = 0
- **In corto circuito** P<sub>e</sub> = 0

# Potenze massime erogabili

Come facciamo a trovare la **potenza massima erogabile da un dipolo?**

![166th23-192832](assets/166th23-192832.png)

Otteniamo la potenza come *funzione della corrente*: possiamo sfruttare le nostre conoscenze dell'analisi matematica per studiare la funzione:

1. Tracciamo i punti di nostra conoscenza:
   1. A corrente zero, la potenza è zero.
   2. Quando v (differenza di potenziale) è zero e i=E<sub>0</sub>/R (corrente di cortocircuito) la potenza è zero.
2. La parabola ha una concavità rivolta verso il basso:
   1. Sia per via dei segni dei coefficienti
   2. Sia perché dal grafico precedente abbiamo un intervallo di valori positivi tra le due intersezioni con l'asse x --> concavità verso il basso.
3. Come conseguenza all'affermazione precedente, questa parabola **ha un massimo**: i massimi vengono trovati andando a derivare l'equazione della parabola.

![166th23-193801](assets/166th23-193801.png)

Capiamo quindi che la "corrente massima" (non esiste la corrente massima!), ovvero la corrente per cui si ottiene la **potenza massima** è proprio i=E<sub>0</sub>/2R; possiamo trovare la potenza massima sostituendo i<sub>max</sub> nell'equazione della potenza erogata:

![166th23-164255](assets/166th23-164255.png)

## Potenza erogata minore di zero

Abbiamo anche dei punti in cui la **potenza erogata è minore di zero**:

<img src="assets/166th23-164824.png" alt="166th23-164824" style="zoom: 25%;" />

## Energia Erogata

Come sappiamo l'energia è l'integrale tra t<sub>0</sub> e t della potenza, e non ci dice molto, siccome essa dipende dalla corrente e dalla tensione:

<img src="assets/166th23-165055.png" alt="166th23-165055" style="zoom:25%;" />

Se però supponiamo che:

- e(t) = E<sub>0</sub>
- i(t) è sia:
  - i<sub>0</sub> > 0
  - i<sub>0</sub> < E<sub>0</sub>/R

<img src="assets/166th23-165625.png" alt="166th23-165625" style="zoom: 33%;" />

Questa conclusione ci dice che il nostro dipolo **può erogare** (o assorbire) **energia infinita**; questo ovviamente accade in un caso ideale, infatti basti pensare a due possibili scenari:

- Il dipolo è alimentato da una batteria; la batteria prima o poi si scarica --> il dipolo non assorbe energia infinita
- Il dipolo è alimentato da un generatore, che a sua volta è "alimentato" da una seconda **fonte di energia**, che può essere chimica, eolica, geotermica... Questo ci fa capire che anche il generatore assorbe energia da qualche altra parte per darla al nostro dipolo.

## Perché il generatore è "reale"

Il generatore si dice reale perchè la potenza massima erogabile è **limitata**, e vale **E<sub>0</sub><sup>2</sup>/4R**. A differenza del generatore reale, quello **ideale**, ha una **resistenza interna nulla**, e quindi:

![166th23-170447](assets/166th23-170447.png)

Di conseguenza:

<img src="assets/166th23-170643.png" alt="166th23-170643" style="zoom:25%;" />

## Differenza tra generatori reali ed ideali

### Generatore reale di tensione

- Potenza massima erogabile: **limitata**.
- Energia massima erogabile: **non limitata**.

### Generatore ideale di tensione

- Potenza massima erogabile: **non limitata**.
- Energia massima erogabile: **non limitata**.

## Caratteristica con la convenzione dell'utilizzatore

![166th23-171839](assets/166th23-171839.png)

# Bipolo Generatore reale di Corrente

![166th23-172730](assets/166th23-172730.png)

Possiamo scrivere le equazioni caratteristiche delle singole componenti per giungere alla relazione caratteristica del componente intero:

![166th23-172833](assets/166th23-172833.png)

![166th23-173055](assets/166th23-173055.png)
