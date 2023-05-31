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
  - block: experience
    id: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: Vulnerability Identification Research Asistant
          company: 'Advisor: Lec. Yinhao Xiao at Guangdong University of Finance and Economics'
          date_start: '2022-03-01'
          date_end: ''
          description: |2-
              Researched automated vulnerability identification schemes. In the research group I was mainly responsible for replication and comparison of similar papers as well as writing processing programs to extract data such as AST, CFG, and PDG from source code according to the needs of the group.

              Now one paper accepted by Future Generation Computer Systems, and one is under review: 

              * (Accepted) DeepVulSeeker: A Novel Vulnerability Identification Framework via Code Graph Structure
              and Pre-training Mechanism
              * (Under Review) JFinder: A Novel Architecture for Java Vulnerability Identification Based Quad Self-
              Attention and Pre-training Mechanism
  - block: accomplishments
    id: awards
    content:
      title: 'Honors and Awards'
      subtitle:
      date_format: Jan 2006
      items:
        - date_end: ''
          date_start: '2022-06-01'
          description: ''
          organization: ICPC
          organization_url: https://ccpc.io/
          title: Ag Medal • China Collegiate Programming Contest, Guangdong Province
        - date_end: ''
          date_start: '2022-11-01'
          description: '<img data-src="/media/ICPC.png" alt="Coursera" style="height: 60px;" class="lazyload">'
          organization: ICPC
          organization_url: https://icpc.global
          title: Cu Medal • International Collegiate Programming Contest, Xi’an Site
        - date_end: ''
          date_start: '2021-11-01'
          description: ''
          organization: CCPC
          organization_url: https://ccpc.io/
          title: Cu Medal • China Collegiate Programming Contest, Guangzhou Site
        - date_end: ''
          date_start: '2021-11-01'
          description: ''
          organization: GPLT
          organization_url: https://gplt.patest.cn/
          title: Individual National Second Prize, Team Silver Prize • GPLT
        - date_end: ''
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
