<script>
import MuezzinlikData from "@/JSON/muezzinlikData.json";
export default {
    data() {
        return {
            MuezzinlikData,
        };
    },
    computed: {},
    methods: {},
    async mounted() {},
};
</script>
<template>
    <header id="header">
        <h5 class="text-center p-2">Müezzinlik</h5>
    </header>
    <section id="mimberCard">
        <div class="row row-cols-1 row-cols-md-3 g-4">
            <div class="col" v-for="item in MuezzinlikData?.Muezzinlik" :key="item">
                <div class="card">
                    <img :src="'/images/Müezzinlik/' + item.imageUrl" class="card-img-top" alt="müezzinlik cami iç mekaninda kullanilir" />
                    <div class="card-footer">
                        <small class="text-body-secondary">{{ item.footer }}</small>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
