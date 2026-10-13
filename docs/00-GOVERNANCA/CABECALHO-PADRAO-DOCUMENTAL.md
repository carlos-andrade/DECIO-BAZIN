# NORMA DOCUMENTAL — CABEÇALHO PADRÃO DO PROJETO DECIO-BAZIN

> **ID:** MDB-GOV-HEADER-001  
> **Tipo:** Norma de governança documental  
> **Versão:** 1.0.0  
> **Estado:** EM_REVISAO  
> **Data de criação:** 2026-10-13  
> **Data de revisão:** 2026-10-13  
> **Responsável (owner):** Projeto DECIO-BAZIN  
> **Aprovador:** Pendente de aprovação formal  
> **Origem:** Sistema de governança do repositório DECIO-BAZIN e sistema mestre GOVERNANCA  
> **Escopo:** Documentos Markdown de pesquisa criados ou alterados no repositório, incluindo PROMPTS, CARTAS, LAYOUT, evidências, relatórios e README de pastas.  
> **Norma superior:** [PROMPTS → CARTAS → LAYOUT ÚNICO → CÓDIGO](REGRA-PROMPTS-CARTAS-LAYOUT-CODIGO.md)

## 1. Objetivo

Aplicar um cabeçalho documental uniforme, identificável e rastreável aos artefactos do projeto. O cabeçalho não transforma um documento em norma aprovada nem substitui revisão técnica ou validação das fontes.

## 2. Cabeçalho normativo obrigatório

Todo documento Markdown de projeto criado ou substancialmente atualizado deve conter, logo após o título (ou antes do título se necessário para parsers), os seguintes metadados:

```markdown
> **Cabeçalho padrão documental — DECIO-BAZIN**
> - **ID:** [identificador único]
> - **Tipo:** [PROMPT | CARTA | LAYOUT | EVIDÊNCIA | RELATÓRIO | README | NORMA]
> - **Versão:** [MAJOR.MINOR.PATCH]
> - **Estado:** [RASCUNHO | EM_REVISAO | APROVADO | REJEITADO | CONCLUIDO | DEPRECADO]
> - **Data de criação:** AAAA-MM-DD
> - **Data de revisão:** AAAA-MM-DD
> - **Responsável (owner):** [papel ou equipa]
> - **Aprovador:** [identidade/papel ou "Pendente"]
> - **Origem/rastreabilidade:** [prompt, carta, evidência, issue ou documento pai]
> - **Escopo:** [finalidade e limites do documento]
> - **Norma superior:** [link à regra de governança aplicável]
```

## 3. Regras de preenchimento

1. **ID único:** padrão sugerido `MDB-[TIPO]-NNN`; IDs existentes podem ser preservados se não houver colisão.
2. **Versão:** começar em `1.0.0`; incremento MAJOR para ruptura incompatível, MINOR para nova funcionalidade/escopo, PATCH para correção sem mudança de intenção.
3. **Estado controlado:** utilizar os estados documentais do sistema GOVERNANCA e explicitar quando o artefacto está em revisão. Nunca usar APROVADO sem evidência de aprovação.
4. **Datas ISO:** usar `AAAA-MM-DD`. Data de revisão só é alterada quando o conteúdo é efetivamente revisto.
5. **Origem:** qualquer conclusão metodológica deve poder ser rastreada a prompt, carta e fontes pertinentes.
6. **Escopo:** declarar o que o documento cobre e, quando necessário, o que não cobre.
7. **Aprovador:** documento em proposta ou investigação permanece sem aprovador formal.
8. **Links:** caminhos relativos devem ser corrigidos conforme a localização; evitar links quebrados.
9. **Código:** comentários ou documentação técnica também devem apontar para o LAYOUT vigente que autorizou a implementação.
10. **Integridade normativa:** esta norma não substitui nem altera a regra protegida `REGRA-PROMPTS-CARTAS-LAYOUT-CODIGO.md`.

## 4. Identidade e aplicação

- Documento de governança: `MDB-GOV-HEADER-001`.
- Comentário de identificação para validação automatizada: `CABECALHO-PADRAO-DECIO-BAZIN: MDB-HDR-001 v1.0.0`.
- A validação automatizada deve exigir o marcador e os metadados mínimos nos documentos cobertos.
- Novos documentos devem copiar o cabeçalho padrão, não criar variantes locais.
- Documentos históricos que ainda não foram revistos devem ser inventariados e migrados progressivamente, preservando conteúdo e histórico.

## 5. Migração inicial

A primeira aplicação será feita aos documentos do dossiê `METODO DECIO BAZIN/`. O restante do repositório será inventariado, migrado por etapas e validado sem modificar conteúdo metodológico sem necessidade.

## 6. Critérios de aceitação

- Norma versionada e rastreável no repositório.
- Cabeçalhos adicionados aos documentos iniciais.
- Links para norma e regra superior conferidos.
- Workflow valida o marcador e os metadados mínimos.
- Nenhuma alteração ao texto protegido da regra PROMPTS → CARTAS → LAYOUT → CÓDIGO.
