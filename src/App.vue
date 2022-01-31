<template>
  <div id="app">

    <div id="Todo">#todo</div>

    <ul>
    <li>All</li>
    <li>Active</li>
    <li>Completed</li>
    </ul>

    <input type="text" placeholder="add details" id="Input">  <b-button variant="primary" id="Botao">Add</b-button
    
    
    <router-view/>
  </div>
</template>

<style>

</style>
