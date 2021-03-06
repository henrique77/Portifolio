# Portifólio e Blog Web com Python e Django

O projeto consiste na costrução de uma aplicação web, utilizando o framework Django, que permite que o usuśrio mantenha armazenados e expostos seus projetos na forma de portifólio. Os projetos do usuário são inseridos e armazenados em um banco de dados [sqlite3](https://www.sqlite.org/index.html).
Além do portifólio, a aplicação possui um blog onde o proprietário pode compartilhar seus conhecimentos criando, atualizando e excluindo postagens, o proprietário ainda pode:
- Exibir postagens para o usuário como uma visualização de índice ou uma visualização de detalhes
- Atribuir categorias às postagens
- Permitir que os usuários comentem nas postagens do blog

Além do framework foram utilizados outros conceitos para o desenvolvimento da aplicação, os principais foram:
 - [HTML5](https://developer.mozilla.org/pt-BR/docs/Web/Guide/HTML/HTML5)
 - [CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
 - [JavaScript](https://www.javascript.com/)
 - [Bootstrap](https://getbootstrap.com/)
 - [sqlite3](https://www.sqlite.org/index.html)
 - [Django admin](https://docs.djangoproject.com/en/3.1/ref/contrib/admin/)

## Portifólio e Blog web

### Como rodar a aplicação
- Copie o repositório para sua máquina local:<br/>
 git clone https://github.com/henrique77/Portifolio.git
- Acesse a pasta do projeto e iniciar o servidor:<br/>
 python3 manage.py runserver
- Acessando o endereço no navegador:<br/>
 http://127.0.0.1:8000/projects/

<div align="center">
  <img src="./github/portifolioBlogWeb.gif" alt="home" height="425">
</div>

### Blog

No blog o usuário pode:<br/>
- Filtrar o conteúdo por categoria;
- Deixar comentário no artigo.

<div align="center">
  <img src="./github/BlogWeb.gif" alt="home" height="425">
</div>


