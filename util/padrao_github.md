# Padrões no Github

## Issues

```
## Título da issue

## Descrição: 
Descrever o objetivo da issue resumidamente, inserindo informações importantes para a compreensão.

## Critérios de aceitação: 
Escrever o que a issue precisa obter para ser dada como concluída.

## Tarefas:
Checklist de tarefas a serem feitas.
- [ ]
```

## Branch

- docs/nome-documento: modificações no geral relaciondas a documentação
- fix/descricao-simples: resolução de um bug
- feature/descricao-simples: funcionalidade, tarefa ou melhoria realizada
- minute/dia-mes-ano: adição de uma ata

## Commit

- test: indica qualquer tipo de criação ou alteração de códigos de teste.
- feat: indica o desenvolvimento de uma nova feature ao projeto. 
- refactor: usado quando houver uma refatoração de código que não tenha qualquer tipo de impacto na lógica/regras de negócio do sistema.
- style: empregado quando há mudanças de formatação e estilo do código que não alteram o sistema de nenhuma forma.
- fix: utilizado quando há correção de erros que estão gerando bugs no sistema.
- chore: indica mudanças no projeto que não afetem o sistema ou arquivos de testes. São mudanças de desenvolvimento.
- docs: usado quando há mudanças na documentação do projeto.
- build: utilizada para indicar mudanças que afetam o processo de build do projeto ou dependências externas.
- perf: indica uma alteração que melhorou a performance do sistema.
- ci: utilizada para mudanças nos arquivos de configuração de CI.
- revert: indica a reverão de um commit anterior.

## Pull Request

```
## Descrição
Escreva uma breve descrição sobre o que o Pull Request resolve

[Nome da Issue](link_da_issue)

## Porque este Pull Request é necessário?
Descreva o motivo da realização do documento

## Critérios de aceitação
(Exemplos de critérios de aceitação)

1. [ ] Todas as informações necessárias estão presentes?
2. [ ] O documento está escrito de forma concisa?
3. [ ] A ortografia do documento está correta?

Resolve #(numero_da_issue)
```
## Histórico de Versão

|   Versão   | Data  |                      Descrição                      |    Autor(es)     |  Revisor(es)  |
| :--------: | :---: | :-------------------------------------------------: | :--------------: | :-----------: |
| `1.0`      | 19/04/2023 | Versão inicial com os padrões para criar issue, branch,commit e pull request | Ana Beatriz e Breno Yuri | Carlos Daniel |

## Referências
'''
RIBEIRO, V. Conventional Commits Pattern. Disponível em: <https://medium.com/linkapi-solutions/conventional-commits-pattern-3778d1a1e657>. Acesso em: 19 abr. 2023.
‌'''
