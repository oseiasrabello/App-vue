<template>
  <header class="container_header">
    <nav class="navbar">
      <legend class="logo">LOGO</legend>
      <div class="menu">
        <ul>
          <li><a href="/">Home</a></li>
          <li><a href="/">About</a></li>
          <li><a href="/">Contacts</a></li>
        </ul>
      </div>
      <label for="">Menu</label>
    </nav>
  </header>
</template>

<script>
export default {
  name: "NavbarComponents",
};
</script>

<style scoped>
.container_header {
  width: 100%;
}

.navbar {
  width: 100%;
  height: 60px;
  background-color: #222;
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.menu ul {
  display: flex;
  gap: 30px;
}

.menu ul li {
  list-style-type: none;
}

.menu ul li a {
  color: #ffff;
  text-decoration: none;
  font-size: 17px;
  font-family: Arial, Helvetica, sans-serif;
}
</style>
