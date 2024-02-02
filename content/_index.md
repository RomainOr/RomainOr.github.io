---
# Leave the homepage title empty to use the site title
title: ''
date: 2021-02-01
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
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: "Temporary Assistant Professor"
          company: CSTB, ICube & IUT Robert Schuman, University of Strasbourg
          company_url: 'https://iutrs.unistra.fr/'
          location: Illkirch-Graffenstaden, France
          date_start: '2023-09-01'
          date_end: ''
          description: Is responsible for Development Quality resources (BUT 2 S4 and BUT 3 S5). Teaches the resources Production Chain Automation (BUT 3), Analysis (BUT 2), Development Quality (BUT 2 S3), System Programming (BUT 2), Virtualization - Operating System (BUT 2) and Introduction to Computer Architecture (BUT 1).

        - title: "Temporary Research and Teaching Assistant"
          company: CSTB, ICube & IUT Robert Schuman, University of Strasbourg
          company_url: 'https://iutrs.unistra.fr/'
          location: Illkirch-Graffenstaden, France
          date_start: '2021-09-01'
          date_end: '2023-08-31'
          description: Was responsible for the Development Quality resource (BUT 2 S4). Teached the resources Analysis (BUT 2), System programming (BUT 2), Virtualization - Operating system (BUT 2), Performance (DUT 2), Algorithmic complexity (DUT 2), Advanced object programming and design (DUT 2), Principles of operating systems (DUT 2), Numerical methods (BUT 1), Numerical tools for descriptive statistics (BUT 1) and Introduction to computer architecture (BUT 1).
          
        - title: "Temporary Lecturer"
          company: UFR Math-Info, University of Strasbourg
          company_url: 'https://mathinfo.unistra.fr/'
          location: Strasbourg, France
          date_start: '2018-09-01'
          date_end: '2021-08-31'
          description: Provided lab sessions about Web development, Java programming and Artificial Intelligence.
          
        - title: "Temporary Lecturer"
          company: ECAM Strasbourg-Europe
          company_url: 'https://en.icam.fr/'
          location: Schiltigheim, France
          date_start: '2018-09-01'
          date_end: '2019-08-31'
          description: Was responsible for all the lectures and the Active Directory lab sessions of the Architecture and Networks module.

        - title: "RDI Consultant"
          company: Actimage
          company_url: 'https://www.actimage.com/en/'
          location: Beggen, Luxembourg
          date_start: '2017-10-01'
          date_end: '2018-08-31'
          description: Worked as a Research, Development and Innovation Consultant for Actimage. Was responsible for the image analysis and algorithmic software for the Sidas Feetbox kiosk project.

        - title: "Research Engineer Internship"
          company: Inria Grand Est
          company_url: 'https://www.inria.fr/en/inria-centre-universite-lorraine'
          location: Villers-lès-Nancy, France
          date_start: '2017-04-01'
          date_end: '2017-09-01'
          description: Created a connected object prototype with haptic feedback as part of a post-stroke rehabilitation system, within the Neurosys team. Used the Unreal Engine 4, Python, OpenVIBE, Matlab and the C language.

        - title: "Engineer Internship"
          company: Luxembourg Science Center
          company_url: 'https://www.science-center.lu/en'
          location: Differdange, Luxembourg
          date_start: '2016-06-01'
          date_end: '2016-08-01'
          description: Developed an educational tool for the experimental stations in C++ with Embarcadero C++ Builder. Prepared a demonstration about NAO with the Chorégraphe package for the visit of the Prime Minister of Luxembourg.
    design:
      columns: '2'
  - block: collection
    id: publication
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: list
  - block: portfolio
    id: courses
    content:
      title: Courses
      filters:
        folders:
          - courses
        exclude_featured: true
      default_button_index: 0
      buttons:
        - name: All
          tag: "*"
        - name: IUT Robert Schuman
          tag: iut
        - name: UFR Math-Info of Unistra
          tag: ufr
        - name: Ecam Strasbourg-Europe
          tag: ecam
    design:
      columns: '1'
      view: card
  - block: markdown
    id: other
    content:
      title: Other Activities
      text: |-
          **Test 1**
          *Test 2*
          From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
          <!--Custom spacing-->
          <div class="mb-3"></div>
          Test 3
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      email: rorhand@unistra.fr
      address:
        street: CRBS, 1 Rue Eugène Boeckel
        city: Strasbourg
        postcode: '67000'
        country: France
        country_code: Fr
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '48.575918'
        longitude: '7.7385449'
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
