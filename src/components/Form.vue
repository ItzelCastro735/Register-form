<script>
</script>

<template>
    <div class="form-container">
        <div class="tryfree">
            <h3>Try ir free 7 days</h3>
            <p>then $20/mo. thereafter</p>
        </div>
        <form action="" class="form">
            <div class="form-inputs">
                <input type="text" placeholder="Name" required>
                <input type="text" placeholder="Last Name" required>
                <input type="text" placeholder="Email Address" required>
                <input type="text" placeholder="Password" required>
            </div>
            <button>CLAIM YOUR FREE TRIAL</button>
            <p>By clicking the button, you are agreeing to our <span>Terms and Services</span></p>
        </form>
    </div>
</template>

<style>
.form-container {
    width: 500px;
    height: auto;
}

.form-container .tryfree {
    width: 100%;
    height: 60px;
    background-color: hsl(248, 32%, 49%);
    border-radius: 10px;
    box-shadow: 0px 6px 0px rgba(0, 0, 0, 0.171);
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 5px;
}

.form-container .tryfree h3 {
    font-family: Arial, Helvetica, sans-serif;
    font-size: 16px;
    color: white;
}

.form-container .tryfree p {
    font-family: Arial, Helvetica, sans-serif;
    font-size: 16px;
    color: rgba(255, 255, 255, 0.829);
}

/* FORM STYLESS */
.form-container .form {
    margin-top: 30px;
    width: 100%;
    height: auto;
    background-color: white;
    border-radius: 10px;
    box-shadow: 0px 7px 0px rgba(0, 0, 0, 0.171);
    text-align: center;
}

.form-container .form button {
    width: 85%;
    height: 50px;
    margin-top: 15px;
    background-color: hsl(154, 59%, 51%);
    border: 2px solid hsl(154, 76%, 40%);
    border-radius: 5px;
    color: white;
    font-weight: 600;
    font-family: Arial, Helvetica, sans-serif;
    cursor: pointer;
}

.form-container .form p {
    font-family: Arial, Helvetica, sans-serif;
    font-size: 11px;
    font-weight: 600;
    color: hsl(246, 25%, 77%);
    padding-bottom: 35px;
}

.form-container .form span {
    color: hsl(0, 100%, 74%);
    font-size: 11px;
    font-weight: 600;
}

.form-container .form .form-inputs {
    width: 100%;
    height: auto;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 15px;
    padding-top: 40px;
}

.form-container .form .form-inputs input {
    width: 80%;
    height: 45px;
    border-radius: 5px;
    border: 1px solid hsl(246, 25%, 77%);
    padding-left: 20px;
    color: hsl(246, 25%, 77%);
    font-size: 13px;
    font-weight: 600;
}

.form-container .form .form-inputs input:focus {
    outline: none;
    border: 1px solid hsl(249, 10%, 26%);
    color: hsl(249, 10%, 26%);
    font-size: 15px;
}

@media screen and (max-width: 540px) {
    .form-container {
        width: 90%;
    }
}
</style>
