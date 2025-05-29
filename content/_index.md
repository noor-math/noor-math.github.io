---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing
sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Lecturer
          company: Kishoreganj University (KiU)
          company_url: 'https://math.kiu.ac.bd/viewprofile/4'
          company_logo: kiu
          location: Kishoreganj, Bangladesh
          date_start: '2023-10-18'
          date_end: ''
        - title: Lecturer
          company: Dhaka Commerce College (DCC)
          company_url: 'https://www.dcc.edu.bd/'
          company_logo: dcc
          location: Dhaka, Bangladesh
          date_start: '2022-03-01'
          date_end: '2023-10-14'
        - title: Lecturer
          company: Primeasia University (PAU) 
          company_url: 'https://www.primeasia.edu.bd/'
          company_logo: pau
          location: Dhaka, Bangladesh
          date_start: '2019-05-21'
          date_end: '2019-02-05'
        - title: Lecturer
          company: German University Bangladesh (GUB) 
          company_url: 'https://www.gub.edu.bd/'
          company_logo: gub
          location: Gazipur, Bangladesh
          date_start: '2019-02-20'
          date_end: '2019-05-20'

    design:
      columns: '2'
  
  - block: accomplishments
    id: accomplishments
    content:
      title: 'Achievements, Awards, and Services'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_end: '2025-01-31'
          date_start: '2012-01-15'
          description: |2-

              <span style="font-size: 1.5em;">**Scholarships:**</span>
              * Awarded to facilitate the M.Sc. dissertation from the Ministry of Science and Technology of Bangladesh.
              * Received university yearly scholarship for outstanding results.
              * Received scholarship for achieving the top position in the undergraduate entrance exam.
              
              <span style="font-size: 1.5em;">**Academic Contributions:**</span> <br>
              <span style="font-size: 1.5em;">Chief Advisor</span>
              * Pie Club (2024-Present), Department of Mathematics, Bangabandhu Sheikh Mujibur Rahman University, Kishoreganj, Bangladesh.

              <span style="font-size: 1.5em;">Mentor</span>
              * Math Olympiad Team (2020-2021), Department of Basic Science, Primeasia University, Dhaka, Bangladesh.

              <span style="font-size: 1.5em;">Executive Member</span>
              * Mathematics Club (2013-2017), Department of Mathematics, Comilla University, Cumilla, Bangladesh.
 
              <span style="font-size: 1.5em;">Journal Reviewer</span>
              * <strong>Heliyon</strong>: Served as a reviewer for Heliyon, Elsevier journal.
              * <strong>International Journal of Modern Physics B</strong>: Served as a reviewer for International Journal of Modern Physics B, World Scientific.
              * <strong>Physics Open</strong>: Served as a reviewer for Current Research in Physics Open, Elsevier journal.

          url: ''

  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: citation
  
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      count: 5
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: true
        exclude_future: false
        exclude_past: false
        publication_type: ""
      offset: 0
      order: desc
    design:
      columns: '2'

  - block: contact
    id: contact
    content:
      title: Contact
      email: nooralam.cou@gmail.com
      phone: +880 1680-979489
      contact_links:
        - icon: facebook
          icon_pack: fab
          name: Noor Alam
          link: 'https://web.facebook.com/noorcou06'
    design:
      columns: '2'
---
