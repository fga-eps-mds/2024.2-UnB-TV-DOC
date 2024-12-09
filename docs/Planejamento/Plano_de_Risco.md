# Plano de Riscos

## 1. Introdução

O desenvolvimento de software, como qualquer outra atividade, envolve riscos. Riscos são situações que podem afetar o progresso da equipe no processo de desenvolvimento. Portanto, é essencial identificar esses riscos, detalhá-los, avaliar a probabilidade de ocorrência, o impacto que causariam e, finalmente, definir ações a serem tomadas caso esses riscos se concretizem.

## 2. Categorias

Para organizar de forma eficaz o **Plano de Riscos**, foram definidas as seguintes categorias de risco:

- **Organizacional**: Relacionado à falta de recursos humanos ou tecnológicos.
- **Gerencial**: Riscos ligados ao tempo de produção do projeto.
- **Técnico**: Engloba riscos relacionados à tecnologia, como problemas de compatibilidade de plataformas e falhas de hardware ou software.
- **Externo**: Abrange riscos fora do controle direto da equipe.

## 3. Análise qualitativa e quantitativa 

Para priorizar os riscos de forma eficaz, foram estabelecidas algumas métricas. A probabilidade de ocorrência dos riscos será registrada a cada sprint, permitindo que os membros da equipe forneçam suas percepções sobre a probabilidade de um risco acontecer. Abaixo estão as métricas utilizadas, com uma breve explicação e os valores correspondentes:

### 3.1: Probabilidade

A probabilidade indica a chance de um risco identificado ocorrer.

| Probabilidade | Explicação                                  | Valor |
|---------------|---------------------------------------------|-------|
| Muito Baixo   | Chance muito baixa de acontecer (1% - 20%)  | 1     |
| Baixo         | Chance baixa de acontecer (21% - 40%)       | 2     |
| Médio         | Chance média de acontecer (41% - 60%)       | 3     |
| Alto          | Chance alta de acontecer (61% - 80%)        | 4     |
| Muito Alto    | Chance muito alta de acontecer (81% - 100%) | 5     |

### 3.2: Impacto

O impacto refere-se aos efeitos causados caso o risco se concretize.

| Impacto       | Explicação                                  | Valor |
|---------------|---------------------------------------------|-------|
| Muito Baixo   | Quase nenhum impacto ao projeto             | 1     |
| Baixo         | Pequeno impacto ao projeto                  | 2     |
| Médio         | Algum impacto ao projeto                    | 3     |
| Alto          | Compromete o andamento do projeto           | 4     |
| Muito Alto    | Torna inviável o andamento do projeto       | 5     |

### 3.3: PROBABILIDADE x IMPACTO

A combinação da probabilidade e do impacto é calculada multiplicando o valor de cada um (P x I).

| P x I       | Muito Baixo | Baixo | Médio | Alto | Muito Alto |
|-------------|:-----------:|:-----:|:-----:|:----:|:----------:|
| Muito Baixo |      1      |   2   |   3   |   4  |      5     |
| Baixo       |      2      |   4   |   6   |   8  |     10     |
| Médio       |      3      |   6   |   9   |  12  |     15     |
| Alto        |      4      |   8   |   12  |  16  |     20     |
| Muito Alto  |      5      |   10  |   15  |  20  |     25     |

### 3.4 Prioridade

Com base no cálculo da combinação da probabilidade e impacto, é possível determinar a prioridade do risco. Isso permite que a equipe se organize melhor caso o risco ocorra.

| Prioridade  | Intervalo |
|-------------|:---------:|
| Muito Baixo |   1 a 5   |
| Baixo       |   6 a 10  |
| Médio       |  11 a 15  |
| Alto        |  16 a 20  |
| Muito Alto  |  21 a 25  |


## Monitoramento de Risco
A monitorização contínua dos riscos é essencial no desenvolvimento de um projeto de software, pois os riscos são dinâmicos e podem variar em intensidade ao longo do ciclo de vida do projeto. Para otimizar esse acompanhamento, foi desenvolvida uma planilha na qual a pontuação dos riscos é registrada a cada sprint, permitindo uma avaliação constante e ajustável dos riscos identificados, facilitando a adaptação das estratégias conforme a evolução do projeto.

Link Para Planilha: [Planilha de Riscos](https://unbbr-my.sharepoint.com/:x:/g/personal/160112028_aluno_unb_br/ERIq2x61IINKk53VNtuuVDQBkFeT9yuiHtn6NzF1D9Lm6Q?e=4k1Qnd)

# Referências

> [1] Saiba mais sobre o gerenciamento de riscos do PMBOK. Disponível em: https://www.projectbuilder.com.br/blog/saiba-mais-sobre-o-gerenciamento-de-riscos-do-pmbok/. Acesso em: 03 out 2023.

| Data | Versão | Descrição | Autor |
| :-----: | :-------------: | :---------------: | :-: |
| 09/12/2024 | 1.0 | Criação do documento do Plano de Risco | [André Goretti](https://github.com/AGoretti) |

