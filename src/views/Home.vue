<template>
  <div class="card">
    <div class="card-image">
      <figure class="image is-16by9">
        <img src="../assets/images/intro.jpg" alt="Home Image">
      </figure>
    </div>
    <div class="card-content">
      <div class="media">
        <div class="media-left">
          <figure class="image is-64x64">
            <img class="is-rounded" src="../assets/images/me.jpg" alt="My image">
          </figure>
        </div>
        <div class="media-content">
          <p class="title is-4">Bervianto Leo Pratama</p>
          <p class="subtitle is-6">@berviantoleo</p>
        </div>
      </div>
      <div class="content is-medium">
        <b-taglist>
          <b-tag rounded size="is-medium" type="is-primary">Web & Mobile Developer</b-tag>
          <b-tag rounded size="is-medium" type="is-info">Cyber Security Enthusiasts</b-tag>
          <b-tag rounded size="is-medium" type="is-success">Institut Teknologi Bandung</b-tag>
        </b-taglist>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component
export default class Home extends Vue {}
</script>
