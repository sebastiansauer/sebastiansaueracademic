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
  email: sebastiansauer1@gmail.com
  # phone: 888 888 88 88
  address:
    street: Residenzstr. 10
    city: Ansbach
    region: Bavaria
    postcode: '91522'
    country: Germany
    country_code: DE
  # coordinates:
  #   latitude: '37.4275'
  #   longitude: '-122.1697'
  directions: Drive to Retti Campus (Rettistr.) and park there
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/sauer_sebastian'
 

design:
  columns: '2'
---
