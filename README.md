# Syncfusion Vue CSP Sample

This application showcases the Syncfusion Vue Grid component implemented with a strict Content Security Policy (CSP).

To learn more about Content Security Policy (CSP), refer to the [Syncfusion Vue CSP documentation](https://ej2.syncfusion.com/vue/documentation/common/troubleshoot/content-security-policy).

## Getting Started

* To clone the sample app repository locally, open the command prompt in the desired location and execute the following command.

```sh

git clone https://github.com/SyncfusionExamples/ej2-vue-csp-example.git

```

* Navigate to the project directory:

```sh
cd ej2-vue-csp-example
```

## Installing Packages

Install the required node modules by running the following command:

```sh
npm install
```

## Development server

To start the development server, run the command `npm run serve`. Then, open your web browser and navigate to [http://localhost:8080/](http://localhost:8080/) to access the application. The application will automatically reload whenever you make changes to the source files.

> Note: The development build utilizes the [eval-source-map](https://webpack.js.org/configuration/devtool/) devtool provided by webpack. To resolve the unsafe-inline CSP error, you can modify the [vue.config.js](./vue.config.js) file and update the devtool setting to `source-map`.
