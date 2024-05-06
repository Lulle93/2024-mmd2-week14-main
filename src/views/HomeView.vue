<script setup>
    
    //   // ternary operator instead of if/else
    //   // return categoryFilter ? portfolioItems.value.filter(item => item.category === categoryFilter) : portfolioItems.value;
    // });
    </script>


<template>
  <main>
    <header>
      <div class="logo">
        <img src="../assets/Logo vue.png" alt="Logo"> 
      </div>
    </header>
  

    <h1 class="text-3xl font-bold underline">
    </h1>
    

    <div class="video">
      <iframe width="520" height="310" src="https://www.youtube.com/embed/Z07KccsnG4w" title="Video CV" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>


    <div class="greenbox">
      <div class="qr">
        <img src="@/assets/qr.jpg" alt="">
      </div>
      
      <form action="#" method="post" id="signup-form">

        <input type="text" name="name" placeholder="Your Name" required>
      </form>

      <form action="#" method="post" id="signup-form">
        
        <input type="email" name="email" placeholder="Your Email" required>
      </form>

      <form action="#" method="post" id="signup-form">

        <button type="submit">Tilmeld dig</button>
      </form>
    </div>

<div class="container">
  <div class="flex flex-row">
    <div class="col-4">
      <div class="card">
          <img src="../assets/Logo Suager 1.jpg" alt="Logo til Donuts butik" class="card-img-top">
          <div class="card-body">
              <h5 class="card-tital">Et logo tom skulle være untik og noget der vækkede opmærksomhed</h5>
              <p class="card-tekst">
                  Farven har en sammenhæng med hinanden, så den røde tråd starter i logoet 
              </p>
          </div>
      </div>
    </div>
  </div>
  
  <div class="flex flex-row">
    <div class="col-4">
      <div class="card">
          <img src="../assets/Poster SuagerRuch.jpg" alt="poster"class="card-img-top">
          <div class="card-body">
            <h5 class="Card-tekst">En poster for deres nye butik</h5>
            <p class="Card-tekst">
              Poster lavet i A4 størrelse, som skal lave reklame for en ny Donuts butik åbner
            </p>
          </div>
      </div>
    </div>
  </div>

  <div class="flex flex-row">
    <div class="col-4">
      <div class="card">
        <img src="../assets/Hjemmeside til suager.png" alt="Hvordan en forside kunne se ud" class="card-img-top">
        <div class="card-body">
            <h5 class="Card-tekst">Hjemmeside</h5>
            <p class="Card-tekst">
              Hvordan et udkast kan se ud, som hjemmeside. Dog er dette en forside, og ingen undersider.
            </p>
          </div>
      </div>
    </div>
  </div>
</div>
  
<div class="container">
  <div class="flex flex-row">
    <div class="col-4">
      <div class="card">
        <img src="../assets/brochure vue.png" alt=" brochure" class="card-img-top">
        <div class="card-body">
            <h5 class="Card-tekst">brochure</h5>
            <p class="Card-tekst">
              Brochure hvor man kan se det vigtigste info, og deres mené, det går igen med de forskellige farver og elementer 
            </p>
          </div>
      </div>
    </div>
  </div>

  <div class="flex flex-row ">
    <div class="col-4">
      <div class="card">
        <img src="../assets/Instagram profil .png" alt="hvordan et post kan se ud" class="card-img-top" width="170px" height="170">
        <div class="card-body">
            <h5 class="Card-tekst">En poster for deres nye butik</h5>
            <p class="Card-tekst">
              Deres sociale medier skal også have en make over, det ville sige det hele skal have den røde tråd. Farverne gemmenkøre, og deres instagram vækker lidt ekstra opmærksomhed og genkendlighed.
            </p>
          </div>
      </div>
    </div>
  </div>
</div>

  </main>
</template>


<style lang="scss">



.container {
  display: flex;
  width: auto;
  height: auto;
  flex-wrap: wrap; 
  justify-content: center;
  align-items: flex-start;
  margin-top: 40px;
  margin-bottom: 40px;
  margin-right: 40px;
  margin-left: 40px;
}

.col-4 {
  flex: 0 0 33.33%; 
  max-width: 33.33%; 
}

.card {
  width: 100%; 
  margin: 10px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.card-img-top {
  max-width: 100%; 
  height: auto;
}

@media (max-width: 726px) {
  .col-4 {
    flex: 0 0 100%; 
    max-width: 100%;
  }
}

.card{
  position: relative;
  align-items: center;
  width: 300px;
  height: 450px;
}
.card-img-top{
  max-height: 150px;
  width: auto;
  display: block;
  margin-left: auto;
  margin-right: auto;
}
body{
  padding: 0px;
  margin: 0%;
  background-color: #e8cfc1;
}
header{
  display: flex;
  justify-content: center;
  align-items: center;
}

.logo{
  display: flex;
  justify-content: center;
  align-items: center;
  top: 0%;
  width: 250px;
  margin-bottom: 10px;
}


.qr{
  position: relative;
  height: 100px;
  width: 100px;
}

.video{
  display: flex;
  width: auto;
  height: auto;
  align-items: center;
  justify-content: center;
  margin-top: 25px;
  margin-bottom: 25px;
}

.greenbox{
  display: flex;
  gap: 50px;
  height: 150px;
  width: 100vw;
  background-color: #AAC6B2;
  justify-content: center;
  align-items: center;
  padding: 0;
  margin: 0;
}

.card {
  color:#333;
  background-color: #f4f4f4;
  padding: 1rem;
  margin: 1rem;
  border-radius: 5px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

@media (max-width: 726px) {
 
  .container {
    flex-direction: column;
    align-items: center; 
  }
  .greenbox {
    width: 100%; 
    
    display: flex;
    flex-direction: column;
    height:auto ;
    gap:10px;
    padding:15px 0;
  }
  
  .qr{
  position: relative;
  height: 100px;
  width: 100px;
}





}


</style>