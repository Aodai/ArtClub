# ArtClub

## General Description

The application will allow the managing of the activities of an art club. The informatic system will contain a user interface  ( web navigator or dedicated application), a database server which will stock the informations about the activity of the association, an application server.  The user has access to the service only through the user interface.  
The system will offer the possibility of managing the members of the association, the management of member contribution fees and the managing of resources ( ex: Conference halls , expositions etc)  
Depending on the form of authentication (admin/user), the user will be allowed to manage members, add fees, add resources.

## Application Requirements

1.	The access to the app must be user and password protected
2.	When realizing the communication protocol you should have in mind the possibility of having multiple people connected at the same time
3.	The administrators will have the possibility of adding/editing members, adding fees , edit resources , define the fees for cotizations ( no clue what that is or how to translate it properly) 
4.	The users will be able to create/edit events and select the invited members, reserve resources for the event , visualize the events where they were invited 
5.	For each resource it will be marked when it is available and when it is reserved 
6.	A resource can be reserve for an event only if it is not in use at the date of the event 
7.	For each reservation the resource used will be unavailable one day before and after the event
8.	Each event that requires resources will generate charges of 200 lei/day/resource for the club
9.	It will be possible to generate a report of due payments from members 
10.	It will be possible to generate a report of assets (I think that’s the best translation for venituri, probably means money available) and spendings for a chosen month 
11.	It will be possible to generate a report of resources available at a certain time interval 
12.	It will be possible to generate a report for the reservation calendar for a resource ( don’t really understand this one since 16 doesn’t really talk about something related to this) 
13.	A resource will be freely reserved for a member if the conditions 15 and 16 are met
14.	A resource can be reserved by a person that is not a member if they will pay a 400 lei/day tax
15.	A resource can be reserved at any time by an administrator if it is not already in use 
16.	A  resource reservation can not be done in a certain month ,by the members, if the sum of spendings exceeds the earnings (idk what this really means tbh) 
