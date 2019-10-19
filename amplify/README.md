# AMPLIFY


- Amplify - Business Amplified - 

- Amplify is designed to be marketed towards small business owners or persons in need of a web presence. It is a fact that in todays world that to be profitable and achieve any growth in today's market, some sort of web presence is imperative. Especially for a small business to try and stay afloat in a veritable sea of sharks in the form corporations and an overflooded market full of competing enterprise. The service we provide with Amplify is a vital one for any entrepreneur seeking a drastically simpler method of marketing and increasing overall total business through this unique and custom tailored web application.  

- Initially available via deployment through Heroku, it is designed and written using React. At its most basic layout, Amplify consists of an initial home website with information regarding the business i.e Bio's, About Info, Descriptions of services offered, location provided by the Google Maps API, a chat function run using Socket IO, contacts, customer reviews, FAQs, links to sign up/in to a profile/Admin page.

- Once the user/Admin has selected to login they will be taken to another page where they can enter their email and password which will be validated and checked against the data provided upon sign up stored in a MongoDB database. 

- After validation they will be taken to a "Services" page where customers can book appointments, request services, and see what is available. They will then be given the option to pay online using the Square API, or pay at the time of their appointment. Appointments booked will be added to a table that contains their user.name / a description of the service requested / date & time of appt. / and cost.
This table will be managed by GET, POST, & CRUD functions powered by an Express server. Admin will also be given special privileges on this page and the ability to control certain functionality.

- These will be the three main components of Amplify with further customization and additional page options available upon request.
