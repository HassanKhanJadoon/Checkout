**Task Description:**

In this task, you are required to enhance the functionality of a web page that serves as a billing and checkout form for an online store. The web page is built using HTML, CSS (Bootstrap 5), and JavaScript. Your objective is to implement form validation to ensure that users provide all required information correctly before proceeding to checkout. Additionally, you need to implement a promo code feature that provides a discount when a valid promo code is entered.

**Instructions:**

Form Validation:

Ensure that all fields marked with required attribute are filled out before the form can be submitted.
Validate the email address entered in the "Email" field to make sure it follows the correct format (e.g., user@example.com).
Display an error alert if any of the required fields are left empty or if the email address is not in the correct format.
Hide the error alert if all validations pass and allow the form to be submitted.

Country and State Selection:

When the user selects a country from the "Country" dropdown menu, dynamically load the corresponding states for that country in the "State" dropdown menu.
Use the provided countryStates JavaScript object to map countries to their respective states.

Credit Card Payment Validation:

Implement credit card payment validation to ensure that the user provides correct information.
Validate the "Name on Card" field to ensure it is not left empty.
Validate the "Credit Card Number" field to accept only numbers with a length between 13 and 19 digits (allow spaces for readability).
Validate the "CVV" field to accept only 3 or 4 digits.
Validate the "Expiration Date" field to accept only a valid date in the format "MM/YY".
Ensure the expiration date is not in the past (i.e., should not be earlier than the current month and year).

Promo Code Implementation:

Implement the promo code feature by using the provided correctPromoCode variable, which contains a valid promo code ("PROMO_2023").
When the user enters a promo code in the "Promo code" input field and clicks the "Redeem" button, check if the entered code matches the correctPromoCode.
If the correct promo code is entered, apply a 10% discount to the total amount displayed in the cart and show a success message indicating the discounted total.
If the entered promo code is empty or incorrect, display an error message informing the user of an invalid promo code.

Testing:

Test the form validation by submitting the form with empty fields, invalid email addresses, and correct information. Ensure that the error alert displays when necessary and disappears when all validations pass.
Test the country and state selection by selecting different countries and verifying that the corresponding states are loaded correctly in the "State" dropdown.
Test the credit card payment validation by entering incorrect information in the credit card fields and verifying that the appropriate error messages are displayed.
Test the promo code implementation by entering the correct promo code ("PROMO_2023") in the "Promo code" input field and clicking the "Redeem" button. Verify that the discounted total is correctly displayed.
