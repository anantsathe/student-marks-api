# Student Marks API

This is a Flask-based API that returns marks for given student names.

## Usage

Make a GET request to `/api` with `name` query parameters:

https://your-app.vercel.app/api?name=John&name=Jane

Returns JSON with marks in the order of names requested.

## Deployment

Deployed on Vercel with CORS enabled for all origins.