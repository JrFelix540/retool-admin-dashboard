# Retooling Restaurant Reviews: Sample Data for an Admin Panel Built with Retool and MongoDB

This repository contains sample data for a restaurant review application. It is intended to be used by article Building An Admin Panel with Retool and MongoDB.

## Sample Data Breakdown

### Restaurants Data

Contains mocked restaurant with the following properties:

- restaurant_id
- name
- street
- cuisine
- email_address
- verified
- stars

### Reviewers Data

Contains mocked restaurant reviewers with the following properties:

- reviewer_id
- name
- email_address
- verified

### Reviews Data

Contains mocked reviews with the following properties:

- content
- rating
- reviewer_id
- restaurant_id

## How to Load Sample Data into MongoDB Atlas

By utilizing the `mongoimport` tool through the command line interface, the sample data is added to MongoDB Atlas. More information on installation and use can be found [here](https://www.mongodb.com/docs/database-tools/mongoimport/#mongodb-binary-bin.mongoimport)
