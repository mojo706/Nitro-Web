<template>
  <ds-card :header="$t('admin.users.name')">
    <hc-empty
      icon="tasks"
      message="Comming Soon…"
    />
  </ds-card>
</template>

<script>
import HcEmpty from '~/components/Empty.vue'

export default {
  components: {
    HcEmpty
  }
}
</script>
