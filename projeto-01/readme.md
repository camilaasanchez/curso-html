Vamos criar seu próprio MySpace Top 8 com HTML!

Crie um novo arquivo chamado top_8.html .

Forneceremos um <style>elemento com os estilos já incluídos. Copie e cole isso no <head>seu arquivo:
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

Em seguida, vamos adicionar o HTML.

Adicione um <div>elemento com um id de "top-8-wrapper".
Dentro, adicione um <h1>elemento de título que diga "Meus melhores amigos!", seguido por dois <div>elementos com uma classe de "top-8-row".
Dentro de cada um <div>com uma "top-8-row"classe, adicione mais quatro <div>elementos, cada um com uma classe de "friend-card".
Dentro de cada um <div>com uma "friend-card"classe, adicione o seguinte:
Um <h2>elemento de cabeçalho com uma "friend-name"classe e o nome do amigo dentro das tags.
Um <img>elemento de imagem com um atributo srce alt.

Se você não quiser usar nomes reais, fique à vontade para adicionar nomes de usuários engraçados ou criar superlativos ("palhaço da turma", "alma da festa", "mais provável de se tornar presidente", "melhor cabelo", "mais provável de ser famoso na internet", etc.).