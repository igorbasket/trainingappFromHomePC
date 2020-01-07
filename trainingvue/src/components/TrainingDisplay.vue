<template>
    <div>
        <Countdown end="August 22, 2022" showDays showHours showMinutes showSeconds></Countdown>
        or
    </div>
</template>

<script>
    import Countdown from 'vuejs-countdown'

    export default {
        name: "TrainingDisplay",
        components: { Countdown }

    }

</script>

<style scoped>

</style>