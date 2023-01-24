# Backend for Kiosk Klick
#### 23/01/2023
#### By Joanna Oluoch


## Project Description
This project is the backend component of my Moringa School Phase 2 Project: Kiosk Klick.

Kiosk Klick is an e-commerce application that allows users to browse local kiosks from the comfort of home. The backend component contains data for each kiosk and its inventory, and the cart.

- The frontend component is found here: [Kiosk Klick Frontend](https://github.com/astronaut-nemo/kiosk-klick-frontend).
- The deployed application is hosted here: {URL coming soon}

- This server uses the json-server-template: [https://github.com/learn-co-curriculum/json-server-template](https://github.com/learn-co-curriculum/json-server-template)

## Setup/Installation Requirements (for local development)
1. Download the zip file under the 'Code' tab.
2. Extract files from the zip file.
3. Open the extracted folder with VS Code.
4. In your VS Code terminal to install the required dependancies (this is only done ONCE), run:
```sh
npm install
```

5. Still in the VS Code terminal to expose the local server on http://localhost:8000, run:
```sh
npm start
```
6. In case `npm start` does not work, directly access the `db.json` by running :
```sh
json-server --watch ./db/db.json --port 8000
``` 
7. And then, you are good to go.

## Requirements
 The project requires Json Server.

## Important Commands
### 1. Running the Server in Development Mode
To run the server in development mode (the server will re-load anytime a change is made to `db.json`), run: 
```sh
npm run dev
```

To simply run the server, run:
```sh
npm start
```

### 2. Resetting/Seeding the Data
To copy data from the `./db/seeds.json` file to the `./db/db.json` file, run:
```sh
npm run seed
```
This will reset the database back to the original data.

## Technologies Used:
- React Server

## Support/Contact Details
- joannaoluoch@gmail.com
- (+254) 0707134998

## License
Licenced under the **MIT-license**.

See the [LICENSE](LICENSE.md) file for license rights and limitations (MIT).
