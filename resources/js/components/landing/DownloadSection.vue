<template>
  <section id="download">
    <v-container fluid>
      <v-row align="center" justify="center">
        <v-col cols="10">
          <v-row align="center" justify="center">
            <v-col sm="4" class="hidden-xs-only">
              <v-img src="/assets/img/ill2.svg" class="d-block ml-auto mr-auto" max-width="350px" />
            </v-col>
            <v-col cols="12" sm="8" class="white--text text-left">
              <h1 class="font-weight-light display-2 mb-2">KUMPULAN ARTIKEL</h1>
              <h1 class="font-weight-light">
                Knowledge Management (Manajemen Pengetahuan) yang mengumpulkan berbagai sumber informasi dari segala aspek yang mendukug pelaksanaan organisasi, pengembangan diri, serta pelayanan publik yang ciamik!
              </h1>
              <v-btn rounded outlined to="/list-artikel" target="_blank" large color="white" class="my-4">
                <v-icon class="mr-2">
                  mdi-book-open-variant
                </v-icon>
                Kumpulan Artikel
              </v-btn>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<style scoped>
#download {
  background-image: url("/assets/img/bgDownload.jpg");
  background-attachment: fixed;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  height: 500px;
}

#download .container,
#download .row {
  height: 100%;
}
</style>