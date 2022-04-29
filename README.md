# Meu manual Git

**(Cria e posta arquivo)**
- 1º Passo: cd *CaminhoDaPasta* --> `faz com que se navegue da pasta atual para uma determinada pasta`
- 2º Passo: git init --> `Inicializa o Repositório`
- 3º Passo: git add . --> `Coloca o arquivo na área de Sttaging`
- 4º Passo: git commit -m "*nomeDoCommit*" --> `para de fato dar o commit no repositório`
- 5º Passo: git remote add origin https://github.com/*nome do Usuário*/*nome do repositório*.git --> `Para passar o commit do meu repositório local (da minha máquina) para um repositório na plataforma do Github`
- 6º Passo: git branch -M main --> `para alterar o nome da branch principal de master para main`
- 7º Passo: git push -u origin main --> `Empurrar o Commit de fato pro repositório`

&nbsp;

**(Altera e posta arquivo)**
- 1º Passo: cd *CaminhoDaPasta* --> `faz com que se navegue da pasta atual para uma determinada pasta`
- 2º Passo: git add . --> `Coloca todos os arquivos na área de Stagging`
- 3º Passo: git commit -m "*nomeDoCommit*" --> `para de fato dar o commit no repositório`
- 4º Passo: git push origin --> `Empurrar o Commit de fato pro repositório`

&nbsp;

&nbsp;

**Comandos**
- comando cd: irá fazer com que você navegue da pasta atual para uma determinada pasta
- git init
- git commit -m "primeiro commit"
- git branch -M "main"
- git remote add origin <link do repositório>
- origin = 
- git push -u origin main
- git pull: puxa todas as alterações feitas no repositório do Github para o seu repositório local
