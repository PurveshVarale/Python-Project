# Python-Project
## Objective
The objective of the "Create Dictionary Data Structure with All Methods" project in Python is to design and implement a custom dictionary-like data structure that replicates and extends the functionalities of Python's built-in dict object. This involves creating a class that encapsulates key-value pair storage and provides various methods to manage, retrieve, and manipulate the data effectively. The goal is to understand how dictionaries work under the hood and enhance your understanding of data structures and algorithms.

### How Does It Work:
1 Class Definition
2 Data Storage
3 Initialization
4 Methods to Implement
5 Handle Edge Cases
6 Customization
7 Testing
# Custom Dictionary Data Structure with All Methods

This project implements a custom dictionary-like data structure with all standard and additional methods.

## Flowchart

```mermaid
flowchart TD
    Start([Start])
    Init([Initialize Dictionary])
    Add[Add Key-Value Pair]
    Update[Update Value for Key]
    Get[Retrieve Value for Key]
    Remove[Remove Key-Value Pair]
    Contains[Check if Key Exists]
    Keys[Get All Keys]
    Values[Get All Values]
    Items[Get All Key-Value Pairs]
    Clear[Clear All Key-Value Pairs]
    Len[Get Dictionary Length]
    ErrorHandling[Handle Edge Cases]

    Start --> Init
    Init --> Add
    Add --> Update
    Add --> Get
    Update --> Get
    Get --> Remove
    Remove --> Contains
    Contains --> Keys
    Keys --> Values
    Values --> Items
    Items --> Clear
    Clear --> Len
    Len --> ErrorHandling
    ErrorHandling --> End([End])

