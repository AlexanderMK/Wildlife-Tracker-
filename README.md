## Project Name
Wildlife Tracker

## Features
This app will help rangers log sightings for animals that may or may not be endangered.

![screenshot of project](wildlife-tracker.jpeg)

## Technologies
Java, JUnit, Gradle, Spark, PSQL

## Usage
To use the code, you can clone the repository at: [
* $ git clone
* $ cd Wildlife-Tracker-IP4 (Skip to database instructions below.)
* $ gradle run
* Go to localhost:4567 in your browser

## Database Instructions (postgres/psql)
* Run in terminal: postgres
* Run in new terminal window: psql
* CREATE DATABASE wildlife_tracker;
* \c wildlife_tracker;
* CREATE TABLE animals (id serial PRIMARY KEY, name varchar);
* CREATE TABLE endangered_animals (id serial PRIMARY KEY, name varchar, health varchar, age varchar);
* CREATE TABLE sightings (id serial PRIMARY KEY, animal_id int, location varchar, ranger_name varchar);
* CREATE DATABASE wildlife_tracker_test WITH TEMPLATE wildlife_tracker;

## Author
Alexander MK
mburukungu@gmail.com

## License
This work can be used under the MIT License.
Copyright (c) 2017 Alexander MK
