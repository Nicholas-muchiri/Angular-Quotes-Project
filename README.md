Angular Quotes
===================

- - - -
Author: [Nicholas muchiri](https://github.com/Nicholas-muchiri)
## Brief description ##
Angular quotes is a web application where users can create quotes and have those quotes voted on whether they are great, disgusting or are inspirational.

### User Requirements ###
The applications allows users to do the following
  * Create a new quote.
  * Add a quote.

## How it works ##
The web app is made with angular Js 5, it is comprised of 3 class components[2 childs and 1 parrent]
  * Quote component-parent component
  * Quote-form-component-for submitting the Quotes
  * Quote-details-component- showing properties of the quote instance: author, publisher, time ago and votes

## Specifications ##
* User submitting a quotes  
    * **Example Input** quote,quote author and quote publisher
    * **Example Output** a section containing inputted quotes with votes init to 0
    * We use **ngModels** to do two way data binding from a template to a component a create an instance of a quote using the **ngSubmit**

## Installation ##
### Cloning into Master ###
* Make sure you have all the Requirements or running angular apps installed such as node,npm, tsc and watchman
* Clone the project into your machine from https://github.com/Nicholas-muchiri/Angular-Quotes-Project.git
* Run ng serve for a dev server. Navigate to http://localhost:4200/. The app will automatically reload if you change any of the source files.

### Using the dist directory ###
* Clone the project into your machine from https:https://Nicholas-muchiri.github.io/Angular-Quotes-Project/
*  Move into the dist directory and open index.html from your browser, make sure you have internet connection as many scripts and assets will be loaded from the online github repository.

### Live demo ###
To view the page click on the link below
* https://Nicholas-muchiri.github.io/Angular-Quotes-Project/

## Technology used ##

* Angular JS
* HTML & CSS

## Known Bugs ##

There are some known bugs to be fixed later on.
## Contributing ##
pull requests are encouraged


## License ##
This project is licensed under the MIT Open Source license, (c) [Nicholas-muchiri](https://github.com/Nicholas-muchiri)
