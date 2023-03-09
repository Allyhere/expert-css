# Expert CSS

![License](https://img.shields.io/badge/license-CC0%201.0-green)
![Github Contributors](https://img.shields.io/github/contributors/allyhere/expert-css)
![Github Forks](https://img.shields.io/github/forks/allyhere/expert-css?style=flat-square)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)


Uma lista de leituras de conceitos, tecnologias, padrões de arquitetura e práticas modernas de CSS muito além do básico.

![Uma caixa com fundo transparente e outline preto com os dizeres expertCss vazando pra fora dela. Declarações de CSS aparecem, ajustam a largura da caixa, centralizam o texto e, por último, aparece um emoji de joinha sinalizando que está tudo certo - Feito por Camilo Micheletto, via figma](/assets/expertCss.gif "expert css logo")

CSS pode ser um pouco frustrante as vezes, principalmente porque ele demanda tanta dedicação quanto Javascript e seus frameworks. Visando entrega e funcionalidade, são poucas as oportunidades que temos de exercer práticas modernas de CSS, mesmo que em forma de melhoria contínua, então a leitura e a prática constante se fazem ainda mais importante.

Nesse repositório vou agregar leituras do que considero práticas avançadas de CSS - mas levem a palavra "avançado" não como uma tentativa de delimitar o que acredito ser complexidade, mas como uma sugestão pessoal com base em cursos que consumi e oportunidades que tive. Na minha experiência, talvez hajam pouquíssimos trabalhos que cobrem esse nível de CSS de você, arquitetura de CSS por assim dizer, então não se cobre tanto se o que você ler aqui parecer complexo, abstrato e talvez um pouco desnecessário. Dito isso, talvez muito do que você lerá aqui será um trabalho que talvez só a paixão e o entusiasmo justifique ter.

Todos os artigos citados aqui são de autores e autoras que acompanho, li e respeito o conteúdo. Se você ficou incomodade com a ausência de conteúdos em português, saiba que eu também estou, e estou ativamente aberto e a procura de conteúdo de CSS de alta qualidade, e eu tenho certeza que nós o temos, então peço encarecidamente sua ajuda pra furar essa bolha.

As atuais categorias listadas abaixo foram criadas e moldadas de forma a agrupar materiais com base no meu interesse pessoal, e minha intenção com esse repositório é fazer dessa lista muito mais do que isso por intermédio do Open Source. Se você conhece algum material de qualquer natureza que agregue nessa lista, dê uma olhada no nosso [guia de contribuição](/CONTRIBUTING.md) e mande um PR! Será muitíssimo bem recebida.

Esse material é licenciado por [Creative Commons Zero v1.0 Universal](https://choosealicense.com/licenses/cc0-1.0/#).

Quem quiser conhecer o que eu escrevo, por ora estou no [DevTo](https://dev.to/lixeletto), bora conectar por lá!

> Esse repositório foi inspirado no trabalho incrível do [Awesome-A11y](https://github.com/brunopulis/awesome-a11y) do Bruno Pulis, recomendo muito conhecer.


<br />

-----------

<br />

## Índice

- [Expert CSS](#expert-css)
  - [Índice](#índice)
  - [Conceitos](#conceitos)
  - [Layout](#layout)
  - [Especificidade](#especificidade)
  - [Variáveis CSS (Custom properties)](#variáveis-css-custom-properties)
  - [Cores e CSS](#cores-e-css)
  - [Tipografia](#tipografia)
  - [Container Queries](#container-queries)
  - [Cascade Layers](#cascade-layers)
  - [Logical Properties](#logical-properties)
  - [Core Web Vitals e CSS](#core-web-vitals-e-css)
  - [Propriedades e conceitos aprofundados](#propriedades-e-conceitos-aprofundados)
  - [Mídias, Ferramentas e Fontes](#mídias-ferramentas-e-fontes)

<br />

-----------

<br />

## <a id="conceitos"></a>Conceitos

Pra uma boa arquitetura CSS é necessário desenvolver uma clareza sobre como esse funciona conceitualmente. Essa sessão de artigos aborda e questiona conceitos que geralmente vimos de forma muito conceitual no início e que precisamos contantemente desafiá-los e aplicar eles de forma que faça sentido pro paradigma atual.

| Artigo | Autor |
| ----------- | -------- |
| [Understanding Layout Algorithms](https://www.joshwcomeau.com/css/understanding-layout-algorithms/) | Josh Comeau |
| [You Don’t Need A UI Framework](https://www.smashingmagazine.com/2022/05/you-dont-need-ui-framework/) | Josh Comeau |
| [Chasing the Pixel-Perfect Dream](https://www.joshwcomeau.com/css/pixel-perfection/) | Josh Comeau |
| [The State Of Pixel Perfection](https://ishadeed.com/article/pixel-perfection/) | Ahmad Shadeed |
| [Every Layout - Rudiments](https://every-layout.dev/rudiments/) | Andy Bell e Heydon Pickering |
| [Mobile-First CSS: Is It Time for a Rethink?](https://alistapart.com/article/mobile-first-css-is-it-time-for-a-rethink/) | Patrick Clancey |
| [The Guide To Responsive Design In 2023 and Beyond](https://ishadeed.com/article/responsive-design/) | Ahmad Shadeed |
| [Conditional CSS](https://ishadeed.com/article/conditional-css/) | Ahmad Shadeed |
| [Inside the mind of a frontend developer: Article layout](https://ishadeed.com/article/inside-frontend-developer-mind-article-layout/) | Ahmad Shadeed |
| [Tweaking In The Browser](https://ishadeed.com/article/tweaking-in-the-browser/) | Ahmad Shadeed |
| [Defensive CSS](https://ishadeed.com/article/defensive-css/) | Ahmad Shadeed |
| [The State Of Mobile First and Desktop First](https://ishadeed.com/article/the-state-of-mobile-first-and-desktop-first/) | Ahmad Shadeed |
| [Critical CSS? Not So Fast!](https://csswizardry.com/2022/09/critical-css-not-so-fast/) | Harry Roberts |
| [CSS: A New Kind Of JavaScript](https://heydonworks.com/article/css:-a-new-kind-of-javascript/) | Heydon Pickering |
| [A Whole Cascade of Layers (the path to SBRDFLT)](https://www.miriamsuzanne.com/2022/09/06/layers/) |  Mirian Suzanne |
| [CUBECSS](https://andy-bell.co.uk/cube-css/) | Andy Bell |
| [Smashing Podcast Episode 36 With Miriam Suzanne: What Is The Future Of CSS? (transcrição)](https://www.smashingmagazine.com/2021/05/smashing-podcast-episode-36/) |  Mirian Suzanne |
| [Modern alternatives to BEM](https://daverupert.com/2022/08/modern-alternatives-to-bem/) | Dave Rupert |
| [Why is CSS so Weird? (video)](https://www.youtube.com/watch?v=aHUtMbJw8iA&ab_channel=MozillaDeveloper) | Mirian Suzanne |
| [Everything You Know About the Web Just Changed (video)](https://www.youtube.com/watch?v=jBwBACbRuGY&ab_channel=AnEventApart) | Jen Simmons |

&nbsp;
<br />

## <a id="layout"></a>Layout

Padrões e conceitos de Layouts com CSS. Cada vez que o paradigma web avança, a comunidade desenvolve uma série de padrões de layout pensados em resolver os desafios daquele tempo. O Bootstrap popularizou muitos padrões importantes na época, voltado pra conceitos que eram modernos como mobile-first e responsividade. Essa sessão é interessante pra entender que padrões fazem sentidos no layout da web contemporânea, pensando também nas ferramentas novas e nos problemas que elas resolvem. Recomendo também todos os artigos do [Advanced Layout Patterns](https://web.dev/patterns/layout/) e os artigos gratuitos do Every Layout.


| Artigo | Autor |
| ----------- | -------- |
| [Don't use flexbox for overall page layout](https://jakearchibald.com/2014/dont-use-flexbox-for-page-layout/) | Jake Archibald |
| [An Interactive Guide to Flexbox](https://www.joshwcomeau.com/css/interactive-guide-to-flexbox/) | Josh Comeau |
| [Full-Bleed Layout Using CSS Grid](https://www.joshwcomeau.com/css/full-bleed/) | Josh Comeau |
| [Practical CSS Grid: Adding Grid to an Existing Design](https://alistapart.com/article/practical-grid/) | Eric Meyer |
| [The Story of CSS Grid, from Its Creators](https://alistapart.com/article/the-story-of-css-grid-from-its-creators/) |  Aaron Gustafson |
| [Grid for layout, Flexbox for components](https://ishadeed.com/article/grid-layout-flexbox-components/) | Ahmad Shadeed |
| [Laying out Forms using Subgrid](https://www.miriamsuzanne.com/2019/10/16/subgrid-forms/) | Mirian Suzanne |
| [Learn CSS Subgrid](https://ishadeed.com/article/learn-css-subgrid/) | Ahmad Shadeed |
| [Using Position Sticky With CSS Grid](https://ishadeed.com/article/position-sticky-css-grid/) | Ahmad Shadeed |
| [Create a split, faux-container layout with CSS Grid and Flexbox](https://piccalil.li/tutorial/create-a-split-faux-container-layout-with-css-grid-and-flexbox/) | Andy Bell |
| [The new responsive: Web design in a component-driven world](https://web.dev/new-responsive/) | Una Kravets |
| [min(), max() e clamp(): três funções CSS lógicas para usar hoje](https://web.dev/min-max-clamp/) | Una Kravets |
| [Modern CSS Solutions](https://moderncss.dev/) | Stephanie Eckles |
| [Style Stage](https://stylestage.dev/styles/) | Stephanie Eckles |
| [Contextual Callouts with CSS Grid](https://www.jonathan-harrell.com/blog/contextual-callouts-with-css-grid/) |Jonathan Harrell |
| [The Flexbox Holy Albatross](https://heydonworks.com/article/the-flexbox-holy-albatross/) | Heydon Pickering |
| [The Flexbox Holy Albatross: Reincarnated](https://heydonworks.com/article/the-flexbox-holy-albatross-reincarnated/) | Heydon Pickering |
| [Tetris And The Power Of CSS](https://heydonworks.com/article/tetris-and-the-power-of-css/) | Heydon Pickering |
| [Faster Layouts with CSS Grid (video)](https://youtu.be/KOvGeFUHAC0) | Mirian Suzanne |
| [Subgrid for Better Card Layouts (video)](https://www.youtube.com/watch?v=lLnFtK1LNu4&embeds_euri=https%3A%2F%2Fwww.miriamsuzanne.com%2F&source_ve_path=MjM4NTE&feature=emb_title) | Mirian Suzanne |
| [Designing With Grid (video)](https://www.youtube.com/watch?v=t0b3uBoDkBs&ab_channel=AnEventApart) | Jen Simmons |
| [CSS Grid Basics playlist (video)](https://www.youtube.com/playlist?list=PLbSquHt1VCf0b43dfLKTrCriXdlZcmgoi) | Jen Simmons |
| [(Layout) Core Concepts](https://www.youtube.com/playlist?list=PLbSquHt1VCf2AP5Jk31w4o7M1vokG4Gli) | Jen Simmons |
| [Designing Intrinsic Layouts (video)](https://www.youtube.com/watch?v=AMPKmh98XLY&ab_channel=AnEventApart) | Jen Simmons |
| [Modern Layouts: Getting Out of Our Ruts” by Jen Simmons (video)](https://www.youtube.com/watch?v=jreccgYLfx8&ab_channel=AnEventApart) | Jen Simmons |

&nbsp;
<br />

## <a id="especificidade"></a>Especificidade
[Especificidade](https://web.dev/learn/css/specificity/) é um tópico muito importante pois molda a forma que você acessa elementos e declara suas regras no CSS. Metodologias como [BEM](https://desenvolvimentoparaweb.com/css/bem/), seletores como [:has()](https://ishadeed.com/article/css-has-parent-selector/) e [:where()](https://developer.mozilla.org/en-US/docs/Web/CSS/:where) e tecnologias como [Cascade Layers](https://ishadeed.com/article/cascade-layers/) são grandes avanços no controle da especificidade, principalmente em grande escala, mas o conhecimento do coneito básico de como o navegador calcula a precedência de CSS ainda se faz necessária pra usufruir de todo o poder dessas ferramentas.


| Artigo | Autor |
| ----------- | -------- |
| [The CSS Cascade](https://wattenberger.com/blog/css-cascade) | Amelia Wattenberger |
| [CSS specificity and the cascade](https://piccalil.li/tutorial/css-specifity-and-the-cascade/) | Andy Bell |
| [Specifishity](https://specifishity.com/) | Estelle Weyl |

&nbsp;
<br />


## <a id="variáveis-css-custom-properties"></a>Variáveis CSS (Custom properties)
Variáveis CSS mereceram um tópico só pra elas pois são extremamente poderosas na criação de variantes, definição de design tokens, dark mode e muito mais. O [Tailwind](https://tailwindcss.com/), por exemplo, conseguiu escalar o seu design system usando composição de variáveis, já [OpenProps](https://open-props.style/) é um framework construído inteiramente de variáveis CSS.

| Artigo | Autor |
| ----------- | -------- |
| [Global and Component Style Settings with CSS Variables](https://www.sarasoueidan.com/blog/style-settings-with-css-variables/) | Sara Soueidan |
| [CSS Custom Properties In The Cascade](https://www.smashingmagazine.com/2019/07/css-custom-properties-cascade/) | Miriam Suzanne |
| [Using Custom Property “Stacks” to Tame the Cascade](https://css-tricks.com/using-custom-property-stacks-to-tame-the-cascade/) | Miriam Suzanne |
| [Unlocking the Benefits of CSS Variables](https://www.jonathan-harrell.com/blog/unlocking-the-benefits-of-css-custom-properties/) | Jonathan Harrel |
| [CSS Variables for React Devs](https://www.joshwcomeau.com/css/css-variables-for-react-devs/) | Josh Comeau |
| [The Power of Composition with CSS Variables](https://blog.maximeheckel.com/posts/the-power-of-composition-with-css-variables/) | Maxime Heckel |
| [Composing the Uncomposable with CSS Variables](https://adamwathan.me/composing-the-uncomposable-with-css-variables/) | Adam Watham |
| [10 powerful ways to use CSS variables](https://nerdy.dev/custom-prop-categories) | Adam Argyle |
| [Component Variants with Scoped CSS Variables](https://www.jonathan-harrell.com/blog/component-variants-with-scoped-css-variables/) | Jonathan Harrell |
| [Unlocking the Benefits of CSS Variables](https://www.jonathan-harrell.com/blog/unlocking-the-benefits-of-css-custom-properties/) | Jonathan Harrell |
| [Live Theming with CSS Variables](https://www.jonathan-harrell.com/blog/live-theming-with-css-variables/) | Jonathan Harrell |

&nbsp;
<br />

## <a id="cores-e-css"></a>Cores e CSS
CSS está progressivamente dando suporte pra diversas funções de cores, permitindo ainda mais fidelidade com designs, facilidade com acessibilidade em relação à cor e a construção de paletas e gradientes mais expressivas. De antemão, recomendo seguir o perfil do Twitter do [Adam Argyle](https://www.twitter.com/argyleink), DevRel no Chrome e membro do CSSWG pra se atualizar desse assunto.

| Artigo | Autor |
| ----------- | -------- |
| [Lights and Shadows](https://ciechanow.ski/lights-and-shadows/) | Bartosz Ciechanowski |
| [Unlocking Colors](https://bkardell.com/blog/Unlocking-Colors.html) | Brian Kardell |
| [Calculating Color: Dynamic Color Theming with Pure CSS](https://una.im/css-color-theming/) | Una Kravets |
| [A color-contrast() strategy for complimentary translucent backgrounds](https://nerdy.dev/color-from-color-contrast-result) | Adam Argyle |
| [Gradient hue interpolation](https://nerdy.dev/gradients-going-the-shorter-longer-increasing-or-decreasing-route) | Adam Argyle |
| [LCH Luminance vs HSL Lightness](https://nerdy.dev/lch-luminance-vs-hsl-lightness) | Adam Argyle |
| [Improving Color on the Web](https://webkit.org/blog/6682/improving-color-on-the-web/) | Dean Jackson |

&nbsp;
<br />

## <a id="tipografia"></a>Tipografia
Tipografia infelizmente é um campo pouco explorado, mas recheado de possibilidades. O conhecimento de fontes pode ampliar os limites da nossa criatividade a respeito do asset mais valioso de um site - o conteúdo.

| Artigo | Autor |
| ----------- | -------- |
| [Fluid typography with CSS clamp](https://piccalil.li/tutorial/fluid-typography-with-css-clamp/) | Andy Bell |
| [Pixels vs. Relative Units in CSS: why it’s still a big deal](https://www.24a11y.com/2019/pixels-vs-relative-units-in-css-why-its-still-a-big-deal/) | Kathleen McMahon |
| [Font Hacking](https://heydonworks.com/article/font-hacking/) | Heydon Pickering |
| [Customizing Color Fonts on the Web](https://webkit.org/blog/12662/customizing-color-fonts-on-the-web/) |  Myles C. Maxfield e David Jonathan Ross |

&nbsp;
<br />

## <a id="container-queries"></a>Container Queries
Container Queries mereceu um tópico só pra si por ser algo emergente que vai mudar completamente o paradigma de layout nos próximos anos. Não vale a pena dispensá-lo por não estar [evergreen](https://css-tricks.com/evergreen-does-not-mean-immediately-available/#aa-evergreen-browsers), pois observando os avanços do [browser interop](https://github.com/web-platform-tests/interop/blob/main/2023/README.md#focus-areas), é uma tecnologia que logo logo poderá ser massivamente adotada, mesmo apenas como melhoria contínua.

| Artigo | Autor |
| ----------- | -------- |
| [Component-level art direction with CSS Container Queries](https://www.sarasoueidan.com/blog/component-level-art-direction-with-container-queries-and-picture/) | Sara Soueidan |
| [Next Gen CSS: @container](https://css-tricks.com/next-gen-css-container/) | Una Kravets |
| [CSS container queries are finally here](https://ishadeed.com/article/container-queries-are-finally-here/) | Ahmad Shadeed |
| [CSS Style Queries](https://ishadeed.com/article/css-container-style-queries/) | Ahmad Shadeed |
| [A Primer On CSS Container Queries](https://www.smashingmagazine.com/2021/05/complete-guide-css-container-queries/) | Stephanie Eckles |

&nbsp;
<br />

## <a id="cascade-layers"></a>Cascade Layers
Apesar de não ter um suporte bom o bastante pra ser utilizada sem o [preset-env do PostCSS](https://github.com/csstools/postcss-plugins/tree/main/plugin-packs/postcss-preset-env), [já tem suporte o bastante](https://caniuse.com/css-cascade-layers) pra ser utilizada em projetos pessoais com alguma parcimônia. Sobre o tópico recomendo seguir a [Miriam Suzanne](https://twitter.com/TerribleMia), membra do CSSWG e do SassCSS.

| Artigo | Autor |
| ----------- | -------- |
| [A Complete Guide to CSS Cascade Layers](https://css-tricks.com/css-cascade-layers/) | Miriam Suzanne |
| [Making Sense of CSS Layers and Scope (video)](https://youtu.be/UmmePVi0TUk) | Miriam Suzanne |

&nbsp;
<br />

## <a id="logical-properties"></a>Logical Properties
Logical properties se referem a propriedades que já conhecíamos, como margin, width e border, mas orientadas de acordo com o eixo de leitura do site. [Logical Properties Level 1](https://www.w3.org/TR/css-logical-1/) já [pode ser progressivamente adotada](https://caniuse.com/css-logical-props) e deixará o seu layout extremamente resiliente de forma internacional.

| Artigo | Autor |
| ----------- | -------- |
| [Digging Into CSS Logical Properties](https://ishadeed.com/article/css-logical-properties/) | Ahmad Shadeed |
| [CSS Logical Properties](https://andy-bell.co.uk/css-logical-properties/) | Andy Bell |

&nbsp;
<br />

## <a id="core-web-vitals-e-css"></a>Core Web Vitals e CSS

Core Web Vitals (CWV) é o conjunto de métricas que definem o estado da performance de uma página web. O CSS é um recurso crítico no carregamento de uma página, pois seu site é renderizado apenas após o DOM e o CSSOM serem lidos por completo, formando a render tree. Se você não conhece o conceito, recomendo comecar por [Core Web Vitals](https://web.dev/vitals/#core-web-vitals) e [Critical Rendering Path](https://web.dev/critical-rendering-path/). Nesse último tópico, a Google tem um [nanodegree gratuito sobre o assunto ministrado por Ilya Grigorik e Cameron Pittman](https://www.udacity.com/course/website-performance-optimization--ud884).

| Artigo | Autor |
| ----------- | -------- |
| [CSS para Web Vitals](https://web.dev/css-web-vitals/) | Una Kravets e Katie Hempenius |
| [Extraia CSS crítico](https://web.dev/extract-critical-css/) | Milica Mihajlija |
| [Defer non-critical CSS](https://web.dev/defer-non-critical-css/) | Demian Renzulli |
| [How to remove unused CSS from a site](https://css-tricks.com/how-do-you-remove-unused-css-from-a-site/) | Chris Coyier |

&nbsp;
<br />

## <a id="propriedades-e-conceitos-aprofundados"></a>Propriedades e conceitos aprofundados
Nessa sessão coloquei artigos variados sobre propriedades e técnicas que expandiram a minha visão sobre a capacidade que certas propriedades tem quando você as entende um pouco melhor.
Parecido com esse tópico, recomendo também a playlist [Speedy CSS Tips do Jhey Thompkins](https://twitter.com/i/events/1549102292632305665).


| Artigo | Autor | Tema |
| ----------- | -------- | -------- |
| [Cubic Bézier: from math to motion](https://blog.maximeheckel.com/posts/cubic-bezier-from-math-to-motion/) | Maxime Heckel | Animação |
| [What does 100% mean in CSS?](https://wattenberger.com/blog/css-percents) | Amelia Wattenberger | Sizing |
| [The master guide to smooth, realistic shadows in CSS](https://dev.to/devang/the-master-guide-to-smooth-realistic-shadows-in-css-463p) | Devang Saklani | Shadows |
| [Relative sizing with EM units](https://piccalil.li/tutorial/relative-sizing-with-em-units/) | Andy Bell | Unidades |
| [Dark Mode by Local Sunlight](https://www.ctnicholas.dev/articles/dark-mode-by-sunlight) | Chris Nicholas | Dark Mode |
| [Advanced CSS-Only HTML Form Styling](https://www.jonathan-harrell.com/blog/advanced-css-only-form-styling/) | Jonathan Harrell | Forms |
| [What’s the Deal with Margin Collapse?](https://www.jonathan-harrell.com/blog/what%E2%80%99s-the-deal-with-margin-collapse/) | Jonathan Harrell | Forms |
| [Better Typography with Font Variants](https://www.jonathan-harrell.com/blog/better-typography-with-font-variants/) | Jonathan Harrell | Forms |
| [CSS Nesting](https://developer.chrome.com/articles/css-nesting/) | Adam Argyle | Nesting |
| [Thinking About The Cut-Out Effect: CSS or SVG?](https://ishadeed.com/article/thinking-about-the-cut-out-effect/) | Ahmad Shadeed | Masking / SVG |

&nbsp;
<br />

## <a id="mídias-ferramentas-e-fontes"></a>Mídias, Ferramentas e Fontes

- [CSSStats](https://cssstats.com/) - Audit de CSS que mostra um dashboard com suas regras, seletores e um score de especificidade.
- [Yellow Lab Tools](https://yellowlab.tools/) - Faz audit de performance da sua página, mas possui informações bem bacanas de performance CSS, dando uma nota pra complexidade e code smells de CSS do seu site.
- [Project Wallace](https://www.projectwallace.com/analyze-css) - De todas que já vi é a ferramenta de audit mais completa, mostra as at-rules, seletores, nível de complexidade, valores, tudo em um dashboard muito bonito e organizado.
- [The CSS Podcast](https://thecsspodcast.libsyn.com/) - Jamais pensei que pudesse aprender tanto CSS apenas ouvindo. Disponível também nas principais plataformas de streaming de áudio.
- [Life of a Pixel (vídeo)](https://www.youtube.com/watch?v=m-J-tbAlFic&list=PLNYkxOF6rcICgS7eFJrGDhMBwWtdTgzpx&index=5) - Documentário importantíssimo sobre o que acontece na engine do navegador pra um píxel renderizar na tela. Ministrado pela [Chrome University](https://www.youtube.com/playlist?list=PLNYkxOF6rcICgS7eFJrGDhMBwWtdTgzpx).
- [Aprenda CSS](https://web.dev/learn/css/) - Um curso de CSS muito completo desenvolvido pela Google.
- [Component Patterns](https://web.dev/patterns/components/) e [Theming Patterns](https://web.dev/patterns/theming/) - Lista de padrões de desenvolvimento de componentes e temas criada pelo Adam Argyle. Todos os exemplos possuem repositório e vídeo. Você pode também acessar a [playlist com apenas os vídeos](https://www.youtube.com/watch?v=MR7dClW6iBg&list=PLNYkxOF6rcIAaV1wwI9540OC_3XoIzMjQ&ab_channel=GoogleChromeDevelopers).
- [DevTools Tips (video)](https://www.youtube.com/playlist?list=PLNYkxOF6rcIAcezfL8q0rjt13ufKseL5X) - Chrome é meu navegador favorito e nessa playlist a Jecelyn Yeen ensina tudo o que você precisa saber pra extrair o melhor dele.
- [Design in the Browser (video)](https://www.youtube.com/playlist?list=PLNYkxOF6rcIDI0QtJvW6vKonTxn6azCsD) - Nessa playlist a Una Kravets ensina, entre outras coisas, uma série de ferramentas e práticas de layout com CSS.
