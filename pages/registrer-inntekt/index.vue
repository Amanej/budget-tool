<template>
<div class="form">
    <h3>Registrer inntekt</h3>
    <input type="text" name="kunde" placeholder="Kunde" />
    <input type="text" name="type" placeholder="Type" />
    <input type="text" name="sum" placeholder="Sum" />
    <button type="submit">Registrer inntekt</button>
</div>
</template>

<style scoped>
.form {
    margin: 20px 15%;
    display: flex;
    flex-direction: column;
}
.form > h3 {
    margin-bottom: 20px;
}
input {
    margin: 10px 20px;
    margin-left: 0;
    padding: 10px;
    border: none;
    font-size: 18px;
}
input:focus {
    outline: none;
}
button {
    margin-left: auto;
    padding: 10px 20px;
    border-radius: 8px;
}
button:focus {
    outline: none;
}
</style>