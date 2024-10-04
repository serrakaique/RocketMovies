# Finalizando o MyMovies 🎥🎬

---

#### Stacks utilizadas

![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens) ![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white) ![Styled Components](https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

---

### Principais pontos que terá no projeto:

**1. Autenticação**

> Permitir que um usuário se autentique na aplicação utilizando um e-mail e uma senha. A autenticação foi feita utilizando JWT(Token).

**2. Upload de imagens**

> Permitir que o usuário consiga alterar a sua imagem de perfil ao clicar no ícone de câmera, localizada no canto inferior direito da foto

**3. Integração front-end e back-end.**

> Por último e muito importante, foi revistos diversos conteúdos importantes ao fazer a integração do nossa interface (front-end feita no stage 09) com a nossa api (back-end feita no stage 08). Aqui que a mágica acontece! 💜

---

#### Projeto Licenciado ⚖ [![Licence](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](../../LICENSE)

---

# 💻 Sobre o desafio

Wooow, esse Stage veio recheado de conteúdo 👀. Compreendi o uso de useState e useEffect, contextos, na prática, e agora, foi desenvolvido a integração do front-end com o back-end do MyMovies. O front-end feito em React.js utilizando o vitejs como setup inicial, estilização com styled-components (CSS dentro do javascript), que ja estava praticamente pronto, reutilizando ele do stage 09. O back-end, no caso a API, feita com Node.js, utilizando express, sendo reutilizada do stage 08.

Botei a mão na massa e apliquei tudo o que foi apresentado no módulo e nos stages anteriores, na **MyMovies** 🚀

#### Agora explicando mais sobre o desenvolvimento.

<p> Foi feita a junção do front-end com o back-end do MyMovies, utilizando a bibliotecas do pacote node.js. Primeiro foi implantado um fluxo de autenticação, famoso login no sistema. Nessa autenticação, tem a pagina de criar a conta com nome email e senha, no login a funcionalidade de checar se o usuário tem cadastro, checar email e senha através de uma solicitação contexto, e ao realizar essa checagem e estiver tudo certo, ira gerar um Token de autenticação (uma chave que identifica ele logado na minha aplicação). </p>
<p> Nesta parte de verificação, foi implantado o Contexto, dentro deste contexto podemos criar um estado(como se fosse uma variável) para pegar as informações. Com ele autenticado, ira disponibilizar a navegação na aplicação, dando um destino as requisições feitas anteriormente e junto da navegação ele carregará sempre o token, pois sem ele o usuário não terá nenhuma permissão de acessar o site, onde o middleware(um "guarda" para verificar se isto esta certo ou não) ficara responsável por "fiscalizar" identificar isto.
O Token que o usuário irá gerar, sera o JTW , um padrão de mercado que define ele no formato .JSON para troca de informações através das requisições HTTP. </p>
<p> Na junção do frontend com minha API, temos uma API RESTful, é um tipo de arquitetura de software, que leva em consideração diretrizes e boas recomendações onde o cliente e o servidor devem ser separados, - exemplo: aplicações em nuvem (servidores cloud) - o estado(javascript) no navegador, ficara responsável de guardar informações ate que seja necessário ser mandado para o backend. Assim o usuário apenas envia dados necessários e recebe uma resposta, não precisando saber de fato como foi implementada. </p>
<p> Por dentro do site, a Home(página inicial), aparecerá as Notas de Filmes criadas, como o usuário é novo estará aparecendo nenhuma. Para criar basta clicar em Adicionar Filme. Na tela de adicionar, Será obrigatório colocar o título do filme, sua nota de mínimo 0 e máximo 5, Observação (um breve resumo feito por você), marcadores para a categoria que o filme compreende (Ação, Aventura, Suspense, Comédia, etc), e salvando, você retorna para a Home. Também tem a possibilidade de editar o perfil na parte de cima da página, clicando no nome ou na foto, irá para a pagina de perfil, poderá editar nome, senha, e trocar também a foto do perfil. </p>
Clicando em uma nota criada, acessara todos o detalhes da nota, vendo que criou, hora, nota, e os detalhes que foram preenchidos na hora da crianção.

---

# MyMovies 🎞🎬

<div align="center">

### Preview do projeto 🤩

[![Video Preview](https://user-images.githubusercontent.com/101990719/186289394-b1b1dcb5-9700-4abd-9866-ec3f1e6e1caf.png)](https://user-images.githubusercontent.com/101990719/186289263-10fe0120-f618-4dba-b769-4b289d2cdc7c.mp4)
