## Terms

- action creator is a function
- action is an object

## To do

- TODO list ideas from https://egghead.io/lessons/javascript-redux-extracting-action-creators
  - Action creator could be non-deterministic, which reducer could not, e.g. global state could be changed and merged inside an action from an action creator.

## How to create actions?

- It is considered _best practice_ to define action type as a constact string, e.g. `const ADD_NOTE = 'ADD_NOTE';`
  - For rationale see http://redux.js.org/docs/basics/Actions.html
- Use https://github.com/acdlite/redux-actions
  - TODO elaborate why and when it should be used
