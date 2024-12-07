# React Router Catch-all Route Issue

This repository demonstrates a common issue in React Router v6 where a catch-all route (`path="/*"`) defined in `Routes` interferes with other route definitions.

The problem arises because the catch-all route is always matched first, preventing other routes from being evaluated.  This is particularly problematic when other routes are added, resulting in only the catch-all route being used.

**Solution:**  Adjust route order or use a more specific catch-all.
