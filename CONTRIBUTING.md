# Contributing

## Requirements
- [Node.js](https://nodejs.org/en/download/)
- [yarn](https://classic.yarnpkg.com/en/docs/install/) 

## Local Setup

- [Fork](https://github.com/saurabhdaware/no-earth-b) this Repository
```sh
git clone https://github.com/<your-username>/no-earth-b.git
cd no-earth-b
yarn
yarn dev
```
- This will run a dev-server in http://localhost:5000

### Air Quality API Env Setup

If you are working on `AirQuality.abell` file, you may want to setup environment variables for API to work.

- Get your API token from https://aqicn.org/data-platform/token/#/
- Create `.env` file in root of project.
- Add following code and replace `<Your API Token>` with your API token.

```
AQI_TOKEN=<Your API Token>
```
