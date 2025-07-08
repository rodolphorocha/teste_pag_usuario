<script setup>
</script>

<template>
  <main>
 <div class="fundo">

    <!-- <img src="/img/Ellipse 2.png" alt=""> -->

  <div class="card">

    <h2>GustavoLopes</h2>
    <p>@surikkto</p>

    <ul>
      <li>
       <span> 24 </span><br> seguidores
      </li>
      <li>
      <span>  69 </span><br> seguindo
      </li>
    </ul>
    <div class="editar">
      <p> Editar perfil</p>
    </div>

    <div class="biografia">
      <p>
        -Suricato
        -Amigo do Maia
        -Flamengo no coração❤❤
        -Joinville - 17y️
      </p>
    </div>

  </div>
</div>
</main>
</template>

<style scoped>


.fundo {
  background-color: #2F9E41;
  position: relative;

}

img {
  position: absolute;
  top: 10%;
  left: 50%;
  z-index: 2;
  text-align: center;
  transform: translateX(-50%);
  pointer-events: none;
}

.card {
  margin: auto;
  background-color: white;
  text-align: center;
  width: 50%;
  overflow: hidden;
  border-radius: 12px;
  position: relative;
  z-index: 1;
}

.card h2 {
  font-weight: bold;
  color: black;
  font-size: 1.8rem;
}

.card p {

}

.card ul {
  display: flex;
  justify-content: center;
  margin: 1vw 2vw 1vw 2vw;

}

.card ul li  {
  margin: auto;
  font-size: 1.3rem;
}

.card ul li span {
  color: black;
  font-weight: bold;
}
</style>
