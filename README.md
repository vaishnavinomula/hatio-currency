# hatio-currency
# Hatio_currency_converter
Challenge: Currency Converter API Integration 
Objective: 
Build a Spring Boot application that integrates with a public API to provide real-time  currency conversion functionality. 
Requirements: 
1. Fetch Exchange Rates: 
Use a public API (e.g., Exchange Rates API or Open Exchange Rates) to fetch real time currency exchange rates. 
2. Endpoints: 
Implement the following REST endpoints: 
a. GET /api/rates?base=USD 
Fetch the exchange rates for the given base currency. Default base should  be USD if not provided. 
b. POST /api/convert 
Convert an amount from one currency to another using the fetched  exchange rates. 
Request Body: 
{ 
 "from": "USD", 
"to": "EUR", 
 "amount": 100 
}
Response: 
{ 
 "from": "USD", 
 "to": "EUR", 
 "amount": 100, 
 "convertedAmount": 94.5 
} 
3. Error Handling: 
Handle cases where: 
a. The external API is unavailable. 
b. Invalid currency codes are provided. 
4. Testing: 
Write basic unit tests for the service layer using JUnit. 
Constraints: 
1. Use Spring Boot to build the application. 
2. Dependency management with Maven. 
3. Keep the solution simple and focused on clean code and best practices. 
Deliverables: 
1. A fully functional Spring Boot application with a clear structure. 2. Instructions to run the application locally (README file). 
3. API documentation. 
4. Git repository containing the code. 
Assessment Criteria: 
1. Code quality, structure, and readability. 
2. Use of best practices in Java and Spring Boot.
3. Correctness and completeness of the implementation. 4. Error handling and robustness. 
5. Basic testing coverage.

}
