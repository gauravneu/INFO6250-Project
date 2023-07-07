# INFO6250-Project
Web Tools By Prof Yusuf Ozbek
The project is about a retail site that sells Games.

Tech Stack: Springboot, Maven, Hibernate, My SQL, and JSP for front-end

Session Management is done using the HttpSession object
Database transactions are done using Hibernate session object and MySQL is used as a database

Types of Users: 
  1) Guest User
  2) Admin
  3) Registered User
  4) Registered Premium User

What Admin can do:
  Add New Games
  Update Games Quantity

What Guest User Can Do:
  Check all the games available on site but can not buy any game or access the Cart
What Registered User Can Do:
  Check all games, can access the cart and update the cart and place the order but cannot buy the games marked as "Premium"
What Registered Premium Users Can Do:  
  Check all games, can access the cart and update the cart and place the order and can also buy the games marked as "Premium"

  Premium Games: These are games which are newly introduced and are exclusively available only for premium Users to buy
