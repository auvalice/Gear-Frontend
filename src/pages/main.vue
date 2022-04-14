<script setup lang="ts">
const { t } = useI18n()
</script>

<template>
  <div>
    <div text-4xl>
      <div i-carbon-settings inline-block w-32 h-32 />
    </div>
    <p>
      <a rel="noreferrer" href="https://github.com/antfu/vitesse" target="_blank">
        Gear
      </a>
    </p>
    <p>
      <em text-sm opacity-75>{{ t('app.description') }}</em>
    </p>
  </div>
</template>

<route lang="yaml">
meta:
  layout: home
</route>
