## Intro

The main idea of it is to determine the level of a person's knowladge, so it's ok if something will not be done. The interview has the main task which will be estimated and reviewed with a candidate. Plus it also has an extra improvements which will add extra points into the total score.

## Description

Let's imaging we need to count a number of visits of "/visit" page and display statistics information on the root page("/").
This statistics should display the total number of visits and a number of visits by each HTTP method supported by Rails 4+.
This web app should be built on top of Rack or Sinatra.

## How to send work

Fork this repository and make a pull request. After a short period of time the pull request will be reviewed with a comments

## Extra points:

- lock version of ruby to 2.1.4; if you used sinatra - lock it to 1.4.2; if rack - 1.5.2
- in a good production env ruby developers like to use thin, unicorn or puma. Please add one of them into the web application and allow to start the app using `thin start`, `unicorn` or `puma`
- it would be nice if the web app shows a statistics by browsers too
- if an user opens an unknown path - redirect him to the index page or show a custom 404 page with a link to the index page
- write an acceptance spec for a provided functionality
- use haml/slim for the index page
