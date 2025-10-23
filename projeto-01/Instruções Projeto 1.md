- Criando seu próprio MySpace Top 8 com HTML!

- Para criar seu próprio MySpace Top 8 com HTML, crie um novo arquivo chamado top_8.html.

- Forneceremos um elemento <style> com os estilos já incluídos. Copie e cole isso no <head> seu arquivo:

<style>
  body {
    width: 85%;
    margin: auto;
  }

  h1 {
    text-align: left;
  }

  img {
    border: 3px solid blue;
  }

  #top-8-wrapper {
    text-align: center;
  }

  .friend-card {
    display: inline-block;
    margin: 1px;
    text-align: center;
  }

  .friend-name {
    color: blue;
  }
</style>

- Em seguida, vamos adicionar o HTML.

- Adicione um elemento <div> com um id de "top-8-wrapper".
- Dentro, adicione um elemento <h1> de título que diga "Meus melhores amigos!", seguido por dois elementos <div> com uma classe de "top-8-row".
- Dentro de cada um <div> com uma "top-8-row" classe, adicione mais quatro elementos <div> , cada um com uma classe de "friend-card".
- Dentro de cada um <div> com uma "friend-card" classe, adicione o seguinte:
- Um elemento <h2> de cabeçalho com uma "friend-name" classe e o nome do amigo dentro das tags.
- Um elemento <img> de imagem com um atributo srce alt.

Observação: Se você não quiser usar nomes reais, fique à vontade para adicionar nomes de usuários engraçados ou criar superlativos ("palhaço da turma", "alma da festa", "mais provável de se tornar presidente", "melhor cabelo", "mais provável de ser famoso na internet", etc.).