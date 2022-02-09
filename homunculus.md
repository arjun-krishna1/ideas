# Simulating users for end to end testing
## Elevator Pitch
- Set up daily end to end testing with logs and reporting with 0 lines of code
## MVP
- Give your url
- Opens your website through a proxy
    - like 12ft.io
    - https://12ft.io/
    - https://12ft.io/proxy?q=https://www.economist.com/science-and-technology/2021/01/02/sars-cov-2-is-following-the-evolutionary-rule-book**** 
- You press record
- Homunculus will record all the clicks you take on your website
- You press stop recording
- You can then set up a schedule and homonculus will repeat all the paths you have recorded on the schedule
- Can use something like [Cypress](https://github.com/cypress-io/cypress) (Selenium like) for building it
- Record console output, networks output, etc and store for later
- Screen record
- Send slack message if anything out of the ordinary
- Automated end to end testing
## Sprinkles
- Record user paths
- Mobile view/Different views
- Turn into a kubernetes cluster, run all at once 
- Add most common/average paths to repertoire from recording actual user paths
- Build user profiles using the user paths and their data
  - ???
## Business
- Freemium
- Pay for more than x paths and/or y clicks
- Pay for us to store all the data beyond certain amount
## Resources
- https://stackoverflow.com/questions/50882063/selenium-alternative-for-python-fastest-way-to-access-web-elements
- Cypress demo video https://player.vimeo.com/video/237527670
- https://www.cypress.io/
