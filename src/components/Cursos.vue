<script setup>

</script>

<template>
  <div class="container text-aling-center">
    <h1>Cursos de programación</h1>
    <p>Aprende con nuestros cursos de programación, nuestros cursos van desde principiante a nivel avanzado, podras elegir entre las tecnologías que más te atraigan.</p>
  </div>
  
 <div class="container justify-content-center ">
    <div class="row row-cols-md-3 mt-5 justify-content-center align-items-center">
      <div class="col-4">
        <div class="card h-100" >
          <img src="/src/assets/images/Angular.jpg" class="card-img-top img-fluid" alt="...">
          <div class="card-body">
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          </div>
        </div>
      </div>
      <div class="col-4">
        <div class="card h-100" >
          <img src="/src/assets/images/React.jpg" class="card-img-top img-fluid" alt="...">
          <div class="card-body">
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          </div>
        </div>
      </div>
      <div class="col-4">
        <div class="card h-100">
          <img src="/src/assets/images/Vue.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          </div>
        </div>
      </div>
    </div>
    <div class="row mt-5 justify-content-center align-items-center">
      <div class="col-4">
        <div class="card h-100">
          <img src="/src/assets/images/Java.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          </div>
        </div>
      </div>
      <div class="col-4">
        <div class="card h-100">
          <img src="/src/assets/images/JavaScript.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          </div>
        </div>
      </div>
      <div class="col-4">
        <div class="card h-100">
          <img src="/src/assets/images/Python.jpeg" class="card-img-top" alt="...">
          <div class="card-body">
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
  <nav aria-label="Page navigation">
  <ul class="pagination justify-content-center mt-3">
    <li class="page-item"><a class="page-link" href="#">Previous</a></li>
    <li class="page-item"><a class="page-link" href="#">1</a></li>
    <li class="page-item"><a class="page-link" href="#">2</a></li>
    <li class="page-item"><a class="page-link" href="#">3</a></li>
    <li class="page-item"><a class="page-link" href="#">Next</a></li>
  </ul>
  </nav>
</template>
<style scoped>
.container{
  
  margin: 0 auto;
}
.container h1{
  color: #103778;
  text-align: center
}
.container p{
  text-align: center;
}
.card img{
  height: 25vh;
  width: 100%;
}

</style>
