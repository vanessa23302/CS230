# CS230
Operating Platforms 

Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
The client was The Gaming Room, and they wanted to expand their current Android game, Draw It or Lose It, into a web-based application that could run across different platforms. They needed the game to support multiple teams and players, make sure all team and game names were unique, only allow one active game at a time, and include secure login and authentication. They also needed the design to scale so it could handle more users in the future.

What did you do particularly well in developing this documentation?
I think I did really well when it came to analyzing the different platforms and explaining why Linux was the best choice. I also feel like I connected the client’s requirements to the design patterns clearly, like using the Singleton to make sure only one game runs at a time. Organizing the document in a way that made sense for both technical and nontechnical readers was also something I did well.

What about the process of working through a design document did you find helpful when developing the code?
Working through the design document really helped me plan things out before I started coding. It gave me a chance to think about how everything should be structured, especially around security, memory, and scalability. Having that roadmap made it easier to focus when I was writing code because I already had a clear idea of how it should work.

If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
If I could go back and revise one part, I would improve the security section. I covered the basics like HTTPS and token authentication, but I know I could add more details about database encryption, intrusion detection, and stronger prevention strategies. Adding that would make the design even more realistic and secure.

How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
I made sure to look closely at the client’s needs and match them with design choices. For example, they needed unique names and only one game running at a time, so I used the Singleton and Iterator patterns to solve those problems. It’s really important to focus on user needs because if the design doesn’t solve their problems or isn’t easy to use, the software won’t really be successful no matter how good the code is.

How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
My approach was to break the requirements into categories and then figure out the best technical solutions for each one, like architecture, storage, and security. I also used comparisons between platforms to justify my recommendations. In the future, I’d like to use more UML diagrams and visuals to make the design easier to understand. I’d also consider microservices and containerization earlier on to make scaling and updates smoother.
