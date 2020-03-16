# Coding Challenge

The functionality of this project is to parse through a nested object and return all the views that match the selector entered by the user.

## How to use

1. Ensure you have a current version of node
2. Clone repo on local machine.
3. Run 'npm i -g ./' inside project root directory



The different types of selectors are classes, classNames, and identifiers.

To use class selector, run command 'selector [put class here]'.
To use classNames selector, run command 'selector .[put className here]'.
To use identifier selector, run command 'selector /[put identifier here]'.


### Compound Selector Attempt

On branch 'multiSelect-attempt', there is a solution for compounding multiple selectors together, such as the command 'selector StackView .column' to view all StackViews with a className of column. To use this functionality, simply add all the selectors separated by a space. 
