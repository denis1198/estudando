<template>
    <div class="form-group">
        <label :for="id" class="form-label">{{ titulo }}</label>
        <slot></slot>
        <div :id="idHelp" class="form-text">
            {{ texto }}
        </div>
    </div>
</template>

<script>
export default {
    props: ["id", "titulo", "idHelp", "texto"],
};
</script>
