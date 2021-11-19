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
        subtitle: Dinámicas y Estáticas
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
        image_alt: Lineas expresión
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
          - label: Preguntas Frecuentes
            url: /faq
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
          - label: Preguntas Frecuentes
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
    subtitle: Que dicen mis pacientes
    grid_items:
      - content: >
          De parecer enfadado todo el día a parecer feliz todo el día, una
          terapia !


          **Marlon Pérez,** 
        image: /images/55963784_2301861263467290_240080648847491072_n.jpg
        image_position: left
        image_width: twenty-five
      - content: |
          Los procedimientos tambien convienen a los jóvenes, hay que prevenir

          **Juan Pablo Díaz,** *Actor*

          \*\*
        image: /images/55944304_311185426182088_1237199736595808256_n.jpg
        image_position: left
        image_width: twenty-five
      - content: >
          Muy recomendable el Endoret facial, efecto natural. nada ajeno y un
          resultado muy durable


          **Eleanor Carr,** Empresaria
        image: /images/257784998_1074683043296763_6570583737317872938_n.jpg
        image_position: left
        image_width: twenty-five
      - content: |
          Los hilos tienen un resultado muy deseable, muy recomendables

          **Gloria Gómez,** Asesora
        image: /images/244452206_4743987678986879_1378863458279036660_n.jpg
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
    content: |
      # Contacteme

      Si desea déjenos sus datos y pronto le estaremos contactando
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
        default_value: Su nombre
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Su email
        is_required: true
      - input_type: tel
        name: Opcional teléfono
        label: Teléfono
        default_value: Teléfono
        options: []
        is_required: false
      - input_type: textarea
        name: message
        label: Message
        default_value: >-
          Escriba su mensaje y si desea que le llamemos puede dejar su número y
          le contactamos
      - input_type: checkbox
        name: consent
        label: >-
          Al diligenciar este formulario acepto que me contacten para recibir
          mas información
        is_required: true
    submit_label: Enviar
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
seo:
  title: Medicina Estética "Urgente"
  description: >-
    Un servicio personalizado para atender de manera prioritaria a personas que
    quieren mejorar su estética en Bogotá, Toxina, Hilos, Ac. Hialurónico,
    Endoret
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Medicina Estética
      keyName: property
    - name: 'og:description'
      value: >-
        Procedimientos para mejorar la calidad de la piel, reducir "arrugas",
        evitar o reducir la flacidez de la piel.
      keyName: property
    - name: 'og:image'
      value: /images/BioPlazmar-02.png
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
