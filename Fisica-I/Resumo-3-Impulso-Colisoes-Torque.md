# Resumo 3 – Impulso e Quantidade de Movimento; Colisão Elástica e Momento de uma Força

**Disciplina:** Física I – Lic. em Matemática – Mod 8 – 2026.2
**Referência:** HALLIDAY, D.; RESNICK, R.; WALKER, J. *Fundamentos de Física, vol. 1 – Mecânica*. Rio de Janeiro: LTC.
(Cap. 9 – Centro de Massa e Momento Linear; Cap. 10 – Rotação; Cap. 11 – Rolamento, Torque e Momento Angular)

---

## 1. Quantidade de Movimento (Momento Linear)

O **momento linear** de uma partícula é o vetor definido pelo produto de sua massa pela sua velocidade:

$$\vec{p} = m\,\vec{v} \qquad [\text{kg·m/s}]$$

Tem a mesma direção e sentido da velocidade. Com esse conceito, Halliday apresenta a **Segunda Lei de Newton na forma original**:

$$\vec{F}_{res} = \frac{d\vec{p}}{dt}$$

"A taxa de variação do momento de uma partícula é igual à força resultante que age sobre ela."

Para um **sistema de partículas**, o momento total é a soma dos momentos individuais e é igual à massa total vezes a velocidade do centro de massa:

$$\vec{P} = \vec{p}_1 + \vec{p}_2 + \dots + \vec{p}_n = M\,\vec{v}_{CM} \qquad \Rightarrow \qquad \vec{F}_{res,ext} = \frac{d\vec{P}}{dt}$$

---

## 2. Impulso

Quando uma força age durante um intervalo de tempo (como numa colisão), ela transfere momento ao corpo. Essa transferência é o **impulso**:

$$\vec{J} = \int_{t_i}^{t_f} \vec{F}(t)\,dt$$

Graficamente, o módulo do impulso é a **área sob a curva F × t**. Se usarmos a força média $F_{méd}$ no intervalo $\Delta t$:

$$J = F_{méd}\,\Delta t$$

### Teorema do Impulso e Momento Linear

$$\vec{J} = \Delta\vec{p} = \vec{p}_f - \vec{p}_i$$

O impulso aplicado a um corpo é igual à variação do seu momento linear.
*Aplicação:* airbags, luvas de boxe e o ato de dobrar os joelhos ao saltar aumentam $\Delta t$, reduzindo a força média para uma mesma variação de momento.

**Série de colisões:** se $n$ projéteis de massa $m$ atingem um alvo num intervalo $\Delta t$, cada um sofrendo variação de velocidade $\Delta v$, a força média no alvo é
$F_{méd} = -\dfrac{n}{\Delta t}\, m\,\Delta v$.

---

## 3. Conservação do Momento Linear

Se a **força externa resultante** sobre um sistema é nula (sistema isolado) e nenhuma partícula entra ou sai (sistema fechado):

$$\vec{P} = \text{constante} \qquad \Rightarrow \qquad \vec{P}_i = \vec{P}_f$$

A lei vale componente a componente: se a força externa é nula em apenas uma direção (ex.: horizontal), o momento se conserva somente nessa direção. As forças internas (como as forças de contato numa colisão) não alteram o momento total, pois pela 3ª Lei de Newton aparecem aos pares e se anulam.

---

## 4. Colisões

**Colisão** é um evento isolado em que corpos exercem forças intensas uns sobre os outros durante um intervalo curto. Como as forças internas dominam, o **momento total sempre se conserva** numa colisão. O que diferencia os tipos é a energia cinética:

| Tipo | Momento linear | Energia cinética |
|---|---|---|
| Elástica | Conserva | Conserva |
| Inelástica | Conserva | Não conserva (parte vira calor, som, deformação) |
| Perfeitamente inelástica | Conserva | Perda máxima – os corpos ficam **unidos** |

Na perfeitamente inelástica: $m_1 v_{1i} + m_2 v_{2i} = (m_1+m_2)\,V$.

### 4.1 Colisão Elástica em uma Dimensão

Conservam-se simultaneamente:

$$m_1 v_{1i} + m_2 v_{2i} = m_1 v_{1f} + m_2 v_{2f}$$

$$\tfrac{1}{2} m_1 v_{1i}^2 + \tfrac{1}{2} m_2 v_{2i}^2 = \tfrac{1}{2} m_1 v_{1f}^2 + \tfrac{1}{2} m_2 v_{2f}^2$$

**Alvo em repouso** ($v_{2i}=0$) – resolvendo o sistema:

$$v_{1f} = \frac{m_1 - m_2}{m_1 + m_2}\,v_{1i} \qquad\qquad v_{2f} = \frac{2m_1}{m_1 + m_2}\,v_{1i}$$

Casos particulares (Halliday):
- **Massas iguais** ($m_1 = m_2$): $v_{1f}=0$ e $v_{2f}=v_{1i}$ → os corpos **trocam de velocidade** (ex.: bolas de sinuca).
- **Alvo muito pesado** ($m_2 \gg m_1$): $v_{1f}\approx -v_{1i}$ → o projétil volta com a mesma velocidade; o alvo quase não se move.
- **Projétil muito pesado** ($m_1 \gg m_2$): $v_{1f}\approx v_{1i}$ e $v_{2f}\approx 2v_{1i}$.

**Alvo em movimento** (caso geral):

$$v_{1f} = \frac{m_1-m_2}{m_1+m_2}v_{1i} + \frac{2m_2}{m_1+m_2}v_{2i} \qquad v_{2f} = \frac{2m_1}{m_1+m_2}v_{1i} + \frac{m_2-m_1}{m_1+m_2}v_{2i}$$

Propriedade útil: numa colisão elástica unidimensional, a **velocidade relativa se inverte**: $v_{2f}-v_{1f} = -(v_{2i}-v_{1i})$.

### 4.2 Colisão em Duas Dimensões

O momento se conserva em cada eixo. Para alvo inicialmente em repouso, com ângulos $\theta_1$ e $\theta_2$ de saída:

- Eixo x: $m_1 v_{1i} = m_1 v_{1f}\cos\theta_1 + m_2 v_{2f}\cos\theta_2$
- Eixo y: $0 = -m_1 v_{1f}\,\text{sen}\,\theta_1 + m_2 v_{2f}\,\text{sen}\,\theta_2$
- Se elástica, soma-se a conservação da energia cinética.

---

## 5. Momento de uma Força (Torque)

O **torque** mede a capacidade de uma força de fazer um corpo **girar** em torno de um eixo. Depende da intensidade da força, do ponto de aplicação e da direção.

### Módulo

$$\tau = r\,F\,\text{sen}\,\phi$$

onde $r$ é a distância do eixo ao ponto de aplicação e $\phi$ é o ângulo entre $\vec{r}$ e $\vec{F}$. Halliday mostra duas leituras equivalentes:

- $\tau = r\,F_t$ — apenas a **componente tangencial** $F_t = F\,\text{sen}\,\phi$ produz rotação;
- $\tau = r_\perp F$ — onde $r_\perp = r\,\text{sen}\,\phi$ é o **braço de alavanca** (distância perpendicular do eixo à linha de ação da força).

Unidade: **N·m** (não confundir com joule). Convenção de sinal: torque **positivo** tende a girar no sentido **anti-horário**; **negativo**, no sentido horário.

### Forma vetorial (Cap. 11)

$$\vec{\tau} = \vec{r} \times \vec{F}$$

A direção é dada pela **regra da mão direita** e é perpendicular ao plano formado por $\vec{r}$ e $\vec{F}$.

### Segunda Lei de Newton para a Rotação

$$\tau_{res} = I\,\alpha$$

análoga a $F = ma$: o torque faz o papel da força, o momento de inércia $I$ o da massa e a aceleração angular $\alpha$ o da aceleração linear.

### Relação com o momento angular

Assim como $\vec{F} = d\vec{p}/dt$, para rotações vale $\vec{\tau}_{res} = \dfrac{d\vec{L}}{dt}$, com $\vec{L} = \vec{r}\times\vec{p}$. Se o torque externo resultante for nulo, o momento angular se conserva.

---

## 6. Quadro-síntese

| Grandeza | Expressão | Ideia central |
|---|---|---|
| Momento linear | $\vec{p}=m\vec{v}$ | "Quantidade de movimento" |
| 2ª Lei (forma geral) | $\vec{F}=d\vec{p}/dt$ | Força muda o momento |
| Impulso | $\vec{J}=\int\vec{F}dt=\Delta\vec{p}$ | Área sob F × t |
| Conservação | $\vec{P}_i=\vec{P}_f$ | Sistema isolado e fechado |
| Colisão elástica | Conserva $\vec{P}$ e $K$ | Velocidade relativa se inverte |
| Torque | $\tau=rF\,\text{sen}\,\phi$; $\vec{\tau}=\vec{r}\times\vec{F}$ | "Força" que provoca rotação |
| 2ª Lei rotacional | $\tau_{res}=I\alpha$ | Análogo de $F=ma$ |
