# Potenza assorbita ed erogata da un bipolo conduttore ohmico filiforme

[TOC]

Per *conduttore ohmico filiforme* si intende un qualsiasi conduttore avente una sezione circolare; di conseguenza **la densità di corrente è proporzionale al campo elettrico** (la legge di ohm funziona).

<img src="assets/ImmaginePNG21.png" alt="ImmaginePNG21" style="zoom:33%;" />

Ovviamente ci aspettiamo che **la potenza assorbita sia maggiore di zero**; questo non è però scontato: se invece di un conduttore ohmico (come un filo, o resistore) avessimo un *generatore* (come una batteria), questa potrebbe anche *erogare energia*, e quindi non la assorbirebbe dal circuito.

Vogliamo quindi **dimostrare** che la potenza assorbita dal dipolo è *v(t) \* i(t)*: 

## Dimostrazione potenza assorbita: Ipotesi del lavoro

Questa ipotesi ci dice che *prendendo il potenziale maggiore o minore di zero non cambia la dimostrazione*:![lavoroipotesi](assets/lavoroipotesi.png)

Ovviamente le cariche si muovono dal punto con il *potenziale maggiore*, al punto col potenziale minore; in questo caso si spostano da A a B.

Immaginiamo di considerare la carica elementare dq che si muove (con la usa velocità *v*) attraverso la sezione del filo; quale sarà il lavoro elementare che si deve compiere per spostare una carica dq?

![lavoroelement](assets/lavoroelement.png)

A questo punto facciamo un'altra ipotesi: ci poniamo nel caso in cui il conduttore è molto più lungo della sua sezione (proprio come un lungo filo conduttore); questo ci permette di affermare che **le linee del campo elettrico sono parallele alle "pareti" del conduttore**:

Questo vuol dire che per qualsiasi punto la **densità delle linee di forza di E** è sempre la stessa; questo si traduce nel fatto che **l'intensità di E è costante per tutta la lunghezza del conduttore**.

![tubo](assets/tubo.png)

Tornando al lavoro, possiamo calcolare il lavoro per unità di tempo, che non è altro che una **potenza elementare**. Per trovare la *potenza totale*, ci basta integrare **lungo gamma**:

![potenza](assets/potenza.png)

Ma come abbiamo detto in precedenza, l'integrale lungo la linea *gamma* che va da A a B non è altro che il potenziale V<sub>AB</sub>:

![powqued](assets/powqued.png)



### Dimostrazione con ipotesi di lavoro alternativa

Questa volta la nostra ipotesi del lavoro è la seguente:

- Il potenziale V<sub>0</sub> è negativo
- La corrente *i(t)* è **negativa** perché la velocità della carica ***v*** è **opposta a *dl***.
  (la velocità ha verso opposto perché abbiamo cambiato il valore del potenziale; le cariche vanno dal potenziale maggiore a quello minore.)

![versoopposto](assets/versoopposto.png)

Di conseguenza, andando a moltiplicare, **la potenza assorbita è sempre maggiore di zero**!

Per questo motivo, soprannominiamo P<sub>e</sub>= *v(t) \* i(t)* **POTENZA EROGATA**:![powerogata](assets/powerogata.png)

Per **costruzione** una potenza ha una grandezza con segno invertito rispetto all'altra.

# Convenzioni di segno per tensioni e correnti

Come prima cosa, da questo momento non rappresenteremo più il dipolo come una "patata" (tondeggiante), ma con il seguente schema:![convenzionisegno](assets/convenzionisegno.png)

## Diversi casi nelle convenzioni di utilizzatore/generatore

### Potenza > 0 - conv. Generatore

Il calcolo della potenza `P = v * i` viene *positivo* quando v ed i **hanno lo stesso segno**; siamo quindi nella convenzione del generatore. Possiamo rappresentare la **tensione**, oltre che con i segni + e -, anche con una freccia, per aiutarci a distinguere le convenzioni.

Rappresenteremo la freccia in modo tale da "puntarla" verso il punto dove avremmo posizionato il "+":

<img src="assets/118th23-151550.png" alt="118th23-151550" style="zoom:25%;" />

Se *v* ed *i* hanno lo stesso segno, vuol dire che il punto dove abbiamo posizionato il "+" (destra) ha un **potenziale maggiore** del punto a sinistra; questo perchè se abbiamo la corrente che fluisce da sx a dx, il potenziale dovrebbe essere al contrario (le cariche vanno dal potenziale maggiore a quello minore, quindi in questo caso dovrebbe essere da sinistra a destra)!

Di conseguenza **deve esserci un generatore che <u>porta</u> le cariche da sinistra  destra** compiendo un certo lavoro.

**In altre parole** se nella convenzione del generatore si ottiene un valore positivo della potenza (nella convenzione del generatore), allora il dipolo sta effettivamente **erogando energia**; è quindi un **generatore.**

### Potenza < 0 - conv. Generatore

Se dal calcolo otteniamo un valore negativo della potenza (nella convenzione del generatore), vuol dire che il componente **assorbe energia**; se il componente è una *batteria*, allora **la batteria si sta ricaricando**.

### Potenza > 0 - conv. Utilizzatore

Se dal calcolo otteniamo un valore positivo della potenza (nella convenzione del l'utilizzatore), vuol dire che le cariche si muovono **naturalmente** dal potenziale alto a quello basso; questo avviene **ad opera del campo elettrico** (è il campo che compie il lavoro e non il componente!). Di conseguenza il componente sta **assorbendo energia**.

### Potenza < 0 - conv. Utilizzatore

Se dal calcolo otteniamo un valore negativo della potenza (nella convenzione del l'utilizzatore) vuol dire che il **bipolo passivo funziona da generatore**; questo è possibile in diversi casi, come nel caso dei **condensatori in fase di scarica** e degli **induttori in fase di scarica**.

**N.b.** Bisogna tenere presente che questi componenti sono sempre detti **"passivi"** perché l'energia che erogano è stata precedentemente assorbita dagli stessi.

# Premessa sui circuiti elettrici

Esempi di dipoli elettrici sono:

- Resistore
- Condensatori
  - Elettrolitici
  - Ceramici
- Componenti SMT: 
  *sono dispositivi elettronici compatti saldati sulla superficie di schede di circuiti, consentendo maggiore densità e efficienza nella produzione di dispositivi avanzati.*
- Induttori
- Diodi

Esistono poi i **tri-poli** elettrici:

- Transistori: possono aumentare l'ampiezza di un segnale
- Mosfet

Successivamente ci sono i **circuiti integrati**, ovvero componenti elettronici in cui sono presenti ulteriori componenti elettronici, come resistori, transistori, ecc. Hanno solitamente più pin: 8/16/32...

Abbiamo successivamente i **processori**, detti **n-poli**, che hanno anche centinaia di pin. All'interno dei processori abbiamo un elevatissimo numero di componenti; ci sono delle aree dette **Porte CMOS**, che è una tecnologia utilizzata per "stampare" i circuiti.

I circuiti stampati solitamente **hanno più piani**, anche se in questo corso vedremo circuiti stampati su un singolo piano. Ad esempio il Mosfet è strutturato su 3 "piani".

# Definizione di Circuito Elettrico

Un circuito elettrico è l'insione di dipoli (ma anche altri componenti come i tri-poli) che sono **connessi elettricamente tra loro**, in punti che d'ora in poi chiameremo **nodi del circuito**.

<img src="assets/circuitobase.png" alt="circuitobase" style="zoom:33%;" />



Già solo il fatto che le componenti sono connesse (Saldate) tra loro, porta a stabilire delle **leggi** che governano le tensioni e correnti del circuito.

# Leggi di Kirchhoff per le tensioni e per le correnti

- Tensioni --> ***LKT*** (**L**eggi di **K**irchhoff per le **T**ensioni)
- Correnti --> ***LKC*** (**L**eggi di **K**irchhoff per le **C**orrenti)

## I Nodi - Legge di Kirchhoff per le correnti

1) Scegliamo **arbitrariamente** i versi delle correnti.
2) Scegliamo uno dei nodi del circuito, ad esempio il nodo B.
3) Disegniamo una superficie "Gaussiana" attorno al nodo.
4) Applichiamo la conservazione della carica dopo aver scelto una **normale uscente**.
   Consideriamo le correnti uscenti come positive, le correnti entranti come negative.
5) Applicando *l'ipotesi di quasi stazionarietà* ci accorgiamo che la somma delle correnti che passano attraverso la superficie è zero.

![kirchhoffcurr](assets/kirchhoffcurr.png)

Come si può notare dai calcoli, non sono presenti integrali o calcoli "strani", ma solo **un'equazione lineare** molto semplice; questo è l'obbiettivo del corso: astrarre al massimo ed apportare delle semplificazioni in modo da riuscire ad ottenere un risultato quanto più vicino alla realtà (anche se non perfettamente esatto), ma in un tempo ragionevole!

Tutto questo ragionamento ci porta a definire la **legge di Kirchhoff per le correnti:**

> **LKC: ** somma <u>algebrica</u> delle correnti in funzione del tempo, è sempre uguale a zero.

<img src="assets/legge.png" alt="legge" style="zoom:25%;" />

Possiamo scrivere le equazioni di Kirchhoff per tutti i nodi del circuito:

![eqlinkirch](assets/eqlinkirch.png)

A questo punto possiamo **sommare** tutte le equazioni; arriveremo inevitabilmente ad una **identità** (0=0), ovvero almeno una di queste 4 equazioni può essere espressa attraverso **combinazione lineare delle altre 3**:

![combinazionelin](assets/combinazionelin.png)

## I Loops - Legge di Kirchhoff per le tensioni

Possiamo anche individuare dei **circuiti chiusi** chiamate **Maglie del circuito**:

![maglie](assets/maglie.png)

Per la legge di Kirchhoff sulle maglie, dobbiamo:

1. Individuare una maglia
2. Stabilire il verso della maglia
3. Stabilire una differenza di potenziale per ogni elemento del circuito
4. Applichiamo la legge di Faraday-Neumann: la circuitazione 
5. Consideriamo la Linea chiusa *gamma*:
   1. Se va dal + al - (Quando incontra un componente elettronico i.e. dipolo) allora la differenza di potenziale viene conteggiata come positiva.
   2. Se va dal - al +  allora la differenza di potenziale viene conteggiata come negativa.

<img src="assets/kirchhoffmaglie.png" alt="kirchhoffmaglie" style="zoom:33%;" />

> **LKT: ** Per ogni maglia del circuito la somma algebrica delle tensioni che interessano quella maglia, è istante per istante uguale a zero.

<img src="assets/inlinekirchhoff.png" alt="inlinekirchhoff" style="zoom: 25%;" />