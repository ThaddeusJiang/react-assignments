# React Assignment - Org Tree

> This assignment is aimed to help us assess your `React` and `JavaScript` skills.

- [React Assignment - Org Tree](#react-assignment---org-tree)
  - [Requirements](#requirements)
    - [Must](#must)
    - [Optional](#optional)
  - [Setup](#setup)
  - [Description](#description)
      - [Spec1](#spec1)
      - [Spec2](#spec2)
      - [Notes](#notes)
  - [Submission](#submission)
  - [FAQs](#faqs)

## Requirements

### Must

- Use `React`
- Use `TypeScript`
- Write Unit Tests (any testing library, but preferred `jest`)

### Optional

- Write E2E Tests (preferred `Playwright`)
- If needed use a CSS library (preferred `tailwindcss`)

## Setup

As this test is to evaluate basic `React` and `JavaScript` skills, we are not be focusing on tooling setup (webpack, babel, etc...).

So feel free to use [create react app](https://github.com/facebook/create-react-app) to jump start your development, although if not comfortable custom setup is also welcomed.

## Description

We want to make a complex form. This form is aimed to help user manage organizations and members, the data for organizations and members are provided with [data](./data/) folder. TODO: provide ~~[REST API]()~~.

Wire frames for the form are provided in the [wire frames](./wireframes) folder.

the wire frames are just guide lines, feel free to alter the styling.

#### Spec1

- User can modify organization details (name).
- User can move an organization under the other organization.
- user can create an organization.

#### Spec2

- User can modify member info (name, age or status).
- User can move a member to the other organization.
- User can create a member.
- User can set a member as the representation, if the member is activated.

#### Notes

- User can't proceed to next step unless they have valid inputs.
- If their inputs are not valid, show appropriate validation errors.
- User can cancel the changes before saving.
- Finally when the user submit the form, handle REST API response please.
- Finer details of UX is left for you to decide.

## Submission

- Submit a working link of your code repository (github/ gitlab/ bitbucket, etc...)
- Submit a link of the deployed app (github.io/ now/ surge, etc...)

## FAQs

- Library Usage
  - You are free to use any 3rd party library you want, although we might ask for justification.
