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
  email: saifeddinenouma@usf.edu
  phone:  (+1) 813-859-9830
  address:
    street: 3720 Spectrum Blvd, IDR 400
    city: Tampa
    region: FL
    postcode: '33612'
    country: United States
    country_code: US
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  # office_hours:
  #   - 'Monday 08:00 17:00'
  #   - 'Tuesday 08:00 17:00'
  #   - 'Wednesday 08:00 17:00'
  #   - 'Thursday 08:00 17:00'
  #   - 'Friday 08:00 17:00'
  # appointment_url: 'https://calendly.com'
  # contact_links:
  #   - icon: twitter
  #     icon_pack: fab
  #     name: saif nouma
  #     link: 'https://twitter.com/saifnouma1'
    # - icon: 
    #   icon_pack: fas
    #   name: Saif Nouma
    #   link: 'https://www.linkedin.com/in/saifnouma/'

design:
  columns: '2'
---
