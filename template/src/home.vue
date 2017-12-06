<template>
    <div id="app">
        <f7-views navbar-through=''>
            <f7-view main='' url='/' :dynamic-navbar='true'>
                <f7-navbar>
                    <f7-nav-left></f7-nav-left>
                    <f7-nav-center sliding=''>Home</f7-nav-center>
                    <f7-nav-right></f7-nav-right>
                </f7-navbar>
                <f7-pages id="pages">
                    <f7-page class="navbar-fixed">
                        <f7-list>
                            <f7-list-item title='To page 1' link='/page1/'></f7-list-item>
                            <f7-list-item title='To page 2' link='/page2/'></f7-list-item>
                        </f7-list>
                    </f7-page>
                </f7-pages>
            </f7-view>
        </f7-views>
    </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App with Framework7 and Webpack'
    }
  }
}
</script>

<style>
  /* Add your styles here */
</style>
