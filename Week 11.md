The beginning of DevOps!

I was really happy to start DevOps this week and it has not disappointed! 

I've spent some time learning about Docker prior to this and having an understanding of the high-level concepts really helped me to get off to a good start. 

I enjoyed working with someone on Monday who was new to the concept of containerisation - talking through the concepts and helping him to understand consolidated my knowledge and helped me see where I still had grey areas. 

I a team we explored deployment of containers on AWS' Elastic Beanstalk - it was not as easy as I expected and the documentation was very difficult to navigate and understand. It seemed that there were so many variable that needed to be right for us to succeed and we went round and round, finding new ways to get it wrong! 

At our peer check ins every morning we had the chance to speak to people working in other teams, and in talking about our troubles we found that we often held the solutions for each other. This cross-pollination of ideas/solutions was invaluable to get us closer to the goal and in the end I managed to deploy an app on Elastic Beanstalk in three different ways; by building a container withing EB, by uploading a Docker-compose.yaml file on the AWS console and finally by using the EB CLI to create an environment and load the Docker.compose file. 

We spent some time as a group diagramming the routes and components of deployment on EB and also investigating the observability functions of cloudwatch and the AWS monitoring GUI. These are still rather mysterious to me, but hopefully time and experience will resolve this! 

The week was enlightening and has felt like a good (and enjoyable) start to the final section of this course.
