# Global groupware User Management

This React application integrates with the Reqres API to perform basic user management functions, including authentication, user listing, and user editing/deletion.

**Features:**

- **Authentication:**
    - Login screen with email and password fields.
    - Validates user credentials.
    - Stores the authentication token securely.
    - Redirects to the user list page on successful login.
- **User Listing:**
    - Fetches and displays a paginated list of users from the Reqres API.
    - Displays user information (first name, last name, avatar).
    - Implements pagination for easy navigation through user data.
- **User Editing:**
    - Enables editing of user details (first name, last name, email).
    - Displays a form pre-filled with existing user data.
    - Validates user input.
    - Updates user information on the server.
    - Displays success/error messages based on API responses.
- **User Deletion:**
    - Allows deletion of individual users.
    - Confirms user action before deletion.
    - Removes the deleted user from the list.
    - Displays success/error messages based on API responses.

**Technologies:**

- **React:** Frontend framework.
- **Axios:** For making HTTP requests to the Reqres API.
- **[CSS Framework]** (e.g., Bootstrap, Material-UI, Tailwind CSS) - Choose and specify the CSS framework used.
- **[State Management]** (Optional) - If used, specify the library (e.g., Redux, Context API).

**Getting Started:**

1. **Clone the repository:**
   ```bash
   git clone <repository_url>
