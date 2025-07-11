<template>
  <form @submit.prevent="CadastraCliente">
    <h2>Caadastro do cliente</h2>

    <input v-model="mome" placeholder="Nome" required />
    <input v-model="email" placeholder="Email" type="emial" required />
    <input
      v-model="senha"
      placeholder="Senha"
      type="password"
      required
      minlength="6"
    />

    <button type="submit">Cadastrar</button>

  </form>
</template>
