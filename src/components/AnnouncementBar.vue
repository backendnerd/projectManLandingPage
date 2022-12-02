<template>
    <div class="bar">
        <p class="message">{{ message }}</p>
    </div>
</template>
<script>
export default {
    data() {
        return {
            message: "Site is still under development! Thanks for waiting.",
        };
    },
};
</script>

<style scoped>
.bar {
    width: 100%;
    color: #f5f5f5;
    background-color: #002743;
    font-size: 0.75rem;
    padding: 0.5rem 0;
    display: flex;
    align-content: center;
    justify-items: center;
    position: relative;
}
.message {
    margin: auto;
}
</style>
