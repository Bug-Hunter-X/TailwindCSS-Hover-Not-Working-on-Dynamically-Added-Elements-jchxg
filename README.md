# Tailwind CSS Hover Issue on Dynamic Elements

This repository demonstrates a bug where Tailwind CSS hover effects fail to apply to elements added to the DOM dynamically using JavaScript.  The issue occurs specifically when attempting to style elements that are added after the initial page load.  This is a common problem and this repo contains a solution.

## Problem
The main problem lies in when tailwind directives are not being applied. This is mostly due to the elements being added to the DOM after the initial page load or any other unexpected behavior.