# Ex09 Event Registration Web Application
# Date:25/11/2024
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
```
# Home page

<style>
  .event-registration {
    display: flex;
    max-width: 480px;
    width: 100%;
    flex-direction: column;
    color: #fff;
    margin: 0 auto;
    font: 400 48px Itim, sans-serif;
  }

  .registration-container {
    display: flex;
    flex-direction: column;
    position: relative;
    min-height: 880px;
    width: 100%;
    align-items: center;
    padding: 128px 48px 11px;
  }

  .background-image {
    position: absolute;
    inset: 0;
    height: 100%;
    width: 100%;
    object-fit: cover;
    object-position: center;
  }

  .navigation-text {
    position: relative;
    color: #000;
    font: 16px Jacques Francois, sans-serif;
  }

  .logo {
    aspect-ratio: 1.04;
    object-fit: contain;
    object-position: center;
    width: 221px;
    margin-top: 21px;
    max-width: 100%;
  }

  .login-button {
    position: relative;
    background-color: #039bb3;
    margin-top: 16px;
    width: 225px;
    max-width: 100%;
    white-space: nowrap;
    text-align: center;
    padding: 15px 48px;
  }

  .register-button {
    position: relative;
    background-color: #039bb3;
    margin-top: 19px;
    width: 277px;
    max-width: 100%;
    white-space: nowrap;
    text-align: center;
    padding: 19px 35px;
  }

  .profile-image {
    aspect-ratio: 1.5;
    object-fit: contain;
    object-position: center;
    width: 100%;
    border-radius: 142px;
    align-self: stretch;
    margin-top: 35px;
  }

  .coordinator-name {
    position: relative;
    font-size: 24px;
    text-align: center;
    margin-top: 17px;
  }

  .visually-hidden {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0;
  }
</style>

<div class="event-registration">
  <div class="registration-container">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/4120ad415f12493eb5df19bb381aa707/afbc92ade47084654c6c7881aafe2a01007de7a46dab4d61fd5df7337fc93bb2?apiKey=4120ad415f12493eb5df19bb381aa707&"
      class="background-image"
      alt=""
    />
    <nav class="navigation-text" role="navigation">
      <span tabindex="0">Home</span>
      <span tabindex="0">Event</span>
      <span tabindex="0">Registration</span>
      <span tabindex="0">About</span>
    </nav>
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/4120ad415f12493eb5df19bb381aa707/61b6f1cfb654f77e188961e896278fe0a1cade656f8b23e1a2f2987f623fb5c9?apiKey=4120ad415f12493eb5df19bb381aa707&"
      class="logo"
      alt="Event logo"
    />
    <button class="login-button" tabindex="0">LOGIN</button>
    <button class="register-button" tabindex="0">REGISTER</button>
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/4120ad415f12493eb5df19bb381aa707/9a2234d3a259166cf7aac63eade3d94dd77fd465ba6b308dcba36f788266cde2?apiKey=4120ad415f12493eb5df19bb381aa707&"
      class="profile-image"
      alt="Coordinator profile picture"
    />
    <div class="coordinator-name">Co-ordintor - Raviprasath</div>
  </div>
</div>
```
```
# Event page

<style>
.sports-events-container {
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  align-items: center;
  color: #000;
  font-weight: 400;
  text-align: center;
  margin: 0 auto;
  padding: 40px 44px 11px;
}

.header-divider {
  aspect-ratio: 7.25;
  object-fit: contain;
  object-position: center;
  width: 100%;
  align-self: stretch;
}

.events-title {
  margin-top: 59px;
  width: 261px;
  font: 40px Italiana, sans-serif;
}

.events-list {
  margin-top: 59px;
  width: 253px;
  font: 36px Jersey 10, sans-serif;
}

.events-image {
  aspect-ratio: 2.02;
  object-fit: contain;
  object-position: center;
  width: 100%;
  border-radius: 18px;
  margin-top: 90px;
  max-width: 368px;
}

.coordinator-name {
  margin-top: 36px;
  font: 24px Itim, sans-serif;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="sports-events-container">
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/4120ad415f12493eb5df19bb381aa707/986c5a6a50bb3a6c0f8014db342461e6bf7a577e9fbf2d168bbbd444688fddf3?apiKey=4120ad415f12493eb5df19bb381aa707&"
    class="header-divider"
    alt=""
  />
  <h1 class="events-title">SPORTS DAY EVENTS</h1>
  <div class="events-list" role="list">
    CRICKET
    <br />
    FOOTBALL
    <br />
    BADMINTON
    <br />
    VOLLEY BALL
    <br />
    100 MTS
    <br />
    200MTS
    <br />
    4*100 MTS
  </div>
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/4120ad415f12493eb5df19bb381aa707/ac2a41979ee06be04f3831f0ca1b3a344a5b178cb2486ffd8e7d89526bdfb98c?apiKey=4120ad415f12493eb5df19bb381aa707&"
    class="events-image"
    alt="Sports day events illustration"
  />
  <p class="coordinator-name">Co-ordintor - Raviprasath</p>
</div>
```
```
# Event Registration page

<style>
.registration-container {
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  align-items: start;
  color: #000;
  margin: 0 auto;
  padding: 160px 30px 11px;
  font: 400 24px Itim, sans-serif;
}

.registration-title {
  font-family: Italiana, sans-serif;
  text-align: center;
  align-self: center;
}

.form-input {
  background-color: #D9D9D9;
  margin-top: 35px;
  width: 348px;
  max-width: 100%;
  padding: 21px;
}

.form-input:first-of-type {
  margin-top: 50px;
}

.submit-button {
  background-color: #039BB3;
  align-self: end;
  margin-top: 16px;
  width: 186px;
  height: 53px;
  border: none;
  cursor: pointer;
}

.submit-button:hover,
.submit-button:focus {
  opacity: 0.9;
}

.coordinator-info {
  text-align: center;
  align-self: center;
  margin-top: 35px;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="registration-container">
  <h1 class="registration-title">EVENT REGISTRATION FORM</h1>
  <form>
    <label for="fullName" class="visually-hidden">Full Name</label>
    <input type="text" id="fullName" class="form-input" placeholder="FULL NAME" required aria-label="Full Name">
    
    <label for="gender" class="visually-hidden">Gender</label>
    <select id="gender" class="form-input" required aria-label="Gender">
      <option value="">GENDER</option>
      <option value="male">Male</option>
      <option value="female">Female</option>
      <option value="other">Other</option>
    </select>
    
    <label for="regNumber" class="visually-hidden">Register Number</label>
    <input type="text" id="regNumber" class="form-input" placeholder="REGISTER NUMBER" required aria-label="Register Number">
    
    <label for="mobileNumber" class="visually-hidden">Mobile Number</label>
    <input type="tel" id="mobileNumber" class="form-input" placeholder="MOBILE NUMBER" required aria-label="Mobile Number">
    
    <label for="emailId" class="visually-hidden">Email ID</label>
    <input type="email" id="emailId" class="form-input" placeholder="EMAIL ID" required aria-label="Email ID">
    
    <label for="eventSelect" class="visually-hidden">Event to Register</label>
    <select id="eventSelect" class="form-input" required aria-label="Event to Register">
      <option value="">EVENT TO REGISTER</option>
    </select>
    
    <button type="submit" class="submit-button" aria-label="Submit registration"></button>
  </form>
  <p class="coordinator-info">Co-ordintor - Raviprasath</p>
</div>
```
```
# About

<style>
.about-section {
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  align-items: center;
  color: rgba(0, 0, 0, 1);
  text-align: center;
  margin: 0 auto;
  padding: 55px 44px 11px;
  font: 400 36px Italiana, sans-serif;
}

.header-image {
  aspect-ratio: 7.25;
  object-fit: contain;
  object-position: center;
  width: 100%;
  align-self: stretch;
}

.section-title {
  margin-top: 55px;
}

.event-description {
  margin-top: 85px;
  font: 48px Jersey 10, sans-serif;
}

.appreciation-message {
  margin-top: 113px;
}

.coordinator-info {
  margin-top: 46px;
  font: 24px Itim, sans-serif;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="about-section">
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/4120ad415f12493eb5df19bb381aa707/986c5a6a50bb3a6c0f8014db342461e6bf7a577e9fbf2d168bbbd444688fddf3?apiKey=4120ad415f12493eb5df19bb381aa707&"
    class="header-image"
    alt="Event header illustration"
  />
  <h1 class="section-title">ABOUT</h1>
  <p class="event-description">
    This Event will conduct
    <br />
    for 5 Days so for that
    <br />
    5 Days the OD will be
    <br />
    provided for the
    <br />
    participant's
  </p>
  <p class="appreciation-message">
    Thank You
    <br />
    for your support
  </p>
  <p class="coordinator-info">Co-ordintor - Raviprasath</p>
</div>
```
# OUTPUT:

![](<Screenshot 2025-12-19 124840.png>)
![alt text](<Screenshot 2025-12-19 124847.png>)
![alt text](<Screenshot 2025-12-19 124855.png>)
![alt text](<Screenshot 2025-12-19 124919.png>)


# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
