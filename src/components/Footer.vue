<template>
<footer>
    <!-- shop -->
        <div class="footer-top">
            <div class="container">
                <nav>
                    <ul>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Characters</a></li>
                    </ul>
            </nav>
            </div>
        </div>
    <!-- / shop -->

    <!-- link utili -->
        <div class="footer-main">
            <div class="container">
                <div class="link">
                    <div>
                    <h2>DC Comics</h2>
                    <ul>
                        <li><a href="#">Link</a></li>
                        <li><a href="#">Link</a></li>
                        <li><a href="#">Link</a></li>
                        <li><a href="#">Link</a></li>
                        <li><a href="#">Link</a></li>
                    </ul>
                </div>
                <div class="div">
                    <h2>Shop</h2>
                    <ul>
                        <li><a href="#">Link</a></li>
                        <li><a href="#">Link</a></li>
                        <li><a href="#">Link</a></li>
                        <li><a href="#">Link</a></li>
                        <li><a href="#">Link</a></li>
                    </ul> 
                </div> 
                <div>
                    <h2>DC</h2>
                    <ul>
                        <li><a href="#">Link</a></li>
                        <li><a href="#">Link</a></li>
                        <li><a href="#">Link</a></li>
                        <li><a href="#">Link</a></li>
                        <li><a href="#">Link</a></li>
                    </ul>
                      
                </div>    
                <div>
                    <h2>Site</h2>
                    <ul>
                        <li><a href="#">Link</a></li>
                        <li><a href="#">Link</a></li>
                        <li><a href="#">Link</a></li>
                        <li><a href="#">Link</a></li>
                        <li><a href="#">Link</a></li>
                    </ul>  
                </div>
            </div>
            <div class="logo">
                <img src="../assets/img/dc-logo-bg.png" alt="logo-DC">
            </div>

            
            </div>

        </div>
    <!-- / link utili -->

    <!-- social -->
        <div class="footer-bottom">
            <div class="container">
                <div><button>Signup now</button></div>
                <div class="social">
                    <h2>Follow Us</h2>
                    <ul>
                        <li><a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a></li>
                        
                    </ul>
                </div>
            </div>

        </div>
    <!-- / social -->
    

</footer>
  
</template>

<script>
export default {
    name:'Footer',

}
</script>

<style  lang='scss' scoped>
@import '../assets/style/partials/variables.scss';
.footer-top{
    background-color: $DCColor;
    nav{
        ul{ 
            text-transform: uppercase;
            list-style: none;
            display: flex;            
        }
        li a{
            display: inline-block;
            padding: 20px 15px;
            margin: 0 10px;
            color: $mainColor;
            font-size: 15px;
            font-weight: 700;
            text-decoration: none;
        }
    }
}
.footer-main{
    background-image: url('../assets/img/footer-bg.jpg');
    height: 400px;
    
        .container{
            display: flex;
            justify-content: space-between;
                .link{
                display: flex;
                padding: 20px 15px;
            }
            h2{
                padding: 0px 15px;
            }
            
            li a{
                display: inline-block;
                padding: 3px 15px;
                color: #959595;
                font-size: 15px;
                font-weight: 700;
                text-decoration: none;
            }
            .logo{
                img{
                    height: 400px;
                }
            }
        }
}
.footer-bottom{
    background-color: #303030;
    height: 150px;
    .container{
        display: flex;
        justify-content: space-between;
        padding-top: 20px;
        button{
            color: $mainColor;
            background-color: #303030;
            padding: 10px 15px;
            border: none;
            border: 2px solid $DCColor;
            text-transform: uppercase;
            font-size: 14px;
        }
        .social{
            display: flex;
            justify-content: space-between;
                ul{ 
                list-style: none;
                display: flex;            
            }
            li a{
                display: inline-block;
                padding: 20px 15px;
                margin: 0 10px;
            }
        }
    }
}

</style>