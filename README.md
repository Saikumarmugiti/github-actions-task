# github-actions-taskname: Shell Commands

on: [push]

jobs: 
  run-shell-command: 
    run-on: ubuntu-latest
    steps: 
      - name: echo a string  
        run: echo "Hello World"
      - name: multiline script
        run: |
          node -v
          npm -v   
