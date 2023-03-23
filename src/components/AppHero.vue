<template>
    <div class="centered">
        <div>
            <slot></slot>
        </div>

    </div>
</template>



  
<script>

export default {

    data() {

        return {

            name: 'AppHero',

        };
    },

};

</script>




  
<style>
.centered {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 800px;
    height: 400px;
    margin: auto;
    background-color: black;
}
</style>