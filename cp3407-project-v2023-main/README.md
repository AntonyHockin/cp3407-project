
# cp3407-project-v2023 template [Delete or change to your team/project name before submitting]

This a project assignment template for CP3407. 
The following is the list of items, which are required to be completed.

## How to submit [You may delete this before submitting]

1. Download your github repository as a zip file and submit via LearnJCU.
2. Add your instructor (JCU-Australia: jc138691@gmail.com Dmitry Konovalov) as a team member to view your project on github

## Team

It is recommended to complete this assignment in a group of 2-4 students.
1. Antony Hockin
2. Joseph Hallows
3. Jack Francis
4. Haakonsolbakke Lier

# Car Rental Website Design Documentation
Welcome to the design documentation our *Yber Rent*. This page provides an overview of the architectural, database, and user interface designs for our website.
*Yber Rent* strives to serve our users with flexibility and high availability. 
  
The architectural design can be broken down into the following key components:
Frontend: A user-friendly web interface built using WordPress' tags, search and filtering to allow customers to search for and rent cars.
WordPress: We utilize WordPress as our content management system (CMS) for managing the content on our website.
Backend WordPress services: These services manage user accounts, car listings accepting, reservations, and payments. Each service is responsible for specific functionalities.
CloudAccess Infrastructure: We host our platform on CloudAccess.net for its robust cloud infrastructure.

## Justification
Our architectural choices focus on ensuring a highly available, reliable, and secure platform. By employing an AWS and WordPress architecture, we can develop, deploy and manage with confidence.

## Database Design
Our database design is structured to accommodate the various data needs of the platform. We use the built-in database in WordPress that takes care of our user data and their listings.

## User Interface Design
### Overview
Our user interface design prioritizes an intuitive and user-friendly experience. 

Key elements include:
Responsive Design: The interface is responsive, providing an optimal viewing experience.
Simple Navigation: An easy-to-navigate menu structure and clear calls to action guide users through the website.
Search and Filter: An efficient search and filter feature enables users to find the right car quickly.
Booking Process: A streamlined booking process minimizes user effort, making reservations straightforward.

## Justification
The user interface design aims to provide an exceptional user experience, enhancing usability, and ensuring users can efficiently find and book cars of their choosing.

## Conclusion
*Yber Rent*'s exemplary architectural, database, and user interface designs are the backbone of a reliable and user-friendly platform. The design choices we have taken are considered to ensure a secure, scalable, and enjoyable experience for both customers and administrators.


# Iterations and Agile Process
Please see [Miro board](https://miro.com/app/board/uXjVMknJr7M=/) for Agile Process



# Version Control
During the development of the Yber Rent webpage, we recognized that the need for version control was minimal. Our approach differed from traditional web development; instead of writing HTML or PHP code from scratch, we opted for efficiency and chose WordPress as our platform. This allowed us to leverage the power of existing plugins and themes, saving time and resources. While code versioning wasn't a priority, our documentation deserved the best, and we turned to GitHub to maintain a thorough record of our processes and changes. For the more visual aspects of our Scrum and Agile development, we relied on Miro, ensuring that our collaborative efforts were well-organized and streamlined. This balanced approach allowed us to focus on delivering a user-friendly and visually engaging website while maintaining transparent and organized project management.


# Building and Development Tools
*Yber Rent* was developed using multiple different softwares and plugins, including:

* WordPress: The main software used to build the site. It's database system also acts as the foundation of our users login / account system. Wordpress has a large variety of plugins that add additional features or change how certain features work. Finally, WordPress comes with many different themes that overhaul the CSS of a site, changing it's look and appearance.
* Rentle: Rentle allows for our site's rental service, providing users with a timeframe to rent from, as well as handling transactions.
* User Registration: The User Registration plugin for WordPress streamlines the process of creating a user login system by providing a user-friendly interface and customizable features, enabling website owners to easily manage user registrations, profiles, and access control with efficiency and precision.
* WP Extended Search: The WP Extended Search plugin significantly enhanced the search feature by enabling it to detect tags on posts, thereby offering users a more comprehensive and accurate search experience, as it now includes tagged content in search results, improving content discoverability.
* Miro: We harnessed the power of Miro for visual collaboration and organization. Miro served as our digital whiteboard, allowing us to visually map out tasks, user stories, and sprint goals. It was an invaluable tool for assigning tasks to team members, tracking progress, and conducting sprint retrospectives. With its versatile canvas, sticky notes, and collaborative features, Miro streamlined our Scrum workflow, fostering transparency and enhancing our team's ability to plan and reflect effectively.
