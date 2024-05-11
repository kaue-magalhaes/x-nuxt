<script setup lang="ts">

</script>

<template>
    <div>
        <ul>
            <li>
                <NuxtLink href="/login">
                    Login
                </NuxtLink>
            </li>
            <li>
                <NuxtLink href="/register">
                    Register
                </NuxtLink>
            </li>
        </ul>
        <h1>
            Esse é o layout guest
        </h1>

        <slot />
    </div>

</template>

<style scoped>

</style>