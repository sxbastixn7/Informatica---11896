Docenti
- Conca (Prima parte)
- Fugacci (Seconda parte)

## **Insiemi**

### Insieme dei numeri naturali

$\mathbb{N}$ = insieme dei numeri naturali
-  $\mathbb{N} = \{0,1,2,3,...\}$

$3 \in \mathbb{N}$ -> 3 appartiene ai numeri reali

### Insieme dei numeri interi

$\mathbb{Z}$ = insieme dei numeri interi
- $\mathbb{Z} = \{0,1,-1,2,-2, ... \}$

$-1 \in \mathbb{Z}$  oppure  $\mathbb{Z} \ni -1$

### Insieme dei numeri razionali

$\mathbb{Q}$ = insieme dei numeri razionali
- $\mathbb{Q} = \{ \frac{a}{b} : a \in \mathbb{Z} , b \in \mathbb{Z} , b\neq 0 \}$

$1/2 \in \mathbb{Q}$  ; $-1/3 \in \mathbb{Q}$  ; $\frac{\sqrt{2}}{\sqrt{3}} \notin \mathbb{Q}$ 

> [!important] 
> Per quest'ultimo devono essere interi per appartenere all'insieme dei razionali
> 

### Insieme dei numeri reali

$\mathbb{R}$ = insieme dei numeri reali

$\sqrt{2} \in \mathbb{R}$ ; $\pi \in \mathbb{R}$ ; $\mathrm{e} \in \mathbb{R}$ 

--- 
$\mathbb{N}$

A = {0, 2, 7, 41} $\subseteq$ $\mathbb{N}$
$7 \in \mathbb{N}$
$8 \notin \mathbb{N}$

l'ordine con cui scrivo gli elementi non è importante :  A = $\{2, 0, 41, 7\}$

B = $\{ a \in \mathbb{N} : a^2 + 7 \ge 25 \}$

$3 \in B$ ?

-  $3^2 + 7 = 16$, NO ;  non soddisfa la condizione.
- $5^2 + 7 = 32$, SI ;  soddisfa la condizione.

C = $\{a \in \mathbb{Z}$ : $a^2 \ge 10$  e $a^3 \le 5 \}$

- $a=-4$ 
- $a^2 = -4^2 = 16$ 
- $a^3 = -4^3 = -64$ 
- SI SODDISFANO ENTRAMBE LE CONDIZIONI

X = matricola informatica 25/26 percorsa A

$T = \{a \in x : a$ è $doriano$  e  $a$  è $genoano\}$
- $T$ non ha elementi e si scrive 
	- $T = \{\}$
	- $T = \emptyset$

$\emptyset$ è l'insieme vuoto.

--- 
$\{m \in \mathbb{N}$ : $n^2 < 0\} = \emptyset$

un numero alla seconda $(n^2)$ non può essere negativo. 

--- 
## GENERALE

se X è un insieme

allora: 
- $x \subseteq X$
- $\emptyset \subseteq X$

> [!example] 
> $X = \{0, 1\}$
> Quanti sottoinsieme ha X?
> I sotto insiemi sono: 
> - $\{0, 1\}$
> - $\{0\}$
> - $\emptyset$
> - $\{1\}$

> [!example] 
>  Cosa significa $B \subseteq A$ ?
>  
>  significa che ogni elemento di $B$ è un elemento di $A$.
>  - $\forall b \in B \implies b \in A$

Dato un insieme di X

$A \subseteq X$ , $B \subseteq X$ 

$A$ $\cap$ $B$ = $\{x \in X : X \in A$ e $X \in b\}$
$A$ \ $B$ = $\{X \in A : X \notin B\}$

$Cx (A) = X$ \ $A = \{x \in X : x \notin A\}$ = $\overline{A}$

\ sta per 'non stanno'

---
$X = \{ 0, 1, 2, 3, 4, 5, 6, 7, 8, 9\}$
$A = \{0, 1,2, 3, 9\}$
$B = \{1, 3, 7, 8\}$

$A \cap B = \{1, 3\}$
$A \cup B = \{0, 1 ,2, 3, 9, 1, 3, 7, 8 \} = \{0, 1, 2, 3, 7, 8, 9\}$

$A$ \ $B = \{0, 2, 9\}$
$B$ \ $A = \{7, 8\}$

$Cx(A) = \{4, 5, 6, 7, 8\}$ $=$ $X$ \ $A$

Quindi $\cap$ , $\cup$ sono operazioni binarie mentre $Cx$ è unaria.

$\cap$ = intersezione
$\cup$ = unione

---
## Propietà delle operazioni

1. $X+Y=Y+X$   somma commutativa
2. $(X+Y)+Z=X+(Y+Z)$  somma associativa
3. $-(-X)=X$
4. $X * (Y+Z)=X * Y+X * Z$  , ***VERA*** ; $X + (YZ) = (X+Y) * (X+Z)$ , ***FALSA***

$A, B \subseteq X$

$\subseteq$ = sottoinsieme

1. 1) $A \cap B = B \cup A$ ; vera
2. 1) $A \cup B = B \cap A$ ; vera
3. 2) $(A \cup B) \cup C = A \cup (B \cup C)$ ; vera
4. 2) $(A \cap B) \cap C = A \cap (B \cap C)$ ; vera
5. 3) $Cx (Cx(A)) = A$
	$Cx (A \cup B) = Cx(A) \cup Cx(B)$
	$Cx (A \cap B) = Cx(A) \cap Cx(B)$
> [!info] 
> Queste sono formule di Morgan
> 

6. 4) $A \cap (B \cup C) = (A \cap B) \cup (A \cap C)$
7. 4) $A \cup (B \cap C) = (A \cup B) \cap (A \cup C)$

---
$X = \{0, 1, 2, 3, 4, 5\}$
$A=\{0, 1, 2, 3\}$
$B=\{2, 3, 4\}$
$A \cap B = \{0, 1, 2, 3, 4\}$
$Cx(A \cup B) = Cx(\{0, 1, 2, 3, 4\}) = \{5\}$

$Cx(A) = \{4, 5\}$
$Cx(B) = \{0, 1, 5\}$
$Cx(A) \cap Cx(B) = \{4, 5\} \cap \{0, 1, 5\} = \{5\}$

---
$a_{1}, a_{2}, ... , a_{n} \in \mathbb{N}$
$a_{1} + a_{2} + ... + a_{n} \in \mathbb{N}$
$\sum_{=1} a_{x} = a_{1} + a_{2} + ... + a_{n}$

---
$X=\mathbb{N}$   $i \in \mathbb{N}$
$A_{i} \{a \in \mathbb{N} : a^2 \ge i\}$
$A_{20} \{a \in \mathbb{N} : a^2 \ge 20\} = \{5, 6, 7, 8 \dots$
$A_{100} \{a \in \mathbb{N} : a^2 \ge 100\}$

$X, Y$ insiemi 
$X * Y$ prodotto cartesiano di $X$ con  $Y$ 
$X * Y = \{(X, Y) : x \in X, y\in Y\}$
$(X, Y) = (X_{1}, Y_{1}) \iff X = X_{1}$ e $Y = Y_{1}$

> [!example] 
> $X = \{0, 1\}$  $Y= \{a, b, c\}$
> $X * Y = \{(0, a), (0, b), (0, c), (1, a), (1, b), (1, c)\}$
> 



























