# REGRA NORMATIVA — PROMPTS → CARTAS → LAYOUT → CÓDIGO

## Regra central

No projeto DECIO-BAZIN, toda orientação de investigação deve seguir uma cadeia única de transformação:

**PROMPTS → CARTAS → LAYOUT ÚNICO → CÓDIGO**

## 1. PROMPTS

Os prompts são pontos de partida para definir objetivos, perguntas, critérios, escopo e requisitos da investigação.

Os prompts não são fonte direta para geração de código.

## 2. CARTAS

Os prompts devem ser transformados em CARTAS/documentos normativos de investigação.

As cartas organizam, consolidam e tornam explícitas as regras, requisitos, premissas, critérios de validação e decisões metodológicas.

## 3. LAYOUT ÚNICO

Todas as cartas devem alimentar um único LAYOUT consolidado.

O LAYOUT é a fonte normativa central do projeto para especificar o que precisa ser implementado.

Nenhum código deve ser criado diretamente a partir de prompt, conversa, hipótese, carta isolada, README ou interpretação não incorporada ao LAYOUT.

## 4. CÓDIGO

Quando a investigação exigir código, scripts, automações, pipelines, modelos quantitativos, backtests ou outras implementações técnicas, a especificação deverá ser derivada exclusivamente do LAYOUT vigente.

## 5. Regra de precedência

A cadeia de autoridade é:

1. PROMPTS — intenção e requisitos iniciais;
2. CARTAS — consolidação normativa dos requisitos;
3. LAYOUT ÚNICO — fonte de verdade para implementação;
4. CÓDIGO — implementação derivada do LAYOUT.

## 6. Controle de alterações

Qualquer alteração relevante na metodologia deverá percorrer a cadeia documental antes de chegar ao código:

**novo requisito → atualização da CARTA → consolidação no LAYOUT → atualização/geração do CÓDIGO**

O código não deve criar regras que não estejam especificadas no LAYOUT.

## 7. Princípio de rastreabilidade

Todo código produzido para a investigação deve poder ser rastreado até o LAYOUT que autorizou sua criação.

O LAYOUT, por sua vez, deve permitir rastrear suas regras às CARTAS correspondentes, e as CARTAS devem permitir rastrear sua origem aos PROMPTS e às evidências pertinentes.
