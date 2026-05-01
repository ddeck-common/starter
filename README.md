# DDeck

A Drupal Distribution designed as a foundation for building collaborative platforms with large contributor teams.

It is based on : 
- Drupal
- Drupal recipes and SDC
- Radix and Radix Admin
- Bootstrap, his ecosystem, and its CSS variables
- HTMX

## Requirements

To Run Ddeck on your local machine you will need :
- [Composer](https://getcomposer.org/download/) 
- [Ddev](https://ddev.com/download/)

## Installation

`composer create-project ddeck-common/starter MY_SITE_NAME`

When installation finished go inside the created directory 

`cd MY_SITE_NAME`

Configure Ddev

`ddev config`

Answer all the question and select Drupal 11 as the project base.

Then 

`ddev start`



