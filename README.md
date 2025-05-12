# Lalababu API

This is the backend API service for the HGZY Predictor project.

## Features

- Live prediction API integration
- Firebase backend
- Real-time responses
- Fully deployable

## Project Structure

- `firebase.json` - Firebase configuration
- `functions/index.js` - Main Cloud Function
- `package.json` - Project dependencies

## Deployment

This API is designed to be deployed on Firebase Functions. Make sure to configure Firebase CLI and run:

```bash
firebase deploy --only functions
