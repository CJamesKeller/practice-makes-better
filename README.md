# PRACTICE MAKES BETTER

## PLAN OF ATTACK, FRONTEND

* (*Required project init stuff*)
* We want a visual interface with some data, and we have data
* But data is behind auth
* [ ] Inputs for auth for request for data
* Now, get data and directly put it on the page
* [ ] That^ (with test)
* Now make it pretty
* Since I'm using UFO reports by state, let's make it a map
* [ ] Add map package
* Then it can be clickable by state for further details
* Maybe route to page `/:state/:incidentId`
* List applicable events on that page
* [ ] Hook up to data
* [ ] Route to page (test - Cypress)
* [ ] Display state name
* [ ] List raw events (test - regular UI test)
* [ ] Put details on a `<Card />`? Something clean looking
* Page for specific incidents
* [ ] OnClick, route to specific incident at `/incident/:id` (test - Cypress)
* [ ] Raw output on page (test - UI)
* [ ] Some kind of "dossier" look to the page, like pseudo file paper?
