---
title: 科研成果
type: landing


sections:
  - block: markdown
    content:
      title: My title
      subtitle: My subtitle
      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      
  - block: collection_work

    content:
      title: <div style="margin-bottom:1em; margin-top:0.5em;">科研成果</div>
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - work
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'content_id'
      sort_ascending: true
      archive:
        enable: true
        text: more
        link: ../work/

    design:
      # Choose a listing view
      view: Showcase
      # Choose single or dual column layout
      columns: '1'
      flip_alt_rows: true

---
