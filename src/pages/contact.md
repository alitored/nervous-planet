---
title: Contact
sections:
  - section_id: contact
    type: section_contact
    background: gray
    title: Dejanos un mensaje
    form_id: contactForm
    form_fields:
      - input_type: text
        name: name
        label: Nombre
        is_required: true
      - input_type: email
        name: email
        label: Email
        is_required: true
      - input_type: select
        name: subject
        label: Asunto
        default_value: Seleccionar
        options:
          - Consultar por sitio web
          - Consultar formas de pago
          - Solicitar soporte
      - input_type: textarea
        name: message
        label: Mensaje
      - input_type: checkbox
        name: consent
        label: Entiendo que me enviarán información a mi Email.
        is_required: true
    submit_label: Send Message
    subtitle: >-
      Envianos un mensaje con tus preguntas o solicitudes y responderemos en
      breve.
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
      value: summary_large_image
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
template: landing
---
