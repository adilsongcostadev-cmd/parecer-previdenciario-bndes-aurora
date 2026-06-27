# Parecer Previdenciário ao BNDES — Case Aurora Bioindustrial S.A.

Trabalho individual da disciplina de ESG (Environmental, Social e Corporate
Governance) do MBA em IA Aplicada à Gestão — FGV In Company (turma INSS).
Prof. Felipe Borges, PMP. Aluno: Adilson Guimarães Costa, Analista do Seguro Social.

## Objetivo
Atuando como equipe técnica do INSS, emitir parecer ao BNDES sobre a situação
previdenciária da empresa fictícia Aurora Bioindustrial S.A., que solicitou
financiamento de R$ 85 milhões.

## Estrutura do repositório
- `INSTRUCOES_PROJETO.md` — prompt/instruções que orquestram a análise.
- `dados/` — case, planilha de dados e orientações do professor.
- `saidas/` — parecer gerado e estudo de reprodutibilidade.

## Método
As instruções foram desenhadas para, a partir dos dados em `dados/`, produzir um
parecer técnico com gráficos, matriz de achados e recomendação final
(aprovar / aprovar com condicionantes / não aprovar).

## Teste de reprodutibilidade
As instruções deste projeto foram validadas executando o prompt em um projeto
limpo e comparando a saída com um parecer de referência.

- Convergência alta: ambos recomendaram APROVAR COM CONDICIONANTES, com score
  idêntico (60,75) e os mesmos achados e condicionantes.
- Lacunas detectadas na 1ª execução: ausência da resposta explícita às 10
  perguntas e do fecho ESG — itens já previstos nas instruções.
- Ação corretiva: inclusão de um "Checklist obrigatório" nas instruções para
  garantir esses itens em execuções futuras.

Saídas em `/saidas`: parecer do projeto, parecer de referência e versão consolidada.