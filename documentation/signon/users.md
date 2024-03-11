---
tags:
  - table
  - filter
  - accessibility
---

# Users page
- Author(s) Calum Ryan
- Last updated: 5 Mar 2024
- Period of work: 2023-24
 
## What we did
- Updated design of the Users page from existing Bootstrap to GOV.UK Design System
- Phased accessibility improvements to overall design that meet WCAG 2.2 (AA)
- Incorporated search and filtering of users based on component used in GOV.UK website search

## Why we did it
To help make managing and editing other users permissions easier and more accessible. The existing design had been in use for many years, but without a consistent interface that was very accessible.

## Previous design
![Bootstrap designed page with filters at the top laid out horizontally and table of users below](https://github.com/dxw/gds-publishing/assets/2226904/18aff832-4411-43bf-b546-1b4c914a9259)

## First design iteration
The first design iteration prioritised as much as possible a like-for-like transition of the existing design replicated in the GOV.UK Design System. There wasn't a comparable component in the design system for filters to be laid out horizontally that worked well for this kind of page. We therefore took inspiration from the design applied to [GOV.UK Search](https://www.gov.uk/search/all?keywords=article&order=relevance) to filter results.

### New users page
The first design iteration of the Users using the GOV.UK Design System.

![Screenshot with Signon Users page using the Design System with a table on the right and left sidebar containing search and filters component including arrows to show/collapse different filters](https://github.com/dxw/gds-publishing/assets/2226904/58b2db04-c11f-45ac-89ef-e688f684fc2b)

![Screenshot with Signon Users page at 400% zoom with results listed vertically include label on left and content on the right](https://github.com/dxw/gds-publishing/assets/2226904/d9562366-f795-4031-b53c-8c490db632af)

### GOV.UK Search to filter results
Following discussion with another interaction designer at GDS, Nikin Nagewadia, it was suggested we take a look at this example from GOV.UK. Our team of developers from [Go Free Range](https://gofreerange.com/) were able to find the code modules needed to import some of its features for the Users page.

<img width="1008" alt="Screenshot from GOV.UK Search with example of filter on left handside taking up about 1/3 of the page and the remaining 2/3 of the page showing search results in a vertical layout" src="https://github.com/dxw/gds-publishing/assets/2226904/573df890-9e95-414d-990e-322e54358caf">

## Second design iteration
Following changes to the design system to make it more accessibile and compliant with WCAG 2.2, we iterated the design to include tags for the status of users rather than a strike through. Following feedback from others in the Publishing team, it was agreed that this was a more consistent, accessible approach. On smaller viewport sizes, the design was improved to align all content to the left following feedback from users with vision impairment.

![Screenshot with Signon Users page in a table layout using the coloured tag components of green for active users and grey for suspend users](https://github.com/dxw/gds-publishing/assets/2226904/5fd88aa5-62f5-4414-b52f-d2d995906ab9)

## Notes for handover
Development work was in progress to change the strikethrough style on suspended users to instead use a tag component in the status column.

User research with vision impaired users was conducted towards the end of our work with GDS of this period. This highlighted two usability issues:
- On smaller viewports which uses an alternative table layout, there's too much space between the table headings and contents. Our proposed change includes aligning table content to the left subject to further user research and checking technical feasibility with developers
- On larger viewports the large quantity of table rows means that it's harder to reference which column content relates to. Our proposed change includes using fixed position table headings subject to further user research and checking technical feasibility with developers
- Another proposed iteration of the design would be to change the overall page layout to a single full width column, and giving over more space for the table whilst positioning the filters above. This would likely need a way to hide the filters using a toggle button. Again this is subject to further user research if possible.
