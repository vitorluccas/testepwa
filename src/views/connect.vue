<script setup>
import HeaderComponent from '../components/HeaderComponent.vue';
import FooterComponent from '../components/FooterComponent.vue';
</script>
<template>
  <HeaderComponent />
 <main>
        <section class="banner">

            <h1><span>Connect</span></h1>

            <p>
                I’m always open to new opportunities and collaborations. Whether you’re looking to start a project or just want to chat, feel free to reach out.
            </p>
        </section>

        <section class="connect">
            <ul class="white-itens">
                <li>
                    <a href="#"><span class="fa-brands fa-instagram"></span>Instagram</a>

                </li>
                <li>
                    <a href="#"><span class="fa-brands fa-behance"></span> Behance</a>    
                </li>
                <li><a href="#"><span class="fa-brands fa-dribbble"></span>Dribble</a>
                </li>
                <li><a href="#"><span class="fa-brands fa-linkedin-in"></span>LinkedIn</a>
                </li>
            </ul>
        </section>
    </main>

  <FooterComponent />
</template>

<style>
section.connect {
    & ul {
        & li {
            text-align: center;
            & span {
                font-weight:bold ;
                padding: 0 15px 0 0;
            }
        } 
    }
}
</style>
