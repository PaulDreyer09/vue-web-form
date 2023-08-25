<template>
  <form>
    <label>Email: </label>
    <input type="text" required v-model="email">
    <label>Password: </label>
    <input type="text" required v-model="password">
  </form>
</template>

<script>
export default {
    data() {
        return {
            email: '',

        }
    }
}
</script>

<style>
    form{
        max-width: 420px;
        margin: 30px auto;
        background: #FFFFFF;
        text-align: left;
        padding: 40px;
        border-radius: 10px;
        /* border: 1px solid #ccc; */
    }

    label{
        color: #aaa;
        display: inline-block;
        margin: 25px 0 15px;
        font-size: 0.6em;
        text-transform: uppercase;
        letter-spacing: 1px;
        font-weight: 600;
    }

    input{
        display: block;
        padding: 10px 6px;
        width: 100%;
        box-sizing: border-box;
        border: none;
        border-bottom: 1px solid #ddd;
        color: #333;
    }

    input:focus{
        border: 1px solid #ddd !important;
    }

</style>