<template>
    <div id="application">
        <div class="buttons">
            <button class="button red" v-for="(lang, i) in langs" :key="`Lang${i}`" @click="setLocale(lang)">{{ lang }}</button>
        </div>
        <Manjaro/>
    </div>
</template>

<script>
import Manjaro from "./components/Manjaro";

export default {
    name: 'application',
    components: {
        Manjaro
    },
    data () {
    return { langs: ['en', 'ru'] }
    },
    methods: {
        setLocale(locale) {
            this.$i18n.locale = locale
        }
    }
}
</script>
