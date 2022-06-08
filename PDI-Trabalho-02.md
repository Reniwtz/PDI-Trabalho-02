<p align = "justify">&nbsp;&nbsp;&nbsp;&nbsp;Neste trabalho, a DCT (1D e 2D) (direta e inversa) deve ser desenvolvida utilizando as equações estudadas em sala de aula, sem o uso de bibliotecas prontas para esse fim.</p><br>

<p align = "justify">1 - Dada uma imagem I em níveis de cinza, de dimensões RxC, desenvolva um programa para:</p>

<p align = "justify">&nbsp;&nbsp;&nbsp;&nbsp;1.1 Exibir o módulo normalizado (expansão de histograma para [0, 255]) da DCT de I, sem o nível DC, e o valor (numérico) do nível DC</p>

<p align = "justify">&nbsp;&nbsp;&nbsp;&nbsp;1.2. Encontrar e exibir uma aproximação de I obtida preservando o coeficiente  DC e os n coeficientes AC mais importantes de I, e zerando os demais. O parâmetro n é um 
inteiro no intervalo [0, RxC-1].</p><br>

<p align = "justify">2. Desenvolva um programa para filtrar uma imagem I de dimensões RxC, utilizando um filtro de Butterworth passa-baixas no domínio da frequência. A função de transferência do filtro é dada por:
<!--\begin{math}
H(d(k,l)) = \frac{1}{\sqrt{1+\left( \frac{d(k,l)}{{fc}} \right)^{2n}}}
\end{math}-->
<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<p>
\[H(d(k,l)) = \frac{1}{\sqrt{1+\left( \frac{d(k,l)}{{fc}} \right)^{2n}}}\]
</p>

em que d(k,l) é a distância euclidiana do coeficiente (k,l) até a origem, fc é a distância de corte até a origem e n >= 1 é a ordem do filtro.</p><br>

<p align = "justify">3. Desenvolva um programa para filtrar um sinal s, em formato .wav, com N amostras, utilizando um filtro de Butterworth passa-baixas no domínio da frequência. A função de transferência do filtro é dada por:<br>
<!--\begin{math}
H(f) = \frac{1}{\sqrt{1+\left( \frac{f}{{fc}} \right)^{2n}}}
\end{math}-->
\[H(f) = \frac{1}{\sqrt{1+\left( \frac{f}{{fc}} \right)^{2n}}}\]
em que f é a frequência em Hz, fc é a frequência de corte em Hz e n > 1 é a ordem do filtro.</p>
