---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      username: admin
  - block: accomplishments
    content:
      title: 'Honors and Awards'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://ccpc.io/
          date_end: ''
          date_start: '2022-06-01'
          description: ''
          organization: ICPC
          organization_url: https://ccpc.io/
          title: Ag Medal • China Collegiate Programming Contest, Guangdong Province
        - certificate_url: https://icpc.global
          date_end: ''
          date_start: '2022-11-01'
          description: ''
          organization: ICPC
          organization_url: https://icpc.global
          title: Cu Medal • International Collegiate Programming Contest, Xi’an Site
        - certificate_url: https://ccpc.io/
          date_end: ''
          date_start: '2021-11-01'
          description: ''
          organization: CCPC
          organization_url: https://ccpc.io/
          title: Cu Medal • China Collegiate Programming Contest, Guangzhou Site
        - certificate_url: https://gplt.patest.cn/
          date_end: ''
          date_start: '2021-11-01'
          description: ''
          organization: GPLT
          organization_url: https://gplt.patest.cn/
          title: Individual National Second Prize, Team Silver Prize • GPLT
        - certificate_url: https://dasai.lanqiao.cn/
          date_end: ''
          date_start: '2021-06-01'
          description: ''
          organization: LanQiao
          organization_url: https://dasai.lanqiao.cn/
          title: Individual National Second Prize • Professional Software Engineering, Lan Qiao Cup
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      email: work@oi-liu.com
      phone: (+86) 159-7509-1868
      autolink: true
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          captcha: false
    design:
      columns: '2'
---
