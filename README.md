<h1 align="center">
      <img src="./github/logo.svg" alt="GoFinances" width="250">
</h1>

<h3 align="center">
 GoFinances
</h3>

<p align="center">Transaction management application, with Node.js along with TypeScript, but this time including the use of databases with TypeORM and sending files with Multer</p>

<p align="center">
  <a href="#rocket-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-use">How to use</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

<p align="center">
  <a href="https://opensource.org/licenses/MIT" >
    <img alt="License" src="https://img.shields.io/badge/license-MIT-%23F8952D">
  </a>
</p>

<div align="center">
     <img src="./github/GoFinances1.png" alt="project image dashboard" width="440">
      <img src="./github/GoFinances2.png" alt="project image upload file" width="440">
</div>

<br />
<br />

## :rocket: Technologies

<br />
This app features all the latest tools and practices in mobile development!
<br />
<br />

- [React](https://reactjs.org/)
- [React Native](https://facebook.github.io/react-native/)
- [Node JS](https://nodejs.org/en/)
- [TypeScript](https://www.typescriptlang.org/)
- [Axios](https://github.com/axios/axios)

## 📢 How to use

<br />

**📡 Backend (Node Js)**

<br />

Step 1 - Access our application's node server folder with the command: `cd server`;

Step 2 - Download the npm packages used in the project with the command: `npm install` , if you prefer yarn execute `yarn`;

Step 3 - Start the server with the command: `npm run dev`, if you prefer yarn run `yarn dev`;

- Node Server is required for both the frontend and the mobile.
- it is necessary to have a postgres database with the name `gofinances`.

<br />
<br />

**💻 Frontend (React Js)**

<br />

Step 1 - Access our application's frontend folder with the command: `cd web`;

Step 2 - Download the npm packages used in the project with the command: `npm install` , if you prefer yarn execute `yarn`;

Step 3 - Start the application with the command: `npm run start`, if you prefer yarn run `yarn start`;

<br />
<br />

**📱 Mobile (React Native)**

<br />

Step 1 - Access our application's mobile folder with the command: `yarn`;

Step 2 - Download the npm packages used in the project with the command: `npm install` , if you prefer yarn execute `yarn`;

Step 3 - Change `baseURL` in ./src/services/apiClient.ts, for the ip of your machine, this is important because the localhost would be the ip of the device or emulator and we need the ip of the server.;

Step 4 - Start the application with the command: `npm run start`, if you prefer yarn run `yarn start`;

<br />
<br />

## :memo: License

<br />
This project is licensed under the MIT License - see the details in <a href="https://opensource.org/licenses/MIT">page</a>.

---

Make with :purple_heart:
