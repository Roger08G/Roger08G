<img src="./assets/banner.png" alt="banner" width="100%" />

<style>
  .articles {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 0;
    width: 100%;
    border: 1px solid #30363d;
  }

  .card {
    padding: 28px 24px;
    text-align: center;
    border-right: 1px solid #30363d;
  }

  .card:last-child {
    border-right: none;
  }

  .card img {
    width: 100%;
    max-height: 220px;
    object-fit: cover;
    border: 4px solid #facc15;
  }

  .card h3 {
    color: #ffffff;
    margin-bottom: 16px;
  }

  .buttons {
    margin: 12px 0 22px;
  }

  .buttons a {
    display: inline-block;
    padding: 6px 14px;
    margin: 0 4px;
    background: #facc15;
    color: #000;
    font-weight: bold;
    text-decoration: none;
    font-size: 12px;
    letter-spacing: 1px;
  }

  .card p {
    color: #ffffff;
    line-height: 1.6;
    font-size: 14px;
  }
</style>

<section class="articles">
  <div class="card">
    <h3>Artículo 1</h3>
    <img src="./assets/article-1.png" alt="Artículo 1" />
    <div class="buttons">
      <a href="#">CÓDIGO</a>
      <a href="#">YOUTUBE</a>
    </div>
    <p>
      Descripción corta del artículo, proyecto o recurso. Explica qué aporta
      y por qué merece la pena verlo.
    </p>
  </div>

  <div class="card">
    <h3>Artículo 2</h3>
    <img src="./assets/article-2.png" alt="Artículo 2" />
    <div class="buttons">
      <a href="#">CÓDIGO</a>
      <a href="#">YOUTUBE</a>
    </div>
    <p>
      Otra descripción breve. Mantén el texto corto para que el perfil se vea
      limpio y profesional.
    </p>
  </div>
</section>