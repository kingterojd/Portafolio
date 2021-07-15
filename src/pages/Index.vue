<template>
  <q-page class="q-py-md">
    <div class="row justify-center">
      <div class="col-lg-4 col-md-8 col-sm-12">
         <q-card flat>
            <q-card-section class="text-center">
              <q-avatar size="100px">
                <img src="https://cdn.quasar.dev/img/boy-avatar.png">
              </q-avatar>
              <div class="text-h6">Our Changing Planet</div>
              <div class="text-subtitle2">by John Doe</div>
            </q-card-section>
            <q-card-section>
              <div v-for="item in 25" :key="item" class="q-pa-md">
                <q-btn color="black" class="full-width" label="Full-width" style="border-radius: 5px"/>
              </div>
            </q-card-section>
         </q-card>
      </div>
    </div>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'PageIndex'
})
</script>
