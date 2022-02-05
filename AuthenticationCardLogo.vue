<template>
    <a href="/">
      <ApplicationLogo />
    </a>
</template>

<script>
    import { defineComponent } from 'vue'
    import ApplicationLogo from './ApplicationLogo'

    export default defineComponent({
        components: {
            Link,
        },
    })
</script>
