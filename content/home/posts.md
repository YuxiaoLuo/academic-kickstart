---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

<<<<<<< HEAD
widget = "pages"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = false  # Activate this widget? true/false
weight = 60  # Order that this section will appear.
=======
# This file represents a page section.
headless: true
>>>>>>> a32eb21fa918f4abe6bab16b9088379dc90577f2

# Order that this section appears on the page.
weight: 60

title: Recent Posts
subtitle:

content:
  # Filter on criteria
  filters:
    folders:
      - post
    tag: ''
    category: ''
    publication_type: ''
    author: ''
    exclude_featured: false
    exclude_future: false
    exclude_past: false
  # Choose how many pages you would like to display (0 = all pages)
  count: 5
  # Choose how many pages you would like to offset by
  offset: 0
  # Page order: descending (desc) or ascending (asc) date.
  order: desc

design:
  # Choose a view for the listings:
  view: compact
  columns: '2'
---
