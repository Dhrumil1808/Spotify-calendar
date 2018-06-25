# Calendar

App is deployed on : https://calendar-agenda.herokuapp.com/





This is a web application which lets you create, edit and delete events in your calendar.

It has two parts:
1) calendar-frontend : Developed in ReactJs
2) calendar-backend : Developed in Spring Boot.


# Calendar- Backend

Consists of four APIs namely:

# 1) Get All Events

API:  http://localhost:8080/events
{ "eventId" : <event_id>, "starttime": <start_time>,"endtime": <end_time>,"startDate": <start_date>,  "endDate": <end_date> , 
        "eventDesc": <event_description>}
        

#  2) Create an Event

API:  http://localhost:8080/events
{ "starttime": <start_time>,"endtime": <end_time>,"startdate": <start_date>,  "enddate": <end_date> , 
        "description": <event_description>}
        
# 3) Edit an Event

API:  http://localhost:8080/events/{event_id}
{ "starttime": <start_time>,"endtime": <end_time>,"startdate": <start_date>,  "enddate": <end_date> , 
        "description": <event_description>}
        
        
 # 4) Delete an Event
 
 API: http://localhost:8080/events/{event_id}
 
 


Steps for running it on localhost:

1) git clone https://github.com/Dhrumil1808/Spotify-calendar
2) go to calendar-backend directory
3) run mvn clean install 
4) if you are using Eclipse IDE, then you can directly run the "Application.java" file from the eclipse.
It will start the server on http://localhost:8080

5) Go to calendar-frontend directory
6) run npm install
7) run npm start

The client will start running on http://localhost:3000 and you can create , edit and delete events in your calendar.
