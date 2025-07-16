# Tutorial-1-Serialization

#Introduction

This tutorial will cover creating a simple pastebin code highlighting Web Api. Along the way it will introduce the various components that make up REST framework, and give you a comprehensive understanding of how everything fits together.

The tutorial is fairly in-depth, so you should probably get a cookie and a cup of your favorite brew before getting started.

Note: The code for this tutorial is available in the encode/rest-framework-tutorial repository on GithHub. Feel free to clone the repo and see the code in action.

#Setting up a new environment.

Before we do anything else we'll create a new virtual environment, using venv. This will make sure our package configuration is kept nicely isolated from any other projects we're working on.

python -m venv env
source env/scripts/activate




Where are we now
We're doing okay so far, we've got a serialization API that feels pretty similar to Django's Forms API, and some regular Django views.

Our API views don't do anything particularly special at the moment, beyond serving json responses, and there are some error handling edge cases we'd still like to clean up, but it's a functioning Web API.

We'll see how we can start to improve things in part 2 of the tutorial.

