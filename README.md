# Address Book

* A program that collects user's contact information including name, phone number and address.

#### February 10, 2017

#### By **Jason Brown**

## Description
  Users enter's contact information.  The app stores names, phone numbers and addresses and displays them in a list.  It can also clear all entries.

| Behavior | Input Example | Output Example |
|----------|---------------|----------------|
| User enters a name. | Jason Brown | "Jason Brown" |
| User enters a phone number. | 503-123-4567 | "503-123-4567" |
| User enters an address. | 1234 N Portland St. 97213 | "1234 N Portland St. 97213" |
| User clicks submit button. User is directed to /create_contact screen with links to contacts.| "submit" | "You created a contact. (link to Jason Brown)" |
| /create_contact url includes a link back to homepage. | "home" | user is directed to homepage. |
| From homepage, user can push a button to delete all contacts. | "Clear" | User is directed to /delete_contacts page. User sees "Address book cleared" confirmation message. |
| From /delete_contacts page, user can click a button to direct them to homepage. | "home" | User is directed to homepage. |



## Setup/Installation Requirements

*  Clone github repository for places webpage
*  From your parent directory in terminal, run "$ composer install"
*  Run php server in terminal (from web directory) by typing "$ php -S localhost:8000"
*  in your browser type "localhost:8000"
*  Webpage will load.

## Known Bugs
_No known bugs exist._

## Technologies Used
* _HTML_
* _PHP_
* _TWIG_
* _SILEX_
* _Composer_


### License
*MIT

Copyright (c) 2017 Jason Brown All Rights Reserved.
