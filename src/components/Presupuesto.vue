<script setup>

</script>

<template>
    <form class="presupuesto">
        <div class="campo">
            <label for="nuevo">Definir Presupuestos</label>

            <input type="number" id="nuevo" class="nuevo-presupuesto" placeholder="Añade tu presupuesto" />
            <input type="submit" value="Definir Presupuesto">
        </div>
    </form>
</template>

<style scoped>
.presupuesto {
    width: 100%;
}

.campo {
    display: grid;
    gap: 2rem;
}

.presupuesto label {
    font-size: 2.8rem;
    color: var(--azul);
    text-align: center;
}

.presupuesto input[type="number"] {
    background-color: var(--gris-claro);
    border-radius: 1rem;
    padding: 1rem;
    border: none;
    font-size: 2.2rem;
    text-align: center;

}

.presupuesto input[type="submit"] {
    background-color: var(--azul);
    border: none;
    padding: 1rem;
    text-align: center;
    font-size: 2rem;
    margin-top: 2rem;
    color: var(--blanco);
    font-weight: 900;
    width: 100%;
    
    transition: background-color .3s ease;
}

.presupuesto input[type="submit"]:hover {
    cursor: pointer;
    background-color: #1048a4;



}
</style>
