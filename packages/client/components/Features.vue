<template>
  <section class="bg-white border-b pb-8">
    <div class="container mx-auto mb-8">
      <h1 class="w-full mb-2 text-5xl font-bold leading-tight text-center text-gray-800">
        Use Cases
      </h1>

      <div class="w-full mb-4">
        <div class="h-1 mx-auto gradient w-64 opacity-25 my-0 py-0 rounded-t"></div>
      </div>

      <workflow-table />
    </div>
  </section>
</template>

<script>
import WorkflowTable from '~/components/workflow/table.vue'

export default {
  name: 'Features',
  components: {
    WorkflowTable,
  },
}
</script>
