# Card Status API

This is an interview exercise. The API returns a card status from a phone number or card id.

## Run

```bash
git clone https://github.com/LifeAyush/card-status-api.git
cd card-status-api
npm install
```

`package.json` installs Express, Mongoose, dotenv, EJS, and csv-parser. It has no start script. Put `MONGODB_URI` in a `.env` file, load the sample CSVs, then start the server:

```bash
node scripts/parseData.js
node src/app.js
```

The server listens on `PORT`, or 3000. Open http://localhost:3000, or call `GET /api/get_card_status?input=` with a phone number or card id.
