<script>
export default {
    data() {
        return {};
    },
    computed: {},
    methods: {},
    async mounted() {},
};
</script>

<template>
    <footer class="text-center text-lg-start text-white bg-dark">
        <!-- Grid container -->
        <div class="container p-2">
            <div class="row my-2">
                <!--Grid column-->
                <div class="col-lg-3 col-md-6 mb-md-0 mt-1">
                    <div class="rounded-circle bg-white shadow-1-strong d-flex align-items-center justify-content-center mb-1 mx-auto" style="width: 100px; height: 100px">
                        <img src="../assets/mosque.png" height="70" alt="" loading="lazy" />
                    </div>
                    <p
                        class="text-center"
                        style="
                            font-style: italic;
                            font-weight: bold;
                            background: -webkit-linear-gradient(90deg, #096479, #734dbf, #734dbf);
                            background: linear-gradient(90deg, #096479, #734dbf, #734dbf);
                            border-radius: 10px;
                        "
                    >
                        Cami Çinicilik Hizmetleri
                    </p>
                    <ul class="list-unstyled d-flex flex-row justify-content-center">
                        <li>
                            <a href="#"><img width="25" height="25" src="../assets/icons/icons8-facebook.svg" alt="facebook-icon" /></a>
                        </li>
                        <li>
                            <a href="#"><img width="25" height="25" src="../assets/icons/icons8-instagram.svg" alt="instagram-icon" /></a>
                        </li>
                        <li>
                            <a href="#"><img width="25" height="25" src="../assets/icons/icons8-tiktok.svg" alt="tiktok-icon" /></a>
                        </li>
                        <li>
                            <a href="#"><img width="26" height="26" src="../assets/icons/icons8-youtube.svg" alt="youtube-icon" /></a>
                        </li>
                    </ul>
                </div>
                <!--Grid column-->
                <div class="col-lg-3 col-md-6 mb-1 mb-md-0 mt-1">
                    <h5 class="text-bold mb-1">HİZMETLERİMİZ</h5>
                    <ul class="list-unstyled">
                        <li class="mb-1">
                            <span class="text-white">Cami Çinicilik</span>
                        </li>
                        <li class="mb-1">
                            <span class="text-white">Otel ve Hamam Çinicilik</span>
                        </li>
                        <li class="mb-1">
                            <span class="text-white">Villa Çinicilik</span>
                        </li>
                        <li class="mb-1">
                            <span class="text-white">Şadırvan Çinicilik</span>
                        </li>
                        <li class="mb-1">
                            <span class="text-white">Nakkaş</span>
                        </li>
                        <li class="mb-1">
                            <span class="text-white">Altın Varak</span>
                        </li>
                        <li class="mb-1">
                            <span class="text-white">Hat Yazıları</span>
                        </li>
                    </ul>
                </div>
                <!--Grid column-->
                <div class="col-lg-3 col-md-6 mb-1 mb-md-0 mt-1">
                    <h5 class="text-uppercase mb-1">Referanslarımız</h5>
                    <ul class="list-unstyled">
                        <li class="mb-1">
                            <span class="text-white">Gaziantep </span>
                        </li>
                        <li class="mb-1">
                            <span class="text-white">Erzurum</span>
                        </li>
                        <li class="mb-1">
                            <span class="text-white">İstanbul</span>
                        </li>
                        <li class="mb-1">
                            <span class="text-white">Afyon</span>
                        </li>
                        <li class="mb-1">
                            <span class="text-white">Kocaeli</span>
                        </li>
                        <li class="mb-1">
                            <span class="text-white">Tekirdağ</span>
                        </li>
                        <li class="mb-1">
                            <span class="text-white">Denizli</span>
                        </li>
                    </ul>
                </div>
                <!--Grid column-->
                <div class="col-lg-3 col-md-6 mb-1 mt-1">
                    <h5 class="text-bold mb-1">İLETİŞİM</h5>
                    <ul class="list-unstyled">
                        <li>
                            <p class="mb-2"><img src="../assets/icons/icons8-address-25.png" alt="telefon" /> Bingöl / Merkez</p>
                        </li>
                        <li>
                            <p class="mb-2"><img src="../assets/icons/icons8-phone.svg" alt="telefon" /> +90 552 807 60 89</p>
                        </li>
                        <li>
                            <p class="mb-2"><img src="../assets/icons/icons8-letter-25.png" alt="telefon" /> camicinicilik@gmail.com</p>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
        <!-- Grid container -->
        <div class="text-center p-2 text-white" style="background-color: #096479">
            ©{{ new Date().getFullYear() }} Cami Çinicilik:
            <span class="text-white" style="font-style: italic">Tüm hakları saklıdır.</span>
        </div>
    </footer>
</template>
