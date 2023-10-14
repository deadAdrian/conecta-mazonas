<script setup>
</script>

<template>
    <v-footer class="bg-green">
        <v-row justify="center mt-3" no-gutters>
            <v-btn target="blank" href="https://www.gov.br/mcom/pt-br/acesso-a-informacao/acoes-e-programas/programas-projetos-acoes-obras-e-atividades/norte-conectado" variant="text">Projeto Norte Conectado</v-btn>
            <v-divider v-if="$vuetify.display.mdAndUp" vertical class="my-v-divider"/>
            <v-btn target="blank" href="http://www.amazoniaconectada.eb.mil.br/" variant="text">Projeto Amazônia Conectada</v-btn>
            <v-divider v-if="$vuetify.display.mdAndUp" vertical class="my-v-divider"/>
            <v-btn target="blank" href="https://www.rnp.br/sistema-rnp/fornecedores/norte-conectado" variant="text">Rede Nacional de Ensino e Pesquisa</v-btn>
            <v-col class="text-center mt-4" cols="12">
                2023 - <strong>ConectA</strong>mazonas
            </v-col>
            <v-divider class="my-v-divider my-3"></v-divider>
            <v-img min-width="200px" max-width="200px" src="./assets/logo.png"/>
        </v-row>
    </v-footer>
</template>
  
<style>

.v-footer {
    max-height: 250px;
    position: fixed;
    bottom: 0px;
}

.my-v-divider {
    border-color: rgba(255, 255, 255) !important;
    opacity: 0.5 !important;
    border-width: 1px;
}

</style>
  