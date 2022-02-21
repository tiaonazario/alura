# Aula 1: Matrix Chat: Criando o nosso projeto Aluracord

## Detalhes desta aula

Nesta primeira aula de React começaremos a fazer a nossa área de login no Aluracord! E você vai colocá-la no ar!

Nesta aula vamos criar tudo do ZERO: desde o package.json até os arquivos bases do Next.js para iniciar nosso projeto e ter o CSS in JS com styled-jsx para cuidar da camada de estilo da nossa aplicação, duas ferramentas essenciais do mundo React. Também entenderemos como React se tornou tão popular no mercado de tecnologia e como iniciar o nosso aprendizado com a tecnologia.

## Conteúdo detalhado desta aula

- Iniciaremos um projeto Next.js;
- Criaremos components com React usando CSS in JS;
- Vamos ver a estrutura inicial de um projeto Next.js;
- Passaremos propriedades para components;
- Faremos deploy do seu Aluracord na Vercel.

Lembre de postar o resultado final do seu Aluracord com as hashtags **#ImersaoReact** e **#Aluracord** marcando o [Mario](https://twitter.com/omariosouto) e o [Paulo](https://twitter.com/paulo_caelum)!

Também entre no [nosso server](https://discord.gg/kbzA7rPFFu) do **Discord** para compartilhar seus resultados e tirar suas dúvidas com a comunidade e professores! Lembre-se que a melhor forma de aprender é ensinando, então ajude a comunidade respondendo as dúvidas e compartilhando seu conhecimento.

## Desafios desta aula!

- Customizar o Aluracord com o SEU tema, seu background do assunto favorito (Filmes, Séries, Esportes, o desenho do coração) e compartilhar com a gente!, lembre-se de [usar o Coolors](https://coolors.co/1be7ff-6eeb83-e4ff1a-ffb800-ff5714) que indicamos nesta aula, para gerar a paleta de cores.
- Nosso arquivo de config com a parte das cores para [você fazer o seu tema está aqui, use-o como base 😍](https://gist.githubusercontent.com/omariosouto/983909257ff37d47c6bc31dd286f6caa/raw/908fc2a625ea0a673cdc62be62b436064ca63abc/config.json)
- Customizar o Aluracord com o SEU tema, seu background do assunto favorito (Filmes, Séries, Esportes, o desenho do coração) e compartilhar com a gente!, lembre-se de [usar o Coolors](https://coolors.co/1be7ff-6eeb83-e4ff1a-ffb800-ff5714) que indicamos nesta aula, para gerar a paleta de cores.

## Códigos e links importantes para você acompanhar a aula

- [Figma com o design que desenvolvemos na tela](https://www.figma.com/file/X5kVg1hNCajiV73ah7iyPz/Imers%C3%A3o-React---Aluracord---Matrix?node-id=0%3A1)
- Iniciar o projeto

- ```
  npx create-next-app --example with-styled-components
  # ou
  yarn create next-app --example with-styled-components
  ```
- Instalar e importar a lib de componentes brasileira totalmente integrada com o Next.js `@skynexui/components`

  ```
  npm install @skynexui/components
  ```

  ou

  ```
  yarn add @skynexui/components
  ```

E depois, no seu código importe:

```
import { Box, Button, Text, TextField, Image } from '@skynexui/components';
```

- [Códigos prontos citados na aula](https://gist.github.com/omariosouto/983909257ff37d47c6bc31dd286f6caa)

## Repositório do Aluracord

- Confira nossa vitrine e deixe seu fork e star em nosso projeto. Vamos fazer o mundo todo ver essa comunidade que estamos criando para aprender React! [https://github.com/alura-challenges/aluracord-matrix](https://github.com/alura-challenges/aluracord-matrix)
- Aqui você consegue ver com detalhes as alterações de arquivos que fizemos: [https://github.com/alura-challenges/aluracord-matrix/pull/1/files](https://github.com/alura-challenges/aluracord-matrix/pull/1/files)

## Links citados nesta aula

- [React](https://pt-br.reactjs.org/docs/create-a-new-react-app.html#recommended-toolchains)
- [Mario Souto - Strategy Pattern](https://www.youtube.com/watch?v=S-jqd6WZ7M0)
- [Mario Souto - Pegando dados de uma API com React](https://www.youtube.com/watch?v=85vJXFpXLQw)
- [Mario Souto - O sistema de rotas do NextJS, principais dúvidas](https://www.youtube.com/watch?v=-kVnp3fg-v4)
- [Mario Souto - Linter](https://www.youtube.com/watch?v=yMRSDdifGW8)
- [Mario Souto - Centralizar conteúdo na tela](https://www.youtube.com/watch?v=Cu-HP-gvggg)
- [CSS Grid Garden](https://cssgridgarden.com/)
- [Flexbox Froggy](https://flexboxfroggy.com)
- [Mario Souto - Storybook na prática](https://www.youtube.com/watch?v=R41_Qedrzik&t=7s)
- [Mario Souto - Configurando ambiente JavaScript/NodeJS/Yarn](https://www.youtube.com/watch?v=GIz71YGzwP4)
- [Documentação interativa com Storybook do SkynexUI](https://storybook.skynexui.dev/?path=/story/components-box--box-component)

## Como compartilhar seu próprio Aluracord

Você pode, depois do deploy, simplesmente marcar a gente usando a hashtag #Aluracord em alguma rede social. Mas quer fazer melhor? Você pode usar [este plugin do Chrome](https://chrome.google.com/webstore/detail/screencastify-screen-vide/mmeijimgabbpbgpdklnllpncmdofkcpn) para gravar o seu site em ação, scrollar e mostrar efeitos especiais e ainda passear pelo seu código quando ele estiver interessante.

Poste no seu Instagram, Linkedin, Twitter ou Facebook e marque #ImersaoReact, @aluraonline e seus professores para que a gente deixe um comentário e, quem sabe, você apareça nos extras das aulas!

## Acessibilidade - Transcrição da aula

Acesse a transcrição da aula 01 [clicando aqui](https://github.com/neforodrigo/imersao_react_2022/blob/main/imersao_react_aula01.md).
