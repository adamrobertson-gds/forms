# Simple routing logic (skip questions) 

## Status

Date created: *2023-05-23*  

Epic trello card: https://trello.com/c/nBnFZQlw/135-epic-simple-routing  
Mural working board: https://app.mural.co/invitation/mural/gaap0347/1671196865223?sender=ue1ef9fc3c2ad3697c3c93132&key=09616cf9-ae28-43a7-8810-10970a59a765  
Basic routing feature write up: https://docs.google.com/document/d/1i7T5D3PQw4hB1wgISi-r5086Fzw1-3nKnwaCGbNMi1E/edit#heading=h.h2rnqdwxl250  
___

## Contents

- [Simple routing logic](#simple-routing-logic)
  - [Status](#status)
  - [Contents](#contents)
  - [What](#what)
  - [Why](#why)

___

<br>

## What

This feature introduces functionality within the form building tool to help form creators create simple skip logic for questions. This means that people completing a form need to be asked only relevant questions based on a previously given answer.

### User stories

**As a form creator**, I need to allow users to skip a question based on their previous answer, so that we only collect the information needed.

**As a form filler**, I need to skip a question based on my previous answer, so that I don’t have to give more information than I need to.

<br>

## Why

When users fill in forms they’re currently shown all the questions within a form, meaning they’re potentially presented with questions that are not relevant to their submission. This can cause anxiety for people completing forms as they may not have the information needed or they may not understand what they’re being asked for. It can also waste their time and add to cognitive load.

When creating paper forms, we know that creators use wording to tell form fillers when a piece of information is required or if they should go to a later section or question to continue.  

We also know that paper forms can be completed in any order, with information being skipped if the person filling it in does not have the information or does not feel that a certain question applies to them. This can result in incomplete forms being submitted.  

Without skip functionality being part of an HTML form users are forced to go through all the questions even when they’re not relevant to their submission. We originally implemented a feature to allow form creators to make questions ‘optional’: this means the person completing a form can pass over questions they do not need to complete. However, this means form creators need to add context to questions within the 'hint text' to help form completers decide if they need to complete a question or not.  

## Hypothesis

**We believe** that by offering simple skip logic, based on the ‘selection from a list’ answer type, we can help form creators create better forms that only ask for information that the processing team need to action a submission.  

<br>

___

<br>

[Back to the top](#simple-routing-logic)
