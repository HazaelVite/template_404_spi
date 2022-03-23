<template>
    <div class="stylesHeader">
        <v-container>
            <v-row align="center" justify="center">
                <v-col cols="3">
                    <a href="https://quimica.unam.mx/" target="_blank">
                        <v-img src="@/assets/logo_fq.png" height="90" contain></v-img>
                    </a>
                </v-col>
                <v-col cols="5" align="center">
                    <div id="titleHeader">
                        Universidad Nacional Autónoma de México<br>
                        Facultad de Química
                    </div>
                </v-col>
                <v-col cols="3">
                    <a href="http://www.unam.mx" target="_blank">
                        <v-img src="@/assets/logo_unam.png" height="100" contain></v-img>
                    </a>
                </v-col>
            </v-row>
        </v-container>
    </div>
</template>

<script>
    export default {
        name: "Header"
    }
</script>

<style>
    .stylesHeader{
        background-color: #1c3d6c;
        color: #fff;
        font-weight: 500;
        font-size: 24px;
    }
    @media (max-width: 839px){
        #titleHeader{
            display: none;
        }
    }
</style>