# Python-Project
## Objective
The objective of the "Create Dictionary Data Structure with All Methods" project in Python is to design and implement a custom dictionary-like data structure that replicates and extends the functionalities of Python's built-in dict object. This involves creating a class that encapsulates key-value pair storage and provides various methods to manage, retrieve, and manipulate the data effectively. The goal is to understand how dictionaries work under the hood and enhance your understanding of data structures and algorithms.

## How Does It Work:
1 Class Definition
2 Data Storage
3 Initialization
4 Methods to Implement
5 Handle Edge Cases
6 Customization
7 Testing
## Custom Dictionary Data Structure with All Methods

### This project implements a custom dictionary-like data structure with all standard and additional methods.

## Flowchart
# Custom Dictionary Data Structure with All Methods

This project implements a custom dictionary-like data structure with all standard and additional methods.

## Flowchart

```mermaid
flowchart TD
    %% Style Definitions
    classDef startEnd fill:#ff6f61,stroke:#333,stroke-width:2px,color:#fff
    classDef process fill:#f9f9f9,stroke:#0366fc,stroke-width:2px
    classDef decision fill:#ffcf33,stroke:#333,stroke-width:2px,color:#333

    %% Nodes
    Start(["Start"]):::startEnd
    Init["Initialize Dictionary"]:::process
    Add["Add Key-Value Pair"]:::process
    Update["Update Existing Key"]:::process
    Get["Retrieve Value by Key"]:::process
    Remove["Delete Key-Value Pair"]:::process
    Contains["Check if Key Exists"]:::decision
    Keys["List All Keys"]:::process
    Values["List All Values"]:::process
    Items["List All Key-Value Pairs"]:::process
    Clear["Clear Dictionary"]:::process
    Len["Get Dictionary Length"]:::process
    ErrorHandling["Handle Invalid Operations"]:::decision
    End(["End"]):::startEnd

    %% Connections
    Start --> Init
    Init --> Add
    Add --> Update
    Add --> Contains
    Update --> Get
    Contains -->|Key Exists| Get
    Contains -->|Key Missing| ErrorHandling
    Get --> Remove
    Remove --> Keys
    Keys --> Values
    Values --> Items
    Items --> Clear
    Clear --> Len
    Len --> ErrorHandling
    ErrorHandling --> End

