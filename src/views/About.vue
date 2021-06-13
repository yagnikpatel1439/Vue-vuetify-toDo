<template>
    <div class="circle-bg">
        <div class="card">
            <span class="
            title 
            ma-16 
            font-weight-black"
            >Yagnik Patel</span>
          <v-list
            color="transparent"
            justify="space-around"
            class="ma-10"
          
          >
            <v-list-item>
               <v-btn
               class=""
                fab
                dark
                small
                color="dark"
                href="https://webme.vercel.app/"
                target="_blank"
                >
                <v-icon dark>
                  mdi-web
                </v-icon>
                </v-btn>
            </v-list-item>
            <v-list-item>
               <v-btn
                class="ma-10"
                fab
                dark
                small
                color="dark"
                href="https://www.linkedin.com/in/yagnik-patel/"
                target="_blank"
                >
                <v-icon dark>
                  mdi-account-tie-outline
                </v-icon>
                </v-btn>
            </v-list-item>
            <v-list-item>
               <v-btn
                fab
                dark
                small
                color="dark"
                href="https://github.com/yagnikpatel1439"
                target="_blank"
                >
                <v-icon dark>
                  mdi-xml
                </v-icon>
                </v-btn>
            </v-list-item>   
          </v-list>
        </div>
    </div>
</template>

<style scoped>
  

body {
        background: rgb(30, 30, 30);
        background: linear-gradient(123deg, rgba(32, 35, 32, 1) 0%, rgba(124, 48, 63, 1) 100%);
        background-attachment: fixed;
        font-family: 'Roboto', sans-serif;
}
.circle-bg {
        width: 340px;
        height: 340px;
        background: linear-gradient(135deg, rgba(220, 100, 42, 1) 0%, rgba(215, 75, 100, 1) 100%);
        border-radius: 100%;
        display: flex;
        align-items: center;
        justify-content: end;
        margin: 200px auto;
 }

 .card {
        background: #fff;
        width: 250px;
        height: 410px;
        border-radius: 30px;
        
        margin: auto;
        position: relative;
        top: -42px;
        transform: rotate(-8deg);
        background: rgb(115 115 115 / 30%);
        background: linear-gradient(135deg, rgba(255, 255, 255, 0.3) 0%, rgb(120 120 120 / 30%) 42%, rgb(51 51 51 / 30%) 100%);
        backdrop-filter: blur(10px);
        border: 1px solid rgb(122 122 122 / 30%);
    }

</style>