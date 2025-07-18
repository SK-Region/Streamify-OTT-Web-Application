# Streamify – A Django-based OTT Platform Clone

**Streamify** is a full-stack web application that replicates the core features of an OTT (Over-The-Top) streaming service. It offers a seamless user experience with dynamic content rendering, user authentication, and a sleek UI built with Bootstrap.

This project demonstrates how to build scalable and interactive web applications using Django for the backend and Bootstrap for frontend styling.

---

## Tech Stack

**Backend:**  
- Django Framework  
  - User Authentication (Sign Up / Login)  
  - URL Routing and Views  
  - Database integration (user info, content metadata)  
  - Template rendering and dynamic content display  
  - Business logic and backend management  

**Frontend:**  
- Bootstrap  
  - Responsive, mobile-friendly layout  
  - Clean and intuitive UI design

**Database:**  
- SQLite (default for development)  
  - Stores user credentials, session info, profile data, and media metadata  
  - Used for verifying login credentials and managing user-specific data like watchlists

---

## Key Features

### Start Page  
The landing page for all users. Displays previews of available content with Sign Up and Log In buttons in the header.

### Sign Up  
New users can register by entering basic details. After successful registration, they're redirected to the login page.

### Log In  
Registered users can log in with their credentials and are redirected to the Home Page on success.

### Home Page (For Logged-In Users Only)  
Displays categorized sections such as:  
- Most Watched Movies  
- Most Watched Series  
- New Releases  

Navigation bar includes access to:  
- Dashboard  
- Profile  
- Genre  
- My List  
- Movies  
- Series  
- Search  
- Popular

### Profile Page  
Users can view and update their profile information.

### Genre Page  
Displays movies/series filtered by genre: Romance, Comedy, Action, Horror, Thriller, and more.

### My List  
Users can add movies or series to a personalized "Watch Later" list.

### Movies Page  
Displays all movies, with genre-based filtering.

### Series Page  
Displays all TV series, also filterable by genre.

---


