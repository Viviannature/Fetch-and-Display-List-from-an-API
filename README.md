# Fetch-and-Display-List-from-an-API

Objective: 
The goal of this project is to build a functional React component that fetches data from an API and displays a list of items. You will also create a reusable list component to follow best practices in component reusability and separation of concerns.

Fetches a list of items from a public API (using JSONPlaceholder as an example).

Displays the list using a reusable ListComponent.

Handles loading, error, and empty state scenarios.

Uses React functional components and hooks (useState, useEffect).

Uses semantic HTML for accessibility.


✅ Final Output:
App (Parent Component) fetches data from an API.

ListComponent is a reusable UI component that displays the list.

Graceful handling of loading, errors, and empty data.

📁 File Structure
Assuming you're using Create React App or a similar environment.

1. ListComponent.js – The Reusable List Component

   💡 renderItem is a function you pass from the parent to customize how each item is displayed.

2. App.js – The Parent Component

3. index.js – Entry Point

✅ Best Practices Followed
✅ Functional components and hooks.

✅ Reusable component for list rendering.

✅ Customizable item rendering via renderItem.

✅ Semantic HTML (<ul>, <li>, <div>).

✅ Graceful error/loading/empty handling.

✅ Separation of concerns between UI and data logic.

🔁 Want to Use Another API?
Just replace the fetch() URL in App.js. Example:

Then adjust renderItem to suit that API’s data structure.


