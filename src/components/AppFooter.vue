<script>

export default {
    name: "FooterSection",
    data() {
        return {
            FooterNav: [
                {
                    Name: "DC COMICS",
                    NavElement: ["Characters", "Comics", "Movies", "TV", "Games", "Videos", "News"]
                },
                {
                    Name: "SHOP",
                    NavElement: ["Shop DC", "Shop DC Collectibles"]
                },
                {
                    Name: "DC",
                    NavElement: ["Terms of Use", "Privacy Policy (New)", "Ad Choiches", "Advertising", "jobs", "Subscriptions", "Talent Workshops", "CPSC", "Ratings", "Shop Help", "Contact Is"]
                },
                {
                    Name: "SITES",
                    NavElement: ["DC", "MAD Magazine", "DC Kid", "DC Universe", "DC Power Visa"]
                },
            ]
        }
    }
}

</script>

<template>
    <footer>
        <div class="wrapper">
            <div class="FooterList">
                <ul class="Nav" v-for="element in FooterNav">

                    <li class="ListName">
                        {{ element.Name }}
                        <ul>
                            <li class="ListItem" v-for="contenuti in element.NavElement">{{ contenuti }}</li>
                        </ul>
                    </li>
                </ul>
            </div>
            <div class="img-wrapper">
                <img src="../assets/dc-logo-bg.png" class="dc-img" alt="">
            </div>
        </div>
        <div class="box">
            <div>
                <button>SIGN-UP NOW!</button>
            </div>
            <div class="flex">
                <span> <strong>FOLLOW US</strong> </span>
                <img src="../assets/footer-facebook.png" alt="">
                <img src="../assets/footer-periscope.png" alt="">
                <img src="../assets/footer-pinterest.png" alt="">
                <img src="../assets/footer-twitter.png" alt="">
                <img src="../assets/footer-youtube.png" alt="">
            </div>
        </div>
    </footer>

</template>
