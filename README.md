
# DIO Resumo GIT e GIThub

Repositorios para armazenar resumoes do curso DIO de GIT e GITHUB [Digital Inovation One] (https://www.dio.me/)

## Anotações feitas 

 Git e Github 

$ cat .git-credentials // Ver a credencial Criada

$ cat .gitconfig // Ver Todas as conf

$ git config --global --show-origin credential.helper// Mostra o Token Criado


$ git clone https://github.com/GabrielTavaresVale/Hello-World.git  //Clona O Repositorio


$ git config init.defaultBranch  //Mostra o Nome do Principal Branch

$ git config --global user.email "gabrielvaletavares@gmail.com" //Aletracao de  dados


SSH

$ ls -al ~/.ssh// Verifica se ha chave SSH


ssh-keygen -t ed25519 -C "your_email@example.com"// Cria uma nova Chave SSH 

Apos isso Irene


$ eval "$(ssh-agent -s)" // Adiciona uma Chave SSH ao Agente

ssh-add// Adiciona Chave Privada ao SHH Agente

~/.ssh //Diretorio onde ficam as chaves  ssh no sistema

ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAICwpI1DEt694m9rprx9xA4AxoCFgs/y4ZPHRdCF6nCMf gabrielvaletavares@gmail.com// Copira e Jogar no GITHUB para criar a ssh chave

$ git clone git@github.com:GabrielTavaresVale/Hello-World.git //Clonar Repositorio SSH
-------
Criando e Clonando Repositorios

git init// Tranforma pasta em repositorio git

git remote -v //ver se esta conectado ao repositorio remoto

$ git remote add origin https://github.com/GabrielTavaresVale/Lepo-Local.git// Adciona repositorio local ao remoto


