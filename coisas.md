<a id="topo"></a>
file -> add folder to workspace -> trabalha na mesma tela dois projetos separados, ao mesmo tempo -> 1° pega um depois, mesmo caminho o outro
par savar - save worksapece

<a href="#atalhos">Atalhos Geral</a>
<a href="#html">HTML</a>
<a href="#tags">Tags</a>
<a href="#list">Listas</a>
<a href="#img">Imagens</a>
<a href="#links">Links</a>
<a href="#tabelas">Tabelas/Table</a>
<a href="#formulario">Formulário</a>


<h1 style="color: #023e8a;">Como sites funcionam </h1>

internet -> rede de conexão entre computadores - web (teia/ rede)

como acessar onde está o site desejado?
cada site tem um endereço, chamdo de <span style="color: #6a994e;">ip</span> diz onde está o computador

www.iplocation.net acha os ip

<span style="color: #6a994e;">domínio</span> identifica o endereço do site -> e ele está conectado a um ip

<span style="color: #6a994e;">dns - sistema de nome do dominio</span> pelo nome/dominio locaiza o ip

dns envia apenas a página inicial, o processo acontece várias vezes, acontecendo sempre uma requisição a cada movimentação na pag

<span style="color: #bb3e03;">CLIENT SIDE</span> QUANDO ALGO É FEITO LOCAL, NO MEU COMPUTADOR

<span style="color: #bb3e03;">SERVIDOR SIDE</span> QUANDO ALGO É FEITO REMOTO, NO SERVIDOR

Quando recebe o site, recebe em forma de arquivos 
1° html
2° css
3° javaScript
<br>
<a href="#topo"><img src="/img/up.jpg" height="30"></a>
<br>
<h1 style="color: #023e8a;" id="atalhos">Atalhos Geral</h1>

<span style="color: #bb3e03;">alt seta cima e baixo</span> sobre ou desce uma linha comando

<span style="color: #bb3e03;">shift alt seta cima e baixo</span> copia linha de comando encima ou embaixo

<h1 style="color: #023e8a;" id="html">html</h1>
<br>
<a href="#topo"><img src="/img/up.jpg" height="30"></a>
<br>
<span style="color: #6a994e;">html</span> Hypertext Markup Langue - <i>Linguagem de marcação de hipertexto</i> -> cria a <b><u>ESTRUTURA</u> DO SITE </b> -> aqui não programa, se desenvolve em html.

CSS -> aparência

JavaScript ->  interatividade (linguagem de programação)

<span style="color: #d4a373;">site lipsum.com</span> para criar texto - tem btn generate lorem ipson 

<span style="color: #d4a373;">site mussumipsum.com</span> para criar texto mas como se fosse o mussum falando (muito legal) 
<br>
<a href="#topo"><img src="/img/up.jpg" height="30"></a>
<br>
<h3 style="color: #023e8a;" id="tags">tags</h3>

<span style="color: #6a994e;">< trong></span> <strong>infromação inportante</strong>

<span style="color: #6a994e;">< em></span> <em>ênfase a conteúdos - leitores de tela usa bastante</em>

<span style="color: #6a994e;">< mark></span> <mark>marca texto</mark>

<span style="color: #6a994e;">< u></span> <u>underscore</u>

<span style="color: #6a994e;">< del></span> <del>texto "apagado"</del>

<span style="color: #6a994e;">< sup></span> <sub>subscrito</sub> ->x<sub>p</sub>

<span style="color: #6a994e;">< sup></span> <sup>sobrescrito</sup> ->x<sup>2</sup>
<br>
<a href="#topo"><img src="/img/up.jpg" height="30"></a>
<br>
<h3 style="color: #023e8a;" id="list">Listas</h3>

<span style="color: #6a994e;">lista aninhada</span> Lista dentro de lista

Não se usa mais type em list

<span style="color: #6a994e;">ul</span> UnOrdered list - lista não ordenada

Ordem não altera resultado final, usa <strong> style </strong>

<span style="color: #6a994e;">ol</span> Ordered list - lista ordenada

Aparece numeração e deve ter ordem específica

<span style="color: #6a994e;">li</span> List Item - item da lista

ob:
<span style="color: #6a994e;">< hr></span> cria uma linha longa horizontalmente - não tem haver com lista
<br>
<a href="#topo"><img src="/img/up.jpg" height="30"></a>
<br>
<h3 style="color: #023e8a;" id="img">Imagens</h3>

<span style="color: #6a994e;">src</span> SouRCe (fonte, origem)

<span style="color: #6a994e;">alt</span> texto aparece caso a img não carregue

<strong><span style="color: #d4a373">correto é por a img no projeto, não pegar direto da internet</span> </strong>

Salvar imagem como, salva na pasta, copia a img e coloca na pasta do projeto, digita endereço

<span style="color: #d4a373">tipos de img</span><span style="color: #bb3e03;" > - png, jpg, jpeg, gif </span>

png possibilita transparência

<span style="color: #6a994e;">width</span> largura apenas

<span style="color: #6a994e;">height</span> altura, ela ajuda a manter proporção da largura

<span style="color: #6a994e;">title</span> título da imagem

<span style="color: #6a994e;">para saber proproção da img</span> botão direito na imagem, na pasta, propriedades, detalhes, imagem -> dimensão, largura e altura

<span style="color: #bc6c25;">caminho Absoluto</span> caminho que volta para raiz do projeto de forma automática

ex: subir nível é subir uma pasta, por exemplo <strong><span style="color:#ff4d6d;">/</span> ele começa da pasta raiz do projeto</strong> 

<span style="color: #bc6c25;">caminho relativo</span> caminho relativo a pasta que está, e deve subir níveis para acessar o que deseja

ex: subir nível é subir uma pasta, por exemplo <strong><span style="color:#ff4d6d;">../</span> ele volta "casa", folder</strong> -> caminho relativo

<strong>Para subir dois níveis, coloca ../../</strong>

<span style="color: #6a994e;">< figure>< /figure></span> define foto, ilustração, diagram, etc. Dentro dela coloca < img> e <span style="color: #6a994e;">< figcaotion></span>"legenda" da imagem<span style="color: #6a994e;">< /figcaotion></scpan>
<br>
<a href="#topo"><img src="/img/up.jpg" height="30"></a>
<br>
<h3 style="color: #023e8a;" id="links">links</h3>

<span style="color: #6a994e;">< a>< /a></span> anchor, âncora, apontar

<span style="color: #6a994e;">href</span> hiperlink reference - referência do hiperlink/link

<span style="color: #6a994e;"># e id</span> âncora para subir toda pag, tipo as setas para cima

cria um link no local desejado < a href="#nome do id">texto</ a>

depois, no título ou local que deseja coloca o ide
< h2 id="nome id">texto< /h2>

<span style="color: #6a994e;">target</span> alvo, local que vai abrir a pág

- <span style="color: #d4a373;">"_self"</span> -mesma- abre na própria aba web

- <span style="color: #d4a373;">"_blank"</span> -vazio, branco- abre uma nova aba web

pode fazer links internos e externos

<h2><strong>index é página main, inicial</strong></h2>
<br>
<a href="#topo"><img src="/img/up.jpg" height="30"></a>
<br>
<h3 style="color: #023e8a;" id="tabelas">Tabelas/table</h3>

<span style="color: #6a994e;">tr</span> table Row, linha de tabela

<span style="color: #6a994e;">td</span> table Data, dados da tabela * Table Cell, células da tabela

<span style="color: #6a994e;">th</span> table Header, cabeçalho da tabela

O <u>border</u> não deve mais ser usado, no lugar usa-se o css. No exeercício será usado apenas porque o css ainda não foi introduzido

<span style="color: #6a994e;">colspan</span> extensão da coluna 

<span style="color: #6a994e;">rowspna</span> extensão da linha

<span style="color: #6a994e;">caption</span> legenda, título da tabela

<span style="color: #6a994e;">theader</span> Table Header - cabeçalho da tabela

<span style="color: #6a994e;">tbody</span> table body, corpo de tabela

<span style="color: #6a994e;">tfoot</span> table footer, rodapé da tabela
<br>
<a href="#topo"><img src="/img/up.jpg" height="30"></a>
<br>
<h3 style="color: #023e8a;" id="formulario">Formulário</h3>

<span style="color: #6a994e;">formulário no html</span> permite que o ussuário inira dados que ssão enviados a um servidor para processamento

ex: google, ao fazer pesquisa
&nbsp;&nbsp;&nbsp;&nbsp;: ficha de incrição

<span style="color: #d4a373;">Tipos de elementos do formulário</span>

- <span style="color: #6a994e;">add texto</span> - linha única de texto

- <span style="color: #6a994e;">add senha</span> - mascara os dados inputados. Linha única

- <span style="color: #6a994e;">área de texto</span> - multilinhas de texto

<span style="color: #d4a373;">Tipos de elementos do formulário para escolhas</span>

- <span style="color: #6a994e;">caixa suspença</span> - para seleeção de uma lista (clica em uma seta e aparece lista de seleção)

- <span style="color: #6a994e;">botão de rádio</span> - selecionar uma opção dentro de uma série de opções (ex: circulo que se clica ao dizer que é gênero feminino)

- <span style="color: #6a994e;">caixa de verificação</span> - para marcar mais de uma opção (quando usuário pode escolher que gosta de rock, pop, samba, dentre vários tipos de estilos de música, ou quando tira o tique de querer receber propaganda no e-mail)

<u>obrigatoriedade depende de como fará o app/site</u>

<span style="color: #d4a373;">Tipos de elementos do formulário para envios</span>

- <span style="color: #6a994e;">botão de envio</span> - para enviar dados para serem processados

- <span style="color: #6a994e;">botão de imagem</span> - para enviar dados para serem processados, porém pode ter imagem e texto ou ser só uma imagem

- <span style="color: #6a994e;">botão de upload de arquivos</span> - para enviar imagem para serem processados - envio de arquivo, aparece o nome dele no lado do btn

<span style="color: #d4a373;">Como funciona o formulário</span>

Ao enviar, o servidor captura o id dos dados e processa ou/e armazenados, depois o ervidor envia nova página para o navegador com base em que recebeu, exemplo, retona mensagem, redireciona para nova página, etc

<span style="color: #6a994e;">input type</span> Tipo da entrada do input, como text, radio, etc - fica assim:

- input type="text" name="usuario"

o name- chave - atributo que indica nome que receberá o dado e o ervidor irá armazerna e pesquisar

usuario, neste caso é valor 

<h3 style="color: #398efdff;">Formulário criação</h3>

<span style="color: #d4a373;">add texto</span>

- <span style="color: #6a994e;">< form>< /form></span> - formulário
&nbsp;&nbsp;- dentro tem <u>ação</u> para onde irá estes dados e depois <u>como</u> irão os dados 

- <span style="color: #6a994e;">submit</span> - enviar, se por value="texto" ele muda, por exemplo para Salvar

- <span style="color: #6a994e;">action</span> - se deixar apenas " ", processa dentro do próprio arquivo, ou coloca nome.extenção (veremos depois)

- <span style="color: #6a994e;">method</span> - <strong>GET</strong> (envia dados - não é seguro, dá para ver senha digitada, por exemplo), <strong>POST</strong> (envia os dados de maneira escondida - é método mais lento, mais seguro)

- <span style="color: #6a994e;">placeholder</span> - texto que some quando a pessoa começa a digitar

- <span style="color: #6a994e;">label</span> - legenda para itens de interface. É um recuros de usabilidade em que se clica na caixa eu já ativa, se clica no texto (ex nome) também ativa

- <span style="color: #6a994e;">fieldset</span> - conjunto de campos

- <span style="color: #6a994e;">legend</span> - legenda para conjunto de campos

<br>
<a href="#topo"><img src="/img/up.jpg" height="30"></a>
<br>