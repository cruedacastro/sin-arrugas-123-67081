---
title: Home
sections:
  - type: hero_section
    title: 'Hola, te presentamos el servicio de medicina estética de "urgencia"'
    subtitle: >-
      Cualquier día nos vemos al espejo y sorpresa! nos vemos anticipadamente
      envejecidos ... Calma, hoy tenemos recursos para devolver el aspecto jóven
      al rostro.
    actions:
      - label: Contacto
        url: /contact
        style: primary
    image: /images/IMG_2104.JPG
    image_alt: A smiling woman
    media_position: right
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
  - type: grid_section
    title: Tecnologías usadas
    subtitle: Dispositivos y biomateriales de última generación
    align: center
    grid_items:
      - image: /images/mesoestetic.png
        image_alt: Logo 1
        image_align: center
      - image: /images/logo.png
        image_alt: Logo 2
        image_align: center
      - image: /images/dermalogica.png
        image_alt: Logo 3
        image_align: center
      - image: /images/vlift.png
        image_alt: Logo 4
        image_align: center
      - image: /images/hialuronico.png
        image_alt: Logo 5
        image_align: center
      - image_alt: Logo 6
        image_align: center
        image: /images/simildiet.png
      - image: /images/neuronox.png
        image_alt: Logo 7
        image_align: center
      - image: /images/endoret logo.png
        image_alt: Logo 8
        image_align: center
    grid_cols: four
    grid_gap_horiz: medium
    grid_gap_vert: medium
  - type: features_section
    title: Servicios
    subtitle: Procedimientos Médicos
    features:
      - title: Eliminar líneas de expresión
        subtitle: 'Dinámicas, Estáticas'
        content: >
          Con el uso de toxina botulínica controlamos expresiones no deseadas
          que reflejan enojo o simplemente nos hacen lucir viejos


          Con Biomateriales avanzados ademas recuperamos la calidad de la piel y
          corregimos inesteticismos no deseados
        actions:
          - label: Preguntas frecuentes
            url: /faq
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: /images/linea timpo.gif
        image_alt: Feature 1 illustration
        media_position: right
        media_width: sixty
        align: right
      - title: Bio estimulación con factor de crecimiento
        subtitle: Medicina regenerativa aplicada
        content: >
          Endoret® es tecnología para la obtención de factores de crecimiento,
          aplicados en la dermis promueven la revitalización cutánea y en
          general estimula el tejido para recuperar la función, tiene
          aplicaciones en Estética, ortopedia, odontología y en general donde se
          requiera rehabilitar un tejido
        actions:
          - label: Learn More
            url: /about
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image_alt: Feature 2 illustration
        media_position: right
        media_width: sixty
        video_embed_html: >-
          <iframe width="560" height="315"
          src="https://www.youtube.com/embed/FnDxu5fiqNQ" title="YouTube video
          player" frameborder="0" allow="accelerometer; autoplay;
          clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen></iframe>
      - title: Control de la flacidez cutánea con Hilos PDO
        subtitle: Hilos de avanzada tecnología reabsorbibles
        content: >
          Redensificar la dérmis es un procedimiento altamente efectivo en el
          control de la flacidez cutánea, aplicables en cualquier area corporal
          que se requiera, en el rostro soon ideales para el control de la
          flacidez del tercio inferior.
        actions:
          - label: See Past Work
            url: /faq
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/feature-3.svg
        image_alt: Feature 3 illustration
        media_position: right
        media_width: sixty
        video_embed_html: >-
          <iframe width="560" height="315"
          src="https://www.youtube.com/embed/WmaCG4lfEf0?controls=0&amp;start=20"
          title="YouTube video player" frameborder="0" allow="accelerometer;
          autoplay; clipboard-write; encrypted-media; gyroscope;
          picture-in-picture" allowfullscreen></iframe>
    feature_padding_vert: large
    align: center
    background_color: none
  - type: grid_section
    title: Testimonios
    subtitle: What My Clients Say
    grid_items:
      - content: >
          De parecer enfadado todo el dia a parecer feliz todo el dia, un
          alivio!


          **Hanson Deck,** *App Developer, Studio*
        image: images/hanson-deck.png
        image_position: left
        image_width: twenty-five
      - content: >-
          Alyvia really understands who our customers are and what tone of voice
          to use when communicating with them.


          **Miles Tone,** *CEO, Studio*
        image: images/miles-tone.png
        image_position: left
        image_width: twenty-five
      - content: >-
          Working with Alyvia was great because she was well versed in all of
          our tools and applications, and was able to manage our store and
          campaigns without any technical glitches.


          **Eleanor Carr,** *CTO, eCommerce Business*
        image: images/eleanor-carr.png
        image_position: left
        image_width: twenty-five
      - content: >-
          I love it when a content writer can really wordsmith and create copy
          that suits the design intention and style!


          **Gordon Norman,** *Web Designer, Local Business*
        image: images/gordon-norman.png
        image_position: left
        image_width: twenty-five
    grid_cols: two
    grid_gap_horiz: medium
    grid_gap_vert: large
    align: center
    background_color: secondary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 12
  - type: form_section
    content: >-
      ## Let's talk


      If you would like more information about my services and pricing, please
      contact me using the form below.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
seo:
  title: Stackbit Personal Theme
  description: The preview of the Personal theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Personal Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Personal theme
      keyName: property
    - name: 'og:image'
      value: images/personal-preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Personal Theme
    - name: 'twitter:description'
      value: The preview of the Personal theme
    - name: 'twitter:image'
      value: images/personal-preview.png
      relativeUrl: true
layout: advanced
---
