#Iniciando os estudos no curso da DIO.ME

##Afinal qual a diferença do GIT para o GitHub?

De forma simples GIT é um sistema de controle de versão e GITHUB é um serviço em nuvem que usou o GIT como base para a criação do GITHUB.

Bom eu já tenho o GIT instalado, pois já estudei um pouco do GITHUB e hoje não lembro quase nada, mas blz, vamos para o primeiro comando para ver o usuário configurado e o  verificando a versão do GIT.

Exibindo a configuração de usuário do GIT
git config --list

Exibindo a versão instalada do GIT
git --version

Agora os TOP 19 comandos mais usado

- git init: inicia um novo repositório no diretório atual
- git clone [URL]: Clona um repositório GIT existente para o diretório local.
- git add .: O ponto indica o diretório atual e faz parte do comando! O Comando adiciona alterações ao índica(staging area) prepará-las para o commmit.
- git commit -m "mensagem": Realiza um commit com as alterações adicionadas e inclue uma mensagem descritiva das mudanças feitas. O commit captura o estado exato dos arquivos preparados em um determinado momento, criando um ponto específico na linha do tempo do histórico do projeto. 
- git status: Exite o status atual do repositório, indicando quais arquivos foram modificados, adicionados ou removidos.
- git log: mostra o histórico de commits do repositório.
- git branch: Lista todas as branches locais e destaca a branch atual.
- git branch [nome da branch]: Cria uma nova branch.
- git checkout [nome da branch] altera para uma branch específica.
- git merge [branch]: combina as alterações de uma branch para a branch atual
- git pull: atualiza o repositório local com as alterações do repositório remoto.
- git push: Envia os commits locais para o repositório remoto
- git remote -v: Lista repositórios remotos configurados.
- git fetch: Recupera as últimas alterações do repositório remoto, mas não faz merge automativamente.
- git reset [arquivo]: Desfaz as alterações no arqvuio especificado, removendo-o do índice.
- git rm [arquivo]: Remove um arquivo do repositório e o inclui no próximo commit.
- git diff: Mostra as diferenças ente as alterações que ainda não foram adicionadas ao indice.
- git remote add [nome do arquivo] [URL]: Adiciona um repositório remoto com um nome específico.
- git push add origin main: Executado para efetuar o push das alterações locais para o repositório online.


Esses dois comandos dificilmente você vai usar, geralmente você assim como eu que não lembra a configuração do GIT na máquina e para verificar se ainda é compatível. 

Links de estudo

Github DOCs
https://docs.github.com/pt/get-started/start-your-journey/about-github-and-git

Conceitos básicos do GIT e do GITHUB
https://learn.microsoft.com/pt-br/contribute/content/git-github-fundamentals
