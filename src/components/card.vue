<template>
    <div class="card">
      <div class="card-image" v-if="$slots.image">
        <slot name="image"></slot>
      </div>
      <div class="card-header" v-if="$slots.header">
        <slot name="header"></slot>
      </div>
      <div class="card-image" v-if="$slots.imageCenter">
        <slot name="imageCenter"></slot>
      </div>
      <div class="card-body" v-if="$slots.body">
        <slot name="body"></slot>
      </div>
      <div class="card-image" v-if="$slots.imageBody">
        <slot name="imageBody"></slot>
      </div>
      <div class="card-footer" v-if="$slots.footer">
        <slot name="footer"></slot>
      </div>
      <div class="card-image" v-if="$slots.imageFooter">
        <slot name="imageFooter"></slot>
      </div>
    </div>
</template>

<script>
export default {
  name: 's-card',
  props: {

  },
  computed: {

  },
  methods: {

  }
}
</script>
