<template>
    <div id="project">
 <div class="exampleproject">
      <span id="project"></span>
      <img style="width:300px;height:200px; margin-top:1rem; margin-left:3rem; border-radius:10px;" src="./assets/recipe.png" alt="">
      <h3 class="sub">#HTML      #CSS      #responsive</h3>
       <h2 class="blog">Recipe Blog</h2>
      <p class="abtblog">In this project, I work with HTML <br> and CSS to create a responsive<br> page. This page is similar with a <br> page. The design is from <br> devchallenge.io</p>
      <button class="demo">Demo </button>
      <button class="demo code">Code </button>
    </div>
     <div class="exampleproject one">
      <img style="width:300px;height:200px; margin-top:1rem; margin-left:3rem; border-radius:10px;" src="./assets/gallary.png" alt="">
      <h3 class="sub">#HTML      #CSS      #responsive</h3>
       <h2 class="blog">Recipe Blog</h2>
      <p class="abtblog">In this project, I work with HTML <br> and CSS to create a responsive<br> page. This page is similar with a <br> page. The design is from <br> devchallenge.io</p>
      <button class="demo">Demo </button>
      <button class="demo code">Code </button>
    </div>
     <div class="exampleproject two">
      <img style="width:300px;height:200px; margin-top:1rem; margin-left:3rem; border-radius:10px;" src="./assets/check out.png" alt="">
      <h3 class="sub">#HTML      #CSS      #responsive</h3>
       <h2 class="blog">Recipe Blog</h2>
      <p class="abtblog">In this project, I work with HTML <br> and CSS to create a responsive<br> page. This page is similar with a <br> page. The design is from <br> devchallenge.io</p>
      <button class="demo">Demo </button>
      <button class="demo code">Code </button>
    </div>
</div>
</template>

<script>
    export default {
        
    }
</script>

<style>
.sub{
 margin-left:3rem;
 font-size:16px;
 margin-top:1rem;
 font-family: 'Poppins'sans-serif;
 font-weight:300;
 word-spacing: 1ch;

}

.blog{
color:palegreen;
margin-left:3rem;
margin-top:0.5rem;
}
.abtblog{
  margin-top:-0.5rem;
  margin-left:3rem;
  font-size:14px;
}
.demo{
  width:120px;
  height:40px;
  border-radius:15px;
  background: #2196f3;
  color:white;
  border-style:none;
  margin-top:0.5rem;
  margin-left:3rem;
}
.code{
  background: transparent;
  border:1px solid  #2196f3;
  margin-left:1rem;
  color: #2196f3;
}
.exampleproject{
  width:400px;
  height:500px;
  background: rgb(19, 19, 19);
  margin:1rem;
  margin-top:3rem;
  margin-left:-2rem;
}
 .one{
  margin-left:25em;
  margin-top:-32.3rem;
}
.two{
  margin-left:52rem;
  margin-top:-32.3rem;
}
.exampleproject:hover{
  transition: 1s;
 transform: translateY(-10px);
  box-shadow:0 15px 35px rgba(15, 15, 15, 0.5);
  background: transparent;
  position: relative;
}

</style>