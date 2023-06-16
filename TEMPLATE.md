# REPO_NAME
This section should contains a simple explanation about the component. The explanation should be very simple and just give the general idea about the component in two lines.

## Features
|ID  |Feature    |Description|Feature Size|Completion|Depend On|Core Feature
|:---|:---       |:---       |:---       |:---|:---|:---|
|1|The user shall be able to delete an old item| This feature allows the user to delete old items more than 1 month|Medium|:white_large_square:|Depend on the auth component|-|
|2|This is completed feature| This feature allows the user to delete old items more than 1 month|Medium|:white_check_mark:|-|-|
|3|The user shall be nice| This feature is nice|Large|:white_large_square:|-|:white_check_mark:|


**Feature** should be written in the same format using *shall* (e.g. The user shall add new items, The user shall add/remove service(s)).

**Feature Description** is a way to elaborate more on the feature and explain it. The description should be simple and precise not more than two lines.

**Feature Size** gives an indication about how complex the feature is to implement (Tiny, Small, Medium, Large, X-Large).

**Depend On** the componenet that the feature is depending on and need to be impolemented to satisfy the feature

**Core Feature** is the feature core or innovative. Core feature must be completed before any innovative features.

## Component UI/UX Mockup (If Any)
The component **MUST** have a functional mockup before starting the actual development.

## Core Features
### Feature 1
Each feature before the start of developement should has a clear vision how it will be implemented and any references should be referenced under each feature. 

## Innovation Features
### Feature 1
An innovation feature is a something that ease the user life and is not that necessary. A user may use the program without innovative features. 

## Installation
The installation steps required to run the repo in production state.
1. Install python3
```
apt install python3
```
2. Run the program 
```
python3 server.py
```

## Development
The development steps required to run the repo in development state.
1. Install development tools
```
apt install python3 Django
```
2. Run development enviroment
```
export DEV=TRUE
python3 server.py
```

## Repo Owner
```JSON
{
  "Name": "Responsible Owner",
  "Email": "owner@example.com",
  "Github": "https://github.com/{owner-account}",
  "Twitter": "https://twitter.com/{owner-account}" /**the owner might add or remove a contact**/
}
```
