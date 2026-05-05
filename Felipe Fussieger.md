---


---

<h1 id="bem-vindo-a-documentação-de-boas-práticas-para-desenvolvimento-web">Bem-vindo a documentação de boas práticas para Desenvolvimento Web!</h1>
<p>Este arquivo tem com intuito de documentar exemplos de utilização e boas práticas de HTML, CSS, JavaScript e outros… Aproveite seus estudos, boa sorte!</p>
<h1 id="o-que-é-html">O que é HTML?</h1>
<p>HyperText Markup Language (HTML) é uma linguagem de marcação padrão utilizada mundialmente para estruturar e organizar conteúdos de páginas web, definindo elementos como textos, imagens, links e outros componentes exibidos nos navegadores.</p>
<p>Um exemplo básico é a utilização das tags de título vão de <code>&lt;h1&gt;</code> a <code>&lt;h6&gt;</code>, onde <code>&lt;h1&gt;</code> representa o título de maior destaque e tamanho, e <code>&lt;h6&gt;</code> o de menor destaque e tamanho:</p>
<pre><code>&lt;h1&gt;Olá mundo!&lt;/h1&gt; // Maior destaque e tamanho
&lt;h6&gt;Olá mundo!&lt;/h6&gt; // Menor destaque e tamanho
</code></pre>
<p>Abaixo há outras tags comúns utilizadas separada por tópicos:</p>
<h3 id="estrutura">Estrutura</h3>
<p><code>&lt;html&gt;</code> — elemento raiz que envolve toda a página:</p>
<pre><code> &lt;html lang="pt-BR"&gt;
    ...
&lt;/html&gt;
</code></pre>
<p><code>&lt;head&gt;</code> — informações da página não visíveis ao usuário:</p>
<pre><code>&lt;head&gt;
    &lt;title&gt;Minha Página&lt;/title&gt;
&lt;/head&gt;
</code></pre>
<p><code>&lt;body&gt;</code> — todo o conteúdo visível da página:</p>
<pre><code>  &lt;body&gt;
		       &lt;h1&gt;Olá, mundo!&lt;/h1&gt;
     &lt;/body&gt;
</code></pre>
<h3 id="títulos-e-texto">Títulos e Texto</h3>
<p><code>&lt;h1&gt;</code> a <code>&lt;h6&gt;</code> — títulos do maior ao menor destaque:</p>
<pre><code>&lt;h1&gt;Título principal&lt;/h1&gt;
&lt;h2&gt;Subtítulo&lt;/h2&gt;
&lt;h6&gt;Título menor&lt;/h6&gt;
</code></pre>
<p><code>&lt;p&gt;</code> — parágrafo de texto:</p>
<pre><code>&lt;p&gt;Este é um parágrafo de exemplo.&lt;/p&gt;
</code></pre>
<p><code>&lt;strong&gt;</code> — texto em negrito com ênfase semântica:</p>
<pre><code>&lt;p&gt;&lt;strong&gt;Atenção:&lt;/strong&gt; leia as instruções.&lt;/p&gt;
</code></pre>
<h3 id="listas">Listas</h3>
<p><code>&lt;ul&gt;</code> — lista não ordenada com marcadores:</p>
<pre><code>&lt;ul&gt;
&lt;li&gt;Ração&lt;/li&gt;
&lt;li&gt;Brinquedo&lt;/li&gt;
&lt;li&gt;Coleira&lt;/li&gt;
&lt;/ul&gt;
</code></pre>
<p><code>&lt;ol&gt;</code> — lista ordenada com números:</p>
<pre><code>&lt;ol&gt;
&lt;li&gt;Banho&lt;/li&gt;
&lt;li&gt;Tosa&lt;/li&gt;
&lt;li&gt;Secagem&lt;/li&gt;
&lt;/ol&gt;
</code></pre>
<p><code>&lt;li&gt;</code> — item pertencente a uma lista <code>&lt;ul&gt;</code> ou <code>&lt;ol&gt;</code>:</p>
<pre><code>&lt;ul&gt;
&lt;li&gt;Item 1&lt;/li&gt;
&lt;li&gt;Item 2&lt;/li&gt;
&lt;/ul&gt;
</code></pre>
<h3 id="links-e-mídia">Links e mídia</h3>
<p><code>&lt;a&gt;</code> — link para outra página ou endereço:</p>
<pre><code>  &lt;a href="https://www.google.com"&gt;Acesse o Google&lt;/a&gt;
</code></pre>
<p><code>&lt;img&gt;</code> — exibe uma imagem na página:</p>
<pre><code>&lt;img src="cachorro.png" alt="Foto de um cachorro"&gt;
</code></pre>
<p><code>&lt;video&gt;</code> — exibe um vídeo na página:</p>
<pre><code>&lt;video src="video.mp4" controls&gt;
Seu navegador não suporta vídeos.
&lt;/video&gt;
</code></pre>
<h3 id="estrutura-de-layout">Estrutura de layout</h3>
<p><code>&lt;div&gt;</code> — bloco genérico para agrupar elementos:</p>
<pre><code>&lt;div class="container"&gt;
&lt;p&gt;Conteúdo agrupado aqui.&lt;/p&gt;
&lt;/div&gt;
</code></pre>
<p><code>&lt;header&gt;</code> — cabeçalho da página:</p>
<pre><code>&lt;header&gt;
    &lt;h1&gt;PetShop&lt;/h1&gt;
&lt;/header&gt;
</code></pre>
<p><code>&lt;nav&gt;</code> — menu de navegação:</p>
<pre><code>&lt;nav&gt;
    &lt;a href="index.html"&gt;Início&lt;/a&gt;
    &lt;a href="login.html"&gt;Login&lt;/a&gt;
&lt;/nav&gt;
</code></pre>
<p><code>&lt;main&gt;</code> — conteúdo principal da página:</p>
<pre><code>&lt;main&gt;
    &lt;h2&gt;Produtos em Destaque&lt;/h2&gt;
&lt;/main&gt;
</code></pre>
<p><code>&lt;footer&gt;</code> — rodapé da página:</p>
<pre><code>&lt;footer&gt;
    &lt;p&gt;© 2025 PetShop. Todos os direitos reservados.&lt;/p&gt;
&lt;/footer&gt;
</code></pre>
<h3 id="formulários">Formulários</h3>
<p><code>form&gt;</code> — agrupa os elementos de um formulário:</p>
<pre><code>&lt;form&gt;
    &lt;input type="text" placeholder="Digite seu nome"&gt;
    &lt;button&gt;Enviar&lt;/button&gt;
&lt;/form&gt;
</code></pre>
<p><code>&lt;input&gt;</code> — campo de entrada de dados:</p>
<pre><code>&lt;input type="text" placeholder="Nome completo"&gt;
&lt;input type="email" placeholder="seu@email.com"&gt;
&lt;input type="password" placeholder="••••••••"&gt;
</code></pre>
<p><code>&lt;button&gt;</code> — botão clicável:</p>
<pre><code>  &lt;button onclick="salvar()"&gt;Salvar&lt;/button&gt;
</code></pre>
<h1 id="o-que-é-css">O que é CSS?</h1>
<p>CSS (Cascading Style Sheets) é a linguagem utilizada para estilizar páginas web, controlando cores, fontes, espaçamentos, layouts e a aparência geral dos elementos HTML.</p>

