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
        - name: Python
          description: Python Programming Language
          icon: python
          icon_pack: custom
        - name: Computer Vision
          description: Object detection & Object Segmentation
          icon: glasses-solid
          icon_pack: custom
        - name: Machine Learning
          description: Regression and Clustering
          icon: laptop-code-solid
          icon_pack: custom
        - name: Robotic Operating System(R.O.S)
          description: Operating System to build robotic applications
          icon: robot-solid
          icon_pack: custom
        - name: Docker
          description: Deployment using containers
          icon: docker
          icon_pack: custom
        - name: Unix
          description: deploying software using linux servers
          icon: linux
          icon_pack: custom
        - name:  PowerBI and Office365
          description: Power BI for creating dashboards for gathering insights on a dataset 
          icon: microsoft
          icon_pack: custom
        - name:  Java
          description: Java Programming Language 
          icon: java
          icon_pack: custom

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
        - title: AI Software Engineer
          company: DroneShield, Sydney
          company_url: 'https://www.droneshield.com/'
          location: Sydney
          date_start: '2024-09-01'
          date_end: ''
          description: |2-  
            AI Software Engineer in the Radio Frequency AI Team at Droneshield. My responsibilites include but arent limited to. 

            * Conducting research on new algorithmic capabilities and performing feasibility assessments.
            * Analysing unlabelled radio frequency data to mark out signal characteristics.
            * Developing detection and tracking algorithms to identify objects of interest in the RF spectrum.
            * Creating visualizations of inferred outputs, to identify anomalies and detect dataset outliers.
            * Managing and implementing pipelines for evaluating and benchmarking algorithms.
            * Implementing systems in object-oriented languages, adhering to software design best practice.
            * Profiling, testing, and debugging code to improve performance and reduce computational complexity.
            * Writing and maintaining documentation for the RFAI software stack.
            * Attending meetings with project stakeholders to gather insights and understand evolving requirements.
            * Collaborating with cross-functional teams to enhance existing systems and develop new features.
            * Contributing domain expertise to guide feature development and decision-making.
        - title: Software Engineer
          company: University of Technology, Sydney
          company_url: 'https://www.uts.edu.au/about/faculty-engineering-and-information-technology/mechanical-and-mechatronic-engineering'
          location: Sydney
          date_start: '2022-08-01'
          date_end: ''
          description: |2-  
            The project was in collaboration with MissionSystems called HyperTeaming. The projects utilizes "Decentralized Monte Carlo Tree Search: DECMCTS" to perform coordinated exploration through autonomous vehicles(air and ground). My work was primiarily focused towards the software stack for the autonomous ground vehicle. The ground vehicle and the autonomy stack(Path Planners) was developed at UTS.

            * Worked on ground plane removal-based algorithm that works on point density to segment ground and non-ground points, downsampled points for computational efficiency, and integrated with the robot navigation stack to create a costmap. This helped maintain the desired publish rate on a higher resolution point cloud.
            * Collaborated on Adaptive Trajectory Planner, creating a version that supports four-wheel steering trajectories to perform spot turns for goal positions situated behind the robot. Using inflation costs and the trajectory definitions (and proper cost functions), the robot can drive autonomously through different terrains. Also, made an additional node that would provide reverse velocity commands when there is not enough momentum to perform a spot turn integrated with the twist-mux package.
            * Managed systems running on Ubuntu with ROS, deploying services using containers to avoid dependency issues.
            * Developed multi-threading packages for handling sensor data and concurrent processes using techniques like bind boost and boost thread to run functions simultaneously within a node.
            * C++, Python, and Bash: Utilized C++ for high-performance tasks such as local planning and joystick interface, and Python for tasks like GUI development and twist-mux locks. Transitioned from bash to docker-compose for package deployment ease.
            * Created an NLP model to convert natural language commands into signal temporal logic formulas for initiating robot path planning. This model achieved higher accuracy than previous models in the field and was the basis for a paper published in ACRA 2023.

        - title: Software Engineer
          company: University of Technology, Sydney
          company_url: 'https://www.uts.edu.au/about/faculty-engineering-and-information-technology'
          location: Sydney
          date_start: '2021-11-01'
          date_end: '2022-07-31'
          description: |2-
            Software Engineer-AI(Deep Learning) at School of Computer Science. The project utilizes Deep Learning techniques(object detection) to perform Search And Rescue Operations (SARS) in flooded areas; detect objects of interest and rescue them by dropping life-saving pods. The project was in collaboration with Australia4Innovation and LQTDU Vietnam.

            * Developed computer vision model tailored to different terrains (forests, water bodies, hilly areas) to minimize false positives and enhance environment-specific detection for detecting people drowning in floods.
            * Winner of NSW State iAwards 2024 in goverment and public sector.

        - title: Casual Academic
          company: University of Technology, Sydney
          company_url: 'https://www.uts.edu.au/about/faculty-engineering-and-information-technology'
          location: Sydney
          date_start: '2016-01-01'
          #date_end: '2020-12-31'
          description: Tutored three subjects during my postgrad study; Deep Learning & Convolutional Neural Networks(CNN), Python for Data Visualization and .NET application development.

        - title: Research Internship
          company: University of Technology, Sydney
          company_url: 'https://www.uts.edu.au/about/faculty-engineering-and-information-technology'
          location: Sydney
          date_start: '2020-11-01'
          date_end: '2022-02-01'
          description: |2-
            Research Internship under U.T.S. supervisor Dr Nabin S. (Senior Lecturer and Co-Director Intelligence Drone Lab) in the domain of Computer Vision using Machine and Deep Learning techniques. Consists of working on Computer Vision-based problems and publishing the obtained experimental results. Required Skill:
            * TensorFlow 
            * PyTorch  
            * OpenCV 
            * Python (Programming Language) 

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
        - title: 'Structuring Machine Learning Projects'
          certificate_url: https://www.coursera.org/account/accomplishments/verify/PYMLJ5UNC57W
          date_end: ''
          date_start: '2018-07-01'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          url: ''
        - title: 'Machine Learning A-Z™: Hands-On Python & R In Data Science' 
          certificate_url: https://www.udemy.com/certificate/UC-UL1VD3YU/
          date_end: ''
          date_start: '2017-09-20'
          description: ''
          organization: Udemy
          organization_url: https://www.udemy.com
          url: ''
        - title: 'Deep Learning A-Z™: Hands-On Artificial Neural Networks' 
          certificate_url: https://www.udemy.com/certificate/UC-VLDUTUL2/
          date_end: ''
          date_start: '2017-09-12'
          description: ''
          organization: Udemy
          organization_url: https://www.udemy.com
          url: ''
        - title: 'Complete Python Bootcamp: Go from zero to hero in Python 3'
          certificate_url: https://www.udemy.com/certificate/UC-S9U636ET/
          date_end: ''
          date_start: '2017-08-15'
          description: ''
          organization: Udemy
          organization_url: https://www.udemy.com
          url: ''
        - title: 'Structuring Machine Learning Projects'
          certificate_url: https://www.coursera.org/account/accomplishments/verify/PYMLJ5UNC57W
          date_end: ''
          date_start: '2018-07-01'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          url: ''
    design:
      columns: '4'

#To Edit Projects
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
        # - name: Other
        #   tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  
  #To edit publications
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: false
  #   design:
  #     columns: '2'
  #     view: card

  - block: markdown
    content:
      title: Work
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  
  # - block: markdown
  #   content:
  #     title: Extra-curricular
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="extracurricular" >}}
  #   design:
  #     columns: '1'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # text: |-
      #   Kindly fill out the below template if you wish to contact me, thank you.
      # Contact (add or remove contact options as necessary)
      email: sharma.suryansh97@gmail.com
      phone: Available Upon Request
      appointment_url: 'https://calendly.com/sharma-suryansh97'
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
    #   # Email form provider
    #   form:
    #     provider: netlify
    #     formspree:
    #       id:
    #     netlify:
    #       # Enable CAPTCHA challenge to reduce spam?
    #       captcha: false
    # design:
    #   columns: '2'
---
