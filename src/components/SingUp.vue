<template>
    <img class="logo" alt="Vue logo" src="../assets/logo.jpg">
    <div class="register">
       
        <input type="text" placeholder="Enter name"/>
        <input type="text" placeholder="Enter Email"/>
        <input type="password" placeholder="Enter password"/>
        <button>Sing up</button>
    </div>
</template>

<Script>
export default{
    name:'SingUP'
}

</Script>


<style scoped>
.logo{
  width: 100px;
}
.register input{
    width: 300px;
    height: 40px;
    padding-left: 20px;
    display: block;
    margin-bottom: 30px;
    margin-right: auto;
    margin-left: auto;
    border: 1px solid skyblue;
}
.register button{

    width: 320px;
    height: 40px;
    border: 1px solid black;
     background: skyblue;
     color: white;
     cursor: pointer;
     
     
}

</style>