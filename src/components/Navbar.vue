
<template>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <RouterLink class="navbar-brand" to="/">D-VICE</RouterLink>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup"
                aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav ms-auto mb-2 mb-lg-0">
                    <RouterLink to="/" class="nav-item nav-link">Home</RouterLink>
                    <RouterLink to="/about" class="nav-item nav-link">About</RouterLink>
                    <RouterLink to="/todo" class="nav-item nav-link">Todo</RouterLink>
                </div>
                <form class="d-flex">
                   <input class="form-control me-3" type="search" placeholder="search" aria-label="Search">
                   <button class="btn btn-outline-secondary " type="submit">Search</button>
                </form>

            </div>

        </div>
    </nav>
    
</template>
<style scoped>

</style>