<template>
  <v-layout>
    <v-flex class="text-center">
      <img src="/v.png" alt="Vuetify.js" class="mb-5" />
      <blockquote class="blockquote">
        &#8220;{{ $t('inspire.message') }}&#8221;
        <footer>
          <small>
            <em>&mdash;{{ $t('inspire.from') }}</em>
          </small>
        </footer>
      </blockquote>
    </v-flex>
  </v-layout>
</template>

<script>
export default {
  head() {
    return {
      // Page title is "title - appName"
      title: 'Inspire',
    }
  },
}
</script>
