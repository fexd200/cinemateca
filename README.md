# cinemateca
# cinemateca <!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.6/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-4Q6Gf2aSP4eDXB8Miphtr37CMZZQ5oXLH2yaXMJ2w8e2ZtHTl7GptT4jmndRuHDT" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.6/dist/js/bootstrap.bundle.min.js" integrity="sha384-j1CDi7MgGQ12Z7Qab0qlWQ/Qqz24Gc6BM0thvEMVjHnfYGF0rmFCozFSxQBxwHKO" crossorigin="anonymous"></script>
   <link rel="stylesheet" href="style.css">
    <title>meu portifolio</title>
</head>
<body>
    <div class="container text -center">
    <img src="avatar-perfil" alt="avatar-perfil" class="rounded-circle" srcset="">
    <p class="lead">Ola, eu me chamo Federico</p>
    <h1>Quero fazer psicologia</h1>
    <p>Estou no terceiro ano do ensino médio, tenho 17 anos e quero fazer o ENEM para psicologia</p>
    <p>Minhas habilidades</p>
    <div>
        <p class="badge text-bg-secondary">HTML</p>
        <p class="badge text-bg-secondary">CSS</p>
        <p class="badge text-bg-secondary">JavaScript</p>
        <p class="badge text-bg-secondary">Scratch</p>
    </div>
    </header>
    <main class="container mt-5">
      <h2>Meus Planejamentos</h2>
      <div class="row">
        <!-- pagina 1 -->
      <div class="col -md-4">
          <div class="card" style="width: 18rem;">
  <img src="imgfilme.jpeg" class="rounded-circle" alt="imagem do projeto de biblioteca virtual">
  <div class="card-body">
    <h5 class="card-title">Minha cinema-teca</h5>
    <p class="card-text">Nesse projeto irei apresentar os meus filmes favoritos, com uma breve descrição de cada um deles.</p>
    <a href="#" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#modal1">Aperte Aqui</a>
  </div>
</div>
        </div>
    <!-- pagina 2 -->
      <div class="col -md-4">
          <div class="card" style="width: 18rem;">
  <img src="..." class="img" alt="imagem do projeto de biblioteca virtual">
  <div class="card-body">
    <h5 class="card-title"> Aprofundando um pouco mais</h5>
    <p class="card-text">Agora, eu irei me aprofundar um pouco mais em cada filme. Desde seu enredo e suas criticas até contribuições para o cinema.</p>
    <a href="#" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#modal2">Aperte Aqui</a>
  </div>
</div>
        </div>
      </div>
    </main>
<!-- modal1 -->
  <div class="modal" id="modal1" tabindex="-1">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <h5 class="modal-title">Minha cinema-teca</h5>
                <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
            <div class="modal-body">
                <p>Nesse projeto irei fazer uma analise totalmente pessoal de cada filme e o porque eu gosto de cada um deles.</p>
                <p> Além de citar os seus impactos sociais irei fazer uma breve reflexão sobre alguns aspectos que eu considero importante sobre essas obras de arte.</p>
            </div>
            <div class="modal-footer">
                <a href="">Ver projeto ao vivo</a>
               <a href="">Ver código do projeto</a>
            </div>
        </div>
    </div>
</div>

<!-- modal 2 -->
  <div class="modal" id="modal2" tabindex="-1">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <h5 class="modal-title">Minha cinema-teca</h5>
                <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
            <div class="modal-body">
                <p>Primeiramente, irei comentar um pouco sobre o filme os sonhadores. O filme é uma referencia a varios outros clássicos franceses com uma critica incrivel.Desde o ato de sairmos de casa para irmos em uma manifestação pacífica até a forma em que nos organizamos socialmente. Afinal até nossa própria indentidade é formada por conta de nossas experiências e referências que no final irá refletir no nosso posicionamento político.

O final é incrível. Não discordo totalmente mas com toda certeza não concordo com a ideia do mathew, afinal se as coisas se resolvessem apenas na base do diálogo não teriamos uma policia extremamente corrupta e facista (que primeiro atira e depois verifica se a pessoa apresentava um perigo ou não) juntamente com tanta desigualdade e barbaridades causadas pelo capitalismo tardio..</p>
                <p> Rogue One é um filme incrivel, diferente dos filmes principais de star wars mostra o facismo imperial e a verdadeira luta dos rebeldes.</p>
                <p>Ja duna parte 2 é um filme grandioso, denis fez um otimo trabalho no filme e mesmo com baixo orçamento foi o mais fiel possivel ao livro.</p>
            </div>
            <div class="modal-footer">
                <a href="">Ver projeto ao vivo</a>
               <a href="">Ver código do projeto</a>
            </div>
        </div>
    </div>
</div>

    <footer class="container py-5">
      <h2>Meu letterboxd para mais informações</h2>
      <div>
       <a href="https://boxd.it/cdncp">letterboxd</a>
      </div>

    </footer>

  <script
    src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
    crossorigin="anonymous"
  ></script>
</body>
</html>
