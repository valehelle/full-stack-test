
# Full-stack Developer Assessment

Thank you for your interest in applying to become, please complete the Assessment Questions and Problem Test and add the relevant links to your

## Assessment Questions

**Instructions:**  Answer as many questions as possible and create a pull   request containing your answers on this file and add the pull request link in your application

1. What is race condition?
1. What is a thread-safe function?
1. What is the difference between thread and process?
1. Explain what is Blue-green Deployment, Canary release, A/B testing?
1. Explain the difference between layout, painting and compositing.
1. What’s the difference between “resetting” and “normalizing” CSS?
    (i). Which would you choose, and why?
1. What are the advantages/disadvantages of using CSS preprocessors?
    (i). Describe what you like and dislike about the CSS preprocessors you have used.
1. What is the difference between class selector and ID selector?
1. How does inheritance work in CSS?
1. Describe the difference between a cookie, sessionStorage and localStorage.
1. Describe the difference between `<script>`, `<script async>` and `<script defer>`
1. How is Docker different from other container technologies?
1. What is Kubernetes, how does it work?
1. How does garbage collector work?
1. What is an integration test?
1. Explain Database Transactions
1. What is a deadlock?
1. Explain the difference between Inheritance vs Composition
1. What are microservices, explain how it could be used when developing applications?
1. What are some common web security flaws and how do you guard against it?

## Problem Test

**Instructions:**  Answer only one question, once you're done add the link to the applications repository and heroku app in your job application

### Principles
 We want you to focus on those three principles while writing code: clarity, simplicity and defensiveness.
* Clarity: write clear code that any developer can read and understand in one go.
* Simplicity: write gimmick-free and straightforward code with no ambiguities.
* Defensiveness: cover edge cases and treat user inputs with care.

### Requirements
* Use any programming language you're comfortable with
* Write Unit Tests
* Track repository with git and push your code to github in a public repo and add becomemy as a collaborator.
* Deploy application to heroku

### Choose a problem
**Problem 1**
Your sales team has a list of leads that they want to send a sms blast out. They need a simple app that will the read a csv list, remove it's duplicates and sends out a sms to each lead within the list
* Use https://www.twilio.com/try-twilio to send sms blasts out
* Download the csv file [here](https://become-my.s3-ap-southeast-1.amazonaws.com/developer-test-data/test-numbers.csv)

**Problem 2**
Your finance team needs to conduct some regional pricing experiments on their products, They need a simple app that will the read a csv list containing it's products and prices, converts it to the required currencies and displays it's values
* Required currencies: JPY, THB, USD, BTC
* Download the csv file [here](https://become-my.s3-ap-southeast-1.amazonaws.com/developer-test-data/test-prices.csv)
* Use https://www.exchangerate-api.com/ for currency conversions
* Use https://www.coingecko.com/en/api to get BTC rates.
