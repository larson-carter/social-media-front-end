<template>
  <div>
    <EmailComponent />
    <div>
      <PassowordComponent />
    </div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import EmailComponent from "@/components/Login/Email.vue";
import PasswordComponent from "@/components/Login/Password.vue";

@Options({
  components: {
    EmailComponent,
    PasswordComponent,
  },
})
export default class Login extends Vue {}
</script>
