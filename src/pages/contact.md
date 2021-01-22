---
title: Contact
sections:
  - section_id: contact
    type: section_contact
    background: gray
    title: DEVIS GRATUIT & INFORMATIONS
    content: >
      Complétez le formulaire de contact, un dératiseur expérimenté prendra
      contact avec vous très rapidement.
    form_id: contactForm
    form_fields:
      - input_type: text
        name: name
        label: Votre Nom
        is_required: true
      - input_type: text
        name: lorem-ipsum
        label: Votre Telephone
        default_value: ''
        options: []
        is_required: false
        type: form_field
      - input_type: email
        name: email
        label: Votre Email
        is_required: true
      - input_type: select
        name: subject
        label: Sujet
        default_value: Please select
        options:
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: Message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
template: landing
---
