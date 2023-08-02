# T3A2 - PART A

<div align="left">
  <img src="./docs/van-voyage-logo.png" width="200"><br>
</div>

<br>

# Van Voyage (Planning and Documentation)

[Part A - Docs](https://github.com/van-voyagers/T3A2-A-van-voyage-docs) <br>
[Part B - Client](https://github.com/van-voyagers/T3A2-B-van-voyage-client) <br>
[Part B - Server](https://github.com/van-voyagers/T3A2-B-van-voyage-server)

<br>

### Created by:

- [James Boland](https://github.com/JRBoland)
- [Jordan Aston](https://github.com/jordanaston)

<br>

### Table of contents:
1. [Description of website](#purpose)
   1. [Purpose](#purpose)
   2. [Functionality / features](#functionality)
      1. [User Onboarding](#onboarding)
      2. [Van Browsing](#browsing)
      3. [Booking / Contact System](#booking)
      4. [Admin CRUD (Postman)](#crud)
      5. [Review System](#reviews)
   4. [Target Audience](#target)
   5. [Tech Stack](#tech)
2. [Dataflow Diagram](#dfd)
3. [Application Architecture Diagram](#aad)
4. [User Stories](#users)
   1. [User Personas](#personas)
   2. [User Stories](#stories)
5. [Wireframes](#wireframes)
   1. [Desktop](#desktop)
   2. [Tablet](#tablet)
   3. [Mobile](#mobile)
   4. [Website flow & navigation](#wfflow)
   5. [Link to Figma file](#figma)
   6. [Design iterations (agile)](#wfiterations)
6. [Trello](#trello)
7. [Other Diagrams](#otherdiagrams)
8. [References](#references)
   
<a name="purpose"></a>
## Purpose: 

The purpose of this application is to facilitate the operation of a hypothetical business that rents out a small fleet of vintage, refurbished camper-vans. It aims to provide a user-friendly platform where customers can conveniently book camper-vans and view their availability in real-time. The application is designed to cover new user registration, profile management, booking logs, availability tracking, and booking confirmation. It is intended to have an inbuilt review system, fostering a transparent and interactive space for customers to share their experiences.

The application is required to be scalable and extensible, built with the potential to integrate additional features or modules in the future, such as search filters, personalised recommendations, payment system, live chat messaging, admin dashboard and an instagram carousel.

<br>

<a name="functionality"></a>
## Functionality & Features: 
<a name="onboarding"></a>
### **User Onboarding**

- **Account Creation:** Users can register for an account via a straightforward sign-up process that only requires email and password.

- **Logging In:** A dedicated login page provides secure access to users' accounts with email and password for verification.

- **User Profile / Account Page:** After creating an account, users can manage their personal profile by updating details such as email, password, first name, last name, phone number, address, date of birth, and license number. Here they also have the ability to delete their account.

- **Logging Out:** Users can securely log out of their accounts when they're done with their session, ensuring their data remains secure.
<a name="browsing"></a>
### **Van Browsing**

- **Van Details View:** Each vintage van is given its own section with an image carousel, details of van features and pricing that updates when dates are selected.

- **Real-time Availability Check:** Users can immediately see whether their chosen van is available for their preferred dates via a dynamic calendar.
<a name="booking"></a>
### **Booking / Contact System**

- **Select Van / Date / Duration:** Users can easily select their van of choice, specify their rental duration, and see the total cost of the booking prior to confirming.

- **Booking Confirmation:** Users will be able to see the details of their booking in their accounts page with the ability to cancel the booking if needed.

- **Contacting Van Voyage:** If users need to contact the business for any reason such as updating booking details or account issues, they can do so via the contact form on the contact page.
<a name="crud"></a>
### **Admin CRUD (Postman)**

- **User Management:** Admins can manage all user accounts, including creation, deletion, and updates.

- **Van Management:** Admins have full control over van details like pricing and availability.

- **Booking Overview:** Admins can access and manage all bookings in the database.

- **Reviews:** Admins have complete control over any reviews posted to the website.
<a name="reviews"></a>
### **Review System:**

- **Post Booking Reviews:** Users can share their experiences and thoughts after their booking is confirmed. Reviews consist of a start rating and a comment.

- **Featured Reviews Carousel:** The most recent reviews are dynamically displayed in a carousel on the home page.

<br>

<a name="target"></a>

## Target Audience: 

The application's target audience is broad and inclusive, designed to cater to anyone with an interest in hiring vintage camper-vans. This could range from individuals planning a unique weekend getaway, families seeking an alternative vacation experience, to aficionados of vintage vehicles who relish the opportunity to experience these refurbished camper-vans.

While the application will be designed with ease of use in mind, it will cater to both tech-savvy users who are comfortable navigating digital platforms, and less tech-oriented individuals who may require a simpler, more intuitive user interface.

<br>

<a name="tech"></a>

## Tech Stack: 

<br>

### **Frontend:**

<img src="docs/tech-stack/react-logo.png" alt="React" width="50">&nbsp;&nbsp;&nbsp;<img src="docs/tech-stack/tailwind-logo.png" alt="Tailwind CSS" width="50">

<br>

### **Backend:**

<img src="docs/tech-stack/express-logo.png" alt="Express.js" width="50">&nbsp;&nbsp;&nbsp;<img src="docs/tech-stack/node-logo.png" alt="Node.js" width="40">&nbsp;&nbsp;&nbsp;<img src="docs/tech-stack/mongodb-logo.png" alt="MongoDB" width="170">

<br>

### **Testing:**

<img src="docs/tech-stack/jest-logo.png" alt="Jest" width="80">

<br>

### **Design:**

<img src="docs/tech-stack/figma-logo.png" alt="Figma" width="30">

<br>

### **Deployment:**

<img src="docs/tech-stack/mongodb-atlas-logo.png" alt="MongoDB Atlas" width="120">&nbsp;&nbsp;&nbsp;<img src="docs/tech-stack/heroku-logo.png" alt="Heroku" width="120">&nbsp;&nbsp;&nbsp;<img src="docs/tech-stack/netlify-logo.png" alt="Netlify" width="120">

<br>

<a name="dfd"></a>
## Data Flow Diagram:

<img src="./docs/diagrams/DFD.png" width="1200">

<br>

<a name="aad"></a>
## Application Architecture Diagram:

<img src="./docs/diagrams/AAD.png" width="1200">

<br>

<a name="users"></a>
## User Stories:

**Format:**

Story #:

_As a [ persona ], I want to [ __ ], so that [ __ ]._

Acceptance Criteria:

- Requirements to complete a user story.

Definition of done:

- ‘Ultimately, the user story is considered complete when…’

---

Click the dropdowns below to view user stories and user personas.

_User personas are included to consider the different ways or approaches different users may take to using the website._

_User stories and personas may contain ~~strikethroughs~~, indicating revision._

<a name="personas"></a>
<details><summary><h3>User Personas</h3></summary>

<details><summary>Potential User</summary>

### **Potential user (AKA: unregistered user, “browsing” user)**

  - Melanie: Retiree / 62
    - Not very technologically savvy. Needs a clear way to browse available vans and instructions on how to book.
  - Jack: Student / 22
    - Wishes to book a van so that he and his partner can go on a road trip for a weekend trip. May be planning to go onto dirt roads/camping locations so will need a suitable van.
  - Chad & Stephanie: Couple / late 20’s
    - Wishes to browse vans and their interior in detail so that they can find a van that fits their ‘aesthetic’.
  - Jerry: Banker / 31
    - Wishes to compare the pricing of hiring a van as they are tossing up between a few different rental options.
  - Jeremiah: Arborist / 29
    - Wants to find contact information so that they can call or email the business with further, specific questions as well as confirm the legitimacy of the site. Wants to be able to check reviews as a way of finding out more about the business from the customer’s perspective.

- The following “potential user” personas were removed with the **first** iteration of revised user stories:

  - ~~Jill: Mum / 35~~
    - ~~Wishes to browse vans so that she can see if there is a van available that will be suited for her, her partner, and her 18 month old baby.~~
      - _The user story for “Jack” meets the same requirements of the user being able to view the van description. The current version of MVP does not include additional extras (such as baby seats or bedding)._
  - ~~Jay: Film director / 29~~
    - ~~Wants to check out the legitimacy of the site (instagram carousel, reviews)~~
      - _Legitimacy may be checked via contact information, reviews added to “Jeremiah” user story. Instagram carousel removed from MVP and is considered as a N2H._

</details>

<details><summary>Registered User</summary>

### **Registered User (AKA: existing user, returning user)**

  - Jarrod: Plumber / 32
    - Wants to be able to compare pricing and availability of dates that are available for booking, to plan their week off from work.
  - Jared: Sparkie / 33
    - Wants to be able to receive confirmation of expected cost before finalising the booking.
  - Jacquie: Teacher / 26
    - Wants to post a review after her experience with the business
  - John: Student / 25
    - Wants to have some control over their profile settings and to be able to view and manage their current bookings

- The following “registered user” personas were removed with the **first** iteration of revised user stories:

  - ~~Greg: Tutor / 41~~
    - ~~Has previously registered but has forgotten their password. Wants to recover their password.~~
      - Not in current MVP.
  - ~~Julie: CEO / 49~~
    - ~~Has a very busy schedule and is fairly disorganised. Wants to receive booking confirmation with dates and all relevant information so that she can forward it to her assistant (to block her calendar? idk haha) without little interference.~~
      - Not in current MVP, email notification moved to N2H.

</details>

<details><summary>Admin User</summary>

### **Admin User (AKA: business user, vendor)**

  - Vance: Business owner / 38
    - Wants to be able to add, edit and delete vans and their details (including pricing, image, description, availability, etc.) from the fleet that is available on the site.
  - Vanessa: Business partner / 38
    - Wants to be able to view relevant details of all registered users, as well as the ability to delete bot/spam user accounts.

</details>

</details>
<a name="stories"></a>
<details><summary><h3>User Stories</h3></summary>

<details><summary>Potential User</summary>

### **Potential User:**

Story 1:

_As a potential user, I want to be able to browse the available vans and their details without having to create an account, so that I can make an informed decision on whether to proceed with the booking._

Acceptance Criteria:

- Individual van page to display responsive, informative, text and image content, including various images from different angles of the same van.
- Each van (object in the database) to hold details of the van, posted by the admin user.
- Vans and their details are to be viewable without authentication (or authorisation).

Definition of done:

- A user is able to browse vans without any required authentication.

Story 2:

_As a potential user, I want to be able to navigate the website easily, so that I may understand more about the business._

Acceptance Criteria:

- Each page on the website displays accessible, responsive, informative, text and image content and action buttons.
- The website should adhere to suitable UI/UX and accessibility standards, with a clear layout and clean, readable labels.
- Clearly labeled and accessible site navigation across devices.

Definition of done:

- The website adheres to UI/UX and accessibility principles. The content displayed is readable and intuitive.

Story 3:

_As a potential user, I want to be able to easily sign up, so that I may make a hassle-free booking._

Acceptance Criteria:

- New user registration/sign-up form; clear instructions on how to do so for each step.
- A new user can not submit a registration form unless necessary fields are filled out.
- Information from the form to be used to create a new user, and then stored in the database.
- ~~Confirmation email~~

Definition of done:

- A potential user is able to create and register their account and complete a booking. The newly created user is to be added to the database.

Story 4:

_As a potential user, I want to find out more information about the business, so that I can ensure the site and business are legitimate._

Acceptance Criteria:

- Easily accessible contact information/page, with resources on how a potential user may contact the business (contact form, email, number, mock ABN).
- Reviews from other users.
- Displayed accessible social media presence, ~~Instagram~~.

Definition of done:

- Reviews are displayed and external business links (eg. ~~Instagram~~).

</details>

<details><summary>Registered User</summary>

### **Registered User**

Story 1:

_As a (not currently logged in) registered user, I want to be able to log into my account, so that I’m authorised to book a van._

Acceptance Criteria:

- Login button is accessible via all main pages that takes the user to the login form.
- Login form with email and password placeholder text.
- Authenticated and authorised users (All authenticated users are authorised to book a van unless they do not have a valid license)
  - Potential additional criteria (currently all N2H):
    - Authorisation requires email confirmation
    - “Remember me?” button and function on the login form.
    - “Forgot your password?” button (and the process that follows) on the login form.

Definition of done:

- Users can log in.

Story 2:

_As a registered user, I want to be able to book a van between certain dates, so that I can hire the van for the selected timeframe._

Acceptance Criteria:

- Ability to complete the booking process for a specific van for set dates.
- Booking form with calendar date blocks.
- ~~A confirmation email with further hire information.~~
- Other users are unable to book dates in which a van is hired out.

Definition of done:

- User can book their desired van, checking the availability by date. ~~User to receive information confirmation~~. User’s “Upcoming Trips” (under bookings) section in Account page to reflect newly added booking. Information to be updated in the database.

Story 3:

_As a registered user, I want to be able to update my personal information, so that it may reflect any changes I make to my address, email, etc._

Acceptance Criteria:

- User panel (Account Settings on Account page) in which the user has full CRUD over their account information. Some information to remain locked to the account (email, D.O.B, and name)
- Mandatory fields to require information.

Definition of done:

- User can update their personal information, with the user’s information in the database reflecting the change.

Story 4:

_As a registered user, I want to be able to view and manage my bookings, so I can confirm the dates and plan my trip._

Acceptance Criteria:

- Booking History panel on the Account page to show upcoming and previous booking information, such as dates, total cost, and van name.
- The user is able to cancel a booking from the Booking History panel.
- Text indicating that users can make changes to their booking by contacting the business.

Definition of done:

- User can view their bookings from the account page. User can manage or has instruction on how to manage their bookings. Bookings to display relevant information.

Story 5:

_As a registered user, I want to be able to log out of my account, so that I can end my session._

Acceptance Criteria:

- Logout button that signs the current user out.
  - Potential additional criteria (currently N2H):
    - If in the booking stages, or if in the process of any other action (cancellation, updating information) popup informs the user that logging out will not save their progress.

Definition of done:

- Users can log out.

</details>

<details><summary>Admin User</summary>

### **Admin User (Business User)**

_(Business/Admin User to have same user story as Registered User stories 1 & 5 (logging in and out))_

Story 1:

_As a business admin user, I want to be able to update my van inventory and their details, so that the vans and their information displayed are accurate._

Acceptance Criteria:

- Admin-level authentication to have authorisation for full CRUD over the van objects stored within the database.
  - Considering the the timeframe and current state of MVP, the admin is to perform CRUD operations through Postman.
- Van objects with their information to be stored in MongoDB, certain properties to have data type validation (dates, prices(integer), etc.).
  - MongoDB is to be connected to the front end (built with React) to accurately reflect and display the vans information

Definition of done:

- Admin user has full CRUD over objects within the database, with changes made updating in the front end.

The following user story has been removed during the **first** iteration of the User stories (Email confirmation moved to N2H):

Story 2:

_~~As a business admin user, I want to be able to receive notice of any bookings made, so that I may record and manage them.~~_

~~Acceptance Criteria:~~

- ~~Upon booking made by a regular user, the admin user is to receive an email with information about the booking.~~

~~Definition of done:~~

- ~~Admin user receives notice of a booking and its details.~~

</details>

</details>

<br>
<a name="wireframes"></a>

## Wireframes:

<div align="left">
<a name="desktop"></a>
  
### DESKTOP

<img src="./docs/wireframe-screenshots/wireframes-desktop.png" width="1200"><br>
<a name="tablet"></a>
### TABLET

<img src="./docs/wireframe-screenshots/wireframes-tablet.png" width="600"><br>
<a name="mobile"></a>
### MOBILE

<img src="./docs/wireframe-screenshots/wireframes-mobile.png" width="1000"><br>
<img src="./docs/wireframe-screenshots/desktop-home.png" width="1000"><br>
<img src="./docs/wireframe-screenshots/desktop-login.png" width="1000"><br>
<img src="./docs/wireframe-screenshots/desktop-create-account.png" width="1000"><br>
<img src="./docs/wireframe-screenshots/desktop-account.png" width="1000"><br>
<img src="./docs/wireframe-screenshots/desktop-vans.png" width="1000"><br>
<img src="./docs/wireframe-screenshots/mobile-menus.png" width="200"><img src="./docs/wireframe-screenshots/mobile-home.png" width="200"><img src="./docs/wireframe-screenshots/mobile-login-signup.png" width="200"><img src="./docs/wireframe-screenshots/mobile-account.png" width="200"><img src="./docs/wireframe-screenshots/mobile-vans.png" width="200"><img src="./docs/wireframe-screenshots/mobile-booking-form.png" width="200"><img src="./docs/wireframe-screenshots/mobile-about.png" width="200"><img src="./docs/wireframe-screenshots/mobile-contact.png" width="200">

<br>
  
<a name="wfflow"></a>

### WEBSITE FLOW & NAVIGATION

<img src="./docs/wireframe-screenshots/frontend-flow-diagram.png" width="1200"><br>

</div>

<br>

<a name="figma"></a>

## [View Wireframes In Figma](https://www.figma.com/file/BemCVUbQDxPoxBus4lTpCc/Van-Voyage?type=design&node-id=0-1&mode=design&t=GJJb0HInyCqr9ETQ-0)

<br>
<a name="wfiterations"></a>

## Design Iterations for Wireframes (Agile)

### **Navigation and Flow:**

- Initially, the wireframe design consisted of just a 'Vans' button in the navigation bar, leading users to the vans page for making a booking. Feedback led to the addition of a 'Book Now' button in the navigation bar and a prominently placed one on the home page, providing quicker access to the booking section. This improved the navigation flow by giving users a direct route to start booking a van.

- In the original design, van information was only accessible through the 'Vans' page. To improve user flow, images of the three vans were added as clickable buttons on the home page, leading directly to the respective Van detail pages. This change provided users with a direct path to the details of the van they are interested in.

- The login and create account forms were initially located on the same page, potentially causing confusion for the user. To improve flow, these were split into individual 'Login' and 'Signup' pages, ensuring a more intuitive path for users either returning to the site or signing up for the first time.

- The mobile view initially displayed all vans listed down the Vans page. To streamline the mobile navigation flow, this was replaced with a dropdown menu allowing quick access to individual van details, reducing the number of steps a user would have to take to find information on a specific van.

### **Layout and Positioning:**

- In the initial design of the vans page, the images of the van were displayed in a vertically cascading manner, taking up a lot of space on the page and requiring the user to scroll to see all the content. The layout was revised to include a carousel for the images, consolidating space and making it easier for the user to view other details on the same screen.

- The van details and booking calendar on the vans page were originally positioned so that the calendar was underneath the van details, requiring the user to scroll down to view available dates. To enhance the user experience and reduce scrolling, the layout was adjusted so that the calendar was positioned beside the van details. This allowed users to view the van details and available dates simultaneously.

- Initially, the social media links were located in the top navigation bar. After several iterations, these links were moved to the footer to reduce clutter in the navigation bar and to place more emphasis on other essential navigation links and buttons.

- The reviews section on the home page was initially positioned higher up on the page. After iterating, we realized that this section was not as critical as others to be seen so prominently, so it was moved to the bottom of the page. This also gave higher visibility to other, more critical sections on the home page.


### **Element Design:**

- Initially, there were not as many images of vans and scenic locations on the home page. After several iterations, we decided to add and enlarge these images to help users visualize the idea and concept of the business, providing a glimpse into what a getaway trip with Van Voyage might look like.

- Over time, we shifted the color scheme towards natural, muted hues like greens and beiges. This decision was made to align the website's overall aesthetic more closely with the business's objective of providing nature-focused van trips.

- In the first iteration of the wireframe design, we had a sticky footer. However, given the growing amount of information on the page and the non-essential nature of the footer content, we decided to switch to a non-sticky footer. This change improved the overall user experience by ensuring the most important information was front and center.


### **Adding / Removing Features:**

- Based on early feedback, we realised that users would want to be able to view the booking history easily. Therefore, we added a "Booking History" section to the user's account dashboard instead of it being seen via email. This also meant that we could handle the cancel booking feature here as well.

- For a more intuitive experience, we decided to implement conditional rendering for the Login, Sign Up, Account, and Log Out buttons in the navigation bar. This means that the user will see "Login" and "Sign Up" buttons when they are not logged into the site. Once they log in, these buttons will switch to "Account" and "Log Out". This dynamic adjustment provides a more tailored user experience and intuitively guides users to relevant sections based on their authentication status. 

- The initial design concept included an Instagram carousel at the bottom of the homepage, which aimed to showcase real-time updates and user experiences. It was thought that this would lend authenticity and vibrancy to the website. However, during the process of user feedback and further development, it was determined that this feature wasn't contributing significantly to the overall user experience.


<a name="otherdiagrams"></a>

## Other Diagrams:

_An Entity Relationship Diagram (ERD) was made to further understand the relationships between the databases:_

<img src="./docs/diagrams/ERD.png" width="1200"><br>

<br>

# Testing:

## Backend Server Testing (Development & Production)

### USERS

#### **ENDPOINT: Sign In**

- Development URL: http://localhost:3000/
- Expected Result: Output = Token
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-1.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = Token
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-1.png" width="1200"><br>

<hr>

#### **ENDPOINT: Get User (Self)**

- Development URL: http://localhost:3000/
- Expected Result: Output = User Details
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-2.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = User Details
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-2.png" width="1200"><br>

<hr>

#### **ENDPOINT: Create Account**

- Development URL: http://localhost:3000/
- Expected Result: Output = Email, Password, Admin, ID
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-3.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = Email, Password, Admin, ID
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-3.png" width="1200"><br>

<hr>

#### **ENDPOINT: Update User Details**

- Development URL: http://localhost:3000/
- Expected Result: Output = Field given has updated
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-4.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = Field given has updated
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-4.png" width="1200"><br>

<hr>

#### **ENDPOINT: Change Password**

- Development URL: http://localhost:3000/
- Expected Result: Output = "Password changed successfully"
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-5.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = "Password changed successfully"
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-5.png" width="1200"><br>

<hr>

#### **ENDPOINT: Delete User (Self)**

- Development URL: http://localhost:3000/
- Expected Result: Output = "Account deleted successfully"
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-6.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = "Account deleted successfully"
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-6.png" width="1200"><br>

<hr>

### USERS (Admin)

#### **ENDPOINT: Get All Users**

- Development URL: http://localhost:3000/
- Expected Result: Output = List of all users
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-7.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = List of all users
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-7.png" width="1200"><br>

<hr>

#### **ENDPOINT: Query Users by Value**

- Development URL: http://localhost:3000/
- Expected Result: Output = Specific user returned
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-8.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = Specific user returned
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-8.png" width="1200"><br>

<hr>

#### **ENDPOINT: Update user details**

- Development URL: http://localhost:3000/
- Expected Result: Output = User object returned with updated field
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-9.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = User object returned with updated field
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-9.png" width="1200"><br>

<hr>

#### **ENDPOINT: Delete User by ID**

- Development URL: http://localhost:3000/
- Expected Result: Output = "User successfully deleted"
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-10.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = "User successfully deleted"
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-10.png" width="1200"><br>

<hr>

### BOOKINGS

#### **ENDPOINT: Get My Bookings**

- Development URL: http://localhost:3000/
- Expected Result: Output = List of bookings
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-11.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = List of bookings
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-11.png" width="1200"><br>

<hr>

#### **ENDPOINT: Create New Booking**

- Development URL: http://localhost:3000/
- Expected Result: Output = Error message since booking is longer than 3 weeks
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-12.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = Error message since booking is longer than 3 weeks
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-12.png" width="1200"><br>

<hr>

#### **ENDPOINT: Delete Booking**

- Development URL: http://localhost:3000/
- Expected Result: Output = Booking (ID) deleted successfully
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-13.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = Booking (ID) deleted successfully
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-13.png" width="1200"><br>

<hr>

### BOOKINGS (Admin)

#### **ENDPOINT: Get All Bookings (Admin)**

- Development URL: http://localhost:3000/
- Expected Result: Output = List of bookings
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-14.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = List of Bookings
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-14.png" width="1200"><br>

<hr>

#### **ENDPOINT: Update Booking (Admin)**

- Development URL: http://localhost:3000/
- Expected Result: Output = Van is booked for those dates, so a relevant error message displays
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-15.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = Details of the Booking
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-15.png" width="1200"><br>

<hr>

#### **ENDPOINT: Delete Booking (Admin)**

- Development URL: http://localhost:3000/
- Expected Result: Output = Booking deleted successfully
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-16.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = Booking deleted successfully
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-16.png" width="1200"><br>

<hr>

### REVIEWS

#### **ENDPOINT: Get All Reviews**

- Development URL: http://localhost:3000/
- Expected Result: Output = List of Reviews
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-17.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = List of Reviews
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-17.png" width="1200"><br>

<hr>

#### **ENDPOINT: Create Review**

- Development URL: http://localhost:3000/
- Expected Result: Output = Details of the review
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-18.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = Details of the review
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-18.png" width="1200"><br>

<hr>

### REVIEWS (Admin)

#### **ENDPOINT: Update Review By ID (Admin)**

- Development URL: http://localhost:3000/
- Expected Result: Output = Details of the review with updated field
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-19.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = Details of the review with updated field
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-19.png" width="1200"><br>

<hr>

#### **ENDPOINT: Delete Review By ID (Admin)**

- Development URL: http://localhost:3000/
- Expected Result: Output = Review successfully deleted
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-20.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = Review successfully deleted
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-20.png" width="1200"><br>

<hr>

#### **ENDPOINT: Get Review By ID (Admin)**

- Development URL: http://localhost:3000/
- Expected Result: Output = Details of the review
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-21.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = Details of the review
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-21.png" width="1200"><br>

<hr>

### VANS (Admin)

#### **ENDPOINT: Get All Vans (Admin)**

- Development URL: http://localhost:3000/
- Expected Result: Output = List of vans
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-22.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = List of Vans
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-22.png" width="1200"><br>

<hr>

#### **ENDPOINT: Query Vans by Value (Admin)**

- Development URL: http://localhost:3000/
- Expected Result: Output = List of vans with that specific value
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-23.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = List of vans with that specific value
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-23.png" width="1200"><br>

<hr>

#### **ENDPOINT: Add Van (Admin)**

- Development URL: http://localhost:3000/
- Expected Result: Output = Details of the van that was added
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-24.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = Details of the van that was added
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-24.png" width="1200"><br>

<hr>

#### **ENDPOINT: Update Van by ID (Admin)**

- Development URL: http://localhost:3000/
- Expected Result: Output = Details of the van that was updated
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-25.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = Details of the van that was updated
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-25.png" width="1200"><br>

<hr>

#### **ENDPOINT: Delete Van by ID (Admin)**

- Development URL: http://localhost:3000/
- Expected Result: Output = Van and associated bookings successfully deleted
- PASS ✅

<img src="./docs/dev-server-testing-screenshots/dev-server-testing-26.png" width="1200"><br>

- Production URL: https://van-voyage-server.onrender.com/
- Expected Result: Output = Van and associated bookings successfully deleted
- PASS ✅

<img src="./docs/prod-server-testing-screenshots/prod-server-testing-26.png" width="1200"><br>




# Packages Used In Server:

### **bcryptjs:** 

A JavaScript-based implementation of bcrypt, designed for password hashing and salting. It works by converting plaintext passwords into hashed strings using a CPU-intensive hash algorithm and a random salt. It's used in this app as a secure way to store user passwords.

### **cors:** 

Cross-Origin Resource Sharing (CORS) is a middleware that enables many types of interactions between different domains. By setting specific headers in HTTP responses, cors allows this app's server to accept and respond to HTTP requests from different origins, providing an essential service for modern web applications that separate frontend and backend domains.

### **dotenv:** 

Dotenv is a zero-dependency module that loads environment variables from a .env file into process.env in Node.js applications. It's used in this app to handle app configuration such as port setting, and securing sensitive data such as database credentials and API keys, keeping them out of the version control.

### **express:** 

Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications. It simplifies server creation, and handles routes, requests, and responses in this app. It also supports middleware to respond to HTTP requests, and has template engines to create dynamic HTML pages.

### **helmet:** 

Helmet is a collection of smaller middleware functions that set HTTP headers related to security. Helmet can help protect this app from some well-known web vulnerabilities by appropriately setting HTTP headers such as Content Security Policy, X-DNS-Prefetch-Control, Expect-CT, and others.

### **http-errors:** 

Http-errors is a utility module that creates HTTP error objects for use in Express applications. It encapsulates errors into objects with properties like status (error code) and message, facilitating systematic error handling and improving code readability in this app.

### **jsonwebtoken:** 

jsonwebtoken is a library that creates JSON Web Tokens (JWTs) which securely transmit information between parties as a JSON object. JWTs are used in this app to manage user authentication, by generating tokens upon login and verifying them on subsequent requests, and to maintain user sessions, minimizing constant reauthentication.

### **mongoose:** 

Mongoose is an Object Data Modeling (ODM) library for MongoDB and Node.js. It manages relationships between data, provides schema validation, and is used to translate between objects in code and the representation of those objects in MongoDB. Mongoose handles the app's interaction with MongoDB for data storage.

## Dev Dependencies

### **jest:** 

Jest is a comprehensive JavaScript testing framework with a focus on simplicity. It supports different kinds of tests like snapshot testing, asynchronous testing, and mocking. Jest is used in this app to write and execute unit and integration tests, ensuring the functionality and reliability of the code.

### **nodemon:** 

Nodemon is a utility that monitors changes in your source code and automatically restarts your server. This tool helps streamline the development process by avoiding manual server restarts, leading to faster iterations during development of this app.

### **supertest:** 

Supertest is a high-level abstraction for testing HTTP, while still allowing you to drop down to the lower-level API provided by superagent. It pairs exceptionally well with Jest and is used in this app to simulate HTTP requests and assert their responses, testing that all endpoints are functioning as expected.

<br>


# Packages Used In Client:


### **@emailjs/browser** and **emailjs-com:** 

These libraries facilitate the sending of emails directly from JavaScript, without needing backend services. They're used in this app to handle communication via email.

### **axios:** 

Axios is a promise-based HTTP client for the browser and Node.js. It's used in this app to make HTTP requests to external APIs and handle responses.

### **jsonwebtoken** and **jwt-decode:** 

jsonwebtoken and jwt-decode are libraries related to JSON Web Tokens (JWTs). jsonwebtoken generates JWTs for secure transmission of information between parties. jwt-decode, on the other hand, allows the decoding of JWTs to retrieve the stored information. These libraries manage user authentication and maintain sessions in this app.

### **react,** **react-dom,** and **react-router-dom:** 

React is a JavaScript library for building user interfaces, and ReactDOM manages the rendering of React components to the DOM. react-router-dom provides the routing functionality within the React app, allowing navigation between different components. These are core dependencies for building and managing this app's user interface.

### **react-calendar:** 

react-calendar is a flexible calendar component for React, used in this app to manage and display dates.

### **react-responsive-carousel:** 

This is a component for building responsive carousels in React. It's used in this app for displaying collections of images or content in a dynamic, sliding format.

### **react-star-ratings:** 

A flexible star ratings component for React. It's used in this app for users to rate items and display existing ratings.

## Dev Dependencies

### **@babel/preset-env,** **@babel/preset-react,** **babel-jest,** and **babel-plugin-transform-import-meta:** 

These are Babel dependencies. Babel is a JavaScript transpiler that converts edge JavaScript into backwards compatible versions. The presets and plugins extend Babel's capabilities, supporting the transformations of React JSX syntax (preset-react), enabling Jest to work with Babel (babel-jest), and transforming `import.meta` to `process.env` in output code (transform-import-meta).

### **@testing-library/jest-dom,** **@testing-library/react,** **jest,** and **jest-date-mock:** 

These dependencies relate to the Jest testing framework and the Testing Library. Jest provides a comprehensive set of testing utilities, while the Testing Library provides a set of tools for testing React components. jest-date-mock is a utility to mock JavaScript Date objects in Jest.

### **@types/react** and **@types/react-dom:** 

These are TypeScript definition files for React and ReactDOM. They provide TypeScript typing for these libraries, offering development-time type checking and editor features.

### **@vitejs/plugin-react:** 

This is a Vite plugin that offers fast Refresh and JSX support for React. Vite is a build tool and development server that offers fast, module-based development.

### **eslint,** **eslint-plugin-react,** **eslint-plugin-react-hooks,** and **eslint-plugin-react-refresh:** 

ESLint is a pluggable linting utility for JavaScript, with plugins providing rules and functionality for specific libraries or frameworks. These ESLint plugins provide linting for React, the React hooks API, and React Fast Refresh, ensuring consistent code style and avoiding common mistakes in this app.

### **autoprefixer,** **postcss,** and **tailwindcss:** 

These are styling-related dependencies. PostCSS is a tool for transforming CSS with JavaScript, Autoprefixer automatically adds vendor prefixes to CSS, and Tailwind CSS is a utility-first CSS framework for rapidly building custom designs. They are used in this app to manage, optimize, and enhance CSS styles.

### **vite:** 

Vite is a modern front-end build tool that provides a faster and leaner development experience for modern web projects. It's used in this app for tasks such as starting a development server, enabling Hot Module Replacement (HMR), or building the app for production.




<a name="trello"></a>

## Planning (Trello):

### [View Trello Board](https://trello.com/b/RtrOpaLV/ca-retro-van-hire-part-a)


To initiate the project planning process, we first set up a Trello board to streamline our project tasks, track progress, and ensure every team member is aligned with the project's objectives. The board was divided into three main categories: To Do, Doing, and Done. These categories provided a clear and concise overview of our work progress at any given point.

We used color-coding for each card to clearly distinguish between different aspects of the project. Blue cards represented frontend-related tasks, Green was used for the database tasks, Turquoise was assigned to backend tasks, Orange was used for project's Part A tasks, and Red was designated for any questions or reminders that came up during the project lifecycle. The color coding system allowed us to quickly grasp the nature of the tasks at a glance.

Labels were another key feature we used to add an extra layer of categorization within the color-coded cards. These labels indicated whether the task involved Coding (Orange label), Planning (Green label), Documentation (Blue label), or corresponded to a specific Rubric (Red label). Labels helped us understand the type of work required for each task, irrespective of its nature (frontend, backend, or database).

In order to maintain a smooth workflow and meet our deadlines, we set due dates for each card. This not only helped us prioritize tasks effectively but also ensured we were consistently making progress towards our project goals.

To further refine our task prioritization process, we used a Trello Power-Up called "Card Priority." This allowed us to classify each task into one of four categories: Urgent and Important, Not Urgent but Important, Urgent and Not Important, and Not Urgent and Not Important. The level of importance was displayed on the front of each card, ensuring that our most critical tasks received immediate attention.

A unique checklist was created for each card, providing a detailed breakdown of the individual steps required to complete the task. As we progressed, we ticked off completed items, allowing us to track our progress in a granular way and ensuring nothing was missed.

Our use of Trello for this project was instrumental in keeping us organized, productive, and aligned with our project goals. It provided a visual snapshot of our project's status and allowed us to efficiently manage our tasks, leading to a streamlined and effective workflow.

<br>

<img src="./docs/trello-screenshots/trello-1.png" width="1200"><br>
<img src="./docs/trello-screenshots/trello-2.png" width="1200"><br>
<img src="./docs/trello-screenshots/trello-3.png" width="1200"><br>
<img src="./docs/trello-screenshots/trello-4.png" width="1200"><br>
<img src="./docs/trello-screenshots/trello-5.png" width="1200"><br>
<img src="./docs/trello-screenshots/trello-6.png" width="1200"><br>
<img src="./docs/trello-screenshots/trello-7.png" width="1200"><br>
<img src="./docs/trello-screenshots/trello-8.png" width="1200"><br>
<img src="./docs/trello-screenshots/trello-9.png" width="1200"><br>
<img src="./docs/trello-screenshots/trello-10.png" width="1200"><br>
<img src="./docs/trello-screenshots/trello-11.png" width="1200"><br>
<img src="./docs/trello-screenshots/trello-12.png" width="1200"><br>
<img src="./docs/trello-screenshots/trello-13.png" width="1200"><br>
<img src="./docs/trello-screenshots/trello-14.png" width="1200"><br>
<img src="./docs/trello-screenshots/trello-15.png" width="1200"><br>
<img src="./docs/trello-screenshots/trello-16.png" width="1200"><br>
<img src="./docs/trello-screenshots/trello-17.png" width="1200"><br>
<img src="./docs/trello-screenshots/trello-18.png" width="1200"><br>
<img src="./docs/trello-screenshots/trello-19.png" width="1200"><br>

<br>
<a name="references"></a>

## References:

[Atlassian. (n.d.). Agile project management: Creating user stories. Retrieved from https://www.atlassian.com/agile/project-management/user-stories](https://www.atlassian.com/agile/project-management/user-stories)

[The Business Analysis Doctor - IIBA Certification, (2022) Data Flow Diagram EXAMPLE [How to Create Data Flow Diagrams]](https://www.youtube.com/watch?v=ab1DZ6o7QBs)

Diagrams were made with: [Lucid](https://lucid.app/documents#/documents?folder_id=recent), [Canva](https://www.canva.com/), and [draw.io](https://app.diagrams.net/)

Facebook, Instagram, Burger Menu and Live Chat Icons created at: [Flaticon](https://www.flaticon.com/) 

Van Voyage logo created with: [Looka](https://looka.com/)

Free to use images taken from: [Unsplash](https://www.canva.com/), [Pexels](https://www.pexels.com/)

Van images from: [Camplify](https://www.camplify.com.au)

