# Guia de Contribuição

## Introdução

Obrigado por considerar contribuir para este projeto! Este guia detalha como você pode colaborar e o que esperamos de suas contribuições. A seguir estão os padrões e práticas recomendadas para tornar o processo de contribuição eficiente para todos os envolvidos.

## Sumário

2. [Branches](#branches)
3. [Commits](#commits)
4. [Pull Requests](#pull-requests)
5. [Código de Conduta](#código-de-conduta)

## Branches

O padrão para nomear uma nova branch é:

```
NumeroDaIssue-Nome-Da-branch
```

Por exemplo, se você está trabalhando na Issue #42 e sua tarefa é implementar um botão de gavoritar, então sua branch deve ser nomeada assim:

```
42-botao-favoritar
```

## Commits

Utilizamos o seguinte padrão para mensagens de commit:

```
gitmoji - Mensagem
```

O Gitmoji serve para adicionar um contexto visual ao commit. Por exemplo, se você fez um bugfix, pode usar o Gitmoji de bug 🐛.
Além de que os commits tem que ser atômicos e significativos.

[GitMoji](https://gitmoji.dev/)

Exemplo de commit:

```
git commit -m "🐛 Corrige erro de digitação"
```

## Pull Requests

O título e a descrição do Pull Request devem ser claros e fornecer informações suficientes para que os revisores entendam o que este PR faz. Seguindo o template para ciração de PR.

```
Descrição

Porque este Pull Request é necessário?

Critérios de Aceitação
Checklist

Resolve #Número_da_Issue.

```

## Código de Conduta

Ao participar deste projeto, você deve concordar em seguir nosso Código de Conduta. Por favor, leia [Código de Conduta](Codigo_de_Conduta.md) para mais informações. 