<script>

import ComicsList from './ComicsList.vue';


export default {
  components: {
   ComicsList,
    
  },
}





</script>



<template>

    <div id="app">
        <div class="slide" v-for="image, i in images">
            <img :src="image" alt="">
        </div>
        <div id="thumbmailsContainer">
            <img v-for="thumbnail in images" :src="thumbnail">


        </div>

    </div>
    <div class="container">
        <div class="row">
            <div class="col-12 m-4">
                <h2>Content goes here</h2>
            <ComicsList></ComicsList>
            </div>
        </div>
    </div>
    <div class="blue col-sm-12 p-5">
        <div class="container text-center">
            <div class="row align-items-center">
                <div class="col">
                    <img class="photo" src="../assets/buy-comics-digital-comics.png" alt="">Digital Comics

                </div>
                <div class="col">
                    <img class="photo" src="../assets/buy-comics-merchandise.png" alt="">DC Merchandise

                </div>
                <div class="col">
                    <img class="photo" src="../assets/buy-comics-subscriptions.png" alt="">Subscriptions
                </div>
                <div class="col">
                    <img class="photo" src="../assets/buy-comics-shop-locator.png" alt="">Comic Shop Locator
                </div>
                <div class="col">
                    <img class="photo" src="../assets/buy-dc-power-visa.svg" alt="">DC Power Visa
                </div>
            </div>
        </div>
    </div>




</template>


<style></style>