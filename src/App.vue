<template>
  <div id="app">

    <label id="Todo">#todo</label>
    
    <ul>
    <li>All</li>
    <li b-nav-item to="/active">Active</li>
    <li>Completed</li>
    </ul>

    <b-navbar-nav id="Nav">
    <b-nav-item to="/">All</b-nav-item>
    <b-nav-item to="/active">Active</b-nav-item>
    <b-nav-item to="">Completed</b-nav-item>
    </b-navbar-nav>

    <input type="text" placeholder="add details" id="Input">  <b-button variant="primary" id="Botao">Add</b-button
      
    <router-view/>
  </div>
</template>

<script>

</script>
