<template>
    <nav class="navbar bg-light fixed-top navbar-expand-lg">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">
            <img src="@/assets/cat.jpeg" alt="" width="30" height="24" class="d-inline-block align-text-top">
            Gopher E-commerce
            </a>
            <!-- Burger menu-->
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <!-- Links -->
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                    <a class="nav-link" aria-current="page" href="#">Plushes</a>
                    </li>
                    <li class="nav-item">
                    <a class="nav-link" href="#">Clothes</a>
                    </li>
                    <li class="nav-item">
                    <a class="nav-link" href="#">Accessories</a>
                    </li>
                    <li class="nav-item">
                    <a class="nav-link" href="#"><UserIcon></UserIcon></a>
                    </li>
                    <li class="nav-item">
                    <a class="nav-link" href="#"><CartIcon></CartIcon> Cart 0</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<script>
import UserIcon from './icons/UserIcon.vue';
import CartIcon from './icons/CartIcon.vue';
export default {
    components: { UserIcon, CartIcon }
}
</script>

<style>

</style>