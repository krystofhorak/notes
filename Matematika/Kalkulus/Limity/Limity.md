## Definice

- kontrukce vyjadřující, že se hodnoty zadané funkce blíží libovolně blízko k nějakému bodu
- tento bod se označuje jako "limita"
- zápis: $\lim_{x \to a}f(x) = A$

## Ukázky

Mějme funkci $f$, kde $f(x) = \frac{x-1}{x-1}; x \neq 1$. Po dosazení několika ukázkových hodnot do tabulky získáme tento výsledek:

|  x   | -1 | 0 | 1 | 2 |   
| ---- | -- | - | - | - |
| f(x) | 1  | 1 | - | 1 |

![[graph-1.png | 400]]

Tato funkce nedává smysl pro číslo 1, protože by nastalo nedefinované dělení nulou. Proto hodnota pro $f(x)$, kde $x = 1$ neexistuje. Můžeme se ale zeptat k jaké hodnotě se tato funkce přibližuje, když se blížíme k bodu 1 na ose x. Z grafu je jasné, že touto hodnotou je číslo 1. Můžeme tedy tvrdit, že:
$$\lim_{x \to 1}f(x) = 1$$

Čteme jako "limita funkce $f(x)$, když se $x$ blíží k 1 je rovna 1". Co když ale není jasně zřejmé, k jaké hodnotě se funkce přiibližuje? Mějme na ukázku funkci $g$:
$$
g(x) =
\begin{cases}
x^2, x \neq 2\\
1, x = 2
\end{cases}
$$

Pokud dosazené $x$ není 2, vrací funkce hodnotu $x^2$. V případě, že se $x$ rovná číslu 2, vrací funkce číslo 1. Graf takovéto funkce by vypadal následovně:

![[graph-2.png | 400]]

|  g   | -1 | 0 | 1 | 2 | 3 | 
| ---- | -- | - | - | - | - |
| g(x) | 1  | 0 | 1 | 1 | 9 |

Jaká je limita funkce $g(x)$, když se $x$ blíží k 2? Přestože je hodnota v bodě 2 definovaná jako 1, není to hodnota, ke které se naše $x$ přibližuje. Pro důkaz si můžeme do funkce dosadit hodnoty, které se přibližují hodnotě 2; zaokrouhlejeme na 4 desetinná místa:

| g     | g(x)   | g     | g(x)   |
| ----- | ------ | ----- | ------ |
| 1.9   | 3.61   | 2.1   | 4.41   |
| 1.99  | 3.9601 | 2.01  | 4.0401 |
| 1.999 | 3.9960 | 2.001 | 4.0040 |

Hodnota se z obou směrů (ať už jdeme do minusu nebo do plusu) přibližuje hodnotě 4. Proto můžeme tvrdit, že:
$$\lim_{x \to 2}g(x) = 4$$

Tedy "limita funkce $g(x)$, když se $x$ blíží k 2 je rovna 4". To lze i vypozorovat z grafu funkce $g$.

## Neexistující limita

Limita neexistuje v případě, že hodnota, ke které se proměnná přibližuje je rozdílná ze strany levé a pravé. Pro ukázku mějme funkci $h$:
$$
h(x) =
\begin{cases}
x^2, x < 2\\
5-\frac{x-4}{x}, x \geq 2
\end{cases}
$$

![[graph-3.png | 400]]

Jaká je limita funkce $h(x)$, když se $x$ blíží k 2? Už od pohledu vidíme, že směrem vpravo se hodnota funkce přibližuje k hodnotě 4, ale ze směrem vlevo se jedná o hodnotu 6. Proto limita neexistuje; zapíšeme jako:
$$\lim_{x \to 2}h(x) = \nexists$$

Je ale možné určit limitu jen z jedné strany - [[Jednostranná limita|jednostranná limita]].