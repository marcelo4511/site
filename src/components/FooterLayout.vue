<template>
    <footer id="footer" class="bg-dark text-white py-1 mt-2">
        <div class="container">
            <!-- Footer Bottom -->
            <div class="row ">
                <div class="d-flex justify-content-between">

                <p>Entre em Contato: <i class="fas fa-envelope-open-o"></i> <a href="mailto:dev@example.com" class="text-white">marcelobs96@outlook.com</a></p>

                    <div class="col-6 text-center">
                        <p>&copy; 2024 Desenvolvedor PHP. Todos os direitos reservados.</p>
                    </div>
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