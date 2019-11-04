# Upload API

Your task is to create a restful JSON backend API with Ruby. 
Users should be able to upload files and manage them.

**MUST** Features is the minimum needed to consider the task completed.

**CAN** Features is extras that are on top of the minimum and are extra point during evaluation.

## MUST Features

* Authentication over API Key for all interactions
* A file to be uploaded for a certain user account. 
  * files have:
    * a name
    * a binary representation
  * users have:
    * an email address
* A file can be deleted again after being uploaded
* A file can be downloaded in their binary representation by only the uploading user

## CAN Features     

* User registration
* User management:
  * change their own passwords
  * delete their own account
* Generate image previews for uploads (e.g. on PDF or image uploads)

## NON-FUNCTIONAL requirements

* Use off-the-shelf components and frameworks (misc. Rails Components, ActiveStorage, Devise, Rspec, …)
* Create Unit and Integration tests
* Add at least some README style docs for installing, setup and running the app

## Keep in mind:

* Every solution is considered - even incomplete
* Solutions are ideally hosted on your public github (or whatever code hosting platform you prefer) account
