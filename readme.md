# Slovenšćina.h

### Primer uporabe
```c
#include "slovenščina.h"
#include <stdio.h>
#include <stdlib.h>

celo glavni() {

  celo a = 12;
  dvojno b = 1.0;

  znak niz[] = "slovenščina";
  celo *seznam = pdodeli(6 * velikost(celo));

  če (seznam == NIC) {
    natisnio("Premalo spomina");
    vrni 1;
  }

  za (celo i = 0; i < 5; i++) {
    seznam[i] = 65 + i;
  }
  seznam[5] = 0;
  
  znak z = ' ';
  celo stevec = 0;
  dokler (z != '\0') {
    natisnio("%c ", z);
    z = seznam[stevec];
    stevec++;
  }

  vrni 0;
}
```
