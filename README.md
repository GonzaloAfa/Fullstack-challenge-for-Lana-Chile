# Fullstack challenge for Lana Chile

In Lana Chile we are thinking about the dream of every Chilean, having his own house.
For this, you will be in charge of building the mortgage simulator that will only operate in Chile. The simulator has to capture information from users and return a simulation at a preferential annual interest rate of 2%.

The data to capture is:

- Name
- Address
- RUT 
- Salary
- Other data that you deem necessary

We need the `RUT` to be valid and the address saved in `longitude` and `latitude` format (see external API’s)

About the simulation, you should use the following formula


![Formula](./b51ba9c282db44073ef0b373f24f5d223c2d8435.svg)



- `M` is the monthly installment
- `P` is the amount of credit
- `r` is the monthly interest rate, which is calculated by dividing the annual interest rate by 12.
- `n` is the number of payments (the number of months you will pay the loan)

Our recommendation is to carry out two projects, one for Backend and one for Frontend.

- For the Frontend: Build the interactions using React or other frameworks that use Javascript
- For the Backend: Create a REST API in `GoLang` that can be connected with your frontend project
- Data has to be stored in a database (ex: PostgreSQL)



## External APIs
To get the data specified above for each address, the applicant shall use these APIs:

➔ Google Maps Geocoding API (https://developers.google.com/maps/documentation/geocoding/intro)

These APIs may only be used via explicit HTTP requests i.e. it is strictly forbidden to
use any API library, wrapper, adapter or SDK​ for them, either official or not.


## The code should:

- Be written as production-ready code. You will write production code.
- Be easy to grow and easy to add new functionality. (example, show differents annual interest rate according to salary)
- Have notes attached, explaining the solution and why certain things are included and others are left out.
- Must be versioned using Git, and published in a private repository at GitHub or GitLab. 
- Users *gonzaloafa* must be given read permission.
- It must include a *README.md* file with instructions for developers e.g. deploy the app, run it on a Linux host or as a Docker container, run the test suite, etc, in a way such that the recruiter can clone the repository and run everything locally.


Good luck!

