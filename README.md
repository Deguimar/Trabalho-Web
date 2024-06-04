# Trabalho-Web
O objetivo desse trabalho será a utilização de elementos do Bootstrap e 
Javascript. Iremos realizar a criação de um site com layout simples de apenas 
uma página para postagem de textos (no estilo Twitter).

Etapa 1 - Organização das Pastas
Antes de começar,é importante organizar as pastas do projeto para manter os 
arquivos organizados como por exemplo:

nome_da_pasta/
│
├── css/
│ └── style.css # Arquivos CSS 
├── js/
│ └── script.js # Arquivos JavaScript 
└── index.html # Arquivo HTML principal


Etapa 2 - Incorporação do Bootstrap
O Bootstrap é um framework CSS que facilita a criação de interfaces de 
usuário responsivas e elegantes. Para incorporar o Bootstrap, você precisa 
incluir links para os arquivos CSS e JS do Bootstrap em seu arquivo HTML.
Deve ser feito dentro da tag <head>.

Incluir Bootstrap CSS:
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-
alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
Incluir Bootstrap JavaScript:
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-
alpha1/dist/js/bootstrap.bundle>
  
Etapa 3 – Adicione uma barra de navegação simples
Adicione uma barra de navegação simples contendo o logo do seu site e o seu 
nome. Na documentação oficial do Bootstrap há um vasto exemplo de barras 
de navegação e códigos aplicáveis. 
https://getbootstrap.com/docs/5.3/components/navbar/

Etapa 4 – Criação do formulário
Crie um formulário que contenha uma área de texto e um botão para 
postagem.
https://getbootstrap.com/docs/5.3/forms/form-control/

Etapa 5 – Postagem
O clicar no botão Postar deverá ser criado dinamicamente em um espaço 
abaixo o que o usuário escreveu. Nesse <div> deverá conter também dois 
botões, um para curtir a postagem e outro para excluir.
https://getbootstrap.com/docs/5.3/components/buttons/
Ao clicar no botão de curtir o mesmo deve mudar a sua cor e estilo.
Ao clicar no botão de deletar, o mesmo deve excluir da tela a postagem 
selecionada.
