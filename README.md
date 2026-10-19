# curso_colaborativo
Repositório para prática de desenvolvimento colaborativo


1. Gestão de Branches (Ramificações)

• Nunca faça commits diretamente na branch principal (main ou master): A branch principal deve conter apenas código estável e pronto para produção.
• Use Feature Branches: Crie uma nova branch para cada nova funcionalidade, correção de erro (bugfix) ou melhoria. Use nomes descritivos, como feature/autenticacao-oauth ou bugfix/correcao-login.
• Sincronize o código constantemente: Antes de iniciar o trabalho ou abrir um pedido de integração, atualize a sua branch local com a branch de desenvolvimento atualizada (git pull) para evitar conflitos complexos no futuro.

2. Fluxo de Trabalho e Integração (Pull Requests)

• Trabalhe com Pull Requests (PRs): Para enviar o seu código para o projeto principal, abra sempre um Pull Request. É através dele que a equipa analisa o que foi feito.
• Revisão de Código (Code Review): Exija a aprovação de pelo menos um ou dois colegas de equipa antes de realizar o merge de um PR. A revisão ajuda a encontrar falhas e a partilhar conhecimento técnico.
• Descrição Clara: Ao abrir um PR, explique detalhadamente o que foi alterado, o motivo da alteração e como testar o código enviado.

3. Commits Organizados

• Commits Pequenos e Atómicos: Faça commits frequentes focado em apenas uma tarefa lógica. Evite acumular dias de trabalho num único commit gigante.
• Mensagens de Commit Padronizadas: Escreva mensagens claras e imperativas (ex: feat: adiciona botão de logout ou fix: corrige validação de e-mail). Muitas equipas utilizam o padrão Conventional Commits.

4. Documentação e Organização do Repositório

• Ficheiro README.md completo: O repositório deve ter um ficheiro explicativo sobre o propósito do projeto, como configurar o ambiente local e como executar os testes.
• Ficheiro CONTRIBUTING.md: Essencial para definir as regras locais da comunidade ou da empresa sobre como novos programadores devem submeter alterações.
• Uso de Issues e Kanban: Utilize as Issues do GitHub para reportar erros ou sugerir melhorias, integrando-as aos Projetos do GitHub (quadro Kanban) para organizar as tarefas em "A fazer", "Em andamento" e "Concluído".
