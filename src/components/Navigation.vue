<template>
    <nav class="navigation">
        <ul class="navigation__list">
            <li class="navigation__item">
                <router-link to="/" class="navigation__link">Home</router-link>
            </li>
            <li class="navigation__item">
                <router-link to="/project" class="navigation__link">Project</router-link>
            </li>
            <li class="navigation__item">
                <router-link to="/blog" class="navigation__link">Blog</router-link>
            </li>
        </ul>
    </nav>
</template>

<script>
export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name: 'Navigation',
};
</script>

