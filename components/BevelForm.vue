<template>
  <form class="bevel d-flex py-1">
    <div class="d-inline-block flex-grow-1 d-flex">
      <input type="email" placeholder="enter your email address" class="emailForm  my-auto pl-3 py-2">
    </div>
    <button class="btn btn-orange px-md-4 py-md-2 text-white flex-shrink-1">notify me</button>
  </form>  
</template>

<style scoped>
.bevel{
  box-sizing: content-box;
  box-shadow: inset 4px 4px 8px #03030A, inset -4px -4px 8px #24242E;
  background: #0F0F20;
  border: none;
  font-family: muli;
  font-weight: 800;
  font-size: 1.5rem;
}
input::placeholder{
  font-family: muli;
  font-weight: 800;
}

.emailForm{
    background: none;
    border: none;
    width: 100%;
    color: white;
    /* box-shadow: inset 4px 4px 8px #03030A, inset -4px -4px 8px #24242E; */
}
.btn-orange{
  background: linear-gradient(224.85deg, #F8501C 2.25%, #FFAB1D 100%);
  color: white;
  height: 100%;
  font-weight: 600;
  font-size: 1em;
}
</style>