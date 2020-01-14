---
title: "Projects"
date: 2019-01-19T02:42:30+01:00
draft: false
author: Eddie Tseng
---

<hr />

## Face App

Facial recognition web application that can detect faces in a picture and returns a matching name if algorithm has been trained. The application takes a picture and returns boxes around each face. If the algorithm does not know the face, it will simply return unknown around the box. This application has been dockerized into two containers. A front end container and a back end container.


You may download the docker containers to run here:

[FaceApp-FrontEnd-Container]

[FaceApp-BackEnd-Container]

**Tech Stack:** Typescript, ReactJS, SCSS, Python, Flask, Docker

**Github:** [FaceApp] 

Uploaded a picture of Biden to train the algorithm.

{{< image src="/faceapp1.png" alt="faceapp train" position="center" >}}



After identifying pictures in a face the application will append the image to the page. The image will identify faces it has been trained on and will display unknown for faces it has not been trained on.

{{< image src="/faceapp2.png" alt="faceapp identify" position="center" >}}

## Remember (IN PROGRESS)

A flashcard application used to help commit knowledge into long term memory. Users are required to create decks. Users can add and remove cards from the deck. Users can enter a study mode to test their knowledge of cards in the deck. The application will determine the next timestamp that the user needs to study each flash card depending on the results. Cards that the user answers incorrectly will have a more frequent interval and the cards that the users answers correctly will have a longer interval. Knowledge that the user frequently gets incorrectly will be reminded at a shorter interval to commit that knowledge to long term memory.

**Tech Stack:** React Native, Redux

**Github:** [Remember]

<hr />

## Skedoodle!
Skedoodle is a multiplayer party game modelled after telestrations designed to be played on mobile devices. Players will be able to connect from their mobile browser into a lobby displayed on a monitor or TV. Once the game starts, each player is given a word and asked to draw that word. Drawings will be converted into a blob (Binary Large OBject) and processed by the database. Each drawing is passed to another different player. The server sends a blob and the app converts the blob back into an image. The following player has to guess what they think the image is. The guess is passed and the next player has to draw that word. This continues until all the rounds are complete. Players will be able to visually see on the host machine (typically displayed on a big monitor) how their word and drawings have mutated over each player's iteration.

**Tech Stack:** ReactJS, Express, PostgreSQL, Socket.io

**Github:** [Skedoodle]


#### Host Machine View
{{< image src="/skedoodle2.png" alt="skedoodle" position="center" >}}

#### Mobile Client View
{{< image src="/skedoodle1.png" alt="skedoodle" position="left" >}}

<hr />

## Scheduler
Interview scheduler that is built using react. The scheduler makes axios requests to a database that stores the data and then updates the state to ensure that the components on the screen are updated in real time.

**Tech Stack:** ReactJS, Express, PostgreSQL, Axios

**Github:** [Scheduler]

#### Scheduler View
{{< image src="/scheduler1.png" alt="scheduler1" position="left">}}
#### Adding an Appointment View
{{< image src="/scheduler2.png" alt="scheduler2" position="left">}}
#### Appointment is Successfully Added and Spots are Updated
{{< image src="/scheduler3.png" alt="scheduler3" position="left">}}

<hr />

## Round Up
An event proposal application where users can generate an event proposal with multiple possible event start times for invitees to RSVP. A unique URL is generated every time a new event is created and invitees can follow the URL to cast their RSVP or edit their existing RVSP. Users will be able to visually see results for every other invitee that has already RSVP-ed.

**Tech Stack:** NodeJS, JQuery, Express, PostgreSQL, Fomantic UI

**Github:** [RoundUp] 

{{< image src="/roundup.png" alt="RoundUp1" position="left">}}

More images available on github.



[FaceApp-FrontEnd-Container]:https://hub.docker.com/r/etseng02/faceapp
[FaceApp-BackEnd-Container]:https://hub.docker.com/r/etseng02/faceappflask
[FaceApp]:https://github.com/etseng02/faceapp
[Remember]:https://github.com/etseng02/remember
[Skedoodle]:https://github.com/etseng02/illustrations
[Scheduler]:https://github.com/etseng02/scheduler
[RoundUp]:https://github.com/etseng02/project-roundup
