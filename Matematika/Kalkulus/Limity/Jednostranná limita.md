## Definice

- označuje limitu funkce, u které se řeší směr, pomocí kterého se přibližujeme k hodnotě
- existuje levá a pravá
- pokud existuje limita u funkce, pak existují obě jednostranné limity
- zároveň ale nemusí existovat ani jedna z nich

## Ukázka

Pro ukázku využijme funkci $h$, která se vyskytovala i v zápiscích o [[Limity|limitách]]:
$$
h(x) =
\begin{cases}
x^2, x < 2\\
5-\frac{x-4}{x}, x \geq 2
\end{cases}
$$
![[graph-3.png | 400]]

Jak víme, limitu funkce $h(x)$, když se $x$ blíží k 2, určit nemůžeme, protože by tato limita závisela na směru změny proměnné x. Můžeme ale zjistit limitu právě pro daný směr:
$$\lim_{x \to 2^-}h(x) = 4$$
$$\lim_{x \to 2^+}h(x) = 6$$
Při bližším zkoumání zjistíme, že se tyto 2 limity liší jejich přibližováním se. V prvním limitu se přibližujeme k $2^-$ a v druhém k $2^+$. Znaménko v exponentu nám říká, kterým směrem se k nějaké hodnotě, v tomto případě číslu 2, přibližujeme.

Známénko **minus** (-) znamená, že se pohybujeme směrem od záporných čísel ke kladným, tedy **doprava**. Tuto limitu označujeme jako **pravou limitu**. Známénko **plus** (+) pak nařizuje pohyb směrem k záporným číslům od kladných, tedy směrem **doleva**, jedná se tedy o **levou limitu**. Po grafickém ověření zjistíme, že naše výroky skutečně platí.