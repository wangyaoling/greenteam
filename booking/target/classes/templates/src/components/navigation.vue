<template>
    <div class="navigations">
      <nav>
        <h2>Booking App</h2>
        <ul>
          <li>
            <router-link to="/dashboard" exact-active-class="active">Dashboard</router-link>
          </li> <li>
            <router-link to="/booking" exact-active-class="active">Booking</router-link>
          </li>
          <li>
            <router-link to="/calendar" exact-active-class="active">Calendar</router-link>
          </li>
          <li>
            <router-link to="/profile" exact-active-class="active">Profile</router-link>
          </li>
        </ul>
      </nav>
    </div>
</template>

<script>
    export default {
        name: 'navigation'
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

  .active {
    font-weight: bold;
  }

  p{
    color: red;
  }
  body{
    margin: 0;
  }
  li{
    list-style-type: none;
    display: inline;
    color: #FFF;
    text-transform: uppercase;
    cursor: pointer;
  }
  ul{
    background-color: #7B90E0;
    padding: 37px 20px 10px 0;
    font-size: 14px;
    text-align: right;
    word-spacing: 18px;
    margin: 0;
  }
  h2{
        position: absolute;
    color: #FFF;
    margin: 25px 0 10px 25px;
  }
  a{
    color: #FFF;
  }
  a:hover{
    text-decoration: none;
  }
</style>
