- Add at least 3 Project features

---

Answer: Here are three project features related to this project:

- Update the card data using fetch.
- Create a state variable, to store the selected courses. This state represents the user's course selection and calculated the total credits and amount.
- To display toast notifications for events (e.g., exceeding credit limits or adding duplicates)

===========================================================================

- Discuss how you managed the state in your assignment project.

---

Answer: In my assignment project, I managed the state using React's built-in state management capabilities, particularly the useState hook.

- I kept the all data in "data.json" file. then I use the fetch function in the useEffect hooks to set the data in the useState.

- When a user clicked the "Select" button on a course card, I used the setState function to add the selected course object to the "enrolls" array.

- To calculate the total credits of the selected courses, I maintained another state variable called "creditTotal". This variable kept track of the cumulative credits of all the selected courses.

- Whenever a course was added, I updated the totalCredits state accordingly. This involved recalculating the total credits based on the current selection and using the "setCredits" function to update the state.
