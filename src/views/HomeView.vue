<script></script>

<template>
  <main>
    <div class="Welcome">
      <h2>As melhores viagens você faz aqui!</h2>
    </div>
    <div class="Popu">
      <h3>As queridinhas do momento:</h3>
    </div>
    <div class="card-group">
      <div class="card">
        <img
          src="https://viagemeturismo.abril.com.br/wp-content/uploads/2017/12/istock-842960000.jpg"
          class="card-img-top"
          alt="..."
          height="221px"
        />
        <div class="card-body">
          <h5 class="card-title">São paulo</h5>
          <p class="card-text">
            3 dias em São Paulo, com passagem de ida e volta, estadia em a 300
            metros do Ibirapuera, almoço e guia turistico inclusos.
            <br />
            <b>Por apenas: R$599,99</b>
          </p>
          <a href="/about" class="btn btn-primary">Ver mais</a>
        </div>
      </div>
      <div class="card">
        <img
          src="https://viagemeturismo.abril.com.br/wp-content/uploads/2016/12/10-9n.jpg"
          class="card-img-top"
          alt="..."
          height="221px"
        />
        <div class="card-body">
          <h5 class="card-title">Rio de janeiro</h5>
          <p class="card-text">
            5 dias no Rio de Janeiro, com passagem de ida e volta, estadia em
            pousada a 800 metros do centro, almoço e guia turistico inclusos.
            <br />
            <b>Por apenas: R$1250,99</b>
          </p>
          <a href="/about" class="btn btn-primary">Ver mais</a>
        </div>
      </div>
      <div class="card">
        <img
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcToyAXuD8CRdDkBypi3QYpaGiOiyrEKRDqTLg&usqp=CAU"
          class="card-img-top"
          alt="..."
          height="221px"
        />
        <div class="card-body">
          <h5 class="card-title">Fernando de Noronha</h5>
          <p class="card-text">
            3 dias em Fernando de Noronha, com passagem de ida e volta, estadia
            em em pousada de frente pro mar, almoço e guia turistico inclusos.
            <br />
            <b>Por apenas: R$1899,99</b>
          </p>
          <a href="/about" class="btn btn-primary">Ver mais</a>
        </div>
      </div>
    </div>

    <div class="Popu2">
      <h3>Viagens ao mundo:</h3>
    </div>

    <div class="exterior">
      <div class="card-group">
        <div class="card">
          <img
            src="https://veja.abril.com.br/wp-content/uploads/2018/08/0620zu_3567rw.jpeg"
            class="card-img-top"
            alt="..."
            height="221px"
          />
          <div class="card-body">
            <h5 class="card-title">Disney World(EUA)</h5>
            <p class="card-text">
              6 dias em Orlando, com passagem de ida e volta, estadia em hotel a
              300 metros do parque, almoço e guia turistico inclusos.
              <br />
              <b>Por apenas: R$2899,99</b>
            </p>
            <a href="/about" class="btn btn-primary">Ver mais</a>
          </div>
        </div>
        <div class="card">
          <img
            src="https://upload.wikimedia.org/wikipedia/commons/8/8a/Paris_vue_d%27ensemble_tour_Eiffel.jpg"
            class="card-img-top"
            alt="..."
            height="221px"
          />
          <div class="card-body">
            <h5 class="card-title">Paris(França)</h5>
            <p class="card-text">
              4 dias na cidade da luz, com passagem de ida e volta, estadia em
              pousada a 800 metros da Torre Eiffel, almoço e guia turistico
              inclusos.
              <br />
              <b>Por apenas: R$2250,99</b>
            </p>
            <a href="/about" class="btn btn-primary">Ver mais</a>
          </div>
        </div>
        <div class="card">
          <img
            src="https://q5e5q6q7.stackpathcdn.com/wp-content/uploads/2017/09/Kyoto.jpg"
            class="card-img-top"
            alt="..."
            height="221px"
          />
          <div class="card-body">
            <h5 class="card-title">Kyoto(Japão)</h5>
            <p class="card-text">
              4 dias na Cidade dos samurais, com passagem de ida e volta,
              estadia em em pousada a 600 metros do centro, almoço e guia
              turistico inclusos.
              <br />
              <b>Por apenas: R$4899,99</b>
            </p>
            <a href="/about" class="btn btn-primary">Ver mais</a>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>
<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
.Welcome {
  text-align: center;
  font-family: "Times New Roman", Times, serif;
  padding-top: 30px;
  padding-bottom: 20px;
  text-decoration: underline;
}
.Popu {
  font-family: Georgia, "Times New Roman", Times, serif;
  font-size: xx-small;
  padding-top: 5px;
  padding-bottom: 5px;
  padding-left: 20px;
}
.Popu2 {
  font-family: Georgia, "Times New Roman", Times, serif;
  font-size: xx-small;
  padding-top: 100px;
  padding-bottom: 5px;
  padding-left: 20px;
}
.card {
  left: 0px;
}
.card-group {
  padding-left: 10px;
  padding-right: 10px;
}
.exterior {
  padding-top: 0px;
}
</style>
