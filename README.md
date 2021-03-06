# Postman Collection for BIM360 Model Coordination API 

[![BIM 360 Model Set](https://img.shields.io/badge/BIM%20360%20Model%20Set-3.0.65-orange)](https://www.npmjs.com/package/forge-bim360-modelcoordination-modelset)
[![BIM 360 Clash](https://img.shields.io/badge/BIM%20360%20Clash-3.3.27-orange)](https://www.npmjs.com/package/forge-bim360-modelcoordination-clash)
[![BIM360 Index API](https://img.shields.io/badge/BIM%20360%20Index-1.2.44-orange)](https://www.npmjs.com/package/forge-bim360-modelcoordination-index)

[![Postman](https://img.shields.io/badge/Postman-v7-orange.svg)](https://www.getpostman.com/)

![Beginner](https://img.shields.io/badge/Level-Beginner-green.svg)
[![License](https://img.shields.io/:license-MIT-blue.svg)](http://opensource.org/licenses/MIT)

## Description

This repository provides two collections of Postman, one follows [API Reference](https://forge.autodesk.com/en/docs/bim360/v1/reference/http/mc-modelset-service-v3-create-model-set-POST/), the other follows [Tutorials](https://forge.autodesk.com/en/docs/bim360/v1/tutorials/model-coordination/) of Model Coordination API.

## What's Postman?

Postman is a popular tool that provides an easy-to-use interface to send HTTP requests. Postman is able to parse the responses that Forge sends you and save response parameter values to variables. These parameters can then be reused in subsequent requests through these variables. The Postman collections in this repository use this ability to provide pre-populated HTTP requests to help you follow the tutorial workflow with minimal effort. You can also modify the requests and experiment without having to write a single line of code. 

- You can learn how to install and use Postman from [here](https://learning.getpostman.com/docs/postman/launching_postman/installation_and_updates).

- You can download the Postman installer from [here](https://www.getpostman.com/downloads/).


## Setup
1.  Clone this project or download it. It's recommended to install [GitHub desktop](https://desktop.github.com/). To clone it via command line, use the following (**Terminal** on MacOSX/Linux, **Git Shell** on Windows):

    ```git clone https://github.com/xiaodongliang/bim360-mcapi-postman.test```

2. To play API endpoints, find collection and environment variables in [API Reference](/API%20Reference), and import them to Postman. Next, check [Readme of API Reference](/API%20Reference/README.md) for detailed steps.
3. To play Tutorials, find collection and environment variables in [Tutorials](/Tutorials), and import them to Postman. Next, check [Readme of API Reference](/Tutorials/README.md) for detailed steps.

## Notes
1. Model Coordination API requires to work with 3-legged token. This collection takes **[Inheriting auth](https://learning.getpostman.com/docs/postman/sending-api-requests/authorization/#inheriting-auth)** to apply 3-legged token to every endpoint in the collection, which means it does not need to input the token in the header explicitly.
2. The repository provides some test models at [Models](/Models).
3. In each collection or collection folder, some comments are enclosed for reference. 
<p align="center"><img src="./help/collectioncomment.png" width="800" ></p> 
4. In each endpoint, some comments are enclosed for reference. Please check if there is any trick when you are stuck with the test.
<p align="center"><img src="./help/endpointcomment.png" width="800" ></p>

## License

This sample is licensed under the terms of the [MIT License](http://opensource.org/licenses/MIT). Please see the [LICENSE](LICENSE) file for full details.

## Written by

Xiaodong Liang [@coldwood](https://twitter.com/coldwood), [Forge Partner Development](http://forge.autodesk.com)
