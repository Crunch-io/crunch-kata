# Crunch Kata

Welcome to the Crunch Kata! The purpose of this exercise is evaluate your
skills in:

1. Automated Testing
2. Problem solving
3. AngularJS

## Problem description

You're working on an application that allows the exploration of survey data. These surveys contain many questions, represented in your view as *variables*. In order to facilitate the discovery of these variables, another team is implementing a tool that allows users to group and order them.

Your job is to develop a web component that displays these variables following the order previously defined by the dataset's owner.

The backend team has provided two test fixtures that you can use to start developing the feature. The first one, `variables.json`, contains the catalog of variables. The second, `order.json`, represents the order in which these variables should be displayed. Each entry in `order.json` maps to an object `variables.json`.

## Instructions

The deliverable should contain the following:

1. An AngularJS directive that display the variables catalog following its hierarchical order. It should be easy to infer to which group a variable belongs, i.e.

    ![HVL](hvl.png)

2. A service that accepts a variable's name and returns the variable's position in the order.
3. A service that accepts a position in the order and returns a variable.
4. An HTTP layer that requests the two fixtures.
5. Automated tests that confirm that your code works.

## About the tools

We only have one hard requirement: AngularJS.

## Deliverable

Publish your work in a GitHub repository.
