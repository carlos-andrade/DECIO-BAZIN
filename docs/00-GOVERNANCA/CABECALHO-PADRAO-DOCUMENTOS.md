# PADRÃO DE CABEÇALHO DOS DOCUMENTOS — DECIO BAZIN

> **Regra operacional:** todo documento criado ou atualizado neste projeto deve iniciar com este cabeçalho padrão, preservando a identificação, rastreabilidade e estado documental.

## Cabeçalho padrão

    ---
    projeto: DECIO-BAZIN
    repositorio: carlos-andrade/DECIO-BAZIN
    tipo_documento: [PROMPT | FASE | EVIDÊNCIA | CARTA | LAYOUT | GOVERNANÇA | OUTRO]
    fase: [FASE XX]
    titulo: [TÍTULO DO DOCUMENTO]
    status: [RASCUNHO | EM INVESTIGAÇÃO | EM VALIDAÇÃO | VALIDADO | APROVADO | OBSOLETO]
    versao: [X.Y]
    data_criacao: [AAAA-MM-DD]
    data_atualizacao: [AAAA-MM-DD]
    origem: [PROMPT | CARTA | EVIDÊNCIA | LAYOUT | OUTRO]
    autoridade: PROMPTS → CARTAS → LAYOUT ÚNICO → CÓDIGO
    ---

## Regras

1. O cabeçalho é obrigatório em todos os novos documentos do projeto.
2. Em atualizações, o cabeçalho deve ser preservado e seus campos de estado, versão e data devem ser atualizados quando aplicável.
3. O cabeçalho não substitui o conteúdo documental; ele fornece identificação e rastreabilidade.
4. Nenhum documento deve omitir sua fase quando estiver vinculado a uma FASE.
5. O campo `origem` deve identificar de onde o documento deriva.
6. A cadeia de autoridade permanece obrigatória: **PROMPTS → CARTAS → LAYOUT ÚNICO → CÓDIGO**.
7. Alterações no padrão devem ser registradas no repositório antes de serem aplicadas aos documentos.
8. Documentos normativos de governança continuam sujeitos às proteções existentes do repositório.

## Aplicação inicial

Este padrão foi aplicado aos documentos da FASE 00 já criados:

- `PROMPT/PROMPT_FASE00_INVESTIGACAO_ORIGEM_DECIO_BAZIN.md`
- `FASES/FASE00_ORIGEM_E_ENTRADA_NO_MERCADO.md`
- `FASES/FASE00_EVIDENCIAS_DOCUMENTAIS_PRELIMINARES.md`

**Estado:** padrão estabelecido para o projeto DECIO-BAZIN.