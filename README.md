# QA-Test_K-bum
Teste de QA
Automação de testes web utilizando o Robot Framework com Selenium, teste no site do Kabum passando por três cenários: Acesso a página de login, Pesquisa de um Produto e Adicionar um produto no carrinho.
Perguntas a serem respondidas:

1 - Defina os 3 tipos de testes citados abaixo.
- Teste unitário
o software é visto como módulos separados e o objetivo deste Teste é explorar a menor unidade do projeto, provocando falhas ocasionadas por defeitos de lógica e de implementação em cada módulo. Nessa técnica de Teste, o foco é verificar os métodos dos objetos ou pequeno trechos de códigos.
- Teste de Integração
Esse nível de Teste de Software visa a provocar falhas associadas às interfaces entre os módulos do software quando eles são integrados para compor a estrutura do software.
- Teste de UI
aqui, o software é verificado para encontrar falhas por meio da sua própria utilização. Nesta técnica, os Testes são realizados no mesmo ambiente e com as mesmas condições em que o software será executado no dia a dia. O principal objetivo deste Teste é verificar se o software realmente satisfaz os requisitos apresentados pelo cliente.

2 - Analise e descreva qual a importância da qualidade de software hoje. E quais os riscos sem ela dentro de um e-commerce.
Teste de Software é uma atividade realizada no Processo de Desenvolvimento de 
Software visando a verificar se o comportamento do software corresponde ao esperado. 
O Teste de Software visa a encontrar falhas no software desenvolvido para que elas 
sejam corrigidas antes de entregar o software ao cliente (PRESSMAN, 2005). 
A atividade de Teste visa a aumentar a confiança do produto, expondo suas falhas 
para que a equipe de desenvolvimento possa corrigi-las. 
Testar um software é realizar um processo investigativo visando a descobrir erros que 
apareçam para o cliente no dia a dia da utilização do software. 
No processo de Testes de um Software, é vital que a Equipe entenda perfeitamente 
a diferença de defeito, erro e falhas. Para muitos, esses conceitos são iguais, entretanto, há uma boa diferença entre eles.
Sem esta atividade dentro de um e-commerce, estamos fadados ao fracasso, haja visto que hoje o consumidor, após a pandemia COVID-19, habituou-se com o processo de compra pela Internet. Se houver falhas no processo do e-commerce, haverá além dos prejuizos financeiros, prejuizos de valor a marca e aos produtos, consequentemente acarretará em descrédito e desvalorização do e-commerce.

3 - Passe o método “Passo a Passo”, para o método escrito na linguagem Gherkin:
Cenário - Busca por produto
1ª - Abrir a home do site
2ª - Digitar “Processador i9” na busca e clicar em pesquisar.
3ª - Validar se existe produto na listagem

Dado que estou na home page do Kabum.com.br
Quando pesquisar pelo produto “Processador i9”
Então um produto da linha "Processador i9" deve ser mostrado na página

4 - Descreva a respeito de TDD(Test Driven Development) e BDD(Behavior Driven
Development) e suas diferenças.
TDD
Test Driven Development(TDD) ou, em português, Desenvolvimento Dirigido por Testes é uma técnica de desenvolvimento de software que se baseia em um ciclo curto de repetições. Primeiramente o desenvolvedor escreve um caso de teste automatizado que define uma melhoria desejada ou uma nova funcionalidade. Então, é produzido código que possa ser validado pelo teste. Posteriormente este código será refatorado para colocá-lo sob padrões aceitáveis.
A grande vantagem deste processo é garantir uma cobertura de testes para 100% do código, já que nada é desenvolvido sem que um teste exista antes.
Além disso, ajuda o desenvolvedor a pensar melhor sobre as implementações, em como testar e garantir que algo realmente irá funcionar, a revisar o trabalho recém feito para torná-lo ainda melhor e assim por diante.

BDD
BDD é técnica de desenvolvimento ágil que visa integrar regras de negócios com linguagem de programação, focando o comportamento do software.
Vantagens:
Melhor desenvolvimento
Deixamos o desenvolvedor entender do ponto de vista do usuário o que é esperado da funcionalidade, dando liberdade para ele pensar na melhor solução técnica ao invés de sugerir uma implementação que pode não ser a ideal ou não resultar no comportamento esperado.
Maior interação entre as áreas
Pessoas que não são da área técnica podem participar e contribuir ativamente na descrição das demandas, já que não é preciso entender detalhes de programação, mas sim o comportamento esperado do ponto de vista de outras áreas como negócio, marketing, usabilidade, experiência do usuário, etc.
Qual é a diferença entre TDD e BDD?
O TDD busca garantir a qualidade do código, sempre pensando em 100% de cobertura de testes, melhorar o que acabou de ser feito e nunca escrever uma linha de código sem antes pensar em como garantir que aquilo irá funcionar.
Já o BDD trabalha para definir como uma demanda chega ao desenvolvedor, integrar diferentes áreas da empresa e pensar a partir do ponto de vista do comportamento esperado de uma funcionalidade pelo usuário. Por consequência, ele acaba influenciando em como os testes são planejados e escritos.
Dizemos então que TDD não vai contra o BDD, podemos aplicar ambos os métodos em conjunto ou apenas um deles.

5 - O que são Page Objects e qual sua vantagem?
PageObject é um padrão de design que ajuda a aprimorar a manutenção de testes e reduzir a duplicação de código, também pode ser utilizado para descrever e documentar o fluxo de uma aplicação.
Vantagens:
Eles mantêm todos os seletores de elementos da página em um só lugar;
Eles padronizam como os testes interagem com a página;

6 - Faça uma teste com Robot Framework, utilizando boas práticas de automação com a
Library Selenium dos seguintes cenários:
- Fazer validação de um usuário inválido no https://kabum.com.br.
- Fazer a busca de iphone no https://kabum.com.br. E validar retorno de produtos.
- Selecione uma categoria no menu de “Departamento” e adicione um produto no
carrinho (Não precisa estar logado). E valide se o produto está no carrinho.
OBS: Subir no Github e compartilhar o link do repositório.

*** Primeiro foi instalado o Python, após o RobotFramework e o Seleniumlibrary. Efetuado o download do Chrome Driver e adicionado a pasta do Windows.

*** Github

echo "# QA-Test_K-bum" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin git@github.com:prof-pccarvalho/QA-Test_K-bum.git

git push -u origin main

# O cenário da escolha de departamento está apresentando erro no locator xpath. Estou entregando este cenário no formato de escrita Gherkin (BDD). Porem os locator não estão fncionado e estou no limite do prazo.Como não consegui negociar prazo, vai a tentativa e esforço.
