<template>
    <footer class="page-footer font-small blue bg-dark">

        <div class="footer-copyright text-center py-3 text-white">
            <router-link class="text-white  mr-5" to="/avisopriv">AVISO DE PRIVACIDAD</router-link>
            <router-link class="text-white  mr-5" to="/avisolegal">AVISO LEGAL</router-link>
            © 2020 Copyright:
            <a class="text-white ml-4" > Pasteleria Yummy</a>
            <a class="text-white ml-4" href="https://www.facebook.com/Yummy-Pasteleria-103286231592222" target="_blank"><img src="../../assets/img/fb.png" alt=""></a>
            <a class="text-white ml-4" href="https://instagram.com/yummypasteleria.mty?igshid=stxx7947ld54" target="_blank"><img src="../../assets/img/instagram.png" alt=""></a>
        </div>
    </footer>
</template>

<style scoped>
    img {
        width: 50px;
    }
    .footer {
    position: absolute;
    bottom: 0;
    width: 100%;
    height: 60px;
    line-height: 60px;
    background-color: #f5f5f5;
}
</style>