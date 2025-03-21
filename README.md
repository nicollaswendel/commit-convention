# Convenção de Commits

Para garantir clareza e consistência no controle de versão, adoto a seguinte convenção de commits. Cada commit deve ser realizado de forma clara e objetiva, de modo a refletir com precisão o que foi alterado no código.

## Estrutura do Commit
Cada commit deve seguir a seguinte estrutura:
- **tipo:** *descrição breve e direta (referência a issue ou task)*

### Tipos de Commit

- **feat**: Adição de nova(s) funcionalidade(s).
`feat: adiciona filtro por data na listagem de empreendimentos`

- **fix**: Correção de bug(s).
`fix: corrige erro ao salvar vistoria`

- **refactor**: Refatoração do código, sem alterar funcionalidades.
`refactor: remove lógica duplicada no serviço de autenticação`

- **chore**: Mudanças que não afetam código-fonte ou testes (configs, dependências, build, etc.).
`chore: atualiza dependências do projeto`

- **docs**: Atualizações na documentação.
`docs: adiciona exemplo de uso da API no README`

- **test**: Adição ou ajuste de testes.
`test: cria testes unitários para serviço de notificações`

- **style**: Alterações visuais ou formatação do código (espaços, indentação, etc.).
`style: padroniza espaçamento no arquivo de configuração`

- **perf**: Alterações que melhoram a performance do sistema.
`perf: otimiza consulta SQL para reduzir tempo de resposta`

## Mensagem do Commit

- **Mensagem curta (padrão)**: A mensagem deve ser escrita no **imperativo** e no **presente** (exemplo: "adiciona", "corrige", "refatora").
- **Mensagem detalhada (se necessário)**: Explicar o motivo da alteração.

## Boas Práticas

- **Evite commits grandes**: Divida os commits de acordo com as funcionalidades ou correções.
- **Evite commits desnecessários**: Não faça commits apenas para salvar seu progresso, a menos que seja uma mudança significativa.
- **Seja específico**: A mensagem deve ser clara e objetiva sobre a alteração realizada.
