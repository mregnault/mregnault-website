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
  #email: mathilde.regnault@ling.uni-stuttgart.de
  #phone: 888 888 88 88
  address:
    street: Keplerstraße 17
    city: Stuttgart
    #region: CA
    postcode: '70174'
    country: Germany
    country_code: DE
  #coordinates:
  #  latitude: '37.4275'
  #  longitude: '-122.1697'
  #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  office_hours:
    - 'Wednesday 15:30 to 18:00'
  #appointment_url: 'https://calendly.com'
  contact_links:
    - icon: video
      icon_pack: fas
      name: My Webex Office
      link: 'https://unistuttgart.webex.com/meet/mathilde.regnault'

design:
  columns: '2'
---
