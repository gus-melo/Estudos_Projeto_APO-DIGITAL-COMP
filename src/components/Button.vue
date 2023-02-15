<template>
    <button>{{ buttonText }}</button>
    <button>{{ buttonText }}</button>
    <button>{{ buttonText }}</button>
</template>

<script>
export default {
 props: {
    buttonText: {
        type: String,
        default: () => "Clique Aqui",
    },
 },
};
</script>