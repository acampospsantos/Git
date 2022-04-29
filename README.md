# Meu manual Git (Comandos)

## (Cria e posta arquivo)
1. Passo: **cd [CaminhoDaPasta]** --> `faz com que se navegue da pasta atual para uma determinada pasta`
2. Passo: **git init** --> `Inicializa o Repositório`
3. Passo: **git add .** --> `Coloca todos arquivo na área de Sttaging(estado entre working diretory e repository)`
4. Passo: **git commit -m "[nomeDoCommit]"** --> `para de fato dar o commit no repositório`
5. Passo: **git remote add origin https://github.com/[nomeUsuário]/[nomeRepositório].git** --> `Para passar o commit do meu repositório local (da minha máquina) para um repositório na plataforma do Github`
6. Passo: **git branch -M main** --> `para alterar o nome da branch principal de master para main`
7. Passo: **git push -u origin main** --> `Empurrar o Commit de fato pro repositório`


## (Altera e posta arquivo)
1. Passo: **cd [CaminhoDaPasta]** --> `faz com que se navegue da pasta atual para uma determinada pasta`
2. Passo: **git add .** --> `Coloca todos os arquivos na área de Stagging`
3. Passo: **git commit -m "[nomeDoCommit]"** --> `para de fato dar o commit no repositório`
4. Passo: **git push origin** --> `Empurrar o Commit de fato pro repositório`

&nbsp;

## Comandos
- **cd [caminhoDaPasta]**: *irá fazer com que você navegue da pasta atual para uma determinada pasta*
- **git init**: *inicializa(cria) o repositório*
- **git add [nomeArquivo]**: *Coloca o arquivo/pasta nomeado na área de Sttaging(estado entre working diretory e repository)*
- **git add .**: *Coloca todos arquivo na área de Sttaging(estado entre working diretory e repository)*
- **git status**: *Verifica o estado dos arquivos/diretórios*
- **git commit -m "[primeiroCommit]"**: *Comando que faz de fato o commit do arquivo*
- **git branch -M "main"**: *para alterar o nome da branch principal de master para main(boa prática)*
- **git remote add origin [link do repositório]**: *Para passar o commit do meu repositório local (da minha máquina) para um repositório na plataforma do Github*
- **git push -u origin main**: *Empurrar o Commit de fato pro repositório*
- **git pull**: *puxa todas as alterações feitas no repositório do Github para o seu repositório local*
- **git clone ssh://git@github.com/[username]/[repository-name].git**: *Cria uma cópia local de um repositório remoto*
- **git rm [nomeArquivo]**: *Remove o arquivo/pasta nomeado*
- **git log**: *Visualizar histórico*
- **git log --stat**: *Visuliza histórico de forma mais completa*

**ME FALTA ENTENDER BRANCH E MERGE (E SEUS COMANDOS)**
