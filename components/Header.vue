<template lang="pug">
  section.hero.is-success
    .hero-head
      header.nav
        .container
          .nav-left
            .nav-item
              strong 📻 Itzik Music
          .nav-right.nav-menu
            router-link.nav-item(to="search") Buscar
            router-link.nav-item(to="about") Nosotros

    .hero-body
      .container.has-text-centered
        h1.title Itzik Music
        h2.subtitle Canciones que estan Vue-nisimas!
</template>
