<template>
  <div>
    <p>Componente de mensagem</p>
    <form action="" id="burger-form">
      <div class="input-container">
        <label for="nome">Nome do cliente</label>
        <input
          type="text"
          id="nome"
          name="name"
          v-model="nome"
          placeholder="Digite seu nome"
        />
      </div>
      <div class="input-container">
        <label for="pao">Escolha seu pao:</label>
        <select name="pao" id="pao">
          <option value="">Selecione seu pao</option>
        </select>
      </div>
      <div class="input-container">
        <label for="carne">Escolha a carne:</label>
        <select name="carne" id="carne">
          <option value="">Selecione sua carne</option>
        </select>
      </div>
      <div class="input-container">
        <label for="opcionais">Escolha opcionais:</label>
        <div class="checkbox-container">
          <input
            type="checkbox"
            name="opcionais"
            v-model="opcionais"
            value="salame"
          />
          <span>Salame</span>
        </div>
      </div>
    </form>
  </div>
</template>
<script>
export default {
  name: "BurrgerForm",
};
</script>
<style scoped>
</style>
