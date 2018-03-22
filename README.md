# Google Image Scrape

Google Image Scrape build using Node.js, MongoDB, and various node modules which scrape images from Fetch images from google and save top 15 images after passing through a compression algorithm then through a black and white filter and saved to a Local HDD.

Keyword List tab will display all the keywords searched by the user.

After clicking on any keyword on the Keyword List tab open up another page (dashboard ) which will have all the images for that particular keyword and now these images will be retrieve from Local HDD.

To run this project first make sure you have MongoDB running in your machine.

Next follow these steps.

Install pm2 using ' npm install pm2 -g ' & then run using ' pm2 start server.js '

Open the server at http://localhost:3000
