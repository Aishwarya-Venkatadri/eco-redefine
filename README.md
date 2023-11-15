# eco-redefine

# Project Title
"EcoRedefine - Redefining Ownership, Reducing Waste"

## Overview

What is your app? Brief description in a couple of sentences.
EcoRedefine - is a sustainable sharing platform where users can easily list and borrow shareable items. The platform aims to redefine ownership, reduce waste, and shrink carbon footprints by promoting a community-driven approach to conscious consumption.


### Problem

Why is your app needed? Background information around any pain points or other reasons.

In a world where consumerism often leads to environmental strain, " EcorRedefine" is a wonderful solution. We often buy things we don't really need, which can be harmful to our environment. But, this app encourages us to share and reduce the amount of resources we use to produce goods. By embracing the idea of sharing, we can contribute to a more sustainable future and make a positive impact on our planet.

### User Profile

Who will use your app? How will they use it? Any special considerations that your app must take into account.

For any individual who has the intent to reduce their environmental impact by borrowing and sharing items. Users can include anyone from environmentally conscious consumers to those looking for cost-effective and sustainable alternatives.

Considerations: User-Friendly Interface, Privacy and Security, Educational Content, Rating and Feedback System


### Features

List the functionality that your app will include. These can be written as user stories or descriptions with related details. Do not describe _how_ these features are implemented, only _what_ needs to be implemented.

1. **User Registration:**
   - As a user, I want to create an account on the app, providing necessary details.

2. **Product Listing:**
   - As a user, I want to easily list items I'm willing to share, including product details, images, and availability.

3. **Browsing Products:**
   - As a user, I want to browse through a variety of shared items, filter based on categories, and view product details.

4. **Product Borrowing:**
   - As a user, I want to request to borrow a specific item, initiate a conversation with the owner, and agree on borrowing terms.

5. **Communication Platform:**
   - As a user, I want a built-in messaging system to communicate with the owner of a shared item, discuss details, and finalize borrowing arrangements.

6. **Environmental Impact Tracker:**
   - As a user, I want to see the positive environmental impact of the items I've borrowed or shared, including reductions in carbon footprint and waste.

7. **User Ratings and Feedback:**
   - As a user, I want the ability to rate and provide feedback on the borrowing experience, contributing to a reliable and trustworthy community.

8. **Educational Content:**
    - As a user, I want access to educational content on sustainable living, the environmental impact of sharing, and tips for conscious consumption.



## Implementation

### Tech Stack

List technologies that will be used in your app, including any libraries to save time or provide more functionality. Be sure to research any potential limitations.
React Js, SCSS, Express.js, JWT (JSON Web Tokens), External API or Custom Implementation, Development Tools: GitHub/ VScode.


### APIs

List any external sources of data that will be used in your app.
TBH

### Sitemap

List the pages of your app with brief descriptions. You can show this visually, or write it out.

1. **Home Page:**
   - **Description:** Displays a hero image with the mission statement and objective of the app. Lists available products for borrowing and highlights the positive environmental impact of sharing.

2. **Login Page:**
   - **Description:** Allows users to log in to their accounts. Accessible when a user clicks on the "Borrow" button on the product tiles.

3. **User Dashboard:**
   - **Description:** Personalized dashboard for authenticated users. Displays listed items, borrowing history, and the environmental impact of shared items.

4. **Add Listing Page:**
   - **Description:** Appears after user authentication. Enables users to add new items to the sharing platform, including product details, images, and availability.

5. **Blog/Articles Page:**
   - **Description:** Features blog posts and articles related to sustainable living, eco-friendly practices, and success stories within the community.

6. **Testimonials Page:**
   - **Description:** Allows users to add testimonials about their positive experiences with the app, sharing insights and building community trust.

7. **About Us Page:**
   - **Description:** Provides an overview of the app's mission, values, and the team behind it. Includes information on the environmental impact of sharing.

8. **Environmental Impact Tracker Page:**
   - **Description:** Visualizes the positive environmental impact users have made by using the app. Includes metrics on carbon footprint reduction, waste reduction, etc.

9. **Settings/Profile Page:**
    - **Description:** Allows users to manage their profile, update personal information, and customize sharing preferences. Includes privacy settings.

10. **Educational Content Page:**
    - **Description:** Offers educational content on sustainable living, the environmental impact of sharing, and tips for conscious consumption.

11. **404 Error Page:**
    - **Description:** Custom error page that displays when a user navigates to a non-existent or inaccessible page.
    - 

### Mockups

Provide visuals of your app's screens. You can use tools like Figma or pictures of hand-drawn sketches.


### Data

Describe your data and the relationships between them. You can show this visually using diagrams, or write it out. 

### Endpoints

List endpoints that your server will implement, including HTTP methods, parameters, and example responses.

1. **User Authentication Endpoints:**
   - **POST /api/auth/register:**
   - **POST /api/auth/login:**

   - **POST /api/messages/send:**

2. **User Profile Endpoints:**
   - **GET /api/profile/:userId:**
   - **PUT /api/profile/update:**

These are just example endpoints, and the actual implementation may vary

### Auth

Does your project include any login or user profile functionality? If so, describe how authentication/authorization will be implemented.
 implement a simple login and user profile functionality using my own custom middleware and a dummy JSON for authentication. 
 
## Roadmap

Scope your project as a sprint. Break down the tasks that will need to be completed and map out timeframes for implementation. Think about what you can reasonably complete before the due date. The more detail you provide, the easier it will be to build.



### Sprint 1:

**Week 1: Days 1-3**

1. **Project Setup:**
   - Set up development environment.
   - Initialize a new React.js project using Create React App.
   - Set up an Express.js server.

2. **Frontend Development:**
   - Create the home page with a hero image and a grid of available products.
   - Implement basic styling for the home page.

3. **Backend Development:**
   - Create routes for retrieving a list of available products.
   - Set up dummy data for the products (name, description, owner).

**Week 1: Days 4-7**

4. **User Authentication:**
   - Implement a simple login page with a form.
   - Create a basic authentication middleware using a dummy user.

5. **Product Detail Page:**
   - Implement a product detail page that shows more information about a selected product.
   - Include a "Borrow" button that redirects the user to the login page.

### Sprint 2:

**Week 2: Days 1-3**

7. **User Profile:**
   - Develop a user profile page displaying basic user information.
   - Implement a route for updating user profile information.

8. **Add Listing Feature:**
   - Create a page for users to add new product listings.
   - Implement a basic form for adding product details.

9. **Backend Enhancements:**
   - Extend the backend to handle adding new product listings.
   - Implement routes for retrieving and updating user profile information.

**Week 2: Days 4-7**

10. **Integration:**
    - Connect the frontend components to the backend routes.
    - Ensure authentication is required for sensitive actions (adding listings, updating profiles).

11. **Styling and UI Polish:**
    - Refine the styling of pages for a more polished look.
    - Implement responsive design for better usability on different devices.

12. **Testing:**
    - Perform testing on different aspects of your application, especially focusing on user flows, authentication, and real-time communication.

### Sprint 3:

**Week 3: Days 1-3**

13. **Documentation:**
    - Write basic documentation for setting up the project, running it locally, and using the app.

14. **Deployment:**
    - Deploy your application to a platform like Heroku or Vercel.

15. **Feedback and Iteration:**
    - Gather feedback from users or peers.
    - Identify areas for improvement and plan for future iterations.



## Nice-to-haves

Messaging/Chat Setup:

Set up Socket.io for real-time communication.
Create basic chat components. 
