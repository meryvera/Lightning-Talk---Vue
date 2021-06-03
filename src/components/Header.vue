<template>
    <nav class="nav">
        <h2>LIM014</h2>
        <ul class="nav-ul">
            <li><a href="">QUIENES SOMOS</a></li>
            <li><a href="">NOSOTROS</a></li>
            <li><a href="">CONTACTO</a></li>
        </ul>
    </nav>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style>
h2{
/*     background-color: yellow; */
    border: 1px solid;
    border-radius: 5px;
    padding: 4px;
    background-color: rgba(201, 198, 198, 0.651);
}
.nav, ul{
    display: flex;
    justify-content: space-between;
    align-items: center;
}
nav{
    background-color: rgba(218, 218, 218, 0.651);
    padding: 1rem;
}
li{
    list-style: none;
    margin-left: 20px;
    background-color: teal;
    padding: 10px;
    border-radius: 15px;
}
a{
    color:whitesmoke;
    text-decoration: none;

}
</style>