# FRAN-C

## What is it ?

**FRAN-C** ("**F**RAN-C **R**eally **A**dresses **N**eed for **C**amembert" or "**F**RAN-C **R**eally **A**dds **N**othing to **C**") is a French programming language aiming at being the crème de la crème for system programming while adding the French touch to your project.

**FRAN-C** is fully compatible with traditionnal C, so you can still use existing libraries without translating them.

## How to use it ?

Just include `baguette.h` in your project and start coding the French way.

You can find all the keywords of the language in [keywords.md](keywords.md).

## Code example

Here are some examples of code snippet translated from traditionnal C to FRAN-C:

<table>
<tr>
<td><center>

**C** 

</center></td>
<td><center>

**FRAN-C**

</center></td>
</tr>
<tr>
<td> 

```C
#include <stdio.h>

int main(int argc, char const *argv[])
{
    printf("Bonjour monde !\n");

    return 0;
}
```

</td>
<td>

```C
#include <stdio.h>
#include "baguette.h"

entier principale(entier argc, caractère immuable *argv[])
{
    imprimerf("Bonjour monde !\n");

    retourner 0;
}
```

</td>
</tr>
<tr>
<td> 

```C
for(int i = 0; i < 5; i++) {
    printf("Baguette !\n");
}
```

</td>
<td>

```C
pour(entier i = 0; i < 5; i++) {
    imprimerf("Baguette !\n");
}
```

</td>
</tr>
<tr>
<td> 

```C
bool boolean1 = false;
bool boolean2 = true;
if(boolean1 && boolean 2) {
    printf("foo");
} else if(boolean1) {
    printf("bar");
} else {
    printf("baz");
}
```

</td>
<td>

```C
bivalent boolean1 = inexact;
bivalent boolean2 = exact;
pourvu_que(boolean1 && boolean 2) {
    imprimerf("foo");
} autrement pourvu_que(boolean1) {
    imprimerf("bar");
} aurtrement {
    imprimerf("baz");
}
```

</td>
</tr>
</table>

## Excuse me what the fuck ?

This project is intended as a joke and was inspired by [brouberol/marcel](https://github.com/brouberol/marcel).

## Contributing

Feel free to contribute and suggest new translations.
