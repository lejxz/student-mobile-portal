# student-mobile-portal

A student portal project for practicing Git and GitHub collaboration.

## Components

### StudentProfile (`StudentProfile.jsx`)
A reusable component displaying fictional student profile details, including name, student ID, and degree program.

## Usage & Integration Example

To render the `StudentProfile` component in your React application:

```jsx
import React from 'react';
import StudentProfile from './StudentProfile';

function App() {
  return (
    <div className="app-container">
      <h1>Student Portal</h1>
      <StudentProfile />
    </div>
  );
}

export default App;
```
