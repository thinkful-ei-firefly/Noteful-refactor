# Noteful-refactor
Refactor your Noteful project to use react context for displaying folders and notes. Once you've refactored to context, you'll implement an API request for fetching the folders and notes. You'll also implement the delete buttons to make API calls and update context accordingly.
Requirements

Refactor your Noteful application to use context instead of prop drilling.
Implement two fetch requests to two endpoints when the application mounts: /folders and /notes. Store the response from these requests using a setState in whichever component you were keeping your dummy state.
Implement the delete button for each note in the list in the main route and folder route.
Implement the delete button on the note page, if the delete is successful, redirect to the / path.
The API calls will be made to a local server called noteful-json-server that you'll need to have running separately to your noteful React application.
