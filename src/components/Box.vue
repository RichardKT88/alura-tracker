<template>
    <div class="box has-text-weight-bold" :style="estilos">
        <slot></slot>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    name: 'BoxVue',
    data() {
        return {
            estilos: {
                background: '#FAF0CA',
                // 'background-color': '#dedede',
                //  backgroundColor: '#f0a25a',
            }
        }
    }
})
</script>

<!-- <style scoped>
.box {
    background: #FAF0CA;
}
</style> -->
