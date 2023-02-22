# Features requirements

This doc introduce the features requirements for the front of the new `Module de gestion bénévoles`.

Every BDD and data call have to be through the api [`CosmoAppy`](https://esnfranceg33kteam.github.io/CosmoAppy/).

## Adherents
- Add + update + Delete of adherent
- Having a list of all adherent
- Having filters of search in the list view
- Add a delete fonction to clean the list of adherents automatically (The life duration of an adherent is 365 days after each adhesion payment)

## Volunteers
To become a volunteer you have to be first register as adherent.
- A volunteer is before everything an adherent (except for the employee)
- Add + update + Delete of a volunteer
- Having a list of all volunteer
- Having filters of search in the list view
- Check adhesion fonction to know who need to update its adhesion
- Card by volunteer about his history of activity in the association

## ESNcard
- Ony an adherent can buy an `esncard` (voir loi sur la concurrence)

## Events
- Add + update of an event
- An adherent can be register to an event as attendee
- A volunteer can be register to an event as staff
- Having a calendar view of each event
- Having a list view of all event
- Having filters of search in the list view

## Plannings
- Add + update + delete of a planning
- A volunteer can be register to an event as attendee
- A volunteer can be register only for a certain among of time of the planning
- Having job for each attendee
- Having a calendar view of each planning
- Having a list view of all planning
- Having filters of search in the list view
- Having color for each kind of planning

## Money
- Add of a Money entry
- Having a list view of all money entries
- Having filters of search in the list view
- Any event spots sell, esncard sell, adhesion sell, ... have to be register as money entry

## Reports (`Compte rendu` in french)
- Add + update of a report
- Create report about event, planning or custom
- Having auto valorisation calcul for any report

## Projects
- Add + update of a project
- Affected volunteers on a project
- see more in the futur

## General pages
- Home page with some fun and usefull stuff (Toolbar on the front page, ...)
- Heatlcheck of api and bdd page
- Configuration page with every data of the configuration
- About page with all the public information about the assotion and the data policy and terms and condition
- Stats page with plots
- My account page with information about the session, role, ...

## Roles
Any role have to be manage from galaxy
- member: can add and update adherent, event, planning, report
- bureau aka admin : can do everything visually possible

