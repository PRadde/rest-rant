# Project REST-Rant

REST-Rant is an app where users can review restaurants.

ROUTES DATA
| Method | Path                     | Purpose                                          |
|--------|--------------------------|--------------------------------------------------|
| GET    | /                        | Home Page                                        |
| GET    | /places                  | Places index page                                |
| POST   | /places                  | Create new place                                 |
| GET    | /places/new              | Form page for creating a new place               |
| GET    | /places/:id              | Details about a particular place                 |
| PUT    | /places/:id              | Update a particular place                        |
| GET    | /places/:id/edit         | From page for editing an existing place          |
| DELETE | /places/:id              | Delete a particular place                        |
| POST   | /places/:id/rant         | Create a rant (comment) about a particular place |
| DELETE | /places/:id/rant/:rantid | Delete a rant (comment) about a particular place |
| GET    | *                        | 404 page (matches any route no defined above)    |


PLACES DATA
| Name                        | City       | State | Cuisines | Picture      |
|-----------------------------|------------|-------|----------|--------------|
| Coronas Cantina             | West Salem | WI    | Mexican  | google image |
| Golden China                | West Salem | WI    | Chinese  | google image |
| Features Sports bar & Grill | West Salem | WI    | Grill    | google image |
| Burrachos Mexican Grill     | Onalaska   | WI    | Mexican  | google image |