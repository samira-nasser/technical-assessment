# technical-assessment

## 0. What systems do you normally work in? Are you familiar with Jira and Confluence? Additionally, could you describe the tools you typically use in your daily work?
`Yes sure we are working everyday and following up our tasks on Jira board, write and get our services documentation from confluence and will list every tool i am using it for daily work.`
- **Jira**: We are using jira for creating our subtasks plus breaking down the epics (user stories) also following up everyone what he is doing and which the tasks that i can pick from it once finish my tasks.
- **Confluence**: We are using it to add the services documentation and make on it the POCs or something like documentation for every service to be used as a reference for us or for any new comer.
- **VSCode**: a code editor redefined and optimized for building and debugging modern web and cloud applications.
- **Docker Desktop**: we are using docker Desktop to provide the ability to package and run our application in a loosely isolated environment called a container.
- **github**: we use github to contribute to our application services repositories and allows us to create, store, manage and share our code branches and open PRs to be reviewed then merge it with the main then deploy it by drafting new release by adding new tag and start running the needed workflow based on which environment we need to deploy on it (test,stg or prod).
- **Postman**: we are using postman for testing our APIs so it allows creatiing better APIs—faster.
- **DBeaver**: it is a database tool for working with data. It supports all popular SQL databases like MySQL, MariaDB, PostgreSQL, and more. we using it to check database tables and for tracing or debugging an issue related to hte data or checking if data exist so DBeaver is a universal database management tool for everyone who needs to work with data in a professional way.
- **ArgoCD**: we use it for tracking deplyed services versions if updated for last version based on last release or not to make sure that the deployment is completed plus checking on it the logs for services if something happened and we need to debug it .
-  **AWS-SSM*: it is a management service that helps us to save or store our environment variables and our secrets for test,stg,prod environments.
-  **datadog**: it is a tool for tracing or checking the logs for the running services for debugging and checking application performnce and need to be integrated and configured for our service to can run it.

## 1. Are you acquainted with the SOLID principle? If so, could you provide a brief explanation?
`Yes sure, They are a set of rules and best practices to follow them while designing a class structure. So all the time we are trying to follow and achieve it as I believe that it is a topic that every developer should learn`
- **The Single Responsibility Principle**: states that a class should do one thing and therefore it should have only a single reason to change.
- **The Open-Closed Principle**: requires that classes should be open for extension and closed to modification.
- **The Liskov Substitution Principle**: states that subclasses should be substitutable for their base classes.
- **The Interface Segregation Principle**: states that many client-specific interfaces are better than one general-purpose interface. Clients should not be forced to implement a function they do no need.
- **The Dependency Inversion Principle**:  states that our classes should depend upon interfaces or abstract classes instead of concrete classes and functions.

## 2. What is Next.js, and how does it differ from Express? Can you discuss the concept of convention over configuration in relation to Node.js frameworks?
 `Next.js is a React framework for building full-stack web applications so it enables you to create high-quality web applications with the power of React components. It's not just a frontend or a backend framework; it's a blend of both, providing a comprehensive solution for building web applications.`
 - **next.js and express.js**: are two different frameworks that are used to build different sets of applications. While ExpressJs is a Node. js-based web application framework to build APIs and server-side applications, NextJs on the other hand is a react-based framework used for creating static websites and SEO optimizations. So Express is a minimalistic and flexible framework suitable for building lightweight and highly customizable web applications, while Next. js excels at server-side rendering and static site generation, making it a great choice for complex React-based applications.
 - **convention over configuration in Nodejs**: Node.js frameworks typically offer pre-built modules and libraries, equipping developers with a unique collection of reusable code that can solve common issues without reinventing the wheel. Following the "convention over configuration" principle, Node.js frameworks reduce the number of challenging decisions a developer has to make, thereby accelerating development cycles.

## 3. Could you explain what an event loop and event emitter are in the context of Node.js?
`Event loops, and event emitters are all important concepts in Node.js that work together to make it a powerful and efficient language.`
- **Event loop**: The event loop is a core part of Node.js that allows it to handle a large number of requests and events simultaneously. The event loop is a continuous loop that listens for events and executes the corresponding callback functions when those events occur. Events can include things like user input, network requests, and file system operations. When an event occurs, the event loop checks if there is a corresponding callback function attached to that event. If there is, the callback function is executed, allowing the program to respond to the event. If there isn’t, the event is simply ignored. The event loop ensures that the program remains responsive and can handle multiple requests and events at the same time.

- **Event emitter**: The event emitter is a built-in module in Node.js that allows you to create custom events and attach callback functions to those events. The event emitter provides a way to communicate between different parts of your program by allowing you to trigger custom events and execute functions in response to those events.

## 4. How would you go about identifying and addressing performance issues in a Node.js application?
`By debugging and deep testing we can catch any performance issue, So improving the performance of a Node.js application requires a multi-faceted approach that includes identifying and addressing performance bottlenecks, optimizing database queries, utilizing caching, reverse proxies, and load balancers, taking advantage of multiple cores, monitoring and tuning the application, and using best practices for development and deployment. For example using a profiler to identify performance bottlenecks or Using a production-ready web server like Express or Koa, instead of the built-in http module`

## 5. If an application suddenly experiences a slowdown or unresponsive behavior, what steps would you take to investigate and rectify the issue? Would you consider utilizing profilers and visualizing metrics in tools like Grafana?

