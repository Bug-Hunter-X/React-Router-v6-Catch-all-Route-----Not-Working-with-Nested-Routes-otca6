# React Router v6 Catch-all Route (*) Issue with Nested Routes

This repository demonstrates a problem encountered when using the catch-all route (*) in React Router v6 with nested routes.  The catch-all route, intended to handle any unmatched paths, fails to function correctly.

## Problem Description
The issue occurs when a catch-all route (`path="*"`) is present alongside nested routes within a `Routes` component. Even when no other routes match, the catch-all route does not activate. 

## Setup
1. Clone this repository.
2. Run `npm install`.
3. Run `npm start`.

Navigate to a non-existent route, e.g., `/invalid`. You'll notice that nothing is displayed. This is because the catch-all route is not working as expected.