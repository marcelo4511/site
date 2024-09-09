<template>
    <footer class="bg-dark text-white py-2 mt-1">
    <div class="container">
        
        <!-- Footer Bottom -->
        <div class="row d-flex justify-content-between">
            <p>Entre em Contato: <i class="fas fa-envelope-open-o"></i> <a href="mailto:dev@example.com" class="text-white">dev@example.com</a></p>

            <div class="col-md-12 text-center">
                <p>&copy; 2024 Desenvolvedor PHP. Todos os direitos reservados.</p>
            </div>
        </div>
    </div>
    </footer>
</template>

<script>
export default {
    name: 'FooterLayout'
}
</script>

<style scoped>
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem;
    position: fixed;
    width: 100%;
    bottom: 0;
}
</style>