---
title: Welcome to Live-Laugh-Lockheed-Martin
description: Innovating for a Better Tomorrow
---

# 🚀 Welcome to Live-Laugh-Lockheed-Martin

![ci-badge](https://github.com/Live-Laugh-Lockheed-Martin/Manoa-Munchies-Nextjs/actions/workflows/ci-manoa-munchies-nextjs.yml/badge.svg)

## Table of Contents
- [Our Vision](#our-vision)
- [What We Do](#what-we-do)
- [Overview](#overview)
- [Status](#status)
- [User Guide](#user-guide)
- [Team Contract](#team-contract)
- [Deployment](#deployment)
- [Milestone 1 (M1) Project Page](#milestone-1-m1-project-page)
- [Milestone 2 (M2) Project Page](#milestone-2-m2-project-page)
- [Milestone 3 (M3) Project Page](#milestone-3-m3-project-page)
- [GitHub Hosting Guidelines](#github-hosting-guidelines)
- [Join Us](#join-us)
- [Contact Us](#contact-us)

## Our Vision
At **Live-Laugh-Lockheed-Martin**, we are dedicated to pushing the boundaries of technology and innovation. Our mission is to create solutions that make the world safer, more connected, and full of possibilities.

We envision a future where advanced technology and human ingenuity come together to solve the world's most pressing challenges. From aerospace and defense to everyday life, our teams are committed to excellence and innovation.

## What We Do
- **Aerospace Engineering**: Developing cutting-edge aircraft and spacecraft.
- **Cybersecurity**: Safeguarding digital assets with state-of-the-art security solutions.
- **Website Development**: Designing future-forward digital solutions that connect people, power innovation, and enhance global security.

## Overview
**Project Title**: Campus Cravings

**Main Objective**:
The core purpose of this project is to solve the challenge of navigating the wide variety of food options on the University of Hawai‘i at Mānoa campus. With multiple food vendors—such as Campus Center, food trucks, Manoa Gardens, Paradise Palms, and vending machines—students often struggle to find specific types of food or track when a favorite dish is available.

The app will provide students with real-time access to menu items across all campus food locations, filtered by their food preferences. This will simplify decision-making and increase satisfaction by reducing the time and effort spent finding meals they enjoy.

**Key Points of Development for Success**:
- Create a backend system that aggregates menu data from all vendors, allowing real-time updates.
- Organize menu items by location, cuisine type, dietary tags (e.g., vegan, halal), and availability (daily/weekly).
- Users: Can create accounts, set preferences (e.g., exclude allergens, favorite cuisines), and view tailored suggestions.
- Vendors: Can log in to update their daily/weekly menus and manage their vendor profile.
- Admins: Manage user/vendor accounts and oversee system operations.

**Core App Features**:
- Search functionality for cuisine types, dishes, and vendors.
- User Home Page
- Vendor Dashboard
- Admin Panel
- Create a simple and quick form for vendors to input and update their menus.

## Status
The project is finished.
[View our GitHub Repository](https://github.com/eibanezUH/Manoa-Munchies-Nextjs)
View our project boarrds:
- [Milestone 1 (M1) Project Page](#milestone-1-m1-project-page)
- [Milestone 2 (M2) Project Page](#milestone-2-m2-project-page)
- [Milestone 3 (M3) Project Page](#milestone-3-m3-project-page)

## User Guide
#### Homepage
<p>Users will land on the homepage when they visit the Campus Cravings site. The homepage provides steps on how to access and use the website. Depending on what type of user they are logged in as (User, Vendor, or Admin), they will see a corresponding navigation menu bar. If they are not logged in to any account, the menu bar will not show any links.</p>
<img src="images/m3/homepage.png" alt="Homepage" width="800" height="450" />

#### Sign In
<p>The Sign In page allows registered users to access their accounts by entering their login credentials.</p>
<img src="images/m3/signin.png" alt="Sign In page" width="800" height="450" />

#### Sign Up
<p>New users can create an account on the Sign Up page by providing their name, email, and password.</p>
<img src="images/m3/signup.png" alt="Sign Up page" width="800" height="450" />

### Users
#### 🍽️ Available Menu
<p>The Available Menu page is the user-facing menu discovery page. It lists all active food items across vendors and includes a live search bar where users can search by name, cuisine, ingredient, or vendor name. Clicking the 'View Details' button reveals the item's description and ingredients. Additionally, clicking the name of the vendor brings up a pop-up that displays relevant information on the vendor's profile, including their email address, physical address, and operating hours. Clicking on the physical address link sends users to the location viewed on Google Maps.</p>
<img src="images/m3/user-food-available.png" alt="User Available Menu page" width="800" height="450" />
<img src="images/m3/user-food-available-show-details.png" alt="User Available Menu page showing details" width="800" height="450" />

#### Top Picks
<p>The "Top Picks For You" page shows a curated list of menu items tailored to the user's food preferences and aversions or if the item is marked as a special. It includes search functionality and links to go back to the full list or update preferences.</p>
<img src="images/m3/user-top-picks.png" alt="User Top Picks page" width="800" height="450" />

#### User Profile
<p>Users can edit their food preferences and aversions here. Each entry appears as a tag that can be removed. They can add new tags (e.g., "Hawaiian", "Chinese") and save to update what appears on the Top Picks page.</p>
<img src="images/m3/user-profile.png" alt="User Profile page" width="800" height="450" />

### Vendors
#### Vendor Dashboard
<p>Vendors can view their profile information on the card to the left and any menu items they have created in the table to the right. By clicking on a table row, they can expand the box to show the description, price, ingredients and special scedule status of the item. Additionally, they can click expand all or hide all to display/hide information.</p>
<img src="images/m3/vendor-dashboard.png" alt="Vendor Dashboard page" width="800" height="450" />

#### Update Vendor Profile
<p>Vendors can update their business name, location, cuisine types (comma-separated), and operating hours for each day of the week. Time inputs make it easy to manage availability. This ensures accurate visibility for users browsing by vendor or filtering by open hours.</p>
<img src="images/m3/vendor-update-profile.png" alt="Update Vendor Profile page" width="800" height="450" />

#### Add Menu Item
<p>Vendors can add a new menu item by filling out details such as name, description, price, ingredients, category, and cuisine. Special days can also be tagged using checkboxes for each day of the week. This page ensures that all vendor entries are clear, searchable, and updated in real time.</p>
<img src="images/m3/vendor-add-menu-items.png" alt="Add Menu Item page" width="800" height="450" />

#### Edit Menu Items
<p>Vendors can edit existing menu items by changing the details listed on the page. The page comes preloaded with the menu item's current items. Clicking 'Submit' will save any changes to made. Clicking the 'Reset' button will reset any changes made to the item's preloaded details. Pressing 'Cancel' will take the user back to the vendor dashboard page.</p>
<img src="images/m3/vendor-edit-menu-items.png" alt="Edit Menu Item page" width="800" height="450" />

### Admin
#### Admin Dashboard
<p>The Admin Dashboard page provides admin users with the ability to view all registered users, their id number in the database, and their roles, and the ability to update any existing user to the role of Vendor by clicking the 'Add Vendor' button.</p>
<img src="images/m3/admin-dashboard.png" alt="Admin Dashboard page" width="800" height="450" />

#### Add Vendors
<p>The Add Vendor page provides admin with the ability to update any existing user to the role of Vendor. When doing so, the admin will fill out the vendors's name and optionally their phone number and address.</p>
<img src="images/m3/admin-add-vendor.png" alt="Admin Add Vendor page" width="800" height="450" />

## Testing Guidelines
<img src="images/playwright-cmd-img.png" alt="Playwright test summary with 15 tests passed" width="700" height="200"/>
<img src="images/playwright-test-report.png" alt="Playwright test report showing tests run across Chromium, Firefox, and WebKit" width="422" height="489"/>

## Community Feedback
The website was demonstrated to 5 students from UH Manoa and feedback was received via word-of-mouth. All interviewees reflected overall positive responses. One student stated that it was helpful to know the operating times of the food trucks in food truck row as they frequent the food trucks regularly. Another student said that the user dashboard and filter system was really clean and she could see herself using the app to pick out what she wanted to eat for the day. Another student expressed his desire to see support for vending machines added should the project be continued. He said that sometimes, vending machines are down or out of stock on certain food items and a way to know that before hand would be nice. Yet another student says that he sometimes stays afterschool late and expressed his interest to see other food places nearby campus added to the list of vendors, citing that it would be helpful to see what is there to eat in the evening.

## Developer Guide
This guide will show how to download, install, run, and modify the project. The project will not be downloaded with any 

1. Clone the repo to your local machine, run npm install and then npm run dev to bring it up.
2. Create a postgreSQL database with createdb [database name].
3. Create an .env file and copy the following into it:

```
DATABASE_URL="postgresql://user:password@localhost:5432/mydb?schema=public"

NEXTAUTH_SECRET=secret
NEXTAUTH_URL=http://localhost:3000

POSTGRES_DATABASE="verceldb"
POSTGRES_HOST="***"
POSTGRES_PASSWORD="***"
POSTGRES_PRISMA_URL="postgres://default:***@***/verceldb?pgbouncer=true&connect_timeout=15&sslmode=require"
POSTGRES_URL="postgres://default:***@***/verceldb?sslmode=require"
POSTGRES_URL_NON_POOLING="postgres://default:***@***/verceldb?sslmode=require"
POSTGRES_URL_NO_SSL="postgres://default:***@***/verceldb"
POSTGRES_USER="default"
```

4. Edit the .env file to set the DATABASE_URL to postgresql://<username>:<password>@localhost:5432/digits?schema=public
5. Then run npx prisma migrate dev and npx prisma db seed to seed the database.
6. Start Next.js using npm run dev, and check http://localhost:3000 (and the console) to ensure that the new landing page displays correctly.

## Team Contract
[View our Team Contract](https://docs.google.com/document/d/1re1sDmqgrhCbOyjak1mA5vgmcGx4IPJbKRek7SYEZfA/edit?tab=t.0)

## Deployment
Our app is deployed and live on Vercel:  
[https://manoa-munchies-nextjs.vercel.app/](https://manoa-munchies-nextjs.vercel.app/)

## Milestone 1 (M1) Project Page
[View M1 Project Board](https://github.com/orgs/Live-Laugh-Lockheed-Martin/projects/2)

## Milestone 2 (M2) Project Page
[View M2 Project Board](https://github.com/orgs/Live-Laugh-Lockheed-Martin/projects/3)

## Milestone 3 (M3) Project Page
[View M3 Project Board](https://github.com/orgs/Live-Laugh-Lockheed-Martin/projects/4)

## GitHub Hosting Guidelines
This page adheres to the [GitHub hosting guidelines](https://courses.ics.hawaii.edu/ics314s24/morea/project/milestone1-ghpages.html).

## Join Us
Are you passionate about innovation and technology? We're always looking for talented individuals to join our team. [Explore Careers](#)

## Contact Us
Have questions or need more information? Reach out to us at [contact@livelaughlockheedmartin.com](mailto:contact@livelaughlockheedmartin.com).

[Back to the top](#table-of-contents)

---

*Empowering Innovation. Securing the Future.*


