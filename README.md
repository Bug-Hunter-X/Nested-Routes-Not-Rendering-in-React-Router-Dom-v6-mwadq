# React Router Dom v6 Nested Routes Issue

This repository demonstrates a common issue encountered when working with nested routes in React Router Dom v6. The problem is that nested routes are not rendering properly when navigating to them.

## Problem

The provided `App.js` uses nested routes, but when navigating to `/about/contact`, the component does not render. The solution provides a fix for this behavior. 

## Solution

The solution involves properly defining the nested routes using the `Route` component within a parent route using the `element` prop, ensuring the correct path structure is used for navigation.