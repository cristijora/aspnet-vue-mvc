<template>
    <div class="time">
        {{ time }}
    </div>
</template>
<script>
    export default {
        props: {
            time: {
                type: Object,
                required: true, 
            }
        }
    }
</script>
<style>
    .time {
        color: #F44336;
    }
</style>