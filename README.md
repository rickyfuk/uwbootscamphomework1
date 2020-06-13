# uwbootscamphomework1
# Project Name
> Homework 1 - Code Refactor

## Table of contents
* [General info](#general-info)
* [Code Style](#code-style)
* [Screenshots](#screenshots)
* [Technology](#technology)
* [Action taken](#Action-taken)
* [Status](#status)
* [Create By](#create-by)

## General info
This project is to refactor the existing code for Horiseon website to meet the following objective:

1. Meet the accessibility requirment
2. Reduce or remove the reduntant Html and CSS code
3. Add description to make the code more easy to read for the customer
4. Put in the amendment details and the better understanding for further developers.

The result is expected to eliminate the unneccessary HTML and CSS code and enhance the reader experience for the site.

Please visit [https://rickyfuk.github.io/uwbootscamphomework1/](https://rickyfuk.github.io/uwbootscamphomework1/) for the site.

## Code Style
Standard

## Screenshots
![screenshot](https://github.com/rickyfuk/uwbootscamphomework1/blob/master/assets/images/screenshot.PNG?raw=true)

## Technology
The following systems have been used for this project:

  1. HTML
  2. CSS

## Action taken
List of Changes
* Change the title from website to Horiseon Social Solution Services for easier to locate the site by search engine

* HTML
  - Change some of the non-semetic code to semetic one in index.html file include:
    1. 'div class="header"' to 'header'
    2. Change 'div class="content"' into 'section'
    3. Change 'div class="benefit"' into 'aside'
    4. Change 'div class="footer"' into 'footer'
  - Add "ALT" element for all the image
* CSS
  - Retitle the following CSS section from style.css file:
    1. Change ".content" to "section"
    2. Change ".benefit" to "aside" 
    3. Change ".footer" to "footer"
  - Combine the CSS following elements:
    1. ".search-engine-optimization", ".online-reputation-management" and ".social-media-marketing" into one element - "article"
    2. ".benefit-lead", ".benefit-brand" and ".benefit-cost" into one element - ".benefit"


List of other additional action
* Add description for every single part of Html and CSS code
  <div>
  <img src="https://github.com/rickyfuk/uwbootscamphomework1/blob/master/assets/images/descriptionexample.PNG?raw=true" alt="descriptionExample">
  *example for the description*
  </div>
* List out the amendment details for easier understadning to the future developer
  <div>
  <img src="https://github.com/rickyfuk/uwbootscamphomework1/blob/master/assets/images/amendmentexample.PNG?raw=true" alt="amendmentExample">
  *example for the amendment*
  </div>
* Fixed click and navigate function for the "Search Engine Optimation"
  - Add "id = search-engine-optimization" to the article on line 62 
  ```html
       1. Open the html file
       2. Find the following code block on line 61:
          <section>
           <article id= "search-engine-optimization">
  ```
* Fixed the entire content to stick in the original position regardless to the viewer point
  - Add "overflow: auto;" and "min-width:1024px;" to the body CSS section
  
  >     1. Open the CSS file
  >     2. Find the following code block on line 13:
  ```CSS
            body {
               background-color: #d9dcd6;
               overflow: auto;
                min-width:1024px;
               }
  ```


## Status
Project is: finished


## Create By
Created by Chung Hei Fuk

