<template>  
  <div class="note-selector" v-bind:class="{active: false}">
     <p class="note-selector-title">{{ note.body }}</p>
     <p class="note-selector-timestamp">{{ note.timestamp }}</p>
   </div>
</template>

<script>
export default {
  name: 'note-selector',
  props: ['note']
};
</script>