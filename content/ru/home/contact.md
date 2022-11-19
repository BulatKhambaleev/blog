---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: bambotvanpersy@bk.ru
  phone: + 7 977 506 05 09
  address:
    street: Советская
    city: село Уральск
    region: Башкортостан
    postcode: '43475'
    country: Российская Федерация
    country_code: РФ
  contact_links:
    - icon: square
      icon_pack: fab
      name: Github репозиторий
      link: 'https://github.com/BulatKhambaleev'
    - icon: square
      icon_pack: fas
      name: Elibrary
      link: 'https://elibrary.ru/'
    - icon: square
      icon_pack: fas
      name: Scholar Google
      link: 'https://scholar.google.com/'
    - icon: square
      icon_pack: fas
      name: Orcid
      link: 'https://orcid.org/'
    - icon: square
      icon_pack: fas
      name: Mendeley
      link: 'https://www.mendeley.com/'
    - icon: square
      icon_pack: fas
      name: Researchgate
      link: 'https://www.researchgate.net/'



design:
  columns: '2'
---
