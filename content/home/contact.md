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
      captcha: true

  # Contact details (edit or remove options as required)
  email: murinko@demografia.hu, murinkolivia@gmail.com
  #phone: 888 888 88 88
  address:
    street: Buday László u. 1-3
    city: Budapest
    postcode: '1024'
    country: Hungary
    country_code: HU
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: Room 608
  office_hours:
    - 'Monday 10:00 to 13:00'
    - 'Wednesday 09:00 to 10:00'
  #appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/LMurinko'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'
design:
  columns: '2'
---
