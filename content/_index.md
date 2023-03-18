---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing


sections:
  - block: hero
    content:
      title: SATELLITE GEOSCIENCES LAB
      image:
        filename: '' # hero-academic.png (located assets/media/***)
      # cta:
        # label: '**Get Started**'
        # url: https://wowchemy.com/templates/
      # cta_alt:
        # label:  Ask a question
        # url: https://discord.gg/z8wNYzb
      # cta_note:
        # label:  >-
      text: |-
       <font size="5">  DEPT. EARTH SYSTEM SCIENCES YONSEI UNIVERSITY </font> <br />
       <font size="3">  연세대학교 위성지구과학 연구실 홈페이지에 방문하신 것을 환영합니다 </font>
        # <!--Custom spacing-->
        # <div class="mb-3"></div>
        # <!--GitHub Button JS-->
        # <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true


  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
       This is the webpage of the Satellite Geosciences Research Group at the Department of Earth System Sciences, Yonsei University. The group is led by Hahn Chul Jung, and the research that we do focuses on radar remote sensing, land information system, natural disaster monitoring, adn the study of large-schale hydrology. <br /><br />
       **The lab's doors are always open to PhD, MSc, and undergraduate students looking for research topics. Please feel free to visit me to learn more about possible research topics and programs.**
       
    design:
      columns: '2'


 

  - block: portfolio
    id: projects
    content:
      title: Research
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
#      buttons:
#        - name: All
#          tag: '*'
#        - name: Deep Learning
#          tag: Deep Learning
#        - name: Other
#          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false


  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
 #     text: |-
 #       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: hahnchul.jung@yonsei.ac.kr
      phone: +82-2-2123-2677
#      appointment_url: 'https://calendly.com'
      address:
        street: 50 Yonsei-ro
        city: Seodaemun-gu
        region: Seoul
        postcode: '03722'
        country: South Korea
        country_code: KR
      directions: Science Hall Rm. 645, College of Science, Yonsei University
#      office_hours:
#        - 'Monday 10:00 to 13:00'
#        - 'Wednesday 09:00 to 10:00'
#      contact_links:
#        - icon: twitter
#          icon_pack: fab
#          name: DM Me
#          link: 'https://twitter.com/Twitter'
#        - icon: skype
#          icon_pack: fab
#          name: Skype Me
#          link: 'skype:echo123?call'
#        - icon: video
#          icon_pack: fas
#          name: Zoom Me
#          link: 'https://zoom.com'
#      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
#      form:
#        provider: netlify
#        formspree:
#          id:
#        netlify:
#          # Enable CAPTCHA challenge to reduce spam?
#          captcha: false
    design:
      columns: '2'


---
