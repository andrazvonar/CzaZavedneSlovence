# Slovenšćina.h

### Primer uporabe
```c
#include "slovenščina.h"
#include <stdio.h>
#include <stdlib.h>

celo glavni() {

  celo a = 12;
  realno b = 1.0;

  znak niz[] = "slovenščina";
  celo *seznam = dodelispomin(5 * velikost(celo));

  ce (seznam == NIC) {
    natisnio("Premalo spomina");
    vrni 1;
  }

  za (celo i = 0; i < 5; i++) {
    seznam[i] = i;
  }

  znak z = " ";
  celo stevec = 0;
  dokler (z != '\0') {
    z = seznam[stevec];
    natisnio("%c ", z);
    stevec++;
  }

  vrni 0;
}
```
