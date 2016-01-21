# Simple Partials Lab

## Objectives

1. Use the render keyword to do named partials
2. Understand how a name of a partial turns into it's filename
3. Work with calling partials in a different folder


## Overview

Flatiron is building out a new system to keep track of students in its classes.  You just joined the technical team, and see that there's lots of repetition in the view layer of the code base.  Use your new knowledge of partials to remove the duplication.

![greys-anatomy](http://57.media.tumblr.com/cbcd8f29790e720e4cea60f44cb2c6b9/tumblr_mrbut3kX1g1r6kab2o1_500.gif)

## Instructions

First, fork and clone this lab.

Run rake db:seed to seed the database.

1. Remove the duplicated code in the students/edit.html.erb and students/new.html.erb files by making a partial called `students/_form.html.erb`
2. Remove the duplicated code in the students/edit.html.erb and students/new.html.erb files by making a partial called `students/_student.html.erb`

We've provided a seeds file so you can have some data to play around with - run `rake db:seed` to seed the database.

<a href='https://learn.co/lessons/displaying-has-many-through-rails-lab' data-visibility='hidden'>View this lesson on Learn.co</a>
