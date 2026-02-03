## Aplication Summary
This application is a simple counter dashboard that allows users to increment or decrement a numeric value
using buttons. It demonstrates basic user interaction, state management, and layout in Jetpack Compose, showing 
how the UI automatically updates when the counter value changes in a declarative Android app.

## Aplication Screenshots
<img width="419" height="928" alt="Screenshot 2026-02-02 at 8 18 05 PM" src="https://github.com/user-attachments/assets/36fed644-c33d-420e-8141-82cb93b5dbb9" />

## Device/emulator/SDK version used
Medium Phone API 36.1

## Q&A
### What makes Compose declarative?

Compose is declarative because you describe what the UI should look like based on the current state, not how to update it step by step. When the state changes, Compose automatically recomposes the UI to reflect that state.

### Where is state stored?

In Jetpack Compose, state is stored in state objects, typically using remember { mutableStateOf(...) } inside a composable (or in a ViewModel for longer-lived state). When this state changes, Compose automatically updates the UI that reads it.

### Which composables are stateful vs stateless?

Stateful composables store and manage their own state, while stateless composables only display data and trigger events without holding state themselves.

### How does this differ from XML + View logic?

In XML + View logic, UI updates are imperative, requiring you to manually find views and change them when data changes. In Compose, UI is declarative, automatically updating based on state without manually manipulating views.

