<template>
    <header>
        <div class="container">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="logo-DC">
            </div>
            <nav>
                <ul>
                    <li><a href="#">Characters</a></li>
                    <li><a class="active" href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Collectibles</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">Fans</a></li>
                    <li><a href="#">News</a></li>
                    <li><a href="#">Shop</a></li>            
                </ul>
            </nav>
        </div>
    </header>
  
</template>

<script>
export default {
    name: 'Header'

}
</script>

<style lang="scss" scoped>
@import '../assets/style/partials/variables.scss';
header{
    .container{
        display: flex;
        justify-content: space-between;
        margin-top: 20px;
    }
}
nav{
    ul{        
        margin-top: 20px;
        text-transform: uppercase;
        list-style: none;
        display: flex;
    }
    li a{
        display: inline-block;
        padding: 20px 5px;
        margin: 0 10px;
        color: black;
        font-size: 12px;
        font-weight: 700;
        text-decoration: none;

        &.active, &:hover{
            // background-color: yellow;
            color: $DCColor;
            border-bottom: 5px solid $DCColor;
        }
    }
}
img{
    width: 80%;
}

</style>