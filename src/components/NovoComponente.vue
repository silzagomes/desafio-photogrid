<template>
<v-app>
    <div   class="novo-componete">

        <div class="inicio">
            <div>
                <v-avatar size="60">
                <img src="https://thumbs.dreamstime.com/b/arranjo-vertical-%C3%A0-escala-cinzenta-de-uma-escada-entre-dois-edif%C3%ADcios-que-conduz-subida-balan%C3%A7a-162943170.jpg">
                </v-avatar >
            </div>

            <div class="topo">
                <v-container>
                <h2 class="text-sm-left">Aline's Photo Grid</h2>
                <p class="text-sm-left">I'm a frontend developer from RJ,Brazil</p>
                </v-container>
            </div>
         </div>

            <div class="imagens">
                <v-row>
                    <v-col v-for="n in 12"  :key="n" class="d-flex child-flex" cols="4">
                        <v-card>
                            <v-img :src="`https://i.pinimg.com/736x/1f/28/c0/1f28c0ed2336583beef229a71cf7053e.jpg`"
                                            max-width="100%">
                            </v-img>
                            <v-card-text >♡ Lorem ipsum </v-card-text>
                        </v-card>
                    </v-col>
                </v-row>
            </div>
                        
            <div class="final">
                <h6><strong>   My Photo Grid desenvolvido por Silza|WoMakersCode RJ</strong></h6>
            </div>
    </div>
</v-app>    
</template>

<script>
export default {
    name:'NovoComponente' 
}
  
</script>

<style scoped>
     
.inicio {
        display: flex;
        justify-content:flex-start;
        align-items: center;
        text-align:center;
        padding-left: 5%;
        padding-top: 5%;
        flex-direction: row;
}

.topo{
        display: flex;
        justify-content:left;
        text-align:left;
        align-items:left;
        padding-left: 2%;
}

.imagens{
       padding: 5%;
       font-size:150%
}

.final{
    display: flex;
    justify-content:center;
    align-items: center;
    text-align:center;
}

</style>
