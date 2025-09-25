La matematica si può esprimere atttraverso, funzioni, teoremi e tesi e i simboli
- Simboli o lettere le utilizziamo per denotare delle variabili $x, y, z, t$

ad esempio possiamo utilizzare $n$ preso in considerazione che designano elementi numeri.
- Ad esempio: $\pi$ = 3,14

Alcuni simboli servono per denotare operazioni o funzioni
- $\sqrt{}$ denota l'operazione unaria di radice quadrata
- $+$ e $*$ per operazioni binarie di addizione

Alcuni simboli servono per denotare relazione tra oggetti
- $\le$ si usa per designare la relazione binaria d'ordine
- $=$ designa anch'esso una relazione binaria, la interpretazione di questo simbolo è sempre la stessa in qualunque contesto esso si trovi, mentre il $\le$ devo specificare il contesto, che cosa intendo. 
Lo studio di questi simboli sarà oggetto della logica del prim'ordine (seconda parte/semestre)

--- 
## Costanti logiche

Si usano conecetti logici espressi da locuzione quali:
- non ...
- ...e...
- ...o...
- se...allora...
- ...se e solo se...
- esiste un oggetto $x$ tale che
- per ogni oggetto $x$

Queste sono le tipiche locuzioni che esistono per esprimere concetti diffcili in maniera facile. Dò una costante logica al posto delle parole. 

## Connettivi 

I connettivi logici sono i simboli

- negazione non or not $\neg$ 
- congiunzione e $\land$
- disgiunzione $\lor$
- implicazione $\implies$ : l'implicazione tra le asserzioni $P$, $Q$ 
- biimplicazione $\iff$ : 

### Significato dei connettivi

#### Negazione $\neg$

La negazione $\neg$ asserisce l'opposto dell'affermazione.

- $\neg P$ è vera  se e solo se  $P$ è falsa

> [!example] 
> Se $P$ è l'affermazione $x<y$, allora $\neg P$ è l'affermazione
> $$\neg (x<y)$$
> Questa è vera solo se e solo se $x<y$ è falso. 
> Se $<$ è l'usuale d'ordibamento tra numeri, allora $\neg (x<y)$ signfica che $x \ge y$

Data un'asserzione $P$, si ha che
$P$ è vera  solo e solo se  $\neg P$  se e solo se  $\neg \neg P$ è vera
						se e solo se $\neg \neg \neg P$ è falsa se e solo se $\neg \neg \neg \neg P$ è vera 
In particolare, vale la **legge della doppia negazione**:
$$P \equiv \neg \neg P$$

Inoltre: 
$$P \equiv Q$$ solo e solo se $$\neg P \equiv \neg Q$$
Infatti, se $P \equiv Q$, allora:
$\neg P$ è vera se e solo se $P$ è falsa se e solo se $Q$ è falsa
		se e solo se $\neg Q$ è vera
e similmente, se $\neg P \equiv \neg Q$ allora $P \equiv Q$

#### La congiunzione $\land$

La congiunzione $\land$ asserisce entrambe le affermazione alle quali si applica
- $P \land Q$ è vera se e solo se $P, Q$ sono entrambe vere

> [!example] 
> Se $P : x$ è pari,  $Q : -x$ è un quadrato perfetto
> allora $P \land Q$ è vera se e solo se
> - $P$: x è della forma $2k$, per qualche naturale $k$; e inoltre
> - $Q$

##### Propietà della congiungzione

- $P \land Q \equiv Q \land P$ (commutatività)
- $(P \land Q) \land R \equiv (Q \land R)$ (associatività): questo permette di evitare delle parentesi quando si è interessatisolo alla verità della congiunzione
- $P, Q \models P \land Q$
- $P \land Q \models P$
- $P \land Q \models Q$
- Se $P \equiv R$ e $Q \equiv S$, allora $P \land Q \equiv R \land S$
	Infatti assunto $P \equiv R$ e $Q \equiv S$, se vale $P \land Q$, allora valgono entrambe P e Q;
	di conseguenza valgono R e S, perciò vale $R \land S$
	Si è cioà ottenuto $P \land Q \models R \land S$
	Similmente si dimostra che $R \land S \models P \land Q$, quindi finalmente $P \land Q \equiv R \land S$

#### Disgiunzione $\lor$

La disgiunzione $\lor$ asserisce la verità di almeno una delle asserzioni a cui si applica
- $P \lor Q$ è vera se e solo se almeno una tra $P, Q$ è vera

##### Propietà 
- $P \lor Q \equiv Q \lor P$ (commutatività)
- ($P \lor Q$) $\lor R \equiv P \lor (Q \lor R)$ (associtatività): permette di risparmiare parentesi se interessati solo alla verità di una disgiunzione.
- $P \models P \lor Q$
- $Q \models P \lor Q$
- $P \lor Q, \neg P \models Q$
- $P \lor Q, \neg Q \models P$
- Se $P \equiv R$ e $Q \equiv S$, allora $P \lor Q \equiv R \lor S$
	Infatti,  se $P \equiv R$ e $Q \equiv S$, se vale $P \lor Q$, allora vale almeno uno tra $P$ e $Q$





## Quantificatori 

- quantificazione esistenziale $\exists$ : 
- quantificazione universale $\forall$: 

Perché queste siano significative 

I simboli lgici si possono usare in modo ripetuto per costruire asserzioni complesse a partire da quelle più facili. 
L'ordine di applicazione di questi simboli è specificato dall'uso di parentesi

> [!example] 
> P  $\lor$ (Q $\land$ R )  ha un significato diverso da ( P $\lor$ Q) $\land$ R

### Priorità tra i simboli

Informalmente, si possono risparmiare parentesi convenendo il seguente ordine di priorità tra i simboli.
- $\exists$, $\forall$
-  $\neg$
- $\lor$ , $\land$
- $\implies$, $\iff$

Per lo studio dei connettivi, il vslore di verità di un'asserzione introduciamo due nuovi simboli:
-  Conseguenza logica $\models$ : $P1, P2, ... , Pn \models Q$
	Per indircare que $P1$, ... , $Pn$ hanno conseguenza come $Q$ 
- Equivalenza logica $\equiv$ : P $\equiv$ Q
	Per indircare que P e Q sono equivalenti, cioè che ognuna è una conseguenza dell'altra.

> [!note] 
> A differenza dei connettivi e dei quantificatori, $\models$ e $\equiv$ non sono simboli particolari del linguaggio matematico, ma sono simboli che servono per parlare di tale linguaggio detti *metasimboli*, questi sono oggetti a un uso rigoroso.
> 

## Leggi di De Morgan

1. $\neg (P \land Q) \equiv \neg P \lor \neg Q$
2. $\neg (P \lor Q) \equiv \neg P \land \neg Q$

Per la prima:
Se $\neg (P \land Q)$  è vera, allora $P \land Q$ è falsa, cioè almeno una tra $P$ e $Q$ è falsa.
Se è falsa $P$, allora $\neg P$ è vera, quindi $\neg P \lor \neg Q$ è vera; se è falsa $Q$, allora $\neg Q$ è vera, quindi di nuovo segue $\neg P \lor \neg Q$
Si è dimostrato $\neg (P \land Q) \models \neg (P \land Q)$

> [!question] 
> Dimostra: $\neg (P \land Q) \equiv \neg P \lor \neg Q$
> 
> Dall'equivalenza
> $$\neg (P \land Q) \equiv \neg P \lor \neg Q$$
> si ottiene l'equivalenza delle negazione dei due numeri
> $$\neg \neg (P \land Q) \equiv \neg (\neg P \lor \neg Q)$$
> e ancora
> $$P \land Q \equiv \neg (\neg P \lor \neg Q)$$
> 
> Dal punto di vista semantico, il connetivo $\land$ è ridondante in presenza dei connetivi $\neg$ e $\lor$ : si potrebbe eliminare, sostituendo tutte le sue occorrenze

Per la seconda:
Similmente, dall'equivalenza
$$\neg (P \lor Q) \equiv \neg P \land \neg Q$$
si ottiene 
$$\neg \neg (P \lor Q) \equiv \neg (\neg P \lor \neg Q)$$

##### Tautologie

Alcune asserzioni risultano sempre vere, indipendentemente dal contesto in cui è interprete.

> [!example] 
> L'asserzione $P \lor \neg P$ è vera (principio del terzo escluso)
> Infatti, se $P$ è vera, allora segue $P \lor \neg P$
> Se invece $P$ è falsa, allora $\neg P$ è vera, quindi ancora $P \lor \neg P$ è vera

Le affermazioni che sono sempre vere in qualunque contesto vengono chiamate *tautologie*.
Quindi $Q$ è una tautologia se e solo se 
$$\models Q$$
$Q$ è sempre vera senza che ci siano degli ipotesi

Un'asserzione che risulta falsa in ogni contesto in cui sia interpretata si dice *contraddizione*
Quindi se $Q$ è una tautologia, allora $\neg Q$ è una contraddizione

> [!example] 
> $\neg (P \lor \neg P)$ è una contraddizione
> Usando le propietà viste
> $$\neg (P \lor \neg P) \equiv \neg P \land \neg \neg P \equiv \neg P \land P \equiv P \land \neg P$$

Supponiamo che $P$ sia una contraddizione di $Q$ un'asserzione qualsiasi.
Allora $$P \models Q$$
Infatti in qualunque contesto sia vera $P$ e sia vera $Q$, in quanto non c’e alcun contesto in cui $P$ sia vera: da un’affermazione sempre falsa, in questo caso $P$, segue qualsiasi conseguenza $Q$.
