# Today I Learned

Welcome to **Today I Learned**, a web app where users can document daily learning experiences, making it easy to keep track of interesting things learned each day. The platform allows users to create, view, and interact with posts that summarize their learnings.

## Website

Visit the live version of the app [here](https://todayilearned-hala.netlify.app/).

## Features

- **Add New Learnings**: Users can post new learnings or insights they've gained each day.
- **View Past Learnings**: Users can view a list of all previous posts in chronological order.
- **Edit/Delete Posts**: Easily manage your learning posts by editing or deleting entries as needed.
- **Responsive Design**: The app is fully responsive, offering a smooth experience across devices, including mobile and desktop.

## Tech Stack

The project is built with:

- **HTML5**
- **CSS3**
- **JavaScript (ES6+)**
- **React.js**: For building the user interface.
- **Supabase**: Used as the backend for handling the database and authentication.
- **Netlify**: Deployed the app for hosting.

## Setup Instructions

To run this project locally, follow these steps:

### 1. Clone the repository:
   ```bash
   git clone https://github.com/hlbels/Today-I-Learned.git
   cd today-I-learned
```

## Setup Instructions

To run this project locally, follow these steps:

### 2. Install dependencies:
Make sure you have [Node.js](https://nodejs.org/) installed, then run:

```bash
npm install
```

### 3. Add environment variables:
Create a `.env` file in the root of the project and add your **Supabase** credentials:

```bash
REACT_APP_SUPABASE_URL=your-supabase-url
REACT_APP_SUPABASE_ANON_KEY=your-supabase-anon-key
```
### 4. Run the project:
Start the development server:

```bash
npm start
```
Your app should now be running on http://localhost:3000.

### 5. Build for production:
To create a production-ready build, run:

```bash
npm run build
```

### 6. Folder Structure
Here's a simplified overview of the project structure:

```bash
today-I-learned/
├── public/                # Static assets
├── src/                   # Source code
│   ├── components/        # React components
│   ├── supabase.js        # Supabase client setup
│   └── App.js             # Main app component
├── .env                   # Environment variables (not included in Git)
├── .gitignore             # Files and directories ignored by Git
├── package.json           # Dependencies and scripts
└── README.md              # Project documentation
```
### How It Works

- **Supabase Integration**: The app uses Supabase to handle user data and posts. Each post is saved to a Supabase database, making it easy to store and retrieve posts in real-time.

- **Frontend**: The frontend is built with React.js, utilizing reusable components and React hooks for state management.

### Future Improvements

- **User Authentication**: Implement user login so users can manage their own learning posts securely.
- **Search Functionality**: Add a feature to search through the learnings by keyword or category.
- **Categories/Tags**: Enable users to categorize their learnings for easier organization.
- **Dark Mode**: Add a toggle for light/dark themes to enhance the user experience.

### Contributions

Contributions are welcome! If you want to improve the project or fix a bug, feel free to fork the repository, create a new branch, and submit a pull request.



