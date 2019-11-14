<template>
  <section
    id="welcome"
    class="hide-overflow"
  >
    <v-layout>
      <v-flex
        hidden-sm-and-down
        md6
      >
        <v-img
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQW3pxRFM7hS_BNBl1Ryk9CHANz9iXgl3IekMKmxpFrdnLVHs0-"
          height="100vh"
          width="100vh"
        />
      </v-flex>

      <v-flex
        xs12
        md6
        align-content-space-between
        layout
        :pa-5="$vuetify.breakpoint.smAndDown"
        wrap
      >
        <base-bubble-1
          style="transform: rotate(180deg) translateY(25%)"
        />

        <v-layout
          align-center
          justify-center
        >
          <v-flex
            xs10
            md6
          >
            <base-heading><h1>Kejadian 1</h1></base-heading>
            <br>
            <base-text>
            <p style="text-align:justify">
             Pada mulanya Allah menciptakan langit dan bumi.
1:2	Bumi belum berbentuk dan kosong; gelap gulita menutupi samudera raya, dan Roh Allah melayang-layang di atas permukaan air.
1:3	Berfirmanlah Allah: "Jadilah terang." Lalu terang itu jadi.
1:4	Allah melihat bahwa terang itu baik, lalu dipisahkan-Nyalah terang itu dari gelap.
1:5	Dan Allah menamai terang itu siang, dan gelap itu malam. Jadilah petang dan jadilah pagi, itulah hari pertama.

            </p>
            </base-text>
            <base-btn class="mt-3">
                <v-btn rounded color="primary" dark router to="/user">Masukin</v-btn>
            </base-btn>
          </v-flex>
        </v-layout>

        <base-bubble-2
          style="transform: rotate(180deg) translate(-200px, -15%)"
        />
      </v-flex>
    </v-layout>
  </section>
</template>