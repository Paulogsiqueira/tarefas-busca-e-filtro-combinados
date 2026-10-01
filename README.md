# Lista de Tarefas — Busca e Filtro Combinados

Lista de tarefas em que busca por título e filtro por situação valem ao mesmo tempo, nunca um substituindo o outro: a lista exibida vem de um único `computed` que aplica os dois critérios sobre cada tarefa.

## Funcionalidades

- Cadastro, conclusão, reabertura e remoção de tarefas
- Contador de tarefas pendentes atualizado automaticamente
- Busca por título (sem diferenciar maiúsculas de minúsculas) e filtro por situação aplicados em conjunto
- Ex.: buscar "vue" com o filtro em "Concluídas" mostra só as tarefas concluídas cujo título contém "vue"

## Rodando o projeto

```bash
npm install
npm run dev
```
