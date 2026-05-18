# API Testing Project — AutomationExercise.com

## Overview
Manual API testing project using Postman for AutomationExercise.com production API.

## Tool
Postman

## Test Coverage
| Flow | Description | Test Cases | Result |
|------|-------------|------------|--------|
| Flow 1 | Full User Lifecycle (Create, Login, Get, Update, Delete) | 8 | ✅ 100% Pass |
| Flow 2 | Products & Search Cross-Validation | 4 | ✅ 100% Pass |
| Flow 3 | Negative Integration (User Cycle) | 6 | ✅ 100% Pass |
| Flow 4 | Negative Login Scenarios | 5 | ✅ 100% Pass |

## Highlights
- Dynamic email generation using {{$timestamp}} to avoid conflicts
- Environment variables used for request chaining
- Validated response codes and JSON body data
- Covered both Positive and Negative scenarios
