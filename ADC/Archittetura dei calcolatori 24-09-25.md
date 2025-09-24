- Docente: D'Agostino

## **L'archittetura**

E' un insieme di attributi come appare al programmatore di sistema (operativo). Si intende la scienza per collegare componenti hardware per creare calcolatori con determinati requesiti funzionali, di prestazioni, di costo. 
## **Architettura calcolatori**

Si divide in due rami: 
- Instruction set architecture (Primo semestre): Come l'hardware viene visto dal software.
- Machine organization (Secondo semestre): Implementazione fisica in termini di blocchi funzionali e logici.

### **Instruction Set Architecture (ISA)**

Categorie di istruzioni
- Load/Store
- Calcoli
- Jump/Branch
- Istruzione speciali

Esempi di architetture
- x86
- ARM
- MIPS
- RISC-V
- PowerPC
- Apple

> [!example] 
> Load di una parola di 32 bit in un registro
> - Risc-V: lwx5, 4(x6)
> - ARM: ldr r3, [r1], #4

Termini più comuni utilizzati:
- Registro
- Accumulatore
- Load
- Move
- Indirizzo
- Byte

### Machine organization

Caratteristiche, numero e prestazione delle unità funzionali (Registrer, ALU).

Un'architettura NON definisce l'implementazione dell'hardware ma bensì descrive le sue funzionalità. Si possono basare sulla stessa ISA, ciò vuol dire che i programmi scritti in un processori AMD funzionerà anche in un processore INTEL. 

### Grandi idee nella progettazione dei calcolatori

- Utilizzo delle astrazioni per semplificare il progetto
- Rendere veloci le stiuazione più comuni
- Prestazioni attraverso il parallellismo 
- Prestazioni attraverso la pipeline
- Prestazione attraverso la predizione
- Gerarchie delle memorie

## Obiettivi del corso

L'obiettivo principale del corso è quello di presentare i paradigmi e le componenti principali alla base dei moderni sistemi di elaborazione che ne determinano le funzionalità e prestazioni. 
Il calcolatore è una risorsa unica e in grado di ese3guire una miriade di componenti eterogenei tra loro in quanto questo esegue algoritmi scritti in un opportuno linguaggio di programmazione. 

- Come vengono tradotti nel linguaggio proprio del calcolatore (Assembly) i programmi scritti in linguaggi ad alto livello (Java, C++, Python) e come fa il calcolatore ad eseguirli

- Cosa determina le prestazioni di un programma
	- L'algoritmo scelto e come questo viene implementato
	- Il linguaggio di programmazione (C, Python, Java) r la sua traduzione nel linguaggio macchina (complilatori ed ottimizzazione)
	- L'efficienza del hardware

## Cos'è un algortimo

E' un insieme di istruzione finito e ripetibile con un algoritmo che non deve essere un ambiguo e sopratutto elementari (fanno parte dell'***ISA***) che porta alla soluzione di un problema da un'input ad un output.

## **Dai chip alle architetture dei calcolatori**

## Chip

E' composto da unwafer di materiale semiconduttore con circuiti elettronici integrati che contiene componenti elettronici microscopici *transistor* che trasmettono segnali di dati. 

I primi calcolatori/macchine
- Macchina analitica di Babbage
- Mark I
- ENIAC
- Macchina di Von Neumann





