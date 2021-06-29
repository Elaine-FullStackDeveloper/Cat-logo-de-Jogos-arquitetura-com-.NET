# Catalogo de Jogos arquitetura com .NET

Construir uma arquitetura base para uma aplicação .net do zero.

Para instalar o Microsoft .NET Core SDK no Ubuntu e ainda poder receber automaticamente as futuras atualizações dele, você deve fazer o seguinte:

Passo 1. Abra um terminal (use as teclas CTRL + ALT + T);
Passo 2. Se você estiver usando o Ubuntu 16.04, use os comandos abaixo para baixar a chave do repositório do programa e adicionar ele no sistema e ativar o repositório universe;

wget -q https://packages.microsoft.com/config/ubuntu/16.04/packages-microsoft-prod.deb
sudo dpkg -i packages-microsoft-prod.deb
sudo add-apt-repository universe
sudo apt-get update
sudo apt-get install apt-transport-https
sudo apt-get install dotnet-sdk-5.0

Criar a pasta catalogo-de-jogos
Abrir o terminal dentro da pasta criada

Criando o projeto web:

dotnet new webapi -n Api-catalogo-de-jogos
dotnet build

Para executar, digite no terminal o comando  :  dotnet run

Para abrir no navegador acesse o link: https://localhost:5001/swagger/index.html 
 


