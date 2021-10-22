---
title: Contact
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: |
      Para contacto, por favor rellena esta formulario
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: nombre
        label: Nombre y apellido
        default_value: Tu nombre y apellido
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Introduce tu dirección de correo electrónico
        is_required: true
      - input_type: select
        name: subject
        label: Asunto
        default_value: Please select
        options:
          - Solicitar una consultoría de transformación digital
          - Me gustaría tener una página web
          - Deseo un sistema web
          - Otro
      - input_type: textarea
        name: message
        label: Mensaje
        default_value: Redacta tu mensaje aquí
      - input_type: checkbox
        name: consent
        label: >-
          Entiendo que este formulario guardará mis datos para luego ser
          contactado.
    submit_label: Send Message
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
