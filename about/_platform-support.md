## Suport de plataformes

Un dels aspectes més apasionants del desenvolupament de Swift a l'espai obert és saber que és gratuit poder transferir-lo a una gran varitat de plataformes, dispositius i altres casos d'ús.

El nostre objectiu és proveir la compabilitat del codi font de Swift entre totes les plataformes, encara que la implementació dels mecanismes puguin diferir de plataforma en plataforma. El pricipal exemple és que les plataformes d'Apple inclouen el *runtime* d'Objective-C, que és necessari per accedir als *frameworks* de les plataformes d'Apple com, per exemple, UIKit i AppKit. En altres plataformes, com Linux, no hi ha presència del *runtime* d'Objective-C perquè no és necessari.

El [projecte de llibreries nucli Swift](/core-libraries/) aspira a extendre les capacitats multiplataforma de Swift proporcionant implementacions portables dels *frameworks* fonamentals d'Apple (com Foundation) sense necessitar dependències del *runtime* d'Objective-C. Tot i que les llibreries nucli encara es troben en les etapes inicials de desenvolupament, en un futur no molt llunyà proporcionaran a Swift una compatibilitat millorada del seu codi font entre totes les plataformes.

### Plataformes d'Apple

Swift pot ser utilitzat mitjançant un Mac per desenvolupar programari a totes les plataformes d'Apple: iOS, macOS, watchOS i tvOS. A més a més, les construccions binàries del codi obert de Swift estan integrades amb les eines de desenvolupador d'Xcode, incloent un suport complet per a tot el sistema de construcció d'Xcode, per al completament de codi a l'editor i per a la depuració integrada, permetent experimentar a tothom els últims desenvolupaments de Swift en un entorn Cocoa i Cocoa Touch familiar.


### Linux

Swift pot ser usat a Linux per construir llibreries Swift i aplicacions. Les construccions binàries de codi obert proporcionen el compilador Swift i la llibreria estàndard, el Swift REPL i el depurador (LLDB) i les [llibreries nucli](/core-libraries/). Així, qualsevol pot desenvolupar codi en Swift mitjançant Linux.


### Windows

Open source Swift can be used on Windows to build Swift libraries and applications. The open source binary builds provide C/C++/Swift toolchains, the standard library, and debugger (LLDB), as well as the [core libraries](/core-libraries/), so one can jump right in to Swift development. SourceKit-LSP is bundled into the releases to enable developers to be quickly productive with the IDE of their choice.

### New Platforms

We can't wait to see the new places we can bring Swift---together.  We truly believe that this language that we love can make software safer, faster, and easier to maintain.  We'd love your help to bring Swift to even more computing platforms.
