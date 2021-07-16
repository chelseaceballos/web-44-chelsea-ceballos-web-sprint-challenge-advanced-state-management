# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?
    Similar to redux libraries, context api helps share data through out the component tree and prevents the need for prop drilling.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
        Action- an action describes the event, and return an action object
		Reducers- a function that takes in the action and previous state, and returns a new state
		Store- Allows to connect state values and reducers actions to any components
	The store is considered to be the “single source of truth” because the only way to change data is to dispatch a redux action(s) that will trigger a change is state with in the reducer causing a re-rendering.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?
With Redux Thunk middleware, you can write action creator(s) that are returned as a function instead of an action. On the same note, thunk can delay the dispatch of the action or allow the action to be dispatched if it meets a specific condition.

4. What is your favorite state management system you've learned and this sprint? Please explain why!
    I really enjoyed redux, I am far from great at it, but Redux really forced me to see the code in a different logic. It's honestly a huge brain tease but I feel like with more practice I can continue to get a greater understanding.  (async redux was a huge challenge though. I get it but i really really needed to reference the guided project)