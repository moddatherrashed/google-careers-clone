<template>
      <button>{{title}}</button>
</template>

<script>
import './scss/_base_button.scss'
export default {
      name : 'BaseButton',
      props:['title']
}
</script>