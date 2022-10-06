<style>
/* formula */
fm {
    float: left;
    margin-right: 100%;
}
/* rosso */
rs {
    color: red;
}
/* verde */
gr {
    color: green;
}
/* arancione */
or {
    color: orange;
}
</style>

### Resistenze in serie <rs> Essenziale </rs>
Per semplificare più resistenze in serie in una sola detta "equivalente"

<fm> $$ Req = R1 + R2 + ... + Rk $$ </fm>

$Req$ è il valore della resistenza equivalente con unità Ohm ($\Omega$)
$R1; R2; ...; Rk$ sono le resistenze in serie con unità Ohm ($\Omega$)

---
### Resistenze in parallelo <rs> Essenziale </rs>
Per semplificare più resistenze in parallelo in una sola detta "equivalente"

<fm> $$ Req = {1 \over {1 \over R1} + {1 \over R2} + ... + {1 \over Rk}} $$ </fm>

$Req$ è il valore della resistenza equivalente con unità Ohm ($\Omega$)
$R1; R2; ...; Rk$ sono le resistenze in parallelo con unità Ohm ($\Omega$)

---

### 2 Resistenze in parallelo <gr> Opzionale </gr>
Per semplificare 2 resistenze in parallelo in una sola detta "equivalente"

<fm> $$ Req = {R1 * R2 \over R1 + R2} $$ </fm>

$Req$ è il valore della resistenza equivalente con unità Ohm ($\Omega$)
$R1 ;  R2$ sono le 2 resistenze in parallelo con unità Ohm ($\Omega$)

---

### Legge di Ohm <rs> Essenziale </rs>
Per trovare la corrente che attraversa una determinata resistenza sapendo la tensione

<fm> $$ \Delta V = R * I $$ </fm>

$\Delta V$ è la tensione con unità Volt ($V$)
$R$ è la resistenza con unità Ohm ($\Omega$)
$I$ è la corrente con unità Ampere ($A$)

---

### Seconda Legge di Ohm <gr> Esercizio raro </gr>
Per trovare la resistenza di un conduttore sapendo la lunghezza, l'area della sezione e la resistività

<fm> $$ R = \rho * {l \over A} $$ </fm>

$R$ è la resistenza con unità Ohm ($\Omega$)
$\rho$ è la resistività del materiale con unità Ohm Metro ($\Omega m$) oppure Ohm per Millimetro quadro su Metro ($\Omega {mm^2 \over m}$)
$l$ è la lunghezza con unità Metri ($m$)
$A$ è l'area della sezione con unità Metri quadri ($m^2$)

---

### Partitore di tensione <rs> Essenziale </rs>
Per trovare la tensione ai capi di una determinata resistenza in una serie

<fm> $$ \Delta Vn = \Delta V * {Rn \over R1 + R2 + Rn + ... + Rk} $$ </fm>

$\Delta Vn$ è la tensione che vogliamo trovare con unità Volt ($V$)
$\Delta V$ è la tensione ai capi della serie con unità Volt ($V$)
$Rn$ è la resistenza ai capi della quale vogliamo trovare la tensione con unità Ohm ($\Omega$)
$R1; R2; ...; Rk$ sono tutte le resistenze in serie con unità Ohm ($\Omega$)

---

### Partitore di corrente <rs> Essenziale </rs>
Per trovare la corrente che attraversa una determinata resistenza in parallelo ad altre

<fm> $$ In = I * {{1 \over Rn} \over {1 \over R1} + {1 \over R2} + {1 \over Rn} + ... + {1 \over Rk}} $$ </fm>

$In$ è la corrente che vogliamo trovare con unità Amp ($A$)
$I$ è la corrente che attraversa tutte le resistenze con unità Amp ($A$)
$Rn$ è la resistenza della quale vogliamo trovare la corrente che la attraversa con Ohm ($\Omega$)
$R1; R2; ...; Rk$ sono tutte le resistenze in parallelo con unità 1 su Ohm ($1 \over \Omega$)

---

### Generatore equivalente <or> Possibile </or>
Per convertire un generatore di tensione in serie ad una resistenza con un generatore di corrente in parallelo ad una resistenza e vicevers

<fm> $$ E = I * R $$ $$ I = {E \over R} $$ </fm>

$E$ è il generatore di tensione con unità Volt ($V$)
$I$ è il generatore di corrente con unità Ampere ($A$)
$R$ è il valore della resistenza con unità Ohm ($R$)

---

# Kirkoff

### KVL <rs> Essenziale </rs>

---

### Thevenin <rs> Essenziale </rs>
Si usa per semplificare un circuito complesso in uno più semplice

Passo 1
Identificare il carico e rimuoverlo dal circuito

Passo 2
Calcolare il generatore e la resistenza di Thevenin 

Passo 3
Ricollegare il carico