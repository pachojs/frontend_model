<template>
    <div class="contenedor">
        <section class="contenido-header">
            <img src="../assets/history.png" alt="">
            <section class="textos-header">
                <h1>Our History Since 1842</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis, est!</p>
                <a href="#">Learn more</a>
            </section>
        </section>
    </div>
</template>


<style scoped>
h1, h2, h3, h4, h5, h6 {
    color: #1d273b;
    font-weight: 300;
}

.contenedor {
    font-family: 'Roboto', sans-serif;
    width: 90%;
    max-width: 1000px;
    margin: auto;
    overflow: hidden;
}

h1{
    font-size: 50px;
    
}

.contenido-header {
    width: 100%;
    height: 600px;
    display: flex;
    justify-content: space-between;
    align-items: center;

}

.contenido-header>img {
    width: 550px;
    animation: ease-in animat 1s;

}

@keyframes animat {
    0%{
        transform: scale(0);
    }
    100%{
        transform: scale(1); /*Probar con 2*/
    } 
}

.textos-header {
    margin: 0 0 0 30px;

}

.textos-header h1{
    text-align: justify;
}

.contenido-header p {
    font-weight: 100;
    margin-top: 14px;
    color: #5D6678;
    text-align: justify;

}

.contenido-header a {
    margin: 28px 0 0 0;
    width: 130px;
    display: inline-block;
    background: #1FDE82;
    text-align: center;
    color: #fff;
    padding: 12px 0;
    text-decoration: none;
    font-weight: 400;
    text-transform: uppercase;
    font-size: 14px;
    border-radius: 5px;
    box-shadow: 0 8px 32px rgba(31, 222, 130, .46);

}

</style>



