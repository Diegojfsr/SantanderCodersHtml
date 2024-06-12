
Principais Tags HTML (Parte II)

- Imagens.
- Listas.
- Tags de uso generico.

<!-- Imagens -->

<!-- 
Dica:
Ajuste de codigo na tela.
Control+,
em configuracoes buscar por Word Wrap
e marcar a opcao On.
Isso vai ajustar o codigo dentro da area visivel do VsCode.
-->

<img src="" alt="">


<!-- 
src - source, onde a imagen esta.
alt - descricao alternativa, descrever conteudo da imagem.
width - largura da imagem e altura altomatica.
height - altura da imagem, e sempre bom manter apenas a largura.
Por padrao o tamanho da imagens sao sempre em pX mas 
podem ser alterados para %.
-->
<!-- Pegando uma imagem local -->
<img src="images/Logohtml.png" alt="Logo do HTML" width="400" height="auto">

<!-- Pegando uma imagem externa -->
<img src="https://static.vecteezy.com/system/resources/previews/012/697/299/non_2x/stylized-3d-html-logo-design-free-png.png" alt="Logo do HTML" width="400" height="auto">


<!-- Listas -->

<!-- 
Dica:
Apertando li*3
ja cria as 3 <li></li>
Apertando o Tab e possivel 
digitar o texto dentro das <li></li>.
-->

<h2>Listas</h2>
<h3>Lista Nao Numerada</h3>
<ul>
    <li>Primeiro Item</li>
    <li>Segundo Item</li>
    <li>Terceiro Item</li>
</ul>

<h3>Lista Numerada</h3>
<ol>
    <li>Primeiro Item</li>
    <li>Segundo Item</li>
    <li>Terceiro Item</li>
</ol>


<!-- Tags de uso generico -->
    <h2>Tags de uso generico</h2>
<!-- Sao tags utilizadas para qualquer coisa -->
<p>Lorem ipsum dolor, sit amet consectetur <span>adipisicing</span> elit. Obcaecati amet laboriosam neque ea nemo quae vero maiores vitae distinctio nobis provident, iusto consequatur ex. Nesciunt sequi quia voluptatum quo distinctio?</p>

<span>tag inLine, E uma tag que nao quebra linha.</span>
<div>Tag block, ela quebra uma linha e cria um bloco de codigo.</div>



