<template>
  <div>Index</div>
  <Link href="/hello">Show Page</Link>
  <div>
    The message is {{ message }}
  </div>
</template>

<script setup>
import { Link } from '@inertiajs/inertia-vue3'
import MainLayouts from '../../Layouts/MainLayouts.vue'
defineProps({ message: String })
</script>
