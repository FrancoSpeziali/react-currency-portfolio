# React Currency Portfolio

In this project you will be building an application to keep track of currencies as part of a portfolio

## What you will be doing

This project assumes you've already had experience with:

- create-react-app
- React Basics
- React Components
- Handling state in React
- Handling styles in React

## Expectations 🤓

✔ Create your own design

✔ Separate your code into components

✔ You can use functional or class based components, or both

## Requirements 😑

Your portfolio should have the following functionality:

✔ Allow the user to input and store their holdings in a base currency (or multiple base currencies). For example, User A has £100 in GBP _AND_ €5000 in EUR.

✔ Allow the user to view their holdings in various other currencies, simultaneously. For example User A has £100 in GBP but they would like to see the value in EUR, USD and JPY at the same time.

✔ Ability to browse and select input / output currencies. For example, when entering a value, the user should be able to select the currency for that value.

## Optional 🦧

✔ Store holdings in multiple base currencies

✔ Add charts to show historical currency data (this would require use of a 3rd party library to draw the chart, for example [chart.js](https://www.chartjs.org/) or [d3.js](https://d3js.org/))

## Getting started

### Step 1 - Decide on a purpose / API

What is the purpose of your application? Will you work with standard currencies or virtual (crypto) currencies?

You can use the following APIs:

**Standard Currencies**

[Exchange rate API](https://www.exchangerate-api.com/)

**Cryptocurrencies**

[Cryptocompare](https://min-api.cryptocompare.com/)

OR find and use your own.

> Hint: You may need to sign up for a key

> Hint: If you want to test the API, you can use a tools such as [Postman](https://www.postman.com/) or [Insomnia](https://insomnia.rest/)

### Step 2 - Designing your application 🎨

Before you start coding, consider the following:

1. How should your UI look? Look at similar websites online for ideas of how to structure your interface

2. How will your application work? What actions will the user be able to perform?

    > Hint: For this part you can ask yourself questions such as "I want the user to be able to ..." 

3. How can you separate the responsibilities in the application?

4. Can you translate these responsibilities into React components?

5. How will you handle state in your application?

## Step 3

Create a new project folder, using `create-react-app`

Use a folder name of your choice

[How to use create-react-app](https://reactjs.org/docs/create-a-new-react-app.html#create-react-app)

## Step 4

💻 Code! 💻

## Things to think about 🤔

#### Handling the API

How will you call the API? It could be a good idea to separate your API call into a separate file - this way you can separate the logic.

> Hint: You shouldn't repeatedly call the API every second, as doing this is not necessary (especially as the data will not change that much). You will only be allowed to make a certain amount of calls per day / month, so calling the API too many times will cause your application to fail (unless you are willing to pay for a professional account!).

How will you handle the results from the API? Where will you store the data?

> Hint: Consider using component state or the Context API
