# 📸 Picture Organiser

## Proposal

The idea for this final year project has always been on my mind.
As a frequent user of photo and images services, I have always found it difficult to keep track of and manage
my photo collection, and the difficulty increases when I need to locate a certain image.
At my current work, pictures are essential to the production of reports. A program that could automate photo
organisation and improve image retrieval would be an invaluable asset.
As a computer science student, I am well-positioned to undertake this project. I understand the common
challenges faced by users and have insights into the potential improvements that could be made to existing
photo organization apps on the market.
Without a doubt, this project will be difficult and requires me to use a wide variety of approaches and abilities
that I have acquired throughout my time at Birkbeck. I am sure that I can apply this knowledge to my
advantage and accomplish my objective of developing an application that organises pictures in an easy-to-use
and efficient manner.

## First Steps

Clone the repository:
```
git clone --recursive https://github.com/Luiz-H-Peres/picture-organiser-app.git
```

Install the dependencies:
```
npm install
```

Run the development server:
```
npm run dev
```

## Be aware

This project is still in development and is not ready for production.
If you face any issues, please report them in the [issues](https://github.com/Luiz-H-Peres/picture-organiser/issues) section.

### Before you start
- Ensure you have the correct version of Node.js installed.
- Ensure you you have the correct credentials for the database.
- Ensure you have API url on frontend/src/api.ts


## Technical Notes

The frontend project uses [Vite](https://vitejs.dev/) as a build tool.

The backend project uses Node.js and [Express](https://expressjs.com/) as a web framework.

⚠️ Local Development Note
Important: When running the application locally, please ensure that the backend API base URL in the frontend file frontend/src/api.js is updated with your current local IP address (e.g., http://192.168.X.X:3000).
This is required because the app is not yet using environment variables or dynamic networking, and hardcoded URLs must match the machine's local IP to allow frontend-backend communication.

📍 This step ensures full functionality when accessing the app from other devices on the same Wi-Fi network, such as testing from a mobile browser or Postman.

For the database, I'm using [MongoDB](https://www.mongodb.com/) as a NoSQL database.

This project it's structured as a monorepo using [NPM Workspaces](https://docs.npmjs.com/cli/v8/using-npm/workspaces). 
Both backend  and frontend are in the same repository, but they are independent projects.
