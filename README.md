goit-js-hw-01create the repository and clone it to your computer.
goit-js-hw-01folder, create the project structure according to the scheme below.
Attention!
File and folder names and nesting structures must conform to the specified scheme. Otherwise, the work → assignment will not be accepted.
Read each task and perform it in the relevant file.
Make sure your code Prettieris formatted with and you don't get any errors or warnings when opening the live page of the task.
Submit your homework to your mentor on the LMS platform.
Submission Format:  The assignment must contain the source files (code repository link) and GitHub Pagestwo links pointing to the live page on it.
Task 1. Order droids
Perform this task task-1.jsin the file.
The repaired droid sales station is ready to be launched, software needs to be written for the sales department. makeTransactionCreate the function, this function will expect two parameters when called:
 quantitynumber— the first parameter must be one that contains the amount of droids ordered
pricePerDroid— the second parameter numbermust be one that contains the price of a droid
stringComplete the code for the function so that it returns a message about product delivery to the user's country : You ordered <quantity> droids worth <totalPrice> credits!", where:
<quantity>— this is the amount of droids ordered
<totalPrice>— this is the total value of the order, i.e. the total cost of all droids ordered
Take the code below and paste it below to check its accuracy after completing the function. The output of the function will be printed to the console.
console.log(makeTransaction(5, 3000)); // "You ordered 5 droids worth 15000 credits!"
console.log(makeTransaction(3, 1000)); // "You ordered 3 droids worth 3000 credits!"
console.log(makeTransaction(10, 500)); // "You ordered 10 droids worth 5000 credits!"
Leave this code for your mentor to check.
Points to be considered by the mentor during the control:
makeTransaction(quantity, pricePerDroid)Defining the function named
makeTransaction(5, 3000)"You ordered 5 droids worth 15000 credits!"return of the call in the form of
makeTransaction(3, 1000)"You ordered 3 droids worth 3000 credits!"return of the call in the form of
makeTransaction(10, 500)"You ordered 10 droids worth 5000 credits!"return of the call in the form of
Printing the results of all calls to the console
makeTransactionReturns true when called with any valid arguments
Task 2. Product Delivery
task-2.jsDefine a function named . getShippingMessageThis function should take three parameters with the following values ​​when called.
countrystring- The first parameter must be one that includes the country of delivery.
pricenumber- The second parameter should be one that contains the total product cost
deliveryFee- The third parameter numbershould be one that includes the product delivery cost
stringComplete the code for the function so that it returns a message about product delivery to the user's country : "Shipping to <country> will cost <totalPrice> credits", where:
<country>- Delivery country
<totalPrice>- Total order cost including product and delivery cost
Take the code below and paste it below to check its accuracy after completing the function. The output of the function will be printed to the console.
console.log(getShippingMessage("Australia", 120, 50)); // "Shipping to Australia will cost 170 credits"
console.log(getShippingMessage("Germany", 80, 20)); // "Shipping to Germany will cost 100 credits"
console.log(getShippingMessage("Sweden", 100, 20)); // "Shipping to Sweden will cost 120 credits"
Leave this code for your mentor to check.
Points to be considered by the mentor during the control:
getShippingMessage(country, price, deliveryFee)A function named is defined.
getShippingMessage("Australia", 120, 50)returns the response of the call "Shipping to Australia will cost 170 credits".
getShippingMessage("Germany", 80, 20)returns the response of the call "Shipping to Germany will cost 100 credits".
getShippingMessage("Sweden", 100, 20)returns the response of the call "Shipping to Sweden will cost 120 credits".
The call with any valid arguments getShippingMessagereturns true.
Task 3. Item Width
task-3.jsPerform this task in the file.
Define a function named that expects three parameters when called getElementWidth:
content— First parameter is the content width
padding— Second parameter which is the padding value for each edge
border— Third parameter which is the border thickness value for each edge
The values ​​of all parameters Npxwill be in the form of , where N is any integer or decimal number.
Your function should return the total width of the element. When calculating the total width, assume that box-sizingthe value border-boxis .
Take the code below and paste it below to check its accuracy after completing the function. The output of the function will be printed to the console.
console.log(getElementWidth("50px", "8px", "4px")); // 74
console.log(getElementWidth("60px", "12px", "8.5px")); // 101
console.log(getElementWidth("200px", "0px", "0px")); // 200
Leave this code for your mentor to check.
Points to be considered by the mentor during the control:
getElementWidth(content, padding, border)The function named is defined.
getElementWidth("50px", "8px", "4px")Returns the number of calls 74.
getElementWidth("60px", "12px", "8.5px")Returns the number of calls 101.
getElementWidth("200px", "0px", "0px")Returns the number of calls 200.
The call with any valid arguments getElementWidthreturns true.

goit-js-hw-02folder, create the project structure as shown in the diagram below.
Attention! File and folder names and nesting structures must comply with the specified scheme. Otherwise, the job will not be accepted.
Read each task and perform it in the relevant file.
PrettierMake sure the code is formatted with and there are no errors or warnings in the console when opening the mission's live page.
Submit the assignment for checking.
Submission Format: Assignment GitHub Pagesmust include links to source files and .
Mission 1. Droid Orders
task-1.jsPerform this task within
 the process file .
Repair droids sales station is ready to write the software for sales department, all you need to do is to define its function that creates a message about repair droids purchase makeTransaction(quantity, pricePerDroid, customerCredits).
It is defined to take three parameters when called:
quantity- quantity of droids ordered
pricePerDroid- price of a droid
customerCredits- total amount in the customer's account
Complete the function as follows:
Define a variable to store the total amount of the order (the total value of all droid orders) and assign an expression to calculate that amount.
Check if customer can pay the order:
If the amount to be paid is greater than the credit in the customer's account, the function "Insufficient funds!"should return the string.
Otherwise, the function "You ordered <quantity> droids worth <totalPrice> credits!"should return the string , where <quantity>is the amount of droids ordered and <totalPrice>is their total value.
Take the code below, define your function, paste it to check its correctness. The results will be printed to the console.
console.log(makeTransaction(5, 3000, 23000)); // "You ordered 5 droids worth 15000 credits!"
console.log(makeTransaction(3, 1000, 15000)); // "You ordered 3 droids worth 3000 credits!"
console.log(makeTransaction(10, 5000, 8000)); // "Insufficient funds!"
console.log(makeTransaction(8, 2000, 10000)); // "Insufficient funds!"
console.log(makeTransaction(10, 500, 5000)); // "You ordered 10 droids worth 5000 credits!"
Leave this code for your mentor to check.
Points to be considered by the mentor:
makeTransaction(quantity, pricePerDroid, customerCredits)A function named was defined.
makeTransaction(5, 3000, 23000)returns the call  "You ordered 5 droids worth 15000 credits!".
makeTransaction(3, 1000, 15000)returns the call  "You ordered 3 droids worth 3000 credits!".
makeTransaction(10, 5000, 8000)returns the call  "Insufficient funds!".
makeTransaction(8, 2000, 10000)returns the call  "Insufficient funds!".
makeTransaction(10, 500, 5000)returns the call  "You ordered 10 droids worth 5000 credits!".
Task 2. Formatting the Message
task-2.jsPerform this task within
 the process file .
formatMessage(message, maxLength)Declare a function named , which takes a string ( messageparameter) and maxLengthchecks its length against the maximum length (parameter).
Complete the function code as follows:
If the string length maxLengthis less than or equal to , the function returns the original string without modification.
If length maxLengthexceeds , the function maxLengthtruncates the string to characters, adds three dots at the end "...", and returns the shortened version.
Paste the code below after defining your function to verify that it is correct. The results of the operation will be printed to the console.
console​ log (formatMessage( "The device will be taken care of" , 16 )); // "The file will be taken care of..." 
console . log (formatMessage( "The device will be taken care of" , 23 )); // "The system will be taken care of" 
console . log (formatMessage( "The vestibule is not easy either" , 20 )); // "The lobby is easy..." 
console . log (formatMessage( "The vestibule is not easy either" , 30 )); // "The vestibule is not easy either" 
console . log (formatMessage( "But now it's turpis a felis in nunc fringilla" , 15 )); // "But now it's ugly..." 
console . log (formatMessage( "But now it's turpis a felis in nunc fringilla" , 41 )); // "But now it's ugly, but now it's running"
Leave this code for your mentor to check.
Points to consider when reviewing the mentor:
formatMessage(message, maxLength)function was defined.
formatMessage("Curabitur ligula sapien", 16)function call "Curabitur ligula..."returns.
formatMessage("Curabitur ligula sapien", 23)function call "Curabitur ligula sapien"returns.
formatMessage("Vestibulum facilisis purus nec", 20)function call "Vestibulum facilisis..."returns.
formatMessage("Vestibulum facilisis purus nec", 30)function call "Vestibulum facilisis purus nec"returns.
formatMessage("Nunc sed turpis a felis in nunc fringilla", 15)function call "Nunc sed turpis..."returns.
formatMessage("Nunc sed turpis a felis in nunc fringilla", 41)function call "Nunc sed turpis a felis in nunc fringilla"returns.
Task 3. Spam control
Perform the task task-3.jsin the file.
checkForSpam(message)messageThe function called takes a string ( parameter), checks for the presence of forbidden words ( spamand ) in it, and returns the result of the check. The words in the string given as a parameter can be case sensitive, for example or .salemessageSPAMsAlE
Complete the function code as follows:
If the forbidden word ( spamor sale) is found, the function truereturns its value.
If the string does not contain any forbidden words, the function falsereturns its value.
Take the code below and paste it after your function declaration to check if the function is working properly. The results of the execution will be printed to the console.
console.log(checkForSpam("Latest technology news")); // false
console.log(checkForSpam("JavaScript weekly newsletter")); // false
console.log(checkForSpam("Get best sale offers now!")); // true
console.log(checkForSpam("Amazing SalE, only tonight!")); // true
console.log(checkForSpam("Trust me, this is not a spam message")); // true
console.log(checkForSpam("Get rid of sPaM emails. Our book in on sale!")); // true
console.log(checkForSpam("[SPAM] How to earn fast money?")); // true
Leave this code for your mentor to check.
Points that the consultant will pay attention to when checking:
checkForSpam(message)The named function has been defined.
checkForSpam("Latest technology news")return of the call false.
checkForSpam("JavaScript weekly newsletter")falsereturn of call
checkForSpam("Get best sale offers now!")return of the call true.
checkForSpam("Amazing SalE, only tonight!")return of the call true.
checkForSpam("Trust me, this is not a spam message")return of the call true.
checkForSpam("Get rid of sPaM emails. Our book in on sale!")return of the call true.
checkForSpam("[SPAM] How to earn fast money?")return of the call true.
Task 4. Delivery Cost
task-4.jsPerform this task in the file.
countryDefine a function that checks whether product delivery is possible to the user country (as a parameter ) and returns a message about the result getShippingCost(country). switchUse the definitely statement.
The format of the string sent "Shipping to <country> will cost <price> credits"is , where <country>and <price>must be replaced by the corresponding values.
List of countries and shipping costs:
China - 100 credits
Chile - 250 credits
Australia - 170 credits
Jamaica - 120 credits
As can be seen from the list, delivery is not possible everywhere. If the specified country is not in the list, the function "Sorry, there is no delivery to your country"should return the string.
After defining your function, you can check the accuracy of the function by pasting the code below. The results will be printed to the console.
console.log(getShippingCost("Australia")); // "Shipping to Australia will cost 170 credits"
console.log(getShippingCost("Germany")); // "Sorry, there is no delivery to your country"
console.log(getShippingCost("China")); // "Shipping to China will cost 100 credits"
console.log(getShippingCost("Chile")); // "Shipping to Chile will cost 250 credits"
console.log(getShippingCost("Jamaica")); // "Shipping to Jamaica will cost 120 credits"
console.log(getShippingCost("Sweden")); // "Sorry, there is no delivery to your country"
Leave this code for your mentor to check.
Points to be considered by the mentor during the audit:
getShippingCost(country)A function named is defined
switchUsing expression inside a function
getShippingCost("Australia")"Shipping to Australia will cost 170 credits"return of the call
getShippingCost("Germany")"Sorry, there is no delivery to your country"return of the call
getShippingCost("China")"Shipping to China will cost 100 credits"return of the call
getShippingCost("Chile")"Shipping to Chile will cost 250 credits"return of the call
getShippingCost("Jamaica")"Shipping to Jamaica will cost 120 credits"return of the call
getShippingCost("Sweden")"Sorry, there is no delivery to your country"return of the call



