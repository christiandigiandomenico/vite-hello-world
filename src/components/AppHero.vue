<script>
export default {
    name: 'AppHero',
}
</script>

<template>
    <div class="jumbotron">

        <p>This is a simple hero unit, a simple jumbotron-style component for calling extra attention to featured content or
            information.</p>

        <hr>

        <p>It uses utility classes for typography and spacing to space content out within the larger container.</p>

        <button>Learn More</button>

    </div>
</template>

<style>
.jumbotron {
    margin: auto;
    width: 700px;
    border: 1px solid gray;
    border-radius: 25px;
    text-align: center;
}

.jumbotron button {
    background-color: blue;
    border: none;
    padding: 15px;
    border-radius: 15px;
}
</style>