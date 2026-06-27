# Parecer Previdenciário ao BNDES — Case Aurora Bioindustrial S.A.

Trabalho individual da disciplina de **Environmental, Social e Corporate Governance
(ESG)** do MBA em Inteligência Artificial Aplicada à Gestão — FGV In Company
(turma INSS). Prof. Felipe Borges, PMP.
Autor: **Adilson Guimarães Costa** — Analista do Seguro Social.

## Objetivo

Atuando como equipe técnica do INSS, emitir um parecer ao BNDES sobre a situação
previdenciária da empresa fictícia **Aurora Bioindustrial S.A.**, que solicitou
financiamento de **R$ 85 milhões**. A análise transforma os dados do case em
diagnóstico técnico, classificação de risco e recomendação fundamentada
(aprovar / aprovar com condicionantes / não aprovar).

## Estrutura do repositório

| Caminho | Conteúdo |
|---|---|
| `INSTRUCOES_PROJETO.md` | Prompt/instruções que orquestram a análise (papel, marco legal, escopo, produto, regras e checklist obrigatório). |
| `dados/` | Insumos do case: orientações do professor, enunciado e planilha de dados. |
| `saidas/` | As três versões do parecer e a documentação do teste de reprodutibilidade (ver `saidas/README.md`). |

## Método

A partir dos dados em `dados/`, as instruções produzem um parecer técnico com:
análise dos principais indicadores; três gráficos (recolhimentos, absenteísmo e
score de risco); matriz de achados (Domínio | Evidência | Risco | Impacto |
Recomendação); resposta às dez perguntas orientadoras; e conclusão com
recomendação final, condicionantes e um fecho conectando os achados às dimensões
Social e de Governança do ESG.

## Resultado e validação

O prompt foi submetido a um **teste de reprodutibilidade**: executado em um projeto
limpo e comparado a um parecer de referência. A convergência foi **alta** — mesma
recomendação (**aprovar com condicionantes**), mesmo score (**60,75/100**) e mesmos
achados e condicionantes. As lacunas observadas na primeira execução foram
corrigidas por um checklist nas instruções, evidenciando o ciclo
**prompt → teste → lacuna → correção**.

Detalhes completos do experimento em [`saidas/README.md`](saidas/README.md).
**Leitura recomendada:** `saidas/Parecer_BNDES_Aurora_consolidado.docx` (versão final).

## Aviso

Empresa, CNPJ e dados são **fictícios**, criados para fins didáticos. O parecer não
constitui análise real de crédito nem manifestação oficial do INSS ou do BNDES.

---
MBA em IA Aplicada à Gestão — FGV In Company (turma INSS) · Disciplina de ESG ·
Prof. Felipe Borges, PMP