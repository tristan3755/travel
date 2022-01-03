<template>

<div class="description">
    <div>
        <p>Une app de <br>Traveling</p>
        <span></span>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Provident vero voluptatem, praesentium mollitia dolores exercitationem necessitatibus, sint sit voluptate porro sapiente facere itaque cumque, dolor natus consectetur amet ea reprehenderit?</p>
    </div>
</div>

</template>
    
<script setup>


</script>

<style scoped>
.description{
    width: 100%;
    min-height: 100vh;
    position: relative;
    background-color: #FFD38A;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-evenly;
}
.description div:nth-child(1){
    min-height: 70vh;
    flex: 0.5;
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    align-items: center;
            border-radius: 15px;
background: #FFD38A;
box-shadow:  20px 20px 60px #d9b375,
             -20px -20px 60px #fff39f;
      animation:morphisme infinite 15s;
}
.description div:nth-child(1) p:nth-child(1){
  font-family: 'Roboto Slab', serif;
  font-weight: bold;
  font-size: 7.5vmin;
  letter-spacing: 1vmin;
  color: white;
  text-transform: uppercase;
  
}
.description div:nth-child(1) span{
 width: 40%;
 height: 2px;
 background-color: white;
 margin-top: -10vh;
}
.description div:nth-child(1) p:nth-child(3){
  font-size: 1.9vmin;
  color: white;
  text-transform: uppercase;
  font-family: 'Roboto', sans-serif;
  width: 60%;
  font-weight: bold;
  letter-spacing: 0.50px;

}
@keyframes morphisme{
    0%{
             border-radius: 15px;
background: #FFD38A;
box-shadow:  20px 20px 60px #d9b375,
             -20px -20px 60px #fff39f;
    }
    25%{
             border-radius: 135px;
background: #FFD38A;
box-shadow:  20px 20px 60px #d9b375,
             -20px -20px 60px #fff39f;
    }
50%{
             border-radius: 25px;
background: #FFD38A;
box-shadow:  20px 20px 60px #d9b375,
             -20px -20px 60px #fff39f;
    }
    75%{
             border-radius: 50%;
background: #FFD38A;
box-shadow:  20px 20px 60px #d9b375,
             -20px -20px 60px #fff39f;
    }100%{
             border-radius: 15px;
background: #FFD38A;
box-shadow:  20px 20px 60px #d9b375,
             -20px -20px 60px #fff39f;
    }
}

</style>