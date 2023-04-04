![iLetters System Overview](https://bit.ly/3ZHyDfV)

### Welcome To The iLetters Project.

A project created to improve the way schools currently communicate with the parents of the learners which is through paper
based newsletters and allow the schools to communicate electronically with the parents via Whatsapp and email.

The backend of the project consists of several microservices built with Laravel, a PHP framework as well as a frontend built with ReactJS, a JavaScript
framework.

You can click on any of the links below to learn more about the microservices or the web application as well as to view the source code 
of the projects.


#### The project is made up of the following microservices:

#### [Aggregator API](https://github.com/MlamliLolwane/AggregatorAPI)

This is the main microservice in which the client communicates with and is responsible for aggregating/combining results from 
all the other microservices before sending the results back to the client.

#### [Contacts API](https://github.com/MlamliLolwane/ContactsAPI)

This microservice is responsible for adding as well as managing the contact details of the parents.

#### [Grades API](https://github.com/MlamliLolwane/GradesAPI)

This microservice is responsible for adding and managing the grades as well as classes the school has i.e. Grade 7A.

#### [LearnerInfo API](https://github.com/MlamliLolwane/LearnerInfoAPI)

This microservice is responsible for adding as well as managing the information of the learner including the names as well as 
the classes the learners are in.

#### [Newsletters API](https://github.com/MlamliLolwane/NewslettersAPI)

This microservice is responsible for composing as well as selecting which grades and classes the newsletters are to be sent to. The Newsletters microservice
is not responsible for the actual sending out of the newsletters.

#### [Schools API](https://github.com/MlamliLolwane/SchoolsAPI)

This microservice is responsible for managing the information of that particular school i.e. the school name as well as the address of the school.
