This repository demonstrates a common yet subtle bug in React Native's FlatList component.  Modifying the data source directly within the `renderItem` function can lead to unpredictable behavior, including infinite loops and rendering inconsistencies.  The `bug.js` file shows the problematic code, while `bugSolution.js` presents the correct approach using immutable data updates and state management.