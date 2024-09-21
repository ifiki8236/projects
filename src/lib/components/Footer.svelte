<footer>
    <div class="main">
        <div class="circle" id="cir1"></div>
        <a href="https://github.com/ifiki8236" target="_blank">Github</a>
    </div>
    <div class="main">
        <div class="circle" id="cir2"></div>
        <a href="https://www.linkedin.com/in/ifiok-edemidiong-b096ba21a" target="_blank">LinkedIn</a>
    </div>
    <div class="main">
        <div class="circle" id="cir3"></div>
        <a href="https://discord.com/invite/code-culture" target="_blank">Discord</a>
    </div>
    

</footer>

<style>
    footer {
        position: relative;
        display: flex;
        bottom: 0;
        width: 100%;
        /* padding-bottom: 20px; */
        height: fit-content;
    }
    
    div, a {
        margin: auto;
        text-decoration: none;
        color: rgb(255, 228, 77);
        font-size: 20px;
    }

    .circle {
        /* background-color: white; */
        height: 50px;
        width: 50px;
        border-radius: 100%;
        margin-bottom: 5px;
    }
    #cir1 {
        background-image: url('$lib/img/icons8-github.svg');
        background-repeat: no-repeat;
        background-size: cover;
    }
    #cir2 {
        background-image: url('$lib/img/icons8-linkedin.svg');
        background-repeat: no-repeat;
        background-size: cover;
    }
    #cir3 {
        background-image: url('$lib/img/icons8-discord.svg');
        background-repeat: no-repeat;
        background-size: cover;
    }
</style>