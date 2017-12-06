<template>
    <f7-page hide-bars-on-scroll=''>
        <f7-navbar back-link='Back' title='Page 2' sliding='' />
        <f7-block>
            This is page number 2
            <br>
            mydata variable {{mydata}}!!!
        </f7-block>
    </f7-page>
</template>

<script>
export default {
  name: 'page2',
  data () {
    return {
      mydata: 'is actually meaningless'
    }
  }
}
</script>

<style>
/* Add your styles here */
</style>
