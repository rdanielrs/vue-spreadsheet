<script setup lang="ts">
//import { Login } from 'vue';

/*function sendToRegister() {
    console.log("testing...")
}*/
 


   
</script>


<template>
    <div class="login">
        <h1>Login</h1>
        <div class="login-form">
            <span>Username</span>
            <input placeholder="spreadsheet-user" type="text">
        </div>

        <div class="login-form">
            <span>Password</span>
            <input type="password">
        </div>

        <button class="sign-in">
            Sign in
        </button>

        <RouterLink to="/register">
            <button class="no-account">
                    No account? Sign up
            </button>
        </RouterLink>

        <!--<button @click="sendToRegister()" class="no-account">
           No account? Sign up
        </button>-->
    </div>

</template>

<style scoped>

.login {
    padding: 25px;
    border-radius: 10px;
    position: absolute;
    top: 50%;
    left: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    transform: translate(-50%, -50%);
    h1 {
        font-size: 36px;
        color: #EDF2F4;
        margin-bottom: 20px;

    }

    button {
        margin-bottom: 15px;
        border: 0;
        border-radius: 8px;
    }

    button:hover {
        cursor: pointer;
    }
}

.login-form {
    display: flex;
    flex-direction: column;
    width: 240px;
    margin-bottom: 20px;
    span {
        color: #EDF2F4;
        font-size: 20px;
    }

    input {
        background: transparent;
        color: #EDF2F4;
        height: 38px;
        outline: none;
        border: none;
        border-bottom: 2px solid #2667ff;
        font-size: 18px;
    }

}

.sign-in {
    background: #2667ff;
    font-size: 24px;
    border-radius: 10px;
    color: #fff;
    width: 240px;
    height: 50px;
}

.no-account {
    background: transparent;
    font-size: 18px;
    color: #2667ff;
    height: 20px;

    
}

a:hover {
    height: fit-content;
}


</style>