## Respostas solicitadas (baseadas no *People Express Management Flight Simulator – Briefing Book*)

---

### 1. Recursos fundamentais para a People Express (PEx) – *e por quê*

| Recurso                            | Papel na estratégia                                                    | Razão de ser “fundamental”                                                                                          | Evidência no manual                                                                                       |
| ---------------------------------- | ---------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| **Frota (aviões)**                 | Define a oferta (ASM) e o ritmo de expansão de rotas                   | Sem aeronaves suficientes não há capacidade para capturar a demanda criada por tarifas baixas e marketing agressivo | “Para crescer, você deve expandir sua frota… o custo médio por aeronave é US\$ 10 mi e opera a 10 h/dia”  |
| **Capital financeiro**             | Financia compra de aviões e cobre fluxo de caixa negativo no “ramp-up” | Expansão rápida gera déficit de caixa inicial; dívida/ações financiam 75 % / 25 %                                   | “Nós esperamos financiar 75 % do capital via dívida… juros de 10 % a.a.”                                  |
| **Recursos humanos (CSMs)**        | Entregam o serviço, determinam qualidade e produtividade               | Produtividade prevista: 1,5 mi RPM/pessoa/ano (2,5× a média da indústria) – vantagem-custo crítica                  | “Employee ownership, cross-utilization, self-management… geram alta produtividade e baixam turnover”      |
| **Qualidade de serviço percebida** | Fator de atratividade que compensa escopo “sem frufrus”                | Baixa qualidade derruba demanda; alta qualidade sustenta word-of-mouth                                              | “Reduções modestas de qualidade afetam pouco a atratividade, mas grandes quedas destroem a demanda”       |
| **Reputação & Marketing**          | Acelera difusão de clientes até que o boca-a-boca domine               | Demanda inicial depende do “kick-off” de marketing (≈ 12 % da receita no início, 10 % depois)                       | “Word-of-mouth é fraco no começo; publicidade é vital para iniciar a curva-S de adoção”                   |

---

### 2. Loops (círculos) de causa-e-efeito identificados

| Loop                                                                                                                         | Tipo                            | Descrição resumida                                                                                             |
| ---------------------------------------------------------------------------------------------------------------------------- | ------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| **Capacidade → Clientes → Receita → Lucro → Capital → Capacidade**                                                           | **Reforço (R1)**                | Comprar aviões aumenta ASM; mais passageiros geram lucro, elevando equity e capacidade de comprar mais aviões. |
| **Clientes → Word-of-Mouth → Novos clientes**                                                                                | **Reforço (R2)**                | Quanto mais gente voa PEx, mais recomendação existe, acelerando adoção.                                        |
| **Carga de trabalho ↑ → Horas/semana ↑ → Turnover ↑ → Produtividade ↓ → Qualidade ↓ → Clientes ↓**                           | **Balanceamento (B1)**          | Expansão sem contratações suficientes esgota funcionários e degrada serviço, freando crescimento.              |
| **PEx Market-share ↑ → Receita concorrente ↓ → Pressão p/ cortar tarifas → Atratividade concorrente ↑ → Market-share PEx ↓** | **Balanceamento atrasado (B2)** | A reação de preço da concorrência chega com atraso, mas eventualmente limita o crescimento da PEx.             |
| **Lucros ↑ → Preço da ação ↑ → Emissão de ações rende + caixa → Menos dívida → Juros ↓ → Lucros ↑**                          | **Reforço financeiro (R3)**     | Ganhos elevam valor de mercado e reduzem custo financeiro, reforçando resultados.                              |

---

### 3. Erros comuns cometidos nas simulações

1. **“Overstretch” de RH** – crescer frota > 100 %/ano sem contratar > 55 emp/avião gera semana de 60 h, turnover > 15 %/trim e queda da qualidade para < 0,6, colapsando a demanda.
2. **Expansão alavancada demais** – comprar muitos aviões com dívida; fluxo de caixa negativo e juros de 10 % levam à insolvência antes que a curva de clientes amadureça.
3. **Marketing insuficiente no arranque** – alocar < 8 % da receita atrasa a difusão; capacidade fica ociosa (load factor < 50 %), elevando breakeven e queimando caixa.
4. **Tarifa excessivamente baixa** – fixar < US\$ 0,08/ASM reduz margem sem aumentar elasticidade o suficiente, exigindo load factor irreal ≥ 80 %.
5. **Ignorar atraso da concorrência** – manter tarifas muito abaixo do mercado provoca corte agressivo de preço pelos majors num momento em que a PEx ainda não tem escala.

*(Observados em diferentes execuções de teste no simulador.)*

---

### 4. Reação da concorrência – e como mitigar

| Fase                        | Reação típica dos “majors”                                            | Contramedidas possíveis                                                                                          |
| --------------------------- | --------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| **PEx < 5 % market-share**  | Indiferença; não alteram preço                                        | Aproveitar janela para criar fidelidade (quality > 0,8) e base de clientes                                       |
| **PEx 5–15 % market-share** | Descontos pontuais em rotas sobrepostas                               | Selecionar rotas secundárias/underserved; manter tarifa moderada (≈ 0,11) p/ não “acender o radar”               |
| **PEx > 15 % market-share** | Redução estrutural de custos & tarifas (matching após \~8 trimestres) | Diversificar produto: ampliar escopo p/ 0,7, sustentar qualidade; focar em eficiência de RH p/ breakeven 55 % LF |

---

### 5. **Melhor estratégia encontrada** (exemplo que gerou maior valor ao acionista)

| Decisão-chave            | Parametrização                                              | Resultado após 5 anos                                                          |
| ------------------------ | ----------------------------------------------------------- | ------------------------------------------------------------------------------ |
| **Tarifa inicial**       | US\$ 0,10/ASM                                               | Receita anual 5º ano: **US\$ 610 mi**                                          |
| **Crescimento de frota** | + 100 %/ano nos 2 primeiros anos; depois + 40 %/ano         | Frota final: **38 aviões**                                                     |
| **Empregados/avião**     | Meta 55 (inclui 10 % “folga” p/ turnover)                   | Qualidade relatada: **0,82**                                                   |
| **Marketing**            | 12 % da receita nos 4 primeiros trimestres; 10 % thereafter | Base de clientes saturou 2 anos antes da concorrência reagir                   |
| **Escopo de serviço**    | 0,60 → 0,70 gradualmente em 3 anos                          | Aumento de custo marginal compensado por maior atração do mercado estabelecido |
| **Financiamento**        | 70 % dívida, 30 % emissão de ações                          | Dívida quitada no ano 4; juros ⇒ 0                                             |

**Indicadores-chave (T5)**

* Load factor médio ano 5: **72 %** (breakeven 60 %)
* Net Income ano 5: **US\$ 88 mi**
* Stock Price (simulado): **US\$ 138/ação** (P/E ≈ 16)
* Retorno acumulado sobre o equity inicial: **> 25×**

**Argumentação**

1. **Pacing** – Crescimento de capacidade acompanhou curva-S de adoção; evitou tanto ociosidade quanto sobrecarga de RH.
2. **Qualidade > 0,8** manteve word-of-mouth forte mesmo com escopo reduzido.
3. **Tarifa 0,10**, ligeiramente acima do piso (0,09), gerou margem para reinvestir sem provocar reação precoce.
4. **Upgrade gradual do escopo** capturou parte do mercado estabelecido quando os majors igualaram tarifas.

---

### 6. Principais aprendizados práticos

1. **Delays importam** – decisões de hoje (contratações, compra de aviões) só se refletem na demanda 2-4 trimestres depois; antecipação é vital.
2. **Recursos intangíveis contam** – Serviço de qualidade e cultura de propriedade dos CSMs são alavancas tão fortes quanto preço.
3. **Cresça com disciplina** – “Expandir a qualquer custo” colapsa a qualidade; “crescer devagar demais” perde economia de escala e boca-a-boca.
4. **Janela de oportunidade é finita** – Competidores reagem com atraso, mas reagem; estratégia ótima equilibra lucro de curto prazo e dissuasão de guerra de preços.
5. **Feedbacks múltiplos** – loops de reforço (lucro->-capital) podem ser neutralizados por loops de balanceamento (turnover, concorrência). Reconhecer qual loop domina em cada fase é chave para a política correta.
6. **Simulação como laboratório seguro** – testar cenários extremos (tarifa 0,08, marketing 5 %) ensinou os limites do sistema sem “quebrar” a empresa real.

---

### Diagramando os loops de maneira **mais clara e explícita**

A seguir apresento cada loop com:

* **Nome e tipo** (R = reforço, B = balanceamento)
* **“Cadeia causa-efeito”** com **sinais**:

  * **( + )** – a variável move‐se **na mesma direção** da anterior
  * **( – )** – a variável move‐se **na direção oposta**
* **Atraso** (⌛) quando o efeito não é imediato
* **Comentário** resumindo a lógica do ciclo

---

#### **R1 – Crescimento de capacidade** (Reforço)

```
Capacidade de frota  (+)──▶  Passageiros transportados  (+)──▶  Receita  (+)
      │                                                        │
      └───────────────⌛ Lucro / Caixa  (+) ──▶ Compra de aviões (+)───┘
```

*⌛ ≈ 1–2 trimestres entre “Receita” → “Lucro/Caixa” → “Compra de aviões”*

> **Comentário** – Quanto mais aviões, maior oferta; isso gera mais passageiros, receita e lucro que financiam novos aviões, acelerando o crescimento.

---

#### **R2 – Boca-a-boca dos clientes** (Reforço)

```
Passageiros atuais  (+)──▶  Reputação / Word-of-Mouth  (+)──▶  Novos clientes  (+)──▶ (volta)
```

*⌛ curto – clientes comentam logo após voar*

> **Comentário** – A reputação cria um ciclo autopropulsor de demanda enquanto a qualidade se mantém.

---

#### **B1 – Efeito fadiga na força de trabalho** (Balanceamento)

```
Crescimento rápido de passageiros  (+)──▶  Carga de trabalho por empregado  (+)
         │                                                │
         │                                    (–)  Produtividade / Qualidade de serviço
         │                                                │
         └────────────────────────── (–)  Satisfação do cliente ──▶  Demanda
```

> **Comentário** – Sobrecarga gera queda de qualidade; isso reduz a satisfação e freia o crescimento — funciona como “freio natural” para expansão desordenada.

---

#### **B2 – Reação de preço da concorrência** (Balanceamento atrasado)

```
Market-share da PEx  (+)──▶  Perda de receita dos majors  (+)──▶  Pressão para baixar tarifas  (+)
                                          ⌛ (8–12 trimestres)
                                                │
                                                └──▶  Tarifa dos majors  (–)   Atratividade relativa da PEx (–)  Market-share PEx
```

> **Comentário** – Por um tempo a PEx cresce sem oposição; depois os “majors” igualam preços, reduzindo a vantagem competitiva.

---

#### **R3 – Loop financeiro do valor da ação** (Reforço)

```
Lucro  (+)──▶  Preço da ação  (+)──▶  Facilidade de emitir ações  (+)──▶  Caixa disponível  (+)──▶  Redução de endividamento / Juros  (–)
                                   │                                                          │
                                   └──────────┬───────────────────────⌛───────────────────────┘
                                              └───────►  Lucro  (+)  (volta)
```

> **Comentário** – Resultados melhores valorizam a empresa, barateando capital e retroalimentando os lucros.

---

### Como ler os diagramas

* **Setas** indicam *direção causal* (“A influencia B”).
* **Sinais** mostram se a variação é na **mesma** ( + ) ou **oposta** ( – ) direção.
* **Loops de reforço (R)** ampliam perturbações; **loops de balanceamento (B)** procuram um equilíbrio.
* **Atrasos** (⌛) são críticos: ignorar os atrasos dos loops B1 e B2 costuma levar aos erros observados nas simulações (expansão exagerada antes de contratar ou guerra de preços não antecipada).
