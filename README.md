# CS230_Operating_Platforms
CS230 Module 8 repo

•	Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
    
 o	The Gaming Room is a client that owns the game Draw it or Lose it which they use to host game nights with customers. They wanted to expand their game from their current Android-based offering to a multi-platform app. While they expand to a variety of platforms, they also wish to expand their capability to host a larger user audience.

•	What did you do particularly well in developing this documentation?
   
   o	During the design of this documentation, I felt that my analysis and suggestion of using a full Linux stack was the best fit for The Gaming Room. Hosting their game server on a cloud-based Linux deployment will keep their costs low while allowing the scalability they desired for their users.

•	What about the process of working through a design document did you find helpful when developing the code?
  
  o	During this process it was fantastic to consider the infrastructure of the deployment before writing the actual code. Knowing how the software will be used, and how it will be implemented makes the coding portion more purposeful and reduces the amount of rework needed.

•	If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
  
  o	The design constraints section could have been expanded over the course of this class as more focus was placed on cloud architecture. As the industry moves away from on-prem deployments, The Gaming Room would likely also deploy their application using cloud architecture. The design constraints could have also touched on the network latency impacts and the memory required to run the application as more concurrent users joined.

•	How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
  
  o	The Gaming Room expressed the need to scale their application to a large user audience who will all need to maintain unique game sessions. As part of my implementation plan I suggested using REST APIs and Websocket communications as it decoupled the client device from the game server OS.

•	How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
  
  o	Initially I hadn’t put much thought into designing software before jumping in; focusing more on a rapid prototype approach instead of a planful execution. In the future I’ll map out everything using a UML diagram and an architecture comparison chart similar to what was in the template.
