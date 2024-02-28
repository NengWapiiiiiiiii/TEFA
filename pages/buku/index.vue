<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
        <h2 class="text-center my-4"></h2>
        <div class="my-3">
          <input type="search" class="form-control rounded-5" placeholder="MAU BACA APA HARI INI?">
        </div>
        <div class="my-3 text-muted"></div>
        <div class="row">
          <div class="col-lg-10">
            <div class="card mb-1">
              <div class="card-body">
                <img src="~/assets/img/buku1.jpg" class="cover" alt="cover 1">
              </div>
            </div>
          </div>
          <div class="col-lg-4">
            <div class="card mb-10">
              <div class="card-body">
                <img src="~/assets/img/BUKU2.png" class="cover" alt="cover 2">
              </div> 
            </div>
          </div>
          <div class="col-lg-4">
            <div class="card mb-10">
              <div class="card-body">
                <img src="~/assets/img/BUKU3.jpg" class="cover" alt="cover 3">
              </div> 
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<style scoped>
.card-body {
  width: 100%;
  height: 20cm;
  padding: 0;

}
.cover {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: 0 30;
}
</style>