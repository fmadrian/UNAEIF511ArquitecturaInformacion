<!-- pages/index.vue -->
<template>
    <MyHeader />
    <main>
        <h1>Home Page</h1>
        <ul>
            <li>
                <NuxtLink to="/about">
                    About (internal link that belongs to the Nuxt App)
                </NuxtLink>
            </li>
            <li>
                <a href="https://nuxtjs.org">External Link to another page</a>
            </li>
            <li>
                <NuxtLink to="users-mygroup/23">
                    How to pass route parameters <b>Example: (mygroup and 23).</b>
                </NuxtLink>
            </li>
            <li>
                <NuxtLink to="docs/main/draft/madeupparameter">
                    How to pass X amount of parameters (a slug) <b>Example: (main, draft, madeupparameter).</b>
                </NuxtLink>
            </li>
        </ul>
    </main>
    <MyFooter />
</template>
<script setup>

</script>