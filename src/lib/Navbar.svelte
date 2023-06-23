<div class="navbar">
    <h2 style="margin-left: 5px; color:white">Twingamerdudes</h2>
    <a href="/" class="home">Home</a>
    <a href="/about">About</a>
    <a href="/projects">Projects</a>
</div>
<style>
    .navbar{
        height: 10vh;
        min-height: 50px;
        position:fixed;
        width: 100%;
        top: 0;
        left: 0;
        display: flex;
        align-items: center;
        z-index: 99;
        padding: 15px;
        box-sizing: border-box;
        background-color: #333
    }
    .navbar a{
        color: white;
        text-decoration: none;
        font-size: 20px;
        margin: 0 10px;
        white-space: nowrap;
        transition: all 0.2s ease-out;
    }
    .navbar .home{
        margin: 0 20px;
        margin-right: 10px;
    }

    .navbar a:hover{
        color: #ddd;
    }
</style>