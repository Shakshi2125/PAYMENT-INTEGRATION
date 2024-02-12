Razorpay Payment : https://shakshi2125.github.io/PAYMENT-INTEGRATION/

This project is a simple web application for integrating Razorpay payment functionality into a web page. It consists of three main components:

1. HTML :

This file contains the structure of the web page.
It includes input fields for entering the payment amount and customer's name.
It also includes a button to initiate the payment process.

2. CSS :

This file contains the styles for the HTML elements, providing visual design and layout to the web page.
It defines the appearance of the button, product and container layout.
The styles are written to ensure the web page is responsive and displays correctly on different devices.

3. JavaScript :

This file contains the JavaScript code responsible for handling the Razorpay payment integration.
It defines a function initiatePayment() that is called when the "Pay Now" button is clicked.
Inside the initiatePayment() function:
- Payment options are configured, including the Razorpay API key, payment amount, customer details, and payment description.
- A new instance of Razorpay is created with the provided options, and the payment form is opened.
- Upon successful payment, a callback function is executed, displaying an alert with the payment ID.
