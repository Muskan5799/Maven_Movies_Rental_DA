# Maven_Movies_Rental_Business_DA
Data analysis of movies CD/DVD rental (transactions) and inventory

# Maven Movies Data Analysis: Enhancing Insights for a Rental Business
### Project Overview:
This project analyzes a movie rental business's database to provide actionable insights for improving operations, marketing strategies, and inventory management. The dataset is hosted in the MAVENMOVIES database, and SQL was extensively used for exploratory data analysis (EDA), schema understanding, and answering business-critical ad-hoc queries.

### Project Objectives:
Customer Insights:
Identify customer details (names, emails) for targeted marketing campaigns. Analyze customer rental patterns to improve customer engagement.

### Movie Inventory Analysis:
Explore the rental inventory and classify movies based on rental rates and availability. Provide recommendations for expanding the movie collection based on popularity and rental rates. Revenue Optimization:

Analyze rental rates to identify trends and the profitability of various pricing categories. Determine the most rented movie categories and ratings to maximize revenue.

### Operational Efficiency:
Help track and manage movie inventory effectively. Highlight gaps in the inventory and optimize stock levels.

# Tools & Library Used
![My SQL Logo](https://github.com/user-attachments/assets/b2a6ff0a-4325-4de3-8676-2f779d686ab4)

# Project Result
[Click here to get full code](https://github.com/Muskan5799/Maven_Movies_Rental_DA/blob/main/MOVEIS_RENTAL_CODE.SQL.sql)

(1)  You need to provide customer firstname, lastname and email id to the marketing team 
![Q1](https://github.com/user-attachments/assets/9971d02f-f033-449e-adfe-91d31bcbffbf)

(2)  How many movies are with rental rate of $0.99?

![Q2](https://github.com/user-attachments/assets/f692f73c-1c50-40dd-b987-34deb3bb7688)

(3) We want to see rental rate and how many movies are in each rental category

![Q3](https://github.com/user-attachments/assets/88d54523-4e4d-44bb-a0b3-23ec9e2fb62e)

(4) Which rating has the most films? 

![Q4](https://github.com/user-attachments/assets/ed1f48e4-e6a6-4a9b-a431-3474ae28b54d)

(5) Which rating is most prevalant in each store?

![Q5](https://github.com/user-attachments/assets/a2a5be31-c215-47c2-b0a5-3d1f629234b1)

(6) List of films by Film Name, Category, Language

![Q6](https://github.com/user-attachments/assets/e712660f-578b-4794-bd8c-2d061720526a)

(7) How many times each movie has been rented out?

![Q7](https://github.com/user-attachments/assets/33dae189-3731-4c54-bc6b-f44affeec4b9)
 
(8) REVENUE PER FILM (TOP 10 GROSSERS)

![Q8](https://github.com/user-attachments/assets/f5c9e5ee-2cb9-4177-9ca4-151c66e15be5)

(9) Most Spending Customer so that we can send him/her rewards or debate points

(10) Which Store has historically brought the most revenue?

![Q9](https://github.com/user-attachments/assets/f47c281e-3915-4c63-8158-6d2f95bc2f8b)

 (11) How many rentals we have for each month

 ![Q10](https://github.com/user-attachments/assets/0649613d-717e-4433-94c6-8b868f4707b1)

(12) Reward users who have rented at least 30 times (with details of customers)

![Q11](https://github.com/user-attachments/assets/bf07619e-14a6-453d-92ed-f7509e154217)

(13) Could you pull all payments from our first 100 customers (based on customer ID) 


(14) Now I’d love to see just payments over $5 for those same customers, since January 1, 2006

![Q13](https://github.com/user-attachments/assets/f4fbf3bd-542a-42b0-8910-5fc5850ca6eb)

(15) Now, could you please write a query to pull all payments from those specific customers, along
     with payments over $5, from any customer?


(16) We need to understand the special features in our films. Could you pull a list of films which
     include a Behind the Scenes special feature?

![Q15](https://github.com/user-attachments/assets/6c4fad19-b284-4718-be14-ad3c3f98a936)

(17) unique movie ratings and number of movies

![image](https://github.com/user-attachments/assets/61b8ec18-490a-47ce-b819-dac9c963e4e7)

(18) Could you please pull a count of titles sliced by rental duration?

![image](https://github.com/user-attachments/assets/d1f08aae-e419-46dd-9fdb-1016ed8b5522)

(19) RATING, COUNT_MOVIES,LENGTH OF MOVIES AND COMPARE WITH RENTAL DURATION

![Q18](https://github.com/user-attachments/assets/074a021d-d84f-488f-9fc2-95647c92bae3)

(20) I’m wondering if we charge more for a rental when the replacement cost is higher.
     Can you help me pull a count of films, along with the average, min, and max rental rate,
     grouped by replacement cost?

![Q19](https://github.com/user-attachments/assets/06c247b1-b928-4236-92e6-e83d85110a22)

(21)  “I’d like to talk to customers that have not rented much from us to understand if there is something
      we could be doing better. Could you pull a list of customer_ids with less than 15 rentals all-time?”

![image](https://github.com/user-attachments/assets/90b2a7cc-0c63-47cf-816c-1d8b468ad43a)

(22) “I’d like to see if our longest films also tend to be our most expensive rentals.
      Could you pull me a list of all film titles along with their lengths and rental rates, and sort them
      from longest to shortest?”

![image](https://github.com/user-attachments/assets/070153d5-8ecd-4fc3-9e13-3910f07febc0)

(23) CATEGORIZE MOVIES AS PER LENGTH

![image](https://github.com/user-attachments/assets/1b0e1cab-de5f-4982-89b3-b50a1be85684)

(24) CATEGORIZING MOVIES TO RECOMMEND VARIOUS AGE GROUPS AND DEMOGRAPHIC

![Q20](https://github.com/user-attachments/assets/135e0426-e92d-4929-ad66-f1dbcf7d115b)

(25) “I’d like to know which store each customer goes to, and whether or
      not they are active. Could you pull a list of first and last names of all customers, and
      label them as either ‘store 1 active’, ‘store 1 inactive’, ‘store 2 active’, or ‘store 2 inactive’?”

![image](https://github.com/user-attachments/assets/1bf5e1d4-a830-4f6c-97be-9c2e97fa42cd)
      
(26) “Can you pull for me a list of each film we have in inventory?
     I would like to see the film’s title, description, and the store_id value
     associated with each item, and its inventory_id. Thanks!”

![image](https://github.com/user-attachments/assets/15997dc1-48ec-455d-861c-7393ac5c770c)

(27) Actor first_name, last_name and number of movies

![Q23](https://github.com/user-attachments/assets/da921f32-9461-429a-98b4-a5469f608582)

(28) “One of our investors is interested in the films we carry and how many actors are listed for each
     film title. Can you pull a list of all titles, and figure out how many actors are
     associated with each title?”

![Q24](https://github.com/user-attachments/assets/f505f306-78d7-464a-8aae-1700509a566f)

(29) “We will be hosting a meeting with all of our staff and advisors soon. Could you pull one list of all staff
 and advisor names, and include a column noting whether they are a staff member or advisor? Thank 

![Q27](https://github.com/user-attachments/assets/2c37a44d-5522-4607-8a2c-512ae38a07b8)













 









