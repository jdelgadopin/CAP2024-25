class: center, up

# Conceptes Avançats de Programació

![:scale 50%](figures/lambda.png)

**Jordi Delgado**, **Gerard Escudero**,

**Curs 2024-25**

![:scale 40%](figures/fib50anysUPC.png)

---

# Conceptes Avançats de Programació

## Guió (provisional): <ins>Programació funcional</ins> (en Clojure)

* Setmanes 1 i 2: [**Clojure: Introducció**](s01_02.html)

* Setmanes 3 i 4: **Programació funcional: Funcions _first-class_**

* Setmanes 5 i 6: **Programació funcional: Closures - Model d'entorns**

* Setmanes 7 i 9: **Programació funcional: Programació funcions ordre superior**

* Setmana 8: _Parcial_

* Setmana 10: **Programació funcional: Immutabilitat EDs**

* Setmana 11: **Programació funcional: Avaluació mandrosa**

* Setmanes 12 i 13: **Macros**

## Llegiu la [guia docent](https://www.fib.upc.edu/ca/estudis/graus/grau-en-enginyeria-informatica/pla-destudis/assignatures/CAP)

---

# Conceptes Avançats de Programació

## Teoria:

**Classes magistrals** amb recolzament de transparències (pensades com a guió de la sessió, no com a apunts), basades en:

* **The Joy of Clojure - 2nd edition**, Fogus, Michael; Houser, Chris, Manning, 2014. ISBN: 9781617291418

* **Clojure Programming: Practical Lisp for the Java World**, Emerick, Chas; Carper, Brian; Grand, Christophe, O'Reilly Media, 2012. ISBN: 9781449394707

* **Mastering Clojure Macros: Write Cleaner, Faster, Smarter Code**, Jones, Colin, The Pragmatic Programmers, 2014. ISBN: 9781941222225

Aquests llibres _haurien_ d'estar a la biblioteca 😭 😭 😭

### Avaluació teoria: 

Un examen parcial i un examen final. **Nota de teoria**: .blue[MAX(final, (parcial + final)/2)]

---

# Conceptes Avançats de Programació

## Laboratori:

### Jutge -  [https://jutge.org](https://jutge.org)

Cal que us registreu amb el vostre correu **@estudiantat.upc.edu**

Apunteu-vos al curs **Problemes en Clojure**

### Avaluació laboratori: 

.cyan[==> **_PER DEFINIR_**]

---

# Conceptes Avançats de Programació

## CAP <ins>NO</ins> és un curs de Clojure

Clojure és un llenguatge de programació molt gran, adequat al _món
real_. 

Nosaltres triarem el **subconjunt que ens convingui**.

## Aspectes de Clojure que no veurem, o només per sobre:

* Namespaces
* Java interop
* Specs
* Concurrència/Multi-Threading: refs & STM, Agents
* Protocols i Datatypes: Interfaces, protocols, datatypes, records.
* Multimètodes
* Metadata
* ... i més coses

---

# Conceptes Avançats de Programació

## Treballar amb Clojure

* [the Clojure CLI](https://clojure.org/guides/install_clojure): És l'utilitat de línia de comandes per gestionar projectes en Clojure que farem servir a CAP.
  És una de les eines més utilitzades i _està instal·lada als laboratoris de la FIB_.

* També es fa servir molt una altra eina anomenada [leiningen](https://leiningen.org/). Quan busqueu informació
  _on-line_ sobre Clojure us la trobareu. La podeu fer servir també, si voleu.
  
## Editors

Qualsevol editor una mica actual té algún _plug-in_ o similar per poder editar Clojure amb comoditat. Per exemple:

* [Calva](https://calva.io/) per a [_Visual Studio Code_](https://vscodium.com/).

* [Cider](https://cider.mx/) per a [_Emacs_](https://www.gnu.org/software/emacs/).

---

# Conceptes Avançats de Programació

## Treballar amb Clojure

És habitual fer servir el **REPL** (_Read, Eval, Print Loop_) en treballar amb Clojure. Provem les
funcions que definim fent-ne prototipus i les testem. Accedirem al **REPL** via terminal o 
via editor/IDE. Sigui com sigui, nosaltres el farem servir molt.

.center[![:scale 90%](figures/Screenshot_2024-08-29_12-34-10.png)]

encara que en realitat el que fa és:

.center[![:scale 90%](figures/Screenshot_2024-08-29_12-34-42.png)]

