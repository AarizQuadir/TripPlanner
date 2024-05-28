# TripPlanner
Welcome to TripPlanner! This is a React-based web application that helps users explore various travel destinations in India. Users can browse through different tours, learn about the destinations, and mark tours as "Not Interested."

### Features
Tour Listing: View a list of tours with details about different destinations.
Mark as Not Interested: Users can mark tours they are not interested in, which will then be removed from the list.
Refresh Tours: Refresh the list to view all tours again after marking some as not interested.
### Demo
You can view the live demo of the application here https://aarizquadir.github.io/TripPlanner/

### Screenshots
Home Page
![Screenshot 2024-05-29 020951](https://github.com/AarizQuadir/TripPlanner/assets/167294376/354f6e55-eac4-4b91-ae11-2c7404f782ea)

![Screenshot 2024-05-29 021016](https://github.com/AarizQuadir/TripPlanner/assets/167294376/bb2e91ab-8e55-4266-bae6-ff9b1541ff63)


No Tours Left

![Screenshot 2024-05-29 021033](https://github.com/AarizQuadir/TripPlanner/assets/167294376/46b537f2-cebb-4766-91f9-30ebc86af5fa)

### Getting Started
Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
Make sure you have the following installed on your local machine:

Node.js
npm (Node Package Manager)
### Installation
Clone the repository:

### bash
Copy code
git clone https://github.com/aarizquadir/TripPlanner.git
Navigate to the project directory:

### bash
Copy code
cd TripPlanner
Install dependencies:

### bash
Copy code
npm install
Running the App
To run the application locally, execute the following command:

bash
Copy code
npm start
The app will run in development mode and you can view it in the browser at http://localhost:3000.

Building the App
To build the app for production, use the following command:

bash
Copy code
npm run build
This will create a build directory with the production build of your app.

### Deploying to GitHub Pages
To deploy the application to GitHub Pages, follow these steps:

Install gh-pages package:

bash
Copy code
npm install --save gh-pages
Update package.json:
Add the following properties:

json
Copy code
"homepage": "http://<username>.github.io/TripPlanner",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}
Replace <username> with your GitHub username.

Deploy the app:

bash
Copy code
npm run deploy

### Contributing
We welcome contributions to this project. Please fork the repository and create a pull request with your changes. Make sure to follow the project's coding standards and conventions.

### License
This project is licensed under the MIT License. See the LICENSE file for details.

### Acknowledgements
Thanks to all the developers who contributed to the React ecosystem.
Images sourced from Unsplash and other free image resources.
Feel free to reach out if you have any questions or suggestions. Enjoy planning your trips with TripPlanner!
