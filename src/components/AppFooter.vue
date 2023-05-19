<script>
export default {
    name: "AppFooter",
}
</script>

<template>
    <div class="container-fluid bg-primary">
        <div class="container p-4">
            <div class="row">
                <div class="d-flex justify-content-evenly align-items-center mt-2 mb-2">
                    <div class="d-flex align-items-center">
                        <img class="image-fluid my-footer-img" src="../assets/img/buy-comics-digital-comics.png" alt="digital-comics">
                        <span>DIGITAL COMICS</span>
                    </div>
                    <div>
                        <img class="image-fluid my-footer-img" src="../assets/img/buy-comics-merchandise.png" alt="digital-comics">
                        <span>DC MERCHANDISE</span>
                    </div>
                    <div>
                        <img class="image-fluid my-footer-img" src="../assets/img/buy-comics-subscriptions.png" alt="digital-comics">
                        <span>SUBSCRIPTION</span>
                    </div>
                    <div>
                        <img class="image-fluid my-footer-img" src="../assets/img/buy-comics-shop-locator.png" alt="digital-comics">
                        <span>COMIC SHOP LOCATOR</span>
                    </div>
                    <div>
                        <img class="image-fluid my-footer-img" src="../assets/img/buy-dc-power-visa.svg" alt="digital-comics">
                        <span>DC POWER VISA</span>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style>
    .my-footer-img {
        width: 3rem;
    }

    span {
        font-size: 1rem;
        color: white;
        margin-left: 1rem;
    }
</style>