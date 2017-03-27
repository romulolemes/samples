Box Samples
====================

This repo is dedicated to sharing code snippets and samples to demonstrate how to get the most out of the Box platform & API. It will include specific use cases, showcasing integrations and other creative uses of the Box API.

Index
-----

[box-node-lambda-sample](https://github.com/box/samples/tree/master/box-node-lambda-sample)
This sample demonstrates how to call Box APIs from an AWS Lambda function using the [Box Node SDK](https://github.com/box/box-node-sdk).
This lets you call Box from a Lambda function.

[box-node-webhook-to-lambda-sample](https://github.com/box/samples/tree/master/box-node-webhook-to-lambda-sample)
This sample shows how to connect a Box webhook to an AWS Lambda function via API Gateway.
This lets you call a Lambda function from Box. 

[box-node-rekognition-lambdas-sample](https://github.com/box/samples/tree/master/box-node-rekognition-lambdas-sample)
This sample shows how to connect Box with AWS Rekognition service. An AWS lambda function uses the AWS Rekognitions service to analyse the image uploaded in Box and updates the metadata of the image file in Box.

[box-node-cognito-lambdas-sample](https://github.com/box/samples/tree/master/box-node-cognito-lambdas-sample)
This sample shows how to integrate Box with AWS Cognito service. Every user created in the Cognito pool is created as an app user in the Box enterprise. Using the Cognito JWT user token, the app user token can be generated from Box. Using Box's app user token, the user performs operations in Box.

Support
-------

Need to contact us directly? You can post to the
[Box Developer Forum](https://community.box.com/t5/Developer-Forum/bd-p/DeveloperForum).

Copyright and License
---------------------

Copyright 2016 Box, Inc. All rights reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
