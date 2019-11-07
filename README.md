# BIM360 Model Coordination API Postman Scripts

 To work with the scripts, firstly upload some source modesl manually to BIM 360 folder and create model set in Model Coordination module with this folder. The demo source model files can be found at [BIM 360 Model Coorination API Unit Test
 in Node.js](https://github.com/xiaodongliang/bim360-mcapi-node-unit.test/tree/master/Source%20Files). It includes two versions of models set.

Steps:
1.	This script assumes the container id of Model Coordination has been achieved by other scripts. The container id is the id of BIM360 project.

<p align="center"><img src="./help/containterid.png" width="600" ></p>

 It can also be achieved on BIM 360 UI manually.

<p align="center"><img src="./help/projectidinui.png" width="600"></p>


2.	Input oAuth credentials, following the steps at: https://forge.autodesk.com/en/docs/oauth/v2/tutorials/get-3-legged-token/ 

 <p align="center"><img src="./help/oAuth2.png" width="600"></p> 

 <p align="center"><img src="./help/config.png" width="600"></p> 
 
3.	Get access token by logging a user of the project.
4.  Set the token to environment variable access_token 

 <p align="center"><img src="./help/token.png" width="600"></p> 

5.	Play the scripts


## Tricks and Tips
1. Check _description_ of the scripts if there is any notes on the usage.

 <p align="center"><img src="./help/desc.png" width="400"></p> 

2. The **Modelset** collection provides the scripts to create modelset, while it is suggested play with scripts of GET at the beginning, so firstly create some modelsets in BIM 360 UI manually
3. Some APIs of MC are jobs, such as **modelset/version creation**, **Index (Object metadata) query**, **clash issue creating** etc. Check job status by other endpoints named with [Get *** Job Status]. 
4. Some APIs require **document** data such as _documentLineage urn_ . Try with other APIs to get the data and input as payload parameters.

## License

This sample is licensed under the terms of the [MIT License](http://opensource.org/licenses/MIT). Please see the [LICENSE](LICENSE) file for full details.

## Written by

Xiaodong Liang [@coldwood](https://twitter.com/coldwood), [Forge Partner Development](http://forge.autodesk.com)
