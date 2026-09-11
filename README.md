# [Maquette]

This repository contains the implementation accompanying our submission. 
The system supports generative, provisional proposals for physical collage 
making, allowing users to explore AI-generated visual suggestions during 
an in-progress physical collage session.

## Structure

- `/public/index.html` — frontend interface
- `/worker` — backend service handling image generation requests
- `server.js` — local development server

## Setup

1. Install dependencies:

npm install


2. Create a `.env` file with the following variables (values omitted for anonymity):

OPENAI_API_KEY=
R2_BUCKET_NAME=
R2_ACCOUNT_ID=


3. Run locally:

npm run dev


## Notes

This code is provided for double-blind review purposes. Identifying 
information has been redacted in accordance with the venue's anonymity 
policy.
