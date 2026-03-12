# Projeto Codemaster DEV 2IF-DS 👩🏻‍💻

## Estado Inicial do projeto 💻🖱️

<p>Recebi o HTML e CSS prontos. O layout renderiza perfeitamente, mas o menu mobile não abre e o formulário recarrega a página...<p>

---

_Lista de tarefas:_ 📖

✅ 1. Menu Mobile

<p>O código JavaScript controla o menu mobile do site.</p>

_**Foi realizado:**_
<p>Ele permite abrir e fechar o menu quando o usuário clica no ícone, mudando as classes do ícone e da lista de navegação.
Também bloqueia a rolagem da página quando o menu está aberto. Além disso, o menu é fechado automaticamente quando o usuário clica em um link ou rola a página.</p>

---
✅ 2. Links Ativos

<p>O código seleciona todos os links do menu de navegação e adiciona um evento de clique a cada um.</p>

_**Foi realizado:**_
<p>Quando um link é clicado, ele remove a classe active de todos os links e adiciona essa classe apenas ao link selecionado, destacando-o no menu.</p>

---
✅ 3. Alterar modo claro/escuro

<p>O código permite alternar entre o modo claro e escuro do site<p>

_**Foi realizado:**_
<p>Quando a função é executada, ela adiciona ou remove a classe light no elemento html, mudando o tema da página. A escolha do usuário é salva no localStorage, e quando a página é carregada novamente, o site aplica automaticamente o tema que foi salvo.</p>

---
✅ 4. Animação da seção home

<p>O código aplica uma animação de entrada (fade-in) na seção “home” do site.<p>

_**Foi realizado:**_
<p>Inicialmente, a seção começa transparente e levemente deslocada para baixo. Após 100ms, a opacidade é ajustada para 1 e a posição volta ao normal, criando um efeito suave de aparecimento e deslizamento para cima.</p>

---
✅ 5. Animação das seções

<p>O código seleciona todas as <section> da página e aplica um estado inicial com opacidade 0 e uma transformação, deixando-as invisíveis. Cada seção pode ter um efeito inicial diferente (como translateY, scale ou rotate).<p>

_**Foi realizado:**_
<p>Em seguida, é criado um IntersectionObserver, que observa quando cada seção entra na área visível da tela durante o scroll. Quando isso acontece, a opacidade da seção muda para 1 e a transformação é removida, fazendo a seção aparecer com uma animação suave.</p>

---
✅ 6. Botão de voltar ao topo

<p>O código seleciona o link dentro do elemento .top e adiciona um evento de clique a ele. Quando o usuário clica no botão, o comportamento padrão do link é bloqueado com preventDefault().<p>

_**Foi realizado:**_
<p>Em seguida, a função window.scrollTo() é usada para rolar a página suavemente até o topo, utilizando behavior: 'smooth'. Assim, o botão funciona como um atalho para voltar ao início da página com uma animação de rolagem suave.'</p>

✅ 7. Formulário de contato.

<p>O código cria um carrossel de slides que permite navegar entre projetos usando botões de próximo e anterior.<p>

_**Foi realizado:**_
<p>Ele controla qual slide está visível, ocultando os outros e movendo o carrossel horizontalmente. Também possui troca automática de slides a cada 5 segundos, que é pausada quando o mouse fica sobre o carrossel e retomada quando o mouse sai.</p>







