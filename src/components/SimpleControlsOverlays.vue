<template lang="html">
  <div data-name="SimpleControlsOverlays">
    <ButtonOverlayToggle
      class="control_button"
      v-bind:overlay_name="'volume'"
      v-bind:show="true"
    />
    <ButtonOverlayToggle
      class="control_button"
      v-bind:overlay_name="'zone_select'"
      v-bind:show="true"
    />
    <ButtonOverlayToggle
      class="control_button"
      v-bind:overlay_name="'settings'"
      v-bind:show="true"
    />
  </div>
</template>

<script>
export default {
  name: "SimpleControlsOverlays",
};
</script>
