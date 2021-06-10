<template>
  <div class="home">
    <v-list
      flat
    >
      <v-list-item>
        <template v-slot:default="{ active }">
          <v-list-item-action>
            <v-checkbox :input-value="active"></v-checkbox>
          </v-list-item-action>

          <v-list-item-content>
            <v-list-item-title>Wake Up sid!</v-list-item-title>
          </v-list-item-content>
        </template>
      </v-list-item>

    </v-list>
  </div>  
</template>

<script>
  

  export default {
    name: 'Todo',
    data() {
      return {
        tasks: [
          {
            id: 1,
            title: 'Wake up'
          },
           {
            id: 2,
            title: 'Bananas'
          },
          {
            id: 3,
            title: 'Ape it'
          },
        ]
      }
    }
  }
</script>
