<template>
    <span class="dot_on" v-if="field.value"></span>
    <span class="dot_off" v-else-if="field.value"></span>
</template>

<script>
export default {
    props: ['resourceName', 'field'],
}
</script>
