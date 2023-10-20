<template>
    <div>
        {{ message }}
    </div>
</template>

<script>

export default {

    data: () => ({
        title: window.config.appName,
        message: "test"
    })
}
</script>
