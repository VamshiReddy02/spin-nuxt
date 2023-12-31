<template>
    <div>
        <div class="container">
      <main>
        <h1 class="title">
          Welcome to <a href="https://developer.fermyon.com/spin">Spin</a> and
          <a href="https://nuxt.com/">Nuxt</a>
        </h1>

        <p class="description">
          Get started by editing <code>pages/index.vue</code>. When you are done,
          you can run <code>spin build</code> and <code>spin up</code> to
          statically export your Nuxt application and start Spin!
        </p>

        <div class="grid">
          <a href="https://nuxt.com/docs/getting-started/introduction" class="card">
            <h3>Nuxt Documentation &rarr;</h3>
            <p>Find in-depth information about Nuxt features and API.</p>
          </a>

          <a href="https://developer.fermyon.com/spin" class="card">
            <h3>Spin documentation &rarr;</h3>
            <p>Learn about Wasm serverless applications with Spin.</p>
          </a>

          <a href="https://fermyon.com/cloud" class="card">
            <h3>Meet Fermyon Cloud &rarr;</h3>
            <p>Learn about the fastest way to run your Spin applications!</p>
          </a>

          <a href="https://developer.fermyon.com/cloud/index" class="card" >
            <h3>Deploy your apps &rarr;</h3>
            <p>Deploy your Spin applications with Fermyon Cloud.</p>
          </a>
        </div>
      </main>
    </div>
    </div>
</template>

<script>
    
</script>

<style scoped>
.container {
    min-height: 100vh;
    padding: 0 0.5rem;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  
  .title a {
    color: #12b488;
    text-decoration: none;
  }
  
  .title a:hover,
  .title a:focus,
  .title a:active {
    text-decoration: underline;
  }
  
  .title {
    margin: 0 0 1rem;
    line-height: 1.15;
    font-size: 3.6rem;
  }
  
  .title {
    text-align: center;
  }
  
  .title,
  .description {
    text-align: center;
  }
  
  .description {
    line-height: 1.5;
    font-size: 1.5rem;
  }
  
  .grid {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
  
    max-width: 800px;
    margin-top: 3rem;
  }
  
  .card {
    margin: 1rem;
    flex-basis: 45%;
    padding: 1.5rem;
    text-align: left;
    color: inherit;
    text-decoration: none;
    border: 1px solid #eaeaea;
    border-radius: 10px;
    transition: color 0.15s ease, border-color 0.15s ease;
  }
  
  .card:hover,
  .card:focus,
  .card:active {
    color: #12b488;
    border-color: #12b488;
  }
  
  .card h3 {
    margin: 0 0 1rem 0;
    font-size: 1.5rem;
  }
  
  .card p {
    margin: 0;
    font-size: 1.25rem;
    line-height: 1.5;
  }
  
  .logo {
    height: 1em;
  }
  
  @media (max-width: 600px) {
    .grid {
      width: 100%;
      flex-direction: column;
    }
  }
  code {
          background: #fafafa;
          border-radius: 5px;
          padding: 0.75rem;
          font-size: 1.1rem;
          font-family: Menlo, Monaco, Lucida Console, Liberation Mono,
            DejaVu Sans Mono, Bitstream Vera Sans Mono, Courier New, monospace;
        }
        main {
          padding: 5rem 0;
          flex: 1;
          display: flex;
          flex-direction: column;
          justify-content: center;
          align-items: center;
        }

</style>