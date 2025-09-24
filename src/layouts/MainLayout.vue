<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated>
       <q-toolbar class="bg-purple text-white shadow-2 rounded-borders">
          <q-btn flat label="Enrique da Costa Carvalho" />
          <q-space />      
          <q-tabs shrink>
            <q-tab name="tab1" label="Tab 1" />
            <q-tab name="tab2" label="Tab 2" />
            <q-tab name="tab3" label="Tab 3" />
          </q-tabs>
        </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script setup lang="ts">
</script>
