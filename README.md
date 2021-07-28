# nodejs-saving-data-to-json

nodejs-saving-data-to-json is Web Application to save a list of your favorite books. All data are store in a Json file.

# ScreenShoot

![GitHub Logo](docs/screenshot.png)

# Installation

```shell
git clone https://github.com/FlavioAro/nodejs-saving-data-to-json.git
npm install
npm run build
npm start
```

# Environment Variables

- `PORT`, this is the http port of the server. by default is `5000`.
- `APPID` - (optional), this is an unique ID for the application to identify in a load balancer

Also you can create a .env file with the environment variables mentioned above.

# Docker

```shell
docker build -t express-books .
```

```shell
docker run -p 80:5000 express-books .
```

then visit: `http://localhost`