<template>
  <div class="container-fluid background">
    <div class="container-fluid">
        <h2>Product categories</h2>
      <div class="row row-gap text-center">
        <div class="col-sm-4 col-4">
             <font-awesome-icon icon="syringe" style="color: #000000; font-size: 24px" />
               <router-link to="../products/AntiMalaria">
               <p class="category-paragraph">Anti-malaria</p>
           </router-link>
        </div>
        <div class="col-sm-4 col-4 ">
             <font-awesome-icon icon="pills" style="color: #000000; font-size: 24px" />
             <router-link to="../products/Multivitamins">
             <p class="category-paragraph">Multivitamins</p>
              </router-link>
        </div>
        <div class="col-sm-4 col-4">
             <font-awesome-icon icon="stethoscope" style="color: #000000; font-size: 24px" />
             <router-link to="../products/Equipments">
             <p class="category-paragraph">Equipments</p>
              </router-link>
        </div>
      </div>

       <div class="row row-gap">
        <div class="col-sm-4 col-4">
             <font-awesome-icon icon="venus-mars" style="color: #000000; font-size: 24px" />
             <router-link to="../products/Contraceptives">
             <p class="category-paragraph">Contraceptives</p>
              </router-link>
        </div>
        <div class="col-sm-4 col-4">
             <font-awesome-icon icon="diagnoses" style="color: #000000; font-size: 24px" />
            <router-link to="../products/Antibiotics">
             <p class="category-paragraph">Antibiotics</p>
              </router-link>
        </div>
        <div class="col-sm-4 col-4">
             <font-awesome-icon icon="eye" style="color: #000000; font-size: 24px" />
             <router-link to="../products/VisionDrugs">
             <p class="category-paragraph">Vision drugs</p>
              </router-link>
        </div>
      </div>

       <div class="row row-gap">
        <div class="col-sm-4 col-4">
             <font-awesome-icon icon="tablets" style="color: #000000; font-size: 24px" />
             <router-link to="../products/UlcerAndGastro">
             <p class="category-paragraph">Ulcer and gastro drugs</p>
              </router-link>
        </div>
        <div class="col-sm-4 col-4">
             <font-awesome-icon icon="bolt" style="color: #000000; font-size: 24px" />
            <router-link to="../products/Analgesics">
             <p class="category-paragraph">Analgesics</p>
              </router-link>
        </div>
        <div class="col-sm-4 col-4">
             <font-awesome-icon icon="heartbeat" style="color: #000000; font-size: 24px" />
             <router-link to="../products/AntiHypertensives">
             <p class="category-paragraph">Anti-hypertensives</p>
              </router-link>
        </div>
      </div>
    </div>

 
  </div>
</template>

<script>
export default {
  name: "Categories"
};
</script>

<style scoped>
.background {
  padding-top: 5em;
  
}

.background h2{
  font-weight: 600;
  font-size: 1.5em;
  color: #000;
}

.category-paragraph{
    margin-top: 3.5em;
    font-size: 13px;
    color: #000;
    font-family: Roboto;
    /* line-height: 1.em; */
}

.row-gap{
    margin-top: 4em;
}

div.row div{
     text-align: center;
}

/* @media (max-width: 575.98px) {
     div.row div{
          width: 7em;
          margin-right: 19px;
     }

     div.row p{
          font-size: 0.9em;
     }
 } */
</style>