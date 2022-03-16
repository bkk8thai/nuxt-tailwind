<template>
  <div class="container mx-auto">
    <FormulateInput
      class="w-96"
      outer-class="border p-2 border-red-200 rounded bg-red-100"
      input-class="border px-2 py-1 border-red-200 rounded outline-none focus:ring focus:ring-red-600 focus:ring-offset-0"
      label-class="text-sm font-red-600 font-bold"
      help-class=""
      error-class=""
      type="text"
      name="sample"
      label="Sample text input"
      placeholder="Sample placeholder"
      help="Sample help text"
      validation="required"
      error-behavior="live"
    />
    <Tutorial />
  </div>
</template>

<script>
import Tutorial from '@/components/Tutorial'

export default {
  name: 'IndexPage',
  components: { Tutorial },
}
</script>
