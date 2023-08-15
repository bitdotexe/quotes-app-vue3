<template>
  <div class="container">
    <br />
    <div class="row text-center">
      <h1>Welcome to QuoteSymphony</h1>
    </div>
    <hr />
    <div class="row">
      <div class="row text-center">
        <div class="col" id="quoteLine">
          "El éxito no es la clave de la felicidad. La felicidad es la clave del
          éxito. Si amas lo que haces, tendrás éxito."
        </div>
      </div>
      <div class="row text-end">
        <div class="col" id="authorLine">- Albert Schweitzer</div>
      </div>
    </div>
    <div class="row justify-content-center" id="buttonChangeQuote">
      <div class="col-auto">
        <button type="button" class="btn btn-secondary">Change quote</button>
      </div>
    </div>
  </div>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@100&display=swap");

h1,
button,
#quoteLine,
#authorLine {
  color: white;
  font-family: "Josefin Sans", sans-serif;
}
#quoteLine {
  font-style: italic;
  font-size: 1.5rem;
}

h1 {
  font-size: 3.5rem;
}

hr {
  color: white;
}

.container {
  max-width: 800px;
  width: 100%;
  padding: 20px;
  box-sizing: border-box;
}
@media (max-width: 768px) {
  .container {
    padding: 10px;
  }
}

#buttonChangeQuote {
  padding: 3rem 0rem;
}

button {
  background: #414141;
}
</style>
