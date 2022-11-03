---
layout: default
title: Template recipe
nav_order: 999
has_children: false
parent: Recipes
---

<!-- [Join the DLRS Trailblazer Community - Today!](https://trailhead.salesforce.com/trailblazer-community/groups/0F9300000009O5pCAE){: .btn .btn-green } -->

# [[Recipe name]]

## What

You want to be able to update a field on the record that is triggering the flow.

## Type

Record Triggered Flow - Fast Field Update (Before Save)

## Description

Our example today is we want to be able to update the opportunity name to meet our naming convention either on create or update of a record.
(Note for NPSP user: We first need to turn off NPSP naming conventions so our naming is happening only from one automation location.) For our example, we actually made it an Update Only Flow.

## Pre-Work

Determine the naming convention you would like to use. For this example, Contact Name - Record Type Name - Amount - Close Date or Account Name - Record Type Name - Amount - Close Date for none Household/people accounts.

## Steps

