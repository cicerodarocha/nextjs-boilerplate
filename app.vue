<template>
  <div>
    <h1>Hello World !!! </h1>
  </div>
  <iframe id='browse' src='https://santacasa.com.br' allowpopups>
  </iframe>
</template>
<script>
  document.querySelector('#browse').loadURL('https://santacasa.com.br')
</script>
<style>
  #browse {
    width:100vw;
    height:80vh;
  }
</style>
