# cs-230
Portfolio Reflection – CS 230: Software Design Document
Client and Software Requirements
The client for this project was The Gaming Room, a company seeking to expand its existing Android-based game application, Draw It or Lose It, to additional platforms. The game is a multiplayer, team-based drawing and guessing game that requires the ability to support multiple concurrent game instances, manage a large library of image assets, and provide consistent performance across platforms. The primary requirement was to design a scalable, web-based distributed system that could support desktop and mobile clients while maintaining security, performance, and extensibility. The goal of the software design document was to evaluate operating platforms, system architectures, memory and storage management strategies, and security considerations to guide future development decisions.

Strengths in Developing the Documentation
One area I performed particularly well in was evaluating and comparing operating platforms. I was able to clearly articulate the advantages and limitations of Linux, Windows, macOS, and mobile platforms in relation to hosting and consuming a web-based application. I also effectively connected technical considerations—such as licensing costs, scalability, and tooling—to business needs. Additionally, I clearly structured the document to communicate complex technical concepts in a way that would be understandable to both technical and non-technical stakeholders.

Value of the Design Process
Working through a formal software design document was extremely helpful in shaping how the code would eventually be developed. The design process forced me to think holistically about the system before writing any implementation code. By considering architecture, constraints, memory usage, and storage requirements early, I was able to make more informed decisions during development. This approach reduced rework and helped ensure that the solution aligned with the client’s long-term goals rather than just immediate functionality.

Opportunities for Improvement
If I were to revise one part of the documentation, I would expand the domain model and system architecture sections. While they met the requirements of the assignment, additional diagrams or more detailed explanations of component interactions could further improve clarity. Enhancing these sections would make the document even more useful for onboarding new developers or transitioning the project to another team.

User Needs and Their Importance
User needs were interpreted by focusing on performance, accessibility, and platform independence. Players expect fast image rendering, minimal latency, and consistent behavior regardless of device. These needs were implemented through recommendations for efficient memory management, scalable server-side architecture, and a responsive web-based client interface. Considering user needs is critical because software that does not align with user expectations—even if technically sound—will ultimately fail to achieve its purpose.

Approach to Software Design and Future Strategies
My approach to software design involved breaking the problem into manageable components and evaluating each layer independently before considering how they interact as a whole. I relied on architectural patterns such as client-server and RESTful APIs to ensure scalability and maintainability. In future projects, I would continue to use this structured approach while incorporating additional techniques such as prototyping and performance modeling earlier in the design phase. These strategies help reduce risk and improve alignment between technical solutions and business objectives.
