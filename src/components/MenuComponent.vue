<template>
    <div class="menu-container">
       <nav class="navbar navbar-expand-lg bg-primary">
        <div class="container-fluid">
            <a class="navbar-brand text-bg-primary" href="#">Navbar</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
            <div class="navbar-nav">
                <a class="nav-link active text-bg-primary" aria-current="page" href="#">Home</a>
                <a class="nav-link text-bg-primary" href="#">Features</a>
                <a class="nav-link text-bg-primary" href="#">Pricing</a>
                <a class="nav-link text-bg-primary">Disabled</a>
            </div>
            </div>
        </div>
       </nav>
    </div>
</template>


<script>
export default {
    
}
</script>

<style scoped>
  .menu-container{
    margin-top: -60px;
  }
</style>


