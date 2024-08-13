# Album Collection

## Features
- **Fetch Album Data**: Retrieves album information from the JSONPlaceholder API.
- **Album List Display**: Shows a list of albums, including user IDs, album IDs, and titles.
- **Delete Albums**: Allows users to delete albums by clicking the "delete" button.
- **Update Album Details**: Enables users to modify album details by clicking the "update" button and editing the input fields in the form.

## Dependencies
This component requires the following library:

- **React**: Version "^16.8.0" or later

Make sure these dependencies are installed in your project.

## API Interaction
The component communicates with the following API endpoints:

- **GET**: `https://jsonplaceholder.typicode.com/albums` - Fetches the list of albums.
- **DELETE**: `https://jsonplaceholder.typicode.com/albums/{itemId}` - Deletes an album by its ID.
- **PUT**: `https://jsonplaceholder.typicode.com/albums/{itemId}` - Updates an album with the specified ID.
