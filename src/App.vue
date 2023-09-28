<template>
  <div class="main-landing">
    <div class="circle"></div>
    <div class="container">
      <div class="title">
        <h2>Создавайте. Копируйте.<br/> Заполняйте.</h2>
        <p>по пунктам — для важных чек-листов и задач</p>
      </div>
      <div class="cta-action">
        <a class="btn cta" href="#">Создать чек-лист</a>
      </div>
    </div>

    <div class="grid">
      <img src="./assets/grid.svg">
    </div>
  </div>
</template>

<style lang="scss" scoped>
.title {
  text-align: center;
  margin-top: 20.104vh;

  h2 {
    font-size: 64px;
    font-weight: 700;
    margin: 0 0 16px;
  }

  p {
    margin: 0;
    font-size: 32px;
    opacity: .8;
  }
}

.cta-action {
  margin: 0 auto;
  width: 100%;
  text-align: center;
  justify-content: center;
  align-items: center;
  display: flex;
  margin-top: 56px;
}


.grid {
  margin-top: 68px;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
}
</style>