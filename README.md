> CONFIGURACAO GIT

      > Versao do git = git --version
      > Configuracao = git config --global --list
      > Adicionar usuario = git config --global user.name "<nome-usuario>"
      > Adicionar usuario = git config --global user.email <email>

> INICIALIZACAO DE REPOSITORIO

      > Iniciar o repositorio = git init

> ADICIONAR ARQUIVOS NO STAGE

      > Identificar arquivos do STAGE = git status
      > Adicionar um arquivo para commit = git add <nome-do-arquivo>.<tipo-de-arquivo>
      > Remover um arquivo adicionado para commit = git rm --cached <nome-do-arquivo>.<tipo-de-arquivo>
      > Adicionar todos os arquivos = git add .

> EXECUTAR COMMIT

      > Fazer um commit comentado = git commit -m "<comentario>"
      > Ver historico de commits = git log
      > Ver historico de commits resumido = git log --oneline
      
> COMO REVERTER COMMIT(checkout = seguro, revert = pouco seguro e reset = elimina todos os commits selecionados)

      > Voltar para um commit(checkout)(volta no tempo) = git checkout <id-commit> (o id esta em git log)
      > Voltar ao ultimo commit(pos checkout) = git checkout <brach>
      > Reverter um commit(revert)(reverte um alteracao) = git revert <id-commit> (o id esta em git log)
      > Apagar commits(reset)(apaga commits, mas nao alteracoes) = git reset <id-commit> (o id esta em git log)
      > Apagar commits(reset)(APAGA TUDO) = git reset <id-commit> --hard
      
> IGNORANDO ARQUIVOS

      > Arquivo que ignora outros arquivos = touch .gitignore
      > Adicionar o arquivo ignorado no git .gitignore
      
> MANIPULACAO DE BRENCH(copia de um commit | linha paralela | arquivos criado em um branch ficam limitados a ela )

      > Listar branchs = git branch
      > Criar branch = git branch <nome-da-nova-branch>
      > Trocar de branch = git checkout <nome-da-branch>
      > Deletar branch SEM commits = git branch -d <nome-da-branch>
      > Deletar branch COM commits = git branch -D <nome-da-branch>
      
> FUNDIDO BRANCH (Para unir branchs é necessario estar na branch de destino)

      > Unir branchs = git merge <nome-da-branch> (caso o nano seja aberto basta fecha-lo)

> CONFLITOS GIT

      > Resolver entre o time de desenvolvimento e realizar alteracao
      > Utilizar vsCode ou editor de texto

> TROCA ENTRE GIT E GITHUB

      > Subir arquivos para gitHub = git push <link-do-repositorio> <branch>
      > Criar um resumo do link = git remote add <nome-resumido(normal: origin)> <link-do-repositorio>
      > Como enviar após criar link resumido = git push <nome-resumido> <branch>
      > Consultar repositorio remoto = git remote -v
      > Clonar projeto do gitHub = git clone <link-do-repositorio>
      > Pegar atualizacao do repositorio remoto(sempre realizar ao trabalhar em um projeto) = git pull origin <branch>
      
> ABERTURA DE PULL REQUEST

      > Lancar um pull request request: git push origin <branch>

> TERMINAL

      > Ver arquivo nao visivel = ls -a
      > Acessar arquivo invisivel .git(não necessario)= cd .git
      > Criar arquivo = touch <nome-do-arquivo>.<tipo-arquivo>
      > Ao abrir a tela do nano(linux): Ctrl + x | em outro digitar= :q
      > Excluir pasta com arquivos = rm -rf <nome-pasta>
      
> OUTRO

      > Criar chave SSH
      

> PLAYLIST CURSO GIT: https://www.youtube.com/watch?v=n_GEGPuNNRA&list=PLcoYAcR89n-qbO7YAVj5S0alABLis_QVU&index=15
