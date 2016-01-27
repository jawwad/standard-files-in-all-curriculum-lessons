Every lesson repository in Github, whether a lab or a lesson, has three common files: **Contributing, License, and .learn** files. 

Students going through our curriculum can raise issues if they see any problems with a lesson, and the contributing file contains guidelines on how to do so.  

The license file contains our copyright information, which is very similar to a Creative Commons license. All of our curriculum is open sourced on Github.

These two files above are the same no matter what the lesson content is. 

The .learn file is where you include tags to describe what’s covered in the lesson and this will of course vary depending on the content. 

In order to avoid manually creating these files every time you make a new lesson, we created a gem you install and run. 

Run **"gem install learn_writer"**
Type  **"learn-write"** from the  command line in any directory where you want to create those files 

The files will be created and the only thing that you'll have to update is the .learn file in Github.

## The .learn file

There are three categories of tags. One is simply called tags. Another is language, and the last is resources. Our ultimate goal with these tags is to make curriculum standardized and easily searchable. For now, here are some general tips for tagging. 

1. In languages, do not include rspec/jasmine or any testing frameworks in the tag unless the lab is explicitly teaching testing (all labs should be test-driven)
2. Refer to the topic, unit, and lesson names for tagging ideas
3. Be as specific as possible

#### Tagging Usage

Use Case        | Example Tags
----------------|------------------------------
topics/concepts | algorithms, arrays, authorization, methods, computer science, join tables, iteration
frameworks      | rails, sinatra, angular
libraries       | jquery, popcorn.js
orms            | arel, activerecord, sequel, sql

#### Examples of good tagging:

tags: rails, strong params, complex nested forms, fields_for

tags: methods, variable assignment, iteration

tags: jquery, variable scope


## What Happens If I Don't Add in These Files?

We've created a linter that checks to make sure that all the above files have been added and have been added correctly. If you're missing any of these files or if, for example, there are problems with how you updated your .learn file, the linter will alert you to these failures when you make a Pull Request). 


<a href='https://learn.co/lessons/standard-files-in-all-curriculum-lessons' data-visibility='hidden'>View this lesson on Learn.co</a>
