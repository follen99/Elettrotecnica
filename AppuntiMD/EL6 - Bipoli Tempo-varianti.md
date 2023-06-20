# Bipoli Tempo-Varianti

## Bipolo interruttore

Il bipolo interruttore può essere **aperto** o **chiuso**:

<img src="assets/166th23-185948.png" alt="166th23-185948" style="zoom:33%;" />

Il fatto che **lo stato dell'interruttore** (aperto o chiuso) **dipende dal tempo**, permette all'interruttore di far parte dei bipoli **tempo-varianti**; possiamo infatti dire "in questo istante l'interruttore è aperto/chiuso".

Il bipolo interruttore è un bipolo di tipo **lineare a-dinamico tempo-variante**:

- La caratteristica è lineare, perchè i(t)=0 / v(t)=0è lineare
- E' a-dinamico perchè le caratteristiche sono **istantanee**

## Bipolo Resistore tempo-variante

Un altro esempio di bipolo tempo-variante può essere la seguente:

<img src="assets/166th23-190547.png" alt="166th23-190547" style="zoom:25%;" />

La sua caratteristica ci dice che passato il tempo 3 secondi, la sua corrente cambia; potrebbe essere un **resistore**:

### Il potenziometro

<img src="https://cdn.pixabay.com/photo/2012/04/24/16/43/potentiometer-40381_960_720.png" alt="Download Potentiometer Rheostat Resistance Royalty-Free Vector Graphic -  Pixabay" style="zoom:25%;" />

Il potenziometro è un esempio di un resistore tempo-variante.

![166th23-191352](assets/166th23-191352-1687194908903-1.png)

> Per angolo si intende l'angolo fisico del potenziometro; infatti la manopola del potenziometro è fisicamente collegata ad un "braccio" che scorre lungo la resistenza interna.

---

## Recap dei dipoli visti finora

Finora abbiamo visto i dipoli:

1. Lineari
2. A-Dinamici
3. Tempo-invarianti (tutti i resistori visti fino all'interruttore e al potenziometro).
4. Tempo-varianti (la loro caratteristica non dipende dal tempo).
5. Passivi - Strettamente passivi
6. Attivi 
   I bipoli generatori ideali e reali sono bipoli **attivi**, perché esiste almeno una condizione di funzionamento in cui il bipolo **eroga** energia al circuito.

Le due ultime definizioni verranno approfondite nella lezione corrente.

 # Bipoli lineari Dinamici

## Il Condensatore

Il condensatore è un dispositivo in cui possiamo **accumulare della carica elettrica**.

Se applichiamo una differenza di potenziale (ovvero colleghiamo il condensatore ad una batteria / generatore), delle cariche tenderanno ad accumularsi sulle due piastre del condensatore.

La nostra ipotesi di lavoro è che **la differenza di potenziale è positiva**, e quindi la piastra collegata ad A si carica positivamente, mentre quella collegata a B si carica negativamente.

<img src="assets/166th23-193004.png" alt="166th23-193004" style="zoom:25%;" />

Possiamo definire la grandezza **Farad** che misura proprio la capacità; inoltre, se la distanza tra le piastre è molto più piccola rispetto alla superficie di quest'ultime, possiamo calcolare la capacità del condensatore come:

<img src="assets/166th23-193621.png" alt="166th23-193621" style="zoom: 33%;" />

Possiamo rappresentare con un grafico la retta della caratteristica del condensatore:

<img src="assets/166th23-194714.png" alt="166th23-194714" style="zoom:25%;" />

Calcolando la tangente dell'angolo compreso tra la retta e l'asse delle x possiamo facilmente trovare il valore corrispondente alla capacità.

### Induzione elettrostatica perfetta

Parliamo di condensatore quando siamo in presenza di **induzione completa** (o perfetta) ovvero quando le cariche su una piastra sono **l'esatto opposto** dell'altra piastra, ovvero se la carica positiva accumulata è l'opposto di quella negativa.

Quando le piastre del condensatore non sono perfettamente **schermate**, si verifica un processo di **induzione** anche su delle piastre che non *dovrebbero* subire induzione:

<img src="assets/166th23-194440.png" alt="166th23-194440" style="zoom:25%;" />

> Esempio di induzione **non perfetta**.

### Ricavare l'equazione caratteristica del condensatore

#### Caratteristica della corrente

Come sempre stabiliamo una convenzione (utilizzatore i va da +  a -) e quindi stabiliamo una differenza di potenziale (positiva).

Possiamo trovare la corrente  grazie ad una **superficie Gaussiana**:

- Se la superficie **circonda** il bipolo, allora il flusso sarà zero.
- Se la superficie (chiusa) avvolge **solo una piastra** il flusso non sarà più zero: possiamo usare la legge della **conservazione della carica** per trovare la corrente:

 ![166th23-202914](assets/166th23-202914.png)

Possiamo recuperare la formula della capacità ricavata prima, e mettere insieme le due equazioni:

 ![166th23-203238](assets/166th23-203238.png)

Ci accorgiamo quindi dalla caratteristica che **la corrente dipende dal tempo**, infatti la derivata è dipende proprio dall'istante di tempo in cui viene calcolata.

La derivata è inoltre un **operatore lineare**, il che rende il condensatore un **bipolo dinamico lineare**.

Se calcoliamo la caratteristica dal punto di vista della convenzione del generatore, otterremmo semplicemente il risultato col segno cambiato:

<img src="assets/166th23-203743.png" alt="166th23-203743" style="zoom:25%;" />

Possiamo inoltre osservare il caso in cui **la capacità è funzione del tempo**:

<img src="assets/166th23-204257.png" alt="166th23-204257" style="zoom: 33%;" />

#### Caratteristica della tensione

Possiamo **integrare entrambi i membri** della caratteristica della corrente in modo da ottenere la tensione:

<img src="assets/166th23-204730.png" alt="166th23-204730" style="zoom: 33%;" />