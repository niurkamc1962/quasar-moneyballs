<template>
  <q-page>
    <div class="q-pa-md">
      <q-list bordered separator>
        <q-item>
          <q-item-section> Salary </q-item-section>

          <q-item-section side> + $4,999.99 </q-item-section>
        </q-item>
      </q-list>
    </div>
  </q-page>
</template>

<script setup lang="ts">
import { ref } from 'vue'

interface entries {
  id: number
  name: string
  amount: string
}

const entries = ref([
  {
    id: 'id1',
    name: '',
    amount: 0,
  },
  {
    id: 'id2',
    name: '',
    amount: 0,
  },
  {
    id: 'id3',
    name: '',
    amount: 0,
  },
  {
    id: 'id4',
    name: '',
    amount: 0,
  },
])
</script>
