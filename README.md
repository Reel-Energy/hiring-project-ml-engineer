# Reel - Hiring project for Machine Learning

## Purpose

As the next step in the interview process for the ML Engineer job at Reel, we will ask you to complete this project. We will use your solution to the project to get a better understanding of your technical abilities and how you approach a technical challenge. Your solution will also be the starting point for our subsequent technical interview. The project is intended to be a small representation of the kind of work we do at Reel.

## Problem description

As a Balancing Responsible Party in the Danish markets we are responsible for placing orders into the day-ahead electricity market auction.  An order includes a volume, price, and an hourly timestamp.  If executed these orders are converted in trades and we buy or sell the given volumes at the settled price.

Due to operational requirements we place orders each week for the next 7 days.  Our data is delayed by 3 days so we need to forecast 10 days into the future.  We need accurate forecasts so we do not buy or sell electricity unnecessarily.

We expect the project to take 2-3 hours to complete. You are always more than welcome to reach out to us if something needs clarification.

## Your task

#### 1. Train a model to forecast our consumption

We have about two and a half years of hourly consumption data in the dataset.csv file.  Using this dataset, create a model that can forecast 10 days into the future.

#### 2. Evaluate your model

Perform analysis of your trained model's predictions.

#### 3. Explain your solution

Write a short (1200 characters max) explanation of how your solution works, why you chose that particular solution, and justify your explanations using the data.

## Submitting your work

1. Clone this repository locally
2. Create and switch to a local branch for development
3. Develop your solution
4. Once you're done and have committed everything, create a patch of your changes
   - `git diff main > <your_name>.patch`
5. Send the following to christian@reel.energy
   1. The patch file
   2. The description of your solution in pdf format

## How we evaluate

We focus on three main points in our evaluation:

1. How you solved the task. There are many ways to approach a task like this.
2. Your reasoning about choosing this solution.
3. How you would manage a model deployed to production over time.
