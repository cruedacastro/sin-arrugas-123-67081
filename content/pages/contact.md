---
title: Contacto
sections:
  - type: hero_section
    title: Contacto
    subtitle: >-
      De acuerdo con la filosofía de la atención "Urgente" haremos lo necesario
      para agendarle el día que a UD le convenga.
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: >
      ### Precios


      Los mas competitivos del mercado


      ### Propósito


      Brindarle una atención rápida y efectiva con los mejores estándares de
      calidad


      ### Términos


      Los servicios ofrecidos incluyen valoración médica y control posterior
    content_align: left
    form_position: left
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nombre
        default_value: Su nombre
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Su correo electrónico
        is_required: true
      - input_type: textarea
        name: message
        label: Mensaje
        default_value: >-
          Escriba su mensaje, si desea que lo contactemos por teléfono deje su
          número
      - input_type: checkbox
        name: consent
        label: >-
          Al enviar este formulario acepto ser contactado para recibir mas
          información
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
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
