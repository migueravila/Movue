<template>
  <header>
    <router-link to="/">
      <h1>Mo<span>Vue</span></h1>
    </router-link>
  </header>
  <main>
    <router-view />
  </main>
  <footer>
    This will be my footer
  </footer>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

*::selection {
  background: #f45b6950;
}

body {
  background-color: #35495e;
}

a {
  text-decoration: none;
}

header {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 10px 16px;
  background-color: #2c3d4e;
  box-shadow: 0px 0px 6px rgba(0, 0, 0, 0.2);
}

h1 {
  color: #fff;
  font-size: 28px;
}

span {
  color: #f45b69;
}
</style>
