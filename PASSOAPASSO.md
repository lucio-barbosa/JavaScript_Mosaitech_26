# MANUAL DO ESTUDANTE
## Como utilizar o projeto JavaScript.Mosaitech_26

**MOSAITECH – Conectando pessoas, negócios e tecnologia.**

### 1. Conhecendo o projeto

O JavaScript.Mosaitech_26 é um ambiente de aprendizagem desenvolvido para ajudar estudantes a compreender os fundamentos da programação JavaScript e sua aplicação em páginas web.

Neste projeto, você encontrará exemplos práticos de:

- Operadores matemáticos e lógicos.
- Manipulação do DOM.
- Eventos JavaScript.
- Seleção de elementos HTML.
- Desenvolvimento de uma calculadora.
- Estrutura de páginas HTML.

### 2. Ferramentas necessárias

Antes de começar, instale os seguintes programas:

**1. Visual Studio Code (VS Code)**

É o editor de código onde você poderá visualizar, escrever e modificar os arquivos do projeto.

Site: https://code.visualstudio.com/

**2. Google Chrome ou Microsoft Edge**

São navegadores utilizados para executar e testar os arquivos HTML e JavaScript.

- Google Chrome: https://www.google.com/chrome/
- Microsoft Edge: https://www.microsoft.com/edge/

**3. GitHub Desktop (opcional)**

Permite baixar projetos do GitHub, acompanhar alterações e publicar seus próprios códigos.

Site: https://desktop.github.com/

**4. Extensão Live Server (recomendada)**

É uma extensão do VS Code que permite executar páginas HTML em um servidor local e atualizar o navegador automaticamente quando você salva alterações.

### 3. Como abrir o projeto

**PASSO 1 – Baixar o projeto**

Acesse o repositório JavaScript.Mosaitech_26 no GitHub.

Clique no botão verde `Code` e depois em `Download ZIP`.

Extraia o arquivo ZIP para uma pasta do seu computador.

**PASSO 2 – Abrir o VS Code**

1. Abra o Visual Studio Code.
2. Clique em `File` (Arquivo).
3. Selecione `Open Folder` (Abrir Pasta).
4. Localize a pasta `JavaScript.Mosaitech_26`.
5. Clique em Selecionar Pasta.

Pronto! Os arquivos do projeto aparecerão no painel Explorer, à esquerda.

**PASSO 3 – Instalar o Live Server**

1. No VS Code, clique no ícone Extensions.
2. Digite `Live Server` na pesquisa.
3. Localize a extensão Live Server, de Ritwick Dey.
4. Clique em Install.
5. Aguarde a instalação.

**PASSO 4 – Executar uma página**

1. No painel Explorer, localize o arquivo `calculadora.html`.
2. Clique com o botão direito sobre ele.
3. Selecione `Open with Live Server`.
4. O navegador será aberto automaticamente.
5. A página será exibida para você interagir.

Você também pode executar outros arquivos HTML da mesma maneira.

### 4. Conhecendo cada arquivo do projeto

**1. calculadora.html**

Finalidade: apresentar uma calculadora desenvolvida com HTML e JavaScript.

O estudante pode:
- Visualizar os campos e botões.
- Digitar números.
- Realizar operações matemáticas.
- Observar como o JavaScript processa os dados.
- Modificar o código e criar novas funcionalidades.

**2. eventosdom1.html**

Finalidade: estudar os eventos do DOM.

O estudante pode:
- Clicar em botões.
- Observar as respostas da página.
- Modificar os eventos.
- Experimentar interações com o usuário.

**3. eventosdom2.html**

Finalidade: aprofundar o aprendizado sobre eventos JavaScript.

O estudante deve observar como os eventos permitem que uma página responda às ações do usuário, como cliques, movimentos do mouse e alterações de campos.

**4. exdom.html**

Finalidade: praticar a manipulação do Document Object Model (DOM).

O estudante pode:
- Selecionar elementos HTML.
- Modificar textos.
- Alterar cores.
- Modificar conteúdos da página.
- Criar interações usando JavaScript.

**5. operadores.js**

Finalidade: estudar os operadores da linguagem JavaScript.

Entre os conteúdos que podem ser trabalhados estão:

- Operadores aritméticos.
- Operadores de atribuição.
- Operadores relacionais.
- Operadores lógicos.
- Operadores de incremento e decremento.

Para executar esse arquivo diretamente no terminal, é necessário ter o Node.js instalado.

Abra o terminal do VS Code e digite:

`node operadores.js`

**6. Pasta image**

Finalidade: armazenar imagens utilizadas pelo projeto.

Você encontrará:
- `arvore_dom.png`: representação visual da árvore DOM.
- `logo-mosaitech.png`: identidade visual da MOSAITECH.
- `logomosaitech.html`: página HTML relacionada à apresentação da logomarca.
- `mosaitech-logo-header.png`: imagem utilizada na identidade visual do projeto.

Não exclua essas imagens sem verificar se algum arquivo HTML depende delas.

**7. README.md**

É o arquivo de documentação do projeto.

Apresenta informações sobre o projeto, suas funcionalidades, tecnologias e instruções de utilização.

**8. .gitignore**

É o arquivo que determina quais arquivos e pastas devem ser ignorados pelo Git.

### 5. Como utilizar as ferramentas do VS Code

**EXPLORER**

É o painel que apresenta os arquivos e as pastas do projeto.

Utilize para:
- Abrir arquivos.
- Criar pastas.
- Criar novos arquivos.
- Organizar o projeto.

**EDITOR DE CÓDIGO**

É a área central onde você escreve e modifica os códigos.

Você poderá trabalhar com HTML e JavaScript.

**TERMINAL**

É a ferramenta que permite executar comandos diretamente no VS Code.

Exemplo:

`node operadores.js`

**EXTENSIONS**

Permite instalar extensões para melhorar seu ambiente de desenvolvimento.

Exemplo: Live Server.

**SOURCE CONTROL**

É a ferramenta integrada ao VS Code para acompanhar alterações no Git e trabalhar com repositórios.

### 6. Como utilizar o navegador para estudar

Depois de executar uma página, você pode utilizar as ferramentas de desenvolvedor do navegador.

No Google Chrome:

1. Abra a página do projeto.
2. Pressione F12.
3. Clique na aba Console.
4. Observe as mensagens e possíveis erros do JavaScript.

**Console**

Permite visualizar mensagens, resultados e erros.

Exemplo:

`console.log("Olá, estudante!");`

**Elements**

Permite visualizar a estrutura HTML e CSS da página.

**Sources**

Permite examinar os arquivos e acompanhar a execução do JavaScript com ferramentas de depuração.

### 7. Como praticar

Recomendamos seguir esta sequência:

1. Abra `operadores.js` e estude os operadores.
2. Abra `exdom.html` e compreenda a estrutura DOM.
3. Estude `eventosdom1.html`.
4. Avance para `eventosdom2.html`.
5. Execute `calculadora.html` e experimente suas funcionalidades.
6. Modifique os códigos e crie suas próprias soluções.

### 8. Desafio do estudante

Após estudar os arquivos, tente desenvolver:

- Uma calculadora com novas operações.
- Uma página com botão para mudar a cor de fundo.
- Um formulário que receba o nome do usuário.
- Uma página que exiba uma mensagem ao clicar em um botão.
- Uma lista de tarefas interativa.

### 9. Boas práticas

- Nunca tenha medo de experimentar.
- Faça uma cópia antes de modificar um arquivo importante.
- Salve suas alterações com frequência.
- Leia as mensagens de erro no Console.
- Utilize comentários para documentar seus códigos.
- Pratique diariamente.
- Publique seus projetos no GitHub para construir seu portfólio.

### 10. Mensagem final

Programar é aprender a resolver problemas por meio da lógica, da criatividade e da tecnologia.

Não basta apenas copiar códigos: é necessário compreender, experimentar, errar, corrigir e desenvolver suas próprias soluções.

**MOSAITECH – Conectando pessoas, negócios e tecnologia.**

*Aprenda hoje. Desenvolva amanhã. Transforme o futuro.*