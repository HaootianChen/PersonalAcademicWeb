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
  email: hc19@illinois.edu
  address:
    street:  258 Coordinated Science Lab, 1308 W Main St
    city: Urbana
    region: IL
    postcode: '61801'
    country: United States
    country_code: US


design:
  columns: '2'
---
