# React Router v6 Nested Route Bug

This repository demonstrates a bug encountered with nested routes in React Router v6. The catch-all route (`/*`) incorrectly overrides nested routes.

## Bug Description
Nested routes within a parent route are not rendering correctly when a catch-all route is defined at the parent level. The catch-all route is always triggered, preventing nested route rendering.

## Solution
The solution involves restructuring the route definitions to ensure nested routes are correctly matched before the catch-all route is evaluated.