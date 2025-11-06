# Dice Roller - Client

A web application client that connects to a remote dice rolling service using Service-Oriented Architecture (SOA).

## Author

Salavuddin Shaik  
Lewis University  
Software Architecture and Design  
CPSC-61200-003

## AI Usage

This project was developed with assistance from Claude AI for:

- Understanding the difference between Azure Web App and Azure Function App
- Troubleshooting Web App creation issues and switching to Function App
- Configuring Azure Function App for Node.js
- Resolving CORS (Cross-Origin Resource Sharing) policy issues between client and server
- Implementing proper client-server communication using Fetch API
- Azure deployment and configuration

## Description

This is the client-side application of a distributed dice roller system. Users can:

- Connect to a remote dice rolling server via URL
- Roll 1, 2, or 3 dice
- See random results displayed with dice emojis
- View total sum of all dice rolled

## Technologies

- HTML5
- CSS3
- JavaScript (Fetch API)
- Azure Static Website Hosting

## Architecture

This application implements Service-Oriented Architecture (SOA):

- **Client**: Web interface (this repository)
- **Server**: Azure Function App providing random number generation

## Live Demo

https://dicerollerrg.z14.web.core.windows.net/

## Server Repository

https://github.com/SalavuddinShaik/DiceRoller-Server
