<template>
   <div class="nav-breadcrumb-wrap">
    <div class="container">
      <nav class="nav-breadcrumb">
        <a href="/">首页</a>
        <span>{{crumbs}}</span>
      </nav>
    </div>
  </div> 
</template>

<script>
export default {
    name: 'nav-crumbs',
    props:['crumbs']
}
</script>