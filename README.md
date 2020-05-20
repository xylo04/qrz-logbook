# Go API client for qrzlog

This API provides methods for external programs to interact with the QRZ Logbook using an HTTP REST interface. The QRZ Logbook is a combination free and paid subscription service of QRZ. Some advanced features require a valid subscription while the majority of operations are free to all QRZ members. All users of the QRZ Logbook, regardless of their subscription status, may access, edit, update, and view their complete logs online at the QRZ website.

## Overview
This API client was generated by the [OpenAPI Generator](https://openapi-generator.tech) project.  By using the [OpenAPI-spec](https://www.openapis.org/) from a remote server, you can easily generate an API client.

- API version: 1.0.0
- Package version: 1.0.0
- Build package: org.openapitools.codegen.languages.GoClientCodegen

## Installation

Install the following dependencies:

```shell
go get github.com/stretchr/testify/assert
go get golang.org/x/oauth2
go get golang.org/x/net/context
go get github.com/antihax/optional
```

Put the package under your project folder and add the following in import:

```golang
import "./qrzlog"
```

## Documentation for API Endpoints

All URIs are relative to *https://logbook.qrz.com/api*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*DefaultApi* | [**DoEverything**](docs/DefaultApi.md#doeverything) | **Post** / | The do-everything endpoint


## Documentation For Models

 - [Request](docs/Request.md)
 - [Response](docs/Response.md)


## Documentation For Authorization

 Endpoints do not require authorization.



## Author

flloyd@qrz.com

