<script setup lang="ts">
    console.log("Testing...")
</script>

<template>
    <div class="login">
        <h1>Register Account</h1>
        <div class="login-form">
            <span>Email address</span>
            <input placeholder="useremail@email.com" type="text">
        </div>

        <div class="login-form">
            <span>Username</span>
            <input placeholder="spreadsheet-user" type="text">
        </div>

        <div class="login-form">
            <span>Password</span>
            <input type="password">
        </div>

        <div class="login-form">
            <span>Confirm password</span>
            <input type="password">
        </div>

        <button class="sign-in">
            Sign up
        </button>

        <RouterLink to="/">
            <button class="no-account">
                Already a member? Sign in
            </button>
        </RouterLink>

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