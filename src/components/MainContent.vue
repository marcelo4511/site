<template>
    <div>
        <!-- Home Section -->
        <section id="home" class="text-light bg-dark text-center d-flex align-items-center" style="height: 100vh;">
            <div class="container">
            <h1 class="display-4">Desenvolvedor PHP Full Stack Especializado</h1>
            <p class="lead">Criação de Aplicações Web e Soluções Backend Otimizadas</p>
            </div>
        </section>

        <!-- Sobre Mim Section -->
        <section id="about" class="py-5">
            <div class="container">
            <h2 class="text-center mb-4">Sobre Mim</h2>
            <div class="row">
                <div class="col-md-6">
                <img src="@/assets/perfil.jpg" width="300" height="300" class="img-fluid" alt="Desenvolvedor PHP">
                </div>
                <div class="col-md-6">
                <p>Eu sou um desenvolvedor fullstack (laravel, vueJS), com mais de 3 anos de experiência em criação de websites e aplicações robustas. Tenho amplo conhecimento em Laravel, MySQL, VUE, APIs RESTful e segurança de aplicações web.</p>
                </div>
            </div>
            </div>
        </section>

        <!-- Serviços Section -->
        <section id="services" class="py-5 bg-light">
            <div class="container">
            <h2 class="text-center mb-4">Meus Serviços</h2>
            <div class="row">
                <div class="col-md-4 text-center">
                <div class="icon mb-3">
                    <i class="bi bi-code-slash" style="font-size: 3rem;"></i>
                </div>
                <h4>Desenvolvimento Backend</h4>
                <p>Criação de backends escaláveis e seguros usando PHP e frameworks modernos como Laravel.</p>
                </div>
                <div class="col-md-4 text-center">
                <div class="icon mb-3">
                    <i class="bi bi-server" style="font-size: 3rem;"></i>
                </div>
                <h4>Integração com APIs</h4>
                <p>Desenvolvimento e integração com APIs RESTful, garantindo a interoperabilidade de sistemas.</p>
                </div>
                <div class="col-md-4 text-center">
                <div class="icon mb-3">
                    <i class="bi bi-lock-fill" style="font-size: 3rem;"></i>
                </div>
                <h4>Interfaces dinâmicas</h4>
                <p>Realização de interfaces para melhor experiência operacional ao usuário (utilizando padrão Vue.js).</p>
                </div>
            </div>
            </div>
        </section>

        <!-- Portfólio Section -->
        <section id="portfolio" class="py-5">
            <div class="container">
            <h2 class="text-center mb-4">Meu Portfólio</h2>
            <div class="row">
                <div class="col-md-4 mb-4">
                <div class="card">
                    <img src="@/assets/finance.png" class="card-img-top" alt="Projeto 1">
                    <div class="card-body">
                    <h5 class="card-title">Expense Home</h5>
                    <p class="card-text">Projeto de finanças para famílias, simples, contendo as despesas, despesas e poupanças, tendo como ponto forte um dashbord administrativo.</p>
                    <p>Esse prejeto foi feito com tecnologias como: Laravel 10, Vue 3 , inertia.Js, Vuetify entre outras</p>
                    <a href="https://homologacao.marcelobsprogramador.online/login" class="btn btn-primary">Ver Projeto</a>
                    </div>
                </div>
                </div>
                <div class="col-md-4 mb-4">
                <div class="card">
                    <img src="@/assets/surveys.png" target="_bank" height="200" width="350" class="card-img-top" alt="Projeto 2">
                    <div class="card-body">
                    <h5 class="card-title">Enquete PRO</h5>
                    <p class="card-text">Descrição breve.</p>
                    <a href="#" class="btn btn-primary">Ver Projeto</a>
                    </div>
                </div>
                </div>
                <!-- <div class="col-md-4 mb-4">
                <div class="card">
                    <img src="https://via.placeholder.com/350x200" class="card-img-top" alt="Projeto 3">
                    <div class="card-body">
                    <h5 class="card-title">Projeto 3</h5>
                    <p class="card-text">Descrição breve do projeto 3.</p>
                    <a href="#" class="btn btn-primary">Ver Projeto</a>
                    </div>
                </div>
                </div> -->
            </div>
            </div>
        </section>
        
    </div>
</template>

<script>
export default {
  name: 'MainContent'
}
</script>

<style scoped>
main {
    padding: 2rem;
    text-align: center;
}

h1 {
    color: #333;
}
</style>