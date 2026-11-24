# Manual de Experimentação e Plano de Teste com Critério | Creator Growth System

**Aluno:** Iago  
**Projeto / Empresa:** NanoGen Lab — E-commerce & Manufatura 3D (Linha Automotiva / *Gearhead*)  
**Produto / Oferta Principal:** Porta-Chaves de Parede Porsche GT3 RS (Impressão 3D Premium) — **Ticket Médio: R$ 69,90**  
**Base Histórica Conectada:** Diagnóstico do Ciclo de 7 Dias (`4.800` alcance → `72` cliques → `12` vendas)

---

## Parte 1: Construção de Hipótese de Crescimento (Base do System)

### Contexto da Operação Auditada
* **Nome do Projeto:** NanoGen Lab
* **Produto / Oferta Principal:** Porta-Chaves de Parede Porsche GT3 RS (`R$ 69,90`)
* **Ponto de Perda / Gargalo Atual:** Baixa transição de **Atenção → Intenção** (**CTR no Link da Bio = `1,50%`** no consolidado semanal, abaixo do piso crítico de `2,00%` e da meta saudável de `3,50%`), apesar da conversão na loja estar saudável (`16,67%`).
* **Formato Atual Utilizado:** Vídeos curtos verticais (`15s a 22s`) no **Instagram Reels / TikTok**.

---

### 1. Isolamento da Variável Única
Para garantir um teste científico limpo (sem contaminação cruzada de causas), **apenas 1 variável** será alterada neste ciclo:

* **Variável Única Alterada:** **Bloco de CTA Comercial nos últimos 5 segundos + Comentário Fixado**
  - *Antes (Controle):* vídeos terminavam sem chamada explícita de compra, sem preço visível e, em alguns casos, com perguntas abertas de engajamento na legenda (ex.: *"Qual próximo carro fazer?"*).
  - *Agora (Variante do Teste):* todos os vídeos do ciclo recebem nos **últimos 5 segundos** uma chamada verbal + texto fixo na tela (*"Garanta o seu por R$ 69,90 no link da bio — envio para todo o Brasil"*), acompanhada de **1º comentário fixado** direcionando ao link do perfil, **sem perguntas concorrentes na legenda**.
* **Variáveis Mantidas 100% Constantes:** produto ofertado (`Porsche GT3 RS`), preço (`R$ 69,90`), duração dos vídeos (`15–20s`), estilo de filmagem dos primeiros `10–15s`, horários de postagem (`19h00`), canais (Instagram Reels e TikTok) e página de checkout do Marketplace.

---

### 2. Declaração da Hipótese Estruturada (`AÇÃO + EXPECTATIVA + MÉTRICA`)
* **AÇÃO:** Inserir nos últimos 5 segundos de todos os 8 Reels do próximo ciclo de 14 dias uma CTA comercial explícita (verbalizada e escrita em tela com o preço de `R$ 69,90` e instrução direta para o link da bio), reforçada por comentário fixado imediato e remoção de perguntas dispersivas na legenda — mantendo todo o restante da produção inalterado.
* **EXPECTATIVA:** Reduzir a fricção de passagem do espectador *gearhead* que hoje consome o vídeo de forma passiva (sem saber se está à venda ou quanto custa), convertendo atenção visual em cliques intencionais no link da bio sem derrubar a qualidade dos visitantes na loja.
* **MÉTRICA:** **Taxa de Clique no Link da Bio — CTR** ($\frac{\text{Cliques na Bio + DMs Comerciais}}{\text{Alcance Único}} \times 100$), monitorada em conjunto com a métrica guarda-chuva (*guardrail*) de **Taxa de Conversão da Loja ($\ge 12,0\%$)**.

---

### 3. Classificação de Força da Hipótese
* **Classificação:** **FORTE**
* **Auditoria de Confiabilidade (Critérios Atendidos):**
  1. **Variável única isolada:** altera somente a CTA final e comentário fixado, preservando gancho, produto, preço e canal.
  2. **Ataque direto ao gargalo real:** atua exatamente na quebra de `Atenção → Intenção` (`1,50%` CTR), sem mexer na etapa de loja que já converte a `16,67%`.
  3. **Baseada em evidência prévia:** peças com CTA direta atingiram `4,17%–4,19%` de CTR no diagnóstico anterior, contra `0,50%–1,00%` sem CTA.
  4. **Ajuste de blindagem aplicado:** inclusão obrigatória da **CTA em texto na tela** (para não depender de usuários assistindo com áudio desligado) e **proibição de enquetes concorrentes na legenda** para não dividir a ação do usuário.

---

## Parte 2: Planejamento de Teste com Critério (Base do System)

### Parâmetros Históricos e Janela do Experimento
* **Média Histórica Atual (Baseline):** **CTR no Link da Bio = `1,50%`** (`72` cliques em `4.800` de alcance nos últimos 7 dias)
* **Janela do Teste Escolhida:** **14 dias** (2 ciclos semanais completos para diluir ruídos diários de entrega orgânica)
* **Frequência de Publicações do Teste:** **8 Reels publicados** (`4` publicações por semana: segunda, quarta, sexta e domingo às `19h00`)

---

### 1. Régua de Validação (Critério Numérico de Sucesso)
A hipótese será considerada **CONFIRMADA** ao final dos 14 dias se atender **simultaneamente** a dois números explícitos:
1. **Indicador Primário (CTR Bio):** atingir **$\ge$ 2,50%** no consolidado das 8 peças — variação mínima de **+1,00 ponto percentual** (**+66,7% de crescimento relativo** sobre o baseline de `1,50%`), superando com margem o piso de alerta operacional (`2,00%`).
2. **Trava de Qualidade (*Guardrail*):** manter a **Taxa de Conversão da Loja em $\ge$ 12,0%** (evitando falsos positivos por cliques curiosos/desqualificados).
* *Projeção prática no volume esperado (`~9.600` de alcance em 14 dias):* com `2,50%` de CTR, gera **`240` cliques** e entre **`29` vendas (`R$ 2.027,10`, no piso de `12%` conv.)** e **`40` vendas (`R$ 2.796,00`, mantendo `16,67%` conv.)**.

---

### 2. Régua de Invalidação (Critério Numérico de Descarte)
A hipótese será considerada **INVALIDADA (REFUTADA)** e o experimento encerrado se ocorrer qualquer uma das condições abaixo:
1. **Estagnação de Topo/Meio:** ao fim dos 14 dias (com amostra mínima de `>= 7.000` de alcance acumulado), o **CTR permanecer $\le$ 1,75%** (ganho inferior a `+0,25 p.p.` / `+16,7%` relativo sobre `1,50%`, continuando abaixo do piso crítico de `2,00%`).
2. **Degradação de Fundo (Falso Clique):** o CTR subir acima de `2,00%`, mas a **Taxa de Conversão da Loja cair abaixo de `8,0%`** — indicando que a CTA gerou curiosidade vazia ou frustração de preço/expectativa no anúncio.

> *(Nota de leitura: resultados de CTR entre **`1,76%` e `2,49%`** com conversão `>= 12,0%` caem na **Zona Cinzenta / Inconclusiva**, tratada no Caminho 3 da Matriz Pós-Teste.)*

---

### 3. Mapeamento de Variáveis de Distorção (Controle de Ruído)
1. **Distorção 1 — Viralização Desqualificada (*Outlier* Algorítmico de Topo):**  
   Se apenas 1 dos 8 Reels viralizar para fora do nicho *gearhead* (ex.: `20.000+` views de entusiastas genéricos de impressão 3D) com CTR de `0,40%`, esse único vídeo puxará a média ponderada para baixo mesmo que os outros 7 Reels batam `3,20%`.  
   *Mitigação:* registrar junto à média global a **mediana do CTR por post** e auditar o resultado com e sem o *outlier*.
2. **Distorção 2 — Sazonalidade de Pagamento e Fricção Técnica no Marketplace:**  
   Oscilações entre dias de pagamento (5º dia útil) e fim de mês, além de eventuais quedas do link da bio ou aumento temporário de frete no marketplace, afetam cliques e checkout sem relação com a CTA.  
   *Mitigação:* a janela de **14 dias** cobre duas semanas distintas de calendário e o link da bio deve ser testado manualmente antes de cada publicação às `19h00`.

---

## Parte 3: Matriz de Decisão Pós-Teste e Giro de Iteração

### 1. Árvore de Decisão em 3 Caminhos

```
Resultado Consolidado (14 dias / 8 Reels)
 ├── [1] CTR >= 2,50% E Conv. Loja >= 12,0% ──▶ HIPÓTESE CONFIRMADA (Padronizar + Girar)
 ├── [2] CTR <= 1,75% OU Conv. Loja < 8,0%   ──▶ HIPÓTESE REFUTADA (Diagnosticar + Pivotar)
 └── [3] CTR entre 1,76% e 2,49% (Conv >=12%)──▶ INCONCLUSIVO (Auditar Outliers + Estender 7d)
```

* **Caminho 1 — Hipótese Confirmada (CTR $\ge$ 2,50% e Conversão $\ge$ 12,0%):**
  - *Incorporação como padrão definitivo:* o bloco final de CTA de 5 segundos (áudio + texto com `R$ 69,90` + 1º comentário fixado sem enquetes concorrentes) passa a ser regra obrigatória do SOP editorial de 100% dos vídeos comerciais da NanoGen Lab, e o novo baseline passa a ser o CTR obtido no ciclo.
  - *Próxima variável a testar (Giro de Iteração):* mantendo essa CTA vencedora fixa, o Ciclo 2 isola **apenas os primeiros 3 segundos (Gancho de Abertura)** — testando *Gancho de Problema/Uso Real na Garagem* vs. *Gancho Visual Estético* para buscar o patamar histórico de `>= 3,50%` de CTR.
* **Caminho 2 — Hipótese Refutada / Invalidada (CTR $\le$ 1,75% ou Conversão $< 8,0\%$):**
  - *Diagnóstico de aprendizado comportamental:* se o CTR não reagiu à CTA final, a audiência está **abandonando o vídeo antes dos últimos 5 segundos** ou o início do vídeo está atraindo **público sem fit de compra** (curiosos de 3D que não clicam independentemente do final). Se a conversão da loja caiu abaixo de `8,0%`, a chamada final criou expectativa desalinhada com a página do marketplace.
  - *Para onde o foco gira:* encerrar ajustes no fim do vídeo e girar imediatamente o próximo teste para o **Gancho dos Primeiros 3 Segundos** (ex.: começar já com as chaves reais penduradas no porta-chaves na parede no frame 0) ou para o **alinhamento preço/frete na página de destino**.
* **Caminho 3 — Resultado Inconclusivo / Zona Cinzenta (CTR entre `1,76%` e `2,49%`):**
  - *Protocolo de ação:* não aprovar em definitivo nem descartar por impulso. Primeiro, verificar se algum *outlier* de alcance distorceu a média (comparando média vs. mediana dos 8 vídeos). Em seguida, rodar uma **extensão controlada de +7 dias (4 peças adicionais)** aplicando apenas maior destaque visual na legenda em tela da CTA (contraste/tamanho) para confirmar se a tendência cruza `>= 2,50%` ou estaciona abaixo da meta.

---

### 2. Modelo do Registro de Aprendizado (Base de Inteligência do Canal)

Preencher esta ficha ao término de **cada ciclo de 14 dias** para construir o histórico cumulativo da NanoGen Lab:

```markdown
### Registro de Experimento #[NÚMERO] — [Mês/Ano]
* **Hipótese Testada:** [Copiar a declaração AÇÃO + EXPECTATIVA + MÉTRICA e a variável única isolada]
* **Resultado vs. Baseline:** [Métrica obtida no ciclo vs. Baseline anterior | Ex.: CTR 2,85% vs. 1,50% (+90%) | Conv. Loja: 15,2% | Decisão: Confirmada / Refutada / Inconclusiva]
* **Aprendizado Comportamental Extraído:** [O que o público demonstrou na prática sobre retenção, interesse, objeção de preço ou formato]
* **Próxima Ação:** [Incorporar padrão / Descartar e qual será a NOVA variável única isolada do próximo ciclo]
```

#### Exemplo de Ficha Pronta para Preenchimento do Ciclo Atual
* **Hipótese Testada:** Inserção de CTA comercial explícita nos últimos 5s (áudio + texto com R$ 69,90) + comentário fixado direto para o link da bio em 8 Reels (14 dias), mantendo gancho, produto e página constantes.
* **Resultado vs. Baseline:** *(A preencher no Dia 14)* — Baseline: `1,50%` CTR | Meta de Validação: `>= 2,50%` CTR (com Conv. Loja `>= 12,0%`).
* **Aprendizado Comportamental Extraído:** *(A preencher após leitura de média e mediana dos 8 Reels e checagem de outliers)*.
* **Próxima Ação:** *(Executar Caminho 1, 2 ou 3 da Árvore de Decisão acima)*.
