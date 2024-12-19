<template>
    <v-app-bar height="80" color="FEF5F8" scroll-behavior="elevate" id="inspire">
        <v-img src="/earth.png" class=""></v-img>
        <v-app-bar-title class ="text-h4">Explore</v-app-bar-title>
        <v-spacer></v-spacer>
        <v-menu transition="slide-x-transition">
            <template v-slot:activator="{props}">
            <v-btn color="#6347F9" v-bind="props">Home +</v-btn>

            </template>
            <v-list>
                <v-list-item>
                    <v-list-item-title>Home Page One</v-list-item-title>
                    <v-list-item-title>Home Page Two</v-list-item-title>
                </v-list-item>
            </v-list>
        </v-menu>
        
        
        <v-menu transition="slide-x-transition">
            <template v-slot:activator="{props}">
            <v-btn color="#6347F9" v-bind="props">Tours +</v-btn>

            </template>
            <v-list>
                <v-list-item>
                    <v-list-item-title>Tour Grid</v-list-item-title>
                    <v-list-item-title>Tour list</v-list-item-title>
                    <v-list-item-title>Tour Single</v-list-item-title>
                </v-list-item>
            </v-list>

        </v-menu>
    



    </v-app-bar>
</template>




<script>
export default {

}



</script>


<styles>

</styles>