# Getting started with Spring Framework - Goals

- Build a Loos coupled Hello World Gaming app with Modern Spring approach

- Get Hannds-On with Spring and understand:
    - Why Spring?
    - Terminology
        - Tight and loose coupling
        - IOC container
        - Application context
        - Component Scan
        - Dependancy Injection
        - Spring Beans
        - Auto Wiring

# 1: Loose coupling with Spring Framework

- Design Game Runner to run games:
    - mario, Super Contra, PacMan etc.

- Iteration 1: Tightly Coupled
    - GameRunner class
    - Game classes: Mario, Super Contra, PacMan etc

- Iteration 2: Loose coupling - Intefaces
    - GameRunner class
    - GamingConsole interface
        - Game classes: Mario, Super Contra, PacMan etc

- Iteration 3: Loose coupling - Spring
    - Spring framework will manage all our objects
        - GameRunner class
        - GamingConsole interface
            - Game classes: Mario, Super Contra, PacMan etc
