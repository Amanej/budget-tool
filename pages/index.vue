<template>
  <section class="container">
    <div>
      <div class="mainSplash">
        <h2>Budsjetter en post</h2>
        <nuxt-link to="/registrer-inntekt">Registrer inntekt</nuxt-link>
        <nuxt-link to="/registrer-kostnad">Registrer kostnad</nuxt-link>
      </div>
    </div>
  </section>
</template>


<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

.mainSplash > h2 {
  margin-bottom: 40%;
  font-size: 28px;
}

a {
  margin: 20px;
}
</style>
