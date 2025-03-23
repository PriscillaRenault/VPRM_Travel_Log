<script setup lang="ts">
//import
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
import { library } from '@fortawesome/fontawesome-svg-core'
import {
  faSquareYoutube,
  faSquareInstagram,
  faSquareFacebook,
} from '@fortawesome/free-brands-svg-icons'

library.add(faSquareYoutube, faSquareInstagram, faSquareFacebook)
</script>

<template>
  <h1>Les Boussoles baroudeuses</h1>
  <nav>
    <ul>
      <li>
        <a href="https://www.facebook.com/profile.php?id=100089986837748&locale=fr_FR">
          <font-awesome-icon :icon="['fab', 'square-facebook']" />
        </a>
      </li>
      <li>
        <a href="https://www.instagram.com/lesboussolesbaroudeuses?igsh=Z2NnaWpvaG1wODdr"
          ><font-awesome-icon :icon="['fab', 'square-instagram']"
        /></a>
      </li>
      <li>
        <a href="#"><font-awesome-icon :icon="['fab', 'square-youtube']" /></a>
      </li>
    </ul>
  </nav>
</template>
