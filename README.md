# API Documentation

## Overview

This API is designed for user management and friend interactions using Sequelize for ORM and JWT for authentication. It supports functionalities such as user login, password management, user profile updates, and friend management. The JWT token expiration is set to 10 minutes, and an API is provided to refresh the token.

## Features

1. **Sign In**
   - Users can log in using their email or mobile number.

2. **Forgot Password**
   - Users can request an OTP to be sent to their email. After verifying the OTP, users can set a new password.

3. **Sign Up**
   - Users can sign up by providing general information, including their Google address with latitude and longitude.

4. **Update Profile**
   - Users can update their profile information, including their address and other general details.

5. **Search Friend**
   - Users can search for other users by name, mobile number, email, or distance. Users who are already friends are not listed in the search results.

6. **Friend List**
   - Users can view their entire friend list and have the ability to remove friends.

7. **Friend Request**
   - Users can accept or reject incoming friend requests.

8. **View Profile**
   - Users can view the profile of any other user.

## Authentication

- **JWT Token**
  - JWT tokens are used for authentication.
  - Token expiration time: 10 minutes.
  - API endpoint for refreshing the token is provided.

## Setup

1. **Install Dependencies**
   ```bash
   npm install
2. extract both api and client npm i and then start 
   forntend - npm start
   backend - npm run dev 
