<template>
        <main>
            <div class="container">
                <h2> ---> Content goes here >--- </h2>
            </div>
        </main>
  
</template>

<script>
export default {
    name: 'Main'

}
</script>

<style lang='scss' scoped>
@import '../assets/style/partials/variables.scss';

main{
    background-color: black;
    color: white;
    height: 150px;
    
    .container{
        display: flex;
        justify-content: space-between;
        
    }
    h2{
        line-height: 150px;
        text-transform: capitalize;
    }
}



</style>