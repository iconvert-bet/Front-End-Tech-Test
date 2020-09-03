# iConvert Front-End Technical Test

## Introduction

Welcome to the iConvert Front-End Technical Test!

We hope that you find this exercise fun and interesting. There are no trick questions; we want to see your solution to a simple problem with well thought-out and well structured code.

## Tasks

We realise everyone has different levels of skill and experience when it comes to development so we have listed different levels of tasks below for you to choose from. If you do not have the time or the knowledge to complete them all then that's ok, we just want to see how you approach the problem and get a feel for how you code.

There are some tasks that could be too big to implement, but you may also describe how you _would_ tackle them (given more time/resources) in the covering note of your submission.

#### Basic Tasks
* Create a small front-end application to read and display data from a mock "campaigns" endpoint
* The endpoint in question can be found at https://run.mocky.io/v3/dfe80d90-c9d6-4add-bd64-a1fbaa1b5f73
* It returns a list of campaigns and their attributes, these should be displayed in a way you think makes sense
* Make sure to include the returned screenshot along with (at least) the campaign name, description, the start\end dates if it is enabled or not


#### Intermediate Tasks
* When displaying whether the campaign is enabled or not, take into account the start and end dates of the campaign (if the end date has passed, the campaign is not enabled, regardless of what `is_enabled` says)
* If there is no start/end date it should describe the campaign as "continuous"
* Add a "More Info" button that reveals the voucher code and voucher code expiry time.
* Add some automated tests (no need to test everything, but 1 or 2 would be good just to give examples of how you _would_ test)

#### Advanced Tasks
* Include a Dockerfile and/or docker-compose.yml
* What could a deployment look like? (Infra/CI/CD)
* Local development for multiple developers
* Code version control and branch/development life-cycle

#### Additional Tasks
* Add a "preview" section (hidden behind a button) that displays what is returned in the HTML field

## Languages

We use a mixture of coding languages at iConvert but out APIs are built in PHP (specifically Laravel), our front-end uses Vuejs and our event streaming system uses NodeJS. But for this tech test we are looking to get a sense of how you code, so please use the language/framework/app/tool with which you feel most comfortable.

## The Deliverable

Please submit a git repository (Github/Bitbucket etc.) that includes your code, along with a README that contains:

* A covering note explaining the technology choices you have made.
* Any instructions required to run your solution and tests in a unix environment.
