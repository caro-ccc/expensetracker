<template>
    <div>
    <h3>Agregar nueva transaccion </h3>
    <form id="form">
        <div class="form-contol">
            <label for="text">Text</label>
            <input type="text" id="text" 
            placeholder="Enter text...">
            
        </div>
        <div class="form-control">
            <label for="amount">Cantidad <br>
            (negative - expense, positive- income)</label>
            <input type= "number" id="amount" placeholder="Ingrese cantidad">
        </div>
        <button class="btn">Agregar</button>
    </form>
</div>
</template>