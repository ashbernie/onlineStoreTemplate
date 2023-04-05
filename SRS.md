# Software Requirements Specification Document

This serves as a template for each projects' Software Requirements Specification (SRS) document. When filling this out, you will be required to create user stories, use cases, requirements, and a glossary of terms relevant to your project. Each group member must contribute to every section, so it is crucial that your group's GitHub repository shows a commit history that reflects the work of each group member. It is highly recommended that you create separate branches for each member, but since this is one single document, you will need to manually merge the branches together. It is also advisable to have multiple working versions of this document (named separately) so that one person can compile the final SRS document from the multiple working versions. Ultimately, how you go about managing this is up to you, but consistent formatting, clear commit messages, and a thorough commit history with contributions from each group member are required.

Fill the document out following the guidelines listed in each section. Maintain [proper Markdown syntax](https://www.markdownguide.org/basic-syntax/) and be sure that your group has a `main` branch with this document and the entire [template repository codebase](https://github.com/david-gary/onlineStoreTemplate) either forked or downloaded and copied into your group's repository. If you have arranged to use a different codebase as a template, you do not need to have the original template included, but a `main` branch is still required.

## Group Members

* [Ashton Jacobs](mailto: ajacob32@uncc.edu)

## Revisions

When a change is made to the document, a new revision should be created. The revision should be added to the table below with all information filled out.

| Version | Date | Description | Author | Reviewed By |
| --- | --- | --- | --- | --- |
| 1.0 | 03/22/23 | Initial draft | [David Gary](mailto:dgary9@uncc.edu) | [David Gary](mailto:dgary@uncc.edu) |

## Table of Contents

1. [Introduction](#introduction)
2. [Requirements](#requirements)
3. [Constraints](#constraints)
4. [Use Cases](#use-cases)
5. [User Stories](#user-stories)
6. [Glossary](#glossary)

## Introduction

In this section, you should give a brief overview of what your project will be. Describe the software system you are building and what problems it solves. You should also give a short description of the stakeholders (users of the system) and what their needs are. There is no set formatting requirement, but you should maintain a consistent structure across future sections. Not all members must contribute to this section.
    
    My project is going to be an online clothing store that is built off of the template provided to us by David Gary on Github. The store will allow users to view clothing by category and will have a checkout feature so users can "order" clothing items. Users of this software system will have an interest in fashion and will use this site to browse a mock clothing brand.

## Requirements

Each group member must supply at least three functional requirements for the project. Each requirement should be written in the following format:

* **REQ-1:**
  * **Description:** Requirement one will be the homepage of this online store.
  * **Type:** Functional - as it allows users to navigate to different pages.
  * **Priority:** 1 (High priority)
  * **Rationale:** This requirement is important becauase this is the first interaction users have with the website, making first impressions important. 
  * **Testing:** This can be tested by seeing if the user can click on the navigation menu and other buttons linked on the homepage.
  
* **REQ-2:**  
  * **Description:** Requirement 2 will be the shop page and will feature the products that users can buy.
  * **Type:** Functional
  * **Priority:** 1 (High priority)
  * **Rationale:** This is important because without this users will not be able to view products, thus not allowing purchases
  * **Testing:** This can be tested by seeing if a user can click an item and add it to there cart or view the product.
  
* **REQ-3:** 
  * **Description:** Requirement 3 will be the about the brand page and will allow users to read a description of the company and its products.
  * **Type:** Functional
  * **Priority:** 3(Medium priority)
  * **Rationale:** This is not as important as the other but it will allow users to connect with the brand and navigate from a "shop now" button.
  * **Testing:** This can be tested by seeing if a user can view the text(brand summary) and click the shop now button.
  
  * **REQ-4:** 
  * **Description:** Requirement 4 will be the contact us page and will feature a form that users can reach out if they have any questions.
  * **Type:** Functional
  * **Priority:** 1 (High priority)
  * **Rationale:** This is important because users need to be able to communicate with the brand if any issues with "orders" arise.
  * **Testing:** This can be tested by seeing if a user can type in the form boxes and successfully submit the form.
  
  * **REQ-5:** 
  * **Description:** Requirement 5 will be the cart page that will allow users to go view their cart and check out.
  * **Type:** Functional
  * **Priority:** 1 (High priority)
  * **Rationale:** This is important because without this users will not be able to complete part of the transaction. 
  * **Testing:** This can be tested by seeing if a user can click an item and add it to there cart, click the cart icon and be navigated to the cart page.
  
  * **REQ-6:** 
  * **Description:** Requirement 6 will be the checkout page that will allow users to enter card information and complete their order. 
  * **Type:** Functional
  * **Priority:** 1 (High priority)
  * **Rationale:** This is important because without this users will not be able to complete the transaction. 
  * **Testing:** Will be tested by seeing if you can navigate from the cart page to the checkout page, enter card informatiion, submit and then receive an email confirmation(maybe this seems beyond my skillset).
  
## Constraints

Constraints include my ability to create this code, not having a proper host for the website, storing private user information such as their address and credit card information.

## Use Cases

In this section, you should list use cases for the project. Use cases are a thorough description of how the system will be used. Each group member must supply at least two use cases. Each use case should be written in the following format:

* **ID:** A unique identifier for the use case. This should be a number that is unique across the entire document (something like UC-1, UC-2, etc. but be sure to replace the word `ID` with the unique identifier).
  * **Description:** A description of the use case that gives the user a high-level overview of how the system is interacted with.
  * **Actors:** A list of the actors that are involved in the use case. Only include the actors that are directly involved. Actors are the people or things that interact with the system. For example, when ordering at a fast food restaurant, one might have the following actors: the customer, the cashier, and the cook. But only the customer and the cashier are directly involved in the use case of ordering food. The cook is not directly involved in the use case of ordering food.
  * **Preconditions:** A list of the preconditions for the use case. This should be a list of the preconditions for the use case, which are the conditions that must be met before the use case can be executed. Continuing with the restaurant example, the customer must have money in their wallet and the cashier must be logged in to the system before the use case of ordering food can be executed.
  * **Postconditions:** A list of the postconditions for the use case. This should be a list of the postconditions for the use case, which are the conditions that must be met after the use case has been executed. Continuing with the restaurant example, the customer must have their food and the cashier must have the customer's money after the use case of ordering food has been executed.

## User Stories

In this section, you should list user stories for the project. User stories are a short description of how a user will be interacting with the system. Each group member must supply at least two user stories. Each user story should be written in the following format:

* **US-1:** 
  * **Type of User:** Admin
  * **Description:** The administrator, admin for short will be the person who receives the Contact Us page forms and the order submissions from the Checkout page. With the information they receive from the contact us page, they will be able to send customers a response via their email or another software to engage with customers. With the order submissions from the checkout page, the admin will be able to fufill customers orders.
   
  * **US-2:** 
  * **Type of User:** Customer
  * **Description:** This user will be accessing the pages to browse products and make purchases of items they like. Interacting by entering personal data to get clothing items shipped to them.

## Glossary

In this section, you should list any terms that are used in the document that may not be immediately obvious to a naive reader. Each group member must supply at least one term. Each term should be written in the following format:

* **Term:** Cart
  * **Definition:** A button that users can click to view items they have selected and would like to purchase.
