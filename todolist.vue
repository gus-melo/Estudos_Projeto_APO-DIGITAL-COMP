<template>
    <div>
    <h1>To-Do List</h1>
    <input v-model.trim="tarefa">
    <button @click="addTarefa" type="button">Adicionar Tarefa</button>
    <ul>
        <li v-for="tarefa in tarefas" :key="tarefa">{{ tarefa }}</li>
    </ul>
</div>
</template>

<script>
    export default {
    name: "todolist",
    data () {
        return {
            tarefa: "",
            tarefas: ["", "", ""]
        }
    },
    methods: {
        addTarefa() {
            this.tarefas.push(this.tarefa)
            this.tarefa = ""
        }
    }
}
</script>