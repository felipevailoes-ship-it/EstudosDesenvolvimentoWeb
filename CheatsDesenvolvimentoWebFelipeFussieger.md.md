---


---

<h1 id="cheats-para-desenvolvimento-web-—-html-css-e-javascript">Cheats para desenvolvimento Web — HTML, CSS e JavaScript</h1>
<blockquote>
<p>Documento de referência rápida com os principais conceitos, sintaxes e boas práticas de desenvolvimento web.</p>
</blockquote>
<hr>
<h2 id="🟠-html-—-hypertext-markup-language">🟠 HTML — HyperText Markup Language</h2>
<h3 id="o-que-é-html">O que é HTML?</h3>
<p>HTML (HyperText Markup Language) é a linguagem de marcação padrão utilizada mundialmente para estruturar e organizar conteúdos de páginas web, definindo elementos como textos, imagens, links e outros componentes exibidos nos navegadores.</p>
<h3 id="como-funciona">Como funciona?</h3>
<p>O HTML funciona através de <strong>tags</strong> — marcações que envolvem o conteúdo e indicam ao navegador como ele deve ser interpretado. A maioria das tags possui abertura e fechamento.</p>
<pre class=" language-html"><code class="prism  language-html"><span class="token comment">&lt;!-- Exemplo de tag com abertura e fechamento --&gt;</span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>p</span><span class="token punctuation">&gt;</span></span>Este é um parágrafo.<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>p</span><span class="token punctuation">&gt;</span></span>

<span class="token comment">&lt;!-- Exemplo de tag sem fechamento (auto-fechada) --&gt;</span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>img</span> <span class="token attr-name">src</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>imagem.png<span class="token punctuation">"</span></span> <span class="token attr-name">alt</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>Descrição da imagem<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
</code></pre>
<h3 id="exemplo-prático-—-estrutura-básica">Exemplo prático — Estrutura básica:</h3>
<pre class=" language-html"><code class="prism  language-html"><span class="token doctype">&lt;!DOCTYPE html&gt;</span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>html</span> <span class="token attr-name">lang</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>pt-BR<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>head</span><span class="token punctuation">&gt;</span></span>
    <span class="token comment">&lt;!-- Informações da página, não visíveis ao usuário --&gt;</span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>meta</span> <span class="token attr-name">charset</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>UTF-8<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>meta</span> <span class="token attr-name">name</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>viewport<span class="token punctuation">"</span></span> <span class="token attr-name">content</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>width=device-width, initial-scale=1.0<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>title</span><span class="token punctuation">&gt;</span></span>Minha Página<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>title</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>link</span> <span class="token attr-name">rel</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>stylesheet<span class="token punctuation">"</span></span> <span class="token attr-name">href</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>css/style.css<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>head</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>body</span><span class="token punctuation">&gt;</span></span>
    <span class="token comment">&lt;!-- Conteúdo visível da página --&gt;</span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>h1</span><span class="token punctuation">&gt;</span></span>Olá, mundo!<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>h1</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>p</span><span class="token punctuation">&gt;</span></span>Bem-vindo à minha página.<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>p</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>body</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>html</span><span class="token punctuation">&gt;</span></span>
</code></pre>
<hr>
<h3 id="principais-tags-utilizadas">Principais tags utilizadas</h3>
<h4 id="🏗️-estrutura">🏗️ Estrutura</h4>

<table>
<thead>
<tr>
<th>Tag</th>
<th>Descrição</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>&lt;html&gt;</code></td>
<td>Elemento raiz da página</td>
</tr>
<tr>
<td><code>&lt;head&gt;</code></td>
<td>Informações da página (título, scripts, estilos)</td>
</tr>
<tr>
<td><code>&lt;body&gt;</code></td>
<td>Conteúdo visível da página</td>
</tr>
</tbody>
</table><pre class=" language-html"><code class="prism  language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>html</span> <span class="token attr-name">lang</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>pt-BR<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>head</span><span class="token punctuation">&gt;</span></span>
        <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>title</span><span class="token punctuation">&gt;</span></span>Minha Página<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>title</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>head</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>body</span><span class="token punctuation">&gt;</span></span>
        <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>h1</span><span class="token punctuation">&gt;</span></span>Conteúdo aqui<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>h1</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>body</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>html</span><span class="token punctuation">&gt;</span></span>
</code></pre>
<h4 id="📝-títulos-e-texto">📝 Títulos e Texto</h4>

<table>
<thead>
<tr>
<th>Tag</th>
<th>Descrição</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>&lt;h1&gt;</code> a <code>&lt;h6&gt;</code></td>
<td>Títulos do maior ao menor destaque</td>
</tr>
<tr>
<td><code>&lt;p&gt;</code></td>
<td>Parágrafo de texto</td>
</tr>
<tr>
<td><code>&lt;span&gt;</code></td>
<td>Destaque inline sem quebra de linha</td>
</tr>
<tr>
<td><code>&lt;strong&gt;</code></td>
<td>Texto em negrito com ênfase semântica</td>
</tr>
<tr>
<td><code>&lt;em&gt;</code></td>
<td>Texto em itálico com ênfase</td>
</tr>
</tbody>
</table><pre class=" language-html"><code class="prism  language-html"><span class="token comment">&lt;!-- Títulos --&gt;</span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>h1</span><span class="token punctuation">&gt;</span></span>Título Principal<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>h1</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>h2</span><span class="token punctuation">&gt;</span></span>Subtítulo<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>h2</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>h6</span><span class="token punctuation">&gt;</span></span>Título menor<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>h6</span><span class="token punctuation">&gt;</span></span>

<span class="token comment">&lt;!-- Parágrafo --&gt;</span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>p</span><span class="token punctuation">&gt;</span></span>Este é um parágrafo de exemplo.<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>p</span><span class="token punctuation">&gt;</span></span>

<span class="token comment">&lt;!-- Span para destacar parte do texto --&gt;</span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>p</span><span class="token punctuation">&gt;</span></span>Meu cachorro é <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>span</span><span class="token style-attr language-css"><span class="token attr-name"> <span class="token attr-name">style</span></span><span class="token punctuation">="</span><span class="token attr-value"><span class="token property">color</span><span class="token punctuation">:</span> red<span class="token punctuation">;</span></span><span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>muito fofo<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>span</span><span class="token punctuation">&gt;</span></span>.<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>p</span><span class="token punctuation">&gt;</span></span>

<span class="token comment">&lt;!-- Negrito e itálico --&gt;</span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>p</span><span class="token punctuation">&gt;</span></span><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>strong</span><span class="token punctuation">&gt;</span></span>Atenção:<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>strong</span><span class="token punctuation">&gt;</span></span> leia as instruções com <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>em</span><span class="token punctuation">&gt;</span></span>cuidado<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>em</span><span class="token punctuation">&gt;</span></span>.<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>p</span><span class="token punctuation">&gt;</span></span>
</code></pre>
<h4 id="📋-listas">📋 Listas</h4>

<table>
<thead>
<tr>
<th>Tag</th>
<th>Descrição</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>&lt;ul&gt;</code></td>
<td>Lista não ordenada (marcadores)</td>
</tr>
<tr>
<td><code>&lt;ol&gt;</code></td>
<td>Lista ordenada (números)</td>
</tr>
<tr>
<td><code>&lt;li&gt;</code></td>
<td>Item da lista</td>
</tr>
</tbody>
</table><pre class=" language-html"><code class="prism  language-html"><span class="token comment">&lt;!-- Lista não ordenada --&gt;</span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>ul</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>li</span><span class="token punctuation">&gt;</span></span>Ração<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>li</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>li</span><span class="token punctuation">&gt;</span></span>Brinquedo<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>li</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>li</span><span class="token punctuation">&gt;</span></span>Coleira<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>li</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>ul</span><span class="token punctuation">&gt;</span></span>

<span class="token comment">&lt;!-- Lista ordenada --&gt;</span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>ol</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>li</span><span class="token punctuation">&gt;</span></span>Banho<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>li</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>li</span><span class="token punctuation">&gt;</span></span>Tosa<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>li</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>li</span><span class="token punctuation">&gt;</span></span>Secagem<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>li</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>ol</span><span class="token punctuation">&gt;</span></span>
</code></pre>
<h4 id="🔗-links-e-mídia">🔗 Links e Mídia</h4>

<table>
<thead>
<tr>
<th>Tag</th>
<th>Descrição</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>&lt;a&gt;</code></td>
<td>Link para outra página</td>
</tr>
<tr>
<td><code>&lt;img&gt;</code></td>
<td>Exibe uma imagem</td>
</tr>
<tr>
<td><code>&lt;video&gt;</code></td>
<td>Exibe um vídeo</td>
</tr>
</tbody>
</table><pre class=" language-html"><code class="prism  language-html"><span class="token comment">&lt;!-- Link --&gt;</span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>a</span> <span class="token attr-name">href</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>https://www.google.com<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>Acesse o Google<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>a</span><span class="token punctuation">&gt;</span></span>

<span class="token comment">&lt;!-- Imagem --&gt;</span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>img</span> <span class="token attr-name">src</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>cachorro.png<span class="token punctuation">"</span></span> <span class="token attr-name">alt</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>Foto de um cachorro<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>

<span class="token comment">&lt;!-- Vídeo --&gt;</span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>video</span> <span class="token attr-name">src</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>video.mp4<span class="token punctuation">"</span></span> <span class="token attr-name">controls</span><span class="token punctuation">&gt;</span></span>
    Seu navegador não suporta vídeos.
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>video</span><span class="token punctuation">&gt;</span></span>
</code></pre>
<h4 id="🧱-layout">🧱 Layout</h4>

<table>
<thead>
<tr>
<th>Tag</th>
<th>Descrição</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>&lt;div&gt;</code></td>
<td>Bloco genérico para agrupar elementos</td>
</tr>
<tr>
<td><code>&lt;header&gt;</code></td>
<td>Cabeçalho da página</td>
</tr>
<tr>
<td><code>&lt;nav&gt;</code></td>
<td>Menu de navegação</td>
</tr>
<tr>
<td><code>&lt;main&gt;</code></td>
<td>Conteúdo principal</td>
</tr>
<tr>
<td><code>&lt;section&gt;</code></td>
<td>Seção de conteúdo</td>
</tr>
<tr>
<td><code>&lt;footer&gt;</code></td>
<td>Rodapé da página</td>
</tr>
</tbody>
</table><pre class=" language-html"><code class="prism  language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>header</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>h1</span><span class="token punctuation">&gt;</span></span>🐾 PetShop<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>h1</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>header</span><span class="token punctuation">&gt;</span></span>

<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>nav</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>a</span> <span class="token attr-name">href</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>index.html<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>Início<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>a</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>a</span> <span class="token attr-name">href</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>login.html<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>Login<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>a</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>nav</span><span class="token punctuation">&gt;</span></span>

<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>main</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>section</span><span class="token punctuation">&gt;</span></span>
        <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>h2</span><span class="token punctuation">&gt;</span></span>Produtos em Destaque<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>h2</span><span class="token punctuation">&gt;</span></span>
        <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>div</span> <span class="token attr-name">class</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>container<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
            <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>p</span><span class="token punctuation">&gt;</span></span>Conteúdo agrupado aqui.<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>p</span><span class="token punctuation">&gt;</span></span>
        <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>div</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>section</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>main</span><span class="token punctuation">&gt;</span></span>

<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>footer</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>p</span><span class="token punctuation">&gt;</span></span>© 2025 PetShop. Todos os direitos reservados.<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>p</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>footer</span><span class="token punctuation">&gt;</span></span>
</code></pre>
<h4 id="📬-formulários">📬 Formulários</h4>

<table>
<thead>
<tr>
<th>Tag</th>
<th>Descrição</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>&lt;form&gt;</code></td>
<td>Agrupa elementos de um formulário</td>
</tr>
<tr>
<td><code>&lt;input&gt;</code></td>
<td>Campo de entrada de dados</td>
</tr>
<tr>
<td><code>&lt;button&gt;</code></td>
<td>Botão clicável</td>
</tr>
<tr>
<td><code>&lt;select&gt;</code></td>
<td>Lista suspensa de opções</td>
</tr>
<tr>
<td><code>&lt;textarea&gt;</code></td>
<td>Campo de texto longo</td>
</tr>
</tbody>
</table><pre class=" language-html"><code class="prism  language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>form</span><span class="token punctuation">&gt;</span></span>
    <span class="token comment">&lt;!-- Campos de input --&gt;</span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>input</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>text<span class="token punctuation">"</span></span> <span class="token attr-name">placeholder</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>Nome completo<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>input</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>email<span class="token punctuation">"</span></span> <span class="token attr-name">placeholder</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>seu@email.com<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>input</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>password<span class="token punctuation">"</span></span> <span class="token attr-name">placeholder</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>••••••••<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>

    <span class="token comment">&lt;!-- Lista suspensa --&gt;</span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>select</span><span class="token punctuation">&gt;</span></span>
        <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>option</span> <span class="token attr-name">value</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>cachorro<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>Cachorro<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>option</span><span class="token punctuation">&gt;</span></span>
        <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>option</span> <span class="token attr-name">value</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>gato<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>Gato<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>option</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>select</span><span class="token punctuation">&gt;</span></span>

    <span class="token comment">&lt;!-- Texto longo --&gt;</span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>textarea</span> <span class="token attr-name">rows</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>4<span class="token punctuation">"</span></span> <span class="token attr-name">placeholder</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>Escreva uma descrição...<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>textarea</span><span class="token punctuation">&gt;</span></span>

    <span class="token comment">&lt;!-- Botão --&gt;</span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>button</span> <span class="token attr-name">onclick</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>salvar()<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>Salvar<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>button</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>form</span><span class="token punctuation">&gt;</span></span>
</code></pre>
<hr>
<h3 id="✅-boas-práticas-de-html">✅ Boas práticas de HTML</h3>
<ul>
<li>Sempre declarar <code>&lt;!DOCTYPE html&gt;</code> no início do documento</li>
<li>Usar o atributo <code>lang</code> na tag <code>&lt;html&gt;</code> para indicar o idioma</li>
<li>Usar o atributo <code>alt</code> em todas as imagens para acessibilidade</li>
<li>Usar tags semânticas (<code>&lt;header&gt;</code>, <code>&lt;nav&gt;</code>, <code>&lt;main&gt;</code>, <code>&lt;footer&gt;</code>) em vez de <code>&lt;div&gt;</code> para tudo</li>
<li>Indentar o código corretamente para facilitar a leitura</li>
<li>Sempre fechar as tags que possuem fechamento</li>
</ul>
<hr>
<h2 id="🔵-css-—-cascading-style-sheets">🔵 CSS — Cascading Style Sheets</h2>
<h3 id="o-que-é-css">O que é CSS?</h3>
<p>CSS (Cascading Style Sheets) é a linguagem utilizada para estilizar páginas web, controlando cores, fontes, espaçamentos, layouts e a aparência geral dos elementos HTML.</p>
<h3 id="como-funciona-1">Como funciona?</h3>
<p>O CSS funciona através de <strong>seletores</strong> que apontam para elementos HTML e <strong>propriedades</strong> que definem o estilo aplicado.</p>
<pre class=" language-css"><code class="prism  language-css"><span class="token comment">/* Estrutura básica do CSS */</span>
<span class="token selector">seletor </span><span class="token punctuation">{</span>
    <span class="token property">propriedade</span><span class="token punctuation">:</span> valor<span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token comment">/* Exemplo */</span>
<span class="token selector">p </span><span class="token punctuation">{</span>
    <span class="token property">color</span><span class="token punctuation">:</span> red<span class="token punctuation">;</span>
    <span class="token property">font-size</span><span class="token punctuation">:</span> <span class="token number">16</span>px<span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<h3 id="formas-de-aplicar-css">Formas de aplicar CSS</h3>
<pre class=" language-html"><code class="prism  language-html"><span class="token comment">&lt;!-- 1. Inline — diretamente no elemento (evitar) --&gt;</span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>p</span><span class="token style-attr language-css"><span class="token attr-name"> <span class="token attr-name">style</span></span><span class="token punctuation">="</span><span class="token attr-value"><span class="token property">color</span><span class="token punctuation">:</span> red<span class="token punctuation">;</span></span><span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>Texto vermelho<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>p</span><span class="token punctuation">&gt;</span></span>

<span class="token comment">&lt;!-- 2. Interno — dentro do &lt;head&gt; --&gt;</span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>head</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>style</span><span class="token punctuation">&gt;</span></span><span class="token style language-css">
        <span class="token selector">p </span><span class="token punctuation">{</span> <span class="token property">color</span><span class="token punctuation">:</span> red<span class="token punctuation">;</span> <span class="token punctuation">}</span>
    </span><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>style</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>head</span><span class="token punctuation">&gt;</span></span>

<span class="token comment">&lt;!-- 3. Externo — arquivo separado (boa prática) --&gt;</span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>head</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>link</span> <span class="token attr-name">rel</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>stylesheet<span class="token punctuation">"</span></span> <span class="token attr-name">href</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>css/style.css<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>head</span><span class="token punctuation">&gt;</span></span>
</code></pre>
<hr>
<h3 id="principais-seletores">Principais seletores</h3>
<pre class=" language-css"><code class="prism  language-css"><span class="token comment">/* Seletor de tag — aplica a todos os elementos da tag */</span>
<span class="token selector">p </span><span class="token punctuation">{</span> <span class="token property">color</span><span class="token punctuation">:</span> black<span class="token punctuation">;</span> <span class="token punctuation">}</span>

<span class="token comment">/* Seletor de classe — aplica a elementos com a classe */</span>
<span class="token selector"><span class="token class">.card</span> </span><span class="token punctuation">{</span> <span class="token property">border-radius</span><span class="token punctuation">:</span> <span class="token number">8</span>px<span class="token punctuation">;</span> <span class="token punctuation">}</span>

<span class="token comment">/* Seletor de ID — aplica a um elemento único */</span>
<span class="token selector"><span class="token id">#titulo</span> </span><span class="token punctuation">{</span> <span class="token property">font-size</span><span class="token punctuation">:</span> <span class="token number">32</span>px<span class="token punctuation">;</span> <span class="token punctuation">}</span>

<span class="token comment">/* Seletor descendente — elementos dentro de outros */</span>
<span class="token selector"><span class="token class">.card</span> p </span><span class="token punctuation">{</span> <span class="token property">color</span><span class="token punctuation">:</span> gray<span class="token punctuation">;</span> <span class="token punctuation">}</span>

<span class="token comment">/* Seletor de múltiplos elementos */</span>
<span class="token selector">h1, h2, h3 </span><span class="token punctuation">{</span> <span class="token property">font-weight</span><span class="token punctuation">:</span> bold<span class="token punctuation">;</span> <span class="token punctuation">}</span>
</code></pre>
<hr>
<h3 id="propriedades-essenciais">Propriedades essenciais</h3>
<h4 id="tipografia">Tipografia</h4>
<pre class=" language-css"><code class="prism  language-css"><span class="token selector">p </span><span class="token punctuation">{</span>
    <span class="token property">color</span><span class="token punctuation">:</span> <span class="token hexcode">#333</span><span class="token punctuation">;</span>                        <span class="token comment">/* Cor do texto */</span>
    <span class="token property">font-size</span><span class="token punctuation">:</span> <span class="token number">16</span>px<span class="token punctuation">;</span>                    <span class="token comment">/* Tamanho da fonte */</span>
    <span class="token property">font-family</span><span class="token punctuation">:</span> <span class="token string">'Segoe UI'</span>, sans-serif<span class="token punctuation">;</span><span class="token comment">/* Tipo da fonte */</span>
    <span class="token property">font-weight</span><span class="token punctuation">:</span> bold<span class="token punctuation">;</span>                  <span class="token comment">/* Peso da fonte */</span>
    <span class="token property">text-align</span><span class="token punctuation">:</span> center<span class="token punctuation">;</span>                 <span class="token comment">/* Alinhamento do texto */</span>
    <span class="token property">line-height</span><span class="token punctuation">:</span> <span class="token number">1.5</span><span class="token punctuation">;</span>                   <span class="token comment">/* Espaçamento entre linhas */</span>
<span class="token punctuation">}</span>
</code></pre>
<h4 id="espaçamento">Espaçamento</h4>
<pre class=" language-css"><code class="prism  language-css"><span class="token selector">div </span><span class="token punctuation">{</span>
    <span class="token property">margin</span><span class="token punctuation">:</span> <span class="token number">16</span>px<span class="token punctuation">;</span>       <span class="token comment">/* Espaçamento externo */</span>
    <span class="token property">padding</span><span class="token punctuation">:</span> <span class="token number">16</span>px<span class="token punctuation">;</span>      <span class="token comment">/* Espaçamento interno */</span>

    <span class="token comment">/* Lados específicos */</span>
    <span class="token property">margin-top</span><span class="token punctuation">:</span> <span class="token number">8</span>px<span class="token punctuation">;</span>
    <span class="token property">padding-left</span><span class="token punctuation">:</span> <span class="token number">12</span>px<span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<h4 id="dimensões-e-bordas">Dimensões e bordas</h4>
<pre class=" language-css"><code class="prism  language-css"><span class="token selector">img </span><span class="token punctuation">{</span>
    <span class="token property">width</span><span class="token punctuation">:</span> <span class="token number">100%</span><span class="token punctuation">;</span>            <span class="token comment">/* Largura */</span>
    <span class="token property">height</span><span class="token punctuation">:</span> <span class="token number">180</span>px<span class="token punctuation">;</span>          <span class="token comment">/* Altura */</span>
    <span class="token property">border</span><span class="token punctuation">:</span> <span class="token number">1</span>px solid <span class="token hexcode">#ccc</span><span class="token punctuation">;</span> <span class="token comment">/* Borda */</span>
    <span class="token property">border-radius</span><span class="token punctuation">:</span> <span class="token number">8</span>px<span class="token punctuation">;</span>     <span class="token comment">/* Arredondar bordas */</span>
    <span class="token property">box-shadow</span><span class="token punctuation">:</span> <span class="token number">0</span> <span class="token number">4</span>px <span class="token number">8</span>px <span class="token function">rgba</span><span class="token punctuation">(</span><span class="token number">0</span>, <span class="token number">0</span>, <span class="token number">0</span>, <span class="token number">0.1</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">/* Sombra */</span>
<span class="token punctuation">}</span>
</code></pre>
<h4 id="display-e-flexbox">Display e Flexbox</h4>
<pre class=" language-css"><code class="prism  language-css"><span class="token comment">/* Flexbox — alinhamento em linha ou coluna */</span>
<span class="token selector"><span class="token class">.container</span> </span><span class="token punctuation">{</span>
    <span class="token property">display</span><span class="token punctuation">:</span> flex<span class="token punctuation">;</span>
    <span class="token property">flex-direction</span><span class="token punctuation">:</span> row<span class="token punctuation">;</span>        <span class="token comment">/* Direção: row ou column */</span>
    <span class="token property">justify-content</span><span class="token punctuation">:</span> center<span class="token punctuation">;</span>    <span class="token comment">/* Alinhamento horizontal */</span>
    <span class="token property">align-items</span><span class="token punctuation">:</span> center<span class="token punctuation">;</span>        <span class="token comment">/* Alinhamento vertical */</span>
    <span class="token property">gap</span><span class="token punctuation">:</span> <span class="token number">16</span>px<span class="token punctuation">;</span>                  <span class="token comment">/* Espaço entre os filhos */</span>
    <span class="token property">flex-wrap</span><span class="token punctuation">:</span> wrap<span class="token punctuation">;</span>            <span class="token comment">/* Quebra de linha automática */</span>
<span class="token punctuation">}</span>
</code></pre>
<h4 id="grid">Grid</h4>
<pre class=" language-css"><code class="prism  language-css"><span class="token comment">/* Grid — layout em linhas e colunas */</span>
<span class="token selector"><span class="token class">.grid</span> </span><span class="token punctuation">{</span>
    <span class="token property">display</span><span class="token punctuation">:</span> grid<span class="token punctuation">;</span>
    <span class="token property">grid-template-columns</span><span class="token punctuation">:</span> <span class="token function">repeat</span><span class="token punctuation">(</span><span class="token number">3</span>, <span class="token number">1</span>fr<span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">/* 3 colunas iguais */</span>
    <span class="token property">gap</span><span class="token punctuation">:</span> <span class="token number">16</span>px<span class="token punctuation">;</span>                              <span class="token comment">/* Espaço entre células */</span>
<span class="token punctuation">}</span>
</code></pre>
<h4 id="responsividade">Responsividade</h4>
<pre class=" language-css"><code class="prism  language-css"><span class="token comment">/* Media Query — adapta o layout para telas menores */</span>
<span class="token atrule"><span class="token rule">@media</span> <span class="token punctuation">(</span><span class="token property">max-width</span><span class="token punctuation">:</span> 576px<span class="token punctuation">)</span></span> <span class="token punctuation">{</span>
    <span class="token selector">h1 </span><span class="token punctuation">{</span>
        <span class="token property">font-size</span><span class="token punctuation">:</span> <span class="token number">1.4</span>rem<span class="token punctuation">;</span>
    <span class="token punctuation">}</span>

    <span class="token selector"><span class="token class">.card-img-top</span> </span><span class="token punctuation">{</span>
        <span class="token property">height</span><span class="token punctuation">:</span> <span class="token number">140</span>px<span class="token punctuation">;</span>
    <span class="token punctuation">}</span>
<span class="token punctuation">}</span>
</code></pre>
<hr>
<h3 id="✅-boas-práticas-de-css">✅ Boas práticas de CSS</h3>
<ul>
<li>Sempre usar arquivo CSS externo em vez de estilos inline</li>
<li>Usar classes em vez de IDs para estilização (IDs são para JS)</li>
<li>Nomear classes de forma descritiva (ex: <code>.card-produto</code> em vez de <code>.cp</code>)</li>
<li>Organizar o CSS por seções com comentários</li>
<li>Usar variáveis CSS para cores e tamanhos repetidos</li>
<li>Sempre testar a responsividade em diferentes tamanhos de tela</li>
</ul>
<pre class=" language-css"><code class="prism  language-css"><span class="token comment">/* Exemplo de variáveis CSS */</span>
<span class="token selector"><span class="token pseudo-class">:root</span> </span><span class="token punctuation">{</span>
    <span class="token property">--cor-primaria</span><span class="token punctuation">:</span> <span class="token hexcode">#0d6efd</span><span class="token punctuation">;</span>
    <span class="token property">--cor-texto</span><span class="token punctuation">:</span> <span class="token hexcode">#333</span><span class="token punctuation">;</span>
    <span class="token property">--borda-arredondada</span><span class="token punctuation">:</span> <span class="token number">8</span>px<span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token selector"><span class="token class">.btn</span> </span><span class="token punctuation">{</span>
    <span class="token property">background-color</span><span class="token punctuation">:</span> <span class="token function">var</span><span class="token punctuation">(</span>--cor-primaria<span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token property">border-radius</span><span class="token punctuation">:</span> <span class="token function">var</span><span class="token punctuation">(</span>--borda-arredondada<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<hr>
<h2 id="🟡-javascript">🟡 JavaScript</h2>
<h3 id="o-que-é-javascript">O que é JavaScript?</h3>
<p>JavaScript é a linguagem de programação da web, responsável por adicionar interatividade e dinamismo às páginas. Com ela é possível manipular elementos HTML, responder a ações do usuário, validar formulários e se comunicar com bancos de dados.</p>
<h3 id="como-funciona-2">Como funciona?</h3>
<p>O JavaScript é executado diretamente no navegador e pode ser incluído no HTML de duas formas:</p>
<pre class=" language-html"><code class="prism  language-html"><span class="token comment">&lt;!-- Interno --&gt;</span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>script</span><span class="token punctuation">&gt;</span></span><span class="token script language-javascript">
    <span class="token function">alert</span><span class="token punctuation">(</span><span class="token string">'Olá, mundo!'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</span><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>script</span><span class="token punctuation">&gt;</span></span>

<span class="token comment">&lt;!-- Externo (boa prática) --&gt;</span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>script</span> <span class="token attr-name">src</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>js/main.js<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span><span class="token script language-javascript"></span><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>script</span><span class="token punctuation">&gt;</span></span>
</code></pre>
<hr>
<h3 id="variáveis">Variáveis</h3>
<pre class=" language-javascript"><code class="prism  language-javascript"><span class="token comment">// var — escopo global (evitar uso moderno)</span>
<span class="token keyword">var</span> nome <span class="token operator">=</span> <span class="token string">'Felipe'</span><span class="token punctuation">;</span>

<span class="token comment">// let — escopo de bloco, valor pode mudar</span>
<span class="token keyword">let</span> idade <span class="token operator">=</span> <span class="token number">20</span><span class="token punctuation">;</span>

<span class="token comment">// const — escopo de bloco, valor não pode ser reatribuído</span>
<span class="token keyword">const</span> pi <span class="token operator">=</span> <span class="token number">3.14</span><span class="token punctuation">;</span>
</code></pre>
<hr>
<h3 id="funções">Funções</h3>
<pre class=" language-javascript"><code class="prism  language-javascript"><span class="token comment">// Função tradicional</span>
<span class="token keyword">function</span> <span class="token function">somar</span><span class="token punctuation">(</span>a<span class="token punctuation">,</span> b<span class="token punctuation">)</span> <span class="token punctuation">{</span>
    <span class="token keyword">return</span> a <span class="token operator">+</span> b<span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token comment">// Arrow function (função de seta)</span>
<span class="token keyword">const</span> <span class="token function-variable function">multiplicar</span> <span class="token operator">=</span> <span class="token punctuation">(</span>a<span class="token punctuation">,</span> b<span class="token punctuation">)</span> <span class="token operator">=&gt;</span> a <span class="token operator">*</span> b<span class="token punctuation">;</span>

<span class="token comment">// Função assíncrona — usada para operações com banco de dados</span>
<span class="token keyword">async</span> <span class="token keyword">function</span> <span class="token function">buscarDados</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
    <span class="token keyword">const</span> resultado <span class="token operator">=</span> <span class="token keyword">await</span> <span class="token function">fetch</span><span class="token punctuation">(</span><span class="token string">'https://api.exemplo.com/dados'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">return</span> resultado<span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<hr>
<h3 id="condicionais-e-loops">Condicionais e Loops</h3>
<pre class=" language-javascript"><code class="prism  language-javascript"><span class="token comment">// If / else</span>
<span class="token keyword">if</span> <span class="token punctuation">(</span>idade <span class="token operator">&gt;=</span> <span class="token number">18</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">'Maior de idade'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span> <span class="token keyword">else</span> <span class="token punctuation">{</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">'Menor de idade'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token comment">// Loop for</span>
<span class="token keyword">for</span> <span class="token punctuation">(</span><span class="token keyword">let</span> i <span class="token operator">=</span> <span class="token number">0</span><span class="token punctuation">;</span> i <span class="token operator">&lt;</span> <span class="token number">5</span><span class="token punctuation">;</span> i<span class="token operator">++</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>i<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token comment">// Loop forEach — percorre arrays</span>
<span class="token keyword">const</span> produtos <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token string">'Ração'</span><span class="token punctuation">,</span> <span class="token string">'Brinquedo'</span><span class="token punctuation">,</span> <span class="token string">'Coleira'</span><span class="token punctuation">]</span><span class="token punctuation">;</span>
produtos<span class="token punctuation">.</span><span class="token function">forEach</span><span class="token punctuation">(</span>produto <span class="token operator">=&gt;</span> <span class="token punctuation">{</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>produto<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<hr>
<h3 id="manipulação-do-dom">Manipulação do DOM</h3>
<pre class=" language-javascript"><code class="prism  language-javascript"><span class="token comment">// Selecionar elementos</span>
<span class="token keyword">const</span> titulo <span class="token operator">=</span> document<span class="token punctuation">.</span><span class="token function">getElementById</span><span class="token punctuation">(</span><span class="token string">'titulo'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token keyword">const</span> botoes <span class="token operator">=</span> document<span class="token punctuation">.</span><span class="token function">querySelectorAll</span><span class="token punctuation">(</span><span class="token string">'.btn'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>

<span class="token comment">// Alterar conteúdo</span>
titulo<span class="token punctuation">.</span>textContent <span class="token operator">=</span> <span class="token string">'Novo título'</span><span class="token punctuation">;</span>
titulo<span class="token punctuation">.</span>innerHTML <span class="token operator">=</span> <span class="token string">'&lt;strong&gt;Título em negrito&lt;/strong&gt;'</span><span class="token punctuation">;</span>

<span class="token comment">// Alterar estilo</span>
titulo<span class="token punctuation">.</span>style<span class="token punctuation">.</span>color <span class="token operator">=</span> <span class="token string">'red'</span><span class="token punctuation">;</span>

<span class="token comment">// Adicionar e remover classes</span>
titulo<span class="token punctuation">.</span>classList<span class="token punctuation">.</span><span class="token function">add</span><span class="token punctuation">(</span><span class="token string">'destaque'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
titulo<span class="token punctuation">.</span>classList<span class="token punctuation">.</span><span class="token function">remove</span><span class="token punctuation">(</span><span class="token string">'destaque'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>

<span class="token comment">// Criar e inserir elemento</span>
<span class="token keyword">const</span> novoItem <span class="token operator">=</span> document<span class="token punctuation">.</span><span class="token function">createElement</span><span class="token punctuation">(</span><span class="token string">'li'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
novoItem<span class="token punctuation">.</span>textContent <span class="token operator">=</span> <span class="token string">'Novo produto'</span><span class="token punctuation">;</span>
document<span class="token punctuation">.</span><span class="token function">getElementById</span><span class="token punctuation">(</span><span class="token string">'lista'</span><span class="token punctuation">)</span><span class="token punctuation">.</span><span class="token function">appendChild</span><span class="token punctuation">(</span>novoItem<span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<hr>
<h3 id="eventos">Eventos</h3>
<pre class=" language-javascript"><code class="prism  language-javascript"><span class="token comment">// Clique em botão</span>
document<span class="token punctuation">.</span><span class="token function">getElementById</span><span class="token punctuation">(</span><span class="token string">'btn'</span><span class="token punctuation">)</span><span class="token punctuation">.</span><span class="token function">addEventListener</span><span class="token punctuation">(</span><span class="token string">'click'</span><span class="token punctuation">,</span> <span class="token keyword">function</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
    <span class="token function">alert</span><span class="token punctuation">(</span><span class="token string">'Botão clicado!'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span><span class="token punctuation">)</span><span class="token punctuation">;</span>

<span class="token comment">// Evento de input — ao digitar</span>
document<span class="token punctuation">.</span><span class="token function">getElementById</span><span class="token punctuation">(</span><span class="token string">'campo'</span><span class="token punctuation">)</span><span class="token punctuation">.</span><span class="token function">addEventListener</span><span class="token punctuation">(</span><span class="token string">'input'</span><span class="token punctuation">,</span> <span class="token keyword">function</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token keyword">this</span><span class="token punctuation">.</span>value<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span><span class="token punctuation">)</span><span class="token punctuation">;</span>

<span class="token comment">// Evento ao carregar a página</span>
window<span class="token punctuation">.</span><span class="token function">addEventListener</span><span class="token punctuation">(</span><span class="token string">'load'</span><span class="token punctuation">,</span> <span class="token keyword">function</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">'Página carregada!'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<hr>
<h3 id="exemplo-prático-—-validação-de-formulário">Exemplo prático — Validação de formulário</h3>
<pre class=" language-javascript"><code class="prism  language-javascript"><span class="token keyword">function</span> <span class="token function">validarLogin</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
    <span class="token comment">// Pega os valores dos campos</span>
    <span class="token keyword">const</span> email <span class="token operator">=</span> document<span class="token punctuation">.</span><span class="token function">getElementById</span><span class="token punctuation">(</span><span class="token string">'email'</span><span class="token punctuation">)</span><span class="token punctuation">.</span>value<span class="token punctuation">.</span><span class="token function">trim</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">const</span> senha <span class="token operator">=</span> document<span class="token punctuation">.</span><span class="token function">getElementById</span><span class="token punctuation">(</span><span class="token string">'senha'</span><span class="token punctuation">)</span><span class="token punctuation">.</span>value<span class="token punctuation">.</span><span class="token function">trim</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">const</span> mensagem <span class="token operator">=</span> document<span class="token punctuation">.</span><span class="token function">getElementById</span><span class="token punctuation">(</span><span class="token string">'mensagem'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>

    <span class="token comment">// Valida se os campos estão preenchidos</span>
    <span class="token keyword">if</span> <span class="token punctuation">(</span><span class="token operator">!</span>email <span class="token operator">||</span> <span class="token operator">!</span>senha<span class="token punctuation">)</span> <span class="token punctuation">{</span>
        mensagem<span class="token punctuation">.</span>textContent <span class="token operator">=</span> <span class="token string">'Preencha todos os campos.'</span><span class="token punctuation">;</span>
        mensagem<span class="token punctuation">.</span>classList<span class="token punctuation">.</span><span class="token function">remove</span><span class="token punctuation">(</span><span class="token string">'d-none'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
        <span class="token keyword">return</span><span class="token punctuation">;</span>
    <span class="token punctuation">}</span>

    <span class="token comment">// Valida formato do e-mail</span>
    <span class="token keyword">if</span> <span class="token punctuation">(</span><span class="token operator">!</span>email<span class="token punctuation">.</span><span class="token function">includes</span><span class="token punctuation">(</span><span class="token string">'@'</span><span class="token punctuation">)</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
        mensagem<span class="token punctuation">.</span>textContent <span class="token operator">=</span> <span class="token string">'E-mail inválido.'</span><span class="token punctuation">;</span>
        mensagem<span class="token punctuation">.</span>classList<span class="token punctuation">.</span><span class="token function">remove</span><span class="token punctuation">(</span><span class="token string">'d-none'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
        <span class="token keyword">return</span><span class="token punctuation">;</span>
    <span class="token punctuation">}</span>

    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">'Login válido!'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<hr>
<h3 id="✅-boas-práticas-de-javascript">✅ Boas práticas de JavaScript</h3>
<ul>
<li>Usar <code>const</code> por padrão e <code>let</code> quando o valor precisar mudar — evitar <code>var</code></li>
<li>Nomear variáveis e funções de forma descritiva</li>
<li>Usar <code>async/await</code> para operações assíncronas</li>
<li>Separar o JavaScript em arquivos organizados por responsabilidade</li>
<li>Sempre tratar erros com <code>try/catch</code></li>
<li>Comentar trechos complexos do código</li>
</ul>
<hr>
<h2 id="🌐-outros-conceitos">🌐 Outros Conceitos</h2>
<h3 id="o-que-é-a-internet">O que é a Internet?</h3>
<p>A internet é uma rede global de computadores interconectados que se comunicam através de protocolos padronizados. Quando acessamos um site, o navegador envia uma requisição a um servidor, que responde com os arquivos HTML, CSS e JavaScript que formam a página.</p>
<pre><code>Usuário → Navegador → Requisição HTTP → Servidor → Resposta → Página exibida
</code></pre>
<hr>
<h3 id="o-que-é-pwa">O que é PWA?</h3>
<p>PWA (Progressive Web App) é uma tecnologia que permite que sites se comportem como aplicativos nativos no celular, podendo ser instalados na tela inicial, funcionar offline e enviar notificações.</p>
<pre class=" language-json"><code class="prism  language-json"><span class="token comment">// manifest.json — configura o PWA</span>
<span class="token punctuation">{</span>
    <span class="token string">"name"</span><span class="token punctuation">:</span> <span class="token string">"PetShop"</span><span class="token punctuation">,</span>
    <span class="token string">"short_name"</span><span class="token punctuation">:</span> <span class="token string">"PetShop"</span><span class="token punctuation">,</span>
    <span class="token string">"start_url"</span><span class="token punctuation">:</span> <span class="token string">"/index.html"</span><span class="token punctuation">,</span>
    <span class="token string">"display"</span><span class="token punctuation">:</span> <span class="token string">"standalone"</span><span class="token punctuation">,</span>
    <span class="token string">"background_color"</span><span class="token punctuation">:</span> <span class="token string">"#ffffff"</span><span class="token punctuation">,</span>
    <span class="token string">"theme_color"</span><span class="token punctuation">:</span> <span class="token string">"#0d6efd"</span><span class="token punctuation">,</span>
    <span class="token string">"icons"</span><span class="token punctuation">:</span> <span class="token punctuation">[</span>
        <span class="token punctuation">{</span>
            <span class="token string">"src"</span><span class="token punctuation">:</span> <span class="token string">"img/icone.png"</span><span class="token punctuation">,</span>
            <span class="token string">"sizes"</span><span class="token punctuation">:</span> <span class="token string">"192x192"</span><span class="token punctuation">,</span>
            <span class="token string">"type"</span><span class="token punctuation">:</span> <span class="token string">"image/png"</span>
        <span class="token punctuation">}</span>
    <span class="token punctuation">]</span>
<span class="token punctuation">}</span>
</code></pre>
<hr>
<h3 id="o-que-é-banco-de-dados-em-cache">O que é Banco de Dados em Cache?</h3>
<p>Bancos de dados em cache armazenam dados diretamente no navegador do usuário, permitindo que a aplicação funcione sem conexão com a internet. Um exemplo é o <strong>PouchDB</strong>, que salva os dados no IndexedDB do navegador.</p>
<pre class=" language-javascript"><code class="prism  language-javascript"><span class="token comment">// Criando um banco local com PouchDB</span>
<span class="token keyword">const</span> db <span class="token operator">=</span> <span class="token keyword">new</span> <span class="token class-name">PouchDB</span><span class="token punctuation">(</span><span class="token string">'petshop'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>

<span class="token comment">// Salvando um documento</span>
<span class="token keyword">await</span> db<span class="token punctuation">.</span><span class="token function">put</span><span class="token punctuation">(</span><span class="token punctuation">{</span>
    _id<span class="token punctuation">:</span> <span class="token string">'001'</span><span class="token punctuation">,</span>
    nome<span class="token punctuation">:</span> <span class="token string">'Ração Premium'</span><span class="token punctuation">,</span>
    preco<span class="token punctuation">:</span> <span class="token number">89.90</span>
<span class="token punctuation">}</span><span class="token punctuation">)</span><span class="token punctuation">;</span>

<span class="token comment">// Buscando um documento</span>
<span class="token keyword">const</span> produto <span class="token operator">=</span> <span class="token keyword">await</span> db<span class="token punctuation">.</span><span class="token keyword">get</span><span class="token punctuation">(</span><span class="token string">'001'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>produto<span class="token punctuation">.</span>nome<span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// Ração Premium</span>
</code></pre>
<hr>
<h3 id="o-que-é-http-e-https">O que é HTTP e HTTPS?</h3>
<ul>
<li><strong>HTTP</strong> (HyperText Transfer Protocol) — protocolo de comunicação entre navegador e servidor</li>
<li><strong>HTTPS</strong> — versão segura do HTTP, com criptografia SSL/TLS que protege os dados trafegados</li>
</ul>
<hr>
<h3 id="o-que-é-responsividade">O que é Responsividade?</h3>
<p>Responsividade é a capacidade de um site se adaptar a diferentes tamanhos de tela, como celulares, tablets e desktops, proporcionando uma boa experiência em qualquer dispositivo.</p>
<pre class=" language-css"><code class="prism  language-css"><span class="token comment">/* Exemplo de layout responsivo com media query */</span>
<span class="token selector"><span class="token class">.container</span> </span><span class="token punctuation">{</span>
    <span class="token property">display</span><span class="token punctuation">:</span> grid<span class="token punctuation">;</span>
    <span class="token property">grid-template-columns</span><span class="token punctuation">:</span> <span class="token function">repeat</span><span class="token punctuation">(</span><span class="token number">4</span>, <span class="token number">1</span>fr<span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">/* 4 colunas no desktop */</span>
<span class="token punctuation">}</span>

<span class="token atrule"><span class="token rule">@media</span> <span class="token punctuation">(</span><span class="token property">max-width</span><span class="token punctuation">:</span> 768px<span class="token punctuation">)</span></span> <span class="token punctuation">{</span>
    <span class="token selector"><span class="token class">.container</span> </span><span class="token punctuation">{</span>
        <span class="token property">grid-template-columns</span><span class="token punctuation">:</span> <span class="token function">repeat</span><span class="token punctuation">(</span><span class="token number">2</span>, <span class="token number">1</span>fr<span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">/* 2 colunas no tablet */</span>
    <span class="token punctuation">}</span>
<span class="token punctuation">}</span>

<span class="token atrule"><span class="token rule">@media</span> <span class="token punctuation">(</span><span class="token property">max-width</span><span class="token punctuation">:</span> 576px<span class="token punctuation">)</span></span> <span class="token punctuation">{</span>
    <span class="token selector"><span class="token class">.container</span> </span><span class="token punctuation">{</span>
        <span class="token property">grid-template-columns</span><span class="token punctuation">:</span> <span class="token number">1</span>fr<span class="token punctuation">;</span> <span class="token comment">/* 1 coluna no celular */</span>
    <span class="token punctuation">}</span>
<span class="token punctuation">}</span>
</code></pre>
<hr>

