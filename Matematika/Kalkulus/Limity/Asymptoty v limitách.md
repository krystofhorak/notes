## Vysvětlení

* objevuje se zde koncept nekonečna
* ve funkcích kde se nachází asymptota lze také hledat limitu
* pokud existuje limita, je v bodě asymptoty $\infty$ nebo $-\infty$, shoduje-li se v obou stranách
* limita o hodnotě $\pm\infty$ může platit pro jednu či obě strany

## Ukázka

Mějme funkci, kde se objevuje asymptota, například funkci $f$. Tato funkce by mohla vypadat následovně:
$$
f(x) = |\frac{1}{x}|; x \neq 0
$$
![[graph-4.png | 400]]

V této funkci se objevuje asymptota v bodě 0 na ose x. K jakému číslu se blíží hodnota právě v tomto bodě? Limita je v tomto bodě neomezená; její hodnota nekonečně narůstá. Proto můžeme tvrdit, že limitou je nekonečno ($\infty$). Zapíšeme jako:
$$\lim_{x \to 0}f(x) = \infty$$
Přesně k nekonečnu tato funkce nikdy nedojde, bude se k němu jen více a více přibližovat. To je ostatně i to, co nám tato limita říká.

## Jednostranná limita

U některých funkcí s asymptotou můžeme zjistit přesný limit alespoň z jedné strany, který se nepřibližuje nekonečnu. Vezmeme si například funkci $g$, která vypadá takto:
$$
g(x) =
\begin{cases}
|\frac{1}{x-2}|, x < 2\\
(x-3) \cdot sin(x), x \geq 2
\end{cases}
$$
![[graph-5.png | 400]]

Jaká je limita funkce $g(x)$, když se $x$ blíží k 2? Tuto limitu nenajdeme, protože se liší limita pravá a levá. Můžeme ale najít právě tyto jednostranné limity.
$$\lim_{x \to 2}g(x) = \nexists$$
$$\lim_{x \to 2^-}g(x) = \infty$$
$$\lim_{x \to 2^+}g(x) = -sin(2)$$
Limitu strany levé lze zjistit dosazením čísla 2, ke kterému v této funkci existuje korespondující hodnota. Po dosazení získáme: $(2 - 3) \cdot sin(2)$, zjednodušíme na $-sin(2)$ a zaokrouhleno na 2 desetinná čísla: $-0.91$.