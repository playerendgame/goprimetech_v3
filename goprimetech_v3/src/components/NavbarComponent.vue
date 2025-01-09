<template>
    <nav class="navbar navbar-expand-lg" id="navbar" :class="{'bg-green': isScrolled}">
        <div class="container-fluid">
            <img class="img-fluid bg-light p-3 rounded-3" style="width: 13vw; margin-right: 2rem" src="../assets/images/logo.png">
            <button class="navbar-toggler bg-light" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0" id="navbarItems">
                <li class="nav-item">
                    <a class="nav-link text-light" :class="{'nav-item': isScrolled}" aria-current="page" href="#">About Us</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-light" :class="{'nav-item': isScrolled}" aria-current="page" href="#">Our Brands</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-light" :class="{'nav-item': isScrolled}" aria-current="page" href="#">Contact Us</a>
                </li>
            </ul>
            <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                <li class="nav-item">
                    <div class="button">
                        <button class="btn btn-outline-light" :class="{'btn-color': isScrolled}">Contact Us!</button>
                    </div>
                </li>
            </ul>
            </div>
        </div>
    </nav>
</template>

<script>
export default {
    data() {
        return {
            isScrolled: false
        }
    },
    mounted() {
        window.addEventListener('scroll', this.handleScroll)
    },
    beforeUnmount() {
        window.removeEventListener('scroll', this.handleScroll)
    },
    methods: {
        handleScroll() {
            if (window.scrollY > 500) {
                this.isScrolled = true
            } else {
                this.isScrolled = false
            }
        }
    }
}
</script>

<style>
.navbar {
    transition: background-color 0.5s ease;
}
.bg-green{
    background-color: rgb(250, 248, 248);
    border-bottom: 0px;
}

.nav-item{
    color: black !important;
}

.btn-color{
    background-color: green;
}

.btn-color:hover{
    color: black;
    border: 1px black;
    border-style: solid;
}
</style>