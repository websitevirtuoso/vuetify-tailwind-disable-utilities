<template>
  <v-app>
    <v-main>
      Has to work even with disabled css utilities classes
      <v-container>
        <v-row>
          <v-col md="6">
            <v-text-field
              label="First name"
              hide-details="auto"
            />
          </v-col>
          <v-col md="6">
            <v-text-field
              label="Last name"
              hide-details="auto"
            />
          </v-col>
        </v-row>
      </v-container>
      Using utility class d-flex to show that it exist
      <div class="d-flex" style="gap: 20px">
        <v-text-field
          label="First name"
          hide-details="auto"
        />
        <v-text-field
          label="Last name"
          hide-details="auto"
        />
      </div>
    </v-main>
  </v-app>
</template>

<script setup lang="ts">
</script>
