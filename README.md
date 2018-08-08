### Application need to create

#### Create a REST API based back end system for the following application:

Home service marketplace. Where home owner and service provider both will be registered to get and provide services. 

#### API list need to create [microservices like architecture optional]

* Service provider are like plumber, electrician etc. Who will register along with his rate for different type of jobs, area, address details, availability, photo, phone etc. [registration for service provider]

* Home owner will register with area, address, phone etc. [registration for home owner]

* Need to match the service based on any home owner requirement and area/address. It will show matching service provider excluding their phone no and address. [matching service provier list]

* After selecting one service provider. Need to send mail to that service provider about this job along with home owner details. [selection of service provider]

* Need to create another API to make payment [any type] from home owner to service provider. There will be 15% commission of total payment. [payment gateway any type]

* Need another API for review/feedback from home owner for that service holder. [review and feedback]

* Need another API to show the service holders list for a specific area based on revivew, and commission paid to company. [providers list]

### Prerequisit 

Whole application need to keep in Docker container. 
You can use any framework [Laravel, Symfony]. 
Need at least 50% PHP Unit testing of all API. 
Swagger for API documentation. 
Only OOPS and SOLID principal along with PSR code standard required.

### Important

Do not fork this repo.

