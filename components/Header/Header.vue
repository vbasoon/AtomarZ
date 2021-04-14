<template>
  <header>
    <div class="container">
      <div class="row top">
        <div class="left">
          <span class="logo"
            ><a href="#"><img src="images/logo.svg" alt="" /></a
          ></span>
          <span class="line"></span>
          <span class="icon-app">
            <a href="#">
              <img src="images/app_icon.png" alt="" />
            </a>
          </span>
        </div>

        <div class="right">
          <div class="buttons">
            <button class="btn btn1">Login</button>
            <button class="btn btn2 active">Register</button>
          </div>
          <div class="burger">
            <p>M</p>
          </div>
        </div>
      </div>

      <nav class="header-menu">
        <ul>
          <li><a href="">W Overview</a></li>
          <li><a href="">Fiat and Spot</a></li>
          <li><a href="">Margin</a></li>
          <li><a href="">Futures</a></li>
          <li><a href="">P2P</a></li>
          <li><a href="">Earn</a></li>
          <li><a href="">Settings</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style>
header {
  background: #243040;
}

.container {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  padding: 0;
}

.row.top {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}

.left,
.right {
}

.left {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}

.logo {
  width: 150px;
  height: 50px;
}

.line {
  display: block;
  width: 2px;
  height: 50px;
  background-color: white;
  margin-right: 5px;
}

.icon-app {
  width: 21px;
  height: 21px;
}

.icon-app img {
  width: 100%;
  font-size: 0;
}

.right {
  display: flex;
  flex-direction: row;
}

.buttons {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-right: 10px;
}

.btn {
  width: 70px;
  height: 30px;
  background-color: transparent;
  font-size: 14px;
  color: #f8f8f8;
  border: none;
  border-radius: 5px;
  border: 1px solid rgba(0, 87, 255, 1);
}

.btn:hover {
  background-color: rgba(0, 87, 255, 1);
  border: 1px solid transparent);
  transition: all 0.3s ease;
}

.btn.active {
  background-color: rgba(0, 87, 255, 1);
  border: 1px solid transparent);
}

.btn2 {
  margin-left: 20px;
}

.burger {
  width: 30px;
  height: 30px;
  border: 2px solid white;
  margin: 0 20px;
  color: white;
}

.row .bottom {
  display: flex;
  justify-content: space-between;
  color: white;
}

.overview {
}

.header-menu {
  display: flex;
  border-top: 0.2px solid rgba(146, 154, 165, 0.8);
}

ul {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

li {
  list-style-type: none;
  padding: 5px;
}

a {
  text-decoration: none;
  margin-right: 5px;
  font-size: 12px;
  color: #929aa5;
}

a:hover {
  color: #f8f8f8;
}
</style>