This repository demonstrates an issue with inconsistent screen dimension retrieval using `Dimensions.get('window')` in React Native. The `bug.js` file shows the problematic code, and `bugSolution.js` offers a more robust approach using `react-native-screens` and the `useDimensions` hook.  This approach ensures accurate dimensions even across orientation changes and on Android devices.