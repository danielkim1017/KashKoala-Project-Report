# KashKoala-Project-Report

KashKoala Stock Trading (Created April 29th, 2022)

// All documentation and diagrams (use case, sequence, state-machine, entity-relationship, system architecture, and project WBS) are found in this PDF:
https://docs.google.com/document/d/14VNryO_FDjhSeN5MSGsNunELIfZPyB6zEL7e0knjivI/edit

Group Members: 
Daniel Kim, Harrison Elliot, Rawin Bunajinda, John Antony 

Problem Definition:
Our client, KashKoala, is a company that allows users to send and receive money to and from other users (similar to Venmo or Cash App). The company wants to incorporate a trading platform for its users so they can buy and sell stocks with the money in their accounts. This would draw new users to their app to trade, and incentivize new and existing users to increase the amount of money in their accounts to buy and sell stocks.

Users need a secure interface to track their stock investments. We need to provide an interface for the customers to add/withdraw/transfer money. This application tracks the prices of stocks and provides information on stock prices to customers. 

Requirements for a customer to register with KashKoala: 18 years of age, $500 minimum amount of money. 

Problem Objective:
We will take an incremental approach to meet each individual objective as we go further into the project. 
The first objective is a registration form that tracks user information along with username and password (Expected by the Middle of March).
The second objective is a working program that allows users to log in. The program will display the current balance and allow users to deposit and withdraw money (Expected by the End of March).
The third objective allows users to buy, sell, and track shares of stock with the money in their account. The updated program will display users' current holdings (Expected by the End of April).
April 29 - Finished Product, Documentation, and Presentation

Stakeholder List:
The client (KashKoala)
Those using the app already (customer)
The bank
Market maker
The government

Success/Acceptance Criteria: 
The client will base success on secure access for users.
Users will base success on their ability to buy, sell, and track stocks through KashKoala.
The bank, the market makers, and the government will base their success on accurate information being portrayed; i.e. accurate stock prices.

Github Link:
https://github.com/helliot01/KashKaola

Conclusion: Our group learned a lot about time management, collaboration, and delegation. It was hard to code collaboratively, while also trying to merge ideas, styles, and conceptions about our project. Once we got into a rhythm with meeting each other, we were able to hit all of our deadlines successfully and reach a level in our project that we were all happy with. Although our project proposal listed three iterations of the project, in practice, a fourth iteration was included. This fourth iteration was a step in between the second and third iterations listed and was an iteration that included all of the functionality listed in the previous iteration, while also adding the ability to add friends and send money to them. A lesson we learned was that we should have spent more time figuring out how to split our class up into smaller classes. Ideally, we would have had one class for the login/registration screen, one class for the home screen, one class for the portfolio screen, and likely an additional class for the reading/writing of files that we used. There were certain roadblocks we faced when trying to split our code up this way, mainly revolving around issues with JFrames and JPanels and getting them to work properly across multiple classes. Although we have a working product, due to the nature of our code being in one large class, it can be difficult to look over. Another roadblock we faced was trying to get a legitimate credit card payment system working. Our final version of the product allows users to add money to their accounts without actually checking with a bank to make sure the user has the amount they are trying to add. Lastly, our code uses multiple text files to store user information, friend information, and portfolio information. This method was used because Java includes easy implementation when it comes to reading and writing files. Ideally, we would’ve liked to incorporate a more robust method for storing user data, but our solution was viable for our needs and works properly.  

Reference:
https://financequotes-api.com/ (Yahoo Finance API Integration)
https://docs.oracle.com/javase/8/docs/api/index.html (Java Documentation for JFrame, JPanel, etc.)
https://robinhood.com/us/en/support/articles/how-robinhood-makes-money/
https://cash.app/help/us/en-us/5007-buying-stock


