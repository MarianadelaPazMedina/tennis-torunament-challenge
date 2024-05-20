<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# Tennis Tournament Challenge Description

## Overview
The goal is to model the behavior of a tennis tournament.

## Requirements
- The tournament format is single elimination.*
- For simplicity, you can assume the number of players is a power of 2.
- The tournament can be either Female or Male.
- Each player has a name and a skill level (between 0 and 100).
- In a match between two players, the skill level and luck influence the decision of the winner. It is your design choice to decide how luck affects the outcome of the match.
- In the male tournament, strength and speed are additional parameters to consider when determining the winner.
- In the female tournament, reaction time is an additional parameter to consider when determining the winner.
- There are no ties.
- From a list of players, the tournament must be simulated and the winner should be output.
- It is recommended to implement the solution in your preferred IDE.
- Good Object-Oriented Programming (OOP) practices will be valued.
- You may define any unclear aspects as you see fit. You can add any clarifications you deem necessary when delivering the exercise.
- Any additional features or extras will be welcomed.
- Layered modeling or Clean Architecture is preferred.
- Delivery of the solution via a version control system (GitHub/Bitbucket/etc) is preferred.

## Important Notes
Single elimination is a tournament system where the loser of each match is immediately eliminated from the competition, while the winner advances to the next round. Rounds are played, and in each round, half of the participants are eliminated until only one competitor remains and is crowned the champion.

### Emphasis
Special emphasis will be placed on the correct modeling and application of good object-oriented programming practices.

## Extra Points
- **Section 1:** Testing the solution (Unit Testing).
- **Section 2:** REST API (Swagger + Integration Testing).
  - Based on a list of players, return the tournament results.
  - Allow querying the results of successfully completed tournaments based on any of the following criteria:
    - Date
    - Male and/or Female Tournament
    - Other criteria you consider relevant.
- **Section 3:** Use a non-embedded database.
- **Section 4:** Deploy the service(s) to AWS/Azure/etc. using Docker or Kubernetes.

## Implementation Notes
- Special emphasis will be placed on the correct modeling and application of good OOP practices.
- Clean Architecture or layered modeling is preferred.
- Version control system (GitHub/Bitbucket/etc) is preferred for solution delivery.


#Domain UML Diagram
<a href="[https://packagist.org/packages/laravel/framework](https://lucid.app/lucidchart/8c5fac1d-5bc0-4c69-8b12-9e92dc8de830/edit?viewport_loc=-1629%2C763%2C3501%2C2022%2CHWEp-vi-RSFO&invitationId=inv_136dec09-7fc0-4070-8618-0fbaffa02bd4)">[<img src="https://img.shields.io/packagist/l/laravel/framework" alt="License">](https://lucid.app/lucidchart/8c5fac1d-5bc0-4c69-8b12-9e92dc8de830/edit?viewport_loc=-1629%2C763%2C3501%2C2022%2CHWEp-vi-RSFO&invitationId=inv_136dec09-7fc0-4070-8618-0fbaffa02bd4)</a>

