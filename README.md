# Invariância do Intervalo: Por Que o Espaço-Tempo Tem uma Régua Própria
 
*Uma explicação passo a passo da Seção 1.6 de Bernard Schutz — o teorema mais importante da Relatividade Especial*
 
> **Antes de começar:** este post assume que você já leu [Geometria do Espaço-Tempo: O Experimento do Relógio de Luz](../relogio-de-luz), onde construímos os eixos $t,x$ e $\bar t, \bar x$ e vimos por que eles ficam inclinados um em relação ao outro. Aqui resolvemos o problema que ficou pendente: **sabemos a direção dos eixos, mas ainda não sabemos a escala** — ou seja, um "metro" no eixo $\bar t$ corresponde a quantos metros no eixo $t$?
 
---

## 1. Vetor entre dois eventos

Dados dois pontos \(E(x_1,y_1,z_1)\) e \(P(x_2,y_2,z_2)\), o vetor que liga \(E\) a \(P\) é \(\vec{EP}\) e pode ser escrito como

$$ \vec{EP} = \langle x_2 - x_1, y_2 - y_1, z_2 - z_1 \rangle. \tag{1.1} $$

O quadrado do comprimento de \(\vec{EP}\) é

$$ |\vec{EP}|^2 = (x_2 - x_1)^2 + (y_2 - y_1)^2 + (z_2 - z_1)^2. \tag{1.2} $$

Se um pulso de luz viaja de \(E\) a \(P\) no intervalo \(\Delta t\), então

$$ |\vec{EP}|^2 = c^2 \Delta t^2. \tag{1.3} $$

Assim,

$$ c^2 \Delta t^2 = (\Delta x)^2 + (\Delta y)^2 + (\Delta z)^2, \tag{1.4} $$

onde \(\Delta x = x_2 - x_1\), \(\Delta y = y_2 - y_1\), \(\Delta z = z_2 - z_1\). Com \(c=1\), temos

$$ \Delta t^2 = (\Delta x)^2 + (\Delta y)^2 + (\Delta z)^2. \tag{1.5} $$

Portanto,

$$ -(\Delta t)^2 + (\Delta x)^2 + (\Delta y)^2 + (\Delta z)^2 = 0. \tag{1.6} $$

Pelo segundo postulado de Einstein, a velocidade da luz é a mesma para todos os observadores inerciais. Qualquer observador inercial mede \(c\), independentemente da velocidade da fonte. Então, para outro observador \(\bar{O}\), vale a mesma relação:

$$ -(\Delta \bar{t})^2 + (\Delta \bar{x})^2 + (\Delta \bar{y})^2 + (\Delta \bar{z})^2 = 0. \tag{1.7} $$

## 2. Intervalo espaço-tempo

Defina o intervalo espaço-tempo por

$$ \Delta s^2 = -(\Delta t)^2 + (\Delta x)^2 + (\Delta y)^2 + (\Delta z)^2. \tag{1.8} $$

Para a luz, \(\Delta s^2 = 0\). Da mesma forma, para \(\bar{O}\),

$$ \Delta \bar{s}^2 = -(\Delta \bar{t})^2 + (\Delta \bar{x})^2 + (\Delta \bar{y})^2 + (\Delta \bar{z})^2. \tag{1.9} $$

Como \(\Delta s^2 = 0\) e \(\Delta \bar{s}^2 = 0\) para a luz, queremos investigar a relação entre \(\Delta \bar{s}^2\) e \(\Delta s^2\). A grandeza geométrica \(\Delta s^2\) é um invariante.

## 3. Transformação linear

Como a transformação entre referenciais inerciais é linear, podemos escrever

$$ \Delta \bar{t} = a_0 \Delta t + a_1 \Delta x + a_2 \Delta y + a_3 \Delta z, \tag{1.10} $$

$$ \Delta \bar{x} = b_0 \Delta t + b_1 \Delta x + b_2 \Delta y + b_3 \Delta z, \tag{1.11} $$

$$ \Delta \bar{y} = c_0 \Delta t + c_1 \Delta x + c_2 \Delta y + c_3 \Delta z, \tag{1.12} $$

$$ \Delta \bar{z} = d_0 \Delta t + d_1 \Delta x + d_2 \Delta y + d_3 \Delta z. \tag{1.13} $$

Substituindo em \(\Delta \bar{s}^2\), obtemos uma forma quadrática nos \(\Delta x^\alpha\). Para organizar, defina

$$ x^0 = t, \quad x^1 = x, \quad x^2 = y, \quad x^3 = z. \tag{1.14} $$

Assim, uma forma geral para o intervalo transformado é

$$ \Delta \bar{s}^2 = \sum_{\alpha=0}^{3} \sum_{\beta=0}^{3} M_{\alpha\beta} \Delta x^\alpha \Delta x^\beta. \tag{1.15} $$

A matriz \(M_{\alpha\beta}\) tem, em princípio, 16 componentes. Como a forma quadrática é simétrica, podemos impor

$$ M_{\alpha\beta} = M_{\beta\alpha}. \tag{1.16} $$

Isso reduz o número de componentes independentes de 16 para 10.

## 4. Restrições impostas pela luz

Para a luz, \(\Delta \bar{s}^2 = 0\) e \(\Delta s^2 = 0\). Considere um feixe de luz viajando na direção \(+x\). Então \(\Delta y = 0\) e \(\Delta z = 0\). Nesse caso,

$$ \Delta \bar{s}^2 = M_{00} \Delta t^2 + 2 M_{01} \Delta t \Delta x + M_{11} \Delta x^2 = 0. \tag{1.17} $$

Para um feixe viajando na direção \(-x\), temos \(\Delta x \to -\Delta x\). Então,

$$ \Delta \bar{s}^2 = M_{00} \Delta t^2 - 2 M_{01} \Delta t \Delta x + M_{11} \Delta x^2 = 0. \tag{1.18} $$

Como as duas expressões devem ser iguais para a luz, concluímos que

$$ 2 M_{01} \Delta t \Delta x = -2 M_{01} \Delta t \Delta x, \tag{1.19} $$

ou seja,

$$ M_{01} = 0. \tag{1.20} $$

De forma mais geral,

$$ M_{0j} = 0, \quad j = 1,2,3. \tag{1.21} $$

Assim, restam apenas \(M_{00}\) e os \(M_{ij}\) com \(i,j = 1,2,3\). Para a luz, com \(c=1\), temos

$$ \Delta t^2 = (\Delta x)^2 + (\Delta y)^2 + (\Delta z)^2 = (\Delta r)^2. \tag{1.22} $$

Logo,

$$ \Delta \bar{s}^2 = M_{00} (\Delta r)^2 + \sum_{i=1}^{3} \sum_{j=1}^{3} M_{ij} \Delta x^i \Delta x^j = 0. \tag{1.23} $$

Mas

$$ (\Delta r)^2 = \sum_{i=1}^{3} \sum_{j=1}^{3} \delta_{ij} \Delta x^i \Delta x^j, \tag{1.24} $$

onde \(\delta_{ij} = 1\) se \(i=j\) e \(\delta_{ij} = 0\) se \(i \neq j\). Portanto,

$$ \Delta \bar{s}^2 = \sum_{i=1}^{3} \sum_{j=1}^{3} \left( M_{00} \delta_{ij} + M_{ij} \right) \Delta x^i \Delta x^j = 0. \tag{1.25} $$

Como isso vale para qualquer \(\Delta x^i\), devemos ter

$$ M_{00} \delta_{ij} + M_{ij} = 0, \tag{1.26} $$

ou seja,

$$ M_{ij} = -M_{00} \delta_{ij}, \quad i,j = 1,2,3. \tag{1.27} $$

Assim, a matriz \(M_{\alpha\beta}\) fica

$$ M_{\alpha\beta} = \begin{pmatrix} M_{00} & 0 & 0 & 0 \\ 0 & -M_{00} & 0 & 0 \\ 0 & 0 & -M_{00} & 0 \\ 0 & 0 & 0 & -M_{00} \end{pmatrix}. \tag{1.28} $$

Então,

$$ \Delta \bar{s}^2 = M_{00} (\Delta t)^2 - M_{00} \left[ (\Delta x)^2 + (\Delta y)^2 + (\Delta z)^2 \right]. \tag{1.29} $$

Usando a definição de \(\Delta s^2\),

$$ \Delta s^2 = -(\Delta t)^2 + (\Delta x)^2 + (\Delta y)^2 + (\Delta z)^2, \tag{1.30} $$

obtemos

$$ \Delta \bar{s}^2 = -M_{00} \Delta s^2. \tag{1.31} $$

Defina

$$ \phi(v) \equiv -M_{00}. \tag{1.32} $$

Então,

$$ \Delta \bar{s}^2 = \phi(v) \Delta s^2. \tag{1.33} $$

A constante \(\phi(v)\) só pode depender da velocidade relativa \(v\) entre \(\bar{O}\) e \(O\), nunca das coordenadas dos eventos.

## 5. Determinação de \(\phi(v)\)

O intervalo medido por \(\bar{O}\) é proporcional ao intervalo medido por \(O\). A constante de proporcionalidade só pode depender da velocidade relativa entre os observadores. Além disso, \(\phi\) não pode depender da direção de \(v\), apenas do módulo \(|v|\).

Considere uma barra em repouso em \(O\), orientada perpendicularmente à direção do movimento relativo. Seu comprimento não é alterado pela transformação. Portanto, para essa configuração,

$$ (\text{comprimento da barra em } \bar{O})^2 = \phi(v) (\text{comprimento da barra em } O)^2. \tag{1.34} $$

Como o comprimento perpendicular não muda, temos

$$ 1 = \phi(v). \tag{1.35} $$

Assim,

$$ \phi(v) = 1. \tag{1.36} $$

Logo,

$$ \Delta \bar{s}^2 = \Delta s^2. \tag{1.37} $$

Portanto, o intervalo espaço-tempo é invariante sob transformações de Lorentz.

## 6. Observação sobre o sinal

Se usarmos a convenção de sinal oposta,

$$ \Delta s^2 = (\Delta t)^2 - (\Delta x)^2 - (\Delta y)^2 - (\Delta z)^2, \tag{1.38} $$

a conclusão final é a mesma, apenas com \(\phi(v) = M_{00}\) em vez de \(\phi(v) = -M_{00}\). O importante é manter a mesma convenção em todas as passagens.

## 7. Prova de que \(\phi(v)=1\) e invariância dos intervalos

Retomando a relação geral obtida na seção 1.6:

$$ \Delta \bar{s}^2 = \phi(v) \Delta s^2, \tag{1.39} $$

onde \(\phi(v) = -M_{00}\) e \(v\) é a velocidade relativa entre os referenciais \(O\) e \(\bar{O}\). Queremos mostrar que \(\phi(v) = 1\). A prova tem duas partes.

### 7.1 Primeira parte: \(\phi\) depende apenas de \(|v|\)

Considere uma barra em repouso em \(O\), orientada perpendicularmente à velocidade \(v\) de \(\bar{O}\) em relação a \(O\). Suponha que a barra esteja sobre o eixo \(y\). No diagrama de espaço-tempo de \(O\), as linhas de mundo das extremidades da barra são paralelas ao eixo \(t\). Sejam \(A\) e \(B\) dois eventos simultâneos em \(O\) que ocorrem nas extremidades da barra. Então,

$$ \Delta t_{AB} = 0, \quad \Delta x_{AB} = 0, \quad \Delta z_{AB} = 0, \quad \Delta y_{AB} = L, \tag{1.40} $$

onde \(L\) é o comprimento da barra em \(O\). Portanto, o intervalo entre \(A\) e \(B\) em \(O\) é

$$ \Delta s^2 = -(\Delta t_{AB})^2 + (\Delta x_{AB})^2 + (\Delta y_{AB})^2 + (\Delta z_{AB})^2 = L^2. \tag{1.41} $$

No referencial \(\bar{O}\), os eventos \(A\) e \(B\) também são simultâneos. Isso ocorre porque a barra é perpendicular à velocidade relativa, e a simetria do problema não permite que um dos eventos ocorra antes do outro. Assim,

$$ \Delta \bar{t}_{AB} = 0, \quad \Delta \bar{x}_{AB} = 0, \quad \Delta \bar{z}_{AB} = 0, \quad \Delta \bar{y}_{AB} = \bar{L}, \tag{1.42} $$

e o intervalo entre \(A\) e \(B\) em \(\bar{O}\) é

$$ \Delta \bar{s}^2 = \bar{L}^2. \tag{1.43} $$

Usando a relação geral (1.39), temos

$$ \Delta \bar{s}^2 = \phi(v) \Delta s^2 \implies \bar{L}^2 = \phi(v) L^2. \tag{1.44} $$

Como a barra é perpendicular à velocidade relativa, seu comprimento não é afetado pela contração de Lorentz. Portanto,

$$ \bar{L} = L. \tag{1.45} $$

Substituindo em (1.44), obtemos

$$ L^2 = \phi(v) L^2 \implies \phi(v) = 1. \tag{1.46} $$

Esse argumento mostra que \(\phi(v)\) não pode depender da direção de \(v\), apenas de seu módulo. De fato, se repetirmos o argumento com a barra em qualquer direção perpendicular a \(v\), o resultado é o mesmo. Como podemos escolher a orientação da barra livremente, concluímos que \(\phi\) só pode depender de \(|v|\):

$$ \phi(v) = \phi(|v|). \tag{1.47} $$

### 7.2 Segunda parte: \(\phi(v) = \pm 1\) e escolha do sinal

Considere a transformação inversa, de \(\bar{O}\) para \(O\). Como a velocidade relativa de \(O\) em relação a \(\bar{O}\) é \(-v\), a relação análoga a (1.39) é

$$ \Delta s^2 = \phi(-v) \Delta \bar{s}^2. \tag{1.48} $$

Substituindo (1.39) em (1.48), obtemos

$$ \Delta s^2 = \phi(-v) \phi(v) \Delta s^2. \tag{1.49} $$

Como isso deve valer para qualquer intervalo \(\Delta s^2\), temos

$$ \phi(-v) \phi(v) = 1. \tag{1.50} $$

Mas, pela primeira parte, \(\phi(v) = \phi(|v|)\), e como \(|-v| = |v|\), temos \(\phi(-v) = \phi(v)\). Portanto,

$$ [\phi(v)]^2 = 1 \implies \phi(v) = \pm 1. \tag{1.51} $$

Agora usamos o fato de que, quando \(v = 0\), os dois referenciais são idênticos. Nesse caso, \(\Delta \bar{s}^2 = \Delta s^2\), logo

$$ \phi(0) = 1. \tag{1.52} $$

Como \(\phi(v)\) deve variar continuamente com \(v\), a transformação de Lorentz varia continuamente com a velocidade relativa, a única possibilidade é

$$ \phi(v) = 1 \quad \text{para todo } v. \tag{1.53} $$

Portanto, concluímos que

$$ \Delta \bar{s}^2 = \Delta s^2. \tag{1.54} $$

Ou seja, o intervalo espaço-tempo entre dois eventos é invariante, independente do observador inercial que o calcula.

### 7.3 Consequência

A invariância do intervalo é o teorema central da Relatividade Especial. Ela substitui a invariância do tempo absoluto e do espaço absoluto da mecânica newtoniana. A partir dela, podemos classificar os intervalos em:

- tipo tempo, se \(\Delta s^2 < 0\),
- tipo espaço, se \(\Delta s^2 > 0\),
- tipo luz ou nulo, se \(\Delta s^2 = 0\).

Além disso, a invariância do intervalo é o ponto de partida para deduzir as transformações de Lorentz, a dilatação temporal e a contração espacial.
```



