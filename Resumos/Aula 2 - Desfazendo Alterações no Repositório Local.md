## 🚩 Aula 2 - Desfazendo Alterações no Repositório Local

Um breve resumo de funções e ferramentas da Aula 2

| Ferramenta | Descrição |
| -----------|-----------|
| git restore [Arquivo] | Restaurar um arquivo |
| git commit --amend -m | Substitui o título de um commit |
| git reset | Redefine o HEAD atual para o estado especificado |
| git reset --soft [commit] | Não toca no arquivo de índice ou na árvore de trabalho (mas redefine o head para <commit>, assim como todos os modos fazem). Isso deixa todos os seus arquivos alterados "Alterações a serem confirmadas", como git status diria |
| git reset --mixet [commit] | Redefine o índice, mas não a árvore de trabalho (ou seja, os arquivos alterados são preservados, mas não marcados para confirmação) e relata o que não foi atualizado. |
| git reset --hard [commit] | Redefine o índice e a árvore de trabalho. Quaisquer alterações nos arquivos rastreados na árvore de trabalho desde então <commit>serão descartadas. Quaisquer arquivos ou diretórios não rastreados na forma de gravação de arquivos rastreados são simplesmente excluídos. |
| git reflog | histórico mais detalhado com as atualizações de commit |