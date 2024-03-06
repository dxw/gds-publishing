---
tags:
  - accordion
  - filter
  - checkboxes
  - accessibility
---

# Users page
- Author(s) Calum Ryan
- Last updated: 5 Mar 2024
- Period of work: 2023-24
 
## What we did
- Conducted user research looking in to which adminS, managing editors and other users set permissions across different apps.
- Changed the existing Bootstrap design to instead use standard components from the GOV.UK Design System that's less complex and more accessible.
- Implemented the accordion component to group permissions by app for a tidyer layout.
- Included the filter component to help find and assign permissions more easily.

## Why we did it
To help make setting many user permissions in one go easier and more accessible. The existing design had been in use for many years, but without a consistent interface that was very accessible.

## Previous design
The previous design included a table layout with a complex listing of permissions with tags and an autocomplete field. The existing design was overwhelming for anyone new to using it and not responsive. It wasn't very accessible either, certain features such as the tag field was difficult to interact with when using an assistive technology such as a screen reader.

## First design iteration
The first design iteration grouped together permissions by their respective app. The search filter is a common component in Publishing apps that filters the list of permissions by letters typed in without needing to reload the page.

![List view of checkboxes with a search field above and collapsable sections with arrow](https://github.com/dxw/gds-publishing/assets/2226904/4eba83f3-80c7-476d-a4f7-7e17309fd440)

