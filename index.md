---
layout: home
header:
  title: Oliver's personal website
  text: >
   Welcome to my personal website where you can learn something about me
  action: # action button is optional
    label: Find Out More
    url: '#about'



sections:
  - type: call-to-action.html
    section_id: about
    background_style: bg-primary
    title: A Quick Summary about Me
    text: I came to the US from China when I was 18 seeking a higher education. I have graduated from UCLA and currently pursuing a master degree in Business Analytics at LMU. I am a person with a wide range of interests and hobbies. And I have had a variety of experience and I worked on various projects. You can see some in more detail in this website. 


  - type: timeline.html
    section_id: timeline
    title: Education Timeline
    background_style: bg-dark text-primary
    last_image: assets/img/portfolio/thumbnails/blank.jpg
    actions:
      - image: assets/img/portfolio/thumbnails/rcc.jpg
        title: >+
          July 2017- May 2019
          Riverside City College
        text: >-
          Major: Business Administration 
          GPA: 4.00
      - image: assets/img/portfolio/thumbnails/ucla.jpg
        title: >+
          September 2019- June 2021
          UCLA (Undergrad)
        text: >-
          Major: Business Economics 
          GPA: 3.83
      - image: assets/img/portfolio/thumbnails/lmu.jpg
        title: >+
          September 2021- present
          LMU (Graduate)
        text: >-
          Major: Business Analytics 
          GPA: 4.00

  - type: services.html
    section_id: services
    #background_style: bg-info
    title: My Skills
    services:
      - title: Microsoft Office Suite
        text: Excel, PowerPoint, etc. 
      - title: Data Analysis
        text: R, Python, SQL
      - title: Data Visualization
        text: Tableau, ArcGIS
      - title: Video Editting
        text: Da Vinci Resolve

  - type: portfolio.html
    # this section has always ID 'portfolio'
    #section_id: portfolio
    #background_style: bg-dark
    projects:
      - title: Project 1
        text: This is a very short project description.
        # the images are located in:
        # img/portfolio/fullsize
        # img/portfolio/thumbnails
        icon: 1.jpg
        url: '#'
      - title: Project 2
        text: This is a very short project description.
        icon: 2.jpg
        url: '#'
      - title: Project 3
        text: This is a very short project description.
        icon: 3.jpg
        url: '#'
      - title: Project 4
        text: This is a very short project description.
        icon: 4.jpg
        url: '#'
      - title: Project 5
        text: This is a very short project description.
        icon: 5.jpg
        url: '#'
      - title: Project 6
        text: This is a very short project description.
        icon: 6.jpg
        url: '#'

  - type: aside.html
    section_id: aside
    title: Free Download at Start Bootstrap!
    actions:
      - title: Download Now!
        url: https://startbootstrap.com/themes/creative/
        class: btn-light

  - type: members.html
    section_id: members
    title: My Hobbies
    background_style: bg-info text-white
    members:
      - title: Traveling
        text: 4 road trips, 8 states, 9 National Parks
        image: assets/img/members/travel.jpg
        url: '#'
      - title: Photos and Videos
        text: photos and videos are the best ways to immortalize a moment
        image: assets/img/members/photo.jpg
        url: '#'
      - title: Music
        text: Drum, guitar, piano, flute
        image: assets/img/members/guitar.jpg
        url: '#'
      - title: Archery
        text: I have been practicing since middle school
        image: assets/img/members/archery.jpg
        url: '#'
       - title: Culinary
        text: cooking relaxes me
        image: assets/img/members/cook.jpg
        url: '#'
       - title: Gaming
        text: video game is the ultimate channel of story telling
        image: assets/img/members/game.jpg
        url: '#'

  - type: contact.html
    section_id: contacts
    title: Let's Get In Touch!
    text: >-
      Ready to start your next project with us? Give us a call or send us an email
      and we will get back to you as soon as possible!
    actions:
    - title: +1 (202) 555-014
      icon: fa-phone
    - title: E-Mail
      icon: fa-envelope
      url: mailto:contact@yourwebsite.com
    - title: Twitter
      icon: fa-twitter
      icon_type: fab
      url: '#'
    - title: Facebook
      icon: fa-facebook
      icon_type: fab
      url: '#'

---
