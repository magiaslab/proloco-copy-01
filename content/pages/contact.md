---
title: Contact
sections:
  - section_id: contact
    type: section_contact
    background: gray
    title: Contatti
    content: >
      Utilizza il form qui sotto per inviarci un messaggio al quale risponderemo
      al più presto
    form_id: contactForm
    form_fields:
      - input_type: text
        name: name
        label: Nome e Cognome
        is_required: true
      - input_type: email
        name: email
        label: Email
        is_required: true
      - input_type: select
        name: Oggetto
        label: Subject
        default_value: Scegli
        options:
          - Informazioni su iscrizione
          - Info su eventi
          - Altro
      - input_type: textarea
        name: message
        label: Messaggio
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
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
      value: summary_large_image
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: landing
---
