<script>

</script>

<div>
    <div class="flex flex-row items-center gap-16 border-b border-black justify-evenly">
        <div class="flex flex-row items-center">
            <img class="w-24" src="public/images/logo.png" alt="logo" />
            <h1 class="text-3xl">Laura Loison coiffure</h1>
        </div>
        <nav class=" flex text-xl gap-12">
            <a class="nav-button" href="/">Accueil</a>
            <a class="nav-button" href="/prestations">Prestations</a>
            <a class="nav-button" href="/contact">Contact</a>
        </nav>
    </div>
</div>
<style>
.nav-button {
    @apply flex border border-black rounded-lg p-2;
    @apply hover:bg-black hover:text-white transition-all duration-500;
}
</style>