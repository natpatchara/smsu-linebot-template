# Bingo generator

SMSU line OA webhook source code by natpatchra pongjirapat

For siriraj student union year 2020-2021

## Table of content
* [Project structure](#project-structure)
* [Technologies](#technologies)
* [Setup](#setup)
* [Usage](#usage)
* [Status](#status)
* [Reference](#reference)

## project structure
```
    .
    ├── api                     # Directory for main webhook api
    ├── img                     # Directory for image material
    ├── json                    # Directory for json line flex template
    ├── richmenu                # Directory for richmenu template and shell script
    ├── template                # Directory for line bot demo
    ├── node_modules            # Directory for nodejs module
    ├── secret                  # Directory for hidden secret (eg. firebase config, line channel etc.)
    ├── package                 # Package config for nodejs
    ├── package-lock            # Package config for nodejs
    ├── .env                    # Hidden env config for vercel server
    ├── License                 # License file
    ├── server.js               # Main javascript file for web server
    └── README.md

```

## technologies

    - javascript
    - nodejs
    - express
    - request
    - node-fetch
    - body-parser
    - line-messaging-api

## setup

In progress

## usage
For usage as a line messaging webhook as a serverless api with vercel
    
## status
As of writing this markdown file, this project is at a stage of real world usage as organisation main line OA. However, there are no benchmarking and intense testing done due to limit of funding.

In summary our current features and to do include:

* features
    * Working as a main webhook when use in accordance with line OA
    * have a proxy function for turning special message type to plain text for dialogflow use

* todo
    * Improve documentation
    * Intensive testing
    * Optimization

## reference
- Tutorial for line messaging API by Jirawatee 
   - [create line channel](https://medium.com/linedevth/%E0%B8%9B%E0%B8%90%E0%B8%A1%E0%B8%9A%E0%B8%97%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B8%AA%E0%B8%A3%E0%B9%89%E0%B8%B2%E0%B8%87-line-bot-b2cb90643901)
   - [basic of line Messaging API](https://medium.com/linedevth/%E0%B8%AA%E0%B8%A3%E0%B9%89%E0%B8%B2%E0%B8%87-line-bot-%E0%B8%94%E0%B9%89%E0%B8%A7%E0%B8%A2-messaging-api-%E0%B9%81%E0%B8%A5%E0%B8%B0-cloud-functions-for-firebase-20d284edea1b)
- [Line messaging API documentation](https://pillow.readthedocs.io/en/stable/)
