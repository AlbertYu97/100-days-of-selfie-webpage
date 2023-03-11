# 100-days-of-selfie-webpage
 I built a webpage to showcase my 100 days selfie challenge

To do this, I used a client-side framework and its APIs. In particular, I used Vue.js as my client-side framework, and I leveraged the VueSilentbox API to create the image gallery that displays all my selfies.
However, in order to feed my application, I needed to create a server-side API that could reshape data from a public Web API. I decided to use the Twilio API to handle the messaging and image processing.
To create my server-side API, I used three files: index.html, api/pics, and incoming-message.
In index.html, I set up the basic structure of my webpage and included the necessary scripts and stylesheets to get my Vue.js app up and running. In the Vue.js code, I defined the loadImages() method to asynchronously retrieve my images from the server-side API.
In incoming-message, I created a Twilio Function that responds to incoming messages by sending a message back to the sender to confirm receipt of their submission.
Finally, in api/pics, I created another Twilio Function that uses the Twilio API to retrieve all the images that were submitted to my phone number. I then transformed this data into the format that the VueSilentbox API expected and returned it to my client-side application as a JSON object.
Overall, I'm really happy with how the project turned out, and I'm excited to continue my coding challenge and add more selfies to my gallery.

## Link to the webpage
https://albert-2823.twil.io/index.html
