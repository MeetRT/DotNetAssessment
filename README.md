# DotNetAssessment
Assessment to test .Net developers.

## To start, please fork this repository and create a pull request with your code when you are finished!

## Introduction

In order to evaluate your skills and coding style we would like you to develop a small .Net Framework application that consumes [Best Buy](https://developer.bestbuy.com/) API RESTFull services. Please use .Net Framework and note .Net Core. You are free to use MVC or other design patters based on your personal preference. 

## Application

We would like to have a small application that accomplishes the following:

1. The main screen will have a search text input where the user can search for any BestBuy product (e.g. Mobile Devices as iPhones, HTCs, Samsung...) within any category or a category you prefer, once the search button on the keyboard, or the search button on the screen has been pressed, you need to search for those products and return to step 2. 

2. Once the products are returned, you will then need to present them as a list with the following information:
	* Product Thumbnail.
	* Product Name.
	* Product Price.
	 
	When the user presses on any item within the list go to step 3.

3. The user should see the details of the product as follows:
	* Product Image, bigger than the Thumbnail.
	* Product Name.
	* Product Price.
	* If the product is on sale, should show sale price.
	* Number of reviews by customers.
	* Review average.
	* Description.
	* Related products Button. If the user presses this button, go to step 4.
	* Accessories Button. If the user presses this button, go to step 5.

4. A list view with the related products for the item showed. Every product should show the following information:
	* Product Image.
	* Product Name.
	* Product Price.
	 
5. A grid list view with the accessories for the item shown. Every accessory should show the following information:
	* Product Image.
	* Product Price.

## Where to start

* Get your API Key as explained within the [documentation](https://developer.bestbuy.com/get-started)

> **Step 1: Get a key**

> Before you can start using our APIs, you need an API key. It's easy. Just visit [GET API Key](https://developer.bestbuy.com/login) and sign up with your email address. 
We'll send you an email with instructions on how to activate your new key. 
Once you've activated your key, you're ready to roll.

```
If you have any issues getting the API Key, please contact us, and we will provide you with one.
```

* Check out the [Best Buy Api Documentation](https://developer.bestbuy.com/documentation) to learn how to get the information this test requires. 

## Procedure

* Fork this repository and work on your own fork.
* When you think your app matches the requirements and you are proud of the code you are going to push, make a pull request to this repository. We will review your code and we will comment inline about your code.
* In your pull request, add a description of the solution you have implemented and any other issue we should take into account at the time of review.

## Requirements

* The application should compile without Error and run without crashing.
* You are allowed to use third party Nugets. For any third-party used within the project there must be a justification of its use.
* You have 1 week to present a pull request with a solution, but the sooner you present a solution the better.

## Plus points

* Pagination or load more for the products list
* Animations
* Unit Testing

## What we're looking for

* Knowledge of .Net Framewok
* Knowledge of design patterns
* Clean code

FirstFocus wishes you good luck and we are looking forward to see your code. 

If you need any help, please do not hesitate to contact us.
