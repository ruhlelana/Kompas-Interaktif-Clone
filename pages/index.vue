<template>
<div>
    <full-page ref="fullpage" :options="options" id="fullpage">
    <div class="section pemilu">
      First section ...
    </div>
    <div class="section energi">
      Second section ...
    </div>
  </full-page>
</div>
</template>

<script>
</script>

<style>
.pemilu {
 background-image: url(/img/pemilu.jpg);
 background-position: center center;
 background-repeat: no-repeat;
 background-size: cover;
}
.energi {
 background-image: url(/img/energi.jpg);
 background-position: center center;
 background-repeat: no-repeat;
 background-size: cover;
}
</style>
