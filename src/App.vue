<script setup>
import MyHeader from '@/components/header/MyHeader.vue'
import MyFooter from '@/components/footer/MyFooter.vue'
</script>

<template>
 <v-app class="w-100">
      <MyHeader />
      <v-main class="mt-8 mt-md-16 mb-16 d-flex flex-column align-center justify-center" style="min-width: 100% !important;">
        <section class="section-header">
          <h1 class="my-heading-2">INVISTA NO AMAZONAS</h1>
         <a class="my-icon" href="#section-1"><v-icon icon="mdi-chevron-down" size="x-large"  /></a>
        </section>
        <span id="section-1" class="mb-15"></span>
        <section class="my-section px-4 pt-6" >
          <div class="d-flex flex-wrap flex-xl-nowrap justify-center mb-6">
            <figure class="mb-6 mb-xl-0">
              <v-img :min-width="$vuetify.display.sm ? '400px' : $vuetify.display.mdAndUp ? '600px' : ''" max-width="600px" src="./assets/mapa-infovia.jpeg"/>
              <figcaption class="my-paragraph">Infovias planejadas do projeto Norte Conectado - RNP</figcaption>
            </figure>
            <div class="d-flex flex-column flex-wrap ml-xl-5" style="text-indent: 20px;">
              <p class="my-paragraph">
                A ausência de conectividade no Amazonas perpetua um cenário desafiador e limitante para o desenvolvimento regional. 
                As comunidades amazônicas, dispersas em áreas remotas e geograficamente complexas, enfrentam barreiras significativas no
                acesso a serviços digitais essenciais e oportunidades online. A falta de infraestrutura de comunicação eficiente não apenas
                restringe o acesso à educação e informações vitais, mas também impede o desenvolvimento de negócios e a participação plena
                na economia digital. Além disso, a ausência de conectividade impacta negativamente os esforços de saúde, governança e 
                participação cívica, restringindo a capacidade das comunidades locais de se engajarem em diálogos globais e de aproveitarem
                as vantagens oferecidas pela tecnologia. Nesse contexto, a ausência de conectividade no Amazonas representa uma lacuna 
                significativa no avanço socioeconômico e cultural, evidenciando a necessidade urgente de investimentos em infraestrutura 
                digital abrangente para garantir a inclusão digital e a igualdade de oportunidades para todas as comunidades da região.
              </p>
            </div>
          </div>
          <div class="d-flex flex-column" style="text-indent: 20px;">
            <p class="my-paragraph">
              Apesar dos desafios da falta de conectividade no Amazonas, o Exército Brasileiro tem desempenhado um papel essencial na 
              implementação das infovias, superando obstáculos geográficos e logísticos para conectar comunidades isoladas e melhorar 
              o acesso à internet na região. Seu envolvimento estratégico reflete o compromisso em promover o desenvolvimento socioeconômico 
              e tecnológico, permitindo que as comunidades amazônicas participem plenamente da era digital e suas oportunidades.
            </p>
            <p class="my-paragraph">
              A criação das infovias no Amazonas abriu caminho para uma conectividade robusta em uma região historicamente desafiadora. 
              Com uma demanda crescente por serviços de internet, os provedores têm a oportunidade de expandir seus negócios e contribuir
              para o desenvolvimento socioeconômico local. A infraestrutura moderna oferece potencial para inovação e parcerias, promovendo
              não apenas o crescimento dos negócios, mas também a inclusão digital e o avanço da região como um todo.
              Imagine uma rede de alta velocidade que cobre a vastidão da floresta, conectando comunidades remotas e impulsionando o desenvolvimento econômico. Com o 5G FWA, você pode tornar isso possível.
              O alcance, a velocidade e a confiabilidade dessa tecnologia são ideais para superar as barreiras geográficas da Amazônia.
            </p>
            <p class="my-paragraph">
              A implementação do 5G FWA no Amazonas pode revolucionar a vida dos residentes, oferecendo acesso a serviços digitais essenciais
              e impulsionando o empreendedorismo local. Isso poderia resultar em um significativo aumento da atividade econômica na região, 
              gerando empregos e promovendo o crescimento sustentável. Para as empresas de telecomunicações, o 5G FWA representa uma 
              oportunidade lucrativa para expandir sua base de clientes e estabelecer uma presença forte em um mercado previamente subatendido, 
              contribuindo assim para o desenvolvimento socioeconômico do Amazonas.
            </p>
          </div>
          </section>
      </v-main>
      <MyFooter />
</v-app>
    
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Ubuntu:wght@300;400;500;700&display=swap');

html { 
  overflow-y: auto !important;
  scroll-behavior: smooth;
}

#app {
  margin: 0px;
  padding: 0px;
  min-width: 100vw;
  font-family: 'Ubuntu', sans-serif;
}

.v-application {
  background-color: transparent !important;
  min-width: 100vw;
}

.v-application__wrap {
  min-width: fit-content !important;
}

main {
  background-color: transparent;
}

.section-header {
  height: 100vh !important;
  width: 100vw !important;
  color: white;
  font-size: 100px;
  text-align: center;
  align-items: center;
  display: flex;
  flex-direction: column;

  .my-heading-2 {
    margin-top: 220px !important;
    margin-bottom: 130px;
  }

  .my-icon {
    transition: transform .5s ease-in;
    animation: 2s bounce infinite;
    cursor: pointer;
    border-radius: 50%;
    color: white;
  }
  
}

@keyframes bounce {
  0% {
    transform: translateY(0px);
  }
  50%{
    transform: translateY(20px);
  }
  100%{
    transform: translateY(0px);
  }
}

.my-section {
  width: 85%;
  background-color: rgba(54, 82, 51, 0.836);
  box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
  border-radius: 6px;
  color: white;
  border: 2px white solid;
  padding-bottom: 20px;

  .my-heading-1{
    font-size: 64px;
  }

  .my-paragraph{
    font-size: 20px;
    padding: 0px;
    text-align: justify;
    margin-bottom: 6px;
  }
}

@media (max-width: 600px) {
  .my-paragraph{
    font-size: 14px !important;
  }
  .my-heading-1{
    font-size: 30px !important;
  }
  .my-heading-2{
    font-size: 30px !important;
  }
}
</style>
