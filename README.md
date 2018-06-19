
# Candidate Test

This candidate test is a way for us to gain insights into your skills. This means there is no "correct" solution. We'll schedule an interview after the review where you'll present the solution and we'll have a discussion about it.

## The Task

Sendify's core offering is a service where customers can search, compare, book and track shipments of goods (consignments) between two geographical locations all over the world.

When a customer wants to book a consignment, they use our web interface to enter the dimension and weight of the package they want to send. The web interface will then send a request for shipment proposals to our backend. 

Your task is to build a service that could serve these requests for shipping proposals. You don't need to create a web UI but some suitable way of demonstrating a request, e.g. via a simple script that makes a call with some test data.

Using layering methodology to allow switching between different database implementations (e.g. RAM or MongoDB), would be a plus but in no means necessary!

### Requirements

- The requests contains:
    - Origin address.
    - Destination address.
    - Type (letter, package, pallet).
    - Package dimensions (width, height, length).
    - Package weight.
- The responses contains:
    - A list of shipping proposals
        - Shipping proposal 
            - Carrier 
            - Product
            - Price
            - Expected transit time
- The application service must be implemented as a Docker image.
- Write your solution in Python.
- A test framework, full test coverage is not a requirement but a plus.
- Whatever else you deem necessary for a maintainable solution that supports multiple developers.

## Submission

Put your solution in a GIT repository and send the link to david@sendify.se.
Looking forward to your solution!