<template>
  <div class="container">
    <div>
      <div>
        <img src="https://appservice.azureedge.net/images/static-apps/v3/staticapps.svg">
      </div>
      <h1 class="title">
        Azure Static Web Apps<br>is awesome
      </h1>
      <div class="links">
        <a
          href="https://azure.microsoft.com/ja-jp/services/app-service/static/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          Azure Static Web Apps
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

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
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #ffffff;
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
</style>
