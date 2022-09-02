<template>
    <div class="hero">
        <img src="https://picsum.photos/id/130/800/400" alt="landscape">
        <div class="hero__content">
            <h2>Hero Title</h2>
        </div>
    </div>
</template>

<script>

export default {
    name: 'HeroSection'
}

</script>

<style>
.hero {
    max-width: 1200px;
    aspect-ratio: 3 / 2;

    padding: 0 16px;
    margin: 0 auto;

    position: relative;
}

img {
    width: 100%;
    height: 100%;

    display: block;

    object-fit: cover;
    object-position: center;
}

.hero__content {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
    font-size: 48px;
}
</style>