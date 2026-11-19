# OAuth Lab
A simple Google OAuth 2.0 authentication project built using Node.js, Express.js, and Passport.js.
## Features
- Google account authentication
- Passport.js integration
- Retrieves the authenticated user's Google profile
## Technologies Used
- Node.js
- Express.js
- Passport.js
- Google OAuth 2.0
## Setup
1. Clone the repository.
2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the project root:

   ```env
   ClientID=your_google_client_id
   ClientSecret=your_google_client_secret
   ```

4. Start the server:

   ```bash
   node index.js
   ```

5. Open `http://localhost:3003` in your browser.

**Note:** Never commit your `.env` file or share your Google Client Secret.
