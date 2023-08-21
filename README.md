# Student Onboarding API Documentation

Welcome to the documentation for the Student Onboarding API! This API allows you to manage student information and perform various operations related to student onboarding. 

# Link swager UI TD1

https://petstore.swagger.io/?url=https://raw.githubusercontent.com/ZoFitahiana/API/main/TD1.yaml

# Link swager UI TD2

https://petstore.swagger.io/?url=https://raw.githubusercontent.com/ZoFitahiana/API/main/TD2_Teacher.yaml

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Endpoints](#endpoints)
- [Schemas](#schemas)
- [Responses](#responses)
- [Contact](#contact)

## Introduction

The Student Onboarding API provides endpoints to retrieve student information and add new students. It is designed to facilitate the onboarding process for educational institutions.

## Getting Started

To get started with the API, you need to have the following information:

- Base URL: `https://STD22017/TD1`

## Endpoints

### Retrieve All Students

- Endpoint: `GET /students`
- Description: Retrieve information about all students.
- Responses:
  - `200`: Successful operation. Returns a list of students.
  - `500`: Internal Server Error.

### Add New Student

- Endpoint: `POST /student`
- Description: Add a new student to the system.
- Request Body: JSON data containing student information.
- Responses:
  - `200`: Successful operation. Returns information about the added student.
  - `500`: Internal Server Error.

## Schemas

The API uses the following schemas to define data structures:

- `Response`: Information about a student with properties like `id`, `name`, and `birthDate`.
- `Add`: Similar to `Response`, representing added student information.
- `Input`: JSON structure for input when adding a new student.

## Responses

The API provides the following response codes:

- `200`: The request was successful.
- `500`: An internal server error occurred.

## Contact

For any inquiries or assistance, please contact:

- Email: hei.tsiaroniaina@gmail.com
