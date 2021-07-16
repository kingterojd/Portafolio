<template>
  <q-page class="q-py-md">
    <div class="row justify-center">
      <div class="col-xs-12 col-md-8 col-lg-4">
         <q-card flat>
            <q-card-section class="text-center q-pb-none">
              <q-avatar size="120px">
                <img src="../statics/images/profile.png">
              </q-avatar>
              <div class="q-pt-md">
                <q-icon name="lab la-github" size="md" class="q-px-sm cursor-pointer">
                  <q-tooltip :offset="[10, 3]">Github</q-tooltip>
                </q-icon>
                <q-icon name="lab la-linkedin-in" size="md" class="q-px-sm cursor-pointer">
                  <q-tooltip :offset="[10, 3]">Linkedin</q-tooltip>
                </q-icon>
                <q-icon name="lab la-gitlab" size="md" class="q-px-sm cursor-pointer">
                  <q-tooltip :offset="[10, 3]">Gitlab</q-tooltip>
                </q-icon>
              </div>
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
