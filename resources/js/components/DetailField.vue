<template>
    <panel-item :field="field">
        <template slot="value">
            <span class="dot_on" v-if="field.value"></span>
            <span class="dot_off" v-else-if="field.value"></span>
        </template>
    </panel-item>
</template>

<script>
export default {
    props: ['resource', 'resourceName', 'resourceId', 'field'],
}
</script>
