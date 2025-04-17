# Grocery Shop Management System - Python
This final project is the cumulation of the ENG202 (introduction to engineering) course taken in SP24 at NDU - Louaize.
All Notions taught in the course have been applied in my final project, notably dictionaries, functions & classes, matplotlib, and many more.<br/><br/>
**Main Features:**<br/>
📄 Print receipt to PDF.<br/>
📈 Track trends on most bought items.<br/>
📨 Send receipt by e-mail to client.<br/>

## How It's Made:

▫️**Tech used:** Python, Matlab.<br/>
▫️**Dependencies:** matplotlib, numpy, FPDF, smtplib, EmailMessage.<br/><br/>
⚠️**Super-secret manager credentials:** ADMIN, 12345<br/><br/>
For ease of use, classes for products, clients, and managers have been made seperately, all with their own access & utility functions. When first running, the user is presdented with 2 options, to either log in/sign up as a user, or to log in as the manager.<br/>
By default, the shop comes with no products, so the manager must first fill out a couple, which ends up looking like this:<br/><br/>
![image](https://github.com/user-attachments/assets/0a6d871b-19a7-4da8-b5ab-1e5ea1576e8f)<br/>
<br/>
One can then exit the manager menu and let customers in, which will prompt them for some personal details, all of which will be used later on. The customer can then add, remove from cart (by item or by quantity) which will return the items and their quantities back to the store! and finally check out of the store.<br/>
The receipt template printed to PDF and sent by e-mail looks looks like:<br/><br/>
![image](https://github.com/user-attachments/assets/9f7ba61c-2d78-4ed6-9c45-b0622d128248)

▫️As additional features, the manager can keep track of their customers in the "View Customers" section of the manager menu:<br/><br/>
![image](https://github.com/user-attachments/assets/21048491-a883-4465-9606-2ec404243c54)
<br/><br/>
▫️The manager can also keep track of trends, their most sold items, and recent transactions by checking the graph made with matplotlib in the "Reports and History" section of the manager menu:<br/><br/>
![image](https://github.com/user-attachments/assets/73fed7e3-c6fc-4ea4-8600-4358187f9b01)

