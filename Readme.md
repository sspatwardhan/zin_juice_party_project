# Juice Party Requirements Calculator

This Python script helps you plan a juice party by determining the juice combinations based on the calorie requirements of your friends.

## Table of Contents

- [Thought Process](#thought-process)
- [Usage](#usage)
- [Workflow](#workflow)

## Thought Process

1. Assumptions (as per [requirements](requirement_docs/Problem1.pdf))
    - Ask availibile juices for every friend
    - Do not share available juices
    - Do not eliminate juices from single list
2. Structural break down
    - Logical division of the methods and files for
        - Better testability
        - Error Handling
3. Good to have (avoided in interest of time)
    - API backed web-application 
    - Enhanced code coverage
    - Enhanced optimization for further unit-testing
    - Logging



## Usage

To use this script, follow these steps:

1. Clone the repository to your local machine
2. To run project - execute following command from the root dir
```
python3 zin_juice_service.py
```
3. Run unitTests - execute following command from the root dir
```
pytest
```
    
    
## Workflow

![Alt text](Zinrelo_Juice_Problem.png?raw=true "Workflow")