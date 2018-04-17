<template>
    <div class="login">
        <img src="../assets/pipe.png" class="pataxo__logo" alt="Logo Pataxó">
        <h1>Sistema Pataxó</h1>
        <form action="">
            <input type="email" placeholder="E-mail" required>
            <input type="password" placeholder="Senha" required>
            <input type="submit" value="Entrar">
        </form>
    </div>
</template>

<script>
export default {
  
}
</script>

<style scoped>
    .pataxo__logo{
        width: 200px;
        margin: 0 auto;
    }
    h1{
        font-weight: bold;
        margin: 0 0 20px 0;
    }
    form{
        display:flex;
        flex-direction: column;
        width: 300px;
        margin: 0 auto;
    }
    form input{
        margin: 10px 0;
        height: 30px;
        border-radius: 4px;
        border: 1px solid #e5e5e5;
        padding: 10px;
    }
    form input[type=submit]{
        height: 40px;
        background-color: #2ecc71;
        color: white;
        font-weight: bold;
        cursor: pointer;
    }
    form input[type=submit]:hover{
        background-color: #27ae60;
    }
</style>
