# dotnet-core-template-project
projeto para criação de template  de projeto



# Template
Modelo  para uso com a funcionalidade dotnet da CLI do .NET

# Como instalar o modelo

1. Você deve ter a versão mais recente das ferramentas dotnet. Isso vem com o Visual Studio 2017 ou em https://dot.net.
2. Execute `dotnet new --install" Template :: * "` para instalar o modelo do projeto.
3. Execute `dotnet new graphql-project --help` para ver como selecionar os recursos do projeto.
4. Execute `dotnew new graphql-project --name" MeuProjeto "` junto com outras opções personalizadas para criar um projeto a partir do modelo.


# Executando o projeto após ser gerado

Depois de criar um novo projeto usando o `dotnet new`, você deve restaurar os pacotes antes de usar o` dotnet run`.

`` ``
dotnet new graphql-project --name "MeuProjeto"
restauração dotnet
dotnet run
`` ``

![alt text](https://github.com/leandro0404/dotnet-core-template-project/blob/master/imgs/01.png)

![alt text](https://github.com/leandro0404/dotnet-core-template-project/blob/master/imgs/02.png)

# Informações gerais sobre a instalação de modelo

O modelo podem ser instalados a partir de pacotes em qualquer feed do NuGet, diretórios no sistema de arquivos ou nos arquivos do tipo ZIP (zip, nupkg, vsix etc.)
Para instalar um novo modelo, use o comando:

    dotnet new -i {o caminho para a pasta que contém os modelo}

# Comandos básicos
## Mostrando ajuda

    dotnet new --help
    dotnet new -h
    dotnet new

## Listando modelos

    dotnet new --list
    dotnet new -l
    dotnet new mvc -l Lista todos os modelos que contêm o texto "mvc"

## Criação de modelo

    dotnet new MeuTemplate --name MeuProjeto --put src --ParameterName1 Value1 --ParameterName2 Value2 ... --ParameterNameN ValueN ...
    
# Diretório com arquivos criados

![alt text](https://github.com/leandro0404/dotnet-core-template-project/blob/master/imgs/03.png)
    
# Solução Criada com o template
![alt text](https://github.com/leandro0404/dotnet-core-template-project/blob/master/imgs/04.png)
