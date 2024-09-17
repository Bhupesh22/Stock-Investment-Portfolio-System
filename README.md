# Stock Investment Portfolio System

```
Project Folder
├── data
│   └── Symbol_List.txt
├── portfolios
├── src
├── flexible_portfolios
└── strategy
    └── dollarCostAveraging.json
Libraries
```
```
org.apache.directory.studio:org.apache.commons.io:2.4
com.fasterxml.jackson.core:jackson-core:2.13.3
com.fasterxml.jackson.core:jackson-annotations:2.13.3
com.fasterxml.jackson.core:jackson-databind:2.13.3   
com.google.code.gson:gson:2.10
com.googlecode.json-simple:json-simple:1.1.1
org.swinglabs:swingx:1.6.1
```

Installation

Navigate to the project directory.
Use your IDE's Maven integration to add the libraries.
Running the Project

Open a terminal in the project directory.
Execute: ```java -jar stockinvestment.jar Text```

# Project Features
Core Functionalities:

Create Portfolio
Examine Portfolio
Get Valuation

# Additional Features:

Buy/Sell Shares
Cost Basis
Display Portfolio Graph
Upload Portfolio
Design Overview

- MVC Architecture: Uses Model-View-Controller for separation of concerns.
- Interfaces: Defines contracts for model, controller, and view components.
- Flexible Portfolio: Extends the base portfolio with additional features.
- Strategy: Implements a strategy-based investment approach (e.g., dollar-cost averaging).
- Swing UI: Provides a graphical interface for user interaction.

# Key Points:

- Data Storage: Uses data/Symbol_List.txt for stock data.
- Configuration: src/config.properties contains project settings.
- Portfolios: Generated portfolios are stored in the portfolios folder.
- Libraries: Essential for project functionality.
- Execution: Run the JAR file from the project directory.

