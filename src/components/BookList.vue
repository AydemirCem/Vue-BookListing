<template>
      <div id='book-list'>
          <h1>{{title}}</h1>
      </div>
</template>
<style>
h1,h2 {font-weight:normal ;}
</style>
<script>
        new Vue({
          el: '#book-list',
          data: {
              title: 'All books'
          }
       })
</script>