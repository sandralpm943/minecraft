<style lang="scss" scoped src="/src/css/header.scss"/>
<template>
    <header>
        <div class="bienvenidos">
                <p>Bienvenidos</p>
            </div>
        <nav>
            
            <div class="naranja">
                <img src="/src/css/img/naranjas2.png" class="fondo"> 
            </div>
            <div class="inicio">
                <p>inicio</p>
            </div>
            <div class="invitado">
                <p>iniciar sesion</p>
            </div>
            
            <section>
            <ul class="pack">
                <li><RouterLink to="/">jugar ahora</RouterLink></li>
                
                <!--<li><RouterLink to="/C">Productos Minecraft</RouterLink></li>-->
            </ul> 
            <ul class="pack2">
                <li><RouterLink to="/B">discord</RouterLink></li>
            </ul> 
        </section>
        <section>
            <ul class="pack1">
                <li>naranjitas</li>
                <li>packs</li>
                <li>dinero ic</li>
                <li>addons</li>
                <li>pedidos</li>
                <li>ropa perzonalizada</li>
            </ul>

        </section>  
        </nav>
    </header>
</template>
