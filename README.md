# Meu Portifólio Profissional
 *Aluna:* Simone Araujo
 ## 📌 Sobre este Projeto
 Este repositório contém o código-fonte do meu portifólio pessoal, desenvolvido como atividade acadêmica no curso de Desenvolvimento de Sistemas. O objetivo do trabalho foi construir uma página web para apresentar meu perfil, as tecnologias que estou estudando e os projetos que venho desenvolvendo ao longo do curso.
 O projeto funciona como uma vitrine online: ao acessar a página, o usuário encontra uma apresentação pessoal, uma galeria com os projetos desenvolvidos e um espaço de contato com links ativos. A página se adapta automaticamente a diferentes tamanhos de tela.
 ## 🔗 Links
 - *🌐 Página publicada:* https://simonearaujo-dev-sys.github.io/meu-portifolio-profissional/
 - *📂 Repositório:* https://github.com/simonearaujo-dev-sys/meu-portifolio-profissional
 - *📑 Apresentação de Slides:* [Ver apresentação no Google Slides] https://docs.google.com/presentation/d/1qebGbIWnGQDXrDPs5xus_MGRCmcyvXMkuYzLoJoDgus/edit?usp=sharing 
 ## 🛠️ Tecnologias Utilizadas
 - *HTML5* — Estruturação de conteúdo
 - *Bootstrap 5* — Layout responsivo e componentes prontos
 - *CSS3* — Estilização personalizada
 - *GitHub Pages* — Hospedagem gratuita da página
 ## ✨ Recurso Novo Adicionado — Carrossel de Imagens
 Como recurso novo, implementei um *carrossel de imagens na página inicial*, que funciona como uma apresentação automática de slides. As imagens transitam suavemente umas após as outras, dando dinamismo à página logo na primeira visualização.
 ### Como foi implementado:
 Utilizei o componente nativo de carrossel do Bootstrap. A estrutura consiste em uma div principal com as classes carousel e slide, contendo uma área interna onde cada imagem é definida com a classe carousel-item. Com o atributo data-bs-ride="carousel", as imagens passam automaticamente sem necessidade de clique do usuário. O código utilizado foi:
 ```html
 <div id="carrossel" class="carousel slide" data-bs-ride="carousel">
   <div class="carousel-inner">
     <div class="carousel-item active">
       <img src="imagens/imagem1.jpg" class="d-block w-100" alt="Apresentação 1">
     </div>
     <div class="carousel-item">
       <img src="imagens/imagem2.jpg" class="d-block w-100" alt="Apresentação 2">
     </div>
   </div>
 </div>
