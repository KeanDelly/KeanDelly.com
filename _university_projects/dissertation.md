---
layout: "project"
title: "Optimisation of Cargo Ship Decks"
year: 2024
technologies: [Python, Github, Google Scholar]
blurb: "My University Dissertation: The Optimisation of Cargo Ship Decks using a Multi Objective Genetic Algorithm"
---          

## Overview
This Project consisted the largest piece of work completed for my University degree. In it, I researched, designed and developed a system to optimise the structural design of a cargo ship's deck using a Multi-Objective Genetic Algorithm(MOGA). To do this, research was conducted into Evolutionary Algorithms(EA) as an optimiser, and Cargo Ship Strucural design for the creation of the problem domain.  After deciding to use a Multi-Objective Genetic Algorithm, an initial implementation against a set of benchmark problems were used to confirm confidence in the MOGA. The cargo ships problem domainwas then created and the initial implementation adapted to suit it. For the problem domain, the factors of weight, cost and strength were chosen to drive optimisation. Following development of the main system, testing to evaluate its effectiveness was undertaken. This involved evaluating the optimisation parameters through sensitivity testing, alongside the demonstration of the algorithm to optimise by diffrent materials, dimensions and layouts. 

## Key Features

- The Ability to optimise the structural design of a cargo ships deck
- User customisable dimensions
- Material dictionaries for the consideration of all options in design
- Stored output for reusability and design comparison
- 3-dimensional graph of design qualities generated on program completion

## Technologies Used

- Python
- Git & Github
- Google Scholar

## Challenges and Solutions

The largest challenge faced during this project was that of the problem domain. More specifically how to represent a cargo ship's deck programatically, and calculate it's characteristics such as cost, weight and strength. After experimentation with multiple methods, it was decided that the deck design should be represented by a number of latitudinal and a number of longitudinal beams, alongside a plating material. Altough simplistic, this had the benefit of being more inline with the acutual construction process of a ship. 

To calcualate the cost and weight of the ship, a summation model was used. Cost was calculated based on a prce per meter per beam, and by cost per meter squared for plating. Weight was calculated in a similar manner. To estimate the strength of the deck, a rearrangement of the permanent deformation eqation in O.F.Hughe's Ship Structural Design and Analysis.

## Outcome

[Discuss the results of the project, its impact, and any metrics or feedback received]

Agueably the project resulted in a success. The MOGA created was able to successfully generate a number of optimal designs, spread across the problem domain and display them to a user. It demonstrates the large potential for an application of artificial intelligence to the ship building industry as a method of speeding up design processes and reducing the shipbuilding insustries enviromental impact. For practical real-life applications, it would be strongly reccomended to use a more complex and representative model, accounting for other components of the ship aswell as a wider variety of shapes. 

## Lessons Learned

[Share insights or skills you gained from this project]

I learned an incredible amount during the creation of this project. 

[View the code repository](http://github.com)

[View the Report]()