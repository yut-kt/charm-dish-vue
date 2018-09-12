<template>
    <div id="app">
        <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.3.1/css/all.css"
              integrity="sha384-mzrmE5qonljUremFsqc01SB46JvROS7bZs3IO2EmfFsd15uHvIt+Y8vEf7N7fWAU"
              crossorigin="anonymous">

        <header class="clearfix">
            <i class="fas fa-bars"></i>
            <h1>charm dish</h1>
            <i class="fas fa-search"></i>
            <i class="fas fa-user"></i>
        </header>

        <router-view></router-view>

        <div class="footer">フッター</div>
    </div>
</template>

<style>
    html,body{
        width: 100%;
        max-width: 414px;
        margin: 0 auto;
        padding: 0;
        color: #666;
    }
    h1,h2,h3,h4,p,ul,li{
        margin: 0 auto;
        padding: 0 auto;
    }
    li{
        list-style-type: none;
    }
    .clearfix:after{
        content: "";
        display: block;
        clear: both;
    }
    img{
        width: 100%;
    }
    a{
        text-decoration: none;
    }

    header{
        position: fixed;
        top: 0;
        left: 0;
        width: 90%;
        padding: 15px 5%;
        background-color: #fefefe;
        box-shadow: 0 0 10px rgba(0,0,0,0.2);
        z-index: 100;
    }
    .fa-bars{
        float: left;
        width: 20%;
    }
    h1{
        float: left;
        width: 65%;
        font-size: 18px;
        text-align: center;
    }
    i{
        font-size: 22px;
    }
    .fa-search{
        float: left;
        width: 10%;
    }
    .fa-user{
        float: left;
        width: 5%;
    }




    /*#app {*/
        /*text-align: center;*/
        /*font-size: 40px;*/
    /*}*/


    /*.header {*/
        /*height: 50px;*/
        /*background-color: #ebebeb;*/
        /*margin-bottom: 50px;*/
    /*}*/

    /*.footer {*/
        /*height: 50px;*/
        /*background-color: #ebebeb;*/
        /*margin-top: 70px;*/
    /*}*/
</style>
