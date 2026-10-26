# Draw-It-or-Lose-It-Software-Design
Software design for a multiplayer web game, covering object-oriented design, platform evaluation, distributed systems, storage, memory management, and security.

# Draw It or Lose It: Software Design

**Course:** CS 230: Operating Platforms

**Author:** Paul Silva

## Project Overview

This repository contains the software design document I developed for The Gaming Room as part of an academic project. The document outlines requirements, design constraints, an object-oriented domain model, platform comparisons, and architectural recommendations for expanding Draw It or Lose It into a web-based application.

## Client and Software Requirements

The Gaming Room wanted to expand its existing Android game, Draw It or Lose It, into a web-based application accessible across multiple operating systems and devices. The application needed to support multiple games, teams, and players while maintaining unique game and team names and unique identifiers. The design also needed to address scalability, consistent game information, and secure communication between clients and the server.

## What I Did Particularly Well

I clearly connected the client's requirements to the proposed software design. I explained how inheritance could reduce duplicate code and how the Singleton and Iterator patterns supported managing game instances and checking for existing names. I also compared operating platforms and provided recommendations covering Linux hosting, persistent storage, memory management, networking, and security.

## How the Design Document Helped With Development

Working through the design document helped me organize class responsibilities and relationships before implementing the code. Defining the relationships between games, teams, and players made the application structure easier to understand. Documenting constraints also helped me consider issues beyond individual classes, such as how users would access the application and how shared game information would be maintained.

## What I Would Revise

I would improve the explanation of how game state would remain consistent across multiple server instances. A Singleton provides one shared instance within an application process, but it does not enforce uniqueness across an entire distributed system. I would clarify how database constraints and transactions would support unique names and consistent updates as the application scales.

## Interpreting and Addressing User Needs

I translated the client's needs into requirements for cross-platform access, unique names, and organized relationships between games, teams, and players. I recommended a browser-based client so users could access the game from different devices without requiring a separate application for each operating system. Considering user needs is essential because a technically functional system must also be accessible, reliable, and useful to its intended audience.

## My Approach to Software Design

I started by identifying the client's requirements and constraints, then used the domain model to organize the application's classes and responsibilities. I compared platform options before recommending an architecture suited to the application's needs. For future projects, I would continue using requirements analysis, domain modeling, and platform comparisons while adding small prototypes and measurable performance tests to validate important design decisions.

## Skills Demonstrated

- Software requirements analysis
- Object-oriented design and design patterns
- Operating platform evaluation
- Client-server architecture
- Storage and memory management planning
- Security and scalability considerations
- Technical documentation
