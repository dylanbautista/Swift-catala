---
layout: page
title: Sobre Swift
---

Swift és un llenguatge de programació de propòsit general, construit amb un enfocament modern en seguertat i rendiment; seguint els patrons actuals del disseny del software.

L'objectiu del projecte Swift és crear el millor llenguatge a l'abast per poder-lo utilitzar des de la programació de sistemes, fins aplicacions mòbils o d'ordinador, passant per serveis al núvol. Més important encara, Swift està dissenyat per fer de l'esriptura i del manteniment de programes *correctes* un procés més senzill per al desenvolupador. Per aconseguir-ho, nosaltres creiem que la forma més obvia d'escriure codi en Swift ha de ser també:

**Segura.** La forma més obvia d'escriure codi hauria d'advocar per la seguretat. Els comportaments indeterminats són els principals enemics de la seguretat i, per consegüent, els errors dels desenvolupadors haurien de ser captats abans que el software estigui en fase de producció. Optar per la seguretat significa que, de vegades, Swift es comportarà estrictament, però nosaltres creiem fermament que la claredat estalvia temps al llarg termini.

**Ràpida.** Swift està pensat per ser un reemplaçament dels llenguatges basats en C (C, C++ i Objective-C). Per tant, cal que Swift sigui comparable a aquests llenguatges en rendiment per a la majoria de les tasques. El rendiment ha de ser també predictible i consistent, no només ràpid en petits períodes que requereixen una neteja posterior. Hi ha molts llenguatges amb característiques originals, tanmateix, ésser ràpid és rar.

**Expressiva.**  Swift es beneficia de dècades d'avançaments en les ciències de la computació per oferir una sintaxi que dona gust usar, amb característiques modernes que els desenvolupadors d'avui en dia esperen. Però Swift mai està satisfet. Nosaltres monitorarem els progressos del llenguatge i mantindrem allò que funciona, fent evolucionar contínuament Swift per fer-lo encara millor.

Les eines són una part crítica de l'ecosistema Swift. Nosaltres ens esforcem durament per integrar Swift correctament dins del conjunt d'eines dels desenvolupadors, per compondre ràpidament codi, per presentar diagnòstics excel·lents i per possibilitar experiències interactives de desenvolupament. Les eines poden fer la programació més potent, com ho fan les playgrounds basades en Swift a Xcode o com ho fa REPL basat en la xarxa amb el codi d'un servidor Linux.

## Característiques

Swift inclou característiques que fan que el codi sigui més fàcil de llegir i d'escriure, deixant al desenvolupador el control que es necessita en un verdader llenguatge de programació de sistemes. Swift suporta tipus de dades inferits per fer el codi més net i menys propens a patir errades. També, els mòduls eliminen les capçaleres (headers) i proveeixen espais de noms (namespaces). La memòria s'administra automàticament, i inclús no és necessari que vostè escrigui punts i comes (;) al codi. Swift, a més, utilitza característiques d'altres llenguatges. Per exemple, els noms d'instància dels paràmetres d'Objective-C; que són expressats seguint una sintaxi neta que fa que les APIs siguin fàcils de llegir i mantenir a Swift.

Les característiques de Swift estan dissenyades per treballar conjuntament amb l'objectiu de crear un llenguatge potent i divertit d'usar al mateix temps. Algunes característiques addicionals de Swift són les següents:

* Clausures unificades amb paràmetres de funcions
* Tuples i múltiples valors de retorn
* Objectes de tipus genèric
* Iteracions ràpides i concises en un rang o en una colecció
* Estructures (*structs*) que suporten mètodes, extensions i protocols
* Patrons de porgramació funcional, v. g., map o filter
* Manipuladors d'errors potents
* Flux de control (*control flow*) avançat amb les paraules clau `do`, `guard`, `defer` i `repeat`

### Seguretat

Swift ha sigut dissenyat des del començament per ser més segur que els llenguatges basats en C. Elimina classes senceres de codi insegur. Les variables sempre s'inicialitzen abans de ser utilitzades, les arrays i els enters són sempre comprovades per si generen desbordament (overflow) i la memòria és administrada de forma automàtica. La sintaxi està feta perquè sigui fàcil definir les seves intencions - com, per exemple, un pot definir amb una paraula clau de tres caràcters una variable (`var`) o una constant (`let`).

Una altra característica de seguretat és que, per defecte, els objectes en Swift no poden ser mai `nil`. Intentar crear o utilitzar un objecte `nil` genera un error de compilació. Això fa que l'escriptura de codi sigui més fàcil i segura; prevé una causa comuna de crashes quan s'executa el codi. Tanmateix, hi ha casos on fer ús d'objectes `nil` és apropiat, i per a aquestes situacions Swift té una innovadora solució anomenada **optionals** (opcionals). Un `optional` pot contenir el valor `nil`, però la sintaxi de Swift li força a administrar-ho de forma segura emprant ``?`` per indicar al compilador que vostè entén el seu comportament i que ho manipularà de forma segura.

{% include_relative _open-source.md %}
{% include_relative _platform-support.md %}
