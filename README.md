# 📊 Dashboard de Desempenho Educacional

## Sobre o projeto

Projeto de Business Intelligence desenvolvido no Power BI com o objetivo de analisar o desempenho e o engajamento de estudantes de uma plataforma educacional fictícia.

O dashboard apresenta indicadores de aprendizagem, participação, desempenho por disciplina e nível de dificuldade, permitindo explorar informações por meio de gráficos, matrizes e filtros interativos.

## Tecnologias utilizadas

- Power BI Desktop
- DAX
- Power Query
- Modelagem relacional de dados
- CSV

## Estrutura do dashboard

### 📈 Página 1 — Visão Geral do Desempenho Educacional

Apresenta os principais indicadores, como total de respostas, alunos ativos, taxa de acerto, tempo médio de resposta e evolução mensal do desempenho.

![Visão Geral](imagens/visao_geral.png)

### 👥 Página 2 — Engajamento dos Estudantes

Analisa a participação dos estudantes, volume de questões respondidas, classificação de engajamento e ranking dos alunos mais ativos.

![Engajamento](imagens/engajamento.png)

### 🎯 Página 3 — Análise de Dificuldades

Compara as taxas de acerto entre disciplinas e níveis de dificuldade, utilizando matrizes, indicadores e rankings para identificar conteúdos com menores índices de acerto.

![Análise de Dificuldades](imagens/dificuldades.png)

## Modelagem de dados

O projeto utiliza três tabelas relacionadas:

- **alunos:** informações cadastrais e modalidades.
- **questoes:** disciplinas e níveis de dificuldade.
- **respostas:** registros de respostas, acertos e tempo de resolução.

As tabelas foram conectadas por relacionamentos de um para muitos, permitindo cruzar informações entre estudantes, questões e respostas.

## Indicadores desenvolvidos

- Total de respostas
- Quantidade de alunos ativos
- Taxa de acerto
- Tempo médio de resposta
- Taxa de participação
- Média de respostas por aluno
- Engajamento dos estudantes
- Desempenho por disciplina e dificuldade

## Principais análises

O dashboard permite identificar disciplinas com menores taxas de acerto, comparar resultados conforme o nível de dificuldade das questões e acompanhar a variação do desempenho ao longo do tempo.

Também possibilita investigar padrões de participação e concentração de atividade entre os estudantes.

## Como visualizar

As imagens das três páginas estão disponíveis neste repositório.

Para explorar os gráficos e filtros interativos, baixe o arquivo `Dashboard_Desempenho_Educacional.pbix` e abra-o no Power BI Desktop.

## Sobre os dados

Este é um projeto demonstrativo desenvolvido com dados simulados para fins de estudo e portfólio. Os resultados não representam informações reais de alunos ou de uma instituição de ensino.

---

**Desenvolvido por Maria Eduarda Carvalho**

Sistemas de Informação | Dados • Business Intelligence • Tecnologia
