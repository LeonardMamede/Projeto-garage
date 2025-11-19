PARTE 1

Trabalho desenvolvido por Leonardo E. Mamede da Silva e Letícia Francisca de Moura e Silva.

A empresa Garage Detail é um lava jato que está no ramo há três anos implantando higienização e estética automotiva. Era de outro dono, que não quis mais continuar no ramo. Em 2025, Naldo, que era funcionário, decidiu assumir como novo gestor/dono.

O site foi desenvolvido com objetivo de divulgar os serviços do Garage Detail, facilitar o agendamento online de lavagens e fortalecer a imagem da marca como referência em cuidado automotivo. Além disso, busca atrair novos clientes, fidelizar os atuais e oferecer informações claras sobre os tipos de lavagem, valores e diferenciais do estabelecimento: higienizar com detalhes.

O público inicial da empresa eram moradores da região do Guará-Sof Sul, a partir dos 18 anos, abrangendo todos os perfis de clientes e empresas. Aproveitando o avanço do e-commerce, a empresa pretende fortalecer sua presença, conquistar novos clientes e expandir suas operações para áreas vizinhas.

A paleta de cores do site é composta por tons de preto, branco e cinza, sendo o preto e o branco as cores primárias, e o cinza utilizado como cor secundária e de fundo. Essa combinação representa a identidade visual da marca, transmitindo profissionalismo, elegância e confiança. O preto expressa força e sofisticação, o branco remete à limpeza e clareza, enquanto o cinza equilibra o contraste, reforçando modernidade e neutralidade.

O site apresenta uma barra de navegação no topo da página, com os botões Início, Sobre e Serviços, posicionados para que o usuário encontre rapidamente as principais seções. Essa disposição segue padrões comuns de navegação, facilita a exploração do conteúdo e proporciona uma experiência intuitiva, incentivando o visitante a conhecer a empresa e seus serviços.

As imagens das seções mostram os serviços de lavagem, polimento e higienização de forma atrativa, despertando o interesse do visitante e evidenciando o compromisso da Garage Detail com a excelência no cuidado automotivo.

A tipografia utilizada (fonte: “Mogra”) de traços simples e contemporâneos, proporciona boa leitura e harmonia com o estilo do site. O uso predominante do preto nas letras mantém a sobriedade e reforça a estética minimalista adotada.

As cores preto, branco e cinza foram selecionadas para transmitir profissionalismo, limpeza, sofisticação e modernidade, reforçando a identidade visual da Garage Detail. 

Os botões do menu posicionados no topo facilitam a navegação e tornam a experiência do usuário intuitiva, enquanto ícones próximos aos textos reforçam a compreensão visual dos serviços. 

O layout, com barra de navegação no topo, seções bem definidas e uso de imagens atrativas, permite que o visitante encontre informações rapidamente e navegue de forma agradável pelo site.

As etapas realizadas incluíram: 
Planejamento e definição do público-alvo e objetivos, realizados por ambos em 09/10/2025; 
Criação do design no Figma, realizada por ambos em 14/10/2025; 
Desenvolvimento do código do site, realizado por Leonardo em 15/10/2025; 
Elaboração do README, realizada por Letícia em 15/10/2025.

Segue link do protótipo do Figma:


https://www.figma.com/design/IEvhcYl8z9TRqXywaucs3Z/Projeto-Integrador?node-id=0-1&t=aa20TCKRnKUGdYJj-1 


* O que já está funcionando bem:
R. Interação, Inputs.
* Quais elementos HMTL se repetem em várias páginas?
R. Header, Nav, Footer, Aside.
* Onde o layout quebra ou fica estranho?
R. Na Página inicial, Menu de navegação, Footer, falta de elementos em Serviço e Sobre. 
* Quais melhorias fariam diferença real para o usuário do pequeno negócio?
R. Na parte de ofertas interativas.





PARTE 2

Garage Detail, lava jato com serviço apenas precencial e com o avanço do e-commerce, a empresa pretende fortalecer sua presença, conquistar novos clientes e expandir suas operações para áreas vizinhas com a ajuda do site
 desenvolvido por Leonardo E. Mamede da Silva e Letícia Francisca de Moura e Silva.

O site foi aberto no DevTools e está funcionando perfeitamente em todas as resoluções de tela
Não houve quebra no layout
Colocar um skiplink para melhoria do usuário 
As partes que se repetem e são idênticos: Header, nav, aside, footer
Os cards tem a mesma estrutura
Nossa seção de contato aparece em todas as páginas
Todas as páginas carregam corretamente, o código está funcionando bem
Interação, Inputs está funcionando bem
Usamos a tags (<header>, <nav>, <main>, <section>, <footer>)
Na pagina de início, temos 2 títulos principais e na página sobre temos um título principal. Os títulos seguem hierarquia lógica.
Todas as imagens têm atributo alt 
Todos os campos têm <label> associado via atributo for
Usamos <label> do lado de fora e não usamos placeholder
Não possui atributo required ou indicação visual
Todos os links e botões são acessíveis via Tab (por teclado)
Nosso projeto contém focus no CSS
O código não contém um skip link
Nosso site contém texto e fundo com contraste adequado (mínimo 4.5:1)
O tamanho da fonte é legível de tamanho 2 rem (32px)
No Lighthouse tivemos nota 50 de desempenho, 99 de acessibilidade, 96 de prática recomendas e 91 de CSO
O media queries está funcionando nas três
resoluções
As imagens estão fluidas e os grids se adaptam as resoluções
A estrutura de arquivos está organizada
Ajustamos a acessibilidade de todas as páginas
<header>, <nav>, <aside> 
Foram modularizados para facilitar qualquer futura mudança no projeto, usando apenas o recurso de componentes
O desafio que encontramos foi como colocar os componentes, consertar o erro das imagens já existetes da ultima entrega.

Futuras melhorias na parte de ofertas interativas fariam diferença real para o usuário do pequeno negócio, botão voltar ao topo pode ser acrescentado, efeitos hover mais elaorados.



Estrutura de pastas
.dist/
|-- index.html
|-- produtos.html
|-- serviços.html
|-- sobre.html
|-- componentes/
|   |-- header.html
|   |-- footer.html
|   |-- aside.html
|   |-- nav.html
|   |-- ofertas.html
|-- css/
|   |-- style.css
|   |-- responsive.css
|   |-- componentes.css
|-- js/
|   |-- components.js
|-- docs/
|   |-- rubricaDFE.pdf
|   |  |-- Protótipo Garage Deatail
|   |  |  |-- image 2
|   |  |  |-- image 3
|   |  |  |-- Protótipo Garage Detail
|-- img/
|   |-- carroRED.jpeg
|   |-- grand_b.jpeg
|   |-- grand_p.jpeg
|   |-- imagem_retan.jpeg
|   |-- lavagem.jpeg
|   |-- logo_b.jpeg
|   |-- logo_inst.jpeg
|   |-- logo_p.jpeg
|   |-- logo_whats.jpeg
|   |-- meninaLJ.jpeg
|   |-- polimento.jpeg
|-- README.md 

