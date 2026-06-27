# Saídas — Parecer Previdenciário ao BNDES (Aurora Bioindustrial S.A.)

Esta pasta reúne os três produtos gerados a partir das instruções do projeto e o
registro do teste de reprodutibilidade que validou o prompt.

## Arquivos

| Arquivo | Origem | Descrição |
|---|---|---|
| `Parecer_BNDES_Aurora_projeto.docx` | Projeto novo (prompt isolado) | Parecer gerado executando as instruções do projeto em ambiente limpo. |
| `Parecer_BNDES_Aurora_referencia.docx` | Parecer de referência | Versão independente, usada como base de comparação. |
| `Parecer_BNDES_Aurora_consolidado.docx` | Melhor dos dois | Versão final: capa com autoria e união dos pontos fortes das duas saídas. |

## Teste de reprodutibilidade

Método: o prompt das instruções foi executado em um projeto novo (sem o histórico
de desenvolvimento) e a saída foi comparada, item a item, com o parecer de
referência.

### Convergências (alta aderência)
- Recomendação final idêntica: **APROVAR COM CONDICIONANTES**.
- Score técnico idêntico: **60,75 / 100** (faixa 60–79).
- Mesmo cálculo de custeio: devida R$ 39,35 mi × recolhida R$ 35,45 mi → diferença
  de R$ 3,9 mi.
- Mesmo diagnóstico nos seis domínios (recolhimentos, obrigações acessórias,
  absenteísmo, SST/CAT, terceirização e contencioso).
- Conjunto de condicionantes praticamente idêntico.

### Lacunas detectadas na 1ª execução
- Ausência da resposta **explícita e rastreável às 10 perguntas orientadoras**.
- Ausência do **fecho ESG** (dimensões Social e de Governança) na conclusão.
- Ambos os itens já estavam previstos nas instruções, mas se diluíram na geração.

### Ação corretiva
- Inclusão de um **Checklist obrigatório** nas instruções do projeto, para garantir
  esses itens em execuções futuras.
- Atualização da matriz de achados para o formato de cinco colunas
  (Domínio | Evidência | Risco | Impacto | Recomendação), incorporado na versão
  consolidada.

## Conclusão do experimento

A comparação evidenciou **alta reprodutibilidade**: a partir dos mesmos dados e
instruções, a recomendação, o score, os achados e as condicionantes foram
reproduzidos de forma independente. As poucas divergências foram de completude
(itens diluídos), corrigidas pelo checklist — demonstrando o ciclo
**prompt → teste → lacuna → correção**.

---
Autor: Adilson Guimarães Costa — Analista do Seguro Social
Disciplina: Environmental, Social e Corporate Governance (ESG) — MBA em IA Aplicada
à Gestão (FGV In Company, turma INSS) — Prof. Felipe Borges, PMP