## Name: Justin Logan (JALogan)
## Date: 3/3/23
## Course: IT FDN 130 A Wi 23: Foundations Of Databases & SQL Programming

# Assignment 7 – Functions

## Introduction

This week we delve further into SQL Functions. Functions are named database objects which accept input parameters, perform actions, and return results. By utilizing Functions, we extend our ability to gain insight & draw conclusions from data.

## User-Defined Functions in SQL

SQL functions are distinct blocks of code that perform specific tasks. Functions are different from Select statements in that they accept input parameters. Any function which is not built-in is User-Defined. There are three types of User-Defined functions: Scalar, Inline, and Multi-Statement Functions. A User-Defined Function would be used in any task which requires input parameters & for which a built-in function does not exist.

## Scalar, Inline, and Multi-Statement Functions

Scalar functions will return only a single value, typically coupled with a Select statement utilizing Where, Group By, or Having clauses. Inline and Multi-Statement functions may both return multiple values or sets, and are considered a good alternative to Views, as Views do not accept input parameters. Both Inline and Multi-Statement functions are invoked in From or Join clauses within Select statements. An Inline function cannot have Begin and End blocks, and cannot define the structure of the returned set, whereas Multi-Statement functions do have Begin and End blocks and as a matter of course defines the structure of the returned table. 

## Summary

In conclusion, SQL Functions offer novel ways to act upon, process, and present data that would not be possible using Selects or Joins. User-Defined Functions extend this functionality beyond the scope of Built-In functions.
