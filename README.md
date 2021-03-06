Instagram Challenge
===================

Trello board: https://trello.com/b/JCj2gyyL/instagram-clone

I have decided that I will be prioritising feature building over infrastructure setup (Travis CI/Heroku) as I want to get a deeper understanding of the concept of using an MVC framework such as rails.

Taking the basic requirements listed by the challenge, I started planning by sticking the requirements onto the trello board. When I take on a feature to do, I then create cards based on what is needed to meet those requirements.


### Attempting (and failing) to implement Devise

I first started off seeing whether I can add the `sign up` and `sign in` pages that devise generates onto the homepage. Unfortunately due to my lack of exposure to rails(I've only spent a day and a half on Rails so far), I spent around an hour trying to figure out where and how to link them together.

I decided to leave that, and then work on sorting out the basic controllers and views to make the website.

### Basic website structure

I moved on from trying to do devise to generating the `Grams` controller and adding the `new` view. I found this easier, as it is starting from scratch. However, I'm still having to refer to the Ruby on Rails guide.

I'm becoming more familiar with the structure of what Rails requires, as well as some basic understanding on what the commands to.




---
## Makers Instructions

* Challenge time: one weekend
* Feel free to use Google, your notes, books, etc., but work on your own
* If you refer to the solution of another coach or student, please put a link to that in your README
* If you have a partial solution, **still check in a partial solution**
* You must submit a pull request to this repo with your code by 9am Monday morning

## Task

Build Instagram: Simple huh!

Your challenge is to build Instagram using Rails. You'll need **users** who can post **pictures**, write **comments** on pictures and **like** a picture. Style it like Instagram's website (or more awesome).

Bonus if you can add filters!

## How to start

1. Produce some stories, break them down into tasks, and estimate
2. Fork this repo, clone, etc
3. Initialize a new rails project

Remember to proceed in small steps! Getting confused? Make the steps even smaller.

## Code Quality

For linting, you can use the `.rubocop.yml` in this repository (or your own!).
You'll need these gems:

```ruby
gem "rubocop", "0.48.1"
gem "rubocop-rails"
```

You can also lint Javascript, CSS, and ERB — feel free to research this. These
will help you to train yourself to produce cleaner code — and will often alert
you to mistakes or mishaps!
