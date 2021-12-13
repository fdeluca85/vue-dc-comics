<template>
    <header>
        <div class="logo">
        <img src="../assets/img/dc-logo.png" alt="logo-DC">
    </div>
    <nav>
        <ul>
            <li><a href="#"></a>Characters</li>
            <li><a href="#"></a>Comics</li>
            <li><a href="#"></a>Movies</li>
            <li><a href="#"></a>TV</li>
            <li><a href="#"></a>Games</li>
            <li><a href="#"></a>Collectibles</li>
            <li><a href="#"></a>Videos</li>
            <li><a href="#"></a>Fans</li>
            <li><a href="#"></a>News</li>
            <li><a href="#"></a>Shop</li>            
        </ul>
    </nav>
    </header>
  
</template>

<script>
export default {
    name: 'Header'

}
</script>

<style scopes>
header{
    display: flex;
    justify-content: space-between;
}
li{
    text-transform: uppercase;
    list-style: none;
    display: flex;
}

</style>