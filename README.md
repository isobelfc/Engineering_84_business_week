# Interview questions and answers
## Questions
### Tell me about yourself
Hi, I'm Isobel. I studied biology at St Andrews, particularly ecology. My dissertation involved using statistical software to model whether a grey seal was foraging or travelling in particular locations based on GPS tag data. I was also heavily involved in a highland dance team throughout university, with training up to five times a week and frequent performances. I enjoyed working with the rest of the team to quickly learn dances and then polish them to performance standard. Since leaving university I have been learning some Python and JavaScript through online courses and enjoy solving problems by applying my existing knowledge in new ways.

### Why Sparta
Reviews talk about good opportunites for growth and development, as well as being very diverse.

### What is Agile and what are the benefits of implementing it
Methodology aiming to reduce the frequency of failed projects by continuously communicating and adjusting, and allowing more changes at a later date. The customer is involved at all stages of the project, improving customer satisfaction. Examples include SCRUM, XP.

### What is SCRUM and what are the benefits of implementing it
A team-based Agile framework to deliver complex systems and products. The use of the Three Amigos approach makes sure that the product owner, developers, and testers are all in agreement of the requirements of the project.

### Where do you see yourself in 2-5 years time
I would like to be a full DevOps Consultant, and working to further develop my skills. Specifically, I'm interested in learning more about automation and gaining skills in that area.

### What is a join?
A join connects two tables on a matched foreign key and primary key. Depending on the join type used, it can return only the data which is shared by both tables, or include all rows from one or both tables even where there is no match in the other.

### What is a primary key and its functions
A primary key provides a unique reference for every row of data in a table. It must not be null or blank, and should not be anything which may change. A composite key is formed from two columns which may each contain duplicates, but form a unique reference when combined. Each table has one primary key.

### What is a foreign key and its functions
A foreign key refers to a primary key from another table containing related data, in order to associate data. Each value in a foreign key column must be present in the primary key of the reference table, but there is no uniqueness constraint and values may be null. A table can contain any number of foreign keys.

### DML
Data Manipulation Language. Manipulate data from within a table.

Functions:
- Select
- Insert
- Update
- Delete

### DDL
Data Definition Language. Defines structure within a database.

Functions:
- Create
- Alter
- Drop
- Truncate

### Normalisation
Normalisation is the process of reorganising data in a database. There are 6 normal forms, although we have only covered 3.

1st Normal Form
- Everything should be atomic
- There should be no repeating groups

2nd Normal Form
- Data is in 1NF
- Plus all non-prime attributes are fully functional dependent on the primary key

3rd Normal Form
- Data is in 2NF
- Plus no transitive dependency, i.e. attributes that are dependent on an attribute that is dependent on another attribute

### Entity Relationship Diagram
An entity relationship diagram displays primary-foreign key relationships between related tables, as well as a list of attributes for each table.

### What is Git and what are the benefits
Git is a version control system. It commits a version of a file, and can rollback to a previous commit if necessary.

### What is Git-hub and what are the benefits
Github is an online repository, which saves files on the cloud, and allows them to be accessed from any system and by multiple users.

### What is OOP and why should we use it
Object oriented programming cuts down on the amount of repeated code

### OOP benefits and use cases

### What is an API and why should we use it
An API allows a user to interact with a system without allowing them to directly edit it

### Python packages and modules - requests module use case with API
Packages are collections of functions that are not part of the base Python selection, but are written by a user and shared with other users

### What is pip

### What are the four pillars of OOP and why should we use them. Include use cases
Abstraction 
- It is not necessary for the user to understand exactly how everything works, only how to perform the tasks they need
- A person driving a car does not need to know how the engine works, only how to drive

Encapsulation
- Allows for some data to be made private
- For example, a user's name might be public, while their date of birth remains private and only accessible in a few contexts

Inheritance
- A class can inherit attributes and methods from a parent class, allowing it to have additional attributes and methods without rewriting those from the parent class
- E.g. a class Animal may contain an attribute setting `alive` to True, and a method `breathe`. If the class Mammal has Animal as a parent class, it will have access to those attributes and methods

Polymorphism
- The inherited attributes and methods can be overwritten
- E.g. the Reptile class may set `limbs` to True, but the Snake class overwrites that to set `limbs` to False

### What is DevOps
Integration of Development and Operations, as a lack of effective collaboration between those two teams would lead to increased errors. By combining them, communication is improved, and the development lifecycle is shortened and streamlined.

### Why do you want to become a DevOps Engineer/Consultant

### Explain the role of a DevOps Engineer/Consultant

### What is cloud computing and why should we use it
The delivery of services over the internet. It helps to save on cost, as it means it is not necessary to run data centres on site. It also saves on setup time, and allows us to access the resources from any location. Data can be backed up in multiple locations, and many cloud providers offer extensive security options, which helps to protect data and infrastructure.

### Explain how you implemented DRY/OOP/MVC/MVT (use STAR)
In our DevOps training, we had to complete a group project focused on an airport terminal. We had to code a program that was capable of tasks such as creating a new passenger and saving them to a passenger database. To do this we used Object Oriented Programming, and created a Person class, and a Passenger class which inherited from it. From there, we could ensure that each passenger contained certain properties, such as first and last name and passport number, and also use these to perform functions such as adding a passenger to a flight.
