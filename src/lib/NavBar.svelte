<script>
    let showMenu = false;

    function toggleMenu() {
        showMenu = !showMenu;
    }
</script>

<style>
    nav {
        background-color: maroon;
        color: white;
        padding: 8px;
        display: flex;
        place-content: center;
        place-items: center;
        position: relative;
    }

    legend {
        font-weight: bold;
        letter-spacing: 0.5px;
        font-size: 1.2rem;
        text-transform: uppercase;
        text-align: center;
        user-select: none;
    }

    .hamburger {
        position: absolute;
        /* top: 12px; */
        left: 16px;
        cursor: pointer;
        user-select: none;
        width: 30px;
    }

    .close {
        font-size: 2rem;
        line-height: 1rem;
        transform: scaleX(2);
        margin-left: 10px;
        color: white;
    }

    .bar {
        display: block;
        background-color: white;
        width: 30px;
        height: 3px;
        margin: 4px 0;
        border-radius: 2px;
    }

    .menu {
        position: absolute;
        top: 36px;
        left: 16px;
        display: flex;
        flex-direction: column;
        background-color: #490202;
        box-shadow: 0 0 8px rgba(0, 0, 0, 0.3);
        padding: 24px;
        border-radius: 8px;
    }

    a {
        color: white;
        padding: 4px 0;
        text-decoration: none;
        user-select: none;
    }

</style>

<nav>
    <legend>Rebeldes de Arkanna</legend>
    <div class="hamburger" on:click={toggleMenu}>
        {#if showMenu}        
            <div class="close">x</div>
        {:else}
            <div class="bar"></div>
            <div class="bar"></div>
            <div class="bar"></div>
        {/if}
        <!-- <div class="bar"></div>
        <div class="bar"></div>
        <div class="bar"></div> -->
    </div>
    {#if showMenu}
        <div class="menu">
            <a href="/">Início</a>
            <a href="/mundo">Criação do Mundo</a>
            <a href="/guilda">A Guilda</a>
            <a href="grupo">O Grupo</a>
            <a href="diario">Diário de Aventuras</a>
        </div>
    {/if}
</nav>