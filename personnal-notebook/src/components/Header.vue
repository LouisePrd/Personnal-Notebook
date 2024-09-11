<script setup>

</script>

<template>
    <div class="navbar">
        <div class="navLogo">
            <img src="" alt="logo" />
        </div>
        <div class="navMenu">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">French</a></li>
                <li><a href="#">English</a></li>
                <li><a href="#">All</a></li>
            </ul>
        </div>
    </div>

</template>

<style scoped>
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem;
    color: rgb(255, 255, 255);
}

.navLogo img {
    width: 50px;
    height: 50px;
}

.navMenu ul {
    display: flex;
    list-style: none;
}

.navMenu ul li {
    margin-right: 1rem;
}

.navMenu a {
    text-decoration: none;
    color: rgb(0, 0, 0);
}

.navMenu a:hover {
    text-decoration: underline;
}



</style>
