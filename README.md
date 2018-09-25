# Typescript project to test absolute paths

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

## Problem

in App.tsx I want to import MyComp with absolute path (src/MyComp) instead than relative path (./MyComp)
This works out of the box on run, but not on test

## Solution

Set NODE_PATH=. environment before running tests
