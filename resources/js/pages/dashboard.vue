<template>
    <div>
        
    </div>
</template>

<script>
import { mapGetters } from 'vuex'

export default {
    layout: 'basic',

    metaInfo () {
        return { title: this.$t('home') }
    },

    data: () => ({
        title: window.config.appName
    }),

    computed: mapGetters({
        authenticated: 'auth/check'
    })
}
</script>
