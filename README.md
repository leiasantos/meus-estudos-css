<h1>Propriedades de Texto no CSS</h1>
<h2>Tabela de Propriedades de Texto no CSS</h2>
    <table>
        <tr>
            <th>Propriedade</th>
            <th>Descrição</th>
            <th>Exemplo</th>
        </tr>
        <tr>
            <td><code>text-indent</code></td>
            <td>Define o recuo da primeira linha do parágrafo.</td>
            <td><code>text-indent: 20px;</code></td>
        </tr>
        <tr>
            <td><code>text-align</code></td>
            <td>Alinha o texto (esquerda, direita, centro, justificado).</td>
            <td><code>text-align: center;</code></td>
        </tr>
        <tr>
            <td><code>text-decoration</code></td>
            <td>Adiciona efeitos ao texto, como sublinhado ou riscado.</td>
            <td><code>text-decoration: underline;</code></td>
        </tr>
        <tr>
            <td><code>letter-spacing</code></td>
            <td>Define o espaçamento entre letras.</td>
            <td><code>letter-spacing: 2px;</code></td>
        </tr>
        <tr>
            <td><code>word-spacing</code></td>
            <td>Define o espaçamento entre palavras.</td>
            <td><code>word-spacing: 5px;</code></td>
        </tr>
        <tr>
            <td><code>text-transform</code></td>
            <td>Controla a capitalização do texto.</td>
            <td><code>text-transform: uppercase;</code></td>
        </tr>
        <tr>
            <td><code>white-space</code></td>
            <td>Controla como os espaços em branco são tratados.</td>
            <td><code>white-space: nowrap;</code></td>
        </tr>
    </table>

  ![image](https://github.com/user-attachments/assets/ea4fc1a7-386f-4cf0-890a-5c5c75ee21f6)

  <h2>Fontes tipográficas</h2>
    <h2>Tabela de Propriedades de Fonte no CSS</h2>
    <table>
        <tr>
            <th>Propriedade</th>
            <th>Descrição</th>
            <th>Exemplo</th>
        </tr>
        <tr>
            <td><code>font-family</code></td>
            <td>Define a família da fonte do texto.</td>
            <td><code>font-family: Arial, sans-serif;</code></td>
        </tr>
        <tr>
            <td><code>font-style</code></td>
            <td>Define o estilo da fonte (normal, itálico, oblíquo).</td>
            <td><code>font-style: italic;</code></td>
        </tr>
        <tr>
            <td><code>font-variant</code></td>
            <td>Define se o texto será exibido em caixa pequena.</td>
            <td><code>font-variant: small-caps;</code></td>
        </tr>
        <tr>
            <td><code>font-weight</code></td>
            <td>Define a espessura da fonte (normal, negrito, numérico).</td>
            <td><code>font-weight: bold;</code></td>
        </tr>
        <tr>
            <td><code>font-size</code></td>
            <td>Define o tamanho da fonte.</td>
            <td><code>font-size: 18px;</code></td>
        </tr>
        <tr>
            <td><code>font</code></td>
            <td>Atalho para definir várias propriedades de fonte ao mesmo tempo.</td>
            <td><code>font: italic bold 16px Arial, sans-serif;</code></td>
        </tr>
    </table>


![image](https://github.com/user-attachments/assets/f24d85c1-62f7-4513-a5a9-ed252c844271)

 <h2>Tabela de Unidades de Tamanho - Relativas e Absolutas</h2>
    <table>
        <tr>
            <th>Unidade</th>
            <th>Tipo</th>
            <th>Descrição</th>
            <th>Exemplo</th>
        </tr>
        <tr>
            <td><code>em</code></td>
            <td>Relativa</td>
            <td>A unidade em é relativa ao tamanho da fonte do elemento pai.</td>
            <td><code>font-size: 2em;</code></td>
        </tr>
        <tr>
            <td><code>rem</code></td>
            <td>Relativa</td>
            <td>A unidade rem é relativa ao tamanho da fonte do elemento raiz (normalmente 16px).</td>
            <td><code>font-size: 1.5rem;</code></td>
        </tr>
        <tr>
            <td><code>%</code></td>
            <td>Relativa</td>
            <td>A unidade % é relativa ao valor do elemento pai (por exemplo, largura ou altura).</td>
            <td><code>width: 50%;</code></td>
        </tr>
        <tr>
            <td><code>vw</code></td>
            <td>Relativa</td>
            <td>A unidade vw é baseada na largura da janela de visualização (viewport). 1vw é 1% da largura da tela.</td>
            <td><code>font-size: 5vw;</code></td>
        </tr>
        <tr>
            <td><code>vh</code></td>
            <td>Relativa</td>
            <td>A unidade vh é baseada na altura da janela de visualização (viewport). 1vh é 1% da altura da tela.</td>
            <td><code>height: 50vh;</code></td>
        </tr>
        <tr>
            <td><code>px</code></td>
            <td>Absoluta</td>
            <td>A unidade px é fixa, representando um pixel da tela ou de um dispositivo.</td>
            <td><code>width: 200px;</code></td>
        </tr>
        <tr>
            <td><code>pt</code></td>
            <td>Absoluta</td>
            <td>A unidade pt é baseada no sistema de impressão, 1pt é igual a 1/72 polegada.</td>
            <td><code>font-size: 12pt;</code></td>
        </tr>
        <tr>
            <td><code>cm</code></td>
            <td>Absoluta</td>
            <td>A unidade cm é relativa ao sistema métrico (centímetros).</td>
            <td><code>width: 10cm;</code></td>
        </tr>
        <tr>
            <td><code>mm</code></td>
            <td>Absoluta</td>
            <td>A unidade mm é uma subdivisão do centímetro (milímetros).</td>
            <td><code>height: 50mm;</code></td>
        </tr>
        <tr>
            <td><code>in</code></td>
            <td>Absoluta</td>
            <td>A unidade in é baseada no sistema imperial (polegadas), 1 polegada = 2,54 cm.</td>
            <td><code>width: 5in;</code></td>
        </tr>
    </table>

![image](https://github.com/user-attachments/assets/1f28eb97-2ee6-4965-906b-2fcff5286011)

<h2>Representação de cores</h2>
<h2>Tabela de Notações de Cores em CSS</h2>
    <table>
        <tr>
            <th>Notação</th>
            <th>Descrição</th>
            <th>Exemplo</th>
        </tr>
        <tr>
            <td>Nome</td>
            <td>Cores por nome (ex.: red, blue)</td>
            <td><code>color: red;</code></td>
        </tr>
        <tr>
            <td>Hexadecimal</td>
            <td>Código hexadecimal de 6 caracteres</td>
            <td><code>color: #FF5733;</code></td>
        </tr>
        <tr>
            <td>RGB</td>
            <td>Valores de Red, Green e Blue (0-255)</td>
            <td><code>color: rgb(255, 87, 51);</code></td>
        </tr>
        <tr>
            <td>RGBA</td>
            <td>RGB com opacidade (0-1)</td>
            <td><code>color: rgba(255, 87, 51, 0.5);</code></td>
        </tr>
        <tr>
            <td>HSL</td>
            <td>Hue (matiz), Saturation (saturação), Lightness (luminosidade)</td>
            <td><code>color: hsl(9, 100%, 60%);</code></td>
        </tr>
        <tr>
            <td>HSLA</td>
            <td>HSL com opacidade (0-1)</td>
            <td><code>color: hsla(9, 100%, 60%, 0.5);</code></td>
        </tr>
        <tr>
            <td>Hexa com Alpha</td>
            <td>Hexadecimal com opacidade de 8 caracteres</td>
            <td><code>color: #FF573380;</code></td>
        </tr>
    </table>


![image](https://github.com/user-attachments/assets/956db5d0-9bed-4080-a4cb-529bcf57fc06)


<h2>Tabela de Propriedades de Border em CSS</h2>
    <table>
        <tr>
            <th>Propriedade</th>
            <th>Descrição</th>
            <th>Exemplo</th>
        </tr>
        <tr>
            <td>border</td>
            <td>Define a largura, o estilo e a cor de todas as bordas.</td>
            <td><code>border: 2px solid red;</code></td>
        </tr>
        <tr>
            <td>border-top, border-right, border-bottom, border-left</td>
            <td>Define as bordas de cada lado do elemento individualmente.</td>
            <td><code>border-top: 2px solid blue;</code></td>
        </tr>
        <tr>
            <td>border-top-width, border-right-width, border-bottom-width, border-left-width</td>
            <td>Define a largura das bordas de cada lado.</td>
            <td><code>border-top-width: 5px;</code></td>
        </tr>
        <tr>
            <td>border-top-color, border-right-color, border-bottom-color, border-left-color</td>
            <td>Define a cor das bordas de cada lado.</td>
            <td><code>border-top-color: green;</code></td>
        </tr>
        <tr>
            <td>border-width</td>
            <td>Define a largura de todas as bordas do elemento.</td>
            <td><code>border-width: 2px 5px 10px 5px;</code></td>
        </tr>
        <tr>
            <td>border-color</td>
            <td>Define a cor de todas as bordas.</td>
            <td><code>border-color: black;</code></td>
        </tr>
        <tr>
            <td>border-style</td>
            <td>Define o estilo das bordas (ex: solid, dotted, dashed).</td>
            <td><code>border-style: dashed;</code></td>
        </tr>
        <tr>
            <td>border-radius</td>
            <td>Define o raio das bordas arredondadas.</td>
            <td><code>border-radius: 10px;</code></td>
        </tr>
    </table>
    
![image](https://github.com/user-attachments/assets/5ead1768-70cb-42c2-94e8-bc635f91f85b)

   <h2>Tabela de Propriedades de Margens em CSS</h2>
    <table>
        <tr>
            <th>Propriedade</th>
            <th>Descrição</th>
            <th>Exemplo</th>
        </tr>
        <tr>
            <td>margin</td>
            <td>Define a margem de todos os lados do elemento de uma vez.</td>
            <td><code>margin: 20px;</code></td>
        </tr>
        <tr>
            <td>margin-top</td>
            <td>Define a margem superior do elemento.</td>
            <td><code>margin-top: 10px;</code></td>
        </tr>
        <tr>
            <td>margin-right</td>
            <td>Define a margem à direita do elemento.</td>
            <td><code>margin-right: 15px;</code></td>
        </tr>
        <tr>
            <td>margin-bottom</td>
            <td>Define a margem inferior do elemento.</td>
            <td><code>margin-bottom: 25px;</code></td>
        </tr>
        <tr>
            <td>margin-left</td>
            <td>Define a margem à esquerda do elemento.</td>
            <td><code>margin-left: 30px;</code></td>
        </tr>
    </table>  

   <h2>Tabela de Propriedades de Padding em CSS</h2>
    <table>
        <tr>
            <th>Propriedade</th>
            <th>Descrição</th>
            <th>Exemplo</th>
        </tr>
        <tr>
            <td>padding</td>
            <td>Define o padding para todos os lados do elemento de uma vez.</td>
            <td><code>padding: 20px;</code></td>
        </tr>
        <tr>
            <td>padding-top</td>
            <td>Define o padding na parte superior do elemento.</td>
            <td><code>padding-top: 10px;</code></td>
        </tr>
        <tr>
            <td>padding-right</td>
            <td>Define o padding à direita do elemento.</td>
            <td><code>padding-right: 15px;</code></td>
        </tr>
        <tr>
            <td>padding-bottom</td>
            <td>Define o padding na parte inferior do elemento.</td>
            <td><code>padding-bottom: 25px;</code></td>
        </tr>
        <tr>
            <td>padding-left</td>
            <td>Define o padding à esquerda do elemento.</td>
            <td><code>padding-left: 30px;</code></td>
        </tr>
    </table>

  <h2>Tabela de Propriedades de Display em CSS</h2>
    <table>
        <tr>
            <th>Propriedade</th>
            <th>Descrição</th>
            <th>Exemplo</th>
        </tr>
        <tr>
            <td>display</td>
            <td>Define o comportamento de exibição do elemento na página.</td>
            <td><code>display: inline;</code></td>
        </tr>
        <tr>
            <td>inline</td>
            <td>Exibe o elemento na mesma linha, sem quebra, com tamanho automático.</td>
            <td><code>display: inline;</code></td>
        </tr>
        <tr>
            <td>block</td>
            <td>Exibe o elemento em uma nova linha, ocupando toda a largura disponível.</td>
            <td><code>display: block;</code></td>
        </tr>
        <tr>
            <td>inline-block</td>
            <td>Exibe o elemento na mesma linha, mas permite definir suas dimensões (largura e altura).</td>
            <td><code>display: inline-block;</code></td>
        </tr>
        <tr>
            <td>list-item</td>
            <td>Exibe o elemento como um item de lista, com marcador (bullet) ou número.</td>
            <td><code>display: list-item;</code></td>
        </tr>
        <tr>
            <td>none</td>
            <td>Remove o elemento da renderização, ele não ocupa espaço e não é exibido.</td>
            <td><code>display: none;</code></td>
        </tr>
        <tr>
            <td>table</td>
            <td>Exibe o elemento como uma tabela, com comportamento de tabela HTML.</td>
            <td><code>display: table;</code></td>
        </tr>
        <tr>
            <td>inline-table</td>
            <td>Exibe o elemento como uma tabela, mas na mesma linha de outros elementos.</td>
            <td><code>display: inline-table;</code></td>
        </tr>
    </table>
    
   <h2>Tabela de Propriedades de Position em CSS</h2>
    <table>
        <tr>
            <th>Propriedade</th>
            <th>Descrição</th>
            <th>Exemplo</th>
        </tr>
        <tr>
            <td>static</td>
            <td>Posicionamento padrão, baseado no fluxo normal do documento. Não permite o uso de <code>top</code>, <code>left</code>, <code>bottom</code>, <code>right</code>.</td>
            <td><code>position: static;</code></td>
        </tr>
        <tr>
            <td>relative</td>
            <td>Posiciona o elemento em relação à sua posição original no fluxo normal. Permite usar <code>top</code>, <code>left</code>, <code>bottom</code>, <code>right</code>.</td>
            <td><code>position: relative;</code></td>
        </tr>
        <tr>
            <td>absolute</td>
            <td>Posiciona o elemento em relação ao seu ancestral mais próximo com <code>position</code> diferente de <code>static</code> (geralmente <code>relative</code> ou <code>absolute</code>).</td>
            <td><code>position: absolute;</code></td>
        </tr>
        <tr>
            <td>fixed</td>
            <td>Posiciona o elemento em relação à janela de visualização. Fica fixo enquanto o usuário rola a página.</td>
            <td><code>position: fixed;</code></td>
        </tr>
    </table>

   <h2>Tabela com Propriedades top, right, bottom, left</h2>
    <table>
        <tr>
            <th>Propriedade</th>
            <th>Descrição</th>
            <th>Exemplo</th>
        </tr>
        <tr>
            <td>top</td>
            <td>Desloca o elemento para baixo, a partir da sua posição original (para <code>position: relative</code>, <code>absolute</code> ou <code>fixed</code>).</td>
            <td><code>top: 20px;</code></td>
        </tr>
        <tr>
            <td>right</td>
            <td>Desloca o elemento para a direita, a partir da sua posição original.</td>
            <td><code>right: 20px;</code></td>
        </tr>
        <tr>
            <td>bottom</td>
            <td>Desloca o elemento para cima, a partir da sua posição original.</td>
            <td><code>bottom: 20px;</code></td>
        </tr>
        <tr>
            <td>left</td>
            <td>Desloca o elemento para a esquerda, a partir da sua posição original.</td>
            <td><code>left: 20px;</code></td>
        </tr>
    </table>

  <h3>Informação retirada da página <a href="https://www.mediaevent.de/css/position-top.html">mediaevent</a></h3>

 ![image](https://github.com/user-attachments/assets/1241be9b-4757-4eec-b5a2-a824d484db80)


 <h2>Propriedades CSS: float, clear, z-index, direction</h2>

   <table>
        <tr>
            <th>Propriedade</th>
            <th>Descrição</th>
            <th>Exemplo</th>
        </tr>
        <tr>
            <td>float</td>
            <td>Posiciona um elemento à esquerda ou à direita do seu contêiner, permitindo que o conteúdo flua ao seu redor.</td>
            <td><code>float: left;</code></td>
        </tr>
        <tr>
            <td>clear</td>
            <td>Evita que o conteúdo flua ao redor de um elemento flutuante, controlando de qual lado o conteúdo será interrompido.</td>
            <td><code>clear: both;</code></td>
        </tr>
        <tr>
            <td>z-index</td>
            <td>Define a ordem de sobreposição dos elementos. Elementos com valores maiores de <code>z-index</code> são posicionados na frente.</td>
            <td><code>z-index: 10;</code></td>
        </tr>
        <tr>
            <td>direction</td>
            <td>Controla a direção do texto dentro de um elemento. Útil para idiomas da direita para a esquerda (RTL).</td>
            <td><code>direction: rtl;</code></td>
        </tr>
    </table>
 
  <h2>Propriedades CSS: width, min-width, max-width, height, min-height, max-height, line-height, vertical-align</h2>
    <table>
        <tr>
            <th>Propriedade</th>
            <th>Descrição</th>
            <th>Exemplo</th>
        </tr>
        <tr>
            <td>width</td>
            <td>Define a largura de um elemento.</td>
            <td><code>width: 200px;</code></td>
        </tr>
        <tr>
            <td>min-width</td>
            <td>Define a largura mínima de um elemento. O elemento não pode ser menor que esse valor.</td>
            <td><code>min-width: 150px;</code></td>
        </tr>
        <tr>
            <td>max-width</td>
            <td>Define a largura máxima de um elemento. O elemento não pode ser maior que esse valor.</td>
            <td><code>max-width: 500px;</code></td>
        </tr>
        <tr>
            <td>height</td>
            <td>Define a altura de um elemento.</td>
            <td><code>height: 300px;</code></td>
        </tr>
        <tr>
            <td>min-height</td>
            <td>Define a altura mínima de um elemento. O elemento não pode ser menor que esse valor.</td>
            <td><code>min-height: 200px;</code></td>
        </tr>
        <tr>
            <td>max-height</td>
            <td>Define a altura máxima de um elemento. O elemento não pode ser maior que esse valor.</td>
            <td><code>max-height: 600px;</code></td>
        </tr>
        <tr>
            <td>line-height</td>
            <td>Define a altura da linha de texto dentro de um elemento.</td>
            <td><code>line-height: 1.5;</code></td>
        </tr>
        <tr>
            <td>vertical-align</td>
            <td>Controla o alinhamento vertical de elementos inline ou inline-block.</td>
            <td><code>vertical-align: middle;</code></td>
        </tr>
    </table>

   <h2>Propriedades CSS: overflow, clip, visibility</h2>
    <table>
        <tr>
            <th>Propriedade</th>
            <th>Descrição</th>
            <th>Exemplo</th>
        </tr>
        <tr>
            <td>overflow</td>
            <td>Controla o que acontece quando o conteúdo de um elemento ultrapassa o tamanho definido.</td>
            <td><code>overflow: hidden;</code></td>
        </tr>
        <tr>
            <td>clip</td>
            <td>Define uma área retangular visível dentro de um elemento. O conteúdo fora dessa área é cortado.</td>
            <td><code>clip: rect(10px, 20px, 30px, 40px);</code></td>
        </tr>
        <tr>
            <td>visibility</td>
            <td>Controla a visibilidade de um elemento, mas o espaço que ele ocupa ainda é mantido.</td>
            <td><code>visibility: hidden;</code></td>
        </tr>
    </table>
 
   <h2>Propriedades CSS: content, quotes, counter-reset, counter-increment</h2>
    <table>
        <tr>
            <th>Propriedade</th>
            <th>Descrição</th>
            <th>Exemplo</th>
        </tr>
        <tr>
            <td>content</td>
            <td>Usada para gerar conteúdo antes ou depois de um elemento com pseudo-elementos.</td>
            <td><code>content: "Texto";</code></td>
        </tr>
        <tr>
            <td>quotes</td>
            <td>Define as aspas usadas para envolver o conteúdo das tags <code>&lt;q&gt;</code>.</td>
            <td><code>quotes: "“" "”" "‘" "’";</code></td>
        </tr>
        <tr>
            <td>counter-reset</td>
            <td>Inicializa ou redefine um contador que pode ser utilizado com <code>counter-increment</code>.</td>
            <td><code>counter-reset: section;</code></td>
        </tr>
        <tr>
            <td>counter-increment</td>
            <td>Aumenta o valor de um contador.</td>
            <td><code>counter-increment: section;</code></td>
        </tr>
    </table>

  <h2>Propriedades CSS: list-style, list-style-image, list-style-type, list-style-position</h2>
    <table>
        <tr>
            <th>Propriedade</th>
            <th>Descrição</th>
            <th>Exemplo</th>
        </tr>
        <tr>
            <td>list-style</td>
            <td>Propriedade abreviada que combina as propriedades <code>list-style-type</code>, <code>list-style-position</code>, e <code>list-style-image</code>.</td>
            <td><code>list-style: disc inside;</code></td>
        </tr>
        <tr>
            <td>list-style-image</td>
            <td>Define uma imagem como marcador da lista.</td>
            <td><code>list-style-image: url('icone.png');</code></td>
        </tr>
        <tr>
            <td>list-style-type</td>
            <td>Define o tipo de marcador para uma lista (círculo, disco, numeração, etc.).</td>
            <td><code>list-style-type: circle;</code></td>
        </tr>
        <tr>
            <td>list-style-position</td>
            <td>Controla a posição do marcador da lista, podendo ser "inside" ou "outside".</td>
            <td><code>list-style-position: inside;</code></td>
        </tr>
    </table>

   <h2>Propriedades CSS: color, background-color, background-image, background-repeat, background-attachment, background-position, background</h2>
    <table>
        <tr>
            <th>Propriedade</th>
            <th>Descrição</th>
            <th>Exemplo</th>
        </tr>
        <tr>
            <td>color</td>
            <td>Define a cor do texto.</td>
            <td><code>color: red;</code></td>
        </tr>
        <tr>
            <td>background-color</td>
            <td>Define a cor de fundo de um elemento.</td>
            <td><code>background-color: yellow;</code></td>
        </tr>
        <tr>
            <td>background-image</td>
            <td>Define uma imagem de fundo para o elemento.</td>
            <td><code>background-image: url('image.jpg');</code></td>
        </tr>
        <tr>
            <td>background-repeat</td>
            <td>Controla a repetição da imagem de fundo.</td>
            <td><code>background-repeat: no-repeat;</code></td>
        </tr>
        <tr>
            <td>background-attachment</td>
            <td>Define o comportamento da imagem de fundo ao rolar a página.</td>
            <td><code>background-attachment: fixed;</code></td>
        </tr>
        <tr>
            <td>background-position</td>
            <td>Controla a posição da imagem de fundo.</td>
            <td><code>background-position: center center;</code></td>
        </tr>
        <tr>
            <td>background</td>
            <td>Propriedade abreviada para todas as propriedades relacionadas ao fundo.</td>
            <td><code>background: #ff5733 url('image.jpg') no-repeat fixed center;</code></td>
        </tr>
    </table>

<h2>Propriedades CSS para Tabelas: caption-side, table-layout, border-collapse, border-spacing, empty-cells</h2>

  <table>
        <tr>
            <th>Propriedade</th>
            <th>Descrição</th>
            <th>Exemplo</th>
        </tr>
        <tr>
            <td>caption-side</td>
            <td>Define a posição do título da tabela (acima ou abaixo).</td>
            <td><code>caption-side: bottom;</code></td>
        </tr>
        <tr>
            <td>table-layout</td>
            <td>Define o layout da tabela: auto ou fixed.</td>
            <td><code>table-layout: fixed;</code></td>
        </tr>
        <tr>
            <td>border-collapse</td>
            <td>Controla se as bordas das células da tabela devem se fundir ou não.</td>
            <td><code>border-collapse: collapse;</code></td>
        </tr>
        <tr>
            <td>border-spacing</td>
            <td>Define o espaço entre as células quando border-collapse é separate.</td>
            <td><code>border-spacing: 10px;</code></td>
        </tr>
        <tr>
            <td>empty-cells</td>
            <td>Controla a exibição de células vazias.</td>
            <td><code>empty-cells: hide;</code></td>
        </tr>
    </table>

  <h2>Propriedades CSS: outline-width, outline-style, outline-color, outline, speak-header</h2>

  <table border="1">
        <thead>
            <tr>
                <th>Propriedade</th>
                <th>Descrição</th>
                <th>Exemplo</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>outline-width</td>
                <td>Define a espessura da borda de contorno de um elemento.</td>
                <td><code>outline-width: 2px;</code></td>
            </tr>
            <tr>
                <td>outline-style</td>
                <td>Define o estilo da borda de contorno de um elemento.</td>
                <td><code>outline-style: dashed;</code></td>
            </tr>
            <tr>
                <td>outline-color</td>
                <td>Define a cor da borda de contorno de um elemento.</td>
                <td><code>outline-color: red;</code></td>
            </tr>
            <tr>
                <td>outline</td>
                <td>Propriedade abreviada para definir a largura, estilo e cor da borda de contorno.</td>
                <td><code>outline: 2px solid red;</code></td>
            </tr>
            <tr>
                <td>speak-header</td>
                <td>Define se os cabeçalhos devem ser falados com destaque em tecnologias assistivas.</td>
                <td><code>speak-header: always;</code></td>
            </tr>
        </tbody>
    </table>


  

    




