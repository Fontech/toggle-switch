<template>
    <boolean-icon :value="field.value" />
</template>

<script>
export default {
    props: ['resourceName', 'field'],
}
</script>
