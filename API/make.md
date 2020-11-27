API Developer Test
==================================

# Coding Test

We need an API to interact with it's Store and Customer data. Create API's in nodejs with any framework with mysql/postgres as the database. Create a React Frontend for any of the listed API's

## Task requirements

- The objective of the test is to showcase the coding skills. The following key aspects are expected
   1. Code Clarity
   2. Reusability
   3. Errors/Exception Handling
   4. Standard Coding practices followed
- All stories to be completed with an appropriate level of testing.
- Feel free to use whatever testing, mocking or stubbing frameworks you prefer, along with any other packages you like.
- Your code should be of production quality.
- Provide a Postman collection to interact with your API
- Provide any documentation / planning you carried out
- Dataset can be found in the `dataset` directory


## User stories

### Story 1 - Retrieving a Store by ID
As a **API consumer**
I want to **retrieve a stores details by a stores ID**
So that **I can view the store details**

#### Acceptance criteria

* Accept Store ID as a parameter
* Return all Store details for the requested Store ID

---

### Story 2 - Retrieving list of Stores

As an **API consumer**
I want to **retrieve a list of stores with id's and names**
So that **I can view the list of stores**

#### Acceptance criteria

* Return all Stores. Only Store ID and Store Name

---

### Story 3 - Update a Store

As an **API consumer**
I want to **update any data belonging to a particular store**
So that **I can update any store details as and when required**

#### Acceptance criteria

* Able to update any data for a Store
* Requested Update Data is validated (best guess)
    * Informative &amp; relevant error message returned for invalid data
* Requested Update Data is sanitised
* Requested Update Data is formatted

---

### Story 4 - Retrieving list of Stores w/ total customers count

As an **API consumer**
I want to **retrieve a list of storex along with their total customers count**
So that **I can view how many customers each store has**

#### Acceptance criteria

* Return all Stores. Only Store ID, Name and Total Customer count

---

### Story 5 - Retrieve a Stores Customers

As an **API consumer**
I want to **retieve a list of all the customers belonging to a particular store**
So that **I can see which customers the store has**

#### Acceptance criteria

* Return a list of Store Customer. Only firstname, lastname, Email.
* Only display the customers for the given Store

---

### Story 6 - Create a Customer

As an **API consumer**
I want to **create a customer for a particular store**
So that **added customers to my database**

#### Acceptance criteria

* Ability to create a customer (all data)
* Must not create customer unless firstname, lastname, email and store id are present and valid.
* Requested Create Data is validated (best guess)
    * Informative &amp; relevant error message returned for invalid data
* Requested Create Data is sanitised
* Requested Create Data is formatted

---

### Story 7 - Search for Store

As an **API consumer**
I want to **search a store by name**
So that **I find the a store if it exists**

#### Acceptance criteria

* Ability to search partial name or full name of Store
* Maximum of 5 results returned.
* Return Store id and name

---

### Story 8 - Authentication

As an **API provider**
I want to **ensure only authorised user can access my API**
So that **my data is protected and secure**

#### Acceptance criteria

* Unauthorised requests should return denied when attempting to access to any endpoint
* Authorisation requested should return the expected response

---

### Story 9 - Database Optimisation

As an **API Provider**
I want to **ensure my database is optimised**
So that **performance is faster for my api consumers**

#### Acceptance criteria

* Optimised for performance



# Technical questions

Please answer the following questions in a markdown file called `Answers.md`.

* What would you add to your solution if you had more time?
* What's your favourite programming language? Why?
* How would you track down a performance bottleneck in an application? Have you ever had to do this?
* How would you deploy your API in a production environment?
* Please describe yourself using either XML or JSON.


Thanks for your time, we look forward to hearing from you!
