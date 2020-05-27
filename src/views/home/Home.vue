<template>
    <div id="home">
        <nav-bar class="nav-bar">
            <div slot="center">购物街</div>
        </nav-bar>
    </div>
    
</template>

<script>
    import NavBar from 'components/common/navbar/NavBar'
    export default {
        name: "Home",
        components:{
            NavBar
        }
    }
</script>

<style scoped>
  #home {
    /*position: relative;*/
    height: 100vh;
  }
  .nav-bar {
    background-color: var(--color-tint);
    font-weight: 700;
    color: #fff;
  }

  .content {
    position: absolute;
    top: 44px;
    bottom: 49px;
    left: 0;
    right: 0;
  }

  .fixed {
    position: fixed;
    top: 44px;
    left: 0;
    right: 0;
  }

  .back-top {
    position: fixed;
    right: 10px;
    bottom: 60px;
  }
</style>
