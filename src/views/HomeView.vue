<script setup>
import HeaderComponent from '../components/HeaderComponent.vue';
import FooterComponent from '../components/FooterComponent.vue';
</script>

<template>
  <HeaderComponent />
  <main>
    <section class="banner">

            <h1>Hi, I’m <span>Alex</span></h1>

            <p>
                a <strong>UI/UX Designer</strong> based in <strong>Los Angeles</strong>. With over <strong>3 years of experience</strong>, I specialize in creating
                user-friendly digital products that solve real-world problems.
            </p>
        </section>

        <section class="cards">
            <ul>
                <li>
                    <h3>ShopEase</h3>
                    <p><img src="/images/shopease.png" alt="imagem celular"></p>
                    <ul>
                        <li>Mobile</li>
                        <li>Application</li>
                        <li>E-commerce</li>
                    </ul>
                </li>
                <li>
                     <h3>Insightly</h3>
                     <p class="emogi">💡</p>
                     <p>
                        Developed a SaaS-based analytics dashboard for Insightly, focusing on providing actionable insights through a user-centric design. The dashboard improved data accessibility and was adopted by 80% of users within the first three months.
                     </p>
                     <ul>
                        <li>Web 3.0</li>
                        <li>HTML</li>
                        <li>Dashboard</li>
                    </ul>
                </li>
                <li>
                    <h3>ShopEase</h3>
                    <p><img src="/images/shopease.png" alt="imagem celular"></p>
                    <ul>
                        <li>Mobile</li>
                        <li>Application</li>
                        <li>E-commerce</li>
                    </ul>
                </li>
                <li>
                     <h3>Insightly</h3>
                     <p class="emogi">💡</p>
                     <p>
                        Developed a SaaS-based analytics dashboard for Insightly, focusing on providing actionable insights through a user-centric design. The dashboard improved data accessibility and was adopted by 80% of users within the first three months.
                     </p>
                     <ul>
                        <li>Web 3.0</li>
                        <li>HTML</li>
                        <li>Dashboard</li>
                    </ul>
                </li>
            </ul>
        </section>
  </main>
  <FooterComponent />
</template>

<style scoped>
section.cards>ul {

    &>li {
        background: white;
        border-radius: 10px;
        padding: 20px;
        margin-bottom: 20px;

        & h3 {
            font-size: 1.5rem;
        }

        & img {
            border-radius: 10px;
        }

        & .emogi {
            font-size: 4rem;
        }
    }

    & ul {
        display: flex;
        margin-top: 20px;

        & li:first-child {
            margin-left: 0;
        }

        & li {
            background: rgb(232, 232, 232);
            color: black;
            margin: 0 10px;
            padding: 4px 8px;
            border-radius: 10px;
            font-size: 0.7rem;
            font-weight: bold;
        }
    }
}

</style>
