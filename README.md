# Projeto Luma

## Descrição do projeto
Este repositório contém o teste final para o site: https://magento.softwaretestingboard.com/, com o objetivo de criar um teste automatizado utilizando o mecanismo de busca do site para encontrar "shirt" (camisa), adicionar o item ao carrinho e realizar o checkout. O repositório também inclui testes de outros cenários, como buscar por "shirt" e seguir o mesmo processo com o último item da busca. Além disso, testes envolvendo cadastro, login e fechamento da compra no carrinho, bem como a adição de um item aleatório do catálogo masculino.

## Tecnologias utilizadas
Foram utilizadas as ferramentas de automação Cypress v14.0 com Node.js, o Visual Studio Code v1.96.4 para a edição de código em JavaScript e a ferramenta de versionamento Git v2.47.1.windows.2.

### Como instalar e usar
**Clone o repositório**
$ git clone https://github.com/SuhMaria/Projeto-Luma.git

Mude para a branch do teste em questão:
$ git checkout Teste-Carrinho

Em seguida atualize a branch com o comando:
$ git pull

1. **Antes de instalar o Cypress, certifique-se de ter o seguinte:**
Node.js instalado

Baixe o Node.js no site oficial: https://nodejs.org/pt

Durante a instalação, escolha a versão LTS (Long Term Support

Verifique se o Node.js foi instalado corretamente:
node --version

Deve aparecer a versão do Node.js.

Verifique também o npm (gerenciador de pacotes do Node.js):
npm --version

Um editor de código
Recomendo usar o Visual Studio Code (VSCode).
Baixe e instale:
https://code.visualstudio.com/

2. **Instalar o Cypress**
No mesmo terminal, instale o Cypress com o comando:
npm install cypress --save-dev

Isso instalará o Cypress como uma dependência de desenvolvimento.
Verifique se foi instalado corretamente:
npx cypress verify

Deve aparecer uma mensagem confirmando que o Cypress foi instalado.

3. **Abrir o Cypress**
   Para abrir o Cypress pela primeira vez, entre na pasta raiz do projeto clonado e no terminal digite :
   cd caminho_do_projeto_clonado_na_sua_máquina
   
   Após isso, digite:
   npx cypress open

   Clicar em:
   E2E Testing

   Escolha o browser de sua navegação (dê preferência pelo Chrome).
