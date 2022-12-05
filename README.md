# NewHacks-2022

Inspiration

We are all students with busy schedules and we wanted a way to improve our time management and make scheduling our daily lives more convenient. Throughout university we have noticed that unhealthy lifestyle habits are extremely common and overlooked by many students who are negatively affected by their habits. This app seeks to change these habits, by creating robust schedules to account for proper sleep, study, and eating habits, while allocating time for other activities.

What it does

PLAN-ET gives recommendations on how to plan your weekly schedule. Users would first need to sign up or login to the website. They then need to upload their existing calendar.ics files which they can get from any Calendar app such as Outlook or Microsoft teams. At this stage, users will be given a form to fill out, where they would need to fill out the duration of time for essential activities such as sleep, mea and study time. The users can also enter other activities, using the Add Field button. After submitting, our robust algorithm will generate an efficient weekly schedule for you, which you can view on the Calendar we have integrated to our web app.

How we built it

We created a React.js app and allowed users to upload .ics files with their current schedules. We leveraged FileReader and a third-party parser to convert calendar events from .ics into JSON. Then we used moment.js to store and manage date-time information in the JSON. Then the user will input data about their desired lifestyle habits (such as how many hours of sleep they want in a day). A custom-made schedule is then created by our own scheduling algorithm. We use Auth0 to add authentication (SignUp/Login and logout) to the app. We used React’s Material UI and bootstrap to design the Website.

Challenges we ran into

There were lots of edge cases to consider when building the scheduling algorithm and it took a long time to implement. Working with multiple asynchronous events at once in JavaScript was difficult and required a deep understanding of the necessary steps of our program. Outdated and Incomplete Documentation and tutorial for integrating the React app with Auth0. Merge Conflicts

Accomplishments that we're proud of

We are proud that we were able to successfully create a working scheduling algorithm and web app to run it. Clean, simple, and intuitive user interface. Completing a polished and useful product within 24 hours.

What we learned

We learned about how to implement scheduling algorithms based on event priority and a set of existing fixed events. Additionally, we learned what makes a good UI and how to implement one as well as how to manage multiple asynchronous JavaScript function calls and state changes at once. Most importantly, we were able to form a cohesive team and learn to collaborate effectively, overcoming many different technical, design, and time challenges.

What's next for PLAN-ET

In the future, we will be looking to add the functionality of saving the generated schedules to users’ profiles and exporting them in a format that is compatible with external calendar apps like Google Calendar. We would also add a backend database to save the user information so that they can login back to view their schedules in our app and make changes to it.

Try it out: https://fastidious-figolla-0c1320.netlify.app/
Devpost Link: https://devpost.com/software/plan-et
