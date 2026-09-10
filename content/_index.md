---
isPage: true
draft: false
title: Accueil
description: Nouveau site de La Creuse

blocks:
  
  - type: cta
    heading:
      surtitle: Mes démarches
      title: Vos démarches en quelques clics
    ctas:
      - text: Accéder au portail
        url: https://mesdemarches.creuse.fr/
        blank: true
    ui:
      theme: light
      align: center

  - type: informations
    ui: 
      grid: container
      align: center
      column: 5
    heading:
      surtitle: Les infos pratiques
      title: Les services du Conseil départemental
    items:
      - title: Espace, famille, jeunesse
        text: Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quod.
        icon: users
        cta:
          url: /
          text: Accéder au service
      - title: Habitat, logement
        text: Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quod.
        icon: house
        cta:
          url: /
          text: Accéder au service
      - title: Insertion, emploi
        text: Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quod.
        icon: briefcase-business
        cta:
          url: /
          text: Accéder au service
      - title: Culture, patrimoine
        text: Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quod.
        icon: palette
        cta:
          url: /
          text: Accéder au service
      - title: Environnement
        text: Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quod.
        icon: leaf
        cta:
          url: /
          text: Accéder au service
      - title: Soutient aux territoires
        text: Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quod.
        icon: hand-heart
        cta:
          url: /
          text: Accéder au service
      - title: Autonomie
        text: Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quod.
        icon: person-standing
        cta:
          url: /
          text: Accéder au service
      - title: Éducation
        text: Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quod.
        icon: backpack
        cta:
          url: /
          text: Accéder au service
      - title: Routes
        text: Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quod.
        icon: road
        cta:
          url: /
          text: Accéder au service
      - title: Sport, loisirs de nature
        text: Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quod.
        icon: bike
        cta:
          url: /
          text: Accéder au service

  - type: video
    heading:
      surtitle: Destination Creuse
      title: La Creuse vous tente ?
    footing:
      ctas:
        - url: https://www.esprit-creuse.fr/
          text: Découvrir l’Esprit Creuse
          blank: true
    ui:
      align: center
      grid: large
      offset: center
      theme: accent
    video:
      controls: true
      autoplay: true
      mp4: /assets/videos/esprit-creuse.mp4
      background: true

  - type: latest
    section: posts
    heading:
      surtitle: À la une
      title: Les dernières actualités
    ui:
      theme: light
  
  - type: pushes
    ui:
      grid: full
    items:
      - surtitle: Solidarité
        title: Trouvez votre service social de proximité
        cta:
          text: Voir les coordonnées des UTAS de la Creuse
          url: /
        image:
          src: /images/uploads/snap-wander-cYUiJXcn-Ak-unsplash.jpg
        darken: true
        card: true

  - type: editorial
    title: « Avec nous dîtes… 23 »
    text: Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quod. Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quod.
    image:
      src: /images/uploads/snap-wander-cYUiJXcn-Ak-unsplash.jpg
    ctas:
      - text: En savoir plus
        url: /
    direction: ltr
    ui:
      grid: large
      offset: center

  - type: editorial
    title: "Le développement durable : un engagement pour aujourd’hui et pour demain"
    text: Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quod. Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quod.
    image:
      src: /images/uploads/snap-wander-cYUiJXcn-Ak-unsplash.jpg
    ctas:
      - text: En savoir plus
        url: /
    direction: rtl
    ui:
      grid: large
      offset: center

  - type: editorial
    title: La Creuse 100% fibré
    text: Le Département et les intercommunalités ont fait le choix d’investir pour une couverture à 100% de notre territoire par la fibre optique avec l’ambition de faciliter l’arrivée de nouveaux habitants, de nouveaux métiers et de nouveaux emplois, et donner à chacun l’accès aux services de demain.
    image:
      src: /images/uploads/snap-wander-cYUiJXcn-Ak-unsplash.jpg
    ctas:
      - text: En savoir plus
        url: /
    direction: ltr
    ui:
      grid: large
      offset: center

  - type: editorial
    title: Le magazine de la Creuse
    text: Le Département et les intercommunalités ont fait le choix d’investir pour une couverture à 100% de notre territoire par la fibre optique avec l’ambition de faciliter l’arrivée de nouveaux habitants, de nouveaux métiers et de nouveaux emplois, et donner à chacun l’accès aux services de demain.
    image:
      src: /images/uploads/snap-wander-cYUiJXcn-Ak-unsplash.jpg
    ctas:
      - text: En savoir plus
        url: /
    direction: ltr
    ui:
      theme: light
      grid: container

  - type: informations
    ui: 
      layout: grid
      grid: container
      align: center
      column: 4
      scrollsnap: md
    heading:
      surtitle: Les infos pratiques
      title: Les services du Conseil départemental
    items:
      - title: L’esprit Creuse
        text: Venez découvrir, entre amis ou en famille, les richesses de notre territoire.
        image:
          src: /images/uploads/logo-esprit-creuse.png
          isLogo: true
        cta:
          url: https://www.esprit-creuse.fr/
          text: Accéder au site
          blank: true
      - title: Job 23
        text: Vous cherchez un emploi, un stage ou une alternance ?
        image:
          src: /images/uploads/logo-job23.png
          isLogo: true
        cta:
          url: https://www.job23.fr/
          text: Accéder au site
          blank: true
      - title: Tourisme Creuse
        text: Organisez votre séjour en Creuse
        image:
          src: /images/uploads/logo-tourisme-creuse.png
          isLogo: true
        cta:
          url: https://www.tourisme-creuse.com/
          text: Accéder au site
          blank: true
      - title: Bibliothèque départementale de la Creuse
        text: Un réseau de 250 bibliothèques et points lecture à votre service
        image:
          src: /images/uploads/logo-biblio.png
          isLogo: true
        cta:
          url: https://biblio.creuse.fr/
          text: Accéder au site
          blank: true
      - title: Etang des Landes
        text: Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quod.
        image:
          src: /images/uploads/logo-edl.png
          isLogo: true
        cta:
          url: https://etang-des-landes.creuse.fr/
          text: Accéder au site
          blank: true
      - title: SDIS 23
        text: Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quod.
        image:
          src: /images/uploads/logo-sdis.jpg
          isLogo: true
        cta:
          url: https://www.sdis23.fr/
          text: Accéder au site
          blank: true
      - title: AAA 23
        text: Besoin d’un conseil, d’un appui technique ou d’une assistance à maitrise d’ouvrage ? 
        image:
          src: /images/uploads/logo-aaa23.png
          isLogo: true
        cta:
          url: https://www.aaa23.fr/
          text: Accéder au site
          blank: true
      - title: Cité International de la tapisserie
        text: Une collection, des savoir-faire et un écosystème art tissé au cœur d'un territoire créatif.
        image:
          src: /images/uploads/logo-cite.png
          isLogo: true
        cta:
          url: https://www.cite-tapisserie.fr/
          text: Accéder au site
          blank: true
---

