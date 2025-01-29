# React Native AsyncStorage Inconsistent Null Return

This repository demonstrates a bug where AsyncStorage in React Native inconsistently returns null when retrieving data.  The issue is not related to data not being stored; the data is stored correctly, but retrieval fails intermittently.

The `bug.js` file shows the buggy code.  The `bugSolution.js` file provides a potential solution.  This problem is especially frustrating due to its inconsistent nature, making debugging challenging.

**To Reproduce:**
1. Clone this repository.
2. Run the app.
3. Observe that retrieving data from AsyncStorage sometimes returns null, even when data has been successfully stored.

**Potential Solution:** The solution might involve handling potential errors more effectively or investigating AsyncStorage's internal state.