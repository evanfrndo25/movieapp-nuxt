<template>
    <div class="loading">
        <span></span>
    </div>
</template>

<script>
export default {
    name: 'LoadingComponent'
}
</script>


<style lang="scss" scoped>
.loading{
    height: 100vh;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;

    @keyframes circle-loading {
        to{
            transform: rotateZ(360deg);
        }
    }
}
</style>