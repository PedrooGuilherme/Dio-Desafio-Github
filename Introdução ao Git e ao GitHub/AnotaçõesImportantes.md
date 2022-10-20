# Git e GitHub

## Git 
O Git é um sistema de controle de versão distribuído e amplamente adotado. É um software livre e muito utilizado no desenvolvimento de software onde diversas pessoas estão contribuindo simultaneamente, podendo criar e editar arquivo.

## GitHub
GitHub é uma plataforma para gerenciar seu código e criar um ambiente de colaboração entre devs, utilizando o Git como sistema de controle. É como se fosse uma rede social, só que de códigos, onde seus desenvolvedores podem disponibilizá-los para outras pessoas verem.

#### Benefícios:
 - Controle de Versão
 - Armazenamento em Nuvem
 - Trabalho em equipe
 - Melhorar Código
 - Reconhecimento

### GUI X CLI
   
- GUI : Possui uma Interface gráfica e se concentra em permitir que os usuários façam alterações no seu repositório fazendo novos commit, melhorando os já existentes, criando ramificações, realizando mesclagens locais e buscando/impulsionando para os repositórios remotos.

- CLI : É um Command-Line,ou seja,não possui uma interface gráfica, sua forma de interação com o usuário é por meio de linha de comando,Leva pull requests, problemas, GitHub Actions e outras funcionalidades de GitHub ao seu terminal para que você possa fazer todo o seu trabalho em um só lugar


### Alguns Comandos Básicos do Terminal:

**Linux**   | **Windows**| **Funcionalidades**
:---------: | :--------: | :------:
ls |dir|Lista arquivos do diretório/pasta
cd .. |cd ..|Retrocede 1 nível de pasta(Pasta anterior)
cd/|cd/|Entra em um diretório ou pasta específica.
cls |Crt+L ou clear|Limpa terminal
TAB|TAB|Autocompleta pastas ao digitar comandos
 mkdir|mkdir|Criar Pasta/Diretório
 echo > NomedoArquivo.extensão|echo > NomedoArquivo.extensão|Cria um arquivo
 rmdir|rmdir|Apaga todos os arquivos do diretório/pasta

## Introdução ao Git:
### Instalação do Git

[Clique aqui para acessar o site](https://git-scm.com/)

### 👨‍🏫 Entendendo o Git
   A sigla SHA significa Secure Hash Algorithm(Algoritmo de HAshe Seguro),é um conjunto de funções hash criptográficas projetadas pela NSA.Trata-se de uma forma curta de apresentar um arquivo por meio de um cifra criptofrafada. A encriptação gera um conjunto de caracteres identificador de 40 dígitos

### Objetos do Git
 - Blobs : Possuem metadados
 - Trees : Armazenam e apontam para tipos de blobs diferentes. Além disso, é responsável por montar toda a estrutura de onde estão localizados os arquivos do git.Relação mútua com o blob.
 - Commit: Junta todos os elementos,são utilizados para auxiliar o controle do versionamento e as modificações de sistemas.Objetos do git que dão significado às alterações,os quais carregam uma mensagem de texto justamente com outros dados;

![Objetos do Git ](./Anota%C3%A7%C3%B5esImportantes.md)

*Se houver modificação no arquivo,o commit e as trees atreladas a ele terão a cifra do do SHA1 modificado.
