# sample-rest-apis

A collection of the same, simple, REST API using various languages and frameworks.

# Why?

As a penetration tester and web application security researcher, being able to parse through source code and find high-impact bugs is important. I'm of the mindset that one of the best ways to improve white box code review skills is to write a little code in the given language and framework in order to establish some familiarty.

In this repo I will be writing the same, simple, web API in all of the modern web application frameworks that I come up against during my engagements and research with the intent of sharpening my own skills and improving my knowledge of these languages and frameworks.

# API Features

This API aims, at minimum, to use the given language and framework features to implement:

- Authentication using JWTs
- Authorization via 2 defined user roles `basic` and `admin`
- Security headers
- Swagger Docs
- A REST API that allows application users to perform CRUD (create, read, update, and delete) operations on notes.
  - `basic` users can only perform CRUD operations on their own notes.
  - `admin` users can perform CRUD operations on any user's notes.

## API Routes

In general each instance of the sample API should expose these routes, though they may slightly differ from framework to framework so refer to the given framework's `README.md` file for specifics.

```
/
POST /sign_up
POST /login
POST /logout
GET /notes
POST /notes
GET /notes/{id}
PUT /notes/{id}
DELETE /notes/{id}
```

Obviously these APIs could be infinitely more complicated, but the point of this project is **learning** how to implement these minimal web application security features in most modern frameworks. This is also nice because it should mean that it will be easy in the future to look back at various implementations of this API to remember how each framework does it without drowning in a ton of code.

# Languagues & Frameworks

This repo is organized hierarchically by language and framework in order to make navigation straightforward. Each framework's folder will contain source code for the sample REST API along with a `README.md` file that explains how to build it.

```
├── Java
│   ├── java-ee
│   │   └── README.md
│   └── spring-boot
│       └── README.md
└── Python
    ├── django
    │   └── README.md
    └── flask
        └── README.md
```

Links to the various `README.md` files are below, for convenience.

## Java

### Java EE

- TODO

### Spring Boot

- TODO

## JavaScript

### Node

- TODO

## Csharp

### .NET Web API

- TODO

## Python

### Flask

- TODO

### Django

- TODO

## Ruby

### Rails

- TODO

## Golang

- TODO

