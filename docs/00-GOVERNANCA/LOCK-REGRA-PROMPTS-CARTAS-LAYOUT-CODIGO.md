# BLOQUEIO NORMATIVO — REGRA PROMPTS → CARTAS → LAYOUT → CÓDIGO

## Estado

**REGRA PROTEGIDA — NÃO ALTERAR**

Este arquivo registra a identidade criptográfica da regra normativa:

`docs/00-GOVERNANCA/REGRA-PROMPTS-CARTAS-LAYOUT-CODIGO.md`

### SHA-256 canônico

`db371eb2bec44c1787851ca925e8507cc553b3fc0914f49cbb2a412e8ca74754`

### Regra

A cadeia **PROMPTS → CARTAS → LAYOUT ÚNICO → CÓDIGO** é estrutural e não pode ser invertida, ignorada ou substituída por outro fluxo.

Qualquer mudança legítima na metodologia deve criar uma nova proposta documental, passar pelo processo de revisão e somente então, se autorizada, substituir formalmente a versão normativa.

Uma alteração direta na regra normativa deve ser tratada como violação de governança.

### Mecanismo

O workflow `.github/workflows/verificar-regra-normativa.yml` compara continuamente o SHA-256 do arquivo normativo com o valor canônico acima.

Se houver divergência, a verificação falha.

**Importante:** a proteção efetiva contra alteração exige também proteção da branch `main` no GitHub, com Pull Request obrigatório e aprovação de CODEOWNERS. O arquivo de CODEOWNERS deste repositório foi preparado para esse controle.
