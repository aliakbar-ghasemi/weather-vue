<template>
  <div>
    <div class="flex flex-col">
      <font-awesome-icon icon="fa-solid fa-user-secret" class="text-2xl" />

      <font-awesome-icon icon="fa-solid fa-coffee" size="lg" />
      <!-- X-factor sizing -->
      <font-awesome-icon icon="fa-solid fa-coffee" size="6x" />

      <font-awesome-icon :icon="['fas', 'coffee']" fixed-width />

      <!-- Rotate -->
      <font-awesome-icon icon="fa-solid fa-coffee" rotation="90" />
      <font-awesome-icon icon="fa-solid fa-coffee" rotation="180" />
      <font-awesome-icon icon="fa-solid fa-coffee" rotation="270" />

      <!-- Mirror -->
      <font-awesome-icon icon="fa-solid fa-coffee" flip="horizontal" />
      <font-awesome-icon icon="fa-solid fa-coffee" flip="vertical" />
      <font-awesome-icon icon="fa-solid fa-coffee" flip="both" />

      <font-awesome-icon icon="fa-solid fa-heart" beat />
      <font-awesome-icon icon="fa-solid fa-circle-info" beat-fade />
      <font-awesome-icon icon="fa-solid fa-basketball" bounce />
      <font-awesome-icon icon="fa-solid fa-triangle-exclamation" fade />
      <font-awesome-icon icon="fa-solid fa-compact-disc" flip />
      <font-awesome-icon icon="fa-solid fa-bell" shake />
      <font-awesome-icon icon="fa-solid fa-cog" spin />
      <font-awesome-icon icon="fa-solid fa-compass" spin spin-reverse />
      <font-awesome-icon icon="fa-solid fa-spinner" spin-pulse />

      <font-awesome-icon icon="fa-solid fa-coffee" border />

      <font-awesome-icon icon="fa-solid fa-coffee" pull="left" />
      <font-awesome-icon icon="fa-solid fa-coffee" pull="right" />

      <font-awesome-icon
        icon="fa-solid fa-coffee"
        transform="shrink-6 left-4"
      />

      <!-- using transform with mask will allow you to scale, shrink, grow, etc. the coffee icon within the circle icon -->
      <font-awesome-icon
        icon="fa-solid fa-coffee"
        transform="shrink-7"
        mask="fa-solid fa-circle"
      />
    </div>
  </div>
</template>

<script lang="ts">
export default {};
</script>

<style>
</style>