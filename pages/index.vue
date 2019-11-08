<template>
　<div>
　　<h1>Hello World</h1>
　　<NLink to="/about">
      地獄
    </NLink>
　　<NLink to="/love">
　　　　人世
    </NLink>
　</div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>
