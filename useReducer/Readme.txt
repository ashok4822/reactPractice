useReducer is an alternative to useState for managing state transitions based on actions. It’s very similar to how Redux works.

Syntax:    const [state, dispatch] = useReducer(reducer, initialState);

state → current state

dispatch(action) → function to send actions

reducer(state, action) → function that determines how state changes


✅ When to Use useReducer

| Use `useState` when…              | Use `useReducer` when…                      |
| --------------------------------- | ------------------------------------------- |
| State is simple and local         | State is complex or has multiple sub-values |
| You only need to update one value | Updates depend on action types              |
| State transitions are independent | State transitions are logically grouped     |


