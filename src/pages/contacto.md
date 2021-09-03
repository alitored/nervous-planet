---
title: Contactar
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
    submit_label: Enviar mensaje
    subtitle: >-
      Envianos un mensaje con tus preguntas o solicitudes y responderemos en
      breve. Si no querés esperar 1157577039
  - title: Comunicate ahora directamente
    subtitle: '1157577039'
    actions:
      - label: Hablemos x Wathsapp
        url: "\uFEFF\uFEFFhttps://api.whatsapp.com/send?phone=541157577039"
        style: primary
        has_icon: true
        icon: instagram
        icon_position: left
        new_window: true
        no_follow: false
        type: action
      - label: '1157577039'
        url: '#'
        style: link
        has_icon: false
        icon: arrow-left
        icon_position: left
        new_window: false
        no_follow: false
        type: action
    type: section_cta
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
