# Vote for Vice Chancellor Elections

this project should be viewd in a prototype logic manner . 

# if file dont run because of a json.launch just run using you local server IDE or retry twice offline

# Below are the guideline and logic a user should utilise to understand the sequence

Welcome to the **Vote for Vice Chancellor Elections** platform! This web application allows users to sign up, log in, view candidates, and cast their votes in a secure and user-friendly voting system. Built with **Firebase** for user authentication and data management, this platform ensures a smooth experience with features like email validation and vote tracking.

## Key Features

- **User Authentication:**
  - **Sign Up & Sign In**: Users can create an account or log in with their email and password.
  - **Password Recovery**: Forgot your password? Request a reset via email.

- **Candidate Selection & Voting:**
  - **View Candidates**: Users can view a list of candidates running for Vice Chancellor.
  - **Vote Once**: A timer counts down, limiting each user to a single vote.
  - **Vote Confirmation**: After voting, users are prompted to rate their experience.

- **Profile Management:**
  - **Profile Page**: After signing in, users can view and update their profile and voting history.

- **Email Validation:**
  - **Mailcheck.ai Integration**: Validates email addresses to ensure only legitimate sign-ups.

## How It Works

1. **Welcome Page:**
   - When you first open the platform, you'll be greeted with a **Welcome Page**. Click **Sign In** to access the next step.

2. **Sign In Page:**
   - On the **Sign In Page**, enter your email and password to log in. If you don’t have an account, click **Create Account** to sign up.

3. **Create Account:**
   - Fill in your email and password to create an account. Once you're done, you'll be redirected back to the **Sign In** page to log in.

4. **Forgot Password:**
   - If you forget your password, you can request a password reset email directly from the platform.

5. **Profile Page:**
   - Once logged in, you’ll be taken to your **Profile Page**. Before casting your vote, you'll need to review all candidates.

6. **Voting Page (Homepage):**
   - The **Voting Page** features a poll with a countdown timer. You can only vote once per election.
   - After voting, you'll be prompted to rate your experience.
   - In the menu, you can access your **Profile**, **Settings**, **Help**, and **Sign Out** options.

   # RECAP:

WELCOME.HTML > SIGN IN.HTML > CREATE ACCOUNT.HTML > PROFILE.HTML > HOMEPAGE.HTML

# HTML FILES ARE IN THE PRIMARY FOLDER. MEANWHILE JAVASCRIPT AND NO SQL ARE IN A SUBFOLDER INTERGREATED TOGETHER FOR BETTER DISTINGUSHING

## Important Notes

- This project is a **prototype** and is not hosted on a live server.
- To use it, you'll need to run the project locally using a development environment such as **Visual Studio Code** or another web server.
- The platform is designed for local use, meaning you can view and interact with the features directly on your **localhost**.

## Firebase Setup

This project uses **Firebase** for user authentication and database management. 

### Steps to Set Up Firebase:

1. **I created a Firebase Project to handle all Email/Password Authenticatio:**
   - Visit the [Firebase Console](https://console.firebase.google.com/), **Email/Password Authentication** and **Firestore Database**.

2. **Add Firebase Configurations:**
   - i copied my Firebase configuration details from the Firebase Console and included them in your `firebase-config.js` files to connect the app to Firebase. no sql as requested

3. **Mailcheck.ai Integration:**
   i Signed up at [Mailcheck.ai](https://mailcheck.ai/) -up. to mailcheck all email that are being used by users for authencAuthentication

---

## Running Locally

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/vote-for-vice-chancellor.git
