<template>
  <nav class="navbar navbar-expand-md navbar-dark bg-dark mb-4">
      <router-link class="navbar-brand" to="contacts">ContactApp</router-link>

      <div class="collapse navbar-collapse" id="navbarCollapse">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <router-link class="nav-link" to="contacts">Contacts</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="/add-contact">Add contacts</router-link>
          </li>
        </ul>
      </div>
    </nav>
</template>

<script>
export default {
 
}
</script>

