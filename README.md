# Bike network location finder

## What is this project

This project is meant to be a teaching/learning tool for junior engineers and people that want to learn how to work in a team.

It is simple enough to finish while also being complicated enough to be interesting and challenging.

## Who?

This project came up as something that will benefit the memebers of [The Fullstack Network](https://fulllstack.network).

* [Twitch](https://twitch.tv/KensoDev)
* [Discord](http://avi.io/discord)
* [Reddit](http://avi.io/reddit)
* [YouTube](https://www.youtube.com/channel/UCuFT6CtDnOGvcn9WdAvBusA)

## Team size

This project works best with 2-3 people. You will team up for the project as you wish.

## Project description

You will create an API to locate and update bike network locations.

Bike network is a company/location to rent bikes around the world. Your website is an index for users to find these networks and also to update information about the network.

### Initial data

Initial data for this project should be grabbed from: [here](http://api.citybik.es/v2/networks) and documentation about this api can be found [here](http://api.citybik.es/v2/).

## Server side

Server side for this project can be written in any language you'd like and backed by any database.

### Tasks

1. Design the schema for the database
2. Provide an API to list the networks
3. Provide an API to get details on a specific network
4. Provide an API to update the available slots in a specific location
5. Provide an API to update that a location is closed
6. Provide an API to update that a location is not safe for use
7. Provide an API to allow users to share reviews on a specific location (no sign in needed).

You should be using the initial citibike API for seeding your data, you should not use it in any other way. In real time, the API should query your database and not communicate with the citybike API.

This means, you will need to create a seeding script that will consume the citibike API and fill your database with initial data in dev.

### Comments

I wouldn't worry about authentication or security for now, just the initial implementation would suffice. Making sure all the moving parts are in place.

## Client side

1. Display a map of all the networks 
![image](http://assets.avi.io/Documentation__CityBikes_API_2017-08-10_16-53-40.png)
-- You can use Google maps for that or any other mapping service you wish.  
-- You can use a pre-built library for that.
2. Clicking on a network will display the stations in the network  
-- At this point, the map of the network should be filled with only the locations for the specific network and you should center it around the locations
3. Clicking on a location will show the location details  
-- The displayed content should be in a separate page or open a modal  
-- The details should include everything in the citibike API and you should make an effort to make it look nice and be readable
4. Clicking on a location will allow the user to update the number of available slots
5. Clicking on a location will allow the user to update and add reviews on the location
6. Clicking on a location will allow a user to mark the network as not safe or closed

## Working on the project

You will be required to manage the project on [trello](https://trello.com). This means that you will create a "task" for every thing you are doing. The more details the better.

You will be judged based on the project management just as much as on the project code.

### Github flow

You code **must** be open source and be managed on Github. You will create a PR for every feature and mark it clearly with the ticket on Trello. This way we can see if you are on target.

Members should review their own code and get one of the judges to review as well.

If you need to create the project under the-fullstack-network github org, we would love to provide that space for you.

## Mentoring

I ([KensoDev](https://github.com/KensoDev)) will personally mentor the first 3 teams to get organized. Mentoring will include code review and looking over the project management.

Mentoring will also include 1H of hands-on mentoring with the team members. You can bring your questions/comments and we get through them to solve problems.

We will star the project together and discuss how we make it happen in the most efficient way.

## Prize

300$ in Amazon gift cards evenly shared across the team

![Amazon gift cards](http://assets.avi.io/Web_Image_2017-08-10_17-16-27.png)

## Judges 

TBD