<template>
  <v-container>
    <v-layout
      text-center
      wrap
    >
      <v-flex mb-12 md12>
        <h4 class="display-2 font-weight-bold mb-3">
          I want to learn about...
        </h4>
      </v-flex>

      <v-flex md3>
        <v-card>
        <v-img
          :src="require('../assets/logo.svg')"
          class="my-3"
          contain
          height="50"
        ></v-img>
        <p class="subheading font-weight-regular">
          Financial Basics
        </p>
        <router-link :to="{name: 'time'}">
        <v-btn
          text
          color="success"
        >
          Learn
        </v-btn>
        </router-link>
        </v-card>
      </v-flex>
      <v-flex md3>
        <v-card>
        <v-img
          :src="require('../assets/logo.svg')"
          class="my-3"
          contain
          height="50"
        ></v-img>
        <p class="subheading font-weight-regular">
          Investment Choices
        </p>
        <router-link :to="{name: 'time'}">
        <v-btn
          text
          color="success"
        >
          Learn
        </v-btn>
        </router-link>
        </v-card>
      </v-flex>
      <v-flex md3>
        <v-card>
        <v-img
          :src="require('../assets/logo.svg')"
          class="my-3"
          contain
          height="50"
        ></v-img>
        <p class="subheading font-weight-regular">
          Practical Tips
        </p>
        <router-link :to="{name: 'time'}">
        <v-btn
          text
          color="success"
        >
          Learn
        </v-btn>
        </router-link>
        </v-card>
      </v-flex>
      <v-flex md3>
        <v-card>
        <v-img
          :src="require('../assets/logo.svg')"
          class="my-3"
          contain
          height="50"
        ></v-img>
        <p class="subheading font-weight-regular">
          Common Pitfalls
        </p>
        <router-link :to="{name: 'time'}">
        <v-btn
          text
          color="success"
        >
          Learn
        </v-btn>
        </router-link>
        </v-card>
      </v-flex>

    </v-layout>
  </v-container>
</template>

<script>

export default {
  name: 'home',
}
</script>
