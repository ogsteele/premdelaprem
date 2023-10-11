---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Prem de la Prem
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-
        {{< gallery album="socials" >}}
    design:
      columns: '1'
  - block: features
    content:
      title: Ingredients
      items:
        - name: (Friendly) Bullying
          description: 80%
          icon: face-grin-squint-tears
          icon_pack: fas
        - name: Gary's Stats
          description: 10%
          icon: chart-line
          icon_pack: fas
        - name: Rugby
          description: 10%
          icon: football
          icon_pack: fas
  - block: Experience
    id: history
    content:
      title: League History
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Prem de la Prem '23-'24
          company: Superbru Premiership Rugby
          company_url: ''
          company_logo: premdelaprem
          date_start: '2023-10-13'
          date_end: ''
          description: |2-
              Major events:

              * Moved to Superbru
              * League expanded to 12
              * Website established
        - title: Prem de la Prem '22-'23
          company: Fantasy Rugby Draft
          company_url: ''
          company_logo: frd
          date_start: '2022-10-13'
          date_end: '2023-09-12'
          description: |2-
              Major events:

              * Moved back to Fantasy Rugby Draft
              * Readopted conference system
        - title: Prem de la Prem '21-'22
          company: Fantasy Rugby World
          company_url: ''
          company_logo: frw
          date_start: '2021-10-13'
          date_end: '2022-09-12'
          description: |2-
              Major events:

              * Moved over to Fantasy Rugby World
              * Dropped the conference system
              * League expanded to ten
        - title: Prem de la Prem '20-'21
          company: Fantasy Rugby Draft
          company_url: ''
          company_logo: frd
          date_start: '2020-10-13'
          date_end: '2021-09-12'
          description: |2-
              Major events:

              * Inaugrual season
              * Founding fathers named
    design:
      columns: '2'
  - block: accomplishments
    id: champions
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Hall of Champions'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_end: ''
          date_start: '2023-06-25'
          description: 'First two-time champion'
          organization: Prem de la Prem Champion '22-'23
          title: Sam Gilbert
        - date_end: ''
          date_start: '2022-06-25'
          description: 'Someone other than Sam ... probably for the last time'
          organization: Prem de la Prem Champion '21-'22
          title: Ben Cripps
        - date_end: ''
          date_start: '2021-06-25'
          description: 'The inaugrual Prem de la Prem Champion'
          organization: Prem de la Prem Champion '20-'21
          title: Sam Gilbert
    design:
      columns: '2'
  - block: people
    id: people
    content:
      title: Meet the League
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - Board Members
        - Coaches
        - Grad Students
        - Administration
        - Visitors
        - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      # Show user's social networking links? (true/false)
      show_social: false
      # Show user's interests? (true/false)
      show_interests: true
      # Show user's role?
      show_role: true
      # Show user's organizations/affiliations?
      show_organizations: true
---
