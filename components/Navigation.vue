<template>
    <nav>
        <ul class="Navigation">
            <li class="Navigation__link">
                <nuxt-link to="/">Home</nuxt-link>
            </li>
            <li class="Navigation__link">
                <nuxt-link to="/test">Test</nuxt-link>
            </li>
        </ul>
    </nav>
</template>

<script>

    export default {
        name: 'Navigation'
    };

</script>


<style lang="scss" scoped>

    .Navigation {
        display: flex;
        justify-content: center;
        margin: 0;
        padding: 0;
        list-style: none;

        &__link {
            font-size: 20px;
        }
    }

</style>
