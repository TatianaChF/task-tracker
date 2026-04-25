<template>
  <div class="container">
    <div class="content">
      <div class="content-inputs">
        <div class="input-container">
          <label>Имя</label>
          <input placeholder="Введите имя" />
        </div>

        <div class="input-container">
          <label>Пароль</label>
          <input placeholder="Введите пароль" />
        </div>

        <div class="input-container">
          <label>Повторите пароль</label>
          <input placeholder="Введите пароль" />
        </div>
      </div>

      <button class="content-btn">Зарегистрироваться</button>
    </div>
  </div>
</template>

<script lang="ts" setup>

</script>

<style lang="scss" scoped>
.container {
  width: 583px;
  background-color: #E6D8C3;
  border-radius: 20px;
}

.content {
  padding: 42px 31px 30px 31px;
  font-family: 'Inter', sans-serif;
  font-size: 20px;
  font-weight: 500;
  color: #2D3748;
  display: flex;
  flex-direction: column;
  gap: 48px;

  &-inputs {
    display: flex;
    flex-direction: column;
    gap: 17px;
  }

  &-btn {
    background-color: #5D866C;
    color: #ffff;
    padding: 6px 10px;
    border-radius: 3px;
    border: none;
    outline: none;
    align-self: end;
    cursor: pointer;
  }
}

.input-container {
  display: flex;
  flex-direction: column;
  gap: 8px;

  input {
    padding: 10px 7px;
    border: 1px solid #C2A68C;
    border-radius: 5px;

    &:focus {
      outline: none;
      border-color: #2D3748;
      box-shadow: 0 0 5px #5D866C;
    }
  }
}
</style>