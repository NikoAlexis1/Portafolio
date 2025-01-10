<template>
    <nav class="navbar bg-dark">
        <div class="container-fluid d-flex justify-content-center">
            <ul class="nav">
                <li class="nav-item">
                    <a class="nav-link" href="#">Inicio</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Sobre mi</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Proyectos</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Contacto</a>
                </li>
            </ul>
        </div>
    </nav>
</template>

<style scoped>
.nav-link {
    color: #c3c3c3;
}
.nav-link:hover {
    color: #ffffff;
}

@media (max-width: 400px) {
    .navbar {
        display: none;
    }
}
</style>