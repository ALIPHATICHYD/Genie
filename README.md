
# GENIE 

## LINK:  https://genie-rho.vercel.app/


## Features :
- Generate text from text input and also from images (Automatically switches between the two models).
- Test your Gemini API key


## Note :

- Only Available in the selected regions. See the list of available regions here: https://ai.google.dev/available_regions
- Models that can be tested :
   - Gemini Pro
   - Gemini Pro Vision

- Response from the API is slow at times especially when using the pro-vision model. Once it is available in the UK, I will try to optimise the app for better performance.

## Description

This is a simple web app that uses the Google Gemini API to generate text from text input and text from images. Initially built for testing the gpt-4-vision model,  on the announcement of the Gemini API, the code was quickly adapted to use the Gemini API.  This app was used for internal testing of the Gemini API for the company I work for, so it was not built for public use and is not maintained. The problem with the Gemini API is that as of the Date of writing <strong> it is not possible to use the API in the UK </strong> and with a big help from my sister who lives in India, I was able to test the API.


## Tech Stack

- Typescript
- NextJS
- TailwindCSS 3.4 
- Gemini API


## RUN LOCALLY

<ul>
<li>Clone the repo</li>
<li>Install dependencies</li>
<li> Insert your API key in the .env file as shown in the .env example</li>
<li>Run the app using <code> npm run dev</code></li>
</ul>


## DEPLOYMENT

The app is deployed on Vercel and can be accessed here: https://genie-rho.vercel.app/


## DOCS USED FOR DEVELOPMENT : 

See Learn. md for the docs used for development



## Screenshots

![Working ](<SCREENSHOTS/Screenshot 2023-12-25 at 8.11.37 PM.png>)

![Working](<SCREENSHOTS/Screenshot 2023-12-25 at 9.31.21 PM.png>) 



