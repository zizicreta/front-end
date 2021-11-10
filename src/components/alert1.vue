<template>
  <div>
    <v-alert
      border="top"
      color="red lighten-2"
      dark
    >
      I'm an alert with a top border and red color
    </v-alert>
    <v-alert
      border="right"
      :color=color1
      dark
    >
            {{line1}}
          </v-alert>
          <v-alert
            border="bottom"
            :color= color2
            dark
          >
            {{line2}}
          </v-alert>
          <v-alert
            border="left"
            color="indigo"
            dark
          >
      I'm an alert with a border left type info
    </v-alert>
  </div>
  </template>
<script>
export default {
  name: 'Alert',
  data:() => ({
    line1: 'test1',
    line2: 'test2',
    border: 'left',
    color1: 'blue',
    color2: 'red'
  })
}
</script>