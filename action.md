# Testing Workflow

name: Example

on:
  push:
    branches: [ testing ]


<!-- Print Somthing -->
jobs:
  example:
    runs-on: ubuntu-latest
    steps:
      - name: Print
        run: echo "Hello World"
      - name: Print
        run: echo "::debug::This is a debug message"
