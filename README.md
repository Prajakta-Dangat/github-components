name: Components Demo

on:
  push:

jobs:
  demo-job:
    runs-on: ubuntu-latest

   steps:
   - name: Step 1
     run: echo "Installing"

   - name: Step 2
     run: echo "Building"

   - name: Step 3
        run: echo "Testing"# github-components
