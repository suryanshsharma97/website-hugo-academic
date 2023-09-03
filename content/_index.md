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
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: R
          description: 90%
          icon: r-project
          icon_pack: fab
        - name: Statistics
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: Photography
          description: 10%
          icon: camera-retro
          icon_pack: fas
  - block: experience
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
        - title: CEO
          company: GenCoin
          company_url: ''
          company_logo: org-gc
          location: California
          date_start: '2021-01-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Analysing
              * Modelling
              * Deploying
        - title: Professor of Semiconductor Physics
          company: University X
          company_url: ''
          company_logo: org-x
          location: California
          date_start: '2016-01-01'
          date_end: '2020-12-31'
          description: Taught electronic engineering and researched semiconductor physics.
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Introduction to TensorFlow for Artificial Intelligence, Machine Learning, and Deep Learning
          certificate_url: https://www.coursera.org/account/accomplishments/certificate/NFHUZ2RRDSH8
          date_end: ''
          date_start: '2020-12-15'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          url: ''
        - title: 'Python(Basic)' 
          certificate_url: https://www.hackerrank.com/certificates/cf16d810f604
          date_end: ''
          date_start: '2020-09-05'
          description: ''
          organization: HackerRank
          organization_url: https://www.hackerrank.com
          url: ''
        - title: 'Data@ANZ Virtual Experience Program Partcipant' 
          certificate_url: https://insidesherpa.s3.amazonaws.com/completion-certificates/ANZ/ZLJCsrpkHo9pZBJNY_ANZ_iNzaCFhN8cR4pMJsu_completion_certificate.pdf
          date_end: ''
          date_start: '2020-07-02'
          description: ''
          organization: ANZ
          organization_url: https://www.anz.com.au
          url: ''
        - title: 'Convolutional Neural Networks'
          certificate_url: https://www.coursera.org/account/accomplishments/verify/4BCTZUP7DXMV
          date_end: ''
          date_start: '2018-08-01'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          url: ''
        - title: 'Deep Learning Specialization'
          certificate_url: https://www.coursera.org/account/accomplishments/specialization/certificate/RRBDYVPR6R2R
          date_end: ''
          date_start: '2018-08-01'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          url: ''
        - title: 'Sequence Models'
          certificate_url: https://www.coursera.org/account/accomplishments/certificate/5RMQ89NED9MQ
          date_end: ''
          date_start: '2018-08-01'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          url: ''
        - title: 'Improving Deep Neural Networks: Hyperparameter tuning, Regularization and Optimization' 
          certificate_url: https://www.coursera.org/account/accomplishments/verify/4BZ4RNPALK46
          date_end: ''
          date_start: '2018-08-01'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          url: ''
        - title: 'Neural Networks and Deep Learning' 
          certificate_url: https://www.coursera.org/account/accomplishments/verify/FKFA3SS8XEJC
          date_end: ''
          date_start: '2018-07-15'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          url: ''
        # - title: 'Structuring Machine Learning Projects'
        #   certificate_url: https://www.coursera.org/account/accomplishments/verify/PYMLJ5UNC57W
        #   date_end: ''
        #   date_start: '2018-07-01'
        #   description: ''
        #   organization: Coursera
        #   organization_url: https://www.coursera.org
        #   url: ''
        # - title: 'Machine Learning A-Z™: Hands-On Python & R In Data Science' 
        #   certificate_url: https://www.udemy.com/certificate/UC-UL1VD3YU/
        #   date_end: ''
        #   date_start: '2017-09-20'
        #   description: ''
        #   organization: Udemy
        #   organization_url: https://www.udemy.com
        #   url: ''
        # - title: 'Deep Learning A-Z™: Hands-On Artificial Neural Networks' 
        #   certificate_url: https://www.udemy.com/certificate/UC-VLDUTUL2/
        #   date_end: ''
        #   date_start: '2017-09-12'
        #   description: ''
        #   organization: Udemy
        #   organization_url: https://www.udemy.com
        #   url: ''
        # - title: 'Complete Python Bootcamp: Go from zero to hero in Python 3'
        #   certificate_url: https://www.udemy.com/certificate/UC-S9U636ET/
        #   date_end: ''
        #   date_start: '2017-08-15'
        #   description: ''
        #   organization: Udemy
        #   organization_url: https://www.udemy.com
        #   url: ''
        # - title: 'Structuring Machine Learning Projects'
        #   certificate_url: https://www.coursera.org/account/accomplishments/verify/PYMLJ5UNC57W
        #   date_end: ''
        #   date_start: '2018-07-01'
        #   description: ''
        #   organization: Coursera
        #   organization_url: https://www.coursera.org
        #   url: ''
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
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
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: sharma.suryansh97@gmail.com
      phone: Available Upon Request
      appointment_url: 'https://calendly.com'
      address:
        city: Sydney
        region: NSW
        postcode: '2007'
        country: Australia
        country_code: AU
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday to Friday 10:00 to 17:00'
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
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
    design:
      columns: '2'
---
