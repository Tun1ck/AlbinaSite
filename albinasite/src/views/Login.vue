<template>
  <div>
    <div class="parents">
    <form class="main">

        <div class="form-item">
            <input type="text">
        </div>

        <div class="form-item">
            <input type="text">
        </div>

        <div class="form-item">
            <button class="myform-btn">Войти</button>
        </div>
    </form>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.parents {
  width: 100%;
  margin: 0%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.main {
  width: 430px;
  height: 600px;
  background-color: rgb(50, 100, 125);
  margin-top: 150px;
  border-radius: 10px;
  padding: 40px 60px;
}
.form-item{
    width: 100%;
    height: 100px;
}
.myform-btn{
    width: 100%;
    height: 50px;
    font-size: 17px;
    background: rgba(103,58,183);
    border: none;
    border-radius: 50px;
    color: #fff;
    cursor: pointer;
    -webkit-transition: all .5s;
    -o-transition: all .5s;
    transition: all .5s;
}

</style>
