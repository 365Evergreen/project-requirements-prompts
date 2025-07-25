## Project objective

A portal for frontline and office-based employees, that 
- displays latest company news
- provides information about the organisation
- provides easy access to policies and procedures
- has easy access to company resources

## Design requirements

- See index.html for intial design
- must be responsive, with a mobile-first approach
  
## Technical stack

- Azure Static Web App, with a React frontend
- CSS, HTMl, JS
- Entra ID

## Access and permissions

- All Entra ID users that are active
- Exclude accounts that are not associated with a person, e.g., service accounts
- B2C users may be able to register for access
-   B2C users will see limited content

## Integrations

- Integration with selected SharePoint Online sites
- Integration with Dataverse tables
- Power Automate workflows will run for some interactions

## Deliverables

An SWA with the following artefacts
- Pages
  - index.html
  - news.html
  - our-company.html
  - policies-and-procedures.html
  - my-home.html
  - meet-our-leaders.html
  - search-results.html
- style.css
- script.js
- search bar
- reusable footer, header and sidebar components
  - the header and footer components are on all exisitng pages
- a vanilla page template that can be used for the creation of new pages
  - with the header and footer components included
    - inbtween, there is a body section for aditional content   


