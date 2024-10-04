
# Meu Repositório Git e GitHub

Este repositório foi criado como parte do curso de Git e GitHub na DIO. Ele contém exemplos práticos do uso dos principais comandos de Git e GitHub, além de dicas e links úteis.

# Documentação
Aqui estão os links para a documentação oficial de ambas as ferramentas:

- [Documentação do Git](https://- git-scm.com/docs/- git/pt_BR)
- [Documentação do GitHub](https://docs.github.com/pt)
# Comandos Básicos do Git   
 Aqui está um resumo dos principais comandos do Git utilizados durante o curso:

 - `- git init`: Inicializa um repositório Git na pasta atual.
- `- git clone [URL]`: Faz o download de um repositório remoto para sua máquina local.
- `- git add [arquivo]`: Adiciona um arquivo específico para a área de stage.
- `- git commit -m "[mensagem]"`: Salva as alterações adicionadas com uma mensagem descritiva.
- `- git commit --amend`: Permite modificar o último commit, alterando a mensagem ou adicionando mudanças adicionais.
- `- git push`: Envia suas alterações locais para o repositório remoto.
- `- git pull`: Atualiza seu repositório local com as últimas alterações do repositório remoto.
- `- git status`: Mostra o status atual do repositório (arquivos modificados, não rastreados etc.).
- `- git log`: Exibe o histórico de commits do repositório.

# Comandos de Branch e Fusões (Merge)
- `git branch`: Lista todas as branches do repositório.
- `git branch [nome-da-branch]`: Cria uma nova branch.
- `git checkout [nome-da-branch]`: Muda para a branch especificada.
- `git checkout -b [nome-da-branch]`: Cria e alterna para uma nova branch.
- `git merge [branch]`: Mescla a branch especificada com a branch atual.
- `git branch -d [nome-da-branch]`: Deleta a branch especificada.
- `git stash`: Salva temporariamente as alterações não committed (em uma stash) sem fazer um commit.
- `git stash pop`: Recupera as alterações salvas na stash e as aplica novamente ao código.
# Comandos de Repositório Remoto
- `git push`: Envia suas alterações locais para o repositório remoto.
- `git pull`: Atualiza seu repositório local com as últimas alterações do repositório remoto.
- `git remote add [nome] [URL]`: Conecta um repositório local a um remoto.
- `git remote -v`: Lista as URLs do repositório remoto.
# Comandos de Reset e Reversão
- `git reset --hard [commit]`: Reseta o repositório para o estado do commit especificado, descartando todas as alterações subsequentes.
- `git reset --soft [commit]`: Reseta o repositório para o commit especificado, mas mantém as mudanças na área de stage.
- `git revert [commit]`: Cria um novo commit que reverte as alterações feitas no commit especificado.