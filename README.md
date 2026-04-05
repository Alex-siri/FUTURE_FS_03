# Alex Gym Website

A modern and responsive landing page for Alex Gym. This project is built to showcase the gym's mission, trainers, success stories, and provide a clean contact interface.

## Features

- **Responsive Design**: Designed to work smoothly across varying screen sizes.
- **Smooth Scrolling Navigation**: Smoothly glides to different sections of the page via the navigation menu (powered by JavaScript).
- **Interactive Contact Form (Full Stack)**: Includes frontend validation and a Node.js/Express backend that saves leads directly to a local JSON database.
- **BMI Calculator**: Real-time JavaScript-powered tool providing custom color-coded health categorizations.
- **Dark Mode Hook**: Integrated light/dark mode toggle switch.

## Project Structure

- `client/`: Contains the frontend UI.
  - `Alex Gym.html`: The main document structuring the webpage content.
  - `styles.css`: Stylesheet governing layout, dark mode, colors, and visual design.
  - `script.js`: JavaScript controlling scroll logic, mobile menu, BMI calculations, and API fetching.
  - `website_photos/`: Images of gym trainers and success stories.
- `server/`: Contains the Node.js backend.
  - `server.js`: Express API handling `GET` status and `POST` form submissions.
  - `leads.json`: Auto-generated file capturing submitted contact forms.

## Technologies Used

- HTML5, CSS3, JavaScript (Vanilla Frontend)
- Node.js & Express (Backend Server)
- FontAwesome (Icons)

## How to Run Locally

1. **Start the Backend Server**:
   Open a terminal, navigate to the `server` folder, install the packages, and run the server.
   ```bash
   cd server
   npm install
   node server.js
   ```
2. **Open the Frontend**:
   Simply open `client/Alex Gym.html` in your web browser. 
3. **Test the Lead System**:
   Fill out the "Contact Us" form on the webpage and hit Send. Check your `server/leads.json` file to see the newly saved data!

---

## 💼 The Business Pitch (Task 3 Deliverable)

### **How This Website Helps "Alex Gym" Grow**
When pitching this website to the owner of Alex Gym, the goal is to show them that this isn't just a digital brochure—it's a **24/7 automated sales representative** that drives revenue. This is how the website generates more members:

1. **Instant Trust & Authority (Social Proof):** 
   Most people choose a gym based on results. Our **Success Stories** section with real before/after quotes, combined with the **Meet Our Trainers** section, instantly establishes Alex Gym as a premium, results-driven authority in the local market.
   
2. **Frictionless Mobile Lead Generation:**
   Over 70% of local "gyms near me" searches happen on smartphones. With our newly built **Mobile-Responsive Hamburger Menu** and fixed navigation, a potential client can find the gym's pricing and hit "Contact" in less than 3 taps from their phone.

3. **Interactive Value (The BMI Calculator):**
   Instead of just asking visitors to buy, we *give them value first*. The interactive **BMI Calculator** keeps users on the page longer. Once they see their result, they are emotionally invested in their health and naturally scroll right down to the **Get In Touch** form to start their fitness journey.

4. **Transparent Tiered Pricing:**
   The **Membership Plans** section uses consumer psychology (centering the "Most Popular" $49 Standard tier) to upsell clients automatically. It removes the fear of hidden fees, which is the #1 reason people hesitate to join a new gym.

5. **Premium Branding Validation:**
   The high-end dark mode, sleek scroll animations, and professional layout make the gym look expensive and modern. This allows Alex Gym to justify higher membership fees because their digital presence matches a premium physical facility.
