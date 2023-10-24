# UOCS322 - Project 3 #
## Erin Szabo
#### Fall 2023
### eszabo@uoregon.edu

The purpose of this project is to learn about JQuery and asynchronous requests in this project.

## Overview

The program is a simple anagram game designed for English-learning students in elementary and middle school. It presents a list of words to students and an anagram. The anagram is a jumble of some of the words, which are randomly chosen. Students attempt to type words that can be created from the jumble. When a matching word is typed, it is added to a list of solved words.

The vocabulary word list is fixed for one invocation of the server, so multiple students connected to the same server will see the same vocabulary list but may have different anagrams.

## Getting started

`flask_vocab.py` runs the anagram game, with the template `vocab.html`. This example uses a conventional interaction through a form, interacting only when the user submits the form. 

## Set Up

-  cd into `vocab/` 
-  Build the flask app image using
    ```
    docker build -t some-image-name .
    ```
- Run the container using

  ```
  docker run -d -p 5001:5000 some-image-name
  ```
 - Launch `http://hostname:5001` using your web browser 


## Game

Use letters from the jumbled set of letters to spell words from the displayed list. As soon as a correct word is spelled it is added to your found list.
	 

## Original Authors

Michal Young, Ram Durairajan. Updated by Ali Hassani.