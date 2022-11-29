<template>
    <div class="container">
        <div>
            <nav class="nav-menu" >
                <p class="nav-menu-name" >Charles Kasasira</p>
                <ul class="nav-menu-list">
                    <li>Home</li>
                    <li>About</li>
                    <li>Projects</li>
                </ul>
                <button class="nav-menu-button" >Resume</button>
            </nav>
        </div>
        <div class="content">
            <div class="main-content">
                <p class="hello" >Hello,</p>
                <p class="charles" >I am Charles.</p>
                <p class="designer" >UI/UX Designer</p>
                <p class="main-content-text" >Hello, I am an aspiring UI/UX designer with the ability to translate the designs into functional Front-end</p>
                <button class="hire-me-button" >Hire Me</button>
            </div>
            <div class="circle" ></div>
            <div class="image-content" >
                <img class="image-guy" src="../static/niceGuy.svg">
            </div>
        </div>

    </div>

</template>

<script></script>

<style>
*{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        
 }
html{
    background-color:#EDA751;
}
.container{
    max-width: 1440px;
    margin: 39px 80px;
    background-color: #f5f5f5;
    border: none;
    border-radius: 10px;
}
.nav-menu{
    margin: 23px 119px;
    padding-top: 28px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.nav-menu-name{
    font-size: 30px;
    color: #EDA751;
    font-weight: 700px;
}
.nav-menu-list{
    list-style: none;
    display: flex;
    gap: 40px;
    font-size: 20px;
}
.nav-menu-button{
    font-size: 20px;
    padding: 15px;
    border: 1px solid #EDA751;
    border-radius: 25px;
    background-color: #f5f5f5;
}
.nav-menu-button:active{
    background-color: #cecece;
    
}

.content {
    width: 96%;
    display: flex;
    justify-content: space-between;
    margin: 0 119px;
    margin-top: 156px;
    position: relative;
    overflow: hidden;

    max-height: 820px;
}

.main-content {
    width: 50%;
}

.hello{
    font-size: 50px;
    font-weight: 500px;
}

.charles{
    font-size: 70px;
    font-weight: 500px;
}

.designer{
    font-size: 40px;
    color: #EDA751;
    font-weight: 50px;
}

.main-content-text{
    padding-top: 25px;
    font-size: 30px;
    width: 500px;
    color: #676767;
}

.hire-me-button{
    padding: 10px 50px;
    border: none;
    background-color: #EDA751;
    color: #ffffff;
    font-size: 30px;
    border-radius: 20px;
    margin-top: 51px;
    margin-bottom: 110px;
}

.hire-me-button:active{
    background-color: #ffffff;
    color: #EDA751;
    border: 1px solid #EDA751;
}
.image-content{
    position: relative;
}

.circle{
    padding: 500px;
    background-color: #EDA751;
    border-radius: 50%;
    position: absolute;
    bottom: -420px;
    right: -25%;
}

.image-guy{
    padding-right: 90px;
}
</style>