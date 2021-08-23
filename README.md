# Cs-230-Operating-Platforms_THE-GAMING-ROOM
Project+Journal
The Gaming Room was specifically a client requesting help deploying their existing game Draw it or Lose it as a web application across multiple platforms. The Gaming Room requested that the following software requirements be met for the game application::
  
    Only one instance of the game can exist in memory at any given time. This can be accomplished by creating unique identifiers for each instance of a game, team, or player.
    
    A game will have the ability to have one or more teams involved.
    
    Each team will have multiple players assigned to it.
    
    Game and team names must be unique to allow users to check whether a name is in use when choosing a team name.
    
  The client-server pattern provides a separation between the hardware, software and system functionality. As a result, only the front end is changed to adapt to different devices or platforms. Therefore, the use of a client-server pattern for the web-based gaming application enables the game to be used on multiple operating platforms. Multiple clients can share the resources provided by one server. This eliminates redundancy and saves on the memory space that the gaming application occupies on the client's device. New clients can easily be added, thus making the game application easily extensible. The client-server pattern allows quick communication between the client and server, and as a result, the game application performs at a fast rate.

  The user interface of the web-based gaming application is separated from the request or storage. As such, the server is able to scale each request individually. Furthermore, the server does not store any client context during communication. As a result, requests made to the server are made together with all the required data, and in case the server had any previous requests, no assumptions are made. Since REST API provides a layered system, a client is not able to know if it is communicating directly with the server or some proxy/load balancer.

# How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
  
   Overall I believe I did a phenomenal job throughout this project and through the weeks of developing the application based on the client's developmental guidelines. By considering the client's request, I was successfully capable of handling and designing the client's task. However, if the client was to request different requirements regarding the platform, this would change things dramatically. It's vital, to consider the user's needs when designing as The lack of user-centered design can cost time and effort and can greatly determine the success or failure of a project. From the user's perspective, it is the difference between completing a task or not and From the developer's perspective, it is the success or failure of a project, application, or system.
