# Bug Reports
Testing the functionality and writing Bug reports on https://www.demoblaze.com/
![demoblaze home-page Screenshot](https://github.com/GrayWing100/Bug_Reports/blob/main/pictures/Demoblaze.png)

### Environment
Please complete the following information:
- OS: macOS
- Browser: Chrome
- Version 129.0.6668.90 

### :one:  Bug ID: BR-1 / Video Playback Button Misalignment


### Priority: P4 - Low

### Description
When a user clicks on the "About Us" section, a video is displayed.  However, the play button for the video is displaced, appearing at the upper left of the screen instead of the center.

### Steps to Reproduce
1. Go to the site https://www.demoblaze.com/
2. Click on the "About Us" button in the navigation menu.
3. Observe the position of the video play button.

### Expected Behavior
The play button should be centered on the video for proper user experience.

### Actual Behavior
The play button appears at the top left corner of the screen and functions correctly when clicked.

### Screenshots
![demoblaze - Play button](https://github.com/GrayWing100/Bug_Reports/blob/main/pictures/demoblaze-playButton.png)

#


### 2️⃣:  Bug ID: BR-2 / The "Welcome User" button has no special functionality

### Priority: P4 - Low

### Description
When a user logs in on the site with a valid username and password, the "Welcome User" button/link in the upper-right corner does not perform any action, preventing access to the account settings

### Steps to Reproduce
1. Go to the site https://www.demoblaze.com/
2. Log in with correct username and password
3. Click on the "Welcome User" button in the upper-right corner.

### Expected Behavior
The user should be redirected to the account settings page.

### Actual Behavior
No action occurs when clicking the "Welcome User" button.

### Screenshots
![demoblaze - Welcome user](https://github.com/GrayWing100/Bug_Reports/blob/main/pictures/demoblaze-welcomeUser.png)

### Test data: Username: Ceao & Password: 1234

#


### 3️⃣:  Bug ID: BR-3 / Successful Purchase with Invalid Credit Card Data

### Priority: P1 - High

### Description
When a user attempts to complete a purchase using invalid credit card information (random numbers), the system processes the order successfully and displays a "Thank you for your purchase" message, which should not happen.

### Steps to Reproduce
1. Go to the site https://www.demoblaze.com/
2. Select any product and click on the "Add to cart" button.
3. Confirm that the item is added to the cart by acknowledging the pop-up message.
4. Navigate to the Cart and click Place Order.
5. Fill in the fields:
    * Name: Enter any random text.
    - Credit card: Enter random numbers (e.g., 123456789).
6. Click the Purchase button.

### Expected Behavior
The system should validate the credit card information and prevent the order from being processed with invalid data.

### Actual Behavior
The system processes the order successfully and displays a "Thank you for your purchase" message despite invalid credit card data.

### Screenshots
![demoblaze - Welcome user](https://github.com/GrayWing100/Bug_Reports/blob/main/pictures/demoblaze-creditCard.png)

### Test data: Username: Random Text & Password: Random Numbers

#


### 4️⃣ :  Bug ID: BR-4 / Contact Form Allows Submission Without Input

### Priority: P4 - Low

### Description
When a user clicks on the "Contact" button and submits the form without entering any details, the system displays a "Thanks for the message!!" notification (as seen in the attached image), instead of prompting the user that the form is incomplete.

### Steps to Reproduce
1. Go to the site https://www.demoblaze.com/
2. Click on Contact without filling out any fields in the form.
3.Click the Send message button.

### Expected Behavior
A notification should appear informing the user that the form is incomplete or empty.

### Actual Behavior
A pop-up with the message "Thanks for the message!!" is shown, even though no data was submitted.

### Screenshots
![demoblaze - Welcome user](https://github.com/GrayWing100/Bug_Reports/blob/main/pictures/demoblaze-message.png)


