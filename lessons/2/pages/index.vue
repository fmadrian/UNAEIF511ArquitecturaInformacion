<!-- pages/index.vue -->
<template>
    <MyHeader />
    <main>
        <h1>Home Page</h1>
        <ul>
            <li>
                <NuxtLink to="/blog">
                    See blog.md
                </NuxtLink>
            </li>
            <li>
                <NuxtLink to="/myfile">
                    See myfile.md
                </NuxtLink>
            </li>
        </ul>
    </main>
    <MyFooter />
</template>
<script setup>

</script>