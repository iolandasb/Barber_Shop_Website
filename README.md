# Barber Shop Website
Website creation using HTML and CSS concepts.

# Conceitos e Funcionalidades

•	strong: negrito. Tem fechamento.

•	em: itálico. Tem fechamento.

•	h: título. Tem 6 níveis (h1, h1, etc). Tem fechamento.

•	p: parágrafo. Tem fechamento.

•	!DOCTYPE html: indica qual a última versão do HTML que está sendo usada. É uma tag de informação. Não tem fechamento.

•	html: tag estrutural e de conteúdo que vai renderizar o html. Tem fechamento.

•	Indentação: forma de organização de um código em HTML.

•	lang="pt-br": informa que o conteúdo da página está em português (brasileiro).

•	title: informa o nome da página. É possível visualizar pelo nome da aba do navegador.

•	head: contém as informações que são passadas ao navegador. As informações ficam aqui.

•	body: contém as informações que se quer exibir na página. O conteúdo fica aqui.

•	font-size: é o tamanho da fonte. É medido em pixel.

•	link: faz a ligação de um arquivo para o outro.

•	rel: indica o relacionamento de algo. Se usarmos por exemplo “<link rel=>” após o “=” deverá ser indicado o arquivo que será linkado.

•	stylesheet: folha de estilo. Necessário para linkar um arquivo a outro.

•	href: endereço de referência. També é necessário para linkar um arquivo a outro.

•	background: define tudo que será o fundo do elemento.

•	#CCCCCC: cinza na linguagem CSS. Mas a cor pode também ser chamada de outras formas, sendo essa apenas uma delas.

•	Alfabeto binário: 0 e 1.

•	Alfabeto (ou dicionário) hexadecimal: 0123456789ABCDEF (literalmente).

•	RGB: red green blue.

•	Cores: para se montar uma cor, se usa o dicionário hexadecimal com as cores básicas RGB. Com isso se utiliza o código #_ _ _ _ _ _, onde se coloca os códigos do vermelho nos 2 primeiros espaços (representado aqui por “_”), do verde nos 2 seguintes e do azul nos 2 seguintes.
  -	0 = ausência de cor.
  -	F = máximo de cor.
  -	Exemplo – preto (ausência de cor): #000000. 
  -	Exemplo – branco (máximo de cor): #FFFFFF.
  -	Exemplo – vermelho #FF0000.
  -	As cores também podem ser representadas por red, green, blue, etc.

•	Dicionário RGB: 0, 1, 2, 3, 4, 5 ...255. Ele tem 255 níveis de representação de cada cor. Aqui, o “0” também é a ausência de cor e 255 é o máximo. Aqui se pode representar a cor da seguinte forma (exemplo de branco): rgb(255,255,255).

•	TAG no CSS: toda vez que se quer referenciar uma TAG no CSS, se usa a TAG.

•	Identificador (id): toda vez que se quer referenciar um identificador no CSS, se usa a “#”. Ele serve para dar um nome a uma TAG e assim identifica-la.

•	img: serve para chamar uma imagem.

•	src: source. Serve para indicar a fonte de algo. Por exemplo, em <img src=> ajuda a chamar a imagem indicando de onde ela saiu. Após o “=” deverá ser indicado o arquivo que será linkado.

•	Dimensões: tem quatro características – largura, altura, espaçamento interno e espaçamento externo do elemento.
  - height: altura. É medida em pixels.
  - width: largura. É medida em “%”.
  - border: borda. É medida em pixels, pode ser adicionada cor.
  - padding: é o espaçamento interno. Ajuda a fazer um elemento se comportar melhor em um espaço. Ex: quando você tem uma borda e não quer que o texto fique colado à borda se utiliza o “padding” para criar esse espaço. Pode-se escolher aonde esse espaçamento irá ocorrer, como por exemplo com o uso do “padding-top”, onde o espaçamento existirá apenas no topo.
  - margin: é o espaçamento externo. Ajuda a fazer um elemento se comportar melhor em um espaço. Ex: quando você tem uma borda e não quer que ela fique colada à outros elementos externos (ex: imagem) se utiliza o “margin” para criar esse espaço. Pode-se escolher aonde esse espaçamento irá ocorrer, como por exemplo com o uso do “margin-left”, onde o espaçamento existirá apenas na esquerda.

•	ul: “unordered lista” - listas não ordenadas: são listas em que a ordem não é relevante.

•	ol: “ordered lista” - listas ordenadas: são listas em que a ordem é relevante.

•	li: “list item”. É necessário para indicar que o item faz parte de uma lista.

•	class: Classes. Servem no CSS para marcar itens e posteriormente colocar um estilo em cada um deles, sendo as classes repetíveis.
o	.:Toda vez que se quer referenciar uma classe no CSS, se usa o “.”.

•	div: divisão. Serve para separar o código em blocos.

•	Comportamento “block”: bloqueia o conteúdo de uma linha. Itens de uma lista fazem isso, porém imagens não, pois estas tem um comportamento “inline”.

•	Comportamento “inline”: não possibilita alterar o espaçamento interno e externo do elemento.

•	Inline-block: comportamento “inline” e “block” ao mesmo tempo. É junção dos dois. Bloqueia os tamanhos de forma fixa, porém o programador que determina estas medidas, podendo definiri largura, espaçamento, etc. Quando existem certos elementos que estão juntos na página (por exemplo, uma lista e uma figura) e se quer que esse comando atue corretamente, é necessário que esses elementos também sejam colocados juntos no código, conforme demonstrado no exemplo abaixo:
  - <img>![image](https://user-images.githubusercontent.com/60974082/113651357-38e18100-9668-11eb-8a25-3bed498013b3.png)</img>

•	display: comando para mostrar.

• vertical-align: ajusta o texto aonde se quer coloca-lo. Exemplo: “vertical-align: top” – o texto ficará na parte de cima.

•	header: comando que informa o que é o cabeçalho da página.

•	a: “ancor”. TAG de conteúdo, tem fechamento. É uma ancora para outra página/site.

•	nav: navegação. Indica que os itens que estão dentro dessa TAG são itens de navegação do site.

•	text-transform: muda algo no texto indicado (ex: para deixar o texto com letras maiúsculas é “uppercase”).

•	uppercase: comando para deixar as letras em maiúscula no navegador.

•	font-weight: muda a fonte do texto (negrito, itálico, etc) de acordo com o indicado (ex: negrito é “bold”).

•	text-decoration: se relaciona com a “decoração do texto”. Ele por padrão vem sublinhado. Se colocarmos “text-decoration: none” esse sublinhado some.

•	reset.css: é um arquivo que foi disponibilizado em aula mas que é comumente usado pelos programadores. Ele serve para “limpar” as configurações pré-definidas do navegador, tirando por exemplo espaços indesejados.

•	position: posicionamento. Os elementos são por padrão estáticos (“static”). Porém é possível alterá-los para relativos (“relative”), característica essa que possui como ponto inicial o ponto em que o elemento estava posicionado originalmente. No entanto, nesse caso é possível mover o elemento, utilizando-se de comandos como “top”, “left”, etc. Importante destacar que o “top” joga o texto para baixo e o “left” para a direita, pois estão sendo adicionados pixels ao ponto inicial. Ex:
  - <img>![image](https://user-images.githubusercontent.com/60974082/113651470-67f7f280-9668-11eb-92a8-8e33b53d7d65.png)</img>

  - absolute: o posicionamento também pode ser absoluto. Nesse caso, o elemento perde o ponto originário dele, o passa a ser determinado pelo programador. Para isso, se usa os mesmos comandos do “relative”, da mesma forma. O posicionamento absoluto é em relação à página, o novo ponto inicial será qualquer ponto que for indicado no navegador.

•	auto: calcula a margem automaticamente. Serve como centralizador.

•	main: o principal, a coisa mais importante. É a principal parte da página. Essa TAG poderia ser substituída pela “div”, por exemplo, porém utilizá-la deixa o código mais legível.

•	footer: é o rodapé da página. Essa TAG poderia ser substituída pela “div”, por exemplo, porém utilizá-la deixa o código mais legível.

•	box-sizing: border-box: o navegador, para determinar o tamanho de uma caixa soma o percentual da largura (“width”) mais os pixels (“padding”). Com esse comando, o navegador entende que a largura será sempre o percentual de largura e que os pixels devem ocorrer apenas dentro da caixa, e não se somar à sua largura.

•	Bordas:
  - solid: sólida (linhas inteiras).
  - dashed: tracejado.
  - dotted: pontilhado.

•	border: esse comando comporta o tamanho, tipo e cor da borda.

•	border-radius: declara o raio de uma borda (com o intuito de transformar um ângulo reto em formato arredondado). O canto que se quer transformar deve ser indicado pelos comandos “top-left”, “bottom-right”, etc. Se não tiver essa determinação, todos os cantos serão arredondados conforme o comando. O tamanho deve ser informado em px. Nesse mesmo comando, podem ser informados 4 tamanhos, que correspondem aos 4 cantos (ou seja, cada canto pode ter um tamanho).

•	Largura: 940 px é a largura padrão da web.

•	hover: é um pseudo-elemento. Comando que identifica quando o mouse está por cima do elemento.

•	active: é um pseudo-elemento. Identifica quando o ouse é clicado.

•	Imagem – CSS: pode-se criar uma imagem apenas no CSS (sem estar no html) a partir de uma imagem salva no computador usando-se url(“”), sendo que dentro das “” deve constar o nome do arquivo. Quando uma imagem é incluída pelo CSS, ela se repete até ocupar toda a extensão da página, ao invés de aumentar a imagem até caber.

•	Unicode: linguagem que tem vários itens e caracteres específicos. Recomendação: https://unicode-table.com. Tem por exemplo o símbolo de copyright. Quando procuramos algum caracter, ele mostra como ele é escrito em diversas linguagens. O mais comum é usar o que consta em “Entidade”.

•	form: TAG de formulário. Detém as entradas de dados do usuário, que é um “input” de informação

•	input: é a colocação de uma informação. Tem sempre um tipo (“type”). Normalmente se coloca um identificador (“id”) em um input, para torna-lo único.

•	label: em um formulário, se usa uma etiqueta para um “input”, que é o “label”. É o texto que será escrito para determinar os campos. É importante manter a relação do “label” com o “input” através de um “for”, principalmente quando existem muitos itens. Ressalta-se que pode ser criado um “input” dentro de um “label”. O exemplo a seguir de “Nome e Sobrenome” é um “label”:
  - <img>![image](https://user-images.githubusercontent.com/60974082/113651536-878f1b00-9668-11eb-8da4-dec022ff8c6c.png)</img>
 
•	textarea: é como um input, mas dá ao usuário a possibilidade de colocar mais de uma linha de texto, um conteúdo completo. É uma TAG de conteúdo, então tem fechamento. Sua caixa de texto pode ser modificada na própria página puxando com o mouse, ou podem serem definidos seus limites de tamanho na programação HTML (por colunas – “cols” e linhas – “rows”).

•	Cols: colunas.

•	Rows: linhas.

•	Radio box: é um “input” com a configuração de serem 3 opções referentes a um único campo. É inserido da seguinte forma (exemplo): 
  - <img>![image](https://user-images.githubusercontent.com/60974082/113651582-a097cc00-9668-11eb-9f33-eac509588e40.png)</img>

•	checkbox: é uma caixa onde se pode dar um check. É inserido da seguinte forma (exemplo):
  - <img>![image](https://user-images.githubusercontent.com/60974082/113651585-a42b5300-9668-11eb-81b6-3329a7853e1d.png)</img>
 
•	TAG x Class x Id: por vezes, comando referentes aos mesmos blocos são dados. Nestes casos, existe uma hierarquia de relevância, ou seja, certos itens que prevalecem sobre outros. E com isso temos que: TAG < Class <Id. No caso abaixo, temos que todos os comandos se referem ao mesmo bloco. Assim temos que p (TAG) < form p (TAG específica) < .teste (Class) < p.teste (Class específica) < #teste (Id):
  - <img>![image](https://user-images.githubusercontent.com/60974082/113651633-bc02d700-9668-11eb-8479-a0d4280e63ce.png)</img>

  - Maior do que todos na verdade é a característica “inline”, pois ela está dentro do elemento, sendo a mais específica. Um exemplo de comando “inline” é o “style” descrito na linha abixo:
  - <img>![image](https://user-images.githubusercontent.com/60974082/113651659-c7ee9900-9668-11eb-80f3-ec0f041271ba.png)</img>
 
  - Quando se quer falar de estilo, usa-se uma classe, e quando se quer falar de comportamento se usa o identificador. Quando o elemento é utilizado no CSS, costuma ser melhor usar uma classe, pois caso algum item necessite ser alterado é mais fácil, uma vez que se pode usar um elemento mais forte (como um “id”) para fazê-lo.

•	select: seletor. Tem fechamento. Guarda dentro dele várias opções.

•	option: opções. Campo de conteúdo que tem fechamento. Cria itens selecionáveis do comando “select”.

•	Celular: o site criado pode se apresentar de forma diferente em um computador e em um celular. Assim, no site http://mobileinputtypes.com/ é possível verificar como a programação do HTML5 ficará em um celular.

•	required: obrigatório. Torna o campo de um “input” obrigatório de ser preenchido.

•	placeholder: sugestão de preenchimento. Ele preenche o espaço de um “input” até que o usuário comece a digitar.

•	checked: marcado. Atua como um placeholder, porém em relação a um radio box (deixa um item específico selecionado).

•	fieldset: é igual a um “<div>”. É referente a um ou mais campos de um assunto específico. Preenchimento dos dados de um cartão ou endereço podem estar dentro de um “fieldset”, por exemplo. Dentro de um “fieldset” não existem parágrafos, pois eles são nomeados de “legend”.

•	legend: são iguais aos parágrafos, porém essa é a denominação específica de parágrafo dentro de um “fieldset”. Atua como o título do grupo.

•	alt: é uma alternativa para uma imagem, facilitando a acessibilidade. Caso não seja possível visualizar a imagem, esse comando a descreve.

•	transition: faz com que a mudança de um item ocorra de forma gradual. Comporta o tempo de transição e o item que se quer alterar. Exemplo:
   - <img>![image](https://user-images.githubusercontent.com/60974082/113651698-da68d280-9668-11eb-81a0-c42b7f01ba09.png)</img>

•	cursor:pointer: transforma a flechinha do mouse em mãozinha, indicando que o elemento é clicável.

•	transform: scale(): transforma todas as características de uma classe, id, etc de forma proporcional. No exemplo abaixo, temos que o comando transforma todos os elementos da classe “enviar” em um tamanho 20% maior (representado pelo 1.2) quando o cursor do mouse passar sobre esse elemento:
   - <img>![image](https://user-images.githubusercontent.com/60974082/113651727-e5bbfe00-9668-11eb-97cf-c99c79ef577e.png)</img>

•	transform: rotate(): rotacional todas as características de uma classe, id, etc. Comporta os graus da rotação. Os comandos relacionados ao “transform” devem constar no mesmo “transform”, pois em caso negativo ele irá realizar apenas o comando do último da sequência de “tranforms”. Exemplo (correto):
   - <img>![image](https://user-images.githubusercontent.com/60974082/113651753-f5d3dd80-9668-11eb-91b1-ca559f2b7084.png)</img>

•	table: tabela. Sequência de linhas e colunas.
  - tr: table row. Linhas.
  - td: células.
  - thead: cabeçalho da tabela.
  - th: célula do cabeçalho.
  - tbody: corpo da tabela.
  - tfoot: rodapé da tabela.
  - colspan=”X”: agrupa células, é um “merge” do excel. No “X” deve ser indicado o número de células que se quer agrupar. Exemplo:
  - <img>![image](https://user-images.githubusercontent.com/60974082/113651797-10a65200-9669-11eb-87eb-cc088e30b58d.png)</img>
 
•	section: tem a mesma função da “div”. Porém, a “div” é apenas para uma separação visual, enquanto que a “section” separa um conteúdo complexo, que semanticamente faz o mesmo sentido (ou seja, é um bloco com o mesmo significado/sentido).

•	em: representa o tamanho da fonte (letra) padrão. Se for colocado, por exemplo, 2em, então a letra terá 2x o tamanho da fonte padrão (que é medida em pixel. Então se a padrão for 15px, essa será 30px).

•	float: é uma forma de diagramação, que possui uma espécie de "sombra" sobre o bloco ou imagem, fazendo com que o texto não entre nessa "sombra". Assim, o texto fica ao redor do bloco ou imagem. Comporta o lado que se quer que a imagem ou bloco fique. Ele afeta totalmente a estrutura da página, e todos os elementos abaixo dele na página são afetados.

•	clear: esse comando limpa a influência o "float" sobre um elemento (classe, identificador, etc), de forma que ele não seja afetado pela sua “sombra”.

•	Fontes: o site https://fonts.google.com/ possui uma lista de fontes preparadas para web (existem fontes que não o são, mas não são adequadas). Lá é possível pegar os códigos HTML e CSS de uma fonte para aplicá-la na página da web.

•	Mapas: no site http://maps.google.com/ é possível selecionar um endereço, clicar no canto esquerdo, clicar em “Compartilhar ou incorporar mapa”, clicar em “Incorporar um mapa” e depois clicar em “Incorporar HTML” e por fim colcar o código no HTML. Isso criará um mapa do lugar na página web.

•	Vídeos: no site http://youtube.com é possível escolher um vídeo, clicar em “Compartilhar” e depois em “Incorporar”, copiar o código e colocar no HTML. Isso trará o vídeo para sua página web.

•	Pseudo-elementos: “:hover”, “:active”, “:visted”, “:required”, etc. São propriedades que servem para marcar melhor os elementos e ter melhor comportamento no site. Eles são criados via CSS, não existem no HTML.

•	line-height: altura da linha. Ela geralmente é proporcional ao tamanho da fonte (1). Mas se colocar um valor maior (ex: 1.5), ela fica maior que o tamanho da fonte.

•	first-child: é um pseudo-elemento. Comando que identifica e atua sobre o primeiro item de uma classe, id, TAG, etc.

•	last-child: é um pseudo-elemento. Comando que identifica e atua sobre o último item de uma classe, id, TAG, etc.

•	nth-child():é um pseudo-elemento. Comando que identifica e atua sobre o item de uma classe, id, TAG, etc, que se coloca dentro do “()” (1, 2, 3, 4, etc). Se dentro do “()” colocarmos por exemplo “2n”, ele irá atuar sobre  todos os itens pares da lista.

•	linear-gradient(x, y): comando que faz um gradiente com as cores que forem colocadas em “x” e “y”. Podem ser inseridas quantas cores quiser. Ademais, na primeira posição (aqui no caso “x”), pode ser colocada a inclinação do gradiente em “deg” (degrees). Exemplo:
  - <img>![image](https://user-images.githubusercontent.com/60974082/113651850-26b41280-9669-11eb-8880-b2958bddab87.png)</img>
 
  - Ainda, pode-se escolher o tamanho que uma cor ocupa no gradiente, por exemplo:
  - <img>![image](https://user-images.githubusercontent.com/60974082/113651885-33386b00-9669-11eb-99f2-ed6ab23fcc70.png)</img>

•	radius-gradient(x, y): funciona igual o “linear-gradient”, porém forma um círculo de gradiente e não tem posição inicial. No resto funciona igual.

•	first-letter: é um pseudo-elemento. Comando que identifica e atua sobre a primeira letra de uma classe, id, TAG, etc.

•	first-line: é um pseudo-elemento. Comando que identifica e atua sobre a primeira linha de uma classe, id, TAG, etc.

•	before e after: são pseudo-elementos. Criam um espaço onde o CSS pode ser usado antes do elemento. São apenas conteúdos de exibição. Eles comportam o comando “content”, e aplicam na classe, id, TAG, etc, o que for inserido dentro desse comando, conforme descrito no exemplo abaixo:
  - <img>![image](https://user-images.githubusercontent.com/60974082/113651947-4ea37600-9669-11eb-84a4-a6a404b278c8.png)</img>

•	Seletores avançados: formas mais específicas de fazer seleção de elementos ainda mais rebuscadas/granulares.
  - >: demonstra que o elemento que vem depois do “>” é uma filha direta do que vem antes do “>”. Assim, não são modificados outros elementos que não os filhos diretos. Exemplo:
  - <img>![image](https://user-images.githubusercontent.com/60974082/113652065-7c88ba80-9669-11eb-9659-0d6f369e1300.png)</img>
 
  - +: demonstra que o elemento que vem depois do “+” é um irmão do que vem antes do “+”. Assim, não são modificados outros elementos que não o irmão direto (que vem logo após). Exemplo:
  - <img>![image](https://user-images.githubusercontent.com/60974082/113652071-801c4180-9669-11eb-9545-50fb30d07069.png)</img>
 
  - ~: demonstra que os elementos que vem depois do “~” são irmãos do que vem antes do “~”. Assim, não são modificados outros elementos que não os irmãos diretos (que vem logo após. Nesse caso, são todos os elementos irmãos que vem depois). Exemplo:
  - <img>![image](https://user-images.githubusercontent.com/60974082/113652077-83afc880-9669-11eb-8088-69f4bd3d5cda.png)</img>
 
  - not(x): comando que aplica uma alteração a todos os filhos/irmãos diretos de uma classe, id, TAG, etc, menos a que se colocar no lugar do “x”. Exemplo:
  - <img>![image](https://user-images.githubusercontent.com/60974082/113652098-8a3e4000-9669-11eb-8751-ec34f4c199b4.png)</img> 

•	calc(): faz cálculos dentro do CSS que pode ser entre porcentagens e pixels, por exemplo. Comporta vários cálculos dentro do “()”. Isso facilita para adequação de imagens (por exemplo) no celular em comparação ao computador. Exemplo:
  - <img>![image](https://user-images.githubusercontent.com/60974082/113652128-988c5c00-9669-11eb-85f3-8e2821b980d4.png)</img> 

•	opacity: confere opacidade ao elemento. Vai de 1 (sem opacidade) a 0 (máximo de opacidade).

•	rgba(x, y, z, w): o “rgb” é uma propriedade de cor, onde o código de “x” equivale ao vermelho, “y” ao verde e “b” ao azul. O “a” é a opacidade da letra, que como descrito no caso acima vai de 1 (sem opacidade) a 0 (máximo de opacidade).

•	box-shadow: x y blur borda # ...: o comando cria uma “sombra” sobre um elemento. Comporta um eixo “x” (pixels), “y” (pixels), um “blur” (pixels) (que é o “espalhamento” da sombra, a sombra possui uma quantidade de pixels que vai do sólido ao transparente), um “borda” (pixels) (que é a intensidade da borda, a partir do eixo da sombra, o quão mais ela vai se espalhar, a sombra expande) e uma cor (“#”). O “...” significa que podem ser acrescentadas mais sombras nesse mesmo comando. Exemplo:
  - <img>![image](https://user-images.githubusercontent.com/60974082/113652173-a9d56880-9669-11eb-8811-3fc46d91e925.png)</img> 

  - Inset: comando que vem após o “box-shadow” que cria uma sombra interna. Comporta o eixo “x”, “y”, espaçamento (pixels) e a cor. Os eixos e espaçamentos não podem ter números negativos.

•	text-shadow: funciona como o “box-shadow”, porém para textos.

•	Versão mobile: a maioria dos acessos da internet são por meio do mobile. Por isso é importante que a página esteja adaptada para o uso ao celular. Quando clicamos no “F12” na página da web, existe o elemento demonstrado abaixo, que ao ser clicado mostra como o site aparece na versão mobile:
  - <img>![image](https://user-images.githubusercontent.com/60974082/113652255-d4272600-9669-11eb-9d1e-ed75bf68664c.png)
</img> 
 
  - É necessário entender os pixels da tela (DCI – quantidade de pixels por polegada), quantos  pixels existem na tela. Para saber isso, se usa a TAG “<meta name=“viewport” content=”width=device-width”>”. Com esse comando, é possível entender e adaptar a página para celular.
Ainda, quando visualizamos a página com o “F12”, consta na parte de cima a seguinte barra, onde em “Responsive” é possível verificar as versões da página em diversos celulares:
  - <img>![image](https://user-images.githubusercontent.com/60974082/113652267-d9847080-9669-11eb-9e1b-9e40f80870ba.png)</img> 

•	@media: media query. Faz uma pergunta ao navegador. Podemos perguntar por exemplo qual o tamanho de uma tela, e se for o tamanho desejado será entregue um estilo diferente. No exemplo abaixo, “screen” é o tipo de tela que se está buscando (poderia ser “print para impressora, etc) e “and ()” é a pesquisa, sendo que “(max-width: 480px)” significa “até 40 pixels”, e “body” é onde se reescreve um estilo diferente:
  - <img>![image](https://user-images.githubusercontent.com/60974082/113652282-de492480-9669-11eb-847f-f3821f9e4c21.png)</img>

•	Guia de Unidades do CSS: https://www.alura.com.br/artigos/guia-de-unidades-no-css.

