<template>
    <div>
        <v-app-bar class="nav_menu"
        height="88"
        width="1440">
            <v-col>
               <img src="img/logo.png" class="nav_img"> 
            </v-col>
                <v-list class="v-list"
                width="256"
                height="56">
                    <v-list-item class="list-item">
                    <v-avatar class="v-avatar" color="grey">
                        <span class="white--text text-h5">RC</span>
                    </v-avatar>
                    <v-list-item link>
                    <v-list-item-content>
                        <v-list-item-title class="text-h8">
                        Regina Cooper
                        </v-list-item-title>
                        <v-list-item-subtitle>Washington, DC, USA</v-list-item-subtitle>
                    </v-list-item-content>
                    <v-list-item-action>
                        <v-icon>mdi-menu-down</v-icon>
                    </v-list-item-action>
                    </v-list-item>
                    </v-list-item>
                </v-list>
                
        </v-app-bar>
    </div>
</template>

<style>
    .nav_img{
        margin-right: 49px;
    }
    .nav_menu{
        height: 88px;
    }
    .list-item{
        
        padding: 0px;
    }
    .v-avatar{
        width: 28px;
        height: 24px;
    }
    .v-list{
        padding: 0px 0px 0px 0px;
    }
</style>