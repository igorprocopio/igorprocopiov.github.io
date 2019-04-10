
Markdown Jupyter
=================




Sumário 
--------

 [1 Títulos](#1-Títulos)
 
 [2 Textos e marcações](#2-Textos-e-marcações)
 
 [3 Listas](#3-Listas)
 
 [4 Equações](#4-Equações)

 [5 Local Files](#5-Local-Files)
 
 [6 Tabelas](#6-Tabelas)
 

# 1 Títulos

# Teste visão

# A b V h G t o p K L A
## P L A M F m f u n h m d k
### L p s N g h F d a b q A T E n a
#### q A T E n a f k l j A b V h L p s N g h
##### h F d a b q A T E f k l j L p s N g h L K m K L 
###### M F m f u n h m d k A M A b V h L U I Y E J F D S

# 2 Textos e marcações


Texto normal, 
paragrafo espaço de uma linha

 Destaques:
 
 *italico*   ou  _italico_ ou no jupyter via html <i>italico</i>
 
 **Negrito** ou __negrito__ ou no jupyter via html <b>marcação</b>
 
 ***negrito itálico*** 
 
esta é a estrutura de `__sublinhado__` em markdown, jupyter contudo converte em negrito.


no jupyter via html <u>marcação</u>



 
 ~~tachado~~ ou no jupyter via html <s>sublinhado</s>
 
 `codigo` com texto
 
 ```
bloco de código.

```

 
<h1 style="border:4px solid Violet;"> Teste a box com cores em HTML
   <br />  <br /> 
    como escrever a cor:   <br /> 
Tomato;    Orange;    DodgerBlue;     MediumSeaGreen;    Gray;    SlateBlue   
</h1>
 
 
Há um <br /> acima de mim!
 
 
> Esta é uma citação de bloco. Você pode 
> manualmente quebrar suas linhas e colocar um `>` antes de cada linha ou você pode deixar suas linhas ficarem muito longas e ficarem por conta própria. 
> Não faz diferença, desde que iniciem com um `>`.

> Você também pode usar mais de um nível
>> de indentação?
> Quão bom é isso?


<!-- texto oculto --> 



***

---

- - -

****************
 


```python
from IPython.display import Markdown
def f(x):
    """a docstring"""
    return x**2
a1 = f(10)
```


```python
a1
```




    100



# 3 Listas
 - One
   - Sublist
        - This
 - Sublist - That - The other thing
   - Two
   - Sublist
  - Three
     - Sublist
     

+ Item
+ Item
+ Mais um item
     
     
     
     
   1. Here we go
            1.1. Sublist
            1.2. Sublist
   2. There we go
   3. Now this


   - a. Here we go
       - b.1. Sublist
       - a.1. Sublist
   - b. There we go
   - c. Now this


Caixas abaixo sem o 'x' são caixas de seleção HTML desmarcadas.

1. [ ] Primeira tarefa para concluir.
2. [ ] Segunda tarefa que precisa ser feita


Esta caixa de seleção abaixo será uma caixa de seleção marcada em HTML.
3. [X] Esta tarefa foi concluída



# 4 Equações



Podem ser escritas em LaTex 
([link1](https://www.overleaf.com/learn/latex/Mathematical_expressions)
[link2](https://www.authorea.com/users/77723/articles/110898-how-to-write-mathematical-equations-expressions-and-symbols-with-latex-a-cheatsheet)) 
com praticamente todas as funcionalidades:

- usar letras gregas: $\alpha$, $\beta$, $\gamma$, $\Gamma$, $\varphi$, $\phi$. 
- usar operadores: $f, \Diamond, \forall, \partial, \exists, \nabla, \in, \notin, \ni, \prod, \sum, \int, \iint, \iiint$.

- Funções básicas: 

${1\over z}$, ${1\over\displaystyle 1+{1\over x}}$

$e^{i\pi} + 1 = 0$

$e^x=\sum_{i=0}^\infty \frac{1}{i!}x^i$

 - Multiplicação	$x\times y$

 - Divisão $x/y$ ou $\frac{x}{y}$

 - Subscrito  $x_{y_z}$

 - Sobrescito $x^{y^z}$

 - Conjunto $\mathbb{N} = \{1, 2,\ldots\}$


- centrar fórmulas complexas:

$$\left|{1\over N}\sum_{n=1}^N \gamma(u_n)-{1\over 2\pi}\int_0^{2\pi}\gamma(t){\rm d}t\right| \le {\varepsilon\over 3}.$$


\begin{eqnarray}
f(x) = \sum_{i=0}^{n} \frac{a_i}{1+x} \\
\textstyle f(x) = \textstyle \sum_{i=0}^{n} \frac{a_i}{1+x} \\
\scriptstyle f(x) = \scriptstyle \sum_{i=0}^{n} \frac{a_i}{1+x} \\
\scriptscriptstyle f(x) = \scriptscriptstyle \sum_{i=0}^{n} \frac{a_i}{1+x}
\end{eqnarray}

 - matrizes

  \begin{pmatrix} 
  x & y \\ 
  z & v \\
  \end{pmatrix}
  
   \begin{bmatrix} 
  0 & \cdots & 0 \\ 
  \vdots & \ddots & \vdots \\ 
  0 & \cdots & 0 \\
  \end{bmatrix}
  

Latex é quase sempre uma alternativa melhor para fórmulas matemáticas complexas, 
contudo markdown Jupyter permite também construir em HTML.

[HTML](https://www.w3schools.com/html/html_symbols.asp) [link2](https://www.w3.org/MarkUp/HTMLPlus/htmlplus_45.html)

- usar letras gregas: &alpha;, &beta;, &gamma;, &Gamma;, &varphi;,  &phi;.
- usar operadores: &fnof;, &loz;, &forall;, &part;, &exist;, &nabla;, &isin;, &notin;, &ni;, &prod;, &sum;,  &int;, &int;&int;, &int;&int;&int;.

 - função básica html 
<math>
	H(s) = &int;<sub><sub>0</sub></sub><sup>&infin;</sup> e<sup>-st</sup> h(t) dt
</math>

# 5 Local Files


   [Clique em mim!](http://www.ufjf.br/econs)

  <img src="ECONS4.jpg" />

  <img src="Jupytert.gif" />

   
   
  <iframe src="URL"></iframe>


# 6 Tabelas

| Nome | Vertices | Arestas | Faces | V-A+F |
| :-- | --: | :-- | --: | :-: |
| Tetraedro | 4 | 6 | 4 | 2 |
| Octaedro | 6 | 12 | 8 | 2 |
| Cubo | 8 | 12 | 6 | 2 |
| icosaedro | 12 | 30 | 20 | 2 |
| Dodecaedro | 20 | 30 | 4 | 2 |


`| :-- |`  &rarr; alinhar a esquerda

`| --: |`  &rarr;  alinhar a direita

`| :-: |`  &rarr; centralizar

`| --- |`  &rarr; centralizar

1. table test

| centered header | regular header | right-justified header | centered header | regular header|
|:-:|-|-:|:-:|-|
|centered cell|regular cell|right-justified cell|centered cell|regular cell|
|centered cell|regular cell|right-justified cell|centered cell|regular cell|


Tabelas em HTML em caso de mais formatações...

<table class="table">
<caption>Tabela 1 - Total de Trabalhadores - </caption>
<thead><tr><th>CBO</th><th>Brasil</th><th>Estado</th><th>Mesorregão</th><th>Microrregião</th><th>Município</th></thead></thead><tbody>
<tr>
<td>Forças armadas</td><td>              .</td><td>              .</td><td>              .</td><td>              .</td><td>              .</td></tr>
<tr>
<td>Poder público</td><td>         -4.987</td><td>           -666</td><td>            -59</td><td>            -16</td><td>            -22</td></tr>
<tr>
<td>Ciências e artes</td><td>          7.659</td><td>            617</td><td>            111</td><td>             31</td><td>             27</td></tr>
<tr>
<td>Técnicos de nível médio</td><td>          8.345</td><td>          1.031</td><td>            -32</td><td>            -28</td><td>            -26</td></tr>
<tr>
<td>Serviços administrativo</td><td>          4.894</td><td>            -94</td><td>            240</td><td>            172</td><td>            126</td></tr>
<tr>
<td>Serviços e comércio</td><td>        -34.219</td><td>         -4.600</td><td>           -584</td><td>           -399</td><td>           -335</td></tr>
<tr>
<td>Agropecuária</td><td>         -2.081</td><td>           -333</td><td>           -182</td><td>            -10</td><td>              0</td></tr>
<tr>
<td>Bens e serviços industriais 1</td><td>         50.481</td><td>          4.987</td><td>           -130</td><td>             55</td><td>            -62</td></tr>
<tr>
<td>Bens e serviços industriais 2</td><td>           -720</td><td>           -222</td><td>            -57</td><td>            -21</td><td>            -25</td></tr>
<tr>
<td>Reparação e manutenção</td><td>          4.941</td><td>            772</td><td>            -64</td><td>            -45</td><td>            -48</td></tr>
<tr>
<td></td><td>              .</td><td>              .</td><td>              .</td><td>              .</td><td>              .</td></tr>
</tbody></table>


```python

```
