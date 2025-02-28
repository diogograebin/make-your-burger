<template>
    <div>
        <p>Componente de Mensagem</p>
        <div>
            <form id="burger-form">
                <div class="imput-container">
                    <label for="nome">Nome do Cliente:</label>
                    <input type="text" id="nome" name="nome" v-model="nome" placeholder="Digite o seu nome">
                    
                </div>

                <div class="imput-container">
                    <label for="pao">Escolha o Pão:</label>
                    <select name="pao" id="pao" v-model="pao">
                        <option value="">Selecione seu pão</option>
                        <option value="integral">Integral</option>
                    </select>
                </div>

                <div class="imput-container">
                    <label for="carne">Escolha a Carne do seu Burger:</label>
                    <select name="carne" id="carne" v-model="carne">
                        <option value="">Selecione o tipo de carne</option>
                        <option value="maminha">Maminha</option>
                    </select>
                </div>

                <div class="imput-container">
                    <label for="opcionais">Selecione os Opcionais:</label>
                    <div class="checkbox-container">
                        <input type="checkbox" name="opcionais" v-model="opcionais" value="salame">
                        <span>Salame</span>
                    </div>
                </div>

                <div class="input-container">
                    <input type="submit" class="submit-btn" value="Criar meu Burger">
                </div>
            </form>
        </div>
    </div>
</template>

<script>

export default{
    name: "BurgerForm"
}

</script>

<style scoped>


</style>