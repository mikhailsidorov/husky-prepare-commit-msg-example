# Husky prepare-commit-msg example

Example project with prepare-commit-msg hook configured to prepend branch name to commit message automaticaly

## Requirements

* bash

## Run

    npm install
    git checkout -b issue-123
    touch example.txt
    git add .
    git commit -m "My new commit"

Commit message will be `issue-123 My new commit`
