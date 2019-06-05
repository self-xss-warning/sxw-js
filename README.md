# SXW.js

#### About
SXW.js is a javascript library that is used to display console warnings aginst Self XSS attacks.

[![Website](https://img.shields.io/badge/website-sxw.js.org%2F-%230375b4.svg?style=flat-square)](https://sxw.js.org/)
![GitHub License](https://img.shields.io/github/license/sxw-js/sxw-js.svg?style=flat-square&logo=github)
![GitHub issues](https://img.shields.io/github/issues/sxw-js/sxw-js.svg?style=flat-square&logo=github)
![GitHub release](https://img.shields.io/github/release/sxw-js/sxw-js.svg?style=flat-square&logo=github)


#### Build Status
[![Build Status](https://img.shields.io/azure-devops/build/sxw-js/sxw-js/1.svg?label=Build%3A%20Azure%20Pipelines&style=flat-square&logo=azuredevops)](https://dev.azure.com/sxw-js/sxw-js/_apis/build/status/sxw-js.sxw-js?branchName=master)

#### Available in

![npm](https://img.shields.io/npm/v/@sxw-js/sxw.js.svg?style=flat-square&logo=npm)

### Usage

#### Using js file directly

 1. Include the sxw.js file in your website.
 2. The script will register built-in functions into `window.sxwjs` object.
 3. At the end of the html document call the printWarning function in `window.sxwjs` as shown in the sample code.
    ```javascript
    <script>
        window.sxwjs.printWarning();
    </script>
    ```
#### Using npm
 1. Install the [npm package](https://www.npmjs.com/package/@sxw-js/sxw.js) using
    ```bash
    npm i @sxw-js/sxw.js
    ```
 2. Include the sxw.js file into your webstie.
 3. At the end of the html document call the printWarning function in `window.sxwjs` similar to the one mentioned above.


### Customizations

##### Sections
The warning displayed in console contains three sections.
 1. A huge STOP sign
 2. A caution text in bold
 3. A detailed message saying that this section is intented for developers only. It also warns aginst copy pasting content in the console.

##### Configuration

SXW.js has a config object with the following variables,

Variable name | Default value | Description
------------ | ------------- | ---------
stopColor | red | the colour of the stop sign
warningText | This section is intended for developers only. Don't copy paste anything in this area.\nIf someone told you to copy and paste something here, it is a scam and will give them access to your account. In that case, kindly report this to our support team. | The content of the detailed error message

These variable can be customized to suit your website needs.

##### Functions

There are three functions in the library that will be available into the `window.sxwjs` object.
 1. `printStop` - Prints just the huge stop sign
 2. `printWarningText` - Prints the caution sign and the detailed error message
 3. `printWarning` - prints all the three sections

None of these functions are called by default. You can choose to call them as you wish.
