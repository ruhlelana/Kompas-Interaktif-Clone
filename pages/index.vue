<template>
<div>
  <full-page ref="fullpage" :options="options" id="fullpage">
    <div class="section hero is-danger pemilu">
      <h1 class="title is-fullheight is-uppercase has-text-weight-bold">
				Pemilu Serentak 2019
      </h1>
		  <h2 class="subtitle is-uppercase">
				Sejarah Baru Pesta Demokrasi
      </h2>
      <h3 class="subtitle is-uppercase">
        lihat
      </h3>
    </div>
    <div class="section hero is-danger energi">
      <h1 class="title is-fullheight is-uppercase has-text-weight-bold">
        Mewujudkan energi berkeadilan
      </h1>
			<h2 class="subtitle is-uppercase">
        di bumi pertiwi
      </h2>
      <h3 class="subtitle is-uppercase">
        lihat
      </h3>
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
