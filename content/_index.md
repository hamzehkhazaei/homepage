---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      username: admin
      title: Biography
    design:
      columns: '2'

  - block: experience
    id: experience
    content:
      title: Experience
      subtitle:
      date_format: Jan 2006
      items:
        - title: Associate Professor
          company: York University
          company_url: 'https://www.yorku.ca'
          location: Toronto, Ontario
          date_start: '2022-07-01'
          date_end: ''
          description: Department of Electrical Engineering and Computer Science.
        - title: Assistant Professor
          company: York University
          company_url: 'https://www.yorku.ca'
          location: Toronto, Ontario
          date_start: '2019-09-01'
          date_end: '2022-07-01'
          description: Department of Electrical Engineering and Computer Science.
        - title: Assistant Professor
          company: University of Alberta
          company_url: 'https://www.ualberta.ca'
          location: Edmonton, Alberta
          date_start: '2017-09-01'
          date_end: '2019-08-31'
          description: Department of Electrical and Computer Engineering.
        - title: Research Associate
          company: University of Toronto
          company_url: 'https://www.utoronto.ca'
          location: Toronto, Ontario
          date_start: '2016-09-01'
          date_end: '2017-08-31'
          description: Department of Electrical and Computer Engineering.
        - title: Research Scientist
          company: IBM
          company_url: 'https://www.ibm.com'
          location: Markham, Ontario
          date_start: '2013-09-01'
          date_end: '2016-08-31'
          description: Canada Research and Development Center.
    design:
      columns: '2'

  - block: portfolio
    id: teaching
    content:
      title: Teaching
      subtitle:
      page_type: teaching
      default_button_index: 0
      buttons:
        - name: All
          tag: '*'
        - name: Grad
          tag: grad
        - name: Undergrad
          tag: undergrad
    design:
      columns: '2'
      view: card
      flip_alt_rows: false

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text:
      autolink: false
      email: hkh@yorku.ca
      phone: (416) 736-2100 x 44233
      address:
        street: 2002 Lassonde Building, 4700 Keele Street
        city: Toronto
        region: ON
        postcode: 'M3J 1P3'
        country: Canada
        country_code: CA
      coordinates:
        latitude: '43.773991'
        longitude: '-79.505050'
      directions:
      office_hours:
      appointment_url:
      form:
        provider: ''
        netlify:
          captcha: true
    design:
      columns: '2'
---
