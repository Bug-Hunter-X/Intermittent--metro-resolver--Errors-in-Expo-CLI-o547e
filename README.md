# Expo CLI Intermittent 'metro-resolver' Build Errors

This repository demonstrates a bug encountered while using the Expo CLI to build a React Native application. The issue involves intermittent build failures stemming from the `metro-resolver` package, with no consistent error message or clear cause within the application code itself.

## Problem Description

The project would occasionally fail to build during development, presenting unpredictable errors related to `metro-resolver`. These errors halted the development process and could not be consistently reproduced, making debugging extremely challenging.

## Solution

The solution involves reviewing and potentially updating dependencies. Cleaning the cache or reinstalling packages can also help resolve these types of intermittent issues. In some cases, specifying the correct version of React Native can also resolve these issues. The code in `expoBugSolution.js` shows how to clean the cache, and potentially reinstall dependencies.

## Reproduction

The provided `expoBug.js` file does not represent the original source of the error but serves as a placeholder to indicate where the problem manifested.  The solution focuses on addressing the broader build environment issues rather than a specific code flaw. Please refer to the Solution section for steps to resolve.