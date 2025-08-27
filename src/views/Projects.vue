<script setup>
import HeaderComponent from '../components/HeaderComponent.vue';
import FooterComponent from '../components/FooterComponent.vue';
</script>
<template>
  <HeaderComponent />
 <main>
      <section class="banner">
        <h1><span>Projects</span></h1>

        <p>
          Explore a selection of my work, showcasing how I approach design
          challenges. Each project reflects my commitment to creating
          user-centered experiences that blend functionality with aesthetic
          appeal.
        </p>
      </section>

      <section class="projects">
        <ul class="white-itens">
          <li>
            <h3>EcoCharge</h3>
            <p>
              Estações de recarga para veículos elétricos abastecidas com
              energia solar.
            </p>
          </li>
          <li>
            <h3>FinWise</h3>
            <p>
              Aplicativo de gestão financeira pessoal com análise de gastos e
              projeções automáticas.
            </p>
            <p>
              <img src="/images/finwise.png" alt="banner finwise" />
            </p>
          </li>
          <li>
            <h3>SmartAgro</h3>
            <p>
              Sistema de monitoramento agrícola com sensores IoT para otimizar
              irrigação e produtividade.
            </p>
          </li>
          <li>
            <h3>PicSphere</h3>
            <p>
              Rede social para compartilhamento de fotos com filtros e álbuns
              colaborativos.
            </p>
            <p>
              <img src="/images/picshere.png" alt="baner picshere" />
            </p>
          </li>
          <li>
            <h3>HealthTrack</h3>
            <p>
              Aplicativo para acompanhamento de saúde e hábitos, integrando
              dados de wearables
            </p>
          </li>
          <li>
            <h3>MentorHub</h3>
            <p>
              Plataforma de conexão entre mentores e mentorados com
              videochamadas integradas.
            </p>
            <p>
              <img src="/images/mentorhub.png" alt="banner mentorhub" />
            </p>
          </li>
        </ul>
      </section>
    </main>

  <FooterComponent />
</template>

<style>
section.projects{
    & ul li{
        & h3{
            font-weight: bold;
            font-size: 1.2rem;
            margin: 0.5rem;
        }
        & p{
            color: #757575;
            font-size: 0.9rem;
            line-height: 1.3rem;
            margin: 0.5rem;
        }

    }
}

</style>
