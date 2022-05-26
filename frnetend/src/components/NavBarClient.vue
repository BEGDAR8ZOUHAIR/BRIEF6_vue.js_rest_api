<template>
  <header>
    <div class="navBar">
      <img src="../assets/images/logo-only-v2.svg" alt="" />
      <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/Login">Log out</router-link></li>
        <li>
          <router-link to="/Rendez-vous"
            ><button>Rendez-vous</button></router-link
          >
        </li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  name: "NavBarClient",
  methods: {
    
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.navBar {
  display: flex;
  background-color: #68d391;
  width: 100%;
  height: 10vh;
  justify-content: space-between;
  padding: 13px 0 12px 0;
}

.navBar img {
  height: 100%;
  padding-left: 5%;
}

.navBar ul {
  display: flex;
  width: 50%;
  justify-content: space-around;
  align-items: center;
  list-style: none;
  padding-right: 5%;
}

.navBar {
  ul {
    li {
      a {
        text-decoration: none;
        font-family: "Hind", sans-serif;
        color: white;
      }
    }
    :hover {
        border: 3px solid #68d391;
    }
  }
}

/* From cssbuttons.io by @alexroumi */
button {
  padding: 10px 20px;
  border: unset;
  border-radius: 5px;
  z-index: 1;
  background: white;
  position: relative;
  font-weight: 400;
 
  overflow: hidden;
  color: black;
}

button:hover {
  background-color: #728499;
}
</style>
