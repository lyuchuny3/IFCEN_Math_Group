**Lemme**: Soit q $\in \mathbb N^*.$ Pour tout $l\in [|0,q|],$
$$\sum_{p=0}^q(-1)^p\binom{q}{p}p^l=\left\{
\begin{aligned}
0&\quad\text{ si }l\in [|0,q-1|];\\
(-1)^qq!&\quad\text{ si }l=q.\\
\end{aligned}\right.$$
**Indication**: On pourra considérer le développement limité à l'ordre $q$ de $x\longmapsto (e^x-1)^q$ au voisinage de 0.
**Preuve**: D'après la formule du binôme, on a: 
$$(e^x-1)^q=\sum^q_{p=0}\binom{q}{p}(-1)^{q-p}e^{px}.$$
Par suite, en effectuant dans chaque terme le développement limité de $x\longmapsto e^{px}$ à l'ordre $q$ au voisinage de 0, on obtient:
$$\begin{aligned}
(e^x-1)^q&\underset{x\to 0}=\sum^q_{p=0}\binom{q}{p}(-1)^{q-p}\left(\sum^q_{k=0}\frac{(px)^k}{k!}+o(x^q)\right)\\
&\underset{x\to 0}=\sum^q_{k=0}\frac{1}{k!}\left(\sum^q_{p=0}\binom{q}{p}(-1)^{q-p}p^k\right)x^k+o(x^q).
\end{aligned}$$
Or $(e^x-1)^q\underset{x\to 0}\sim x^q$. Par  unicité du développement limité à l'ordre $q$ au voisinage de 0, on a: $$\sum_{p=0}^q(-1)^p\binom{q}{p}p^l=\left\{
\begin{aligned}
0&\quad\text{ si }l\in [|0,q-1|];\\
(-1)^qq!&\quad\text{ si }l=q.\\
\end{aligned}\right.$$ 

这个证明表现了DL在证明一些特殊的等式中的作用,是DL的一个很少见的应用,(DL本来是用作近似的，却可以拿来作为证明精确相等关系的桥梁，这点值得大家去体会)

à continuer... 

