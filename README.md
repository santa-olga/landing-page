# landing-page
:books: Uma página HTML para divulgação de projetos de extensão do IFMS -  campus Nova Andradina

## :fire: Executando o projeto

### :gear: Configuração

1. Instalação do Git
Para que seja possível utilizar os comandos de versionamento é necessário fazer o download e instalação do programa Git, diposvível **[nesse link](https://git-scm.com/)**.

2. Com o Git instalado, se faz necessário clonar o repositório do projeto no seu computador por meio do comando:
```
git clone https://github.com/santa-olga/landing-page.git
```
### :zap: Execução

Com o projeto clonado basta executar o arquivo `ìndex.html` para visualização do site.

### :rocket: Publicando alterações feitas localmente

1. Com o projeto clonado se faz necessário navegar até a pasta raiz do projeto e reinicializar os serviços git por meio do comando:
```
git init
```
2. Após reinicializar os serviços, se faz necesssário adicionar todos os arquivos e ditretórios locais ao projeto remoto por meio do comando:
```
git add .
```
3. Após adicionar os arquivos, se faz necesssário commitar as alterações feitas localmente por meio do comando:
```
git commit -m "Descrição da mudança efetuada"
```
Obs: não esqueça de adicionar uma descrição sucinta das mudanças efetuadas.

4. Após commitar as modificações é ncessário enviar arquivos/diretórios para o repositório remoto por meio do comando:
```
git push origin develop
```
Também é possível publicar as alterações por meio do comando:
```
git push
```

### :bug: Atualizar o projeto local com modificações remotas
Para atualizar os arquivos basta executar o comando:
```
git pull
```
