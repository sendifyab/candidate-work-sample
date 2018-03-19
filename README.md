# Candidate Test

This candidate test is a way for us to gain insights into your skills. This means there is no "correct" solution. We'll schedule an interview after the review where you'll present the solution and we'll have a discussion about it.

The task your assigned in this test is a potential real world problem you might work on as a developer at Sendify.

## The Task

Sendify's core offering is a service where customers can search, compare, book and track shipments of goods (consignments) between two geographical locations all over the world.

When a customer wants to book a consignment, they use our web interface to enter the dimension and weight of the package they want to send. The web interface will then send a request for shipment proposals to our backend. 

Your task is to build a service that could serve these requests for shipping proposals.

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
- Provide a suitable way of demonstrating your service.
- The project must contain a README including instructions how to run your service.
- Write your program in Python.

NOTE: This is a work sample test, while you're creating the project imagine it would actually be used (and maintained) in a production environment.

## Submission

Submit your solution by sending a link to the GIT repository in an email to david@sendify.se.
Looking forward to your solution!