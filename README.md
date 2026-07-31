#Hi I'm Clark 👋

I am a Real investing estate analyst teaching myself to build. Interested in forecasting, experimentation, and data products that reach real users.

Currently building **[BikePredict](https://bikepredict.fyi)** — a machine learning system that predicts Citi Bike availability across ~2,400 NYC stations, 1 hour to multiple days ahead. Live GBFS data, weather forecasts, and MTA subway data feed 18 production models across 6 horizons. The app is live, a Meta ad campaign is running, and signups are tracked end-to-end via Pixel.

## What I Work On

- **Forecasting & ML** — scikit-learn, time series, feature engineering at scale
- **Experimentation** — A/B tests, hypothesis testing, effect sizes over p-values
- **Data pipelines** — ingestion, feature building, hourly model scoring
- **Full-stack** — Next.js, Vercel, Snowflake,BigQuery, PostgreSQL/TimescaleDB

## Stack

`Python` `pandas` `scikit-learn` `SHAP` `Optuna` `PostgreSQL` `TimescaleDB` `Snowflake` `Next.js` `TypeScript` `Mapbox GL` `deck.gl` `Vercel` `Tableau`

## Projects

### [BikePredict — Citi Bike Availability Forecasting](https://github.com/cprenz/citibike_availability_predictions)

An end-to-end machine learning system that forecasts bike availability at ~2,400 NYC Citi Bike stations, from 1 hour to multiple days ahead. Built a live ingestion pipeline polling the GBFS API every 2.5 minutes, engineered 75+ features (observed vs. forecast weather, MTA subway proximity via BallTree, demand climatology, cyclical time encodings), and trained 18 production models across 6 horizons on 161M+ rows. Results are scored hourly, pushed to Snowflake, and served through a Next.js web app at [bikepredict.fyi](https://bikepredict.fyi). Includes 7 hypothesis tests with paired/Welch t-tests (effect sizes and confidence intervals), a Tableau Public analytics dashboard, and a live Meta ad campaign with Pixel-based conversion tracking.

## Get in Touch

clark.prenz@gmail.com · [bikepredict.fyi](https://bikepredict.fyi)
