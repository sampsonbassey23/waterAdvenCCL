<template>
 <div>
    <div class="section1-background bg-cover bg-center p-6">
       <NavBar class="text-gray-400"/>
       <UnderLineTextsSection1/>
       <ProjectTitle class="ml-28 mt-6 text-white"/> 
       <AfterTiTleText class="ml-28"/>
    </div>
        <div class="section2 flex">
        <div class="column1">
            <ColumnOneContainer/>
        </div>
        <div class="column2 w-full">
            <ColumnTwoContainerVue/>
            <Cart class="ml-10"/>
        </div>
    </div>
 </div>
</template>
<script setup>
import ColumnTwoContainerVue from '@/components/Column-two-container.vue';
import NavBar from '../components/NavBar.vue';
import ProjectTitle from '../components/ProjectTitle-Section1.vue'
import UnderLineTextsSection1 from '../components/UnderLineTexts-Section1.vue'
import AfterTiTleText from '../components/AfterTiTleText.vue'
import ColumnOneContainer from '@/components/Column-one-container.vue';
import Cart from '@/components/Cart.vue';
</script>

<style scoped>
.section1-background{
    background-image: url('../assets/joy.jpg');
}
 </style>