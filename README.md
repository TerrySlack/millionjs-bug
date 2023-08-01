# Millionjs 

Repo to demonstrate that millionjs generates an error when compiling the project to run

# Setup
This project uses yarn.
To install, type the command yarn in a console, at the root of the project folder

# Issue(s)
million is installed.  Currently 2.5.4-beta.0.  This issues is present as far back as s2.4.9

In config/webpack.base.js
    import million into the file, using require, as per the docs.

    On line 24, million.webpack() is added 

    in a console, run: yarn dev
    You can then see the errors generated.
    Even when attempting to push this to a repo, there are errors and I had to turn off  husky and lint-staged

# node
I currently use node 20.0.0 and have also tried it on node 20.5.0

I cannot downgrade node below 20.0.0.