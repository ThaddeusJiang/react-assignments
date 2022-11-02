# React Assignment - Order

- [React Assignment - Order](#react-assignment---order)
  - [Description](#description)
    - [Step 1](#step-1)
    - [Step 2](#step-2)
    - [Step 3](#step-3)
    - [Step 4](#step-4)
    - [Notes](#notes)
  - [Submission](#submission)
  - [FAQs](#faqs)

## Description

We want to make multi step form. This form is aimed to help user pre order food from restaurants, the data for restaurants and food items and is provided in the [data](./data) folder.

Wire frames for the form are provided in the [wire frames](./wireframes) folder.

The wire frames are just guide lines, feel free to alter the styling.

### Step 1

- Users select Meal Category (breakfast, lunch or dinner).
- They also need to input number of people (maximum 10)

Both of these should be required field.

### Step 2

- Users select appropriate restaurants that provides meals based on selection in first step.

This is also a required field.

### Step 3

- User selects dishes they want to pre order based on the meal and restaurant they selected in first two steps.

- They first choose a dish
- They can also add number of servings of the dish (defaulted to 1)
- Also users can't select the same dish twice, rather add more servings.

The total number of dishes (i.e Number of dishes \* respective serving) should be greater or equal to the number of person selected in first step and a maximum of 10 is allowed.

### Step 4

On the final step, users should be able to review all their previous choices
and click submit.

### Notes

- User can't proceed to next step unless they have valid inputs on the current step.
- if their inputs are not valid, show appropriate validation errors.
- At any step user can go back and change their preference on any previous step.
- Finally when the user submit the form, just log the data on the console as we don't provide any back end for now.
- Finer details of UX is left for you to decide.

## Submission

- Submit a working link of your code repository (github/ gitlab/ bitbucket, etc...)
- Submit a link of the deployed app (github.io/ now/ surge, etc...)

## FAQs

- Library Usage
  - You are free to use any 3rd party library you want, although we might ask for justification.
