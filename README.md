# Car Rental App

Develop a car rental application that allows both regular users and an admin user to interact with the 
system.

The System can enable users to rent cars for a specified duration

# Regular User Flow

• Users should be able to login into the application using valid credentials 
• Regular users can search for available cars based on the filters like:
o Maker
o Model
o Rental Price
• The system displays a list of cars that match the user’s search criteria.
• Users can select a car from the list and specify the rental duration.
• Once the rental duration is provided, the system generates a rental agreement containing
o Car information
o Rental duration (in days)
o Total cost
o User details
• Users can view all their rental agreements in the “My Rental Agreements“ tab.
• User can edit rental agreement details before accepting it.
• Once the user accepts the rental agreement, it cannot be edited or deleted.
• If the user wants to return the rented car, they can mark it as “request for return“.

# Admin User Flow
• Admin user can view all the rental agreements.
• They have the authority to update or delete any rental agreement.
• The admin user can validate all cars marked as “request for return” for conducting an 
inspection.
• Once the inspection is completed, the admin can mark the car as returned.


 # Screen-shots of the features
<img width="960" alt="Screenshot 2023-09-21 161842" src="https://github.com/shahnwaza058/mini-assignments/assets/138658659/d4630cbd-12c2-45d6-8e92-a90c6b7233c0">

<img width="960" alt="Screenshot 2023-09-21 161859" src="https://github.com/shahnwaza058/mini-assignments/assets/138658659/7d69a7ac-cd81-492c-b975-650e0685f6ec">
<img width="960" alt="Screenshot 2023-09-21 161932" src="https://github.com/shahnwaza058/mini-assignments/assets/138658659/f181f4a2-d645-4a6c-b3f7-9b21ccf99cdb">
<img width="960" alt="Screenshot 2023-09-21 162040" src="https://github.com/shahnwaza058/mini-assignments/assets/138658659/d3add162-8cb6-4c00-92d8-f46c9d8c9f69">
<img width="960" alt="Screenshot 2023-09-21 162055" src="https://github.com/shahnwaza058/mini-assignments/assets/138658659/e1a0fcba-82a1-4ccb-a6c4-f19cd3dd30da">
<img width="960" alt="Screenshot 2023-09-21 162108" src="https://github.com/shahnwaza058/mini-assignments/assets/138658659/911b2bd7-0370-4b2e-9a9a-f03fb372b65c">
<img width="960" alt="Screenshot 2023-09-21 162120" src="https://github.com/shahnwaza058/mini-assignments/assets/138658659/291ccc6c-959e-4b56-8ca7-e15500d5e3bc">
<img width="960" alt="Screenshot 2023-09-21 162134" src="https://github.com/shahnwaza058/mini-assignments/assets/138658659/4965971f-4856-412f-a7ae-e91cb3140b5b">
<img width="960" alt="Screenshot 2023-09-21 162143" src="https://github.com/shahnwaza058/mini-assignments/assets/138658659/91fe72c9-c304-4e33-80de-a2d7df112828">
<img width="960" alt="Screenshot 2023-09-21 162218" src="https://github.com/shahnwaza058/mini-assignments/assets/138658659/4f24c8a6-2089-436c-abb8-4944a4e6cfb1">
<img width="960" alt="Screenshot 2023-09-21 162228" src="https://github.com/shahnwaza058/mini-assignments/assets/138658659/01174bd3-0d92-4151-beda-827e2129da8b">

## Installation and Setup



1. **Install Dependencies:**

   ```bash
   npm install
   ```


2. **Start the Application:**

   ```bash
   npm start
   ```

   The application will be accessible at `http://localhost:3000`.


