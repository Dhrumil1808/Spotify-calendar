# Calendar

This is a web application which lets you create, edit and delete events in yoiur calendar.

It has two parts:
1) calendar-frontend : Developed in ReactJs
2) calendar-backend : Developed in Spring Boot.


#Calendar- Backend

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
 
 

