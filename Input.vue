<template>
    <div>
        <label v-if="label">{{ label }}</label>
        <input type="text" class="px-3 py2 rounded outline-none border border-transparent shadow focus:border-red-400" placeholder="Escreva algo..." :value="value
        "/>
        <input type="text" class="px-3 py2 rounded outline-none border border-transparent shadow focus:border-red-400" placeholder="Escreva algo..." :value="value
        "/>
        <input type="text" class="px-3 py2 rounded outline-none border border-transparent shadow focus:border-red-400" placeholder="Escreva algo..." :value="value
        "/>
    </div>
</template>

<script>
export default {
    props: {
    value: { default: null, type: String },
    label: { default: null, type: String },
 }
};
</script>