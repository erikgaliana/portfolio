<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Welcomme to my portfolio. Here you can find my most recent projects.
      
    </p>
    <h3>Solve it App</h3>
    <h5>Front End: React, CSS & Bulma</h5>
    <h5>Back End: MongoDB, Express, NodeJs</h5>
   
    <ul>
      <li><a href="https://github.com/erikgaliana/Solve-it-Client" target="_blank" rel="noopener">Front end</a></li>
      <li><a href="https://github.com/erikgaliana/Solveit-server-v2" target="_blank" rel="noopener">Back end</a></li>
       <li><a href="https://solveitapp.herokuapp.com/signup" target="_blank" rel="noopener">Deploy</a></li>
       <li><a href="https://docs.google.com/presentation/d/1EMXLbaZ9w-EUtdVOb-lHWrEL6W_3imFUzu1hxSstYQg/edit#slide=id.gc6f80d1ff_0_0" target="_blank" rel="noopener">Slides</a></li>
    </ul>
    <h3>Cyrano App</h3>
    <h5>Front End: Handlebars, CSS & SASS.</h5>
    <h5>Back End: MongoDB, Express, Nodejs.</h5>
    <ul>
      <li><a href="https://github.com/erikgaliana/cyrano" target="_blank" rel="noopener">Front end & Back End</a></li>
      
       <li><a href="https://cyrano-app.herokuapp.com/" target="_blank" rel="noopener">Deploy</a></li>
       <li><a href="https://docs.google.com/presentation/d/1Frh8japy7cSnuAcvR2Q2peMtav2uDUv8s_auTBW3t88/edit#slide=id.p" target="_blank" rel="noopener">Slides</a></li>
    </ul>
    <h3>Space Invaders Project</h3>
    
    <ul>
      <li><a href="https://github.com/erikgaliana/space-invaders" target="_blank" rel="noopener">ES5 version</a></li>
      <li><a href="https://github.com/erikgaliana/space-invaders/tree/es6-refactor" target="_blank" rel="noopener">ES6 version</a></li>
      <li><a href="https://erikgaliana.github.io/space-invaders/" target="_blank" rel="noopener">Deploy</a></li>
      <li><a href="https://docs.google.com/presentation/d/1831IUdaGy_n7sWcznBENAP65qSTW7FH7K6IxLQMOq8U/edit#slide=id.gc6f59039d_0_0">Slides</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Portfolio',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
