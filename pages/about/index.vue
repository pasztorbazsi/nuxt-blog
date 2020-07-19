<template>
  <div class="about-page">
    <h1>This is my absolutely fantastic "About Me" Page!</h1>
    <p>I just wanted to play around a little with Nuxt.js (which is actually Vue.js underneath the hood).</p>
    <p>And this little site was the result.</p>
    <p></p>
    <p>Please visit <a class="go-to" href="https://the-dev-you-need.netlify.app/" target="_blank">my portfolio</a> to know more.</p>
  </div>
</template>

<style scoped>
.about-page {
  text-align: center;
  padding: 30px;
}

.go-to a:hover,
.go-to a:active {
  color: #ccc;
  text-decoration: none;  
}

.go-to,
.go-to a:visited {
  color: black;
  text-align: center;
  margin-top: 20px;
}

</style>
