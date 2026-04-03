<script setup>
    //variaveis
    let exibir = false;
    let media = 3;

</script>

<template>
    <h1 v-if="exibir">Hello World</h1>

    <p v-if="media >= 7">Aprovado</p>
    <p v-else-if="media >=5">Em Exame</p>
    <p v-else>Reprovado</p>

</template>